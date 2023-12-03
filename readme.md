Objective:

- Create a web application to divulgation products

FrameWorks:

- Ruby backend  -v 3.2.2
- Rails front   -v 7.0.8
- PostgreSQL
- Heroku

---

Complements:
- Ruby
  - Manage Database
  - connect DB data with FRONT

- Rails
  - Create the server
  - Management of routes
  - Views

- PostgreSQL
  - Insert the code in https://dbdiagram.io/d
  ```
  Table products {
    id int [PK]
    name string
    description string
    price double
    avatar string
    category_id int [ref: > categories.id]
    created_at datetime
    updated_at datetime
  }

  Table categories {
    id int [PK]
    name string
    description string
    created_at datetime
    updated_at datetime
  }
  ```

- Heroku

  - Environments versioning
  - Application publication
---
- Steps

  - Install programs and gems
  - Create the project
  - Add migrations
  - Add routes