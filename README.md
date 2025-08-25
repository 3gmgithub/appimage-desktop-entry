Bash script that creates desktop entry for an .AppImage

appimage-desktop-entry

```txt
Usage: appimage-desktop-entry [OPTIONS]
    
Options:
    
    --help            Display this help message
    --app-name        Use to specify name of app in menu (Defaults to filename, if omitted)
    --app-path        Use to specify app filepath
    -s                Add '--no-sandbox' to app
    --remove          Remove the .desktop file
    
Create desktop entry:

    appimage-desktop-entry --app-name 'Example' --app-path '/path/to/Example.AppImage'

    appimage-desktop-entry --app-name 'Example' --app-path '/path/to/Example.AppImage' -s


Remove desktop entry:

    appimage-desktop-entry --app-name 'Example' --app-path '/path/to/Example.AppImage' --remove
```