## 2.1 Original code of broadcast chat
#### Server
![](/images/2.1.1.png)
#### Client
![](/images/2.1.2.png)
![](/images/2.1.3.png)
![](/images/2.1.4.png)
<br>
To run, just run `cargo run --bin <file_name>`. When I type some text in a client, the text will also be sent to other clients and server.

## 2.2 Modifying the websocket port
![](/images/2.2.1.png)
Other than the client.rs file, I also changed the port in server.rs file, specifically in line 44 and 45. The protocol in server.rs file is different from the client.rs where client.rs uses a websocket, while server.rs uses a TCP protocol.