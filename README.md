# Hahn.ApplicationProcess.Application

## Build application

Once unzipped, run following commands to restore nuget and installing npm packages
```bash
dotnet restore
```

Aurelia project is built inside "ClientApp" folder within web project. Run command at root
```bash
npm install
```

## Start application

Set the web project as startup and run. By default, swagger UI page will open at https://localhost:44395
Basic authentication credentials:
User name: user1
Password: password1

To run Aurelia UI, execute following Aurelia CLI command at "ClientApp" folder
```bash
au run
```
Browse at http://localhost:8080
