# Computercraft Core API
The Core API runs off the Computercraft operating system, which allows users to enjoy a better computercraft expirience, and to make a better development environment for everyone. We also look forward to creating a UI operating system with entire graphical elements. Computercraft is quick and easy to set up very simple contraptions, but it is rather difficult to set up big projects for redstone, or a base with security all over. The possibilities are endless.

The Core API is made for a wide veriety of things, including heavy screen rendering, to CO-OP Turtle building via mobile computing (handheld). The Core API is a great way for many possibilities that where passed up due to the huge work beind them. Core will have many objectives. All objectives are located below for convinience.

## Installation
Setting up a copy is very simple for Consumer use. Simply use the following command on any computer terminal. NOTE: This requires network access with HTTPS
#### pastebin run DzJ0faVz
This will start the remote installer process. You can use an Emulator if you wish, but it works well ingame also. When the installer starts, you will need to press enter. This will install the startup file, and reboot. The startup file will then install the software and reboot.

## Development
If you wish to help contribute to this project, you will need to set up your workspace. This repository includes the project, with the emulator binaries. It is pretty simple to get going, just follow the steps below.
* Download a copy from either github or the client application and open the main directory.
* Run start.bat. This file simply starts the emulator workspace.
  * Click "Start Session", then Select the workspace "main", then Click "Load Selected"
  * This will launch three computers with ids and names
    * 0: Main. This will launch the main development computer for development. Releases are pulled from this computer
    * 1: Debugger. This will launch and display all logs from computer 0: Main via a simulated modem network
    * 2: User. This will launch the os and show the user expirience. 
* You are good to go! Simply use the project folder indicated below for the source

#### Source /src/sessions/main/computer/0

## Objectives
Since there are a lot of objectives, its slightly difficult to show all of them in a huge list. We have separated them into ideas or files that serve a similar purpose.

## Use Conceptual Ideas
We want a broad range of possibilities. Here, we will list a bunch of specific actions or contraptions made possible by the Core API. This will also have references to the apis if they can be done.
- [x] Multiple Cursors in the terminal all writing with different colors at the same time.
- [x] Rendering multiple shapes to a screen, and rastering them with virtual layers.
- [x] Filesystem with options and functions not avalible by Computercraft fs. Such as auto closing open files at shutdown
- [x] An API Loader that can load all apis sequentially ordered by the APIs themselves with the requireAPI() function
- [ ] CO-OP Turtle construction with mobile computer controller and monitor. The host computer would host it
- [ ] Mobile touch screen interfacing for the mobile computers.
- [ ] Networking for streaming data via LAN (virtual)
- [ ] Automatic update checking and syncing with the release folder.
