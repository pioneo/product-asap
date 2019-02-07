
# ASaP-IDE

The ASaP-IDE is an Eclipse-based full-featured Integrated Development Environment (IDE) for developing generic Smart Services based on the [Agent-based Smart Service Platform (ASaP)](https://publikationen.sulb.uni-saarland.de/handle/20.500.11880/25477). 

## Requirements
 * Java 8 or newer (Note that a full JDK needs to be installed, not just a JRE).
 * The current version of the ASaP-IDE is based on an 64-bit Eclipse, so it's recommended to install a 64-bit JDK.

## Installation

First, download the ASaP-IDE via one of the following links: 

 * [ASaP-IDE for Windows](https://github.com/pioneo/product-asap/releases/download/v1.0.2/win.zip)
 * [ASaP-IDE Mac](https://github.com/pioneo/product-asap/releases/download/v1.0.2/asap.dmg)
 
### Installation on Windows

The download will be delivered as compressed file (.zip). Decompress this file into the directory of your choice (e.g. "c:\asap" on Windows) and ensure you have full Read and Execute permissions. You can optionally create a shortcut of the executable file ("asap.exe" on Windows, or "asap" on Mac).

The relevant project structure of the decompressed file should look as follows: 

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

Note that there is a known problem with the built-in decompression utility on all current versions of Windows. We recommend that you use a more robust decompression utility such as the open source [7zip](https://www.7-zip.org) when decompressing an Eclipse download. Some people report success when initially decompressing and Eclipse-based application into a root directory (e.g. c:\) and then moving it to a more appropriate home (e.g. c:\Program Files\ASaP). 

For more information on basic Eclipse installation issues, visit [Eclipsepedia - the Eclipse.org Wik](https://wiki.eclipse.org/Eclipse/Installation). 

## Usage



## Troubleshooting


