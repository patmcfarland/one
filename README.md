```mermaid
flowchart TB
A[Blockchain Data<br>Customer<br>-Person-] -->B{Blockchain Data<br>System<br>-Software System-}
B -- Gets account<br>information from and<br>makes payments using --> C{Mainframe Blockchain<br>System} 
C -- Temperature Number --> D[Temperature successfully<br>converted!] 
D -- Start Again -->B
B -- Quit --> E[Stop Program]
C -- Quit --> E
```
