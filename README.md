# SQLAlchemy-Paginatioin
The pagination implementation for SQLAlchemy (Python3)

example of use:

```
query = session.query(cls)

data_paginated = paginate(query=query, page=page, page_size=20)
```
