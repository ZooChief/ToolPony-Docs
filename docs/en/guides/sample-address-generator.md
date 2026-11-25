# Sample address generator guide



Generate address samples for 18 countries and regions, with local formatting, subdivisions, and batch export.





## Get started



1. Select a country or region and a subdivision. Set the batch size and optional contact fields.
2. Reuse a seed with the same settings to reproduce a batch. Copy fields individually or export TXT, CSV, or JSON.
3. Address samples stay in this browser when you choose Save locally. You can remove them in the tool.







## Example



### Input



```
Germany · Berlin · Seed pony-demo
```



### Expected result



```
Testperson 001
Beispielstraße 4957
10115 Berlin
Deutschland
```





<a id="case-study"></a>



## Check a Canadian unit address



1. Use the seed label-review to generate two Ontario test addresses with unit numbers and no contact details. Repeating the same settings gives the same pair.
2. In the text download, the unit precedes the street number with a hyphen. On the city line, ON is followed by two spaces and the postal code. JSON also keeps each component in a separate field.



[Run example](<https://toolpony.com/en/tools/sample-address-generator/#example-canadian-label>)





## Try it

[Open full tool · Sample address generator](<https://toolpony.com/en/tools/sample-address-generator/>)





## Calculation method



Up to 100 samples per batch. Locality and postcode are format fixtures, and street and recipient are synthetic. Phone examples use reserved numbers or masks. Use the results for form and software testing.





**Method references** [USPS · Publication 28, §213](<https://pe.usps.com/text/pub28/28c2_003.htm>) · [Canada Post · Civic address](<https://www.canadapost-postescanada.ca/cpc/en/support/articles/addressing-guidelines/civic-address.page>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fsample-address-generator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/sample-address-generator/)
