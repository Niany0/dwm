## This is my main suckless dwm setup!
There are configs for dwm and other suckless programs. I'll put everything related to suckless in this repo so you can download it.

## Dependencies
- scrot
- thunar
- rofi
- dmenu
- kitty
- (optionally you can enable picom(config in releases))

## Attention!
To download a whole *de* you have to download it from releases. So if you only need the dwm config, you can execute:
```
git clone https://github.com/Niany0/dwm
cd dwm
sudo make install
```

## Commands that must be included in .xinitrc
```                                                                                                                                
exec dwm                                                                                                                                           
exec slstatus     
```
*will be updated...*

### Sources:
- [Suckless](https://suckless.org)
