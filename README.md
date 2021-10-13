# AntlrSQL

Focusing on SQL analysis and function extensions (i.e. recommendation) using ANTLR. I am also planning to use this repo to include some implementation surveys for current SQL parsers. 
If possible, can we include SQL dialects with all-in-one ability?

---

## Thoughts
+ An intermediate layer that supports the common feature for the core sql ability 

+ 

+ An extension layer that supports dialect-wise features

+

+ Regenerate optimized sql statements for actual database engines

## Difficulties
1. Common features
2. Grammar file rewrites and reorganization
3. SQL element org and re-org
4. Check sql equalness

---

## TODOs
### SQL Analysis TODO
1. Dynamic grammar construction
2. Identifier (db, col, entity) recommendation
3. Error handling mechanism
4. SQL execution mechanism (engine)

### Parser Survey TODO
1. Parser implementation in TiDB
