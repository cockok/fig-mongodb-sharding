fig-mongodb-sharding
====================

# Using

```shell
fig up -d
# Wait a few minutes.
fig run client mongo mongos/admin
sh.addShard("shard1:27018")
sh.addShard("shard2:27018")
```

# Memo

- MongoDB ports
 - default 27017
 - shard 27018
 - config 27019
