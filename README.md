UDACITY FSWD
PROJECT 3 - CATALOG -
BRIAN HARLIN
12/19/15


==============================================================
EchoChamber INTRODUCTION:
==============================================================

This is a catalog of music that everyone should hear. The intent is that a user will invite friends with similar tastes or 'good' taste in music to add music that they feel everyone should hear.

EchoChamber has been created using Flask, SqlAlchemy, sqlite, Vagrant, and JQuery.
It employs Google and Facebook for login authentication and authorization.

A user can view music without being logged in, however, will not be able to participate in adding, editing or deleting music.

A user that is logged in will have a unique user id. They will be authorized to any music they wish. They will be authorized also to edit and delete any music that they added. They will not, however, be authorized to edit or delete music that another user has added. Further, if a user A added an artist, but another user B added songs under that artist, user A (or any other user) will not have the authority to delete the artist as long as there are songs by that artist in the database. An Admin table has been added to the database for future use, that will allow the admin to delete any music. This will be possibly implemented in a future release.

==============================================================
INSTRUCTIONS:
==============================================================
