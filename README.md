# vscode-dev-containers

A collection of VS Code dev container configs for
[GitHub Codespaces](https://docs.github.com/en/github/developing-online-with-codespaces).
Choose a dev container config that fits your project and copy it into your
GitHub repository. Then launch a dev container for your repository on GitHub
Codespaces.

All configs in the
[`container`](https://github.com/454de6e/vscode-dev-containers/tree/main/containers)
folder are based on the
[official containers](https://github.com/microsoft/vscode-dev-containers) and
customize `devcontainer.json` and files inside the `.vscode` folder. These are
just configs, not GitHub templates. You still need to set up your GitHub repo
properly for the configs to make sense. I am planning to add a GitHub template
for each configuration in the future.

These are the available configs:

| Config                                                                                   | Description                                              |
| :--------------------------------------------------------------------------------------- | :------------------------------------------------------- |
| [`gatsby`](https://github.com/454de6e/vscode-dev-containers/tree/main/containers/gatsby) | Config for [Gatsby](https://www.gatsbyjs.com/) projects. |
