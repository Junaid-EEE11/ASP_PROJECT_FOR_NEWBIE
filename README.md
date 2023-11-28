# ASP_PROJECT_FOR_NEWBIE

On Day 1, the focus should be on setting up the environment, understanding the basic structure of an ASP.NET Core project, running the initial project
## 1. Setup Development Environment:

  Download ASP.NET Core SDK from https://dotnet.microsoft.com/en-us/download.
  To make make sure .NET Core is installed on your machine:
    open command prompt and write
        dotnet --version
      if *.*.* comes then it is installed correctly.

## 2.  Create a New ASP.NET Core Project and Run the sample project:

  Use dotnet new command for a project named "Business_App".
    write in command promt: 
      dotnet new mvc -n Business_App
      cd .\Business_App
      dotnet run
  open site with browser [https://localhost:7017]
  
  Alert: Choose the appropriate ASP.NET Core template (MVC, Web API, etc.) based on the business solution requirements. In this case We have used MVC Templete. 
  [[If you want to use WebAPI then write: 
    dotnet new webapi -n Business_App
    cd Business_App
    dotnet run
GoTo [https://localhost:7037/weatherfocast] with a browser to see the sample project of webapi]]

## 3.  Understand the Project Structure:

  Familiarize yourself with the project structure, go to C:\Users\Users_Name\Business_App folder and inspect key folders (Controllers, Models, Views, etc.), and important files Program.cs, Controller\HomeController.cs, View\ErrorView.cs.


## 4.  Setup Version Control:

  Initialize a Git repository for the project (if using version control).
  create/signup a account in github.com and create a repository named Business_APP. Clone this PC using github desktop. and copy all folders in this repository.
  Commit the initial project setup to the repository.

Day_01 completed
----------------------------------
On day 2, the focus shifts towards implementing a specific feature/module, integrating it into the ASP.NET Core project, ensuring functionality, and addressing key aspects like authentication, data handling, validation, and documentation.

## 1.  Addition of Functionality:
  Identifing core features for your business solution user authentication, data CRUD operations, others

## 2.  Implemention User Authentication:
  Introducing user authentication and authorization.
  Implemention a simple authentication mechanism using ASP.NET Core Identity or JWT Authentication.
























  
