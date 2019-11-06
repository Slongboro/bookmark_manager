Set up the database 
- to access = psql postgres
- CREATE DATABASE bookmark_manager;
- CREATE DATABASE "bookmark_manager_test";
- connect to \c bookmark_manager;
- CREATE TABLE bookmarks(id SERIAL PRIMARY KEY, url VARCHAR(60));
handy tips
- list databases = \l
- list tables = \dt
- leave psql = \q

User Story
As a busy internet user
So that I can quickly access my favourite websites
I would like to see a list of bookmarks

As a user
So I can store bookmark data for later retrieval
I want to add a bookmark to Bookmark Manager