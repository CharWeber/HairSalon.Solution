# _Eau Claire Hair Salon_

#### _this is a one to many database testing site under the guise of a salon website_

#### By _**Charles T Weber**_

## Technologies Used

* C#
* .NET
* MSTEST
* Javascript
* Bootstrap CSS

## Description

_This project was designed for MVC restful routing practice while utilizing Razor calls and Html helpers. We were also testing database connectivity to save our objects and store them locally._

<hr>

## System Requirements

* .Net SDK 5.0.4 or higher

## Setup/Installation Requirements

1. [Clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) this repository from GitHub to your local machine.

        $ git clone https://github.com/CharWeber/HairSalon.Solution

### Database Instructions/Set-Up

1. Open MySql Workbench

2. Log into your local server Instance. make note of the port number

3. Once in the Navigator>Administration window, Slect DATA IMPORT/RESTORE

4. Select the mySQL file located in this directory

5. Under Default Schema to be Imported to, select the New button
  * Enter the name of the database, Make note of it
  * Click Ok

6. Navigate to Tab called Import Progress and click Start Import at the bottom right corner of the window

7. Once it has finished reopen the Navigator>SChemas and slect Refresh All. The new Schema should appear.

### appSettings.json
for this application to run you must add a file to the HairSalon directory

1. create a new file call "appsettings.json" in the root of the HairSalon Directory

2. Place this code within appsettings.json
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database={YOUR-DATABASE-HERE};uid=root;pwd={YOUR-PASSWORD-HERE};"
  }
}
```

3. replace the bracketed sections with the information you've made a note of before(database name and password, remove the brackets around your info). This information is senstitive to your experience so try not to push the code to any place online without proper protection.

4. Save this file to HairSalon/appsettings.json




3. Install the [.NET framework](https://docs.microsoft.com/en-us/dotnet/core/install/windows?tabs=net50).


4. Open a new terminal instance in the HairSalon.Solution/HairSalon directory.

5. Type "dotnet run" in the terminal.

        $ dotnet run

6. Open any browser (chrome recommended) and travel to this website

        http://localhost:5000/

<hr>

## Known Bugs

* the css styling is not linking correctly, the footer is picking up styling from previous projects. **SOLVED** if the css styling isn't loading correctly try hard refreshing the page (refresh with clear cache)
* when trying to run you may run into an issue (CS7002) where it will ignore your main entry point in Program.cs

## License

MIT 2021
If you run into issues or bugs with this web application, please contact one of the developers below. Thank you!

## Contact Information

_charlestweber@gmal.com_

Photo by <a href="https://unsplash.com/@janpictures?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">JAN Pictures</a> on <a href="https://unsplash.com/@janpictures?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  