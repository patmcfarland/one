```mermaid
flowchart TD
A[Extract<br>-Process-] -->B{tendermint<br>-Directory-}
A -- Gets JSON file<br>from blockchair data provider --> B{Mainframe Blockchain<br>System<br>-Software System-} 
C -- Temperature Number --> D[Temperature successfully<br>converted!] 
D -- Start Again -->B
B -- Quit --> E[Stop Program]
C -- Quit --> E
```
