# Spending-Tracker-Java
Created GUI with javax.swing, MySQL connected via JDBC. Implemented tables for categories, spending details. Features include add/remove items, view monthly spending with totals, dynamic category addition, date-based spending view with category. Used prepared statements, date constraints for security, user interaction.


Created a GUI using javax.swing
Used mysql work bench to create the database tables and store the values in it
Created two tables one is for adding category
Other is the spending table where all the spending details is stored such as name, date,, purchased amount with a autoincrement id, cat_id
The user can pick a date fill the name and the amount and category and submit the details
Connection to mysql database is done using the JDBC(java database connectivity)
The app also display the list of items purchased in the current month along with the total sum of amount of all the items of that month
The user can remove the listings from the table as and when he wishes to
Also the user can add category by clicking the category option which brings in the new window
The entries of the category window once submitted are reflected in the mysql category table in the database
Also created a feature where the user can view spending based on the specified date
The view spending window is divided into two sections one is to view the spendings date wise and other is to view the spending date wise with category
The date picker is made interactive where the user cannot select the date beyond the current date while adding. And also in the view spending section once the starting date is picked user cannot pick the second date less then the starting date and more than the current date.
In both the sections in view spending tab the entries are displayed in a table and also total amount of each respective table entries are show.
Natural join is used when displaying the item details with category
Also used prepared statements to make the app sql injection free
