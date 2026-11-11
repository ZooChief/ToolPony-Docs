# YAML to JSON



Paste a YAML document and convert it to JSON. Mappings must use string keys; output is formatted and ready to copy or download.





## Get started



1. Paste one YAML document with string mapping keys.
2. Convert to JSON.
3. Inspect, copy or download the result.







## Example



### Input



```
name: ToolPony
ready: true
```



### Expected result



```
{
  "name": "ToolPony",
  "ready": true
}
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/yaml-to-json/>)







## Good to know



Multiple documents, custom tags, cyclic aliases and values that JSON cannot represent are rejected. Quote a value if you mean a string rather than a boolean or number.







## Limits



Up to 1 MB. Custom tags, multiple documents, non-string keys, excessive aliases, cyclic structures, and values that JSON cannot preserve are rejected.

[Documentation](https://docs.toolpony.com/en/guides/yaml-to-json/)
