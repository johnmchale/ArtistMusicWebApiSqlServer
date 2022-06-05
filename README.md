# ArtistMusicWebApiSqlServer

This is an ASP.NET Core 3.1 Web API solution that connects to a SQL Server database

It is mainly based on the following article:

https://medium.com/swlh/building-a-nice-multi-layer-net-core-3-api-c68a9ef16368

## appsettings.Development.json - example file

create an **appsettings.Development.json** file in the root directory (i.e. same level as **appsettings.json**) of the **MyMusic.Api** project with the necessary credentials

```
{
  "ConnectionStrings": {
    "Default": "server=.\\SQLEXPRESS; database=MyMusic; user id=sa; password=*********"
  },
  "Logging": {
    "LogLevel": {
      "Default": "Debug",
      "System": "Information",
      "Microsoft": "Information"
    }
  }
}
```
