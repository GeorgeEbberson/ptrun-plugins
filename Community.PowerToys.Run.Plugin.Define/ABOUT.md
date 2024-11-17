Define plugin for PowerToys Run
===============================
For suggesting the definitions of words quickly and easily.

Building
--------
From the plugin you want to compile's directory:
```
dotnet build -c Release
```
Then copy the following five files:
* `Images\define.dark.png`
* `Images\define.light.png`
* `Community.PowerToys.Run.Plugin.Define.deps.json`
* `Community.PowerToys.Run.Plugin.Define.dll`
* `plugin.json`

from `bin\Release` to `%localappdata%\Microsoft\PowerToys\PowerToys Run\Plugins\Define`
