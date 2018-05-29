# Node Redis
Simple user management app using Node.js and Redis

## Usage

Make sure you have Redis installed and running

Install Dependencies

```sh
$ npm install
```

Run Server

```sh
$ npm start
```

## Install redis
```sh
$ wget http://download.redis.io/redis-stable.tar.gz
$ tar xvzf redis-stable.tar.gz
$ cd redis-stable
$ make
$ make test
```

## CP Redis Server and Client
```sh
$ sudo cp src/redis-server /usr/local/bin/
$ sudo cp src/redis-cli /usr/local/bin/
```

## Starting Redis
```sh
$ redis-server
```
## Check if Redis is working
```sh
$ redis-cli ping //output: PONG
```

## Enter to CLI
```sh
$ redis-cli  

```

[Install Redis](https://redis.io/topics/quickstart)

## More info
[Redis](https://redis.io/commands/)

Visit http://localhost:3000

