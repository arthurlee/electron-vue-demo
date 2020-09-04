# electron-vue-demo

## Prepare Environment For Chinese Developer
### set registry to taobao
```
npm config set registry https://registry.npm.taobao.org
```

### Windows
```
npm config set ELECTRON_MIRROR http://npm.taobao.org/mirrors/electron/
```

### Mac

- bash
Add 
```bash
echo "export ELECTRON_MIRROR=http://npm.taobao.org/mirrors/electron/" >> ~/.bash_profile
```

.zsh
```zsh
echo "export ELECTRON_MIRROR=http://npm.taobao.org/mirrors/electron/" >> ~/.zshrc
```


## Project setup
```
npm install
```

### Compiles and hot-reloads for development Vue
```
npm run serve
```

### Compiles and hot-reloads for development Vue in Electron
```
npm run electron:serve
```


### Compiles and minifies for production
```
npm run electron:build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
