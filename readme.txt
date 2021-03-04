GIT 基命令
git init                -->创建git仓库
git add fileName        -->添加文件
git commit -m description       -->将已添加的文件提交到仓库 description:描述
git reset --hard version        -->版本回退，version:HEAD^-回退一个版本，版本号
git log                 -->查看日志，可携带参数(--pretty=oneline:一行显示一个版本)
git reflog              -->记录你使用的每一次git命令
git status              -->查看当前状态