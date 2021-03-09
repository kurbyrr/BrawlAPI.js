# brawlapi.js

NodeJS API wrapper for https://brawlapi.com

# Installation

```
npm i brawlapi.js
```

```
yarn add brawlapi.js
```

# Usage

```js
import { Client } from "brawlapi.js";
const client = new Client();
const main = async () => {
  const maps = await client.getMaps();
  console.log(maps);
};
main();
```
