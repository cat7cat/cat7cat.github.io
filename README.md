<h1>
    github    
</h1>

GIT 教學
https://backlog.com/git-tutorial/tw/



遠端的 - 正常已經有內容
本地端

兩地端的檔案 可能有四種情境要處理

遠端      1.有     2.有    3.沒有    4.沒有
本地端    1.有     2.沒有   3.有     4.沒有

1.無法 有的話也要查閱&對照檔案內容差異
2.可拉 直接抓下
3.可推 直接上傳
4.可推可拉

同步 - 唯一的參照

force指令 可以全部取代掉(不建議使用)


看 HOWHOW  PULL拉下來   PUSH推上去

大部分公司都是建議用二.四

把檔案拉下來
```git=
git init
git remote add origin 遠端git路徑 
git pull origin main

```
CTRL+K  三秒內 按 V

可以把read.md的說明編輯

之後再把要新上傳的檔案放上去遠端 

```git=
git status
git add .
git commit -m "新增說明"
git pull origin main 

```