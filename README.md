# I3 Config

1) https://github.com/vishalmry/i3-rice

#Config I3 in .config/i3/config

# ${{\color{purple}Lock Screen}}\ $

1) https://github.com/Raymo111/i3lock-color

2) https://github.com/meskarune/i3lock-fancy

3) https://github.com/i3/i3lock

# ${{\color{purple}Linux Terminal}}\ $

### DOC 

1) https://www.geeksforgeeks.org/how-to-make-linux-terminal-look-awesome/

2) https://www.imaginelinux.com/linux-terminal-customization/

3) https://dev.to/mikgross/ultimate-terminal-customization-51c7

4) https://www.freecodecamp.org/news/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38/

5) https://dev.to/arthurborges/3-setting-an-awesome-terminal-part-2-5dh9

# ${{\color{purple}Change Color Palette According to the Wallpaper}}\ $

### PYWAL

# ${{\color{purple}Wallpapers}}\ $

1) http://wallhaven.cc/
2) 
3) https://www.toptal.com/designers/subtlepatterns/
4) 
5) https://www.reddit.com/r/wallpapers/
6) 
7) https://unsplash.com/fr
8) 
9) https://www.pxfuel.com/en/query?q=unixporn

10) just https://images.google.com

Use some great keywords and I find something cool all the time.

Examples:

``car wallpaper 1920x1080``

``Old barns 1920x1080``

``fantasy space 1920x1080``

``Purple sky 1920x1080``


# ${{\color{purple}Rice tmux}}\ $

1) https://www.fosslinux.com/81276/change-colors-in-tmux.htm

2) https://medium.com/hackernoon/a-gentle-introduction-to-tmux-8d784c404340

3) https://medium.com/hackernoon/a-gentle-introduction-to-tmux-8d784c404340

4) https://github.com/jimeh/tmux-themepack

# ${{\color{purple}Polybar}}\ $

1) https://github.com/polybar/polybar

``cp /etc/polybar/config.ini polybar``

2) https://www.youtube.com/watch?v=kWRQoLFntQc

### Icons :

3) https://www.nerdfonts.com/cheat-sheet

### Vidéo :

4) https://www.youtube.com/watch?v=kWRQoLFntQc

# ${{\color{purple}Rofi}}\ $

1) https://colorhunt.co/palletes

2) https://www.youtube.com/watch?v=a-KEPMjZ1CI

3) https://github.com/adi1090x/rofi

Create theme in the directory :

``/home/$user/.local/share/rofi/theme``

New theme :

``Name.rasi``

* {
  width: 40; # la longueur de rofi
  show-icons: true;
  icon-theme : "Papirus";
  
  bg: #443C68;
  hv: #635985;
  txt: #fff;
  ug: #443C68;

  background-color: @bg;
  dark: @bg;
  border: 0px;
}

window {
  width: 520;
  location: center;
  ancor: center;
  spacing: 0;
  children: [mainbox];
  orientation: horizontal;
}

mainbox {
children: [ inputbar, message, listview ];
}

message {
  padding: 5px;
}

inputbar {
  color: @txt;
  padding: 11px;
  border: 0px 0px 2px 0px;
  border-color: @txt;
}

entry,prompt,case-indicator {
  text-font: inherit;
  text-color: inherit;
}

prompt {
  margin: 0px 5px 0px 0px;
}

listview {
  lines; 15;
}

entry {
  placeholder: "";
  cursor: text;
}

element {
  padding: 8px;
  vertical-align: 0.5;
  color: @txt;

}





# ${{\color{purple}Vidéo}}\ $

1) https://www.youtube.com/watch?v=bdumjiHab

2) https://www.youtube.com/watch?v=3H17rkGaJ5U













