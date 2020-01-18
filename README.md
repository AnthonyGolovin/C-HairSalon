# _Friday Programming Test Project_

## Description/Specs

#### _Setup/Installation Requirements:_

1. Open Terminal or CMD.
2. Enter Desired installation directory.
3. Copy the repository off git hub (EX. use command "git clone https://github.com/AnthonyGolovin/C-HairSalon").
4. A new file should appear in that directory labled "HairSalon.Solutions", enter the new project directory in CMD or terminal.

#### _Setup/Database:_
1. Open CMD or temrinal, navigate to your MySQL bin folder and enter "mysql -uroot -pepicodus".
2. Now create a new database called anthony_golovin. (EX. CREATE DATABASE anthony_golovin;).
3. Type in the console USE anthony_golovin.
4. Create the following two tables by entering text below in your console.
##### _CLIENTS TABLE:_
CREATE TABLE `clients` (
  `Name` varchar(255) DEFAULT NULL,
  `ClientId` int(11) NOT NULL AUTO_INCREMENT,
  `StylistId` int(11) NOT NULL,
  `Description` varchar(45) DEFAULT NULL,
  PRIMARY KEY (`ClientId`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

##### _STYLISTS TABLE:_
CREATE TABLE `stylists` (
  `Name` varchar(255) DEFAULT NULL,
  `StylistId` int(11) NOT NULL AUTO_INCREMENT,
  PRIMARY KEY (`StylistId`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
5. Lastly enter "dotnet watch run" and enter the local 5000 address into your browser.

## Support and contact details

_For any syntax errors please review the Setup/Installation Requirements section above and follow the above steps._

## Technologies Used

_*C#
_*WindowsConsole
### License
*Licensed under the MIT license*
Copyright (c) 2016 **_Anthony P Golovin**_
