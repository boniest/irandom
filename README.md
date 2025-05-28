# irandom

- added "ichoices" which returns an iterator.
- added "isample" which returns an iterator.
- added "ishuffle which returns an iterator and modifies a list in place.

```
PS C:\Users\kevin\source\code\irandom> python .\irandom.py
isample: first item latency: 3.337860107421875e-05; n=1099511627776; k=1048576
sample: first item latency: 0.5933218002319336; n=1099511627776; k=1048576
old_sample: first item latency: 0.5317442417144775; n=1099511627776; k=1048576

isample: list latency: 0.5926382541656494; n=1099511627776; k=1048576
sample: list latency: 0.5789961814880371; n=1099511627776; k=1048576
old sample: list latency: 0.4994783401489258; n=1099511627776; k=1048576

ichoices: first item latency: 0.020250558853149414; n=1099511627776; k=1048576
choices: first item latency: 0.17171907424926758; n=1099511627776; k=1048576
old choices: first item latency: 0.15145301818847656; n=1099511627776; k=1048576

ichoices: list latency: 0.17704176902770996; n=1099511627776; k=1048576
choices: list latency: 0.18131470680236816; n=1099511627776; k=1048576
old choices: list latency: 0.1496579647064209; n=1099511627776; k=1048576

ishuffle: first item latency: 0.2124156951904297; n=16777216
shuffle: first item latency: 9.283416271209717; n=16777216
old shuffle: first item latency: 9.110907316207886; n=16777216

ishuffle: list latency: 9.97104001045227; n=16777216
shuffle: list latency: 10.27851128578186; n=16777216
old shuffle: list latency: 10.571462154388428; n=16777216
```
