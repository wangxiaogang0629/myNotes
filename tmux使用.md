##tmux使用

##连接mac
* 1、系统偏好设置打开网络，远程登录
* 2、ssh 用户名@ip地址
* 3、输入密码登录
* 4、创建一个会话
* 5、乙方电脑连接会话
* 

* 开启 `tmux`
* 退出 `exit`
* 杀死会话 `tmux kill-session -t second-session`
* 创建命名会话 `tmux new -s first`
* 监测计算机内存、cpu使用情况 开启会话后 `top`
* 分离会话 先按 `ctrl + d` 再按 `d`
* 查看当前存在的会话 `tmux ls`
* 链接某个会话 `tmux attach`
* 创建一个新的会话并在后台运行 `tmux new -s second_session -d`
* `-t` 参数加上会话名称来连接到指定的会话，如连接到 second_session 这个会话
	* `tmux attach -t second_session`

* 创建俩个窗口的新会话 `tmux new -s windows -n shell`
	* `-n` 参数可以让tmux 把第一个窗口名为 shell, 方便识别

* 要在当前会话创建一个新的窗口，只需要按下 `PREFIX c`
* 重新命名窗口 `PREFIX , `
* 切换到上一个窗口 `PREFIX p` 或者 `PREFIX n` 键（n=next, p=previous）

###使用面板

* `PREFIX %` 键 左右各一半 `PREFIX "` 继续分割面板
* 切换面板 `PREFIX o` 或者 UP、DOWN、LEFT 或 RIGHT 键（上、下、左、右箭头)

###其他命令
* `tmux list-key` 列出搜游绑定的键
* `tmux list-command` 列出所有命令

###快捷键
* prefix % 水平方向创建窗格
* prefix " 垂直方向创建窗格
* 

