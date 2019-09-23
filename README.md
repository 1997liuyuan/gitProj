1.下载git并安装
2.在终端配置用户信息
git config --global user.name  "Your Name"
git config --global user.email "email@example.com" 3.查看配置信息
git config --list
4.创建文件夹，右键Git Bush here 调出终端
5.输入 git init 创建本地版本库
6.在文件夹类写好文件后
git add .：添加文件至本地版本库
git commit -m ""：提交至本地版本库
7.第1步：**创建SSH Key。在用户主目录下，看看有没有.ssh目录，如果有，再看看这个目录下有没有 ”id_rsa“ 和 ”id_rsa.pub“ 这两个文件，如果已经有了，可直接跳到下一步。如果没有，打开Shell（Windows下打开Git Bash），创建SSH Key：
8.登陆Github -> 点击右上角个人头像 -> 点击Settings进入设置页面 ->点击SSH and GPG keys选项 -> 点击右上角New SSH key ->在添加面板中，Title：设置SSH key 标题，可任意填Key：id_rsa.pub”文件内容拷贝至此然后点击 Add SSH Key 就可以看到你创建的SSH Key了
9.