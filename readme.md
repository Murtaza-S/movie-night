# Movie Night

## To use the software :

- ./dn <command>


## command :

- ls-genre -> list the genre

- ls-towatch -> gives to be watched films. [-limit -> to limit on movie suggestions or list]

- ls-watched -> showcases the movies you have watch

- surprise-me -genre='Genre' -> suggests a title from the genre that is not watched.

- rm -id=unique_id -> This removes the movie from the database

- watched -id=unique-id -> Converts the movie as watched

- add -title='Movie' -genre='Genre' -year=year-of-release


## Extention:

- -limit=LIMIT -> limits the number of suggestions in ls-towatch, ls-genre, ls-watched


## Initialize your database:

- Change the path of the database in db-handle->consts.go

sqlite3 path/to/db -init path/to/init/command
