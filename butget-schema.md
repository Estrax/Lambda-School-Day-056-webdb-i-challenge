## Schema for creating the budget database

```sql
CREATE TABLE accounts (
    id     INTEGER PRIMARY KEY AUTOINCREMENT
                   NOT NULL
                   UNIQUE,
    name   STRING  NOT NULL
                   UNIQUE,
    budget NUMERIC NOT NULL
);
```