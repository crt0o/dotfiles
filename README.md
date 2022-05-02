# Dotfiles
![A screenshot of the desktop](https://i.imgur.com/H190Ihu.png)
These are the dotfiles for my current rice, this time using `bspwm`. I decided not to include a bar, since I found I didn't really need it and it was just taking up precious screen real-estate. I haven't really gotten to setting up a GTK theme, since it's a lot of work. I might do it in the future tho.
## Info
- **WM** -> `bspwm`
- **Walpaper setter** -> `feh`
- **Wallpaper** -> From (this)[https://www.reddit.com/r/EarthPorn/comments/tooxia/dolomites_natural_park_oc_andrealivieriphoto] reddit post, author is @andrealivieriphoto on Instagram
- **Terminal** -> `kitty`
- **Shell** -> `bash`
- **Compositor** -> `picom-jonaburg-git` (`aur`)
- **Lockscreen** -> `slock`
- **Font** -> JetBrains Mono Nerd Font (`nerd-fonts-jetbrains-mono` on the `aur`) for most things
- **Colors** -> A modified version of the catpuccin color scheme
- **Editor** -> `micro` (`aur`)
- **App launcher** -> `rofi`
- **Keybinding daemon** -> `sxhkd`
## Notes
- I also included the dotfiles for `spicetify` which is used to apply themes to Spotify. I used the `spicetify-cli` `aur` package, but there is also an install script on their website. It didn't really work out of the box for me, probably because I use the `flatpak` version. [This reddit post](https://www.reddit.com/spicetify/wiki/guideforflatpak) and [their install guide](https://spicetify.app/docs/advanced-usage/installation) were useful in getting it set up.
- The screen locker, `slock`, is configured via source, which is also included. Install with `sudo make clean install`.
- There are some settings in `.config/bspwm/bspwmrc` which need to be modified for your specific setup (I marked them with `TODO:`).
- I basically kept `.bashrc` as default so I didn't include it in the repo.
- `feh` is set up to display the wallpaper at `~/Backgrounds/background.*`.
