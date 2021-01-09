## dotnet sample chat web app

init app with docker
Blazor WebAssembly vs Angular
    https://guidnew.com/blog/lessons-learned-from-porting-an-angular-app-to-blazor/
SignalR or gRPC Services (implement both and compare performance)
    https://docs.microsoft.com/en-us/aspnet/core/grpc/comparison?view=aspnetcore-5.0
    https://docs.microsoft.com/en-us/aspnet/core/tutorials/signalr-blazor-webassembly?view=aspnetcore-5.0&tabs=visual-studio
    gRPC do not have browser support
    ...Broadcast real-time communication: gRPC supports real-time communication via streaming, but the concept of broadcasting a message out to registered connections doesn't exist. For example in a chat room scenario where new chat messages should be sent to all clients in the chat room, each gRPC call is required to individually stream new chat messages to the client. SignalR is a useful framework for this scenario. SignalR has the concept of persistent connections and built-in support for broadcasting messages...
Microservices
CI
demo

## app features
- create chat room
- share the link
- local storage of opened rooms
- ?? backup chat rooms
- init random chat