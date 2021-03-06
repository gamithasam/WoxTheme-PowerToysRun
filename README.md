# [PowerToys Run](https://github.com/microsoft/PowerToys/wiki/PowerToys-Run-Overview) theme for [Wox](https://github.com/Wox-launcher/Wox)

A theme for Wox inspired by Microsoft's [PowerToys Run](https://github.com/microsoft/PowerToys/wiki/PowerToys-Run-Overview) tool.

### Light Theme
![](https://github.com/gamithasam/WoxTheme-PowerToysRun/blob/main/sample-light.png?raw=true)

### Dark Theme
![](https://github.com/gamithasam/WoxTheme-PowerToysRun/blob/main/sample-dark.png?raw=true)

## Instructions

Simply copy the `PowerToysDark.xaml` theme file or `PowerToysLight.xaml` theme file to your Wox's `Themes` directory.

After you switch back to another theme, Wox should be restarted in order to acquire the default dimensions.

## Remarks

Wox's theme [fixes the result height to 50px](https://github.com/Wox-launcher/Wox/blob/324dc8e4cfad3a47c88bbac3fc526d6fec0dbfad/Wox/ResultListBox.xaml#L23) so I couldn't match PowerToys' design perfectly.

PowerToys Run itself seems to be based on Wox with some heavy modifications.

This theme is based on this [theme](https://github.com/gamithasam/WoxTheme-FluentDark) which was based on [this light theme](https://github.com/gunt3001/WoxTheme-FluentLight). The main difference between those two and this theme is the dimensions of the textbox. The textbox of this theme is identical to Microsoft PowerToys Run except for the placeholder `Start Typing...` which is absent in this theme.

## License
MIT License © gamithasam
