# lib.dom-enums

Adds more typing information and documentation on top of lib.dom.d.ts. Uses [microsoft/vscode-custom-data](https://github.com/microsoft/vscode-custom-data).

## How to Build:

https://github.com/microsoft/vscode-custom-data#updating-web-data

```sh
cd data/
git pull
cd web-data/
yarn update-sources
yarn generate-data
cd ../..
node generate.js
```