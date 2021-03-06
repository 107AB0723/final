# 資財三乙 107AB0723 徐薇妮 期末
# CH8

# 步驟

1.執行 run_complete_detector.sh\
2.利用SKlearn的RandomForestClassifier以及FeatureHasher提取特徵\
3.以機器學習方式訓練提取特徵\
4.用預測出來的scores和test_y辨別是惡意或善意的檔案\
5.繪製ROC curve的圖

# 結果
![image](https://github.com/107AB0723/final/blob/main/Curve.png)\
利用隨機森林決策樹model提取特徵的惡意軟件，\
再用接收器操作特徵（ROC）曲線測量的是檢測器的真實陽性率（成功檢測到的惡意檔案的百分比）\
和錯誤陽性率（被錯誤標記為惡意檔案的善意檔案的百分比）的變化。\
當靈敏度設定越高得到的假陽性(被錯誤標記為惡意檔案的善意檔案)越多，但會提高檢測率 ;\
而當靈敏度設定越低，則檢測的正確率(成功檢測到的惡意檔案)越高。

# 心得

這學期的課程內容相當豐富，透過線上課程的方式讓我可以看得更清楚老師的操作過程，\
也可以同步跟著老師操作，相較於實體課程，學習效率提升很多！\
雖然有時候老師動作太快會有點跟不上，\
但透過翻轉教學的方式，我們可以自行上網查詢操作教學或與同學互相交流討論。\
像是在這堂課接觸到很多網站、軟體和專有名詞，就讓我學習到很多以前沒接觸過的新知識，\
雖然沒有教到很多課本內容，但我覺得老師給了我們很多課外的內容，讓我收穫很多。\
謝謝老師準備這麼多元的課程內容，而且總是以輕鬆詼諧的教學方式教導我們，讓我們上課不會覺得有壓力～\
希望之後有機會還能再修到老師的課！！！

