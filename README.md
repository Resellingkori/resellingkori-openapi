# ResellingKori OpenAPI Specification

[ResellingKori Partner API](https://github.com/Resellingkori/partner-docs) described in OpenAPI 3.1.

Use it with API explorers, code generators, and contract testing tools.

## Files

| File | Use |
|---|---|
| `resellingkori-partner-api.openapi.yaml` | Human-readable, easier to edit |
| `resellingkori-partner-api.openapi.json` | Machine-readable, for code generators |

## View in browser

Go to **[editor.swagger.io](https://editor.swagger.io)** → File → Import File → select the `.yaml` file.

## Generate a client

```bash
# Install: https://openapi-generator.tech
openapi-generator-cli generate \
  -i resellingkori-partner-api.openapi.yaml \
  -g php \
  -o ./generated-client

# Other generators: python, typescript-axios, java, ruby, go, dart, swift6 ...
```

## API version

Revision **3.1** · Signing **RK2** · Order schema **2** · Currency **BDT**

## Documentation

- [Getting Started](https://github.com/Resellingkori/partner-docs/blob/main/GETTING_STARTED.md)
- [Full API Guide](https://github.com/Resellingkori/partner-docs/blob/main/PARTNER_API_GUIDE.md)
