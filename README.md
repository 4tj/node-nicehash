# node-nicehash
> [nicehash.com](https://www.nicehash.com/docs) nodejs api client

I only abstracted some of my commonly used APIs. If there is a need for support, I will welcome issue feedback and I will add it, and PR is very welcome

### Installation
```bash
npm install node-nicehash
```

### Getting started
```javascript
import Nicehash from 'node-nicehash'

const client = Nicehash()

const client2 = Nicehash({
  timeout: 5000 // http request timeout
})

client.account().then(data => console.log(data))
```
