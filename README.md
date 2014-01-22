# Group Travel

## User Stories

1. As a user, I want to insert my flight information
2. As a user, I want to see my friends' flight information
3. As a user, I want to add hotel information (direction, price, check-in, check-out time)
4. As a user, I want to be able to put in shared purchases
5. As a user, I want to be able to pay back my friends (Venmo, Paypal, QuickPay etc.)
6. As a user, I want to be able to track flight status of my friends
7. As a user, I want send messages via GroupChat, iMessage etc.
8. As a user, I want to share trip ideas and start a discussion page
9. As a user, I want to be able to vote on ideas
10. As a user, I want to be able to invite my friends to the website
11. As a user, I want to organize a video chat (Google Hangout, Skype etc.)
12. As a user, I want to be update on travel restrictions, visas etc
13. As an admin, I want to be able to control read/write permission

## Domain Modeling

Users

| Id (integer) | First (string) | Last (string) |
| ------------ | -------------- | ------------- | 
| 1            | Stephen        | Crump         |
| 2            | Eric           | Lee           |      
| 3            | Wonjun         | Lee           | 
| 4            | Jon            | Finch         |

Airline

| Id (integer) | Name (text)        | Cost (integer) | Covered by (integer) |
| ------------ | ------------------ | -------------- | -------------------- |
| 1            | Airbnb             | 450            | 1                    |
| 2            | Rental car         | 200            | 2                    |  
| 3            | Groceries          | 120            | 2                    |

Payments

| Id (integer) | Expense id (integer) | Payor (integer) | Payee (integer) |
| ------------ | -------------------- | --------------- | --------------- |
| 1            | 1                    | 1               | 2               |
| 2            | 1                    | 1               | 3               |  
| 3            | 1                    | 1               | 4               |
