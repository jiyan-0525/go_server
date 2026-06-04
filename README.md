# goserver

run
```
go mod init github.com/USERNAME/goserver
```
after replacing USERNAME and goserver with your own values.

Build the server: 
```
go build
```
This will create a standalone binary file in your current directory (the server application).

Run the server: 
```
./goserver
```
where goserver is the name of the built binary; by default it's the same as your project's directory.

Make sure you can hit your server's endpoint(s) either in a browser or with curl. It should be available on localhost:8010.
```
http://localhost:8010
```