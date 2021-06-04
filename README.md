# Flipartner
Flipper companion application (desktop)

## Build:
### Linux:
```sh
docker-compose exec dev ./build_linux.sh
```

## Run:
```sh
./build/flipartner-x86_64.AppImage
```
or just launch the file above from your favourite file manager.

## Usage:
- Press `Update` to install the latest available version. It will be brightly coloured if there is an actual update.
- Long press `Update` to get the menu.
- Select `Other versions...` to get a list of all available firmware versions. There, you may install any of them you like.
- Select `Update from local file...` if you wish to install a *.dfu file you downloaded yourself.

## Limitations:
* Some run-time errors are not handled correctly
