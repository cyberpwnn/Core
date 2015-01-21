# Core
A Computercraft API in which many different things can be accomplished with. Simple things like loading APIs in an order by calling "RequireAPI" or bigger things like making an interactive operating system with actual graphical menus and widows. It all can be done!

## Objectives
There are many objectives in this project. The issue is trying to address all of them and actually get some done.
### CPI
- [x] A way for libraries to plug in to other libraries in a safe way.
- [x] A logging system for any debugging needed which sends data remotley through a modem.

### Renderer
- [x] An entire rendering system with objective hooks which allow other apis and programs to manipulate geometrical shapes all from one object.
- [ ] The ability to move, scale, and change values of each object also.

## Setting Up a Copy
Setting up a copy of the project is rather simple. Just git a copy (fork if you want), and simply execute the start.bat in the main directory. This will Launch the computercraft emulator. The emulator has a session already loaded with the core api project loaded on it. Here is a full set of instructions below.
* Download a copy and open the main folder
* Execute the start.bat file, located in the root directory
  * This will launch the Computercraft Emulater with the project on it
  * Click "Start Session", Select "main", and Click "Load Selected"
  * This should show two windows. The first (Marked with main, and the id 0) contains the core apis in it, while The second window simply echoes any debug messages it receives from the main console window. This is for issues when the renderer is misbehaving or when the screen is being used for something else at the time.
  * Using the Restart and terminate controls on both of them, you will begin to notice that only restarting the main console is needed.
* All of the source files are located withing the session at \src\sessions\main\computer\0
