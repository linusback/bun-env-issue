# bun-env-issue

Repository to recreate the bug mentioned in bun issue 9635
[https://github.com/oven-sh/bun/issues/9635](https://github.com/oven-sh/bun/issues/9635)

Requires docker to easily test both versions of bun.
If docker-compose is installed versions can be run like this.

Run broken version

```docker-compose up --build broken```

Run working version

```docker-compose up --build working```