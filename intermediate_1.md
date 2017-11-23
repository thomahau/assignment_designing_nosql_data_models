## Restaurant Table Reserving App

```javascript
// Table
{
  tableId: Number,
  seats: Number
},
// Reservation
{
  name: String,
  phone: Number,
  guests: Number,
  time: Datetime,
  tableId: Number
}
// Index table of reservations
// Datetime   | Table IDs
Datetime: [tableId, tableId, ...]
Datetime: [tableId, tableId, ...]
```
