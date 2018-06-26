
請在此【com.exam】這個package下實作所有的程式，完成一題請先 commit (最後再push全部的commits即可)
<pre>
第一題題目:
在專案根目錄有一個文字檔menu.txt，記錄這家餐廳的菜單，一行資料如下:
1,大麥克,65,534
各欄代表 點餐號碼、餐點名稱、售價與熱量(kcal)
請設計一執行類別，名稱為Main.java，執行後讀取所有菜單後並列出
每項餐點資訊如下:
1) 大麥克
2) 雙層吉士牛肉堡
3) 麥脆雞原味
4) 麥香魚
5) 薯條大包
6) 可樂
7) 冰紅茶
0) 結算
q) 離開(結束程式)
請輸入餐點: 4   (使用者輸入4)
請輸入數量: 2   (使用者輸入2)
目前餐點:       (列出目前餐點清單、分隔線後，再列出功能列表)
1. 麥香魚 2份
=================
1) 大麥克
2) 雙層吉士牛肉堡
3) 麥脆雞原味
4) 麥香魚
5) 薯條大包
6) 可樂
7) 冰紅茶
0) 結算
q) 離開(結束程式)
請輸入餐點: 1   (使用者輸入1)
請輸入數量: 1   (使用者輸入1)
目前餐點:       (列出目前餐點清單、分隔線後，再列出功能列表)
1. 麥香魚 2份
2. 大麥克 1份
=================
1) 大麥克
2) 雙層吉士牛肉堡
3) 麥脆雞原味
4) 麥香魚
5) 薯條大包
6) 可樂
7) 冰紅茶
0) 結算
q) 離開(結束程式)
請輸入餐點: 0   (使用者輸入0，代表點餐完成，需列出目前餐點清單，與總計金額)
所有餐點:
1. 麥香魚 2份
2. 大麥克 1份
合計: 165	 (合計 50*2+65 的結果)


第二題題目
請為第一題加入功能，每次點完並合計後，使用者只需按下Enter就
可以繼續服務下一位客人。


第三題題目
在每次結算時計算所有餐點的熱量合計，超過1200kcal就在
最後加印一行"高熱量餐點"


第四題題目
當使用者輸入錯誤，例如輸入 "a"、"KAKA"、"15"等無法辦識功能時，印出錯誤訊息並可重新輸入，如下:
1) 大麥克
2) 雙層吉士牛肉堡
3) 麥脆雞原味
4) 麥香魚
5) 薯條大包
6) 可樂
7) 冰紅茶
0) 結算
q) 離開(結束程式)
請輸入餐點: a   (使用者輸入a，印出無此餐點，並可以重新選擇餐點)
[無此餐點]
請輸入餐點: 1   (使用者輸入正確餐點編號)
請輸入數量: b   (使用者輸入b，錯誤數量，需印出數量錯誤，並重新輸入數量)
[數量錯誤]
請輸入數量: 2   (使用者輸入正確數量)
目前餐點:       (列出目前餐點清單、分隔線後，再列出功能列表)
大麥克 2份
=================
</pre>


menu.txt的內容:
<pre>
1,大麥克,65,534
2,雙層吉士牛肉堡,55,446
3,麥脆雞原味,60,244
4,麥香魚,50,321
5,薯條大包,45,376
6,可樂,35,397
7,冰紅茶,30,117
</pre>