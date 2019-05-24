# SignalRCorePackJSclient
aspnetcore signlarcore messgepack javascript client

commands;

dotnet new angular --auth Individual
install-package microsoft.entityframeworkcore.sqlserver
edit appsettings.json
update DefaultConnection:  "Server=(localdb)\\MSSQLLocalDB;Database=aspnet-coreauth-23bc9b9d-9d6a-45d4-8429-2a2761773502;Trusted_Connection=True;MultipleActiveResultSets=true"

change Startup.cs line 30
options.UseSqlServer(
packagemanager: update-database
f5

Open Edge to https://localhost:44389/
register user: Test1@email.com
login as Test1@email.com

Open Chrome to https://localhost:44389/
register user: Test2@email.com
login as Test2@email.com

Stop Debugging

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
