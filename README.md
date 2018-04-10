## Work with the project
* Visual Studio 2017 15.6.5 or greater.

## The project
* Based on Official Documentation [See](https://docs.asp.net/en/latest/intro.html).
* Decoupled Unit-testable.
* Upgraded from AspNET Core 1.0.1 to AspNET Core 2.0.
* Layered project, Model, Repository and Services.
* UnitOfWork (repository).
* Generic Repository.
* Role based Authorization & Claims-Based Authorization (Administration Menu) [See](https://docs.asp.net/en/latest/security/authorization/index.html).
* For icons I am using Awesomefont [See](http://fontawesome.io/icons/).
* **Users:** admin and test, password for both of them 1122334455.
* All new accounts are created with the default password: **1122334455**, can be changed at `UserService`.
* Implemented Globalization and internationalization (not finished yet.)
* Added Code Analysis [See] (https://github.com/DotNetAnalyzers/StyleCopAnalyzers).
* Database provider SQL (configured as localdb).
* Made from the ASP.NET Core Web Application (.NET Core) Template with `Individual User Accounts` authentication.

## Configuration
* WarningAsErrors **false** can be changed at `buildOptions` node of each project.json file.
* ConnectionString at node section `TemplateConnection` of appsettings.json.

## Unit Testing
* xUnit 2.3.1.
* For Repository and Service Layer, using InMemory (database) [See](https://docs.efproject.net/en/latest/providers/in-memory/index.html?highlight=testing).
* For Controllers, using Moq 4.8.2
* Custom `CodeCoverage.runsettings` [See](https://msdn.microsoft.com/en-us/library/jj159530.aspx).
