## Queries

```
query {
  client(id: "{id}") {
    id
    name
    age
  }
}

query {
  documents(id: "{id}") {
    id
    type
    number
    issueDate
    expiryDate
  }
}

query {
  relatives(id: "{id}") {
    id
    relationType
    name
    age
  }
}
```