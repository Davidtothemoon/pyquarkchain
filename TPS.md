### TPS Competition Questionnaire

*Please replace the square brackets and the text in it with your answers*

**Number of CPUs**

96

**Memory (GB)**

[How much memory does the machine have for running one cluster? For example, 16G.]

**Storage (GB)**

747

**Network**

1G

**Machine Type (Optional)**

[If you are using public cloud service, note down the name of the provider and the machine type. For example, AWS EC2 m5.2xlarge.]

**Command Lines for Running Cluster**
```
master:
pypy3 cluster.py --num_shards=1024 --num_slaves=64 --mine
```

**Peak TPS**

17165.72

**Video URL**

https://youtu.be/oBmiYM-v3o8

**Output From `stats` Tool**
```
----------------------------------------------------------------------------------------------------
                                      QuarkChain Cluster Stats
----------------------------------------------------------------------------------------------------
CPU:                96
Memory:             747 GB
IP:                 localhost
Shards:             1024
Servers:            64
Shard Interval:     10
Root Interval:      60
Syncing:            False
Mining:             True
Peers:              172.31.26.48:38291, 172.31.23.189:38291
----------------------------------------------------------------------------------------------------
Timestamp                     TPS   Pending tx  Confirmed tx       BPS      SBPS      ROOT       CPU
----------------------------------------------------------------------------------------------------
2018-10-24 21:55:04          0.00            0             0     32.80      0.00         1     59.41
2018-10-24 21:55:14          0.00          600             0     32.82      0.00         1     61.49
2018-10-24 21:55:24          0.00          600             0     32.82      0.00         1     62.82
2018-10-24 21:55:34          0.00          600             0     32.82      0.00         1     64.13
2018-10-24 21:55:44          0.00         5384             0     32.88      0.00         1     65.93
2018-10-24 21:55:54         37.87        12712          2272     33.02      0.00         1     64.45
2018-10-24 21:56:05       1741.87       223648        104512     35.97      0.00         1     65.74
2018-10-24 21:56:15       8387.47      1108056        503248     47.12      0.00         1     66.46
2018-10-24 21:56:25       9334.13      1239240        560048     48.58      0.00         1     65.30
2018-10-24 21:56:35       9372.00      1245904        562320     48.63      0.00         1     65.83
2018-10-24 21:56:45       9712.93      1287272        582208     48.38      0.00         1     65.55
2018-10-24 21:56:55      10726.77      1338498        640198     46.33      0.00         1     62.19
2018-10-24 21:57:05      13399.50      1589254        831802     39.18      0.00         1     65.42
2018-10-24 21:57:15      15143.73      1829712        975080     33.70      0.00         1     65.99
2018-10-24 21:57:25      15968.87      1993516       1056396     31.00      0.00         1     65.80
2018-10-24 21:57:35      16243.80      2043828       1081980     30.40      0.00         2     66.38
2018-10-24 21:57:48      16566.27      2095640       1120072     29.98      0.00         2     66.45
2018-10-24 21:57:58      16956.12      2225782       1228666     30.20      0.00         2     67.19
2018-10-24 21:58:08      17165.72      2361189       1334411     30.28      0.00         2     67.08
```

**Additional Comment**

[If you have special setup, e.g., running a single cluster over multiple machines, the above questionnaire might not fit. Note down
whatever you want us to know here to help evaluate the result.]
