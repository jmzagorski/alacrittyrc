# Alacritty config
> My [Alacritty](https://alacritty.org/index.html) config

This repository contains my Alacritty configuration files for different environments. Each config file is named after its intended environment and should be used when launching Alacritty in that context. Examples are provided below:

### Windows
Create a shortcut and add these to the **Target**. This assume alacritty is located in Program Files, so replace it with your location

```
"C:\Program Files\alacritty\bin\alacritty.exe" --config-file %appdata%\alacritty\alacritty-wsl.toml

"C:\Program Files\alacritty\bin\alacritty.exe" --config-file %appdata%\alacritty\alacritty-pwsh.toml

"C:\Program Files\alacritty\bin\alacritty.exe" --config-file %appdata%\alacritty\alacritty-cmd.toml
```
