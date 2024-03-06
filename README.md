# Steps followed

1, First We need to Install .NET Core SDK Latest

2, Create Web API Using below command

dotnet new webapi

To create the template anyway, run the command with '--force' option:

dotnet new webapi --force

3, Run the application

dotnet run

4, Install the below extension

1, C#

2, Nuget Package manager

5, Install Entity Framework

dotnet tool install --global dotnet-ef

6, Add package Entity Framework Design

dotnet add package Microsoft.EntityFrameworkCore.Design

7, Execute the below command form verify the EF Installation

dotnet ef

8, Enter scaffold command

dotnet ef dbcontext scaffold "connectionstring" Microsoft.EntityFrameworkCore.SqlServer --output-dir Models

9, For Generating bd context only in the folder

dotnet ef dbcontext scaffold --context-dir Models

10, Create the controller also complete the steps in the middleware

``

## Git setup

```

git init

git status

git branch -M ProductAPIVS

git add README.md

git add LICENSE

git config user.email "vishnuvarthan.mail@gmail.com"

git config user.name "Vishnuvarthan"

git add .

git commit -m "Initial Commit: ProductAPIVS"

git branch -M ProductAPIVS

git remote add origin https://github.com/Vishnuvarthangs/.NetCore.git

--git push -u origin ProductAPIVS

git push -f origin ProductAPIVS

https://stackoverflow.com/questions/11696295/rejected-master-master-non-fast-forward

https://stackoverflow.com/questions/2452226/master-branch-and-origin-master-have-diverged-how-to-undiverge-branches

```
