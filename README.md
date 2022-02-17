# F1 Fantasy API

The documentation is available on this page. The [Github is available here](https://github.com/zeroclutch/f1-fantasy-api). The [Discord is available here](https://discord.gg/bAMc7yNfnA).

### Get started

You can get started by looking at the `Client` under the classes dropdown. This will be your entrypoint into the API.

### Example

```js
const { Client } = require('./src/index.js')

const client = new Client( /* options */ )
client.init()
.then(() => {
    console.log(client.grandsPrix.get('Imola'))
})
```

### Help us out

This is all very much a work in progress, we'd love for you to join us and contribute!