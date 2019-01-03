# 注意事项
1.windows环境下不要用pm2，会有各种弹框，关都关不掉

# 使用
npm i 不要使用cnpm

npm run dev 开启前端
node app.js 启动后台，可以直接用ide的debug启动，这样就可以打断点了

# 热更新

## 后台js更新
```
npm install -g nodemon

```
在node parameters中添加
C:\Users\bdmingfangw\AppData\Roaming\npm\node_modules\nodemon\bin\nodemon -w D:\workdoc\github\vue2-nodejs-express-mysql-pm2\VueExpress\server

然后run即可，debug是不行的经常断
