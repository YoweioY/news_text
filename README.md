# 新聞語料關鍵字分析

1. 利用聯合新聞網作為主要的文本來源，將收集回來的新聞內文存在一個 List 容器變數 `news` 內。
2. 使用`jieba`斷詞套件與相關工具做斷詞。
3. 將每篇新聞文章斷詞後的結果存入 `tokens` 變數，並且將斷詞後的結果計算成每個單字的出現次數（詞頻），並存成以「出現單字為 KEY、出現次數為 Value」的 dict 型態變數 `word_count`。
4. 將每個單字的出現次數（詞頻）依照出現次數由多到少進行排序。

09_news_text03.ipynb為最終版程式
資料來源: https://udn.com/news/
