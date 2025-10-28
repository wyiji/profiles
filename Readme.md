# Git 初始設定與常用語法

## 初始設定

```bash
# 設定使用者名稱
git config --global user.name "你的名字"

# 設定使用者信箱
git config --global user.email "你的信箱"

# 檢查設定
git config --list
```

## 常用語法

```bash
# 初始化本地倉庫
git init

# 新增檔案到暫存區
git add 檔案名稱

# 提交暫存區到本地倉庫
git commit -m "提交訊息"

# 查看狀態
git status

# 查看提交紀錄
git log

# 連接遠端倉庫
git remote add origin 遠端網址

# 推送到遠端倉庫
git push origin master

# 拉取遠端更新
git pull origin master

# 檢查目前分支
git branch

# 建立新分支
git branch 分支名稱

# 切換分支
git checkout 分支名稱
```