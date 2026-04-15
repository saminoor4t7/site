```mermaid
flowchart TD
Z[APP OPEN] --> A[ASKED QUESTION]

A --> B[Customer]
A --> F[Supplier]

B -->|NEW USER| C[SIGN UP]
B -->|OLD USER| D[LOGIN PAGE]

F -->|NEW USER| G[SIGN UP]
F -->|OLD USER| H[LOGIN PAGE]

C --> I[WITH EMAIL]
C --> J[WITH PHONE]

D --> K[LOGIN WITH PHONE + PASSWORD]

G --> L[WITH PHONE]

H --> M[LOGIN WITH PHONE + PASSWORD]

K --> N[Open Prescripter File]
```
 [Open Prescripter](prescripter.md)

 
 [Open MEDICAL_STORE](MEDICAL_STORE.MD)