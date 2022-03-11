# _{StylistClient.Solution}_

#### By _**{Marisa Edgar}**_

#### _{A program to keep track of the salons stylists and their clients}_

## Technologies Used

* _Markdown_
* _C#_
* _HTML5_
* _Razor_
* _CSS_
* _EntityCore_
* _Bootstrap_

## Description

_{An application to keep track of the salons stylist and their clients, as a project for Epicodus using one to many relationships}_

## Setup/Installation Requirements

* _Requires VSCode and MySql_
* _You can find my github repository at https://github.com/marisa-edgar/StylistClient.Solution_

* _Click the code button, and copy the https link_

* _In your your terminal navigate to the directory you would like to store the project_

* _In your terminal type *git clone* followed by the repo link_*


* _Open in VS Code by typing *code .* in your terminal_

* _In order to access a usable version of the sql database you will need to do the following:_

* _Create a file named appsettings.json in the SalonClient directory_

* _The file should contain this block of code except with your own username and password(in MYSQL, you will need to install and create an account) for the server(brackets around private information not included):_

{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=to_do_list;uid=[Your Id Goes Here];pwd=[Your Password Here];"
  }
}

* _Open MySQL and log into your server_

* _In the "Navigator" panel select the "Administration" tab._

* _Select "Data Import/Restore"_

* _Select "Import from self-contained file" navigate to to the SalonClient directory you cloned above and select marisa_edgar.sql_

* _In "Default Schema to be Imported to" select new and name the schema marisa_edgar_

* _NOTE: Make sure you name the file marisa_edgar or else the project won't locate the correct database_

* _Click Start Import_

* _The schema has been added! You may need to refresh your databases to see the newly imported database_

* _In your terminal run "dotnet restore" to download all dependencies.

* _Once all of the above is completed you can view the project on your local server by running "dotnet run"_

* _The project can be viewed at localhost:5000_



## Known Bugs

* _No known bugs_


## License

_{Questions or Concerns please email me at marisaedgar1212@gmail.com}_

Copyright (c) _2022_ _Marisa Edgar_