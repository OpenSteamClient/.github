## OpenSteamClient
OpenSteamClient is a collection of open-source libraries and various tidbits to interface with Steam.

## End users
OpenSteamClient is not yet ready for general use. There's a TODO list available at the various repos, but most end users are probably interested in the GUI, which is being developed [here](https://github.com/OpenSteamClient/OpenSteamClient).
Currently a rewrite is ongoing, and it's not recommended to use right now.

## Support libraries
Steam only officially provides 32-bit client libraries on Windows and linux. Dotnet is only available as 64-bit. Luckily, there is a 64-bit library also available, but it's only meant primarily for games, but it also works fine for client use.
Most of their dependencies are only available as 32-bit. To compensate for this we have various 64-bit support libraries that we try to match to thir dependencies as closely as possible.

## Contribution guidelines
Currently development is in a early stage and nothing is set in stone.
Please hold contributions until major architectural changes and plans have been finalized. If you wish to be notified about this, open an issue in the corresponding repo and I'll handle it.
Our libraries currently have no API stability guarantees, and they are developed in lock-step with OpenSteamClient, the main GUI app. 


## Repos and their uses
| Repository  | Purpose | Language |
| ------------- | ------------- | - |
| [OpenSteamClient](https://github.com/OpenSteamClient/OpenSteamClient) | (Being rewritten in C#/Avalonia) An open-source GUI frontend for Steam, powered by Qt | C++ |
| [OpenSteamworks.Native](https://github.com/OpenSteamClient/OpenSteamworks.Native) | Native support libraries (fakeservice, protobufhack) | C#, C++ |
| [OpenSteamworks.Utils](https://github.com/OpenSteamClient/OpenSteamworks.Utils) | Misc OpenSteamworks utils | C# |
| [OpenSteamworks.Protobuf](https://github.com/OpenSteamClient/OpenSteamworks.Protobuf) | Auto-generated Steam Client Protobuf | C# |
| [OpenSteamworks.KeyValue](https://github.com/OpenSteamClient/OpenSteamworks.KeyValue) | OpenSteamClient's home-grown KeyValue library | C# |
| [archived_packages](https://github.com/OpenSteamClient/archived_packages) | Old Steam Client package utility | JS |

<!--
| [OpenSteamworks](https://github.com/OpenSteamClient/OpenSteamworks) | Library to interface with Steam's client API's | C# |
| [OpenSteamworks.Client](https://github.com/OpenSteamClient/OpenSteamworks.Client) | Library to build your own frontend for Steam | C#, C++ |
| [OpenSteamClient.Overlay](https://github.com/OpenSteamClient/OpenSteamClient.Overlay) | OpenSteamClient's custom Overlay (currently private) | C++, ImGui |
-->
