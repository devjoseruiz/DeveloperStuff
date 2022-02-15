# Developer Stuff
## Backup of VSCode extensions & config

### How to backup a list of installed extensions

```bash
code --list-extensions > vscode_extension_list.txt
```

### How to reinstall extensions

```bash
sh install_extensions.sh vscode_extension_list.txt
```

### How to restore settings

Simply override the settings.json file.
