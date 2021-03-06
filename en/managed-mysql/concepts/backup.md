# Backups

[!KEYREF mmy-short-name] provides automatic and manual database backups. Backups take up space in the storage allocated to the cluster. If the total amount of data and backups exceeds the amount of storage, the excess is charged at the corresponding [rates](../pricing.md).

Automatic [physical backups](https://dev.mysql.com/doc/refman/5.7/en/backup-types.html) of all data in a cluster are created once a day. You can't disable automatic backups, but you can change the period for storing automatic backups (by default, it is seven days).

To restore a cluster from a backup, [follow the instructions](../operations/cluster-backups.md).

