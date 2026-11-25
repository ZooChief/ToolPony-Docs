# JSON formatter guide



Paste JSON, choose an indentation, and format or minify it. Copy the result or download a JSON file. Cmd/Ctrl + Enter runs the formatter.





## Get started



1. Paste a JSON document.
2. Choose two or four spaces, then format; use Minify for a compact result.
3. Copy the result or download the JSON file.







## Example



### Input



```
{"name":"ToolPony","ready":true}
```



### Expected result



```
{
  "name": "ToolPony",
  "ready": true
}
```







## Try it

[Open full tool · JSON formatter](<https://toolpony.com/en/tools/json-formatter/>)





## Good to know



Keys and strings need double quotes. Comments and trailing commas are not JSON. Numbers outside safe precision are rejected to avoid silently changing their values.







## Limits



Up to 1 MB. Invalid JSON and unsafe numeric precision are rejected. Formatting does not validate against an application schema.





**Method references** [IETF · RFC 8259 (JSON)](<https://www.rfc-editor.org/rfc/rfc8259>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fjson-formatter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/json-formatter/)
