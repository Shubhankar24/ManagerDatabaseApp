# Manager Database App

A simple ASP.NET Core MVC project for managing managers  SQL Server.

## Tech Stack
- ASP.NET Core MVC (.NET 8)
- SQL Server LocalDB
- Entity Framework Core

## Setup
- Open in Visual Studio
- Update `appsettings.json` with your SQL Server connection string (⚠️ Required)
- inside appsettings.json --> just add this in first line along with ur database location -------> "ConnectionString":{
  "ConStr":"Data Source =your db location; Initial Catalog = DatabaseName; Integrated Security =True; TrustServerCertificate=True"
  },
  
- Open Package Manager Console:
  - Run `Add-Migration Mig1`
  - Run `Update-Database`
- Run the app 🚀


## Features
- Create, Read, Update, Delete managers
- Stylish Bootstrap homepage

## Future Improvements
- Deployment to Render or Azure

  ## *Happy Learning :)*
