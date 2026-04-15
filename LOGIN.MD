# 🔐 Login Module

This module handles authentication for both **Customers** and **Suppliers**.

## 📊 Login Flow

```mermaid
flowchart TD
    Z[APP OPEN] --> A{Who are you?}

    A --> B[Customer]
    A --> F[Supplier]

    B -->|New User| C[Sign Up]
    B -->|Returning User| D[Login Page]

    F -->|New User| G[Sign Up]
    F -->|Returning User| H[Login Page]

    C --> I[Register with Email]
    C --> J[Register with Phone]

    G --> L[Register with Phone]

    D --> K[Login: Phone + Password]
    H --> M[Login: Phone + Password]

    K --> N[Open Prescriptor]
    M --> O[Open Medical Store]
```

## 🔗 Navigation

- ➡️ [Go to Prescriptor Module](PRESCRIPTOR.md)
- ➡️ [Go to Medical Store Module](MEDICAL_STORE.md)
- 🏠 [Back to Home](README.md)