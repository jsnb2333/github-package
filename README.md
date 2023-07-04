# 概述
这是一个使用 GitHub Package管理包的github demo库。

## 介绍文件夹
hello-github-package 文件夹，是package。

use-package 文件夹，是使用库。

## 使用方式
命令行:

**cd .\use-package\\**

**npm install**，从GitHub Package网下载“@jsnb2333/hello-github-package”包作为项目依赖

**npm start**，控制台打印“Hello GitHub Package”，表示使用成功。

注意：要登录npm login --registry=https//npm.pkg.github.com,npm才能下载GitHub Package网上的仓库。
登录方式与https://registry.npmjs.org是不同的。[详情](https://docs.github.com/zh/packages/working-with-a-github-packages-registry/working-with-the-npm-registry)