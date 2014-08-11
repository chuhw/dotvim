## 使用方法：
- 抓下來後要 update submodule
- 指令：

    ```vim
    git submodule update --init
    ```

### 要加入新的 submodule 要用 git submodule add
- 指令：

    ```vim
    git submodule add REPOURL .vim/bundle/REPONAME
    ```

- ex:

    ```vim
    git submodule add https://github.com/nanotech/jellybeans.vim.git .vim/bundle/jellybeans.vim
    ```

### 要移除 submodule 要用 git submodule deinit
- 指令：

    ```vim
    git submodule deinit .vim/bundle/REPONAME
    git rm .vim/bundle/REPONAME or git rm --cached .vim/bundle/REPONAME
    ```

- ex:

    ```vim
    git submodule deinit .vim/bundle/Align
    git rm .vim/bundle/Align or git rm --cached .vim/bundle/Align
    ```
