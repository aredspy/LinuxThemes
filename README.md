# Customized Linux Themes



https://github.com/aredspy/LinuxThemes/assets/106393710/cb508cc6-0f8e-451e-9a95-f6a693c69179


### Alternate conky with VPN tunnel info:

![alt conky](conky_alt.png)

## Stuff in here

- Modiified conky cyber theme with nmcli grep instead of old iwconfig, forked from [ElectroTallinn](https://github.com/neuromask/electrotallinn-theme)
- Custom compiled Google Noto Emojji font that replaces dragon and crown with Dialga and Arceus because pokemon in terminal is funny [NotoColorEmoji](https://github.com/googlefonts/noto-emoji)
- Customized glava glsl audio bars
- Customized neofetch theme taken from [Neofetch Themes](https://github.com/Chick2D/neofetch-themes/) 

### Install

- For conky, copy into `~/.config/conky` and run `conky -c $HOME/.config/conky/cyber-theme/config.conf`
- For noto emoji, overwrite `/usr/share/fonts/google-noto-emoji/NotoColorEmoji.ttf` and run `sudo fc-cache -f -v` to refresh font cache
- For glava, copy into `~/.config/glava` and update `rc.glsl` with `#request mod bars`
- For neofetch, copy into `~/.config/neofetch`. More info about this on [Wiki](https://github.com/dylanaraps/neofetch/wiki/Customizing-Info)
