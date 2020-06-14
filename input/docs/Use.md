Description: How to integrate and use the libraries in your project
---
Due to the early development stage of the project there is no nuget available. The libraries target .NET Core 3.1. A stable release is not planned before .NET 5, to allow the API to mature.

The buildpipline is ready but to get this out into the public it needs more testing on different linux distributions. Currently it is tested on Fedora 32. If you are willing to contribute head over to: https://github.com/gircore/gir.core/

Until the nuget is available you could just build the code locally. To get started just checkout the code and build the project:

    $ git clone https://github.com/gircore/gir.core.git
    $ cd Build
    $ dotnet run -- release build

You can reference the project you want to use like this.

    $ dotnet add reference [RepoPath]/Libs/Gtk/Core/Gtk.Core.csproj

The repository contains an example app, which demonstrates some of the available UI controls. Feel free to take a look and explore: [Example App](https://github.com/gircore/gir.core/tree/develop/GtkApp)