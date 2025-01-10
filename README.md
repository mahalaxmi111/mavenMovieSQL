# Maven_Movies_Rental_Business_DA
Data analysis of movies CD/DVD rental (transactions) and inventory

# Maven Movies Data Analysis: Enhancing Insights for a Rental Business

## Project Overview:
This project analyzes a movie rental business's database to provide actionable insights for improving operations, marketing strategies, and inventory management. The dataset is hosted in the MAVENMOVIES database, and SQL was extensively used for exploratory data analysis (EDA), schema understanding, and answering business-critical ad-hoc queries.

## Project Objectives:

### Customer Insights:

Identify customer details (names, emails) for targeted marketing campaigns.
Analyze customer rental patterns to improve customer engagement.

### Movie Inventory Analysis:

Explore the rental inventory and classify movies based on rental rates and availability.
Provide recommendations for expanding the movie collection based on popularity and rental rates.
Revenue Optimization:

Analyze rental rates to identify trends and the profitability of various pricing categories.
Determine the most rented movie categories and ratings to maximize revenue.

### Operational Efficiency:

Help track and manage movie inventory effectively.
Highlight gaps in the inventory and optimize stock levels.


# Tools & Library Used
[![MySQL](https://github.com/user-attachments/assets/ee3c21b7-e789-41c4-aaf4-93164756dada)](https://www.mysql.com/) &nbsp;

# Project Result

[Click here to get full code](https://github.com/mahalaxmi111/mavenMovieSQL/blob/main/MOVIES_RENTAL_CODE.sql)

# Query Task

1. "How can we extract the first name, last name, and email address of all customers to prepare a comprehensive contact list for the marketing team?"

![email](https://github.com/user-attachments/assets/79df8525-d2c4-4493-a513-77cd2a15ede2)




2. "What is the total number of movies in the inventory that are available for rent at the lowest rental rate of $0.99?"

![CHEAPEST_RENTAL](https://github.com/user-attachments/assets/263304b7-30de-4341-8c3f-a89bc95d86a2)



3. "How can we categorize all movies based on their rental rates and determine the count of movies in each category?"

![TOTAL_FILMS](https://github.com/user-attachments/assets/5e2b1518-6122-43a5-ab45-a8b5d68605b1)




4. "Which movie rating (e.g., PG, PG-13, R) has the highest number of titles in the inventory, and how can this information help optimize inventory management?"

![rating_wise_count](https://github.com/user-attachments/assets/7b3dd621-77ec-4a46-bbc2-d39f27fad6b3)




5. "What is the total count of PG-rated movies that have been rented, and what does this indicate about customer preferences?"

![TOTAL_FILMS](https://github.com/user-attachments/assets/c11e68ec-5ec1-40ea-a279-36e04767010b)



6. "Can you provide a list of films categorized by their genre, along with their language and film name?"

![TLC](https://github.com/user-attachments/assets/ddca7efd-0b5f-4ab0-95ea-f674b1021da7)

7. "Can you provide a list of movies and the number of times each has been rented out?"

![popularity](https://github.com/user-attachments/assets/5d080e81-b8d6-464f-ac66-8f10ba303653)


8. "What are the top 10 highest-grossing films, and how much revenue has each generated?"

![REVENUE](https://github.com/user-attachments/assets/e31cd954-b727-4846-8932-8be8814ce3ae)


9. "Can we identify the store with the highest historical revenue, and how does it compare to others in the same region?"

![MOST_REVENUE](https://github.com/user-attachments/assets/ce0e1d56-440e-441e-98d3-4d962a75576c)



10. "How many movie rentals did we have in total each month over the past year?"

![RENTALS_PER_MONTH](https://github.com/user-attachments/assets/101c69cf-dd2a-4a58-ba7b-e49a65ac6f8e)

11. "How do we determine the rewards for users who have rented 30 or more times, and what details about their preferences should we consider?"

![REWARD_VIA_PHONE](https://github.com/user-attachments/assets/fe1ee2e6-a849-4fe6-adb5-57387578c970)


12. "Could you pull all payments from our first 100 customers (Based on customers id)"

![FIRST_100_CUSTOMER_PAYMENTS](https://github.com/user-attachments/assets/93a1fa1a-f52d-48d7-ad2f-c27d25515772)



13. "Now I’d love to see just payments over $5 for those same customers, since January 1, 2006"

![JAN_06_2006](https://github.com/user-attachments/assets/5696f432-ffca-4399-bd87-adb74af98c50)

14. "Now, could you please write a query to pull all payments from those specific customers, along with payments over $5, from any customer?"

![PAYMENTS_OVER_$5](https://github.com/user-attachments/assets/f0c6f66f-06b7-40f2-b00d-170564a7709c)

15. "We need to understand the special features in our films. Could you pull a list of films which include a Behind the Scenes special feature?"

![BTS](https://github.com/user-attachments/assets/ca0fdc2e-f515-423a-98b5-8a3d8710a286)


16. "Which customer qualifies as the top spender, and what rewards or points should we offer them?"

![MOST_SPENDING_CUSTOMER](https://github.com/user-attachments/assets/f8c13175-8740-465d-a8b8-5d714229f1d7)


17. "Could you please pull a count of titles sliced by rental duration?"

![SLICED_BY_RENTAL_RATE](https://github.com/user-attachments/assets/d5b4c571-eef0-458b-a637-d1b24f0412c3)



18. "How do movie ratings and lengths correlate with rental demand (number of movies rented) across various rental periods?"

![COMPARE_WITH_RENTAL_DURATION](https://github.com/user-attachments/assets/21266d45-4ded-4e55-b659-3d31041e71f4)


19. "I’m wondering if we charge more for a rental when the replacement cost is higher. Can you help me pull a count of films, along with the average, min, and max rental rate, grouped by replacement cost?"

![MIN_MAX_AVG](https://github.com/user-attachments/assets/b7e8e1a4-60b3-4a04-89d2-7fbb435b9da0)


20. "Which movies should be recommended to individuals based on specific demographics like cultural background or interests?"

![FIT_FOR_RECOMMENDATION](https://github.com/user-attachments/assets/b43b9514-6312-4c01-8d0e-bed5f818d205)


21. “I’d like to know which store each customer goes to, and whether or not they are active. Could you pull a list of first and last names of all customers, and label them as either ‘store 1 active’, ‘store 1 inactive’, ‘store 2 active’, or ‘store 2 inactive’?”

![ACTIVE_STORE](https://github.com/user-attachments/assets/f7320c81-82c9-4c9e-80ef-ccf101b38bd1)

22. “Can you pull for me a list of each film we have in inventory? I would like to see the film’s title, description, and the store_id value associated with each item, and its inventory_id. Thanks!”

![FILMS_IN_INVENTORY](https://github.com/user-attachments/assets/bf0493fe-5568-4948-8df0-e3dc1eebfde5)


23. "Can you list the movies that [FIRST_NAME] [LAST_NAME] has been part of, and how many are there in total?"

![NO_OF_FILMS_BY_ACTOR](https://github.com/user-attachments/assets/f4fe18e7-d2f3-422d-8982-81912d09824d)


24. “One of our investors is interested in the films we carry and how many actors are listed for each film title. Can you pull a list of all titles, and figure out how many actors are associated with each title?”

![ACTOR_ASSOCIATED_WITH_TITLE](https://github.com/user-attachments/assets/89399124-0cb7-49a6-9761-b5b06f70a044)


25. “Customers often ask which films their favorite actors appear in. It would be great to have a list of all actors, with each title that they appear in. Could you please pull that for me?” 

![FAV_ACTOR_APPEAR](https://github.com/user-attachments/assets/e8754202-1514-4b5e-bc47-5cbe52e6551f)


26.“The Manager from Store 2 is working on expanding our film collection there. Could you pull a list of distinct titles and their descriptions, currently available in inventory at store 2?”

![COLLECTION_OF_STORE_2](https://github.com/user-attachments/assets/0b2f49b6-6e9d-4c33-bdd7-db91e696acfa)


27.  “We will be hosting a meeting with all of our staff and advisors soon. Could you pull one list of all staff and advisor names, and include a column noting whether they are a staff member or advisor? Thanks!”

![UNION](https://github.com/user-attachments/assets/938a5342-7901-4e5d-bda0-b79f4dfb4d12)

