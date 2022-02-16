# bookmark_manager

```
As a user
So that I can see the bookmarks I have
I would like to see a list of all saved bookmarks
```

```
As a user
So that I can save websites I visit frequently
I would like to add new bookmarks
```

![Class Model](/public/ClassModel.png)

![Domain Model](/public/DomainModel.png)


#### Setting Up Database

- Connect to psql
- Create the database using the psql command CREATE DATABASE bookmark_manager;
- Connect to the database using the pqsl command \c bookmark_manager;
- Run the query saved in the file 01_create_bookmarks_table.sql
- Run the query saved in the file 02_create_bookmarks_table_test.sql