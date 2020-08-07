# 在码云/GitHub中上传已有项目 #

## 1.配置 ##
	
	在项目目录下，右键打开git命令行
	git config --global user.name 'Nyang-git'
	git config --global user.email '1246568637@qq.com'

## 2.初始化并上传 ##
	
	在项目目录下
	git init   
	git remote add origin 码云仓库地址
	git add .
	git commit -m '描述'
	git push -u origin master
	