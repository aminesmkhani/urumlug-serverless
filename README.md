
# UrumLug - ServerLess Episode Codes
![Cloudflare Worker](https://camo.githubusercontent.com/dbfce91befb9e3595169aab72f1307a504559b7acc255ba911a0e170b927c485/68747470733a2f2f6465706c6f792e776f726b6572732e636c6f7564666c6172652e636f6d2f627574746f6e)

## Acknowledgements

 - [CloudFlare Workers](https://workers.cloudflare.com/)
 - [Telegram Bot](https://core.telegram.org/bots/api)
 - [Video and toturial](https://youtu.be/OZEu0bPX8gA)


## Reference

### urlshortnerBot

```http
  GET /configure-webhook
  # For Configure Bot Webhook
```

| KV | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `URL_List` | `string` | **Required**. Your Bind key |

| Bot Key | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `telegramAuthToken` | `string` | **Required**. Your Telegram Botfather bot key |


### urluploader

```http
  GET /configure-webhook
  # For Configure Bot Webhook
```

| Bot Key | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `telegramAuthToken` | `string` | **Required**. Your Telegram Botfather bot key |


### translateBot

```http
  GET /configure-webhook
  # For Configure Bot Webhook
```

| Bot Key | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `telegramAuthToken` | `string` | **Required**. Your Telegram Botfather bot key |


| Traslate AppBinding | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `translateService` | `string` | **Required**. Your Bind key |


### vWorker (Depricated)


| KV Namespace | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `vpKv` | `string` | **Required**. Set settings KV Binding Worker|





## Authors

- [@aminesmkhani](https://www.github.com/octokatherine)
- [@vfarid(vWorker)](https://www.github.com/vfarid)

