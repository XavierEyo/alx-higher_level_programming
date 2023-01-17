# 0x14. JavaScript - Web scraping

## General


* JavaScript programming
* SON data
* Request and fetch API
* Read and write a file using fs module

## Environment

* OS: ``ubuntu``
* IDE: ``Vim``, ``VS Code``
* Language: ``JavaScript``
* Style guidelines: ``semistandard`` ``Airbnb style``
* Node.js

* Shebang: ``#!/usr/bin/node``
* Star Wars api: [swapi-api.hbtn.io](https://swapi-api.hbtn.io/)

### install Node 10

```bash
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

### Install semi-standard

```bash
$ sudo npm install semistandard --global
```

### Install request module and use it

```bash
$ sudo npm install request --global
$ export NODE_PATH=/usr/lib/node_modules
```

## Run the code

> reading file and parsing it with Node.js

```bash
:$ ./0-readme.js doesntexist
{ [Error: ENOENT: no such file or directory, open 'doesntexist']
  errno: -2,
  code: 'ENOENT',
  syscall: 'open',
  path: 'doesntexist'
```
```

> status code of a ``GET`` request

```bash
```

> Prints the title of a Star Wars movie where the episode number matches a given integer


```bash

```
