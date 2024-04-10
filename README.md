# 介绍
本项目为 WEB 技术网页展示项目源码部分。
+ 基于 Hexo 搭建
+ Github Page 部署
+ [Github 部署地址](https://github.com/Fukamisora/Fukamisora.github.io)
+ [示例网页](https://fukamisora.github.io/)
------
# 前置要求
+ node.js
+ git

# 使用方法
1. 安装 hexo
```
npm install hexo-cli -g
```

2. 克隆项目
```
git clone https://github.com/Fukamisora/GBA_Website.git
```

3. 安装其他插件
```
npm un hexo-renderer-marked --save

npm i hexo-renderer-multi-markdown-it --save

npm i hexo-autoprefixer --save

npm i hexo-algoliasearch --save

npm i hexo-symbols-count-time --save
```

> Hexo 框架使用方法详细参考 [官方说明文档](https://hexo.io/zh-cn/docs/)

------
# 附录
## git 常用指令
```
git clone https://github.com/Username/Repositories.git            # 克隆项目

git init                                   # 初始化仓库
git add .                                  # 添加所有文件到缓存
git status                                 # 查看仓库状态
git commit -m "messages"                   # 注释修改文件
git push origin main                       # push到 main 分支

git branch                                 # 查看当前分支
git branch branch_name                     # 创建 branch_name 分支

git checkout branch_name                   # 切换到 branch_name 分支
git switch branch_name                     # 切换到 branch_name 分支

git checkout -b branch_name                # 创建 branch_name 分支并切换到 branch_name 分支
git switch -c branch_name                  # 创建 branch_name 分支并切换到 branch_name 分支

git push origin branch_name                # 将分支 branch_name 上传

git merge branch_name                      # 将 branch_name 分支合并到当前分支
git branch -d branch_name                  # 删除 branch_name 分支

git fetch origin main                      # 将 main 分支拉取到本地（不合并）
git pull origin main                       # 拉取 main 分支
git pull origin main : local_branch        # 将 main 分支 拉取并合并到 local_branch
```
