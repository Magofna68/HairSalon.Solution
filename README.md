# Hair Salon

#### Web app that will allow the user to add and track clients and stylists to business model.

#### By _**Brandon Magofna**_

## Description

This is my week 10 project at Epicodus. This app will act as a tool for a owner to use at their disposal. App will host stylists with the ability to add clients and stylists to the application. Users are able to add, edit, or delete either stylists or clients.

### Software Requirements

1. Internet browser
2. [Node](https://nodejs.org/en/)
3. A code editor like VS Code or Atom to view or edit the codebase.

## 🔧 *Setup/Installation instructions:*

* Clone this repository to your Dekstop.
* Navigate to the directory named 'HairSalon' in the terminal 
* Type 'dotnet restore' in the terminal to download all dependencies   
* Open MySQL Workbench and create a schema using the naming convention 'yourFirstName_yourLastName' and click apply
* In that schema create 2 tables titled 'stylists' and 'clients'
* In the 'stylists' table there will be 2 columns: title the first 'StylistsId' and set the date type to INT, the second titled 'Name' and data type is set to VARCHAR(255)
* The 'StylistsId' column should have the PK, NN, and AI boxes checked
* The 'Name' column should have 'Null' as the default expression
* Click apply to save that table
* Move to the 'clients' table and create 3 columns: name the first 'ClientId' with the data type INT, the second 'Name' with data type VARCHAR(255), and the third 'StylistId' with the data type INT
* The 'ClientId' column should have the PK, NN, and AI boxes checked
* The 'Name' column should have 'Null' as the default expression
* The 'StylistId' column should have '0' as the default expression
* Click apply to save that table
* Navigate back to the 'HairSalon' directory and create a file titled 'appsettings.json'
* In 'appsettings.json' copy and paste this code: {
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database={YourFirstName_YourLastName};uid=root;pwd={YourPassword};"
  }
}
* Replace {YourFirstName_YourLastName} with the name of your database, and replace {YourPassword} with your password
* Navigate back to the 'HairSalon' directory and type 'dotnet run' into the terminal
* Open a browser window and navigate to the URL 'http://localhost:5000'


⚠️ *Note: To run this project locally you will need to have .NET Core. You can check if you have .NET Core by running dotnet --version in the command line. If you do not have .NET Core please find more information and download [here](https://dotnet.microsoft.com/download/dotnet)*


#### To see my live website go to https://github.com/Magofna68

## Known Bugs

_No known bugs_

## Support and contact details

_Please reach out through my GitHub account._

## Technologies Used

- HTML
- C#
- VS Code
- .Net
- Entity
- Razor
- MySQL Workbench
- git / github



### License

MIT License.

Copyright (c) 2021 **_Brandon Magofna_**