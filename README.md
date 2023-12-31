# TIS-100 Saves

[Get the game](https://www.zachtronics.com/tis-100/)

## Common Labels

* `S` Main loop start
* `L` Inner loop
* `T` Main test
* `N` Next step, a pre-condition suceeded
* `C` “Continue”, branch convergence
* `F` Final instructions

## TIS-100 Segments

> **Note**
> Statistics listed as “Cycles / Nodes / Instructions”


### 00150 Self-Test Diagnostic
**Best** — 83 / 8 / 8  
[Program 0](save/00150.0.txt) — 83 / 8 / 8 — “TRIVIAL”    
[Program 1](save/00150.1.txt) — 100001 / 8 / 22 — “EXACT 100001 CYC”    

### 10981 Signal Amplifier
**Best** — 84 / 4 / 6  
[Program 0](save/10981.0.txt) — 160 / 4 / 6 — “OBVIOUS”    
[Program 1](save/10981.1.txt) — 84 / 6 / 11 — “PARALLEL”    

### 20176 Differential Converter
**Best** — 203 / 5 / 10  
[Program 0](save/20176.0.txt) — 433 / 5 / 15  
[Program 1](save/20176.1.txt) — 203 / 5 / 11  

### 21340 Signal Comparator
**Best** — 278 / 6 / 20  
[Program 0](save/21340.0.txt) — 278 / 6 / 20 — “JUMPY VERSION”    
[Program 1](save/21340.1.txt) — 325 / 6 / 32 — “UNCODITIONAL”    

### 22280 Signal Multiplexer
**Best** — 265 / 5 / 16  
[Program 0](save/22280.0.txt) — 265 / 5 / 16  

### 30647 Sequence Generator
**Best** — 106 / 4 / 17  
[Program 0](save/30647.0.txt) — 131 / 4 / 18 — “BAK-FUL”    
[Program 1](save/30647.1.txt) — 106 / 5 / 18 — “SAV-LESS”    

### 31904 Sequence Counter
**Best** — 260 / 5 / 27  
[Program 0](save/31904.0.txt) — 260 / 6 / 29 — “CLASSIC”    
[Program 1](save/31904.1.txt) — 277 / 8 / 27 — “NO BACKUP”    
[Program 2](save/31904.2.txt) — 288 / 5 / 27 — “CLASIC+LESS NODE”    

### 32050 Signal Edge Detector
**Best** — 272 / 4 / 15  
[Program 0](save/32050.0.txt) — 272 / 4 / 15  

### 33762 Interrupt Handler
**Best** — 169 / 9 / 43  
[Program 0](save/33762.0.txt) — 277 / 9 / 43 — “FIRST CRACK”    
[Program 1](save/33762.1.txt) — 169 / 10 / 44 — “FEWER CYCLES”    

### 40196 Signal Pattern Detector
**Best** — 174 / 4 / 14  
[Program 0](save/40196.0.txt) — 331 / 4 / 15 — “COUNTER”    
[Program 1](save/40196.1.txt) — 313 / 8 / 25 — “DELAY CHAIN”    
[Program 2](save/40196.2.txt) — 174 / 4 / 14 — “STATE MACHINE”    

### 41427 Sequence Peak Decetor
**Best** — 295 / 5 / 38  
[Program 0](save/41427.0.txt) — 295 / 7 / 41 — “FAST”    
[Program 1](save/41427.1.txt) — 461 / 5 / 38 — “MIN NODES”    

### 42656 Sequence Reverser
**Best** — 343 / 3 / 10  
[Program 0](save/42656.0.txt) — 416 / 4 / 18 — “SEP READ & WRITE”    
[Program 1](save/42656.1.txt) — 343 / 3 / 10 — “SINGLE NODE”    

### 43786 Signal Multiplier
**Best** — 1635 / 5 / 26  
[Program 0](save/43786.0.txt) — 2206 / 5 / 26 — “STACKLESS SOLN”    
[Program 1](save/43786.1.txt) — 1635 / 5 / 40 — “PRE-SORT A AND B”    

### 50370 Image Test Pattern 1
**Best** — 2282 / 2 / 9  
[Program 0](save/50370.0.txt) — 2282 / 2 / 9  

### 51781 Image Test Pattern 2
**Best** — 1733 / 2 / 14  
[Program 0](save/51781.0.txt) — 1733 / 3 / 15  

### 52544 Exposure Mask Viewer
**Best** — 1079 / 6 / 52  
[Program 0](save/52544.0.txt) — 1079 / 6 / 52 — “UNROLLED”    

### 53897 Histogram Viewer
**Best** — 2587 / 4 / 18  
[Program 0](save/53897.0.txt) — 3696 / 4 / 18 — “FEW INSTS”    
[Program 1](save/53897.1.txt) — 2587 / 5 / 25 — “MINDLESS OUTPUT”    
[Program 2](save/53897.2.txt) — 3139 / 4 / 20 — “JRO POWER”    

### 60099 Signal Window Filter
**Best** — 1059 / 6 / 35  
[Program 0](save/60099.0.txt) — 1059 / 6 / 35 — “SIMPLE ONE”    

### 61212 Signal Divider
**Best** — 6377 / 6 / 31  
[Program 0](save/61212.0.txt) — 6377 / 6 / 31 — “WORKS”    

### 62711 Sequence Indexer
**Best** — 1042 / 6 / 27  
[Program 0](save/62711.0.txt) — 2521 / 6 / 27 — “RESET BTWN IXS”    
[Program 1](save/62711.1.txt) — 1042 / 6 / 37 — “MUCH SMARTER”    
[Program 2](save/62711.2.txt) — 1062 / 6 / 31 — “COMPROMISE”    

### 63534 Sequence Sorter
**Best** — 2648 / 6 / 64  
[Program 0](save/63534.0.txt) — 2648 / 6 / 64 — “CHEATER”    
[Program 1](save/63534.1.txt) — 2714 / 6 / 64 — “DON'T ASK HOW”    

### 70601 Stored Image Decoder
**Best** — 6551 / 6 / 32  
[Program 0](save/70601.0.txt) — 6551 / 6 / 32 — “WAY TOO SIMPLE”    

### UNKNOWN Illegal Eagle
**Best** — 620 / 5 / 45  
[Program 0](save/UNKNOWN.0.txt) — 620 / 5 / 45  

## TIS-NET Segments

### NEXUS.01.526.6 Sequence Merger
**To Be Solved**

### NEXUS.01.874.8 Integer Series Calcuator
**Best** — 6035 / 3 / 12  
[Program 0](save/NEXUS.01.874.8.0.txt) — 6035 / 3 / 12 — “NAIVE”    
[Program 1](save/NEXUS.01.874.8.1.txt) — Incomplete — “PRE-COMPUTED”    

### NEXUS.02.981.2 Sequence Range Limiter
**To Be Solved**

### NEXUS.03.176.9 Signal Error Corrector
**To Be Solved**

### NEXUS.04.340.5 Subsequence Extractor
**To Be Solved**
