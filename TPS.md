### TPS Competition Questionnaire

*Please replace the square brackets and the text in it with your answers*

**Number of CPUs**

48

**Memory (GB)**

[How much memory does the machine have for running one cluster? For example, 16G.]

**Storage (GB)**

296 GB

**Network**

1 Gbps LAN

**Machine Type (Optional)**

[If you are using public cloud service, note down the name of the provider and the machine type. For example, AWS EC2 m5.2xlarge.]

**Command Lines for Running Cluster**
```
[Copy the command line here]
```

**Peak TPS**

4847.15

**Video URL**

[URL for the video showing how you produced the above TPS.]

**Output From `stats` Tool**
```
----------------------------------------------------------------------------------------------------
                                      QuarkChain Cluster Stats
----------------------------------------------------------------------------------------------------
CPU:                48
Memory:             296 GB
IP:                 localhost
Shards:             128
Servers:            128
Shard Interval:     10
Root Interval:      60
Syncing:            False
Mining:             True
Peers:              172.31.20.202:38291
----------------------------------------------------------------------------------------------------
Timestamp                     TPS   Pending tx  Confirmed tx       BPS      SBPS      ROOT       CPU
----------------------------------------------------------------------------------------------------
2018-10-24 22:24:58          0.00            0             0     19.60      0.00         1     79.98
2018-10-24 22:25:08          0.00            0             0     19.60      0.00         1     74.34
2018-10-24 22:25:18          0.00            0             0     19.60      0.00         1     79.69
2018-10-24 22:25:28          0.00         1200             0     19.62      0.00         1     84.99
2018-10-24 22:25:38        577.47        46872         34648     20.67      0.00         1     78.71
2018-10-24 22:25:48       3464.93       318312        207896     25.35      0.00         1     85.85
2018-10-24 22:25:58       4241.07       427192        254464     42.20      0.00         1     86.40
2018-10-24 22:26:08       4847.15       476003        288557     47.15      0.00         1     88.06
```

**Additional Comment**

[If you have special setup, e.g., running a single cluster over multiple machines, the above questionnaire might not fit. Note down
whatever you want us to know here to help evaluate the result.]
