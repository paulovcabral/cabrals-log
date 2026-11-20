---
title: Welcome to Cabral's Log
description: First entry in the logbook. What this blog is about and what's coming next.
tags: meta, postgresql, aws
---
# Welcome to Cabral's Log

This is the first entry in my logbook.

I'm a database engineer, and most of my days are spent with **PostgreSQL**.
Here I'll share practical notes from that work, along with posts about the
other data stores I use: **DynamoDB**, **ElastiCache**, and the wider **AWS** ecosystem.

## What to expect

- **PostgreSQL deep dives**: query plans, indexing, MVCC, vacuum, replication
- **Beyond Postgres**: DynamoDB data modeling, caching strategies with ElastiCache
- **Field notes**: incidents, lessons learned, and things I wish I'd known earlier

## A taste of what's ahead

```sql
EXPLAIN (ANALYZE, BUFFERS)
SELECT *
FROM orders
WHERE customer_id = 42
ORDER BY created_at DESC
LIMIT 10;
```

Understanding what that output is really telling you is a good place to start.
More soon.
