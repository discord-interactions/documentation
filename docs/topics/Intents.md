# Intents

## Enable Intents
Please add the intents your bot actually needs to operate.

Gateway intents list on the [Discord API Documentation](https://discord.com/developers/docs/topics/gateway#gateway-intents). 

```js
const client = new Client({ intents: ['GUILD_CREATE', 'MESSAGE_CREATE'] })
```
