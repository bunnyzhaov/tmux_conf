# tmux_conf
mac上的tmux配置

### 在已有的tmux上修改配置

编辑`.tmux_conf`文件

### 新换的mac电脑上配置tmux

新建配置文件
```
.tmux_conf
``

使用此配置前,新电脑需要先安装依赖:
```
brew install reattach-to-user-namespace
```

若无依赖,则配置中的若干配置命令无法识别,配置不生效
