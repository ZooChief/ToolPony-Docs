# URL encode and decode guide



Encode or decode URLs and form values, or edit ordered query parameters with repeated names and empty values.





## Example



### Input



```
Encode component: a+b & c
```



### Expected result



```
a%2Bb%20%26%20c
```





<a id="case-study"></a>



## Keep the plus signs in a search term



1. Encode C++ &amp; tea as a form value to obtain C%2B%2B+%26+tea. Literal plus signs become %2B, spaces become + and the ampersand becomes %26. Reverse the output to recover the original. In URI component mode spaces become %20.
2. In Query parameters, open the example with two tag entries. Change the second value to UI &amp; UX. The first tag, the empty value and \#filters survive, and the edited value becomes UI+%26+UX.



[Run example](<https://toolpony.com/en/tools/url-encoder-decoder/#example-query-plus>)





## Try it

[Open full tool · URL encode and decode](<https://toolpony.com/en/tools/url-encoder-decoder/>)





## Calculation method



A component escapes reserved separators. A complete URL retains separators. A form value uses + for a space. Query editing applies form encoding to each name and value separately and retains the path and fragment.





**Method references** [IETF · RFC 3986](<https://www.rfc-editor.org/rfc/rfc3986>) · [WHATWG · Form encoding](<https://url.spec.whatwg.org/#application/x-www-form-urlencoded>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Furl-encoder-decoder%2F>)

[Documentation](https://docs.toolpony.com/en/guides/url-encoder-decoder/)
