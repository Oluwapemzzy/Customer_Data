# Customer Data
Customer Segmentation for a Subscription Service.

I used the same excel workbook for both Project 1 and Project 2

## MICROSOFT EXCEL STEPS
- I cleaned my dataset by selecting the dataset using ctrl+shift+end to select my dataset, then I clicked DATA on the toolbar then clicked on remove duplicates. This helped me removed any duplicate rows.
- I eliminated all blank spaces by selecting the dataset then click on DATA in the tool bar then I selected "Find and select", look for "special", clicked on "blanks", then the blank spaces was selected and then i deleted.
- My dataset was clean and ready and read to use
- I proceeded to do the project task where I was to find the subscription pattern, average subscription duration and identify the most popular
subscription types.


### Subscription Pattern

The goal is to understand the behavior of customers in terms of their subscriptions. I tried revealing the Subscription patterns by calculating insights such as:
  1. Which subscription types are most or least popular.
 
 ![Subscription Type](https://github.com/user-attachments/assets/d3402ff5-ed27-4c87-880d-288d2ea0f683)

  2. Revenue generated per customer or per subscription type.
 
  ![Revenue Generated](https://github.com/user-attachments/assets/8b61c6af-9b95-4f15-84cf-1bcfff90764a)

  3. The cancellation rates across different types or regions.
 
  ![Cancelation Rate](https://github.com/user-attachments/assets/7e69f32e-f240-439c-b630-ae47cfe006cc)

  4. Average revenue generated per customer or per subscription Region.

  ![Average Revenue](https://github.com/user-attachments/assets/824f4bc1-6280-496a-9c7b-1fa354c63396)

  5. Average Duration

  ![Average Duration](https://github.com/user-attachments/assets/e01c4ec0-03e7-47c4-948a-8275bc9ec2d6)

This approach should provide a comprehensive overview of the subscription patterns within the data, allowing you to identify high-revenue areas, popular subscription types, and potential retention issues.


- I calculated the average subscription duration using pivot table and identifed the most popular
subscription types to be **BASIC**

![Basic](https://github.com/user-attachments/assets/d902607a-9224-4849-a8e2-2ba98fb7526c)



## MY SQL
1. Retrieve the total number of customers from each region.

![1](https://github.com/user-attachments/assets/16a36460-cd37-4c12-bcde-2eadaede36e7)

2. Find the most popular subscription type by the number of customers.

![2](https://github.com/user-attachments/assets/dc934b77-df89-4988-ba0b-babe932e53df)

3. Find customers who canceled their subscription within 6 months.

![3](https://github.com/user-attachments/assets/713d3955-222f-448c-b0f0-18b7c1e5b63c)

4. Calculate the average subscription duration for all customers.

![4](https://github.com/user-attachments/assets/41a4e964-7ab4-4af2-acb4-8b2c20c6bced)

5. Find customers with subscriptions longer than 12 months.

![Uploading 5.PNG…]()

6. Calculate total revenue by subscription type.

![6](https://github.com/user-attachments/assets/d9441172-85cd-4c89-952c-48b5d7ece02b)

7. Find the top 3 regions by subscription cancellations.

![7](https://github.com/user-attachments/assets/cbd43cd8-efdb-4fc8-837a-d1aea000d6ae)

8. Find the total number of active and canceled subscriptions.

![8](https://github.com/user-attachments/assets/6353b516-35f9-4636-94b0-ab6ac4c2c190)

