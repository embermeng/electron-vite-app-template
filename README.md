# electron-vite-app

An Electron application with Vue and TypeScript

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) + [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

## Project Setup

### 准备工作

1. node版本: v20.19.2
2. 使用npm config list ll -ls，打开.npmrc文件，添加下面的配置，路径如：C:\Users\admin\.npmrc
   registry=https://registry.npmmirror.com/
   home=https://npmmirror.com
   electron_mirror=https://registry.npmmirror.com/-/binary/electron/
   electron_builder_binaries_mirror=https://registry.npmmirror.com/-/binary/electron-builder-binaries/
3. 安装cnpm: npm i cnpm -g

### Install

```bash
$ cnpm install
```

### Development

```bash
$ cnpm run dev
```

### Build

```bash
# For windows
$ cnpm run build:win

# For macOS
$ cnpm run build:mac

# For Linux
$ cnpm run build:linux
```
