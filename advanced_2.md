## Social Media Site Activity Feed

```javascript
// User
{
  userId: Number,
  username: String,
  password: String,
  profile: {
    email: String,
    firstName: String,
    lastName: String,
    aboutMe: String
  },
  frequentFriendsIds: [userId, userId, ...],
  feed: [
    {
      itemId: Number,
      time: Datetime
    }
  ]
},
// Feed items
{
  itemId: Number,
  content: {
    userId: Number,
    activity: String,
  }
}
```
