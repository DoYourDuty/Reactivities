# Reactivities
```
dotnet new sln - for new solution file.
dotnet new webapi -n API - for new webapi project in folder
dotnet new classlib -n Application - For new class library 
dotnet new classlib -n Domain
dotnet new classlib -n Persistence
dotnet sln add .\API\API.csproj  - For add project into solution
dotnet sln add Application 
dotnet sln add Persistence 
dotnet sln add Domain 
dotnet sln list - For listing added project into solution.
dotnet add reference ../Application - For adding reference of other project
dotnet add reference ..\Domain\
dotnet add reference ..\Persistence\
dotnet add reference ..\Domain\
dotnet ef migrations add InitialCreate -p Persistence -s API - for migration db
git status - For get the git status of current repo
git init - to initiate the git 
dotnet new gitignore - for create ignore file
git add . - to add into stage
git branch -M main - After commit. create new branch called main
git remote add origin https://github.com/DoYourDuty/Reactivities.git - Add remote location
git push -u origin main - push to github repo the main branch
```
