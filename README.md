https://quantizd.com/building-facebook-messenger-bot-with-nodejs[https://quantizd.com/building-facebook-messenger-bot-with-nodejs/]

npm install

$ cp config/default.json.example config/default.json

Add your Facebook page access token in config/default.json config file.

{
  "facebook": {
    "page": {
      "access_token": "YOUR_PAGE_ACCESS_TOKEN"
    }
  }
}


For local setup

node index.js

run    ./ngrok http 8989
which give us two urls one for http and one for https
use the https url in facebook page configuration along with the secret key