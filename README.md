### Server and Client example in Ruby

To run, you will need to open two shell sessions: one for the server,
and one for the client.

In the server shell session, in irb:
```ruby
SimpleServer.new.start
```

In the client shell session, in irb:
```ruby
SimpleClient.new.perform_requests(10)
```

To stop the server, press Ctrl-C.
