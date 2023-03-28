# rust-api
Following the Rust books tutorial walk through of creating an api from the Rust standard library - https://doc.rust-lang.org/book/ch20-00-final-project-a-web-server.html.

## Pre-req
- Rust installed

## How to run?
- Start project - ``cargo run``

## How to hit endpoints?
I've just used ``curl`` from my terminal but you could optionally use your own preffered approach to make http requests to the endpoint ``127.0.0.1:7878``.
#### HTTP GET:
- ``curl 127.0.0.1:7878/name`` - returns my name
- ``curl 127.0.0.1:7878/age`` - returns my age
- ``curl 127.0.0.1:7878/anything-else`` - returns 404

note: if you use an alternative way of sending http requests you'll need to remember to remove the ``curl `` from the start of the request url.
