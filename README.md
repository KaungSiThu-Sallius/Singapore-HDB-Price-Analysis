# HDB Resale Price Analysis  

## Overview  

Analyzed Singapore HDB resale prices to identify trends by town, flat type, and time.  

## Business Questions

```
Q1: Which town has the highest average resale price?
Q2: How do resale prices trend over time?
Q3: Which flat type (3-room, 4-room, etc.) is most expensive?
Q4: Which towns have average resale prices higher than the national average?
Q5: Find flats where the price is 20% higher than the average price in their town.
Q6: Compare each month’s average price to the previous month using subqueries.
```

### Q1: Which town has the highest average resale price?

![Screenshot 2025-01-29 at 10 01 13 AM](https://github.com/user-attachments/assets/46851d09-8a49-4c79-ad2b-73f0c394975b)

### Q2: How do resale prices trend over time?

![Screenshot 2025-01-29 at 10 02 09 AM](https://github.com/user-attachments/assets/fbff03c3-af8e-4d54-83bd-df6a83a64142)

### Q3: Which flat type (3-room, 4-room, etc.) is most expensive?

![Screenshot 2025-01-29 at 10 02 34 AM](https://github.com/user-attachments/assets/f440bb13-7d30-4d56-8b57-7f75b2e52b11)

### Q4: Which towns have average resale prices higher than the national average?

![Screenshot 2025-01-29 at 10 02 54 AM](https://github.com/user-attachments/assets/9aef3685-df2f-4320-a8db-ea6f5c1b875a)
![Screenshot 2025-01-29 at 10 34 09 AM](https://github.com/user-attachments/assets/bb56d53d-b372-4e24-a8e9-00fc659dca32)


### Q5: Find flats where the price is 20% higher than the average price in their town.

![Screenshot 2025-01-29 at 10 03 14 AM](https://github.com/user-attachments/assets/39df2667-0bb6-47f1-b6b3-23cf68dbc79a)

### Q6: Compare each month’s average price to the previous month using subqueries.

![Screenshot 2025-01-29 at 10 03 40 AM](https://github.com/user-attachments/assets/e1296074-3149-453a-be56-1fa04738c0a7)
![Screenshot 2025-01-29 at 10 34 26 AM](https://github.com/user-attachments/assets/b53c859c-1b14-4aff-ae61-a07a5e8114c7)


## Key Findings  

- Highest average resale price: **BUKIT TIMAH** (SGD 883k).
- Prices increased by **7% YoY** from JAN to DEC during 2024.  
- Most expensive flat type: **MULTI-GENERATION** (avg. SGD 1049k).  

## Tools Used  

- SQL (SQLite)  
- Python (pandas)  
