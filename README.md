# zdgithub.github.io
- hexo分支用来存放博客网站的基本文件
- master分支存放生成的静态网页

在本地对博客进行修改后，执行以下命令更新部署：
1. git add .
2. git commit -m "提交信息"
3. git push origin hexo
即可将改动推送到github的默认分支，已经设置为hexo分支
4. hexo d -g 发布网站到master分支

当在其它电脑上更改时
1. git clone 仓库名
2. 在该仓库文件夹下执行：npm install hexo ; npm install ; npm install hexo-deployer-git