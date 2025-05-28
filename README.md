# irandom
copied directly from Python, then modified so that `random` is now `irandom` and `choices` is now `ichoices`, and they both return iterators.

```
PS C:\Users\kevin\source\code\irandom> python .\irandom.py
isample: first item latency: 2.86102294921875e-05; n=1099511627776; k=1048576
sample: first item latency: 0.5935227870941162; n=1099511627776; k=1048576

isample: list latency: 0.59226393699646; n=1099511627776; k=1048576
sample: list latency: 0.5742096900939941; n=1099511627776; k=1048576

ichoices: first item latency: 0.02016925811767578; n=1099511627776; k=1048576
choices: first item latency: 0.19440007209777832; n=1099511627776; k=1048576

ichoices: list latency: 0.18208718299865723; n=1099511627776; k=1048576
choices: list latency: 0.18341541290283203; n=1099511627776; k=1048576

ishuffle: first item latency: 0.21599483489990234; n=16777216
shuffle: first item latency: 9.432875156402588; n=16777216
old shuffle: first item latency: 9.318235874176025; n=16777216

ishuffle: list latency: 9.987539291381836; n=16777216
shuffle: list latency: 9.757800817489624; n=16777216
old shuffle: list latency: 8.954532623291016; n=16777216
```
