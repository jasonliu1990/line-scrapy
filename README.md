# line-scrapy 
Line Today 爬蟲
## 主要分成四個table
* table1: 新聞文章
* table2: 評論
* table3: 評論的回覆
* table5: 文章分類
## 將拿到的資料塞入資料庫
使用 sqlalchemy</br>
<code> pip install sqlalchemy</code></br>
<code> pip install pyodbc</code></br>
將dataframe直接塞入DB</br>
<code> dataframe.to_sql('<table name>', engine, index=False, if_exists='append')</code></br>
