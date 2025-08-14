# [SQL in BigQuery] Explore Ecommerce Dataset 
# I. Introduction
I explored this eCommerce dataset to practice my **analytical mindset** in calculating **useful information** for various reports. By using SQL on the  BigQuery platform, I solved **data mining** and **exploration problems**, including joining data from separate spreadsheets related to eCommerce transactions.
# II. Dataset Access 
* Log in to your Google Cloud Platform account and create a new project.
* Navigate to the BigQuery console and select your newly created project.
* In the navigation panel, select "Add Data" and then "Search a project".
* Enter the project ID "bigquery-public-data.google_analytics_sample.ga_sessions" and click "Enter".
* Click on the "ga_sessions_" table to open it.
# III. Exploring the Dataset
## Query 01: calculate total visit, pageview, transaction for Jan, Feb and March 2017 (order by month).
### SQL code:
![image](https://github.com/user-attachments/assets/14dcaedf-e5ec-40aa-a758-040408c4c3e1)
### SQL result:
![image](https://github.com/user-attachments/assets/f084bcf6-7482-4cae-9ce0-97744341a157)
## Query 02: Bounce rate per traffic source in July 2017 (Bounce_rate = num_bounce/total_visit) (order by total_visit DESC).
### SQL code:
![image](https://github.com/user-attachments/assets/809e14ce-447d-4ef2-b3bc-da3b9f85c8f3)
### SQL result:
![image](https://github.com/user-attachments/assets/2ed138a0-ed47-41ab-bb38-c40d2a4f5407)
## Query 3: Revenue by traffic source by week, by month in June 2017.
### SQL code:
![image](https://github.com/user-attachments/assets/fdae3024-aa6a-42b3-bbf0-10d515b0a006)
### SQL result:
![image](https://github.com/user-attachments/assets/9f0adca6-1aea-4ecb-b9f5-16939e5ae271)
## Query 04: Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017.
### SQL code:
![image](https://github.com/user-attachments/assets/6f0d5c5e-136d-43f4-b10c-10c14ecd675d)
![image](https://github.com/user-attachments/assets/3742e204-6908-4fa9-a3ec-7a7cf462f5b5)
![image](https://github.com/user-attachments/assets/0a0a7e9a-b773-4e27-ae0c-d26a74e128ea)
### SQL result:
![image](https://github.com/user-attachments/assets/249742ea-c97a-4d4e-aae6-8908aa3c44bb)
## Query 05: Average number of transactions per user that made a purchase in July 2017.
### SQL code:
![image](https://github.com/user-attachments/assets/46d4dc65-eb0a-4a22-af10-9b2db022dcd3)
![image](https://github.com/user-attachments/assets/cd2e146d-e7d3-4d74-95a8-c8a423945d74)
![image](https://github.com/user-attachments/assets/5ed3bcd8-2fd6-4848-bfc6-1fa5dbfab5bb)
### SQL result:
![image](https://github.com/user-attachments/assets/ea3b4206-556c-48e0-951d-8d59119a1757)
## Query 06: Average amount of money spent per session. Only include purchaser data in July 2017.
### SQL code:
![image](https://github.com/user-attachments/assets/fe912edc-30f2-42d6-b669-5f794f001aec)
### SQL result:
![image](https://github.com/user-attachments/assets/20b9e68e-f785-4841-93a9-2220d6c4a8bc)
## Query 07: Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. 
### SQL code:
![image](https://github.com/user-attachments/assets/7a4a477e-3c4f-4ec5-89d6-7bac873bf182)
![image](https://github.com/user-attachments/assets/d35ace2c-311c-40fc-8142-2441657ec1d7)
![image](https://github.com/user-attachments/assets/70425c06-b8af-4202-8165-334114c36136)
### SQL result:
![image](https://github.com/user-attachments/assets/79a4bcb0-c918-4680-9ef3-8e89878d572d)
## "Query 08: Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017. For example, 100% product view then 40% add_to_cart and 10% purchase.
Add_to_cart_rate = number product  add to cart/number product view. Purchase_rate = number product purchase/number product view. The output should be calculated in product level."
### SQL code:
![image](https://github.com/user-attachments/assets/38876987-14b8-4244-9b82-0b703821443a)
![image](https://github.com/user-attachments/assets/1631d6d9-24f4-4a04-8cfe-948ce4c9eab6)
![image](https://github.com/user-attachments/assets/f04185de-e558-4614-b1c7-6b31d2393736)
![image](https://github.com/user-attachments/assets/a1f69480-ad57-45ed-bde7-80351f7c674f)
### SQL result:
![image](https://github.com/user-attachments/assets/10791443-5924-4085-81e0-3cb260140f27)
# IV. Conclusion
In conclusion, my exploration of the eCommerce dataset using SQL on Google BigQuery has provided **valuable insights** into **essential metrics** such as total visits, pageviews, transactions, bounce rate, and revenue per traffic source. These insights offer a solid foundation for **data-driven decision-making**, helping businesses **optimize performance** and understand **customer behavior** more effectively. To gain a deeper understanding of key trends and patterns, the next step will be to visualize the data using tools like Power BI or Tableau, enhancing clarity and accessibility for stakeholders. Overall, this project demonstrates the power of combining SQL with big data tools like Google BigQuery to **efficiently analyze large datasets and extract actionable insights**.
