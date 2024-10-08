### SQL or NoSQL


[![](https://github.com/donnemartin/system-design-primer/raw/master/images/wXGqG5f.png)](https://github.com/donnemartin/system-design-primer/blob/master/images/wXGqG5f.png)  
_[Source: Transitioning from RDBMS to NoSQL](https://www.infoq.com/articles/Transition-RDBMS-NoSQL/)_

Reasons for **SQL**:

- Structured data
- Strict schema
- Relational data
- Need for complex joins
- Transactions
- Clear patterns for scaling
- More established: developers, community, code, tools, etc
- Lookups by index are very fast

Reasons for **NoSQL**:

- Semi-structured data
- Dynamic or flexible schema
- Non-relational data
- No need for complex joins
- Store many TB (or PB) of data
- Very data intensive workload
- Very high throughput for IOPS

Sample data well-suited for NoSQL:

- Rapid ingest of clickstream and log data
- Leaderboard or scoring data
- Temporary data, such as a shopping cart
- Frequently accessed ('hot') tables
- Metadata/lookup tables
##### Source(s) and further reading: SQL or NoSQL
- [Scaling up to your first 10 million users](https://www.youtube.com/watch?v=kKjm4ehYiMs)
- [SQL vs NoSQL differences](https://www.sitepoint.com/sql-vs-nosql-differences/)