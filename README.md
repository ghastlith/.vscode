# .vscode

This is a storage repository that contains the vscode settings of the author, ant its purpose is to provide easy access to them on the fly.

To use it simply copy the contents of the files [settings](./settings.json) and [keybindings](./keybindings.json) and paste them into the vscode internal file counterparts. This will ensure that the application is properly configured.

As for the extensions, install every desired one by running the following command on the terminal.

```sh
code --install-extension ${extension-id}
```

As a sanity check to see if all the extensions were successfully installed, the following command may be used.

```sh
code --list-extensions --show-versions
```
