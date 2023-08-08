# Simple API

Simple HTTP API for playing with `User` model.


## Files

### `models/`
- `user.py`: user model

### `api/v1`

- `app.py`: entry point of the API


## Setup

```
$ pip3 install -r requirements.txt
```


## Run

```
$ API_HOST=0.0.0.0 API_PORT=5000 python3 -m api.v1.app
```


## Routes

- `GET /api/v1/status`: returns the status of the API

