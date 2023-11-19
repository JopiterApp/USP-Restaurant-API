# USP-Restaurant-API

## Access
Access API specifications through [bump.sh](https://bump.sh/doc/USPRestaurantsAPI) (prettiest one)

Or through an alternative. Some alternatives from [OpenAPI.tools](https://openapi.tools):

- [MrinDoc](https://mrin9.github.io/OpenAPI-Viewer/#/load/https%3A%2F%2Fraw.githubusercontent.com%2FJopiterApp%2FUSP-Restaurant-API%2Fmain%2Fopenapi.yaml)
- [Redoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/JopiterApp/USP-Restaurant-API/main/openapi.yaml)


## Generating the API

Using [Redocly CLI](https://redocly.com/docs/cli/installation/) run 

- redocly bundle openapi/openapi.yaml --lint -o openapi.yaml 
- redocly bundle openapi/openapi.yaml --lint -o openapi.json