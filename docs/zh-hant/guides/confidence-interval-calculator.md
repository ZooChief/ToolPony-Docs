# 置信區間計算器使用指南



由樣本數據或彙總統計量計算均值的 z 或 t 置信區間，也可用 Wilson 方法估計比例區間。





## 示例



### 輸入



```
樣本 36，均值 56，標準差 8，置信水平 99%
```



### 預期結果



```
56 ± 3.434
```





<a id="case-study"></a>



## 用五次測量估計均值



1. 五次測量爲 48、49、50、51、52，平均值爲 50。採用樣本標準差，自由度爲 4，均值的 95% t 置信區間約爲 48.04 至 51.96。這裏假定觀測相互獨立，且總體近似正態。



[運行示例](<https://toolpony.com/zh-hant/tools/confidence-interval-calculator/#example-five-measurements>)





## 抽檢 30 件，發現 0 件不合格



獨立抽檢 30 件，發現 0 件不合格。按 Wilson 方法估計總體不合格率，95% 區間爲 0% 至約 11.35%。如果擴大抽樣且仍未發現不合格，區間會變窄。



[運行示例](<https://toolpony.com/zh-hant/tools/confidence-interval-calculator/#example-no-failures>)







## 試一試

[打開完整工具 · 置信區間計算器](<https://toolpony.com/zh-hant/tools/confidence-interval-calculator/>)





## 計算方法



均值區間的誤差幅度等於臨界值 × 標準差 / √n。已知總體標準差時取 z，使用樣本標準差時取自由度爲 n − 1 的 t。Wilson 區間由二項試驗中的成功次數和總次數估計比例。



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## 計算模式





### 均值區間



- 數據來源 · 已知總體 σ / 樣本 s / 樣本數據
- 樣本量
- 均值
- 標準差
- 樣本數值
- 置信水平 · %







### Wilson 比例區間



- 樣本量
- 成功次數
- 置信水平 · %







**方法來源** [NIST · Confidence limits for the mean](<https://www.itl.nist.gov/div898/handbook/eda/section3/eda352.htm>) · [NIST · Confidence limits for a proportion](<https://www.itl.nist.gov/div898/handbook/prc/section2/prc241.htm>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fconfidence-interval-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/confidence-interval-calculator/)
