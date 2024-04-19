# Creating an ASP.NET MVC Project

## Setting Up

1. **Open Visual Studio.**
2. **Create a new project and select ASP.NET Web Application.**
3. **Choose the MVC template and ensure that authentication is set as needed.**

## Install NuGet Packages

Make sure you install all of these if you want a functinal application, to install go under

Tools > NuGet Packaage Manager > Manage NuGet Packet for Solution and then downlaod the below:

1. Microsoft.EntityFrameWorkCore
2. Microsoft.EntityFrameWorkCore.Design
3. Microsoft.EntityFrameWorkCore.Sql
4. Microsoft.EntityFrameWorkCore.Tools

## Scaffold your Database

Copy the below Code, Change the Connection string to yours paste it in 'Connection String'

Scaffold-DbContext "Data Source=LEIGHCHESHP\SQLEXPRESS;Initial Catalog=BargainBooks2;Integrated Security=True;Encrypt=False;Trust Server Certificate=True" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models

## Adding a Model

1. **Right-click on the Models folder.**
2. **Add a new class and define properties.**

## Adding a View

1. **Right-click on the Views folder.**
2. **Select Add and then View.**
3. **Provide a name and select the template as needed.**

## Adding a Controller

1. **Right-click on the Controllers folder.**
2. **Select Add and then Controller.**
3. **Choose MVC 5 Controller with views, using Entity Framework.**
4. **Follow the prompts to link the model and context.**

## Running the Application

1. **Build the project.**
2. **Run it using the local server provided by Visual Studio.**

Follow these steps, and you will have a basic ASP.NET MVC application running on your local machine.