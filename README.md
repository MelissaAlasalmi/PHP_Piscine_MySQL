# PHP_Piscine_MySQL

For day 05 of the Piscine, we learned the basics of MySQL. Here's what each of my exercise submissions does.

Ex00 : db_malasalm
Creates a database named after my school login. This database will be used for the next exercises.

Ex01 : ft_table
Using the file "base_student.sql" located at the root of the repo to fill the database, this creates a table that is used to list students and staff.
The table contains the following:
- An id, the table’s primary key. It is auto-incremented.
- A login, with a maximum size of six characters. By default the value is "toto".
- A multiple choice group with only the following possibilities: "staff", "student", and "other".
- A creation_date: YYYY-MM-DD.

Ex02 : Mass data
Adds the following five users to "ft_table":
- ’loki’ is ’staff’, created on the ’2013-05-01’
- ’scadoux’ is ’student’, created on the ’2014-01-01’
- ’chap’ is ’staff’, created on the ’2011-04-27’
- ’bambou’ is ’staff’, created on the ’2014-03-01’
- ’fantomet’ is ’staff’, created on the ’2010-04-03’

Ex03 : Copy!
Uses the table "user_card" to find users with an ’a’ in their last_name to be copied into "ft_table".
- The login is only copied if its size is strictly less than 9 characters.
- The results of the query are ordered alphabetically in ascending order of last_name.
- The limit of the number of copied users is 10. 
- The last_name serves as login.
- The birthdate serves as creation_date. 
- These users are sorted into the ’other’ group.

Ex04 : Updates pending, please restart
The last exercise used the member’s birthdate as creation_date in "ft_table". Makes no sense! This updates the user’s creation_date by adding 20 years to it - but only for users that have an id larger than 5.

Ex05 : Little bit of cleaning
Removes the people manually inserted into "ft_table" in Ex02.

Ex06 : Where is vinc’ ?
Displays the title and summary of all movies containing ’Vincent’ in their summary - case-insensitive, ordered by ascending id_film.

Ex07 : 42 is everywhere!
Displays the title and summary of all movies containing 42 in their title or summary, ordered from the shortest film to the longest.

Ex08 : The good old days...
Displays the last_name, first_name, and birthdate (only the date, not the time) from the table "user_card" in a column named ’birthdate’.
- Only includes everyone born in 1989, listed alphabetically by last_name.

Ex09 : Short films
Displays the number of ’short films’ (with a duration less than or equal to 42) in a column named ’nb_short-films’.

Ex10 : Aren’t we good here?
Displays the title in a ’Title’ column, the summary in a ’Summary’ column, and the prod_year of every ’erotic’ movie, in descending order by production year.

Ex11 : Money is essential
Displays the last_name in uppercase in a ’NAME’ column, the first_name, and the price of users who have a subscription with a value higher than 42 euros. Results are listed in ascending order by last_name and by ascending first_name.

Ex12 : Why simplify things when they can be complicated?
Displays the last_name and first_name of every person with a composed last_name and/or first_name, alphabetically, by last_name followed by first_name.

Ex13 : Are you good at maths?
Displays in a column named ’average’ the average number (rounded up to the nearest unit) of seats in each cinema.

Ex14 : You, you will read again...
For each floor, displays the floor_number in a ’floor’ column and nb_seats by floor in a ’seats’ column, ordered by floor with the highest number of seats to the least.

Ex15 : What’s your phone number?
Displays all the distributors’ phone_number in a column named ’rebmunenohp’, only if they start with ’05’ - listed by removing the number 0 before the 5, and by reverting the numbers (ex :0542842169 -> 961248245).

