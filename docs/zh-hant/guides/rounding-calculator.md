# 舍入計算器使用指南



按小數位或二進制分數步長精確舍入，支持九種規則。





## 示例



### 輸入



```
−2.5，個位，半數取偶
```



### 預期結果



```
−2
```







## 試一試

[打開完整工具 · 舍入計算器](<https://toolpony.com/zh-hant/tools/rounding-calculator/>)





## 計算方法



將精確餘數與半個步長比較，恰好一半時按方向或奇偶規則處理。最接近模式在平局時遠離零。



$$
x=qs+r,\qquad 0\le r<s,\qquad r=\tfrac{s}{2}\text{ at a tie}
$$



位數 2 表示保留到百分位，0 表示個位，−2 表示百位。分數步長可舍入到 1/4 或 1/16 等倍數。



半數取偶只在正好一半時選擇偶數倍。例如 −2.5 得 −2，−3.5 得 −4。向上取整始終朝正無窮方向。





[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Frounding-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/rounding-calculator/)
