```mermaid
erDiagram
   CUSTOMER ||--|{ PRODUCT : chooses
    CUSTOMER {
        string Address
        string Name
        string Email
    }
    PRODUCT {
        string ProductID
    }
    PRODUCT ||--|{ INVENTORY
    INVENTORY {

    }
    SALE {

    }
```