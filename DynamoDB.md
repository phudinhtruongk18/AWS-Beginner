-tables are a collection of items
  - item are collection of attributes, key - value pairs
Primary key: Partition Key + Soft Key

GSI(Global Seconddary Index): Can use for query without scan all, cost
zzz

Let say that i have a list of Primary key (include Partition Key + Soft Key)
what should i do to get items right the way? (less than 100 items, retrieve up to 16 MB)
-> BatchGetItem

GSI vs LSI
https://www.dynamodbguide.com/local-or-global-choosing-a-secondary-index-type-in-dynamo-db/#:~:text=A%20global%20secondary%20index%20is%20a%20more%20vanilla%20version%20of,the%20same%20partition%20key%20requirement.
