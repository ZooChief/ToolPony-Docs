# Unix timestamp converter guide



Convert Unix seconds, milliseconds, microseconds or nanoseconds to UTC and back, preserving each digit.





## Example



### Input



```
0 seconds
```



### Expected result



```
1970-01-01T00:00:00.000Z
```





<a id="case-study"></a>



## One nanosecond before the epoch



1. Select ns and enter -1. The UTC result is 1969-12-31T23:59:59.999999999Z. Change direction to recover the same integer.
2. Reading logs across offsets? 1970-01-01T05:44:59.999999999+05:45 represents that same instant. Copy a single unit or export all four in one CSV row.



[Run example](<https://toolpony.com/en/tools/unix-timestamp-converter/#example-before-epoch>)





## Try it

[Open full tool · Unix timestamp converter](<https://toolpony.com/en/tools/unix-timestamp-converter/>)





## Calculation method



Unix time counts from 1970-01-01T00:00:00Z and excludes leap seconds. Dates from 1900 to 9999 UTC accept up to nine fractional digits and an explicit offset.







## Calculation mode





### Timestamp to date



- Unix timestamp
- Unit · Seconds / Milliseconds / Microseconds / Nanoseconds







### Date to timestamp



- ISO 8601 with offset
- Unit · Seconds / Milliseconds / Microseconds / Nanoseconds







**Method references** [GNU · Seconds since the Epoch](<https://www.gnu.org/software/coreutils/manual/html_node/Seconds-since-the-Epoch.html>) · [IETF · RFC 3339](<https://www.rfc-editor.org/rfc/rfc3339>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Funix-timestamp-converter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/unix-timestamp-converter/)
