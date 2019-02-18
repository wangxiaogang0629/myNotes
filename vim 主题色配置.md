### 修改vim主题色

* `cd ~` 进入用户主目录

* `cp -r /usr/share/vim/vimrc ~/.vimrc` 复制系统的vim配置文件到用户目录

* `vim .vimrc` 编辑.vimrc文件

* `colorscheme参数` 表示主题色

* `cd /usr/share/vim/vim74/colors/` 后主为vim的文件为vim的主题文件 将其作为`colorscheme参数` 即可


###其他设置

* `syntax on` 语法高亮

* `autocmd InsertLeave * se nocul` `autocmd InsertEnter * se cul` 用浅色高亮当前行

* `set tabstop=4` Tab键的宽度

* `set softtabstop=4` `set shiftwidth=4` 统一缩进为4

* `set number` 显示行号

* `colorscheme pablo`	设置颜色主题

* `set ruler`	在编辑过程中，在右下角显示光标位置的状态行

* `set scrolloff=3` 	光标移动到buffer的顶部和底部时保持3行距离