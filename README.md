# Process
repository---仓库  commitchanges---提交修改    space---空间     preview---预览    quickly get started---快速上手    mechine---机器   command---命令      origin---起源   remote---远程连接    already exists---已经存在      failed---失败的     ref---判断
anonymous---匿名的    associated---有关联的   mirror---镜子（景象网点）   receive---接收



实现django cms demo
1.登陆网址https://github.com/teebook/bookcms
2.进入这个网址 https://www.django-cms.org/en/
3.找到Get started 这个模块并在终端/命令行复止执行下面的代码
$ python3 -m venv .venv         //调用python的解释器（-m）已模块的方式运行命令 创建一个虚拟环境 目录名称为venv
$ source .venv/bin/activate     //用于激活当前目录下的.venv文件夹中的python虚拟环境
$ pip install django-cms        //安装django cms 到你的python中
$ djangocms mysite              //创建一个新的目录
$ cd mysite                     //进入这个目录  
$ python -m manage runserver    //启动django服务器在网站上测试















终端中的代码提交到GitHub上
1）git init //初始化一个本地仓库
2）git add . //添加文件到仓库  .代表当前目录及其所有子目录中的所有文件。如果你想添加特定的文件或文件夹，可以使用git add <file>或git add <folder>
3）git commit -m 。。。。//-m后面跟着的是你对这次提交的描述信息
4）在GitHub上创建一个新的仓库
5）git remote add origin URL //url是仓库的url
6）git push -u origin main //推送到远程仓库
