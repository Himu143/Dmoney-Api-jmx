## Dmoney-Api-jmx

## Project Scenario (Request):

  1. Login to user
  2. Create a new agent
  3. Give balance to the newly created agent from system
  4. Create a customer
  5. Search the newly created user by phone number
  6. Deposit balance to the customer from the agent
  7. Withdraw some money from the agent
  8. Delete the user

## Technology and Tool Used
  - Apache Jmeter
  - JAVA 8
 
## Prerequisite
  - Jmeter must be installed
  - JAVA 8 or 11 must be installed
  
## How to run this project
  - Clone this project
  - Copy the Dmoney-Load-Test.jmx file and place it in the bin folder of the Jmeter installation location
  - Run the project by opening the Dmoney-Load-Test.jmx file in Jmeter
  
## How to generate report
  - Delete the previously Report folder from the project 
  - Open command promt in bin folder of the Jmeter installation location
  - hit this command: jmeter -n -t .\Dmoney-Api-Performance-Test.jmx -l dmoneyapi-performance.csv -e -o Reports
   
## Report of load testing

![report1](https://user-images.githubusercontent.com/78273243/215479799-120c63e7-84ef-4111-94ea-06207ebf6f9a.jpg)
![report2](https://user-images.githubusercontent.com/78273243/215479834-ae10cfa8-1a3d-445a-94df-04c57de89948.jpg)

## Test Plan
![testplan](https://user-images.githubusercontent.com/78273243/215480447-e469b15a-520c-4848-ac82-de592c7bed24.jpg)

## View Result Tree
![viewResultTree](https://user-images.githubusercontent.com/78273243/215480073-9c2066e8-ed63-4c54-9d65-dd7fa904e70d.jpg)

## Summary Report

![summary report](https://user-images.githubusercontent.com/78273243/215480288-786067ec-fbff-4cc0-a4d3-48ea0164b038.jpg)
