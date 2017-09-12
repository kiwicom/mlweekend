# Entry task story

Since this summer was kind of boring, you have applied for one temporary contract on dark web. It turned out that you are the only data scientist in the team, the others are mostly hackers doing industrial espionage. Long story short -- after some work on their side they gave you a VPN access to some factory in Kazakhstan to enable you to call endpoint to one of the machines where a secret mathematical formula is hidden. You goal is to get the formula.
Unfortunately the machine works like a black box -- you can just send a _x_-value to it

`/api/do_measurement?x=4` (the IP will be specified in e-mail)

to measure the _y_-value within the resulted JSON

`{"data": {"y": 188.58938971580736, "x": 4.0}}`

Also it looks like that the machine is just a working prototype so the readings are a bit fuzzy and it is probably a good idea to do more measurements to get some reasonable data. Also for some intervals of _x_, the _y_-values are missing; feel free to interpolate.

Your task is do the measurements, get the secret formula _f_ where _y = f(x)_ and send it to the organisers (with a graph included). Also, use Numpy please and attach all the code you have used.
