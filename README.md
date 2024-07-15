
> Prerequisites
* `sudo apt-get update && sudo apt-get install -y dotnet-sdk-6.0`

* `dotnet --list-sdks` Making sure sdk 6.0.132 [/usr/lib/dotnet/sdk] is available

* `dotnet add package Microsoft.EntityFrameworkCore.Sqlite --version 6.0.8`

* `dotnet add package System.Net.Http.Json --version 6.0.0`

* `git clone https://github.com/wevak/BlazingPizzaApp.git` to clone the repository

Code compilation :- `dotnet watch`

> References:
https://learn.microsoft.com/en-gb/training/modules/interact-with-data-blazor-web-apps/1-introduction