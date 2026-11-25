# 直角三角形計算器使用指南



根據兩個已知量求直角邊、斜邊和角度，支持從高、面積或周長反推。





## 開始使用



1. 請輸入兩個已知量，其中至少一項是邊長、高、面積或周長。
2. 兩個解互換兩條直角邊及兩個銳角的標號。







## 示例



### 輸入



```
c = 5，h = 2.4
```



### 預期結果



```
兩條直角邊爲 3 和 4，面積爲 6，周長爲 12。任一邊均可記爲 a。
```







## 試一試

[打開完整工具 · 直角三角形計算器](<https://toolpony.com/zh-hant/tools/right-triangle-calculator/>)





## 計算方法



c 是斜邊，h 是斜邊上的垂直高。長度統一單位，面積使用對應的平方單位。



$$
c^2=a^2+b^2,\quad h=ab/c,\quad S=ab/2,\quad P=a+b+c
$$



$$
a,b=\frac{\sqrt{c^2+2ch}\;\pm\;\sqrt{c^2-2ch}}{2}
$$





[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fright-triangle-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/right-triangle-calculator/)
