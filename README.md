# 一，下载git项目

## 使用ssh克隆（下载）项目
1. 生成ssh key
- 创建仓库目录，双击进入
- 右键Git Bash Here
- ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
- clip < ~/.ssh/id_rsa.pub  -- 复制到粘贴板
- 登陆github -> setting -> SSH and GPG keys -> New SSH key -> 粘贴

2. 下载项目
- 复制git链接 git@github.com:274152416/demo.git
- 控制台执行git命令
- git clone git@github.com:274152416/demo.git
