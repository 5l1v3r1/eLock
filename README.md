
# eLock
<div align="center">
<img align="center" src="./buildAssets/icon/icon.png"></img>
</div>

_eLock is an electron based app with certain restrictions which helps to prevent malpratices to a greater extent._

![shield-version](https://img.shields.io/badge/version-v1.1.0-orange.svg)

## Features

- Disabled Copy , Paste ...
- On change of application , the examination app quits.
- Special keys blocked.

<br/><br/>

## Getting Started

> ## Cloning repository
```bash
git clone https://github.com/pranshuchittora/eLock.git
```
> ## Installing dependencies
```bash
npm install
```
<h4 align="center"> 
OR
</h4>

```bash
yarn install
```
> ## Running the Project

```bash
npm start
```
<h4 align="center"> 
OR
</h4>

```bash
yarn start
```
>## Packaging the app
```bash
npm run build:win  #For windows
```
```bash
npm run build:mac  #For MacOS
```
```bash
npm run build:linux  #For Linux
``````
## Project Struture
    .
    +-- appLogic                 # Main Logic of the app
    |   +-- keys.json
    |   +-- mainMenu.js
    |   +-- restriction.js    
    +-- build                    # Contains builds for dist
    +-- buildAssts               # App assets
    +-- public                   # Webpage
    +-- index.js                 # Entry point
    +-- package.json             # No explanation required
    +-- README.md
