# Modrinth App Flatpak

to build this flatpak:

```sh
# install the dependencies:
flatpak install org.gnome.Platform//44
flatpak install org.gnome.Sdk//44
flatpak install org.freedesktop.Sdk.Extension.node18//22.08
flatpak install org.freedesktop.Sdk.Extension.rust-stable//22.08

# build the flatpak:
# (it will take a long while and a lot of cpu cores to build webkit2gtk)
./build.sh

# and run it:
flatpak run com.modrinth.theseus
```
