# Fork of filestack-js

## Repo Setup Steps

```sh
git clone https://github.com/filestack/filestack-js
cd filestack-js
git checkout v3.26.1
```

## Changes made

<!-- git log ...v3.26.1 --reverse --format='1. [%s](https://github.com/danthegoodman/filestack-js/commit/%H)' -->

1. [package.json: update version](https://github.com/danthegoodman/filestack-js/commit/7c22a7a498f3c9e4d012bdaa66c9866496e27a7d)
1. [src/lib/client.ts: Remove usages of @sentry/minimal](https://github.com/danthegoodman/filestack-js/commit/a3bab7ddad9304f4e9f6999a290772a9d855996b)
1. [package.json: remove unused dependencies](https://github.com/danthegoodman/filestack-js/commit/91b877cac110f4570ca9796f3d4b73b7bc79421e)
1. [package.json: remove script triggering autobuild on install and pack](https://github.com/danthegoodman/filestack-js/commit/0ccecf1e9be78c421684a9d052831f18f8042e85)

## Build Steps

```sh
nvm use v14.21.3
npm install
npm run build
npm pack
```
