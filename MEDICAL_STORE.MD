# 🏪 Medical Store Module

This module covers the store-side flow: receiving orders, checking stock, and delivering medicines.

## 📊 Store Order Flow

```mermaid
flowchart TD
    Z[STORE] --> A[Register Store on App]
    A --> B[Order Received]
    B --> C{Medicine Found?}

    C -- Yes --> D[Generate Order]
    C -- No --> X[Medicine Not Available]

    D --> E[Supplier Sets Medicine Validity]
    E --> F[Hand Over to Rider]
    F --> G[Order Delivered ✅]
```

## 🔗 Navigation

- ➡️ [Go to Prescriptor Module](PRESCRIPTOR.md)
- 🔐 [Go to Login](LOGIN.md)
- 🏠 [Back to Home](README.md)