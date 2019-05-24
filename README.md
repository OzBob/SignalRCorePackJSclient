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