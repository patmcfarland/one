```mermaid
flowchart TD
A[Gets JSON files<br>-Extract Process-]
A -- from blockchain<br>data provider --> B
B[TenderMint Folder<br>-Directory-]
B -- = 100 JSON files --> C[Update Folder<br>-Directory-]
B -- < 100 JSON files --> A
C -- files are formatted --> D
D[Break files into pieces<br>-Translate Process-]
C -- files are not formatted --> E
E[Error Log<br>-File-]
F[Postgres Database<br>-Load Process-]
D -- files contain transactions --> F
D -- files do not contain transactions --> G
G[empty log<br>-File-]
```
