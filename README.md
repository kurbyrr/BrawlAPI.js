# brawlapi.js

NodeJS API wrapper for https://brawlapi.com

# Usage

```js
import { Client } from "brawlapi";
const client = new Client();
const main = async () => {
  const maps = await client.getMaps();
  console.log(maps);
};
main();
```
