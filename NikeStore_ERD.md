```mermaid
erDiagram
   CUSTOMER ||--o{ ORDER : places
    CUSTOMER {
        string Address
        string Name
        string Email
    }
    PRODUCT {
        string ProductID
    }
    INVENTORY {

    }
    SALE {

    }
```