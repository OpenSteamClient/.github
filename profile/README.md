## OpenSteamClient
OpenSteamClient is a collection of open-source libraries and various tidbits to interface with Steam.

## End users
OpenSteamClient is not yet ready for general use. There's a TODO list available at the various repos, but most end users are probably interested in the GUI, which is being developed [here](https://github.com/OpenSteamClient/OpenSteamClient).
Currently a rewrite is ongoing.

## Support libraries
Steam only officially provides 32-bit client libraries on Windows and linux. Dotnet is only available as 64-bit. Luckily, there is a 64-bit library also available, but it's only meant primarily for games, but it also works fine for client use.
Most of their dependencies are only available as 32-bit. To compensate for this we have various 64-bit support libraries that we try to match to thir dependencies as closely as possible.

## Contribution guidelines
Currently development is in a early stage and nothing is set in stone.
Please hold contributions until major architectural changes and plans have been finalized. If you wish to be notified about this, open an issue in the corresponding repo and I'll handle it.
Our libraries currently have no API stability guarantees, and they are developed in lock-step with OpenSteamClient/ClientUI, the main GUI app. 


## Repos and their uses
| Repository  | Purpose | Language |
| ------------- | ------------- | - |
| [OpenSteamClient](https://github.com/OpenSteamClient/OpenSteamClient) | (Currently being remade, C++ version is pretty terrible right now) An open-source GUI frontend for Steam, powered by Qt | C++ |
| [OpenSteamworks](https://github.com/OpenSteamClient/OpenSteamworks) | Library to interface with Steam's client API's | C# |
| [OpenSteamworks.Client](https://github.com/OpenSteamClient/OpenSteamworks.Client) | Library to build your own frontend for Steam | C#, C++ |
| [OpenSteamworks.Native](https://github.com/OpenSteamClient/OpenSteamworks.Native) | Native support libraries (fakeservice, protobufhack) | C#, C++ |
| [SDL](https://github.com/OpenSteamClient/SDL) | 64-bit SDL support library | C |
| [SDL_ttf](https://github.com/OpenSteamClient/SDL_ttf) | Support for SDL to load .ttf files | C |
| [Tools](https://github.com/OpenSteamClient/Tools) | Tools to help with automatable maintenance tasks | Javascript, Typescript, C++ |

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
