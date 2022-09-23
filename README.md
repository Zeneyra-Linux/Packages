# Packages
Repository for Package Management of Zeneyra Linux

**NOTE: This isn't the server repository that stores all the built packages for Kagero, but is the repository to manage and discuss about the packages that will go into the official Orochi repositories for Kagero!**

## Orochi Repositories
Similar how Arch Linux has core, extra, community and multilib as its Pacman repositories, Zeneyra Linux has multiple repositories to sort all the packages and also allow other software or distros that use libkagero or Kagero to directly use Zeneyra's repositories.  
All repositories feature a `-nightly` Shuriken to install the nightly version of a package if needed (pre-compiled if possible), as well as a `-git` package to self-compile the application, given it's open-source.  
| Name                | UUID | URL | Description                                                                                                              |
| ------------------- | ---- | --- | ------------------------------------------------------------------------------------------------------------------------ |
| [Zeneyra](zeneyra/) | N/A  | N/A | Cross-platform repository to distribute Zeneyra software. Includes system-critical packages.                             |
| [Linux](linux/)     | N/A  | N/A | Non-Zeneyra software that is essential to install and maintain a working Linux installation, in this case Zeneyra Linux. |
| [GNU](gnu/)         | N/A  | N/A | Software of the GNU project or GNU-related ones.                                                                         |
| [Server](server/)   | N/A  | N/A | Software like Nginx, Apache, etc. to configure and run a webserver, VPS and alike.                                       |
| [Desktop](desktop/) | N/A  | N/A | Repository for GUI applications and Desktop Environemnts/Window Managers.                                                |
| [Development](dev)  | N/A  | N/A | Collection of toolchains, compilers, runtimes and in general programming languages and IDEs for software development.    |
| [Utilities](utils/) | N/A  | N/A | General utilities that don't belong to the other repositories.                                                           |
| [FOSS](foss/)       | N/A  | N/A | Free Open Source Software that doesn't really fit into the other repositories and is mostly community-made.              |


## Package Sources
If possible, packages and its contents should be built on an installation of Zeneyra Linux, but they can also be built with pre-compiled binaries. If the package includes only non-compiled contents, then it doesn't really matter anyway - they could also be made on Windows.  
The package descriptors should include everything neccesary to make a package, e.g. type, id, content structure and source, etc. This point will definitely change in the future as a Package Builder for Orochi isn't finished yet.