A misc plugin for openbmc

## How to use

1. 光标停在bbclass的文件名上，按下gf键，便可跳转到对应的文件

2. openbmc的CI会检查commit message里面的错误单词，这个插件可以按照CI的检查规则纠正单词

比如输入 `accordign/accoring` 会被自动纠正为 `according`

参考输入下视频文件

[obmc-misc.webm](https://github.com/user-attachments/assets/17adb99c-6ff9-4853-bf0a-462f75f85113)

## How to install

### Vundle

Put this in your `.vimrc`.

```vim
Plugin 'wangzqbj/obmc-misc.vim'
```

### pack

Put it in `~/.vim/pack/general/start`
```sh
mkdir -p ~/.vim/pack/general/start
git clone https://github.com/wangzqbj/obmc-misc.vim.git ~/.vim/pack/general/start/obmc-misc.vim
```
