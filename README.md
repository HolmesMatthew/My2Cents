# My2Cents
Helping you save your cents
> Capstone Project for PDX Codeguild
___

## Project Overview
Budget/Finacial app. The idea behind My2Cents is to steamline the budgeting process as much as possible. The User will select the budget they want to use, either by preset or a custom budget(accounting for: --). Then using Plaid Api to gain access to User bank accounts, the app will sort through recent transactions and propose a budget allowing the User to make changes if necessary. The app will then highlight areas the User is spending an excess of money
> The app will allow the User to skip linking their bank account and manualy enter their information.
## Features
The most tedius part of a budget is setting it up, let ***My2Cents*** do it for you! Eliminate guesswork and save time with this all in one budget app with a clean and effective intuitive design

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
    - Savings calculator
- Transaction history
- Bills paid/unpaid
> if time permits
>   - loan/credit calculator
>   - "snowball" debt calculator
>   
## Schedule

### Week one
> User and basic budget 
- Initialize Plaid Api
- Set up basic User interface using Django
- Build basic budget model and user interface 
### Week Two
> add Plaid functionality
- Build transaction model
- Start bils model
### Week Three
> Finish logic and begin styling
- Finish bills model
- Start Styling

### Week Four
> Finish styling and make last minute additions time permiting
- Finish styling
- Make last minute corrections/additions

_Top schedule **or** bottom?_

|Week One|Week Two|Week Three|Week Four|
| :---: | :---: | :---: | :---: |
|`User and basic budget:` Initialize Plaid Api, Set up basic User interface using Django, Build basic budget model and user interface|`add Plaid functionality:` Build transaction model, Start bills model|`Finish logic and begin styling:` Finish bills model, Start Styling|`Finish styling and make last minute additions time permitting:` Finish styling, Make last minute corrections/additions 

## If time permits
~Not Sure Yet~ 

