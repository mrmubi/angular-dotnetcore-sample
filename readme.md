# Angular Dotnet Core Sample
This sample implements Angular and .NetCore

dotnet --version

Install node.js https://nodejs.org/dist/v12.4.0/node-v12.4.0-x64.msi

node -v

git --version

npm install --global @angular/cli@8.1.2

ng new project_name --directory project_name/ClientApp --routing true --style css --skip-tests true --skip-git true

cd project_name/ClientApp
npm start

mkdir ServerApp
cd ServerApp
dotnet new globaljson --sdk-version 3.0.100

dotnet new mvc --language C# --auth None

dotnet watch run

dotnet add package Microsoft.AspNetCore.SpaServices.Extensions --version 3.0.0

npm start (client app folder)

dotnet tool uninstall --global dotnet-ef
dotnet tool install --global dotnet-ef --version 3.0.0

dotnet add package Microsoft.EntityFrameworkCore.Design --version 3.0.0
dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 3.0.0

dotnet ef migrations add Initial


