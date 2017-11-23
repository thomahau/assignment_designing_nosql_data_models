## User Login

```javascript
// User
{
  username: String,
  password: String,
  profile: {
    aboutMe: String,
    birthday: {
      value: Date,
      visibility: Boolean
    },
    gender: {
      value: String,
      visibility: Boolean
    },
    phone: {
      value: Number,
      visibility: Boolean
    },
    location: {
      value: {
        city: String,
        state: String,
        country: String
      },
      visibility: Boolean
    }
  }
}
```
