# ML100Days
NLP Machine learning

## D01-D04 Python NLP程式基礎
- 字串處理
- 正規表達式 ([練習用網站:regex101](https://regex101.com/))

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
  - `{:0<10f}'.format(3.1415926)` --> 3.141592300
  
### D3  HW
Regex 101
- 電話號碼配對
- 身分證字號配對
- 電子郵件配對 
- HTML格式配對
- 特定檔案名稱與格式配對
- URL配對

### D4 HW
Python regex
- [詐欺郵件文本資料](https://www.kaggle.com/rtatman/fraudulent-email-corpus/data)清洗與處理的操作
- 電子信箱中的寄件機構資訊
- 所有寄件者與收件者 姓名、地址、信件日期、信件主旨、信件內文 (dictionary--> list --> dataframe)
