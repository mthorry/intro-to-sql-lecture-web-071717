# Intro to SQL

1. Install the SQLite Browser if you haven't already [here](http://sqlitebrowser.org/)
2. Open the SQLite Browser and click 'File -> Open DataBase'
3. Choose the `chinook.db` file from this repo. This database is open source and maintained by Microsoft (SQL is no fun if you don't have any data)


## What are the four things I can do with data?
+ Create It
+ Read It
+ Update It
+ Delete It


## Challenges

1. How would you return all of the rows in the artists table?
  ```SQL

  ```
2. How would you select the artist with the name "Black Sabbath"
  ```SQL

  ```
3. How would you create a table named 'fans' with an autoincrementing ID that's a primary key and a name field of type text

  ```sql

  ```

4. How would you alter the fans table to have a artist_id column type integer?

  ```sql

  ```
5. How would you add yourself as a fan of the Black Eyed Peas? ArtistId **169**
  ```sql

  ```

6. Check out the [Faker gem](https://github.com/stympy/faker). `gem install faker`, open up irb, run `require 'faker'` and then generate a fake name for yourself using `Faker::Name.name`. How would you update your name in the fans table to be your new name?
   ```sql

   ```

7. How would you return fans that are not fans of the black eyed peas.
  ```sql

  ```


8. I want to return the names of the artists and their number of rock tracks
 who play Rock music
and have move than 30 tracks in order of the number of rock tracks that they have
from greatest to least
