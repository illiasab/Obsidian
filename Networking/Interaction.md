## Types of Interaction with Networking overall
### REST -> user sends request only when needed and gets data.

### Short Polling -> Automatic repetition request by timer. Super easy but requires unnecessary traffic and burden(нагружать) server.
### Long Polling -> "Зависание" on request. Minimizes traffic(in contrast to short polling), while takes resources of server for a continuous time.
### WebSocket - Least delay, switch messages in real time, a bit harder in implementing.

### GraphQL -> allows to request concrete lines to answer(more flexible).

### RPC/GRPC - interaction through calling function with parameters.

[[Networking]]
