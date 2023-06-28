---
title: 迁移My Blog
date: 2023-06-28
---

## My Blog 迁移
1. 从github把备份的blog拉取下来，带有source, git等文件夹
2. 链接这个库与gitee
3. 重新安装npm
```
npm install
npm install hexo-deployer-git -save
hexo clean
hexo g -d
```



