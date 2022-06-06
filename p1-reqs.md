p1 reqs:
# RoSA

Meet RoSA your robotic shopping assistant!

## Scenario

You're an entrepreneur that provides shopping services to a select clientele (i.e you're an instacart shopper). To be able to focus on your main service of shopping for your clients, you need a robot assitant to help you manage your records.

You recently launched a partnership with Pega. You now sell pega products. (You shop for your clients using Pega's platform).

## Functionalities

- You should still be able to take in customer shopping lists and shop for them in the pega platform.
  - Use the information you have on file (i.e the db) for the client to make the sale
  - Don't forget to record the expenses in a receipt and email that to the client
  - With regards to the expense report, still add the service base fee, store this in DB as well
- RoSA should build a profit report for you
  - Profit report should contain: comissions from selling for pega
  - FYI pega gives you 20% of the subtotal per shopping trip
  - Profit report should separate out customers
  - Profit report should be in excel format and emailed to you
- Bonus:
  - Take in from your inbox, emails of weekly shopping lists from a client stored in an excel sheet and place that order in pega and record the expense in the db
  - Hint:
    - You need to have a set format for the shopping lists
    - You need a pattern for the email subject
    - Standardize your inputs

## Tech Stack

- UiPath
- SQLServer

## Scope

- 1 vendor : [Pega](https://training.openspan.com/login)
- 5 customers with 5 different credit cards and addresses
- Each shopping should have at least 5 items
- Customer info is stored in DB, order/shopping trip history per customer is also stored in DB
- Weekly shopping lists per customer could be stored in DB, but if you want to accomplish the bonus feature, store it excel sheet and then record the items included in the shopping trip in the DB after shopping for them
- Expense reports still in excel and should be unique per customer
- Profit report should be in excel format
- Use both flowchart and sequence type workflows

## Note

- Automate as much as possible, I want little to no user input
- Unless necessary little to no user input