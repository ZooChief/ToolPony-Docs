# Unicode 編碼轉換



在文本、Unicode 碼點、UTF-8 十六進制字節與 UTF-16 轉義間雙向轉換。





## 示例



### 輸入



```
🐴
```



### 預期結果



```
U+1F434 或 F0 9F 90 B4
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/unicode-converter/>)







## 計算方法



碼點模式將輔助平面字符視爲一個標量。UTF-16 對該字符使用兩個編碼單元。無效代理項序列和 UTF-8 字節會被拒絕。







## 計算模式



**編碼文本**

- 輸入
- 編碼 · Unicode 碼點 / UTF-8 十六進制字節 / JavaScript UTF-16 轉義





**解碼文本**

- 輸入
- 編碼 · Unicode 碼點 / UTF-8 十六進制字節 / JavaScript UTF-16 轉義

[文檔站](https://docs.toolpony.com/zh-hant/guides/unicode-converter/)
