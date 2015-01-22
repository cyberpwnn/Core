# Core
A Computercraft API in which many different things can be accomplished with. Simple things like loading APIs in an order by calling "RequireAPI" or bigger things like making an interactive operating system with actual graphical menus and widows. It all can be done!

## Setting Up a Copy
Setting up a copy of the project is rather simple. Just git a copy (fork if you want), and simply execute the start.bat in the main directory. This will Launch the computercraft emulator. The emulator has a session already loaded with the core api project loaded on it. Here is a full set of instructions below.
* Download a copy and open the main folder
* Execute the start.bat file, located in the root directory
  * This will launch the Computercraft Emulater with the project on it
  * Click "Start Session", Select "main", and Click "Load Selected"
  * This should show two windows. The first (Marked with main, and the id 0) contains the core apis in it, while The second window simply echoes any debug messages it receives from the main console window. This is for issues when the renderer is misbehaving or when the screen is being used for something else at the time.
  * Using the Restart and terminate controls on both of them, you will begin to notice that only restarting the main console is needed.
* All of the source files are located withing the session at \src\sessions\main\computer\0
* It's highly recommended to use an external text editor. With all of the files, and the lengths of them.

## Objectives
There are many objectives in this project. The issue is trying to address all of them and actually get some done.
### CPI
- [x] A way for libraries to plug in to other libraries in a safe way.
- [x] A logging system for any debugging needed which sends data remotley through a modem.
- [x] Create an event system for executing code when the core system does some tasks.
  - [x] Starting up
  - [x] Shutting down
  - [x] A crash, with the errors returned
  - [ ] Calls onstop before oncrash for any libraries to close first.
- [ ] A configuration file for loading external apis, and debugging information prefered to be loaded after a startup for objective purposes

### Filesystem
- [x] A way for libraries to plug in for file creation
- [ ] Ability to create files with ease, better tools and more.
- [x] Hooks into the event system.
  - [x] Force Closes unclosed files on stop

### Event
- [x] A new way to create, call, and pull events from many things. An objective take at it
- [x] Add the ability to create events, call them, and pull them
  - [x] Ability to schedule a function for execution on call
  - [ ] Ability to wait for a call, then continue (Waiting for thread api)

### Renderer
- [x] An entire rendering system with objective hooks which allow other apis and programs to manipulate geometrical shapes all from one object.
- [x] Handling text strings longer then 1 accordingly
- [ ] The ability to move, scale, and change values of each object also.
- [ ] Different shapes for different objectives
  - [x] Boxes, for making boxes.
  - [ ] Lines (point a to point b)
  - [ ] Polygons (point a to point b to point c to ...)
  - [ ] Circles
  - [ ] Triangles and quads
- [ ] Hooks into the event system.

### UI
- [ ] A functional windowing system with buttons, events and other UI components
  - [ ] Windowing, with working operation buttons
  - [ ] Buttons with actions and click listeners
  - [ ] Text fields with text options
  - [ ] Scroll views which can have text feilds
- [ ] Hooks into the event system.

### Configurator
- [ ] A way for libraries to plug in and make config files for reading. Stored in the /config folder
  - [ ] Adding, deleting, and modifying keys/values
  - [ ] Reloading configs, and getting all of the data for reduction in disk activity
  - [ ] Autocache for returning the same value, an update option to reload it
- [ ] Hooks into the event system.

### Thread
- [ ] The ability to create, run, and stop threads for simultaneous actions
- [ ] Thread managment and pulling for control.
  - [ ] Thread lock detection
  - [ ] Thread killing and other handles
- [ ] Hooks into the event system.
