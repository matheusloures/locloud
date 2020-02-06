# locloud

> Locally generate a Non Relational Database and initialize it with helper functions to Create, Read, Update, Delete and much more.

## Installation

```shell
$ npm install -g locloud
```

## Usage

- Hit the command line on your project's folder
- Write `locloud` and enter

## Documentation

### create(tableName) <Promise>
- Creates a new db on your folder 

### genOrUpdate(key, what, tableName) <Promise>
- Creates or Updates a key 

### readOn(key) <Promise>
- Promise reading a key

### deleteThis(key, tableName) <Promise>
- Delete the key

### zeroOn(key, tableName) <Promise>
- Zero a number on a key

### emptyOn(key, tableName) <Promise>
- Empty a String on a key

### toggleBoolOn(key, tableName) <Promise>
- Toggle boolean on a key

### plus(amount, key, tableName) <Promise>
- Add to a number value on a key