# tauri-test

## Project setup
```

WSL:
    1. You must use something like vcXsrv to display the window.
    vcXsrv can be downloaded here: https://sourceforge.net/projects/vcxsrv/
    2. run the command 'export DISPLAY=$(cat /etc/resolv.conf | grep nameserver | awk '{print $2}'):0' to export your display. This must be done each time you start a new session in your terminal
    3. npm install
    4. npm install -g @vue/cli
    5. vue add tauri

Linux & Windows: (not yet tested)
    1. npm install
    2. npm install -g @vue/cli
    3. vue add tauri

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
