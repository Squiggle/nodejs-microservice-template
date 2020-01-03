# Microservice template

## Prerequisites

OpenAPI Generator

`npm install @openapitools/openapi-generator-cli -g`

## Generating

```
npx openapi-generator generate -i spec.yml -g nodejs-express-server -o src -c config.json
```