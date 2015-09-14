# 建立repository
```shell
>git init
```
基本上有UI工具就用工具就好了, 不需要學指令, 使用GitHub Desktop、Source tree或Tortoise Git都很好,
我用GitHub Desktop建立一個Repository, 主要是因為他的Git ignore有我想要的Node.
![Add](https://cloud.githubusercontent.com/assets/1026320/9849913/c0499318-5b21-11e5-836c-f8936524b11b.png)
建立好了之後, 它會幫我建立.gitattributes及.gitignore, 並且commit一個版本在master上.
# 開始
再來我建立一個Express站台
```shell
>express -TA -e
```
然後我要加到版控中, 等等, 我已經關掉GigHub Desktop改成SourceTree了,
![git002](https://cloud.githubusercontent.com/assets/1026320/9850185/7f9b361c-5b23-11e5-9490-a9223442c4f4.png)
從選單File->Open開啟剛剛的目錄, 接下來可以在Working Copy和File Status看到差異, 等等, 我沒有要commit, 我要執行Git Flow.
![git003](https://cloud.githubusercontent.com/assets/1026320/9850304/53ae32ce-5b24-11e5-89d3-844b859e8dd1.png)
OK就是了, 會多了一個Develop的Branche, 而且你應該也在Develop上, 等等, 還沒要commit, 再執行一次Git Flow.
![git004](https://cloud.githubusercontent.com/assets/1026320/9850375/c017db18-5b24-11e5-90b1-ebb163c60ec8.png)
建立新Feature, 表示我要開發一個功能
![git005](https://cloud.githubusercontent.com/assets/1026320/9850484/76a73644-5b25-11e5-9d24-61c0332b859e.png)
此Feature是我個人使用的, 如果我不換Device, 也不跟別人共同開發, 基本上不會上到GitHub
![git006](https://cloud.githubusercontent.com/assets/1026320/9850487/7ad3999c-5b25-11e5-92cc-5a24609b782f.png)
最後在feature/Peter分支我commit.
![git007](https://cloud.githubusercontent.com/assets/1026320/9850623/7e495afc-5b26-11e5-8bac-b9c9867805e6.png)
又回到了GitHub Desktop將Publish到自己GitHub
![git008](https://cloud.githubusercontent.com/assets/1026320/9850760/5f10f806-5b27-11e5-82fa-a82254fd8125.png)
現在可以在GitHub網站上看到TA專案了,接下來Feature開發完了要回Develop與大家共享, 在Peter分支上執行Git Flow
![git009](https://cloud.githubusercontent.com/assets/1026320/9850898/65747c76-5b28-11e5-8d6f-2997f5639419.png)
![git010](https://cloud.githubusercontent.com/assets/1026320/9850901/69268094-5b28-11e5-9575-1b7fcc293fed.png)
執行Push, 將Develop及master上傳到GitHub, 併回Develop完成後要給QA或使用者測試, 所以在Develop分支上執行Git Flow, 建立Start New Release
![git011](https://cloud.githubusercontent.com/assets/1026320/9850989/0ef8cbf8-5b29-11e5-9395-5d1df9057e7b.png)
非常順利的可以上線了, 於是再執行Git Flow來Finish Release
![git012](https://cloud.githubusercontent.com/assets/1026320/9851034/46894124-5b29-11e5-980e-ec7eec038826.png)
完成後到GitHub上看一下, release的分支刪除了, 多了一個Tag:V0.1, 但是自己上的Peter分支仍在
![git013](https://cloud.githubusercontent.com/assets/1026320/9851302/8aba2736-5b2a-11e5-8676-940f1493e2bb.png)
請手動刪除
