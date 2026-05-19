# Bob & Kafka Playground

This repo is an environment to explore Bob and with Confluent AI capabilities. 

It contains a Bob MCP configuration against a locally running MCP Confluent 
server that access a local CP deployment
(based on [cp-all-in-one](https://github.com/confluentinc/cp-all-in-one))

Check .bob/mcp.json for the Bob MCP configuration.


## Confluent AI Capabilities

- https://github.com/confluentinc/mcp-confluent
- https://github.com/confluentinc/agent-skills


## Running CP Services

```
cd cp-all-in-one
docker compose up -d
```

## Examples

### Listing and registering schemas

![image](/screenshots/registering_schema.png)

## License

Apache 2.0


## Author

Matías Cascallares
