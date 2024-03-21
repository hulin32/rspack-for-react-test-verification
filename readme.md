## How to test manifest

1. git pull https://github.com/flyingalex/rspack to your local
2. run `cargo build` to build it
3. then go to this project, change `@rspack/core` path to your local rspack root
4. run `pnpm i`
5. run `pnpm run build`
6. check manifest.json in dist folder
