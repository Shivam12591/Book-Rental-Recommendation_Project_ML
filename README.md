Book Rental Recommendation
Project 

DESCRIPTION
Book Rent is the largest online and offline book rental chain in India. They provide books of various 
genres, such as thrillers, mysteries, romances, and science fiction. The company charges a fixed 
rental fee for a book per month. Lately, the company has been losing its user base. The main reason 
for this is that users are not able to choose the right books for themselves. The company wants to 
solve this problem and increase its revenue and profit.

Project Objective:
You, as an ML expert, should focus on improving the user experience by personalizing it to the 
user's needs. You have to model a recommendation engine so that users get recommendations for 
books based on the behavior of similar users. This will ensure that users are renting the books 
based on their tastes and traits.

Note: You have to perform user-based collaborative filtering and item-based collaborative filtering.

Dataset description:
BX-Users: It contains the information of users.
a. user_id - These have been anonymized and mapped to integers
b. Location - Demographic data is provided
c. Age - Demographic data is provided
If available, otherwise, these fields contain NULL-values.

BX-Books:
a. isbn - Books are identified by their respective ISBNs. Invalid ISBNs have already been removed from 
the dataset.
b. book_title
c. book_author
d. year_of_publication
e. publisher

BX-Book-Ratings: Contains the book rating information.
a. user_id
b. isbn
c. rating - Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1–10 (higher values 
denoting higher appreciation), or implicit, expressed by 0.

Note: Download the "BX-Book-Ratings.csv", "BX-Books.csv", "BX-Users.csv", and 
"Recommend.csv" using the link given in the Book Rental Recommendation project problem 
statement.

Following operations should be performed:
1. Read the books dataset and explore it
2. Clean up NaN values
3. Read the data where ratings are given by users
4. ake a quick look at the number of unique users and books
5. Convert ISBN variables to numeric numbers in the correct order
6. Convert the user_id variable to numeric numbers in the correct order
7. Convert both user_id and ISBN to the ordered list, i.e., from 0...n-1
8. Re-index the columns to build a matrix
9. Split your data into two sets (training and testing)
10. Make predictions based on user and item variables
11. Use RMSE to evaluate the prediction
