# netlify-proxy

API proxy on Netlify Edge

## Deploy

### Deploy With Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yuri2peter/palm-netlify-proxy)

## Usage

```
curl https://{YOUR_DOMAIN}?_target=https://generativelanguage.googleapis.com/v1/models/gemini-pro:generateContent&key={YOUR_KEY} \
   -H 'Content-Type: application/json' \
   -X POST \
   -d '{ "contents":[
   { "parts":[{"text": "Hi"}]}
   ]
}'
```

## Discussion

Please Visit Simon's Blog. https://simonmy.com/posts/使用netlify反向代理google-palm-api.html
