static-resources 随启随用的静态文件服务器
==============================

Running static file server static-resources. 静态文件服务器。

## Installation

Install it as a command line tool via `npm -g`.

```sh
npm install static-resources -g
```

## Execution

```sh
$ static-resources
// or with port
$ static-resources -p 8000
// or start it but silent(don't open browser)
$ static-resources -s
// or with hostname
$ static-resources -h localhost -p 8888
// or with folder
$ static-resources -d ~/git/static-resources
// or enable html5 history
$ static-resources -f /index.html
```

## Help

```sh
$ static-resources --help
Usage:
  static-resources --help // print help information
  static-resources // 8000 as default port, current folder as root
  static-resources 8888 // 8888 as port
  static-resources -p 8989 // 8989 as port
  static-resources -s // don't open browser
  static-resources -h localhost // localhost as hostname
  static-resources -d /home // /home as root
  static-resources -f /index.html  // Enable html5 history,the index is /index.html
```

## Visit

```
http://localhost:8000
```
执行命令后，默认浏览器将为您自动打开主页。

## License
The MIT license.
