# SignalRCorePackJSclient
aspnetcore signlarcore messgepack javascript client

Testing claims in: https://docs.microsoft.com/en-us/aspnet/core/signalr/messagepackhubprotocol?view=aspnetcore-2.2

commands;

dotnet new angular --auth Individual -uld
install-package microsoft.entityframeworkcore.sqlserver
edit appsettings.json

packagemanager: update-database
f5

Open Edge to https://localhost:44389/
register user: Test1@email.com
login as Test1@email.com

Open Chrome to https://localhost:44389/
register user: Test2@email.com
login as Test2@email.com

Stop Debugging

VS2019 PM>Install-Package Microsoft.AspNetCore.SignalR.Protocols.MessagePack -Version 3.0.0-preview6.19307.2

VSCode: ./ClientApp
npm update
npm audit
//npm update lots of thingz

npm i @aspnet/signalr@next
//which installs v "^3.0.0-preview5-19227-01"
npm i @aspnet/signalr-protocol-msgpack@next

//which installs v "^3.0.0-preview5-19227-01"

//BUT WANRS:

//"npm i @aspnet/signalr-protocol-msgpack@3.0.0-preview5-19227-01 requires a peer of @aspnet/signalr@^1.0.0-preview3 but none is installed. You must install peer dependencies yourself."

//which is NOT avilable on https://www.npmjs.com/package/@aspnet/signalr
raised in Github: https://github.com/aspnet/AspNetCore/issues/10307


Recent update to npm @aspnet/signalr-protocol-msgpack@next has updated it to v3

Try again:

npm i @aspnet/signalr-protocol-msgpack@next

//BUT WARNS:

//"npm WARN @aspnet/signalr-protocol-msgpack@3.0.0-preview6.19307.2 requires a peer of @aspnet/signalr@^1.0.0-preview3 but none is installed. You must install peer dependencies yourself."

