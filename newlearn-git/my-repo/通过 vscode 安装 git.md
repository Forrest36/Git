# 通过 vscode 安装 git
 - 点击左侧栏 源代码管理(source control)
 - 未安装 git 会提示安装，点击 Download Git for Windows
 - 点击弹窗上的 open 打开官方链接
 - 下载对应的安装包 64-bit Git for Windows Setup.双击安装包安装
 - choosing the defauit editor used by Git(选择git的默认编辑器)，可以选择VScode
 - Adjusting the name of the initial branch in new repositories,选择下面的选项Override the default branch name for new repositories 把默认的分支名字改为 main

# 安装完成第一件事，配置邮箱地址
 - 在命令行(win+R,输入cmd) / vscode终端(右上角菜单栏"终端"->新建终端) / 在git操作的文件夹内右键选择 "Open Git Bash here"
 - git config --global user.name "Forrest36"
 - git config --global user.email Forrest36@163.com
 - 完成邮箱配置后提交完成

# 再次修改后提交 
 - SOURCE CONTROL GRAPH 会新增第二次提交的存档
 - 第二次的存档与第一次的存档有一条线连接，表明二是基于一演变来的
 - 点击第二次存档，右边编辑区里色部分为删除的部分，绿色为新增的部分

# 远程提交
