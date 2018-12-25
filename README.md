# easy-mock-localhost
本地easy-mock 搭建

##1. 开发环境
###Node.js (>= v8.9) & MongoDB (>= v3.4) & Redis（>= v4.0）
####a.Node.js
  download --> [官网下载](https://nodejs.org/en/download/)
####b.MongoDB 
  download --> [官网下载](https://www.mongodb.com/download-center?jmp=nav)
unZip --> tar -xzf mongodb-xx.xx.x.tar.gz
mv --> mv **/mongodb-xx.xx.x.tar.gz /user/local (没权限加sudo)
start --> cd /usr/local/mongodb/bin   ./mongod
c.Redis
download --> [官网下载](https://redis.io/download)
unZip --> tar -xzf redis-xx.xx.x.tar.gz
mv --> mv **/redis-xx.xx.x.tar.gz /user/local (没权限加sudo)
test --> make test
install --> sudo make install
start --> redis-server 

##2. 本地运行
* clone --> git clone https://github.com/easy-mock/easy-mock.git
* install --> npm install
* start --> npm run dev
* http://0.0.0.0:7300/

Mock.js: http://mockjs.com/examples.html

