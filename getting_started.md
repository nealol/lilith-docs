# Getting Started

## Download
Downloads can be found at https://dl.lilithmod.xyz. Once you've downloaded, you can proceed to the section for your operating system: 

- [Windows Users](#windows-users)
- [MacOS Users](#macos-users)
- [Linux users](#linux-users)

## Windows Users

All you need to do is download the newest exe from the link above, put it in a new "lilith" folder, and double click to run it.

Lilith will give you a link to open. To copy it, just select the link, and it'll be copied. Paste this into your browser and verify with Discord oauth. Once this is complete, Lilith should start up.

To use Lilith, you need to go into your Minecraft client (any client works) and direct connect to `localhost`. If you have any errors, see Troubleshooting.

### Power Users on Windows

I recommend using Windows Terminal with Powershell 7 and acrylic enabled to run Lilith. Once you've installed all of the above and google how to turn on acrylic mode, you can run Lilith by navigating to the directory: `cd "PATH"` (Replace PATH with the full path to the Lilith folder), and doing `.\lilith-win-0-3-1-beta.exe`. The final command is tab-completable.

## MacOS Users

After downloading the latest Lilith version for MacOS, put it in a folder by itself, and [copy the path to that folder](https://themacbeginner.com/copy-full-path-file-folder-finder-mac-osx/).

Open a new Terminal window and type `cd "PATH"` and replace PATH with the path to the folder you copied in the previous step. Press enter to change your current directory. You now need to make Lilith executable by typing `chmod +x ./lilith-m` and then pressing tab followed by enter. You'll now be able to run Lilith by typing `./lilith-m`, pressing tab, and then pressing enter.

### Creating a .command file

For an easier way to launch Lilith, you need to create a file in the Lilith folder called `lilith.command`. The naming of this file will be important for auto-update when it's introduced.

Open the file with something like TextEdit and paste the following (You can hover to copy):
```bash
#!/bin/bash
cd "PATH"
./lilith-macos-0-3-1-beta
```

Once again, replace `PATH` with the path to the Lilith folder. Save the file and you'll now need to go into terminal, navigate to the Lilith folder as shown in the preceding section, and do `chmod +x ./lilith.command`. Now you can double click on the .command file in Finder to open a new Terminal window and run Lilith.

### Step by Step Recap

- Download Lilith for Mac
- Create a new folder for Lilith and move the downloaded file inside of it
- Open a terminal and navigate to the Lilith folder
- Run `chmod +x ./lilith-macos-0-3-1-beta`
- Create a file named `lilith.command` in the Lilith folder
- Paste the following into the file and replace PATH with the path to the Lilith folder:
```bash
#!/bin/bash
cd "PATH"
./lilith-macos-0-3-1-beta
```
- In terminal, run `chmod +x lilith.command`
- Run Lilith by double clicking the command file in Finder.

## Linux Users

I'm not going to pretend you don't know how to use the terminal; you're on Linux.

Lilith is a command line executable which you should put in its own folder such as `~/lilith`. Remember to run `chmod +x` on the executable.

### Alpine Users

I don't care enough to test Lilith for Alpine but it may work. If you try it, please let me know if it works.