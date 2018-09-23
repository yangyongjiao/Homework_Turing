
# 图灵班提交作业说明

### 0. 准备工作：检查本地秘钥有无问题

请同学们先打开个人电脑c盘下面的.ssh文件夹，查看有没有修改该目录下公钥文件id_rsa.pub，如果已重命名，请再改回来，否则后续作业无法正常提交！
![pic](https://github.com/tsingke/Homework_Turing/blob/master/%E3%80%90%E4%BD%9C%E4%B8%9A%E4%BB%BB%E5%8A%A1%E3%80%91/%E5%AE%9E%E9%AA%8C%E6%8A%A5%E5%91%8A%E6%A8%A1%E6%9D%BF/ssh.png)

>> <不要重复生成公钥，切忌修改公钥，请勿丢失公钥>

>> <不要重复生成公钥，切忌修改公钥，请勿丢失公钥>

>> <不要重复生成公钥，切忌修改公钥，请勿丢失公钥>

**重要的事情说3遍**。

----
### 1. 先-配置git信息（自报家门）
任何同学第一次使用git前，先给自己的机器配置好名字,这样你提交作业时，才知道作业的实际贡献者是谁

`$ git config --global user.name "写你的名字"`

`$ git config --global user.email "写你的邮箱"`

> 注：只配置一次即可，后续提交作业时无须再配置

-----

### 2.后-提交作业（学会即可）
**说明1：**  `没有提交过作业，也就是第一次准备提交作业的同学，请依次执行下面的命令：`
```
1. 克隆远程作业: $ git clone git@github.com:tsingke/Homework_Turing.git 

2. 在作业文件夹里添加个人文件夹，然后在里面添加已写好的作业(程序代码+程序结果截图)

3. 切换到集体作业目录，在该目录下右键打开git bash here，接着做个远程作业同步：
   $ git pull   <同步远程作业> ，一般会很快！
 
4. $ git add .  

5. $ git commit -m "第一次提交作业"

6. $ git push origin master

```
-----

**说明2：** `已完成作业提交的同学，如果想修改作业，请务必先执行$git pull 命令 以保持和远端仓库作业内容同步 ，具体操作过程如下`：

```
打开集体作业大目录，然后右键点击“git bash here”，接着依次执行下面的命令：

1. $ git pull

   > git pull 结束后 在本地作业目录下修改本人作业，添加源码，添加执行结果截图文件

2. $ git add .

3. $ git commit -m "modify my homework"

4. $ git push origin master

```
-----


附录：作业提交前为何要先执行 $git pull 命令？ 

解释: 在集体参与的github项目里，项目内容可能随时会发生内容的变动或修改。我们采用git pull的目的就是为了保持和远程项目仓库作业内容始终一致，在此基础上再增量式添加本人的作业内容。如果本地作业提交前没有先执行git pull命令，那么本地已有的那些老版本的项目内容会在提交时将远程仓库里其他参与人最新提交的作业内容进行完全覆盖。所以，为了避免作业覆盖问题，在提交本地作业前务必先要执行git pull命令。


