# Simutrans flatpak

## Build and run

```
git submodule init
git submodule update
flatpak-builder build --user --install-deps-from=flathub --force-clean --ccache --install com.simutrans.Simutrans.yaml
flatpak run com.simutrans.Simutrans
```
