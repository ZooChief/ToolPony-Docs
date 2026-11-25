# UUID generator guide



Generate version 4 UUIDs using the browser’s secure random source.





## Example



### Input



```
Generate 1 identifier
```



### Expected result



```
Example shape: 550e8400-e29b-41d4-a716-446655440000
```





<a id="case-study"></a>



## Prepare 27 IDs for an import



1. Generate 27 uppercase UUIDs. In each identifier the third group starts with 4 and the fourth starts with 8, 9, A or B.
2. The last page contains rows 25–27. Copy row 27 to check one record, or download the text file to import all 27 lines in their original order.



[Run example](<https://toolpony.com/en/tools/uuid-generator/#example-import-ids>)





## Try it

[Open full tool · UUID generator](<https://toolpony.com/en/tools/uuid-generator/>)





## Calculation method



Version 4 UUIDs use 122 random bits, with six bits reserved for version and variant. Generate up to 500 per batch.





**Method references** [IETF · RFC 9562 (UUID)](<https://www.rfc-editor.org/rfc/rfc9562>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fuuid-generator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/uuid-generator/)
