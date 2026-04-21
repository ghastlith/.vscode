# .vscode

This is a storage repository which contains all my vscode settings and its purpose is to provide easy access on the fly.

The way to use it is to simply clone it inside the root of the repository being using at the moment and removing the [.git](.git/) folder. By doing this, vscode will automatically fetch the config from the .vscode folder and will not track changes unnecessarily.

As for the extensions, an extra step is needed, which is to run the following command on the terminal for every desired extension

```sh
code --install-extension ${extension-id}
```
