HelloGo
-------

A simple Golang service that returns JSON messages of different sizes. Useful for testing load generators.

Server listens on port :8080 on all interfaces.

Endpoints:
- /json     Hard-coded "Hello World" JSON response
- /json1k   JSON response of roughly 1KB in size
- /json10k  JSON response of roughly 10KB in size
