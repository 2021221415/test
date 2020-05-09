<!--
 * @Author: Juck
 * @Date: 2020-05-09 16:07:05
 * @LastEditTime: 2020-05-09 16:16:40
 * @LastEditors: Juck
 * @Description: 
 * @FilePath: \test\README.md
 * @Juck is coding...
 -->

# README

## 步骤

```bash
    # 创建一个远程仓库，比如在github上新建一个
    # 创建本地仓库，比如test文件夹
    # 使用git将本地的test仓库管理起来
    git init test
    # 设置远程仓库地址为git@github.com:2021221415/test.git，别名为origin。
    git remote add origin git@github.com:2021221415/test.git
    # 比如现在你可以做一些修改
    git add .
    git commit -m "some changes"
    # 同步到远程仓库(要先设置远程仓库的分支,分支名是master)
    # --set-upstream
    git push -u origin master
    git push
```