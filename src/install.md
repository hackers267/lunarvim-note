# 安装

## 前提条件

想要安装`lunarVim`，需要以下几个条件:

- 安装最新版本的`Neovim`
- 已安装`git`，`make`,`pip`,`python`,`npm`,`node`和`cargo`
- 拥有足够的权限来安装全局的`npm`包
- 如果是`Windows`用户，需要安装`PowerShell 7+`

## 安装发行版

```shell
LV_BRANCH='release-1.3/neovim-0.9' bash <(curl -s https://raw.githubusercontent.com/LunarVim/LunarVim/release-1.3/neovim-0.9/utils/installer/install.sh)
```

## 安装`Nightly`版

```shell
bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/master/utils/installer/install.sh)
```

## 更新`LunarVim`

要更新`LunarVim`，使用使用以下的方式:

- 在`LunarVim`内部更新：使用命令`:LvimUpdate`
- 在命令行中更新:`lvim +LvimUpdate +q`

### 更新插件

更新插件需要在命令行中更新:

- `:LvimSyncCorePlugins`

## 卸载

如果要卸载`LunarVim`，使用以下命令:

```shell
bash ~/.local/share/lunarvim/lvim/utils/installer/uninstall.sh
```
