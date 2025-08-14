# Catppuccin Unity7 DE Port

> [!NOTE]
> I only added support for the standard Mocha theme. Feel free to make a pull request for the other ones.

This just allows the catppuccin gtk theme to work with Unity7.

## Installation

Copy the `unity` folder into the catppuccin gtk theme ([download here](https://github.com/catppuccin/gtk)). That's it.

For some reason, the **Unity Tweak Tool** won't show Catppuccin in the themes section,
so you can just run this command to set the theme:

```
$ gsettings set org.gnome.desktop.interface gtk-theme "catppuccin-mocha-mauve-standard+default"
```

## Credits

The original versions of the title bar buttons came from the Yaru Theme, since I couldn't find an easy way to use the gtk ones
(and also out of lazyness).
