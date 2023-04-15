### Surf Browser Flatpak 
Surf with tabbed, bookmarks and websearch.

#### Dependencies
* flatpak
* flatpak-builder

#### Installation
Download the script and install it with flatpak-builder.
```
git clone https://github.com/bakedsnake/org.suckless.Surf.git
cd org.suckless.Surf
mkdir build
flatpak-builder --user --install ./build org.suckless.Surf.yml
```

#### Usage
Now you should be able to see it in your flatpak list, and should be able to run it like any other flatpak package:
```
flatpak run org.suckless.Surf 
```

##### Keybindings
```
Url: Ctrl + g
Web search: Ctrl + s
Bookmark: Ctrl + m
Find: Ctrl + f or Ctrl + /
Scroll down: Ctrl + j
Scroll up: Ctrl + k
Show tabs: Ctrl + Shift
New tab: Ctrl + Shift + Enter
Select tab: Ctrl + < tab number >
Move tab to right: Ctrl + Shift + j
Move tab to left: Ctrl + Shift + k
```

Happy browsing (:
