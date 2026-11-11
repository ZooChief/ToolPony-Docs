# CSV compare



Paste or import the older and newer tables. Keep the first row as the header, then choose the delimiter and key columns. Compare and filter the changes. CSV is suitable for spreadsheets, and JSON preserves the original text and complete report.





## Get started



1. Paste or import the older and newer tables. Keep the first row as the header, then choose the delimiter and key columns.
2. Compare and filter the changes. CSV is suitable for spreadsheets, and JSON preserves the original text and complete report.







## Example



### Input



```
ID,Name,Qty
001,Oak,2
002,Pine,1
004,Ash,3

Qty,ID,Name
4,001,Oak
1,003,Fir
3,004,Ash
```



### Expected result



```
Added 1 · Removed 1 · Changed 1
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/csv-compare/>)







## Limits



Up to 1 MiB of UTF-8 text, 5,000 data rows and 80 columns per table. Matches use exact text, including leading zeros. Duplicate and empty keys are reported separately. Row numbers count records, including the header.

[Documentation](https://docs.toolpony.com/en/guides/csv-compare/)
