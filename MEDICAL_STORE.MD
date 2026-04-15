``` MERMAID
    flowchart TD
    Z[STORE]-->A[REGISTER STORE ON APP]
          A-->B[order recieved]
    B-->C[find medicine]
    C-->|yes|D[order generate]
    C-->|no|X[medicine not available]
    D-->E[SUPPLIER SET VALIDITY OF MEDICINE]
    E-->F[GIVE GROCERY TO THE RIDER]
    F-->G[ORDER DELEIVERED]
    ```
    [OPEN LOGIN](LOGIN.MD)
    