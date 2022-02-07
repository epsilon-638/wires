## Wires, a lang based on an Advent of Code problem
### Following along in https://beautifulracket.com
#### Problem: Each wire is identified by lowercase letters and can carry a 16 bit signal. Each wire can only recieve a signal from a single source. However, each wire can provide a signal to multiple other wires. Wires can be connected via bitwise logic gates, no gate provides signal until all of its inputs have a signal

```racket
#lang wires
x AND y -> d
x OR y -> e
x LSHIFT 2 -> f
y RSHIFT 2 -> g
NOT x -> h
NOT y -> i
```
### Output:
```racket
d: 72
e: 507
f: 492
g: 114
h: 65412
i: 65079
x: 123
y: 456
```
### Huge props to Matthew Butterick and his book Beautiful Racket. He portrays how solutions to problems can be elegantly solved by creating DSLs abiding in the language-oriented paradigm. 
