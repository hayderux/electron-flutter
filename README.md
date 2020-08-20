# electron-quick-start-flutter
A minimal Electron application with flutter & dart

![Screenshot](screenshots/main.png)

## To Use

```bash
# Clone this repository
git clone https://github.com/hayderux/electron-flutter
# Go into the repository
cd electron-flutter
#install flutter dependencies
flutter pub get
# Install dependencies
npm install
# Run the app
npm run dev
```



 
## Release
To build for production, run `npm run release`


## Package
The output directory's package manifest, `build/web/package.json`, includes electron-packager, and therefore can be packaged for distribution on Windows, MacOS, and Linux.

to build for the host platform run:
``` 
npm run release
```
To build for all platforms, run :

``` 
npm run package
```
