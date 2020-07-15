# SMS-Challenge

  Author- Vikas Pandey
  versio- 1.0
  Description: SMS challenge app is a dashboard app which fetches the data hosted in MongoDB client and displays in a table.
  User can sort the data based on the columns and also can filter the data using date selectors. Pagination has been enabled 
  to traverse the data spread in multiple pages.
  
  Pre-Requisites:
  1- Visual Studio Code. (https://code.visualstudio.com/download)
  2- MongoDB client. (https://www.mongodb.com/try/download/community)
  3- Chrome browser.
  4- Node.JS  (https://nodejs.org/en/download/)
  
  Execution Instructions:
  
  1- Download the file directory to local machine or server.
  2- Open the folder directory in Visual studio code.
  3- Load the data to MongoDB client by executing below steps.
      a. Copy the data.json file in the directory (ex: C:\Program Files\MongoDB\Server\4.0\bin) where MongoDB client is installed.
      b. Open the terminal in visual studio code and navigate to bin folder of MongoDB client where data.json is placed.
      c. execute the command mongoimport --db SMS_Challenge --collection users --file data.json --jsonArray.
  4- Setup Node server by following steps.
      a. Open the terminal in visual code and navigate to directoy(ex: C:\Users\Vikas\sms-fs-challenge\node server) containing server.js.
      b. run command npm install. All dependent node modules will be downloaded and local node module directory will be created.
      c. run command node server.js. Listening on port 3000... msg will be displayed on console.
  5- Setting up Angular server to host app. use below steps for same.
      a. open the terminal in visual code and navigate to SMS
      b. run command npm install -g @angular/cli.
      c. run command ng serve. Server will start on localhost showing the port number details.
  6- Open the chrome browser and enter the url: http://localhost:4200/
  7- App will be loaded and table will be displayed with data.
  
      
