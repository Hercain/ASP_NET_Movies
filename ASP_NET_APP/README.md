# Wersja pliku

Jest to wersja pliku bez autentykacji. Użytkownicy mogą korzystać z aplikacji bez logowania.

## Lokalne użycie

Upewnij się, że posiadasz zainstalowane .NET Core na swojej lokalnej maszynie.
Dodatkowo, powinieneś posiadać narzędzia dotnet-aspnet-codegenerator oraz dotnet-ef, a w tym wszystkie paczki z nimi powiązane. Możesz je zainstalować w następujący sposób:

```bash
dotnet tool install --global dotnet-aspnet-codegenerator
dotnet tool install --global dotnet-ef
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.SQLite
dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools
```
