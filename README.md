[![Build Status](https://travis-ci.org/bsomes/trashed-panda-backend.svg?branch=master)](https://travis-ci.org/bsomes/trashed-panda-backend)


# trashed-panda-backend

### Setup
This application requires Go version 1.7 or later. Dependencies are managed using Govendor. Install this tool using 
```shell
$ go get -u github.com/kardianos/govendor
```
Then run
```shell
$ govendor sync
```
to install missing dependencies.

Input data is managed using a PostgreSQL database. The connection string is managed by the environment variable DATABASE_URL. Set this to connect to a postgreSQL database with your own input data.

Set the PORT environment variable to the port the server will listen on. If this is not set the default is 8080.
