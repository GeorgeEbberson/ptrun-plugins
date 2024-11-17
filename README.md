Plugins for PowerToys Run
=========================
A bunch of plugins for PowerToys Run.

They are:
* [`Define`](Community.PowerToys.Run.Plugin.Define/ABOUT.md), for getting the definition of words

The `libs` folder
-----------------
This is where we store the PowerToys DLLs to compile against. Currently we expect to find five DLLs,
all of which can be found in `C:\Program Files\PowerToys` on Windows:
* `PowerToys.Common.UI.dll`
* `PowerToys.ManagedCommon.dll`
* `PowerToys.Settings.UI.Lib.dll`
* `Wox.Infrastructure.dll`
* `Wox.Plugin.dll`

When compiling for a new PowerToys version, these will all need updating.

Setup
-----
* You'll need a .NET 8.0 toolchain installed

References
----------
Sites which I've used whilst doing this:
* [Henrik Lau Eriksson's blog][eriksson-blog] on this was my main inspiration and much of the initial code came from their examples
* Eriksson also wrote a [linting tool][ptrun-lint] which I haven't tried yet but which seems very promising
* The [Everything for PowerToys][everything-powertoys] plugin is a great example

[eriksson-blog]: https://conductofcode.io/post/creating-custom-powertoys-run-plugins/
[ptrun-lint]: https://github.com/hlaueriksson/Community.PowerToys.Run.Plugin.Lint
[everything-powertoys]: https://github.com/lin-ycv/EverythingPowerToys
