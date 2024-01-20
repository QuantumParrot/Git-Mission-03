### 分支

`git branch dev` -- 本地端建立 dev 分支

`git checkout dev` -- 本地端切換至 dev 分支

`git push origin dev` -- 將本地端的 dev 分支推至遠端節點 ( github repo ) 上

### 還原

`git reset HEAD^` -- 退回至當前 commit ( *HEAD* ) 的上一個步驟 ( *^* )，暫時可以理解為 " 拆掉當前 commit " 的意思

### 合併

在 GitHub Repo 上方發送 PR

合併請求成功之後，切回 `main` 分支，再透過 `git pull origin main` 將最新進度拉回至本地端

