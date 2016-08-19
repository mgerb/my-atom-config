# Store your Atom settings on GitHub

- Fork this repo
- Navigate to your ~/.atom folder (File > Settings > Open Config Folder)
```bash
  git init .
  git remote add origin https://github.com/<user>/atom-config
  git pull origin master
```
- `npm run import` - installs atom-terminal for easy access
- `npm run sync` - exports your settings into backup.txt and pushes to GitHub
- edit .gitignore to remove/add files you want to sync

## Sync Steps

- File > Settings > Open Config Folder
- Alt+Shift+t (uses atom-terminal to open terminal in current directory)
- `npm run sync`
