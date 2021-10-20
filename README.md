Running the project

1. `npm install`
2. Checkout https://github.com/denoland/deno_std/pull/1435 locally
3. Build `deno` locally, and change `cli/compat/mod.rs:17` to a file URL pointing to the checked out branch from no 2.
4. `target/debug/deno run --compat --unstable -A --no-check ./node_modules/vite/bin/vite.js --host 127.0.0.1 --port 8080 --debug`