# generate-useragent-node
Simple useragents generator.
# How to install
```bash
npm i generate-useragent-node
```
# How to use
```node

import { userAgentFactory } from "../lib";
let seed: string = "username";
const useragent = userAgentFactory(seed);
console.log(useragent)
  ```
