+++
title = "LunarVim快捷键"
description = "LunarVim快捷键"
date = 2023-07-25 14:04:00
[taxonomies]
tags = ["快捷键"]
[extra]
toc = true
+++

# LunarVim快捷键

在使用LunarVim这类的编辑器的时候，其中一个优势是可以使用快捷键。对快捷键的熟练使用可以大大提高工作效率。

## 查看快捷键

通过是否包含有 *&lt;leader\>*键可以把*LunarVim*的快捷键分类两类：

- 以 *\<leader\>* 开头的快捷键
- 不包含 *\<leader\>* 的快捷键

> *LunarVim*默认的 *\<leader\>* 是Space(空格键)。

如果要查看以 *\<leader\>* 开头的快捷键，那么直接按下 *\<leader\>* 键即可。

如果要查看不以 *\<leader\>* 开头的快捷键，那么直接按下 *\<leader\>* 键后，再按 *BS* 即可。

## 常用默认快捷键

### Buffer操作

| 模式          | 按键           | 说明                 |
|-------------- | -------------- | ---------------------|
| normal        | \<leader\>bf   | 在buffer中查找       |
| normal        | \<leader\>bj   | 在buffer中跳转       |
| normal        | \<leader\>bn   | 转到下一个buffer     |
| normal        | \<leader\>bb   | 转到上一个buffer     |
| normal        | \<leader\>bh   | 关闭左侧buffer       |
| normal        | \<leader\>bl   | 关闭右侧buffer       |
| normal        | \<leader\>c    | 关闭当前buffer       |
| normal        | \<leader\>be   | 关闭指定buffer       |
| normal        | \<leader\>bD   | 以目录排序buffer     |
| normal        | \<leader\>bL   | 以语言排序buffer     |
| normal        | \<leader\>bW   | 不格式化保存buffer   |

### 跳转操作

| 模式    | 按键    | 说明    |
|---------------- | --------------- | --------------- |
| normal    | gd    | 跳转到定义    |
| normal    | gr    | 跳转到引用    |
| normal   | gI   | 跳转到实现   |
| normal   | gD   | 跳转到声明   |
| normal   | gs   | 显示签名帮助 |
| normal   | gl   | 显示行内诊断 |

### 插件

| 模式    | 按键    | 说明    |
|---------------- | --------------- | --------------- |
| normal    | \<leader\>e  | 打开目录栏 |
| normal    | `<leader>f`| 查找文件   |
| normal    | \<leader\>;  | 打开面板   |
| normal    | `<C-\>`,`<M-1/2/3>` | 打开toggleterm |
