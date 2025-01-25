```mermaid
erDiagram
   CUSTOMER ||--|{ PRODUCT : chooses
    CUSTOMER {
        string Address
        string Name
        string Email
    }
    PRODUCT |{--|| SALE : becomes
    PRODUCT {
        string ProductID
    }
    SALE ||--|{ INVENTORY : alerts
    INVENTORY |{--|| CUSTOMER : "goes to"
```

<p> My Paragraph <p>