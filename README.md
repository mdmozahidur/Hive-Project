u.data -- The dataset has 100000 ratings by 943 users on 1682 movies. The file has 4 tab 
("\t") separated columns. The first column is the user id, the second column is the movie id, the 
third column is the rating, and the fourth column is a timestamp.

u.user -- Demographic information about the users; this has 5 pipe "|" separated columns. the 
first column is the user id, the second column is the age, the third column is the gender (Male 
denoted by 'M' and Female denoted by 'F'), the fourth column is the occupation, and the fifth 
column is the zip code. The user ids are the ones used in the u.data data set.

Copy u.data and u.user to the virtual machine (Filezilla)
Copy u.data and u.user from the virtual machine into HDFS (hadoop fs -put)
Create one table for u.data and one table for u.user in Hive

---How many unique female users provided at least one rating of 5 (in one single Hive 
query)?
---How many female and male users gave ratings of 4 and above to the movies (in one 
single Hive query)?
--- the top 5 age groups who gave the 5-rating to the movies (in one single Hive 
query)? 
---The female users belonging to which 5 occupations provided the most number of ratings
(in one single Hive query)?
