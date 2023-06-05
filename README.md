# demo-transaction-api-jmeter

## Technology Used
- JMeter
- Jdk-11

## Scenario
Based on the following flow, creating a JMX file with positive test cases:
1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Payment 200 tk from customer account (Merchant account: 01686606905)
7. Assert expected customer balance

## How to run this project
- clone this project
- save the Demo-Transaction-API.jmx file into bin folder of Jmeter
- open the Demo-Transaction-API.jmx file with jemeter
- run the project
- for generating report from command prompt, run the below command:
  $ jmeter -n -t Demo-Transaction-API.jmx -l Demo-Transaction-API-log.csv -e -o Reports
    [Note:Before runing the following command, delete if there is any already Demo-Transaction-API-log.csv file and Reports folder in the bin]
    
## Command Prompt Screenshot:  
    ![Screenshot 2023-06-06 052122](https://github.com/suptimusfika/demo-transaction-api-jmeter/assets/48064134/ee58dd1a-0e33-410f-8cb8-1f861b78b37c)

## Html Report
![Apache-JMeter-Dashboard](https://github.com/suptimusfika/demo-transaction-api-jmeter/assets/48064134/0bdcadb1-ed7f-4c03-8b7d-3abce19eff0e)
