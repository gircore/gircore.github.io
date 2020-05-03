Description: General information
---
Currently there are multiple libraries supported to integrate deeply into linux.
## GTK
[Gtk] is the toolkit which is used to display windows and widgets on the screen. The widgets can be added directly in code or described through an xml file.

Supported widgets are for example: Windows, dialogs, lables, images, spinner, progressbars, several buttons and switches, textboxes, tables,  lists, menus, toolbars, popovers, and much more. It powers several linux desktops like [Gnome] and [Xfce] and applications like [Gimp].

![A picture of an example gtk application][GtkApp]

## WebkitGTK
[WebkitGTK] is a browser component for GTK and can be used to embed the webkit webengine into an application as a widget. There is support for the web inspector and several settings to tweak the webview to your needs.

The bindings make it easy to:
* Embed javascript into a webpage
* Call a javascript function
* Callback from the webpage into the C# code.

![A picture of an example gtk application with visible webpage][GtkAppBrowser]

## Libchamplain
[Libcchamplain] is map component for GTK and can be used to embed maps into an application widget. By default it uses openstreetmap.

![A picture of an example gtk application with visible openstreetmap][GtkAppMaps]

## libhandy
[libhandy] extends GTK with new widgets, to support mobile devices. Meaning full blown applications automatically adopt their UI to different view modes,if the available space changes.

One widget of this library is the *Paginator* which is shown in the pictures above. It allows to swipe through widgets and is used to switch between the webpage and maps control.

[libhandy]: https://source.puri.sm/Librem5/libhandy
[Libchamplain]: https://wiki.gnome.org/Projects/libchamplain
[WebkitGTK]: https://webkitgtk.org/
[Gtk]: https://gtk.org
[Gimp]: https://gimp.org
[Gnome]: https://gnome.org
[Xfce]: https://xfce.org

[GtkApp]: GtkApp.png "Example GtkApp"
[GtkAppBrowser]: GtkAppBrowser.png "Example GtkApp with Browser"
[GtkAppMaps]: GtkAppMaps.png "Example GtkApp with Maps"