* Write to db first, write to cache later -> db become source of truth
Approach 1: [[Debezium]] sync the update to cache
Set

Approach 2: Run the SQL send to database, add the modification to select row data updated for cache to update (in case of CUD)
