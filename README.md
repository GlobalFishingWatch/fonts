Forked from https://github.com/openmaptiles/fonts 

## Supported Font Families

The following fonts that are available in Mapbox Studio are supported.

* Roboto Medium + Italic
* Roboto Mono Light + Italic

## Package the Fonts

Fontnik binaries are only provided for node v6, start with:

```
nvm install 6
nvm use 6
```

Install required packages:

```
npm install
```

Generate fonts:

```
node ./generate.js
```
The PBFs will created be in the `_output` directory.
They need to be moved to the client repo.

## Font License

Please mind the license of the original fonts.
All fonts are either licensed under OFL or Apache.
