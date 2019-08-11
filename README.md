# electron-quick-start-flutter
A minimal Electron application with flutter & dart

![Screenshot](screenshots/main.png)

## To Use

```bash
# Clone this repository
git clone https://github.com/electron/electron-quick-start-typescript
# Go into the repository
cd electron-quick-start-flutter
#install flutter dependencies
pub get
# Install dependencies
npm install
# Run the app
npm run dev
```



 
## Release
To build for production, first run `npm run build`.

The output directory, `build/web/` contains a `package.json` pointing to the built
application, and can be run as follows:

```bash
cd build/web
npm install
npm start
```

### Packaging
The output directory's package manifest, `build/web/package.json`, includes
[`electron-packager`](https://github.com/electron-userland/electron-packager),
and therefore can be packaged for distribution on Windows, MacOS, and Linux.

run `npm run build` in `build/web` to build for the host platform.
