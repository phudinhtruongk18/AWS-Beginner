-tables are a collection of items
  - item are collection of attributes, key - value pairs
Primary key: Partition Key + Soft Key

GSI(Global Seconddary Index): Can use for query without scan all, cost
zzz

Let say that i have a list of Primary key (include Partition Key + Soft Key)
what should i do to get items right the way? (less than 100 items, retrieve up to 16 MB)
-> BatchGetItem
