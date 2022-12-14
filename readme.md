# TAOP89 Lab 5
https://courses.mai.liu.se/GU/TAOP89/Lab/lab-45-i.pdf
## Greedy Exponential Weighted Mean (best)
| Test 	| Optimum (Y) 	| Herustic (Y) 	| % 	| Time 	|
|---	|---	|---	|---	|---	|
| floc1 	| 3880 (2) 	| 3880 (2) 	| 0 	| 0.0002 	|
| floc2 	| 15252 (7) 	| 17070 (9) 	| 0.1192 	| 0.0004 	|
| floc3 	| 244101 (3) 	| 273930 (1) 	| 0.1222 	| 0.0004 	|
| floc4 	| 118802 (9) 	| 124588 (10) 	| 0.0487 	| 0.0006 	|
| floc5 	| 141630 (10) 	| 143796 (10) 	| 0.0153 	| 0.0009 	|
| floc6 	| 106668 (12) 	| 111333 (20) 	| 0.0437 	| 0.0019 	|
| floc7 	| 174760 (11) 	| 187096 (30) 	| 0.0706 	| 0.0036 	|
| floc8 	| 314657 (30) 	| 314657 (30) 	| 0 	| 0.0051 	|

### Changing E (cost to build)
| E (floc3)    | Optimum (Y) | Herustic (Y) | %    |
|------|-------------|--------------|------|
| 0.01 | 73741 (9)   | 74156 (10)   | 5.6  |
| 0.1  | 108832 (9)  | 116251 (7)   | 6.8  |
| 1    | 244101 (3)  | 273930 (1)   | 12.2 |
| 10   | 601739 (1)  | 727530 (1)   | 20.9 |
| 100  | 3391739 (1) | 5263530 (1)  | 55.2 |

## Greedy Least Amount (first, not as good)
| Test  | Optimum     | Herustic    | %      | Time   |
|-------|-------------|-------------|--------|--------|
| floc1 | 3880 (2)    | 3880 (2)    |      0 |      0 |
| floc2 | 15252 (7)   | 16354 (7)   | 0.0723 |      0 |
| floc3 | 244101 (3)  | 273930 (1)  | 0.1222 |  0.001 |
| floc4 | 118802 (9)  | 203127 (3)  | 0.7098 |      0 |
| floc5 | 141630 (10) | 193607 (7)  |  0.367 |  0.001 |
| floc6 | 106668 (12) | 174217 (6)  | 0.6333 |  0.002 |
| floc7 | 174760 (11) | 519655 (5)  | 1.9735 |  0.005 |
| floc8 | 314657 (30) | 788494 (11) | 1.5059 | 0.0075 |

## Greedy Weigthed Mean (factor=1)
| Test  | Optimum     | Herustic    | %      | Time  |
|-------|-------------|-------------|--------|-------|
| floc1 | 3880 (2)    | 3880 (2)    |      0 |     0 |
| floc2 | 15252 (7)   | 16354 (7)   | 0.0723 |     0 |
| floc3 | 244101 (3)  | 273930 (1)  | 0.1222 |     0 |
| floc4 | 118802 (9)  | 168342 (4)  |  0.417 | 0.001 |
| floc5 | 141630 (10) | 143796 (10) | 0.0153 | 0.001 |
| floc6 | 106668 (12) | 113432 (11) | 0.0634 | 0.002 |
| floc7 | 174760 (11) | 348719 (10) | 0.9954 | 0.005 |
| floc8 | 314657 (30) | 597737 (14) | 0.8996 | 0.008 |