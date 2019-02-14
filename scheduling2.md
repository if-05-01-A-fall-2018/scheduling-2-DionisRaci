## 1

The process needs to be swapped in 5 times, until it runs at all.

| Run | 1 | 2 | 3 | 4 | 5 |
| -- | -- | -- | -- | -- | -- |
Q | 1 | 2 | 4 | 8 | 15 |
Acc | 1 | 3 | 7 | 15 | 30 |

## 2

From the fromula: E3 = T/8 + T1/8 + T2/4 + T3/2  
we can Find that process B comes first since it takes lower time until it runs

A: 50/8 + 150/8 + 300/4 + 85/2 = 142,5  
B: 300/8 + 150/8 + 85/4 + 50/2 = 102,5

## 3

CPU bound processes don't need any user interaction so the processes progress is limited by the CPU.  
So they needs high quanta but low priority.

I/O bound processes are dependant on the user input.
So they need low quanta but high priority to respond immediately on the users reaction.
