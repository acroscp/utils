## Run exe in Flatpak App (utf8 patch does'nt work?)

### step.1

shell `flatpak run --command=bash APP`

### step.2

```
STEAMAPP=1234567 \
STEAM_COMPAT_DATA_PATH=~/APP/.local/share/Steam/steamapps/compatdata/$STEAMAPP \
$LOCATION_OF_proton run patch.exe 
```
