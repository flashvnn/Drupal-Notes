Drupal-Notes
============

###Drush Commands

**Export Database to File**


> drush cc
>
> drush sql-dump > ~/my-sql-dump-file-name.sql

**Import Database**

> drush sql-drop
>
> drush sql-cli < ~/my-sql-dump-file-name.sql

### Redis

**Clear all database**
With redis-cli

> FLUSHDB       - Removes data from your connection's CURRENT database.

> FLUSHALL      - Removes data from ALL databases.
