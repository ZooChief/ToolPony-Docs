# 百分比計算器使用指南



計算百分比和百分點變化，按兩次折扣求成交價或反推原價。





## 開始使用



1. 要算 240 的 15%，選擇「求百分比對應的數值」。已知部分爲 36 且知道總量或比例時，選擇相應反推模式。
2. 有先後順序和原值時，選「百分比變化」。兩個正數沒有基準先後時，選「百分比差異」。
3. 15% 輸入 15。可用下面的例子覈對計算結果。







## 示例



### 輸入



```
240 的 15%
```



### 預期結果



```
36
```





<a id="case-study"></a>



## 同一件商品連續打折



1. 原價 250，先減 20% 得 200，再按 200 減 10%，成交價爲 180。兩次合計降價 28%。點擊反推驗證可以還原原價。



[運行示例](<https://toolpony.com/zh-hant/tools/percentage-calculator/#example-two-discounts>)





## 從 4% 提高到 5%



註冊率從 4% 提高到 5%，相差 1 個百分點。以原來的 4% 爲基準，相對增幅爲 1 ÷ 4 = 25%。



[運行示例](<https://toolpony.com/zh-hant/tools/percentage-calculator/#example-percentage-points>)







## 試一試

[打開完整工具 · 百分比計算器](<https://toolpony.com/zh-hant/tools/percentage-calculator/>)





## 計算方法



相對變化率以原值的絕對值爲分母。兩個百分率相減得到百分點變化。連續增減的係數相乘。對稱差異率以兩數絕對值的均值爲分母。



$$
x=yp/100,\quad p=100x/y,\quad y=100x/p
$$



$$
\Delta\%=100\frac{x_1-x_0}{|x_0|},\quad D\%=200\frac{|x_1-x_0|}{|x_1|+|x_0|}
$$



80 增至 100 的變化率爲 25%，因爲原值是 80。同樣兩個數的百分比差異約爲 22.22%，因爲分母是均值 90。



漲 20% 後爲 120，用「反推原值」可得 100。變化率 −100% 無法反推。原值爲 0 時無法計算百分比變化率。



實測爲 90、參考爲 96 時，絕對百分誤差爲 6.25%。相對於這個正參考值的有符號結果爲 −6.25%。







## 計算模式





### 求百分比對應的數值



- 百分比 · %
- 數值







### 求所佔百分比



- 部分
- 總量







### 求總量



- 部分
- 百分比 · %







### 百分比變化



- 數值含義 · 一般數值 / 百分率 (%)
- 原值
- 新值







### 百分比差異



- 數值一
- 數值二







### 帶符號數值的差異率



- 數值一
- 數值二







### 按比例增減



- 原值
- 變化率（帶正負） · %
- 第二次增減 · %







### 反推原值



- 新值
- 變化率（帶正負） · %
- 第二次增減 · %







### 百分誤差



- 實測值
- 參考值
- 誤差口徑 · 絕對值 / 相對於參考值的有符號誤差







**方法來源** [Eurostat · Percentage point](<https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Glossary:Percentage_point>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fpercentage-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/percentage-calculator/)
