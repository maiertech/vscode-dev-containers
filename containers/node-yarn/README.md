# `node-yarn` config

## build

- Dockerfile: `Dockerfile` from
  [javascript-container](https://github.com/microsoft/vscode-dev-containers/tree/master/containers/javascript-node).
- Node: 12

## settings

- Remote settings:
  [`.devcontainer/devcontainer.json`](https://github.com/454de6e/vscode-dev-containers/blob/main/containers/node-yarn/.devcontainer/devcontainer.json)
- Workspace settings:
  [`.vscode/settings.json`](https://github.com/454de6e/vscode-dev-containers/blob/main/containers/node-yarn/.vscode/settings.json)

## extensions

- [dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## postCreateCommand

`yarn install`
