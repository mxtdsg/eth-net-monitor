# eth-net-monitor

- - -

## Install monitor
1. install
```git clone https://github.com/cubedro/eth-netstats
cd eth-netstats
npm install
grunt
WS_SECRET=XXX npm start
```
change port if needed

## Install client
1. install
```
git clone https://github.com/cubedro/eth-net-intelligence-api
cd eth-net-intelligence-api
npm install i -g pm2
npm install
```
2. config the `app.json` file
3. send data `$ pm2 start app.json`
