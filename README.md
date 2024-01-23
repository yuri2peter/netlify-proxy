# netlify-proxy

API proxy on Netlify Edge

## Deploy

### Deploy With Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yuri2peter/netlify-proxy)

## Usage

Use `_target` to specify the target URL.
Other parameters are passed to the target URL.

```
curl https://{YOUR_DOMAIN}?_target=https://generativelanguage.googleapis.com/v1/models/gemini-pro:generateContent&key={YOUR_KEY} \
   -H 'Content-Type: application/json' \
   -X POST \
   -d '{ "contents":[
   { "parts":[{"text": "Hi"}]}
   ]
}'
```

## Advantages

- Simple and free.

## Shortages

- Netlify sets the single request timeout to 10 seconds, which is kind of short.

## Discussion

Please Visit Simon's Blog. https://simonmy.com/posts/使用netlify反向代理google-palm-api.html
