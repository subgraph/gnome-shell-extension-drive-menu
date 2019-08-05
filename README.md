# GNOME Shell Extension Drive Menu for Citadel

Broken out fork of the official [GNOME Shell drive-menu](https://gitlab.gnome.org/GNOME/gnome-shell-extensions) 
extension with adaptations for usage under Citadel. Built using [meson-gse](https://github.com/F-i-f/meson-gse).

```shell
./meson-gse/meson-gse
meson build
ninja -C build test          # Checks syntax of JavaScript files
ninja -C build install       # Install to /usr/share/gnome-shell/extensions
ninja -C build extension.zip # Builds the extension in build/extension.zip
```

