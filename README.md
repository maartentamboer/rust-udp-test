# rust-udp-test
This is a small test project that I've made whilst playing around with rust.


## Members in the workspace
### protocol
protocol is a lib that describes the messages using enums and has a simple serialize and deserialize function.
These use [Serde](https://serde.rs/) and [Bincode](https://github.com/TyOverby/bincode).

### server
The server. Handles Request messages and replies with a response.

### client
The client. Sends a request message and prints the response.
