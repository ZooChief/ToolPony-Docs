# Probability calculator guide



Work with event probabilities or a two-way table of counts. Compare conditional probabilities, recover independent events, and calculate repeated trials or normal ranges.





## Example



### Input



```
Independent events A = 0.31, B = 0.56
```



### Expected result



```
At least one: 0.6964
```





<a id="case-study"></a>



## Attendance at two workshop sessions



1. Of 50 people, 18 attended both sessions, 12 only the morning (AM), 6 only the afternoon (PM), and 14 neither. Among the 24 afternoon participants, 18 also attended the morning: 75%. Among the 30 morning participants, 18 returned: 60%.



[Run example](<https://toolpony.com/en/tools/probability-calculator/#example-workshop-attendance>)





## Try it

[Open full tool · Probability calculator](<https://toolpony.com/en/tools/probability-calculator/>)





## Calculation method



P(A ∪ B) = P(A) + P(B) − P(A ∩ B). Among the observations in B, the share also in A is P(A ∩ B) / P(B). For independent events the intersection is the product of the marginals.



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## Calculation mode





### Two independent events



- Probability of A
- Probability of B







### Known intersection



- Enter · Probabilities / Observed counts
- Probability of A
- Probability of B
- Both events
- Event A name
- Event B name
- A ∩ B
- A ∩ ¬B
- ¬A ∩ B
- ¬A ∩ ¬B







### Recover independent events



- First known quantity · Probability of A / Probability of B / Not A / Not B / Both events / At least one event / Exactly one event / Neither event
- First probability
- Second known quantity · Probability of A / Probability of B / Not A / Not B / Both events / At least one event / Exactly one event / Neither event
- Second probability







### Repeated independent trials



- Probability of A
- Trials of A
- Probability of B
- Trials of B







### Normal distribution interval



- Mean
- Standard deviation
- Lower bound
- Upper bound







**Method references** [OpenStax · Contingency Tables](<https://openstax.org/books/introductory-statistics-2e/pages/3-4-contingency-tables>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fprobability-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/probability-calculator/)
