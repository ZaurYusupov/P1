P1

# Hello World!
Robotic shopping assistants rule! 

The automation you will read about below is referred to as RoSA.

RoSA was built with certain required parameters and its creation and customization plays into a simulation scenario.  The scenario is simple enough, a well known regional vendor "Pega" signed an exclusive partnership deal with "RoSA" operator entrepreneur who provides shopping services to a select clientele (i.e an instacart shopper). To be able to focus on servicing clients, the entrepreneur deploys RoSA to shop and to help manage their records.

## RoSA, Robotic Shopping Assistant

### Project Scope

- 1 vendor : [Pega](https://training.openspan.com/login)
- 5 customers with 5 different credit cards and addresses
- Each shopping has at least 5 items
- Customer info is stored in DB
- Expense reports in excel and unique per customer
- Profit report in excel format
- Used both flowchart and sequence type workflows

### Functionalities

- Entrepreneur takes in customer shopping lists and shops for them in the pega platform.
  - Automated shopping by utilizing the order information and other client information stored in the database
  - RoSA records the expenses in a receipt and emails that to the client
  - RoSA records the Pega shopping expenses, also records the Pega order confirmation number and adds to the total a flat service fee for RoSA services.
    Shopping receipt is a dynamic preformatted excel sheet, with additional sheet showing the shoppers' original order form
  - Consumer/user friendly formatting, custom logo added for visual impact

- RoSA builds a profit report for the entrepreneur
  - Profit report contains: comissions from selling for Pega, showing both the percent value and the dollar value
  - FYI pega pays the entrepreneur 20% of the subtotal per shopping trip
  - Profit report separates out customers
  - Profit report is a dynamic preformatted excel sheet
  - Consumer/user friendly formatting, custom logo added for visual impact

### Tech Stack

- UiPath
- SQLServer
