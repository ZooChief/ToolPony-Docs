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





<a id="case-study"></a>



## Reconcile two stock lists after their columns move



1. Load the inventory example and select ID as the key. The old file has columns ID, Name, Qty. The new file starts with Qty. Compare the two exports.
2. ID 001 (Oak) changes from 2 to 4, ID 002 disappears and ID 003 is added. ID 004 stays unchanged. The result has one changed, one removed and one added record even though the columns moved.
3. In the new file change just 001 to 1 and compare again. Expect two additions, two removals and zero changed records. Restore the leading zeros in the source export to match the same item again.





## Try it

[Open full tool · CSV compare](<https://toolpony.com/en/tools/csv-compare/>)





## Limits



Up to 1 MiB of UTF-8 text, 5,000 data rows and 80 columns per table. Matches use exact text, including leading zeros. Duplicate and empty keys are reported separately. Row numbers count records, including the header.



For an inventory, use a stable SKU as the key. If the old export says 0012 and the new one says 12, the comparison reports one removal and one addition. To compare the quantity as a change, preserve the leading zeros in both exports.





**Method references** [IETF · RFC 4180 (CSV)](<https://www.rfc-editor.org/rfc/rfc4180>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fcsv-compare%2F>)

[Documentation](https://docs.toolpony.com/en/guides/csv-compare/)
