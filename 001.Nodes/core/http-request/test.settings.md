# Sample Api
 
| Purpose                   | Endpoint                                      |
| ------------------------- | --------------------------------------------- |
| List of users (customers) | `https://dummyjson.com/users`                 |
| Single user               | `https://dummyjson.com/users/1`               |
| Search users              | `https://dummyjson.com/users/search?q=john`   |
| Paginated users           | `https://dummyjson.com/users?limit=10&skip=0` |

### Example 1: List of Customers

```http
GET https://dummyjson.com/users
```

Response (truncated):

```json
{
  "users": [
    {
      "id": 1,
      "firstName": "Emily",
      "lastName": "Johnson",
      "email": "emily.johnson@x.dummyjson.com",
      "phone": "+81 965-431-3024",
      "company": {
        "name": "Dooley, Kozey and Cronin"
      }
    }
  ],
  "total": 208,
  "skip": 0,
  "limit": 30
}
```

---

### Example 2: Single Customer

```http
GET https://dummyjson.com/users/1
```

Response:

```json
{
  "id": 1,
  "firstName": "Emily",
  "lastName": "Johnson",
  "email": "emily.johnson@x.dummyjson.com",
  "phone": "+81 965-431-3024",
  "company": {
    "name": "Dooley, Kozey and Cronin"
  }
}
```

---

## Alternative APIs

### JSONPlaceholder

List:

```http
GET https://jsonplaceholder.typicode.com/users
```

Single:

```http
GET https://jsonplaceholder.typicode.com/users/1
```

---

### Random User API

One customer:

```http
GET https://randomuser.me/api/
```

Ten customers:

```http
GET https://randomuser.me/api/?results=10
```

---

### ReqRes

List:

```http
GET https://reqres.in/api/users?page=1
```

Single:

```http
GET https://reqres.in/api/users/2
```
 