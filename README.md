```mermaid
flowchart LR
A[Blockchain Data<br>Customer<br>{Person}] -->B{Blockchain Data<br>System}
B -- Temperature Scale --> C{Quit or enter<br>temperature number} 
C -- Temperature Number --> D[Temperature successfully<br>converted!] 
D -- Start Again -->B
B -- Quit --> E[Stop Program]
C -- Quit --> E
```
