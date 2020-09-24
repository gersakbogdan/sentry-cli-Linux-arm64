# Sentry-cli for Linux-arm64

sentry-cli for Linux arm64 compiled from source (https://github.com/getsentry/sentry-cli)

## Installation

### Node

To install the binary via npm you need to set the `sentrycli_cdnurl`property.

#### Method 1

```sh
npm install @sentry/cli --sentrycli_cdnurl=https://github.com/gersakbogdan/sentry-cli-Linux-arm64/raw/master
```

#### Method 2

Add property into your `.npmrc` file (https://www.npmjs.org/doc/files/npmrc.html)

```rc
sentrycli_cdnurl=https://github.com/gersakbogdan/sentry-cli-Linux-arm64/raw/master
```

#### Method 3

Another option is to use the environment variable `SENTRYCLI_CDNURL`.

```sh
SENTRYCLI_CDNURL=https://github.com/gersakbogdan/sentry-cli-Linux-arm64/raw/master npm install @sentry/cli
```
