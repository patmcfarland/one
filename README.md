```mermaid
flowchart TD
A[Extract<br>-Process-]
A -- Gets JSON file<br>from blockchain<br>data provider --> B
B{tendermint<br>-Directory-}
B -- Quit --> C[Stop Program]
```
