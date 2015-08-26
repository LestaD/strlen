# strlen

[![NPM](https://nodei.co/npm/strlen.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/strlen/)

 ![Mocha Testing](https://img.shields.io/badge/build-passing-brightgreen.svg)
 ![Dependencies](https://david-dm.org/lestad/strlen.svg)
 ![npm version](https://badge.fury.io/js/strlen.svg)
 
Command line tool for counting characters

# Usage

From arguments:
```bash
$ strlen Any long string
15
```

From pipe:
```bash
$ echo "12345" | strlen
5
```

And
```bash
$ strlen < ~/.ssh/id_rsa.pub 
396
```

Last:
```bash
$ strlen Me | cat
2
```
