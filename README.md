Retort WP
========

WordPress development environment based on PHP built-in server + WP-CLI.  
A simple and fast to build a WordPress development environment.

This is used [wp-instant-setup by miya0001](https://github.com/miya0001/wp-instant-setup) as reference.

## Demo Movie

https://www.youtube.com/watch?v=6vL-2rJXGtQ

## Requires
* macOS (OSX)
* PHP 5.4+
* MySQL

## How To Use

```bash
$ mkdir ./retort-wp
$ cd ./retort-wp
$ curl -LOk https://raw.githubusercontent.com/visualive/retort-wp/master/rwp
$ chmod u+x ./rwp
$ ./rwp start
```

Or

```bash
# Anyway, let's trial.
$ cd ~/Desktop &&\
curl -L https://goo.gl/9ZJeCm | sh
```

### Options
|Option|Description|
|:--|:--|
|-h|Display the help|
|-v|Display the version|
|start|Start server|
|stop|Stop MySQL|

<kbd>control</kbd> + <kbd>c</kbd> でサーバー停止後 `./rwp stop` を実行する.

## Default WordPress Account
* User: rwp
* Password: rwp
