git init
git add *
git commit -m ''
//配置本机与 github 链接 用 ssh密钥
//第一步： 生成密钥 ssh-keygen -t rsa -C '1392998434@qq.com'
//创建密钥文件 ：将生成的密钥写入文件中

//第二部： 查看密钥 cat ~/.ssh/id_rsa.pub    xxx.pub 文件表示的是 密钥文件
//第三步： 来到github [new ssh] 将ssh密钥复制进去：建立电脑与GIT HUB链接
如何将本地仓库 添加到 远程仓库
第一步：创建一个远程仓库 创建一个本地仓库（）
第二步： 建立本地仓库与远程仓库链接 
git remote add origin 链接远程仓库地址
第三步： 将本地仓库添加到远程仓库 git push -U origin master
 -git push 添加
 -u 表示用户
 -origin 组织
 -master 主支

 如果更改代码添加到远程
 git add-----------> git commit----------> git push
 第一次才需要建立电脑与git hub的链接
 只有新的仓库 才需要建立 本地仓库与远程仓库的链接
  
  方式二 ：直接使用git hub 工具直接上传



  ### github
  1.如何使用github 进行项目管理
  2.如何使用github 自学 开源代码 
  3.如何使用github 进行多人合作开发