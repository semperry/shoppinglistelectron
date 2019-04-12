# Electron ShoppingList Desktop App

This application is a test for my first run at a cross platform Electron desktop app. Add items, remove them all, or double click to remove one at a time.

### Version
1.0.0

## Usage


### Installation

Install the dependencies
```sh
$ npm init
```

```sh
$ npm install --save electron
```
Create "start" script in package.json file
in "scripts":
```sh
{
  "start": "electron ."
}
```

### Serve
To run electron

```sh
$ npm start
```

### To Package & Build

For Windows

```sh
$ npm run package-win
```

For Mac

```sh
$ npm run package-mac
```

For Linux

```sh
$ npm run package-linux
```