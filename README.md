
<h1> NTUT 資財三乙 林鴻璋 107AB0709
  
1.輸入並執行args.malware_paths 、args.benignware_paths 、args.evaluate
2.從 malware_paths 和 benignware_paths 內的檔案取得資料
3.使用隨機森林決策樹model 進行訓練
4.得出結果
![](https://github.com/mao0810/-/blob/main/image.png)

接收器操作特徵（ROC）曲線測量的是檢測器成功檢測到的惡意檔案的百分比和被錯誤標記為惡意檔案的善意檔案的百分比 這兩者的變化。
這邊可以看到我們如果靈敏度越高的話，他呈現出的假陽性回越多
相對靈敏度越低，錯誤越少

