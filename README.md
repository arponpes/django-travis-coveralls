# django-travis-coveralls

[![Build Status](https://travis-ci.org/arponpes/ticross.svg?branch=master)](https://travis-ci.org/arponpes/ticross)

## Example of django project using travis and coveralls.

### Possible configuration

> For include postgresql
```
addons:
  postgresql: "9.6"
services:
  - postgresql
```
***

> **.coveragerc** 

You can add whatever you want to ignore for the coverture test

```
omit = .venv/*, core/migrations/* 
```


Documentation

- [Django](https://docs.djangoproject.com/en/2.0/)
- [Coveralls](https://docs.coveralls.io/)
- [Travis](https://docs.travis-ci.com/)