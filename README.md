# <img src="http://i.imgur.com/BpUrg3a.png" width="50" /> Nodetomic Api Swagger 

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f5084c4bad544b2586e3e973c8e3a336)](https://www.codacy.com/app/kevoj/nodetomic-api-swagger?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=kevoj/nodetomic-api-swagger&amp;utm_campaign=Badge_Grade) [![NPM version](https://badge.fury.io/js/nodetomic-api-swagger.svg)](https://npmjs.org/package/nodetomic-api-swagger) [![Build Status](https://travis-ci.org/kevoj/nodetomic-api-swagger.svg?branch=master)](https://travis-ci.org/kevoj/nodetomic-api-swagger) [![dependencies Status](https://david-dm.org/kevoj/nodetomic-api-swagger/status.svg)](https://david-dm.org/kevoj/nodetomic-api-swagger) [![devDependencies Status](https://david-dm.org/kevoj/nodetomic-api-swagger/dev-status.svg)](https://david-dm.org/kevoj/nodetomic-api-swagger?type=dev) [![Gitter chat](https://img.shields.io/gitter/room/kevoj/scaling-fullstack.svg)](https://gitter.im/scaling-fullstack/Lobby) [![GitHub license](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://raw.githubusercontent.com/kevoj/nodetomic-api-swagger/master/LICENSE) [![Downloads](https://img.shields.io/npm/dt/nodetomic-api-swagger.svg?style=flat-square)](https://npmjs.org/package/nodetomic-api-swagger)

> RESTful API Nodejs designed for horizontal scalability with support for cluster, based on Swagger, Redis, JWT, Passport, Socket.io, Express, MongoDB.

<a href="https://www.codacy.com/app/kevoj/nodetomic-api-swagger?utm_source=github.com&utm_medium=referral&utm_content=kevoj/nodetomic-api-swagger&utm_campaign=Badge_Grade" ><img src="http://i.imgur.com/n98gapy.png"></a>

### Technologies

<a><img src="http://oraclelinuxworld.com/wp-content/uploads/2016/01/NodeJS-Small-Blog-Feature-Image-.jpg" width="50"></a>
<a><img src="https://avatars2.githubusercontent.com/u/7658037?v=3&s=400" width="50"></a>
<a><img src="https://chris.lu/upload/images/redis.png" width="50"></a>
<a><img src="http://nightdeveloper.net/wp-content/uploads/2014/12/mongo_db.png" width="50"></a>
<a><img src="http://code.runnable.com/images/provider-icons/icon-express-alt.svg" width="50"></a>
<a><img src="https://www.pubnub.com/wp-content/uploads/2014/07/SOCKETIOICON.gif" width="50"></a>
<a><img src="https://pbs.twimg.com/profile_images/542039812916510720/Vw-JEJQA.png" width="50"></a>
<a><img src="https://cms-assets.tutsplus.com/uploads/users/16/posts/24511/preview_image/babel-1.png" width="50"></a>
<a><img src="http://www.themightycribb.com/wp-content/uploads/2016/08/gulpjs-logo.jpg" width="50"></a>
<a><img src="https://avatars0.githubusercontent.com/u/8770005?v=3&s=400" width="50"></a>
<a><img src="http://bluebirdjs.com/img/logo.png" width="50"></a>
<a><img src="https://nodemon.io/nodemon.svg" width="50"></a>
<a><img src="https://pbs.twimg.com/profile_images/599259952574693376/DMrPoJtc.png" width="50"></a>
<a><img src="http://www.erikasland.com/static/images/mongoose.png" width="50"></a>
<a><img src="https://nr-platform.s3.amazonaws.com/uploads/platform/published_extension/branding_icon/300/PKpktytKH9.png" width="50"></a>
<a><img src="https://awesomes.oss-cn-beijing.aliyuncs.com/repo/151017151426-82-1.jpg?x-oss-process=style/repo" width="50"></a>
<a><img src="https://seeklogo.com/images/E/eslint-logo-DDFB6EBCF6-seeklogo.com.png" width="50"></a>
<a><img src="https://avatars3.githubusercontent.com/u/2824157?v=3&s=400" width="50"></a>
<a><img src="https://i2.wp.com/community.nodemailer.com/wp-content/uploads/2015/10/n2-2.png?fit=422%2C360&ssl=1" width="50"></a>
<a><img src="https://cdn.xebialabs.com/assets/files/plugins/travis-ci.jpg" width="50"></a>

### Preview

**url:** <http://localhost:8000/socket>

[![](https://j.gifs.com/0gw5gX.gif)](https://www.youtube.com/watch?v=drhEQl-4x0w)

### Swagger Api

**url:** <http://localhost:8000/docs> 

<img src="https://i.imgur.com/m0eJiva.png">

### Horizontal scalability

View horizontal scaling representation image with nodetomic-api-swagger <a href="https://github.com/kevoj/nodetomic-api-swagger/wiki/1.-Horizontal-scalability">HERE!</a>

### Structure

<pre> 
/src/
|-- api
|   |-- swagger
|   |-- controllers
|   |-- models
|   `-- sockets
|-- assets
|-- auth
|   |-- swagger
|   |-- controllers
|   |-- passports
|   `-- services
|-- config
|-- lib
|   |-- express
|   |-- mongoose
|   |-- redis-jwt
|   |-- socket.io
|   `-- swagger
|-- views
`-- app.js
</pre> 

## Requirements

- [Nodejs](https://nodejs.org) >= **6.x.x** (Recommended **9.x.x**)
- [MongoDB](https://www.mongodb.com)  >= **3.x.x**
- [Redis](https://redis.io)  >= **3.x.x** (Recommended **4.x.x**)

## Installation

**Npm**

```bash
git clone https://github.com/kevoj/nodetomic-api-swagger
cd nodetomic-api-swagger
npm i
```

**Yarn**

```bash
yarn add nodetomic-api-swagger --ignore-engines
```

## Development

### Start

**Command:** `npm start` 

**Description:** Start the project in development mode

![Imgur](https://i.imgur.com/qY1mzDZ.png)

**Note:** if you want work with **nodemon** execute the command `npm run modemon`

### Build

**Command:** `npm run build`

**Description:** Compile the project by outputting the dist folder

![Imgur](http://i.imgur.com/yTI3otr.png)

**Note:** Generate folder **`dist`**. So "dist/client" is optional. You can paste the compilation of a client here, for example of Vue, React, Angular...

![Imgur](https://i.imgur.com/bVFqr1f.png)

### Test

**Command:** `npm test`

**Description:** Run Lint and run Build in production mode and execute the authentication methods and basic requests.

![Imgur](http://i.imgur.com/4cM4HXs.png)

### Lint

**Command:** `npm run lint`

**Description:** Run ESLint to verify the entire project code

<br>

## Pm2 [Development]

### Dev-Simple

**Command:** `npm run dev-simple`

**Description:** Run Pm2 and compile the project in development mode in a single instance

![Imgur](http://i.imgur.com/cNuBVzK.png)

### Dev-Cluster

**Command:** `npm run dev-cluster`

**Description:** Run Pm2 and compile the project in development mode in multiple instances

![Imgur](http://i.imgur.com/wEU2Uz5.png)

## Pm2 [Production]

### Simple

**Command:** `npm run simple`

**Description:** Run Pm2 and compile the project in production mode in a single instance

![Imgur](http://i.imgur.com/tLA2hu7.png)

### Cluster

**Command:** `npm run cluster`

**Description:** Run Pm2 and compile the project in production mode in multiple instances

![Imgur](http://i.imgur.com/HTWJcUk.png)

## Stop

### Pm2

**Command:** `npm stop`

**Description:** Stops all processes associated with project pm2

### Node

**Command:** `killall node`

**Description:** Destroyed all process for node

## API Docs

You can find the documentation <a href="https://github.com/kevoj/nodetomic-api-swagger/wiki" >HERE!</a>

## License

MIT © [Leonardo Rico](https://github.com/kevoj/nodetomic-api-swagger/blob/master/LICENSE)