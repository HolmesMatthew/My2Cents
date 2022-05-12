# My2Cents
Helping you save your cents
> Capstone Project for PDX Codeguild
___

## Project Overview
Budget/Finacial app. The idea behind My2Cents is to streamline the budgeting process as much as possible. The User will select the budget they want to use, either by preset or a custom budget. Then using `Plaid Api` to gain access to User bank accounts, the app will sort through recent transactions and propose a budget allowing the User to make changes if necessary. The app will then highlight areas the User is spending an excess of money and recommend changes showing possible gains.

## Features
The most tedious part of a budget is setting it up, let ***My2Cents*** do it for you! Eliminate guesswork and save time with this all in one budget app with a clean and effective intuitive design

### You will be able to 
- login
- have access to all data provided by plaid
- have full control of budget 
- change budget preferences 
- change budget display type; pie chart, bar graph ext...
- track bills paid/unpaid 

## Data Model
Data working flow
- User
    - Account
    - Budget preferences
  
- Transaction history
- Savings Tracker
- Bills Tracker
  
## Schedule

### Week one
> User and basic budget 
- Initialize Plaid Api
- Set up basic User interface using Django
- Build basic budget model and user interface 
### Week Two
> Add Plaid functionality and add savings tracker
- Build transaction model
- Build savings tracker
### Week Three
> Add bills Model and start styling
- Build bills model
- Start Styling

### Week Four
> Finish styling and make last minute additions time permitting
- Finish styling
- Make last minute corrections/additions

_Top schedule **or** bottom?_

|Week One|Week Two|Week Three|Week Four|
| :---: | :---: | :---: | :---: |
|`User and basic budget:` Initialize Plaid Api, Set up basic User interface using Django, Build basic budget model and user interface.          |`Add Plaid functionality and add savings tracker:` Build transaction model, Build savings tracker                                              |`Add bills Model and start styling:` Build bills model, Start Styling                                                                            |`Finish styling and make last minute additions time permitting:` Finish styling, Make last minute corrections/additions|

## If time permits
- Add additional functionality: loan/credit calculator 
- Add additional functionality: 'snowball' debt calculator

