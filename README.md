# asp-net_cmd
asp.net commands that needs to have easy was

# to create new dotnet project
dotnet new mvc -n MyProjectName
# normal commands to run dotnet project
1. dotnet restore
2. dotnet build
3. dotnet run
4. dotnet watch run [to see changes in live time]
# For packages you can go to nuget and get command for the required package.
# here are some basic packeges command
1. dotnet add package Microsoft.EntityFrameworkCore
2. dotnet add package MySql.Data
3. dotnet add package MySqlConnector
4. dotnet add package MySql.Data.EntityFrameworkCore
5. dotnet add package Microsoft.EntityFrameworkCore.Tools
6. dotnet add package Microsoft.AspNetCore.Session
7. dotnet add package Microsoft.AspNetCore.Authorization
# to add model or controller or anything the commands are 
1. dotnet new class -n MyNamespace -o MyModel
2. dotnet new class -n MyNamespace -o MyController

# to migrade and update database
1. dotnet ef migrations add mymigrationname
2. dotnet ef database update
