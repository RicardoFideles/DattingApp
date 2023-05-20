
dotnet watch run

dotnet ef migrations add InitialCreate -o Data/Migrations

dotnet ef database update