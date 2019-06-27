# 插件

## Tmux Resurrect

保存tmux当前的运行配置和环境,方便下次进入后直接启用

1. 下载:

```shell
mkdir -p ~/.tmux/plugins
cd ~/.tmux/plugins
git clone https://github.com/tmux-plugins/tmux-resurrect.git
```

2. 安装(在配置文件.tmux.conf写入)

`run-shell ~/.tmux/tmux-resurrect/resurrect.tmux`

3. 载入配置(命令行模式)

tmux source-file ~/.tmux.conf

4. shortcuts

保存会话:

 `前缀键 + Ctrl-s`

恢复会话:

 `前缀键 + Ctrl-r`

