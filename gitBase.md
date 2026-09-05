* X
/* 
echo "# ihaiouhuang.github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Ihaiouhuang/ihaiouhuang.github.io.git
git push -u origin main 

///////////////////////////////////////////////

git remote add origin https://github.com/Ihaiouhuang/ihaiouhuang.github.io.git
git branch -M main
git push -u origin main
*/
* git Linus(Linux早期)
	* 版本控制 svn git hg pac
	* 毕业论文.doc
	* 毕业论文-修改版.doc
	* 毕业论文-再修改版.doc
	* 毕业论文-最终修改版.doc
	* 毕业论文-最终修改版2.doc
	* 毕业论文-最终修改版3.doc
	* 以管理毕业论文为需求提出需要记录文件变更过程的需求
		* source control manager
		* git-scm
		* version control / svm hg
	* 记录变更时一个很重要的功能，也很复杂
	* git config --global user.name "xieran"
	* git config --global user.email "xxx@qq.com"
	* git config --global alias.st status
	* git config --global alias.br branch
	* git config --global alias.co checkout
	* git config --global alias.ci commit
	* git init 在一个文件夹的 .git 文件夹下初始化一个仓库
	* git status 查看当前仓库的状态
	* git add file.txt 添加 file.txt 到待提交区
	* git add . 添加当前文件夹里的所有文件
	* git commit -m "提交信息"
	* git diff 显示被跟踪的文件的修改状态
	* git log 查看提交日志/历史
	* git commit -a -m 'xxx'	添加所有文件并提交
	* git remote add 远程仓库名字 https://ihaiouhuang.github.io/learn-git-2021/hello.html
	* git remote remove 远程仓库名字
	* git remote set-url 远程仓库名字 git:git@github........
	* git remote - v 查看远程仓库的名字及地址
	* git push -u origin	main
	* ssh-keygen 生成公私钥对
	

	git remote add origin https://ihaiouhuang.github.io/learn-git-2021/hello.html

	https://USERNAME.github.io/miao/a.txt
	* 步骤 git 仓库 配置
		* git init 														建立 git 仓库 
		* git add 文件								 				添加 要提交 文件		（ git add . ）
		* git status 													查看状态
		* git remote add origin 地址					添加远程仓库
		* git remote set-url origin 地址			更改 git 远程仓库链接地址
		* git remote remove origin 						删除 git 远程仓库
		* git push -u origin main							不用重复写