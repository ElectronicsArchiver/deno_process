[![Build Status](https://github.com/axetroy/deno_process/workflows/test/badge.svg)](https://github.com/axetroy/deno_process/actions)

### process module for Deno

Features:

- [x] Cross platform support
- [x] kill
- [x] get
- [x] getAll
- [x] getTree

### Usage

```typescript
import {
  get,
  getAll,
  getTree,
  kill
} from "https://github.com/axetroy/deno_process/raw/master/mod.ts";

console.log(await get(1)); // get process info with pid
console.log(await getAll()); // get all process list
console.log(await getTree()); // get process tree
await kill(1024); // kill process by pid
await kill("deno"); // kill process by name
```

## License

The [MIT License](LICENSE)
