
# ASaP-IDE

The ASaP-IDE is an Eclipse-based full-featured Integrated Development Environment (IDE) for developing generic Smart Services based on the [Agent-based Smart Service Platform (ASaP)](https://publikationen.sulb.uni-saarland.de/handle/20.500.11880/25477). 

## Requirements
 * Java 8 or newer (Note that a full JDK needs to be installed, not just a JRE).
 * The current version of the ASaP-IDE is based on an 64-bit Eclipse, so it's recommended to install a 64-bit JDK.
 * Your cloud login to your personal ASaP-Cloud.

## Installation

First, download the ASaP-IDE via one of the following links: 

**Latest (Version 1.0.2)**
 * Windows [64-bit](https://github.com/pioneo/product-asap/releases/download/v1.0.2/win.zip)
 * Mac [64-bit](https://github.com/pioneo/product-asap/releases/download/v1.0.2/asap.dmg)
 
### Installation on Windows

The download will be delivered as compressed file (.zip). Decompress this file into the directory of your choice (e.g. "c:\asap" on Windows) and ensure you have full Read and Execute permissions. You can optionally create a shortcut of the executable file ("asap.exe" on Windows, or "asap" on Mac).

The relevant file structure inside the decompressed folder should look as follows: 

```
win
│
└───repository
│   
└───eclipse
│   │   asap.exe
│   │   ...
│
└───config
    │   Local ASaP Application.launch
```

* "asap.exe": The windows exeutable file to start the ASaP-IDE
* "Local ASaP Application.launch": A minimal launch configuration to test the developed services in a local ASaP Application within the ASaP-IDE. 

Note that there is a known problem with the built-in decompression utility on all current versions of Windows. We recommend that you use a more robust decompression utility such as the open source [7zip](https://www.7-zip.org) when decompressing an Eclipse download. Some people report success when initially decompressing and Eclipse-based application into a root directory (e.g. c:\) and then moving it to a more appropriate home (e.g. c:\Program Files\ASaP). 

For more information on basic Eclipse installation issues, visit [Eclipsepedia - the Eclipse.org Wik](https://wiki.eclipse.org/Eclipse/Installation). 

### Installation on Mac

The download will be delivered as a disk image file (.dmg). Double click the disk image to make its content availabe. Drag the contained application (.app) into destination folder (e.g. /Applications). 

To show the content of the installed application file (.app), Control-click on the file and chooose "Show Package Contents". 
The relevant file structure should look as follows: 

```
content
│
└───config
│    │   Local ASaP Application.launch
│
└───eclipse
│   
│   Info.plist
│
└───MacOS
│
└───repository
│
└───Resources
```

* "Local ASaP Application.launch": A minimal launch configuration to test the developed services in a local ASaP Application within the ASaP-IDE. 


## Quick Start

To start the ASaP-IDE double click the executable file "asap.exe" for Windows or the application bundle "Asap.app" on Mac. 

When the ASaP-IDE is launched, the first thing you see is a dialog that allows you to select where the workspace will be located. The workspace is the directory where your work will be stored. This workspace directory is used as the default content area for your projects as well as for holding any required metadata. 

![Selecting Workspace](/screenshots/selectWorkspace.png)

After the workspace selection, you will be prompted with a login dialog to your personal ASaP-Cloud. This login is required to use the ASaP-IDE. In case you haven't any cloud login data, feel free to [contact](mailto:info@pioneo.de) us. 

![Selecting Perspective](/screenshots/selectPerspective.png)

![Loaded ASaP-IDE](/screenshots/readyToGo.png)

![Creating new Agent Service Project](/screenshots/newProject.png)


## Troubleshooting


