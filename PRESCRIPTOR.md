# 💊 Prescriptor Module

This module allows patients to upload prescriptions and order medicines from online stores.

## 📊 Patient Order Flow

```mermaid
flowchart TD
    Z[PATIENT] --> A[Login to App]
    A --> B[Visit Online Store]
    B --> C[Select Store]
    C --> D[Upload Prescription]
    D --> E{Medicines Available?}

    E -- Yes --> F[Generate Bill]
    E -- No --> X[Medicine Not Available]

    F --> G[Set Reminder]
    G --> H[Confirm Order]
    H --> I[Deliver by Rider]
    I --> J[Set Medicine Validity]
    J --> K[Validity Alert]
    K --> L[Daily Medicine Reminder]
```

## 🔗 Navigation

- ➡️ [Go to Medical Store Module](MEDICAL_STORE.md)
- 🔐 [Back to Login](LOGIN.md)
- 🏠 [Back to Home](README.md)