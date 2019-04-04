# Surfer

Simple keyboard based web browser. No tabs.

Based on webkit2gtk and gtk3. Lariza and Epiphany, Surf inspired.

No xlibs dependency &mdash; works on wayland, weston, sway.

## Adblock

Install https://github.com/jun7/wyebadblock

Then sudo ln -s /usr/lib/wyebrowser/adblock.so  /usr/lib/surfer



Otherwise You can use `/etc/hosts block` list from  sites like 
someonewhocares.org


## Compile and install:
  
  git clone https://github.com/nihilowy/surfer.git

  cd surfer

  make &&  sudo make install

  on Arch: pacaur -S surfer

## Hotkeys:

`Ctrl + click` link &mdash; open link in new window

`Ctrl + n` &mdash; new window

`Ctrl +  b` &mdash; go back

`Ctrl +  f` &mdash; go forward

`Ctrl + q` &mdash; quit

`Esc` &mdash; stop loading

`Ctrl + h` &mdash; home (bookmarks list)

`Ctrl + shift + b` &mdash; bookmark site (to remove just edit file with 
links: .fav in your home dir)

`Ctrl + o` &mdash; toogle url bar

`Ctrl + /` &mdash; find word

`Ctrl + r` &mdash; reload page

`Ctrl + =` &mdash; zoom in

`Ctrl + -` &mdash; zoom out

`Ctrl + e` &mdash; scroll down

`Ctrl + d` &mdash; scroll up

`Ctrl +  j` &mdash; page up

`Ctrl +  k` &mdash; page down

`Ctrl + i` &mdash; web inspector (page source)

`Ctrl + Shift + s` &mdash; toogle user style black theme 
(/usr/share/surfer/black.css)

`Ctrl + Shift + h` &mdash; show history (.hist file in HOME dir), to 
enable history 
change HISTORY_ENABLE to 1 in surfer.c

`F11` &mdash; toogle fullscreen




**Edit `surfer.c` to change hotkeys**
