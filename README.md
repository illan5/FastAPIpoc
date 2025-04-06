
<img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" alt="Fast API logo" width="400"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/800px-Python-logo-notext.svg.png" alt="Logo python" width="100"><img src="https://www.uvicorn.org/uvicorn.png" alt="Logo python" width="120">


## Fast API POC: Building Python web API

### Description
Testing basic Fast API functionality, using Uvicorn to run locally the HTTP server.

##### Versions:

`fastapi           0.115.12`
`uvicorn           0.34.0`

### Usage
```
$ uvicorn main:app --reload
```
Main endpoint: `http://127.0.0.1:8000`

#### Interactive API documentation (Swagger UI)
`http://127.0.0.1:8000/docs`

<img src="FastApi-SwaggerUI.png" alt="Swagger UI" width="500">


#### Alternative interactive API documentation (Redoc)
`http://127.0.0.1:8000/redoc`

<img src="FastAPI-Redoc.png" alt="Redoc" width="500">


### Reference
https://realpython.com/fastapi-python-web-apis/