# Data visualization with Node.js, D3.js , DC.js and mongoDB
Create the visual charts with the data provide in Excel sheet. Import that CSV into mongoDB, then create the charts using D3.js

## Commong libraries / framework:

## D3.js: 

A javascript based visualization engine which will render interactive charts and graphs based on the data.
## Dc.js: 

A javascript based wrapper library for D3.js which makes plotting the charts a lot easier.
## Crossfilter.js: 

A javascript based data manipulation library. Works splendid with dc.js. Enables two way data binding.
## Node JS: 

Our powerful server which serves data to the visualization engine and also hosts the webpages and javascript libraries.

## Mongo DB: 

The resident No-SQL database which will serve as a fantastic data repository for our project.

## Setup
Navigate to main folder and 


run *npm install*

it will install dependencies. 

run *node server

and open http://localhost:8080

## Output Screens
### Import CSV in data folder using following command

Navigate to "data" folder and copy the file into "C drive"

type the following command

mongoimport -d donorchoose -c projects --type csv --file C:\projects-min.csv --headerline --upsert

![Alt text](https://raw.githubusercontent.com/amir-saeed/Node-data-visualization-with-D3js-DCjs-and-mongoDB/master/Demo/import_command.png?raw=true "Mongo DB")

### View the imported records using robomongo management studio GUI
All imported records

![Alt text](https://raw.githubusercontent.com/amir-saeed/Node-data-visualization-with-D3js-DCjs-and-mongoDB/master/Demo/mongo-records.png?raw=true "Mongo DB")

Single record

![Alt text](https://raw.githubusercontent.com/amir-saeed/Node-data-visualization-with-D3js-DCjs-and-mongoDB/master/Demo/mongo-single-record.png?raw=true "Mongo DB")

### Final output when you run the application

![Alt text](https://raw.githubusercontent.com/amir-saeed/Node-data-visualization-with-D3js-DCjs-and-mongoDB/master/Demo/output.png?raw=true "Mongo DB")



