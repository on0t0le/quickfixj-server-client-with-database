# Database integration with QuickFIXJ server and client
### Basic setup
The repository contains the example code for the server and client applications uses QuickFIXJ library

Both client and server stores the data in the dedicated database

To start the example stack execute the next command:
```sh
docker-compose -f docker-compose.yml up -d
```
To stop the stack
```sh
docker-compose -f docker-compose.yml down --volumes
```
