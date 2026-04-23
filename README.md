# .vscode

This is a storage repository which contains all my vscode settings and its purpose is to provide easy access on the fly.

To use it simply clone this repository on the root of the project being used at the moment and remove the [.git](.git/) folder. By doing this, vscode will automatically fetch the config from the .vscode folder and will not track changes unnecessarily.

As for the extensions, an extra step is needed, which is to run the following command on the terminal for every desired extension.

```sh
code --install-extension ${extension-id}
```
