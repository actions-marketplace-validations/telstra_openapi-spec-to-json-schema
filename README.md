# openapi spec to json schema

This action retrieves a validated openapi specification file from a user provided origin and returns a generated json schema file

## Inputs

### `specification-url`

**Required** The openapi specification origin url.

## Outputs

### `json-schema-file`

The json schema file.

## Example usage

```yml
uses: telstra/openapi-spec-to-json-schema@v1.0.0
with:
  specification-url: 'https://dev.telstra.com/sites/default/files/redocs/1620871323/messaging-api-swagger_0.yaml'
```
