#在Visual Studio中使用SVN管理项目版本
###初次使用
1. 下载并安装TortoiseSVN [https://tortoisesvn.net/downloads.html](https://tortoisesvn.net/downloads.html)  
2. 下载并安装Visual SVN [https://www.visualsvn.com/visualsvn/download/](https://www.visualsvn.com/visualsvn/download/)
3. 在SVN服务器上新建仓库
4. 在Visual Studio中新建或者打开旧有的解决方案(Solution)，在Solution Explorer窗口(可用Ctrl+Alt+L快捷键激活)中，右键点击解决方案，点击弹出菜单项“Add Solution to Subversion...”，在弹出对话框中确认根目录(一般就是解决方案所在目录)，点击“Next>”, 选中"Existing Repository"，点击“Next>”, 填入仓库的地址，并点击“Next>”,然后点击“import”
5. 在Visual Studio的Solution Explorer窗口中，右键点击解决方案，点击Commit, 确定需要提交的文件和修改内容无误后，输入适当的注解，然后点击"OK"。
###日常使用
1. 提交修改：每产生一次单独的，能正常工作的修改后，即可提交修改。操作方法为在Visual Studio的Solution Explorer窗口中，右键点击解决方案，点击Update, 再点击Commit, 确定需要提交的文件和修改内容无误后，输入适当的注解，然后点击"OK"。
2. 查看历史修改记录：右键点击解决方案或者项目或者文件，选中”Visaul SVN”->"Show Log..."
3. 查看当前未提交的修改内容：右键点击解决方案或者项目或者文件，选中"Show Changes"
4. 撤消当前未提交的修改内容：右键点击解决方案或者项目或者文件，选中"Revert Changes..."
