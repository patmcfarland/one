```mermaid
flowchart TB
A[Blockchain Data<br>Customer<br>-Person-] -->B{Blockchain Data<br>System<br>-Software System-}
B -- Gets account<br>information from and<br>makes payments using --> C{Quit or enter<br>temperature number} 
C -- Temperature Number --> D[Temperature successfully<br>converted!] 
D -- Start Again -->B
B -- Quit --> E[Stop Program]
C -- Quit --> E
```
