FROM mcr.microsoft.com/dotnet/core/aspnet:2.2
WORKDIR /app
COPY /bin/Release/netcoreapp2.2/publish /app/
ENTRYPOINT ["dotnet","ConsoleDocker.dll"]