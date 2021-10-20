Running the project

1. `npm install`
2. `deno upgrade --canary`
2. Checkout https://github.com/denoland/deno_std/pull/1435 locally
3. `export DENO_NODE_COMPAT_URL=file:///path/to/deno_std/`
4. `deno run --compat --unstable -A --no-check ./node_modules/vite/bin/vite.js --host 127.0.0.1 --port 8080 --debug`