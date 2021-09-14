# tauri-test

## Project setup
```

WSL & Linux:
    1. (WSL Only) You must use something like vcXsrv to display the window.
    vcXsrv can be downloaded here: https://sourceforge.net/projects/vcxsrv/
    2. (WSL Only) run the command 'export DISPLAY=$(cat /etc/resolv.conf | grep nameserver | awk '{print $2}'):0' to export your display. This must be done each time you start a new session in your terminal
    3. Follow this setup guid for Tauri: https://tauri.studio/en/docs/getting-started/setup-linux
    4. npm install
    5. npm install -g @vue/cli
    6. vue add tauri

npm install
```

### Compiles and hot-reloads for development
```
npm run tauri:serve
```

### Compiles and minifies for production
```
npm run tauri:build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
