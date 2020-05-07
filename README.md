# netty-client-server
Basic client-server application made using netty framework

Netty is a non-blocking input/output framework that makes it relatively simple to develop low level network server and clients.
Netty is async non-blocking IO model is designed for highly scalable architectures and may allow for higher throughput than an analogous blocking model. Basically non blocking server runs all requests asynchronously on a single thread(no function should block the eventloop). This contrasts with the blocking server model, which typically runs each request on a seperate thread. By never having to switch threads or create threads as load increases, the non-blocking model allows for reduced overhead and quicker expansion as traffic increases.
