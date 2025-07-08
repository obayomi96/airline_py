# airline_py

### routes

- `/users/`
  `/login/`
  `/logout/`
- `/flights/`
  `<int:flight_id>`
  `<int:flight_id>/book`
- `/admin/`


### N/B

- Use `os` from python, for environment variables if needed
- Install `gunicorn` for deploy capability
- Be sure to freeze `requirements` before deploy or versioning
