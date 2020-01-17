# REMChain-Automated-Failover

#### These scripts will help a block producer perform a failover, in the event they fail to produce blocks within a specified timeframe.

***

### Setup Producer-Failover:

```
sudo wget https://github.com/remblock/REMChain-Automated-Failover/raw/master/producer-failover && sudo chmod u+x producer-failover && sudo ./producer-failover
```

***

### Edit Producer-Failover Config:

```
nano remblock/producer-failover/config
```

***

### Setup Backup-Failover:

```
sudo wget https://github.com/remblock/REMChain-Automated-Failover/raw/master/backup-failover && sudo chmod u+x backup-failover && sudo ./backup-failover
```

***

### Edit Backup-Failover Config:

```
nano remblock/backup-failover/config
```
