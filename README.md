# email-login-lookup

## Why?

https://twitter.com/patio11/status/665946396155969536
https://twitter.com/patio11/status/665946548472168449

## How?

```bash
npm install
npm run debug
```

## Usage

> http://localhost:8888/?email=patrick@porch.com
```json
"https://login.microsoftonline.com/"
```
> http://localhost:8888/?email=patrick@ymail.com
```json
"https://login.yahoo.com/"
```
>http://localhost:8888/?email=patrick@bittorrent.com
```json
"mail.google.com/a/bittorrent.com"
```
>http://localhost:8888/?email=patrick@hotmail.com
```json
"https://login.live.com/"
```
