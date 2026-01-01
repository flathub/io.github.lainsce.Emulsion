# Emulsion

___Stock up on colors___

Store your palettes in an easy way, and edit them if needed.

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing

```
flatpak install flathub io.github.lainsce.Emulsion
flatpak run io.github.lainsce.Emulsion
```

## Building

```
git clone git@github.com:flathub/io.github.lainsce.Emulsion.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.lainsce.Emulsion.json
```

---

**Technologies**: GTK, Vala, libhelium
