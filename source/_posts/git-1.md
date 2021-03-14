---
title: git 使用
date: 2021-03-14 15:48:38
tags:
---

### git init
``` bash
git init
```

### 建立新分支 backup
``` bash
git checkout -b backup
```

### add all file
``` bash
git add .
```

### 加入全部異動檔案
不論檔案狀態是 Untracked files 或是 Changes not staged for commit（紅色），都會一口氣變成 Changes to be committed（綠色）
``` bash
git add -A
git add --all 
```

### and commit
``` bash
git commit -m "1st commit"
```

### add origin
``` bash
git remote add origin https://github.com/hot5656/blog.git
```

### push origin to remote
``` bash
git push -u origin backup
```

### dump remote server setting
``` bash
git remote -v
```

### change origin setting
``` bash
git remote set-url origin https://github.com/hot5656/blog.git
```

### change modify status
```
git status
```




