# ML100Days
NLP Machine learning

## D01-D04 Python NLP程式基礎
- 字串處理
- 正規表達式

### D1 HW
- .tsv ：以t作為分隔符的檔案，可以用 pd.read_csv('檔名',set='\t')開啟，存成df
- 使用 df.values 取出值存成list
- 計算有多少個句子是以 . 結尾
- 將所有. 換成 ,
- 將所有sentence 中的第一個 the 置換成 The
- 將偶數句子全部轉換為大寫，基數句子全部轉換為小寫
- 將所有句子合併在一起，並以' / ' 為間隔

### D2 HW
- 計算numeric, digit, decimal 各有幾個
  - 補充函數： ` getattr(x, 'foobar')` is equivalent to `x.foobar`
  -  `getattr('qqq','upper')()` --> output：'QQQ'
- 運用formatting 技巧 output
  - `'{:.2f}%'.format(98.12452)` --> 98.12%
  - `'{:.2%}'.format(0.9812452)` --> 98.12%
  - '{:0<10f}'.format(3.1415926)` --> 3.141592300
  
