Problems:
- Cached table can be query in many places, many file DAOs, many methods in file DAO -> can apply but it will make the code complicated. It's better to implement if query access table at only 1 place.
- Need to know the values cause we need to update cache before we update to the db, so at some complicated query -> dont have the values to update -> can run the sql on the cache but it too slow (idk why :> - should not be slow) + need to load all data of tables to cache (too heavy)
- [[MapLoader]]
- [[MapStore]]