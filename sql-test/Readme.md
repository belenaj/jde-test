# SQL test

## Introduction

In this exercise you will need to deploy a sample database (Chinook) and work on a few queries. In this repo we facilitate how to do it with PostgreSQL but you can do it as you like.

 - Option 1 - Install postgres SQL and deploy the Chinook_PostgreSql.sql file to have the Chinook database created.
 - Option 2 - Run the docker file in the repository:
```
           cd sql-chinook-test
           docker build . -t mypostgres
           docker run --name mypostgres -e POSTGRES_PASSWORD=postgres -d -p 5432:5432  mypostgres:latest
           user/database/password: postgres
```
 - Option 3 - Do it on your own -> https://github.com/lerocha/chinook-database

Chinook database diagram: https://www.sqlitetutorial.net/sqlite-sample-database/
 
Connect your favorite SQL client and build the queries described below.

We like clean, clear and readable code. Also we like that the code we execute is efficient.

## Exercices

1. Get how many tracks there is which composer is Queen

2. Get different album title and genres for Foo Fighters

3. Get playlist_id, playlist name and number of tracks of the top 10 playlist with more songs

4. Get playlist names which name is duplicated in the table (similar name and different id)

5. Get the average track duration by genre

6. Get all the Track names which are not present in any Playlist

7. Get all the Track names together with the number of times each track appears in playlists. 

8. Get the the longest track per Genre

## Work to deliver

Please provide one single file with all the queries above named as sql-test-done.txt

