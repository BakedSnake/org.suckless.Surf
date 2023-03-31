### Surf Browser Flatpak 
Install Luakit with flatpak.

#### Dependencies
* flatpak-builder

( Might create a repo in the future, but for now flatpak-builder it is. ).

#### Installation
Download the script and install it with flatpak-builder.
```
git clone https://github.com/bakedsnake/org.suckless.Surf
cd org.suckless.Surf
mkdir build
flatpak-builder --user --install ./build org.suckless.Surf.yml
```

#### Usage
Now you should be able to see it in your flatpak list, and should be able to run it like any other flatpak package:
```
flatpak run org.suckless.Surf 
```

Happy browsing (:
