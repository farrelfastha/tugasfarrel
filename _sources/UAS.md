---
title: UAS

---

# UAS


### 1
$(P \to Q) \to (R \to S)$


| NO | P | Q | R | S | $(P \to Q)$ | $(R \to S)$ | $(P \to Q)\to(R \to S)$
|  - | - | - | - | - | ----------- | ----------- | --|
|  1 | F | T | T | T | T | T | T |
|  2 | F | T | T | T | T | T | T |
|  3 | F | T | T | F | T | F | T |
|  4 | T | T | F | F | T | T | T |
|  5 | T | F | F | F | F | T | T |
|  6 | F | T | F | T | T | T | T |
|  7 | T | T | T | F | T | F | F |
|  8 | T | T | T | T | T | T | T |

#
### 2 .
![image](https://hackmd.io/_uploads/BkWyYGNNyl.png)
#### a . hitung Closennes centrality  = 

| node | A | B | C | D | E | F | G |
| -    | - | - | - | - | - | - | - |
| G    | 3 | 4 | 3 | 2 | 1 | 3 | 0 |

$$
Cc(g) = \frac{7-1}{3+4+3+2+1+3} = 0,375
$$

#### b . beetwinnes centrality =

| node | A | B | C | D | E | F | G |
| -    | - | - | - | - | - | - | - |
| f    | 2 | 3 | 2 | 1 | 2 | 0 | 3 |

$$
C_b(f) = \frac{7-1}{((13-1)(13-2))/2}=\frac{6}{66}
$$