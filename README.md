# mlflow-oas3
This repository contains the OpenAPI Specification (OAS) 3.0 that describes MLFlow APIs. The specification is retrieved from [this commit](https://github.com/mlflow/mlflow/blob/c0d719a9e43ad15acd84e1b5d4126ef6a81963e9/docs/source/openapi.yml)  but has been adapted with the addition of these lines:

``` yaml
servers:
- url: http://server-url:server-port
```
You need to modify these lines according to your MLFlow server IP addresses.