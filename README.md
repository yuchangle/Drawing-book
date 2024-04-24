# Process
### repository---仓库                commitchanges---提交修改           space---空间          preview---预览    
### quickly get started---快速上手    mechine---机器     command---命令      origin---起源   remote---远程连接   
### already exists---已经存在      failed---失败的     ref---判断   anonymous---匿名的    associated---有关联的   
### mirror---镜子（景象网点）   receive---接收   copilot---助手    enterprise---企业     status---状态
### organization---组织     sponsor---赞助者    gist---依据、  connect---连接    refused---拒绝 authenticity---真实性
### establish---建立 fingerprint---指纹  verification---证实  



# 实现django cms demo
### 1.登陆网址https://github.com/teebook/bookcms
### 2.进入这个网址 https://www.django-cms.org/en/
### 3.找到Get started 这个模块并在终端/命令行复止执行下面的代码
### $ python3 -m venv .venv         //调用python的解释器（-m）已模块的方式运行命令 创建一个虚拟环境 目录名称为venv
### $ source .venv/bin/activate     //用于激活当前目录下的.venv文件夹中的python虚拟环境
### $ pip install django-cms        //安装django cms 到你的python中
### $ djangocms mysite              //创建一个新的目录
### $ cd mysite                     //进入这个目录  
### $ python -m manage runserver    //启动django服务器在网站上测试


# 终端中的djangocms代码提交到GitHub上
### 1.下载git
### 2.生成ssh密钥对，（ssh-keygen -t rsa -b 4096 -C "你的邮箱"）运行后默认按一下回车 设置一个密码 确认一遍
### 3.使用命令打开公钥文件件 （cat ~/.ssh/id_rsa.pub）复制内容 登陆你的GitHub账号，点击右上角头像Setting 选择 SSH snd GPGkeys ，点击
###    New SSH key 把复制的内容粘贴进去
### 4.测试ssh链接GitHub 使用（ssh -T git@github.com）第一次链接 输入yes
### 5.在GitHub上创建一个新的仓库
### 6.进入djangocms代码文件夹中（cd mysite）
### 7.创建一个新的本地仓库（git init）
### 8.克隆这个仓库（git clone）git@github.com:你的GitHub名/你创建的仓库名）
### 9.将代码添加到本地仓库中（git add.）提交并更改（git commit -m "Initial commit"）
### 10.将本地更改推送到GitHub上（git push -u origin main） 
### 备注：ssh代理（eval $(ssh-agent -s)）(ssh-add ~/.ssh/id_rsa) 

# nginx
### /bin/bash -c "$(curl -fsSL https://gitee.com/ineo6/homebrew-install/raw/master/install.sh)" 下载homebrew
### brew update 更新homebrew
### brew install nginx 安装nginx
### brew services start nginx 启动nginx 访问http://localhost:8080/ 可以看到欢迎界面

# 使用terminal与服务器连接
### 使用ssh username@server_ip -p port——number
### 成功之后输入服务器密码
### 断开链接 exit

# vim操作命令
### ：wq  保存并退出
###  esc 键退出编辑
###  ：q！ 退出不保存



