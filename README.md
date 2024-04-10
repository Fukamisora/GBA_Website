# 介绍
本项目为 WEB 技术网页展示项目源码部分。
+ 基于 Hexo 搭建
+ Github Page 部署
+ [Github 部署地址](https://github.com/Fukamisora/Fukamisora.github.io)
+ [示例网页](https://fukamisora.github.io/)

------
# 前置
## 插件
```
<<<<<<< HEAD
=======
npm i hexo-cli -g

>>>>>>> 5fa5e22a7c77b812e501af9deb9e65236c82391c
npm un hexo-renderer-marked --save

npm i hexo-renderer-multi-markdown-it --save

npm i hexo-autoprefixer --save

npm i hexo-algoliasearch --save

npm i hexo-symbols-count-time --save
```
## 一键部署到github（选）
```
npm install hexo-deployer-git --save
```

# git 常用指令
```
<<<<<<< HEAD
=======
git clone https://github.com/Fukamisora/GBA_Website.git            # 克隆本项目

>>>>>>> 5fa5e22a7c77b812e501af9deb9e65236c82391c
git fetch origin main                      # 将 main 分支拉取到本地（不合并）
git pull origin main                       # 拉取 main 分支
git pull origin main : local_branch        # 将 main 分支 拉取并合并到 local_branch

git init                                   # 初始化仓库
git add .                                  # 添加所有文件到缓存
git status                                 # 查看仓库状态
git commit -m "messages"                   # 批量注释修改文件
git push origin main                       # push到 main 分支

git branch                                 # 查看当前分支
git branch dev                             # 创建 dev 分支

git checkout dev                           # 切换到 dev 分支
git switch dev                             # 切换到 dev 分支

git checkout -b dev                        # 创建 dev 分支并切换到 dev 分支
git switch -c dev                          # 创建 dev 分支并切换到 dev 分支

git merge dev                              # 将 dev 分支合并到当前分支
git branch -d dev                          # 删除 dev 分支
```
------
