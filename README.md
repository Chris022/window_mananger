# window_mananger

## How to install a Window-Manager in debian with GNOME
* Put the programm in the bin folder
* In the dir: "/usr/share/xsessions" create a new File and paste in the following code.

```
[Desktop Entry]
Name=<name>
Comment=<your comment>
Exec=<nameOfProgram>
Icon=<image>.png
Type=XSession
```