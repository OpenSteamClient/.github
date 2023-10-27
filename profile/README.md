## OpenSteamClient
OpenSteamClient is a collection of open-source libraries and various tidbits to interface with Steam.

## End users
OpenSteamClient is not yet ready for general use. There's a TODO list available at the various repos, but most end users are probably interested in the GUI, which is being developed [here](https://github.com/OpenSteamClient/OpenSteamClient).
Currently a rewrite is ongoing.

## Support libraries
Steam only officially provides 32-bit client libraries on Windows and linux. 
To compensate for this we have various 64-bit support libraries that we try to match to the official ones as closely as possible.

## Contribution guidelines
Currently development is in a early stage and nothing is set in stone.
Please hold contributions until major architectural changes and plans have been finalized. If you wish to be notified about this, open an issue in the corresponding repo and I'll handle it.
Our libraries currently have no API stability guarantees, and they are developed in lock-step with OpenSteamClient, the main GUI app. 


## Repos and their uses
| Repository  | Purpose | Language |
| ------------- | ------------- | - |
| [OpenSteamClient](https://github.com/OpenSteamClient/OpenSteamClient) | An open-source GUI frontend for Steam, powered by Avalonia | C# |
| [OpenSteamworks](https://github.com/OpenSteamClient/OpenSteamworks) | Library to interface with Steam's client API's | C# |
| [OpenSteamworks.Client](https://github.com/OpenSteamClient/OpenSteamworks.Client) | Library to build your own frontend for Steam | C#, C++ |
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
