---
layout: app

permalink: /Pingendo/

icons:
  - Pingendo/icons/128x128/Pingendo.png

screenshots:
  - Pingendo/screenshot.png

authors:
  - name: Pingendo
    url: https://github.com/Pingendo

links:
  - type: GitHub
    url: Pingendo/pingendo
  - type: Download
    url: https://github.com/Pingendo/pingendo/releases

desktop:
  Desktop Entry:
    Name: Pingendo
    Comment: 
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: Pingendo
    StartupWMClass: Pingendo
    X-AppImage-Version: 4.2.2.431
    Categories: Utility
    X-AppImage-BuildId: 1Fl4UVqXCNwb4dkIXRBhAfP683V
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  license: MIT
  dependencies:
    adm-zip: "^0.4.11"
    angular: "^1.7.5"
    angular-tree-control: "^0.2.30"
    autoprefixer: "^9.2.1"
    codemirror: "^5.39.0"
    deep-diff: "^1.0.1"
    diff-dom: "^2.4.0"
    electron-about-window: "^1.12.1"
    electron-log: "^2.2.16"
    electron-packager: "^12.2.0"
    electron-store: "^2.0.0"
    electron-window-state: "^5.0.3"
    fs-extra: "^7.0.0"
    htmlhint: "^0.9.13"
    jquery: "^3.3.1"
    js-beautify: "^1.7.5"
    json-diff: "^0.5.2"
    keytar: "^4.3.0"
    mini-css-extract-plugin: "^0.4.2"
    netlify: "^2.2.0"
    node-localstorage: "^1.3.1"
    node-machine-id: "^1.1.10"
    node-sass: file:./node-sass
    oauth-electron: "^1.0.6"
    request: "^2.88.0"
    sass-lint: "^1.12.1"
    semver: "^5.6.0"
    source-map-support: "^0.5.5"
    temp: "^0.8.3"
    tinycolor2: "^1.4.1"
    true-case-path: "^1.0.3"
    universal-analytics: "^0.4.17"
    uuid: "^3.3.2"
  npmSkipBuildFromSource: true
  npmRebuild: false
  author: Pingendo Inc.
  description: ''
  resolutions:
    webpack-sources: 1.0.1
  electronWebpack:
    renderer:
      webpackConfig: webpack.renderer.additions.js
  github:
    repo: pingendo
    owner: Pingendo
  fileAssociations:
  - ext:
    - html
    - htm
    name: Pingendo
    role: Editor
  main: main.js
---
