
## Dependencies
`vue`
`vuex`
`vue-router`
`vue-property-decorator`
`typescript`
`webpack`

## Configure BackEnd
* Configure back-end host in `gulpfile.js` use proxy
```
apiProxy = 'https://gitbitex.com:8080/';
```
* Configure websocket host in `src/script/constant.ts`
```
static SOCKET_SERVER = 'wss://gitbitex.com:8080/ws';
```

## Install
* Install nvm
  ```
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
  ```
* Install npm & nodejs
  ```
  nvm install 11.15.0
  ```
* Use nodejs 11.15.0
  ```
  nvm use 11.15.0
  ``` 
* git clone https://github.com/CheetahExchange/gitbitex-web
* Run `npm install`
* Run `npm start`
* Run `npm run build` to build production

## Configure Nginx
* Root dir
* Reverse proxy api
* Reverse proxy websocket


