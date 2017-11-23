## eCommerce Business

```javascript
// Department and product
{
  departmentId: Number,
  name: String,
  products: [
    {
      productId: Number,
      name: String,
      price: Number,
      stock: Number
    }
  ]
},
// Transaction
{
  transactionId: Number,
  time: Datetime
  products: [
    {
      productId: Number,
      quantity: Number
      price: Number
    }
  ]
}
// Index table for Transactions
// Dates   | Transaction IDs
Date: [transactionId, transactionId, ...]
Date: [transactionId, transactionId, ...]
Date: [transactionId, transactionId, ...]
```
