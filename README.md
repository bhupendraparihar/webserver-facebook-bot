[https://quantizd.com/building-facebook-messenger-bot-with-nodejs](https://quantizd.com/building-facebook-messenger-bot-with-nodejs/)

```
npm install
```

Add your Facebook page access token in config/default.json config file.

```
{
  "facebook": {
    "page": {
      "access_token": "YOUR_PAGE_ACCESS_TOKEN"
    }
  }
}
```

For local setup

```
node index.js
```
```
./ngrok http 8989
```
which give us two urls one for http and one for https
use the https url in facebook page configuration along with the secret key