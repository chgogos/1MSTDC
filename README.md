# One Machine Scheduling with Time Dependent Capacity

## Problem description

In total 190 problem instances exist. 

**Format of problem instances**

An example:  
```
NOP: 12
NINT: 6
0 2 1
2 4 2 
4 6 3
6 10 4
10 12 3
12 300000 2
1 4 4
2 4 9
3 2 13
4 3 4 
5 4 7
6 3 8
7 2 10
8 3 3 
9 2 13 
10 3 5 
11 3 9
12 5 7 
```

Explanation of the above format
```
NOP: followed by the number of jobs
NINT: followed by the number of intervals
NINT rows with time intervals: from to capacity
NOP rows with jobs: id duration due
```

**Format of problem solutions**

```
8 0 0
4 1 2
10 0 3
1 2 4
6 1 5
11 0 6
2 1 8
5 3 6
12 0 9
7 2 8
9 1 12
3 2 10
```

Explanation of the above format

```
Each row refers to a job id, the lane id where it is put and the start time of the job
```

A graphical representation of the solution (lanes are the horizontal strips of the capacity, numbered bottom-up)

![](./images/example1_cost20.png)

## Results

The name of each problem instance conforms to i&lt;n&gt;\_&lt;MC&gt;\_&lt;k&gt; 

* n is the number of jobs
* MC is the Maximum Capacity
* k is an identification number for the problem instance of the specific set


| Problem                                              |   Known best |   Our's best | Filename                                                             |
|:-----------------------------------------------------|-------------:|-------------:|:---------------------------------------------------------------------|
| [i120_3_1](./problem_instances/i120_3_1.txt)         |          848 |          848 | [i120_3_1_cost848.sol](./solutions/i120_3_1_cost848.sol)             |
| [i120_3_2](./problem_instances/i120_3_2.txt)         |         3568 |         3570 | [i120_3_2_cost3570.sol](./solutions/i120_3_2_cost3570.sol)           |
| [i120_3_3](./problem_instances/i120_3_3.txt)         |         2410 |         2410 | [i120_3_3_cost2410.sol](./solutions/i120_3_3_cost2410.sol)           |
| [i120_3_4](./problem_instances/i120_3_4.txt)         |         1019 |         1019 | [i120_3_4_cost1019.sol](./solutions/i120_3_4_cost1019.sol)           |
| [i120_3_5](./problem_instances/i120_3_5.txt)         |         3858 |         3858 | [i120_3_5_cost3858.sol](./solutions/i120_3_5_cost3858.sol)           |
| [i120_3_6](./problem_instances/i120_3_6.txt)         |         3120 |         3120 | [i120_3_6_cost3120.sol](./solutions/i120_3_6_cost3120.sol)           |
| [i120_3_7](./problem_instances/i120_3_7.txt)         |          720 |          720 | [i120_3_7_cost720.sol](./solutions/i120_3_7_cost720.sol)             |
| [i120_3_8](./problem_instances/i120_3_8.txt)         |         4084 |         4084 | [i120_3_8_cost4084.sol](./solutions/i120_3_8_cost4084.sol)           |
| [i120_3_9](./problem_instances/i120_3_9.txt)         |         1663 |         1663 | [i120_3_9_cost1663.sol](./solutions/i120_3_9_cost1663.sol)           |
| [i120_3_10](./problem_instances/i120_3_10.txt)       |         1268 |         1268 | [i120_3_10_cost1268.sol](./solutions/i120_3_10_cost1268.sol)         |
| [i120_5_1](./problem_instances/i120_5_1.txt)         |         1030 |         1030 | [i120_5_1_cost1030.sol](./solutions/i120_5_1_cost1030.sol)           |
| [i120_5_2](./problem_instances/i120_5_2.txt)         |         1511 |         1514 | [i120_5_2_cost1514.sol](./solutions/i120_5_2_cost1514.sol)           |
| [i120_5_3](./problem_instances/i120_5_3.txt)         |          959 |          959 | [i120_5_3_cost959.sol](./solutions/i120_5_3_cost959.sol)             |
| [i120_5_4](./problem_instances/i120_5_4.txt)         |          496 |          496 | [i120_5_4_cost496.sol](./solutions/i120_5_4_cost496.sol)             |
| [i120_5_5](./problem_instances/i120_5_5.txt)         |         3061 |         3061 | [i120_5_5_cost3061.sol](./solutions/i120_5_5_cost3061.sol)           |
| [i120_5_6](./problem_instances/i120_5_6.txt)         |          455 |          455 | [i120_5_6_cost455.sol](./solutions/i120_5_6_cost455.sol)             |
| [i120_5_7](./problem_instances/i120_5_7.txt)         |          519 |          519 | [i120_5_7_cost519.sol](./solutions/i120_5_7_cost519.sol)             |
| [i120_5_8](./problem_instances/i120_5_8.txt)         |         1214 |         1214 | [i120_5_8_cost1214.sol](./solutions/i120_5_8_cost1214.sol)           |
| [i120_5_9](./problem_instances/i120_5_9.txt)         |         3223 |         3231 | [i120_5_9_cost3231.sol](./solutions/i120_5_9_cost3231.sol)           |
| [i120_5_10](./problem_instances/i120_5_10.txt)       |         1131 |         1131 | [i120_5_10_cost1131.sol](./solutions/i120_5_10_cost1131.sol)         |
| [i120_7_1](./problem_instances/i120_7_1.txt)         |         1120 |         1121 | [i120_7_1_cost1121.sol](./solutions/i120_7_1_cost1121.sol)           |
| [i120_7_2](./problem_instances/i120_7_2.txt)         |         2725 |         2725 | [i120_7_2_cost2725.sol](./solutions/i120_7_2_cost2725.sol)           |
| [i120_7_3](./problem_instances/i120_7_3.txt)         |         3493 |         3505 | [i120_7_3_cost3505.sol](./solutions/i120_7_3_cost3505.sol)           |
| [i120_7_4](./problem_instances/i120_7_4.txt)         |         4021 |         4028 | [i120_7_4_cost4028.sol](./solutions/i120_7_4_cost4028.sol)           |
| [i120_7_5](./problem_instances/i120_7_5.txt)         |         3059 |         3078 | [i120_7_5_cost3078.sol](./solutions/i120_7_5_cost3078.sol)           |
| [i120_7_6](./problem_instances/i120_7_6.txt)         |         2640 |         2640 | [i120_7_6_cost2640.sol](./solutions/i120_7_6_cost2640.sol)           |
| [i120_7_7](./problem_instances/i120_7_7.txt)         |         1655 |         1655 | [i120_7_7_cost1655.sol](./solutions/i120_7_7_cost1655.sol)           |
| [i120_7_8](./problem_instances/i120_7_8.txt)         |         3225 |         3225 | [i120_7_8_cost3225.sol](./solutions/i120_7_8_cost3225.sol)           |
| [i120_7_9](./problem_instances/i120_7_9.txt)         |         4470 |         4474 | [i120_7_9_cost4474.sol](./solutions/i120_7_9_cost4474.sol)           |
| [i120_7_10](./problem_instances/i120_7_10.txt)       |          493 |          493 | [i120_7_10_cost493.sol](./solutions/i120_7_10_cost493.sol)           |
| [i120_10_1](./problem_instances/i120_10_1.txt)       |          746 |          749 | [i120_10_1_cost749.sol](./solutions/i120_10_1_cost749.sol)           |
| [i120_10_2](./problem_instances/i120_10_2.txt)       |         1124 |         1125 | [i120_10_2_cost1125.sol](./solutions/i120_10_2_cost1125.sol)         |
| [i120_10_3](./problem_instances/i120_10_3.txt)       |         1442 |         1453 | [i120_10_3_cost1453.sol](./solutions/i120_10_3_cost1453.sol)         |
| [i120_10_4](./problem_instances/i120_10_4.txt)       |          887 |          887 | [i120_10_4_cost887.sol](./solutions/i120_10_4_cost887.sol)           |
| [i120_10_5](./problem_instances/i120_10_5.txt)       |         1447 |         1449 | [i120_10_5_cost1449.sol](./solutions/i120_10_5_cost1449.sol)         |
| [i120_10_6](./problem_instances/i120_10_6.txt)       |         1118 |         1118 | [i120_10_6_cost1118.sol](./solutions/i120_10_6_cost1118.sol)         |
| [i120_10_7](./problem_instances/i120_10_7.txt)       |         2463 |         2463 | [i120_10_7_cost2463.sol](./solutions/i120_10_7_cost2463.sol)         |
| [i120_10_8](./problem_instances/i120_10_8.txt)       |          721 |          721 | [i120_10_8_cost721.sol](./solutions/i120_10_8_cost721.sol)           |
| [i120_10_9](./problem_instances/i120_10_9.txt)       |          977 |          983 | [i120_10_9_cost983.sol](./solutions/i120_10_9_cost983.sol)           |
| [i120_10_10](./problem_instances/i120_10_10.txt)     |          820 |          820 | [i120_10_10_cost820.sol](./solutions/i120_10_10_cost820.sol)         |
| [i250_10_1](./problem_instances/i250_10_1.txt)       |         4094 |         4103 | [i250_10_1_cost4103.sol](./solutions/i250_10_1_cost4103.sol)         |
| [i250_10_2](./problem_instances/i250_10_2.txt)       |          506 |          506 | [i250_10_2_cost506.sol](./solutions/i250_10_2_cost506.sol)           |
| [i250_10_3](./problem_instances/i250_10_3.txt)       |         1349 |         1349 | [i250_10_3_cost1349.sol](./solutions/i250_10_3_cost1349.sol)         |
| [i250_10_4](./problem_instances/i250_10_4.txt)       |         4731 |         4731 | [i250_10_4_cost4731.sol](./solutions/i250_10_4_cost4731.sol)         |
| [i250_10_5](./problem_instances/i250_10_5.txt)       |         6390 |         6391 | [i250_10_5_cost6391.sol](./solutions/i250_10_5_cost6391.sol)         |
| [i250_10_6](./problem_instances/i250_10_6.txt)       |         6280 |         6284 | [i250_10_6_cost6284.sol](./solutions/i250_10_6_cost6284.sol)         |
| [i250_10_7](./problem_instances/i250_10_7.txt)       |         4497 |         4511 | [i250_10_7_cost4511.sol](./solutions/i250_10_7_cost4511.sol)         |
| [i250_10_8](./problem_instances/i250_10_8.txt)       |         5881 |         5887 | [i250_10_8_cost5887.sol](./solutions/i250_10_8_cost5887.sol)         |
| [i250_10_9](./problem_instances/i250_10_9.txt)       |         5321 |         5327 | [i250_10_9_cost5327.sol](./solutions/i250_10_9_cost5327.sol)         |
| [i250_10_10](./problem_instances/i250_10_10.txt)     |         1293 |         1293 | [i250_10_10_cost1293.sol](./solutions/i250_10_10_cost1293.sol)       |
| [i250_20_1](./problem_instances/i250_20_1.txt)       |         5573 |         5573 | [i250_20_1_cost5573.sol](./solutions/i250_20_1_cost5573.sol)         |
| [i250_20_2](./problem_instances/i250_20_2.txt)       |         1882 |         1888 | [i250_20_2_cost1888.sol](./solutions/i250_20_2_cost1888.sol)         |
| [i250_20_3](./problem_instances/i250_20_3.txt)       |         2813 |         2813 | [i250_20_3_cost2813.sol](./solutions/i250_20_3_cost2813.sol)         |
| [i250_20_4](./problem_instances/i250_20_4.txt)       |         2525 |         2525 | [i250_20_4_cost2525.sol](./solutions/i250_20_4_cost2525.sol)         |
| [i250_20_5](./problem_instances/i250_20_5.txt)       |         1054 |         1054 | [i250_20_5_cost1054.sol](./solutions/i250_20_5_cost1054.sol)         |
| [i250_20_6](./problem_instances/i250_20_6.txt)       |         1583 |         1606 | [i250_20_6_cost1606.sol](./solutions/i250_20_6_cost1606.sol)         |
| [i250_20_7](./problem_instances/i250_20_7.txt)       |         1565 |         1570 | [i250_20_7_cost1570.sol](./solutions/i250_20_7_cost1570.sol)         |
| [i250_20_8](./problem_instances/i250_20_8.txt)       |         2190 |         2190 | [i250_20_8_cost2190.sol](./solutions/i250_20_8_cost2190.sol)         |
| [i250_20_9](./problem_instances/i250_20_9.txt)       |         1553 |         1553 | [i250_20_9_cost1553.sol](./solutions/i250_20_9_cost1553.sol)         |
| [i250_20_10](./problem_instances/i250_20_10.txt)     |         6531 |         6541 | [i250_20_10_cost6541.sol](./solutions/i250_20_10_cost6541.sol)       |
| [i250_30_1](./problem_instances/i250_30_1.txt)       |         3013 |         3013 | [i250_30_1_cost3013.sol](./solutions/i250_30_1_cost3013.sol)         |
| [i250_30_2](./problem_instances/i250_30_2.txt)       |         3054 |         3054 | [i250_30_2_cost3054.sol](./solutions/i250_30_2_cost3054.sol)         |
| [i250_30_3](./problem_instances/i250_30_3.txt)       |         4757 |         4753 | [i250_30_3_cost4753.sol](./solutions/i250_30_3_cost4753.sol)         |
| [i250_30_4](./problem_instances/i250_30_4.txt)       |         4096 |         4093 | [i250_30_4_cost4093.sol](./solutions/i250_30_4_cost4093.sol)         |
| [i250_30_5](./problem_instances/i250_30_5.txt)       |         4194 |         4194 | [i250_30_5_cost4194.sol](./solutions/i250_30_5_cost4194.sol)         |
| [i250_30_6](./problem_instances/i250_30_6.txt)       |         5031 |         5019 | [i250_30_6_cost5019.sol](./solutions/i250_30_6_cost5019.sol)         |
| [i250_30_7](./problem_instances/i250_30_7.txt)       |         3641 |         3641 | [i250_30_7_cost3641.sol](./solutions/i250_30_7_cost3641.sol)         |
| [i250_30_8](./problem_instances/i250_30_8.txt)       |          686 |          686 | [i250_30_8_cost686.sol](./solutions/i250_30_8_cost686.sol)           |
| [i250_30_9](./problem_instances/i250_30_9.txt)       |         1502 |         1502 | [i250_30_9_cost1502.sol](./solutions/i250_30_9_cost1502.sol)         |
| [i250_30_10](./problem_instances/i250_30_10.txt)     |         5188 |         5193 | [i250_30_10_cost5193.sol](./solutions/i250_30_10_cost5193.sol)       |
| [i500_10_1](./problem_instances/i500_10_1.txt)       |         4614 |         4614 | [i500_10_1_cost4614.sol](./solutions/i500_10_1_cost4614.sol)         |
| [i500_10_2](./problem_instances/i500_10_2.txt)       |          822 |          822 | [i500_10_2_cost822.sol](./solutions/i500_10_2_cost822.sol)           |
| [i500_10_3](./problem_instances/i500_10_3.txt)       |          951 |          953 | [i500_10_3_cost953.sol](./solutions/i500_10_3_cost953.sol)           |
| [i500_10_4](./problem_instances/i500_10_4.txt)       |         2102 |         2116 | [i500_10_4_cost2116.sol](./solutions/i500_10_4_cost2116.sol)         |
| [i500_10_5](./problem_instances/i500_10_5.txt)       |          610 |          610 | [i500_10_5_cost610.sol](./solutions/i500_10_5_cost610.sol)           |
| [i500_10_6](./problem_instances/i500_10_6.txt)       |         5981 |         5981 | [i500_10_6_cost5981.sol](./solutions/i500_10_6_cost5981.sol)         |
| [i500_10_7](./problem_instances/i500_10_7.txt)       |         2768 |         2783 | [i500_10_7_cost2783.sol](./solutions/i500_10_7_cost2783.sol)         |
| [i500_10_8](./problem_instances/i500_10_8.txt)       |         4460 |         4460 | [i500_10_8_cost4460.sol](./solutions/i500_10_8_cost4460.sol)         |
| [i500_10_9](./problem_instances/i500_10_9.txt)       |          462 |          462 | [i500_10_9_cost462.sol](./solutions/i500_10_9_cost462.sol)           |
| [i500_10_10](./problem_instances/i500_10_10.txt)     |         1998 |         2008 | [i500_10_10_cost2008.sol](./solutions/i500_10_10_cost2008.sol)       |
| [i500_20_1](./problem_instances/i500_20_1.txt)       |         7602 |         7569 | [i500_20_1_cost7569.sol](./solutions/i500_20_1_cost7569.sol)         |
| [i500_20_2](./problem_instances/i500_20_2.txt)       |          790 |          790 | [i500_20_2_cost790.sol](./solutions/i500_20_2_cost790.sol)           |
| [i500_20_3](./problem_instances/i500_20_3.txt)       |         8941 |         8970 | [i500_20_3_cost8970.sol](./solutions/i500_20_3_cost8970.sol)         |
| [i500_20_4](./problem_instances/i500_20_4.txt)       |         1272 |         1272 | [i500_20_4_cost1272.sol](./solutions/i500_20_4_cost1272.sol)         |
| [i500_20_5](./problem_instances/i500_20_5.txt)       |         1717 |         1744 | [i500_20_5_cost1744.sol](./solutions/i500_20_5_cost1744.sol)         |
| [i500_20_6](./problem_instances/i500_20_6.txt)       |         9099 |         9097 | [i500_20_6_cost9097.sol](./solutions/i500_20_6_cost9097.sol)         |
| [i500_20_7](./problem_instances/i500_20_7.txt)       |          523 |          523 | [i500_20_7_cost523.sol](./solutions/i500_20_7_cost523.sol)           |
| [i500_20_8](./problem_instances/i500_20_8.txt)       |         3180 |         3192 | [i500_20_8_cost3192.sol](./solutions/i500_20_8_cost3192.sol)         |
| [i500_20_9](./problem_instances/i500_20_9.txt)       |         6289 |         6338 | [i500_20_9_cost6338.sol](./solutions/i500_20_9_cost6338.sol)         |
| [i500_20_10](./problem_instances/i500_20_10.txt)     |         5618 |         5662 | [i500_20_10_cost5662.sol](./solutions/i500_20_10_cost5662.sol)       |
| [i500_30_1](./problem_instances/i500_30_1.txt)       |         2670 |         2670 | [i500_30_1_cost2670.sol](./solutions/i500_30_1_cost2670.sol)         |
| [i500_30_2](./problem_instances/i500_30_2.txt)       |          477 |          477 | [i500_30_2_cost477.sol](./solutions/i500_30_2_cost477.sol)           |
| [i500_30_3](./problem_instances/i500_30_3.txt)       |         5975 |         5974 | [i500_30_3_cost5974.sol](./solutions/i500_30_3_cost5974.sol)         |
| [i500_30_4](./problem_instances/i500_30_4.txt)       |         4307 |         4307 | [i500_30_4_cost4307.sol](./solutions/i500_30_4_cost4307.sol)         |
| [i500_30_5](./problem_instances/i500_30_5.txt)       |         5869 |         5873 | [i500_30_5_cost5873.sol](./solutions/i500_30_5_cost5873.sol)         |
| [i500_30_6](./problem_instances/i500_30_6.txt)       |         1614 |         1626 | [i500_30_6_cost1626.sol](./solutions/i500_30_6_cost1626.sol)         |
| [i500_30_7](./problem_instances/i500_30_7.txt)       |         3795 |         3795 | [i500_30_7_cost3795.sol](./solutions/i500_30_7_cost3795.sol)         |
| [i500_30_8](./problem_instances/i500_30_8.txt)       |         8895 |         8888 | [i500_30_8_cost8888.sol](./solutions/i500_30_8_cost8888.sol)         |
| [i500_30_9](./problem_instances/i500_30_9.txt)       |          862 |          862 | [i500_30_9_cost862.sol](./solutions/i500_30_9_cost862.sol)           |
| [i500_30_10](./problem_instances/i500_30_10.txt)     |          352 |          352 | [i500_30_10_cost352.sol](./solutions/i500_30_10_cost352.sol)         |
| [i750_10_1](./problem_instances/i750_10_1.txt)       |         4337 |         4312 | [i750_10_1_cost4312.sol](./solutions/i750_10_1_cost4312.sol)         |
| [i750_10_2](./problem_instances/i750_10_2.txt)       |         7744 |         7744 | [i750_10_2_cost7744.sol](./solutions/i750_10_2_cost7744.sol)         |
| [i750_10_3](./problem_instances/i750_10_3.txt)       |         5819 |         5821 | [i750_10_3_cost5821.sol](./solutions/i750_10_3_cost5821.sol)         |
| [i750_10_4](./problem_instances/i750_10_4.txt)       |         5078 |         5082 | [i750_10_4_cost5082.sol](./solutions/i750_10_4_cost5082.sol)         |
| [i750_10_5](./problem_instances/i750_10_5.txt)       |         1517 |         1500 | [i750_10_5_cost1500.sol](./solutions/i750_10_5_cost1500.sol)         |
| [i750_10_6](./problem_instances/i750_10_6.txt)       |         7895 |         7895 | [i750_10_6_cost7895.sol](./solutions/i750_10_6_cost7895.sol)         |
| [i750_10_7](./problem_instances/i750_10_7.txt)       |          948 |          943 | [i750_10_7_cost943.sol](./solutions/i750_10_7_cost943.sol)           |
| [i750_10_8](./problem_instances/i750_10_8.txt)       |         7956 |         7962 | [i750_10_8_cost7962.sol](./solutions/i750_10_8_cost7962.sol)         |
| [i750_10_9](./problem_instances/i750_10_9.txt)       |        12779 |        12814 | [i750_10_9_cost12814.sol](./solutions/i750_10_9_cost12814.sol)       |
| [i750_10_10](./problem_instances/i750_10_10.txt)     |         3840 |         3840 | [i750_10_10_cost3840.sol](./solutions/i750_10_10_cost3840.sol)       |
| [i750_20_1](./problem_instances/i750_20_1.txt)       |         5874 |         5979 | [i750_20_1_cost5979.sol](./solutions/i750_20_1_cost5979.sol)         |
| [i750_20_2](./problem_instances/i750_20_2.txt)       |          700 |          700 | [i750_20_2_cost700.sol](./solutions/i750_20_2_cost700.sol)           |
| [i750_20_3](./problem_instances/i750_20_3.txt)       |         1314 |         1314 | [i750_20_3_cost1314.sol](./solutions/i750_20_3_cost1314.sol)         |
| [i750_20_4](./problem_instances/i750_20_4.txt)       |         9632 |         9562 | [i750_20_4_cost9562.sol](./solutions/i750_20_4_cost9562.sol)         |
| [i750_20_5](./problem_instances/i750_20_5.txt)       |         9073 |         9073 | [i750_20_5_cost9073.sol](./solutions/i750_20_5_cost9073.sol)         |
| [i750_20_6](./problem_instances/i750_20_6.txt)       |        11434 |        11434 | [i750_20_6_cost11434.sol](./solutions/i750_20_6_cost11434.sol)       |
| [i750_20_7](./problem_instances/i750_20_7.txt)       |         4855 |         4855 | [i750_20_7_cost4855.sol](./solutions/i750_20_7_cost4855.sol)         |
| [i750_20_8](./problem_instances/i750_20_8.txt)       |        11298 |        11284 | [i750_20_8_cost11284.sol](./solutions/i750_20_8_cost11284.sol)       |
| [i750_20_9](./problem_instances/i750_20_9.txt)       |         4393 |         4393 | [i750_20_9_cost4393.sol](./solutions/i750_20_9_cost4393.sol)         |
| [i750_20_10](./problem_instances/i750_20_10.txt)     |         2632 |         2632 | [i750_20_10_cost2632.sol](./solutions/i750_20_10_cost2632.sol)       |
| [i750_30_1](./problem_instances/i750_30_1.txt)       |         4707 |         4767 | [i750_30_1_cost4767.sol](./solutions/i750_30_1_cost4767.sol)         |
| [i750_30_2](./problem_instances/i750_30_2.txt)       |         5128 |         5128 | [i750_30_2_cost5128.sol](./solutions/i750_30_2_cost5128.sol)         |
| [i750_30_3](./problem_instances/i750_30_3.txt)       |         2364 |         2364 | [i750_30_3_cost2364.sol](./solutions/i750_30_3_cost2364.sol)         |
| [i750_30_4](./problem_instances/i750_30_4.txt)       |         2948 |         2945 | [i750_30_4_cost2945.sol](./solutions/i750_30_4_cost2945.sol)         |
| [i750_30_5](./problem_instances/i750_30_5.txt)       |          661 |          667 | [i750_30_5_cost667.sol](./solutions/i750_30_5_cost667.sol)           |
| [i750_30_6](./problem_instances/i750_30_6.txt)       |         2577 |         2577 | [i750_30_6_cost2577.sol](./solutions/i750_30_6_cost2577.sol)         |
| [i750_30_7](./problem_instances/i750_30_7.txt)       |         1070 |         1070 | [i750_30_7_cost1070.sol](./solutions/i750_30_7_cost1070.sol)         |
| [i750_30_8](./problem_instances/i750_30_8.txt)       |         2911 |         2912 | [i750_30_8_cost2912.sol](./solutions/i750_30_8_cost2912.sol)         |
| [i750_30_9](./problem_instances/i750_30_9.txt)       |         2700 |         2700 | [i750_30_9_cost2700.sol](./solutions/i750_30_9_cost2700.sol)         |
| [i750_30_10](./problem_instances/i750_30_10.txt)     |         1994 |         1994 | [i750_30_10_cost1994.sol](./solutions/i750_30_10_cost1994.sol)       |
| [i750_50_1](./problem_instances/i750_50_1.txt)       |         5134 |         5134 | [i750_50_1_cost5134.sol](./solutions/i750_50_1_cost5134.sol)         |
| [i750_50_2](./problem_instances/i750_50_2.txt)       |         4959 |         4792 | [i750_50_2_cost4792.sol](./solutions/i750_50_2_cost4792.sol)         |
| [i750_50_3](./problem_instances/i750_50_3.txt)       |        12572 |        12147 | [i750_50_3_cost12147.sol](./solutions/i750_50_3_cost12147.sol)       |
| [i750_50_4](./problem_instances/i750_50_4.txt)       |         2356 |         2356 | [i750_50_4_cost2356.sol](./solutions/i750_50_4_cost2356.sol)         |
| [i750_50_5](./problem_instances/i750_50_5.txt)       |         9840 |         9847 | [i750_50_5_cost9847.sol](./solutions/i750_50_5_cost9847.sol)         |
| [i750_50_6](./problem_instances/i750_50_6.txt)       |        11480 |        11500 | [i750_50_6_cost11500.sol](./solutions/i750_50_6_cost11500.sol)       |
| [i750_50_7](./problem_instances/i750_50_7.txt)       |         4868 |         4868 | [i750_50_7_cost4868.sol](./solutions/i750_50_7_cost4868.sol)         |
| [i750_50_8](./problem_instances/i750_50_8.txt)       |        10580 |        10583 | [i750_50_8_cost10583.sol](./solutions/i750_50_8_cost10583.sol)       |
| [i750_50_9](./problem_instances/i750_50_9.txt)       |         5154 |         5154 | [i750_50_9_cost5154.sol](./solutions/i750_50_9_cost5154.sol)         |
| [i750_50_10](./problem_instances/i750_50_10.txt)     |         5150 |         5028 | [i750_50_10_cost5028.sol](./solutions/i750_50_10_cost5028.sol)       |
| [i1000_10_1](./problem_instances/i1000_10_1.txt)     |          641 |          641 | [i1000_10_1_cost641.sol](./solutions/i1000_10_1_cost641.sol)         |
| [i1000_10_2](./problem_instances/i1000_10_2.txt)     |        23556 |        23521 | [i1000_10_2_cost23521.sol](./solutions/i1000_10_2_cost23521.sol)     |
| [i1000_10_3](./problem_instances/i1000_10_3.txt)     |          814 |          812 | [i1000_10_3_cost812.sol](./solutions/i1000_10_3_cost812.sol)         |
| [i1000_10_4](./problem_instances/i1000_10_4.txt)     |        15199 |        15211 | [i1000_10_4_cost15211.sol](./solutions/i1000_10_4_cost15211.sol)     |
| [i1000_10_5](./problem_instances/i1000_10_5.txt)     |        15335 |        15180 | [i1000_10_5_cost15180.sol](./solutions/i1000_10_5_cost15180.sol)     |
| [i1000_10_6](./problem_instances/i1000_10_6.txt)     |         2025 |         2025 | [i1000_10_6_cost2025.sol](./solutions/i1000_10_6_cost2025.sol)       |
| [i1000_10_7](./problem_instances/i1000_10_7.txt)     |          732 |          729 | [i1000_10_7_cost729.sol](./solutions/i1000_10_7_cost729.sol)         |
| [i1000_10_8](./problem_instances/i1000_10_8.txt)     |        20626 |        20574 | [i1000_10_8_cost20574.sol](./solutions/i1000_10_8_cost20574.sol)     |
| [i1000_10_9](./problem_instances/i1000_10_9.txt)     |        22252 |        22162 | [i1000_10_9_cost22162.sol](./solutions/i1000_10_9_cost22162.sol)     |
| [i1000_10_10](./problem_instances/i1000_10_10.txt)   |         3986 |         3982 | [i1000_10_10_cost3982.sol](./solutions/i1000_10_10_cost3982.sol)     |
| [i1000_20_1](./problem_instances/i1000_20_1.txt)     |         9440 |         9440 | [i1000_20_1_cost9440.sol](./solutions/i1000_20_1_cost9440.sol)       |
| [i1000_20_2](./problem_instances/i1000_20_2.txt)     |        16004 |        15971 | [i1000_20_2_cost15971.sol](./solutions/i1000_20_2_cost15971.sol)     |
| [i1000_20_3](./problem_instances/i1000_20_3.txt)     |        20004 |        19986 | [i1000_20_3_cost19986.sol](./solutions/i1000_20_3_cost19986.sol)     |
| [i1000_20_4](./problem_instances/i1000_20_4.txt)     |         7907 |         7975 | [i1000_20_4_cost7975.sol](./solutions/i1000_20_4_cost7975.sol)       |
| [i1000_20_5](./problem_instances/i1000_20_5.txt)     |        14183 |        14183 | [i1000_20_5_cost14183.sol](./solutions/i1000_20_5_cost14183.sol)     |
| [i1000_20_6](./problem_instances/i1000_20_6.txt)     |        24508 |        24507 | [i1000_20_6_cost24507.sol](./solutions/i1000_20_6_cost24507.sol)     |
| [i1000_20_7](./problem_instances/i1000_20_7.txt)     |         9727 |         9726 | [i1000_20_7_cost9726.sol](./solutions/i1000_20_7_cost9726.sol)       |
| [i1000_20_8](./problem_instances/i1000_20_8.txt)     |        16906 |        16789 | [i1000_20_8_cost16789.sol](./solutions/i1000_20_8_cost16789.sol)     |
| [i1000_20_9](./problem_instances/i1000_20_9.txt)     |        10290 |        10301 | [i1000_20_9_cost10301.sol](./solutions/i1000_20_9_cost10301.sol)     |
| [i1000_20_10](./problem_instances/i1000_20_10.txt)   |        10781 |        10781 | [i1000_20_10_cost10781.sol](./solutions/i1000_20_10_cost10781.sol)   |
| [i1000_30_1](./problem_instances/i1000_30_1.txt)     |         6894 |         6780 | [i1000_30_1_cost6780.sol](./solutions/i1000_30_1_cost6780.sol)       |
| [i1000_30_2](./problem_instances/i1000_30_2.txt)     |         1675 |         1668 | [i1000_30_2_cost1668.sol](./solutions/i1000_30_2_cost1668.sol)       |
| [i1000_30_3](./problem_instances/i1000_30_3.txt)     |        18312 |        18087 | [i1000_30_3_cost18087.sol](./solutions/i1000_30_3_cost18087.sol)     |
| [i1000_30_4](./problem_instances/i1000_30_4.txt)     |        12399 |        12411 | [i1000_30_4_cost12411.sol](./solutions/i1000_30_4_cost12411.sol)     |
| [i1000_30_5](./problem_instances/i1000_30_5.txt)     |         3718 |         3707 | [i1000_30_5_cost3707.sol](./solutions/i1000_30_5_cost3707.sol)       |
| [i1000_30_6](./problem_instances/i1000_30_6.txt)     |        12090 |        12090 | [i1000_30_6_cost12090.sol](./solutions/i1000_30_6_cost12090.sol)     |
| [i1000_30_7](./problem_instances/i1000_30_7.txt)     |         9775 |         9765 | [i1000_30_7_cost9765.sol](./solutions/i1000_30_7_cost9765.sol)       |
| [i1000_30_8](./problem_instances/i1000_30_8.txt)     |         2085 |         2085 | [i1000_30_8_cost2085.sol](./solutions/i1000_30_8_cost2085.sol)       |
| [i1000_30_9](./problem_instances/i1000_30_9.txt)     |        15564 |        15528 | [i1000_30_9_cost15528.sol](./solutions/i1000_30_9_cost15528.sol)     |
| [i1000_30_10](./problem_instances/i1000_30_10.txt)   |        18609 |        18483 | [i1000_30_10_cost18483.sol](./solutions/i1000_30_10_cost18483.sol)   |
| [i1000_50_1](./problem_instances/i1000_50_1.txt)     |         2883 |         2883 | [i1000_50_1_cost2883.sol](./solutions/i1000_50_1_cost2883.sol)       |
| [i1000_50_2](./problem_instances/i1000_50_2.txt)     |        16388 |        15977 | [i1000_50_2_cost15977.sol](./solutions/i1000_50_2_cost15977.sol)     |
| [i1000_50_3](./problem_instances/i1000_50_3.txt)     |        11613 |        11618 | [i1000_50_3_cost11618.sol](./solutions/i1000_50_3_cost11618.sol)     |
| [i1000_50_4](./problem_instances/i1000_50_4.txt)     |         1142 |         1142 | [i1000_50_4_cost1142.sol](./solutions/i1000_50_4_cost1142.sol)       |
| [i1000_50_5](./problem_instances/i1000_50_5.txt)     |         1390 |         1390 | [i1000_50_5_cost1390.sol](./solutions/i1000_50_5_cost1390.sol)       |
| [i1000_50_6](./problem_instances/i1000_50_6.txt)     |        16656 |        16667 | [i1000_50_6_cost16667.sol](./solutions/i1000_50_6_cost16667.sol)     |
| [i1000_50_7](./problem_instances/i1000_50_7.txt)     |        19566 |        19566 | [i1000_50_7_cost19566.sol](./solutions/i1000_50_7_cost19566.sol)     |
| [i1000_50_8](./problem_instances/i1000_50_8.txt)     |         1886 |         1889 | [i1000_50_8_cost1889.sol](./solutions/i1000_50_8_cost1889.sol)       |
| [i1000_50_9](./problem_instances/i1000_50_9.txt)     |        13740 |        13747 | [i1000_50_9_cost13747.sol](./solutions/i1000_50_9_cost13747.sol)     |
| [i1000_50_10](./problem_instances/i1000_50_10.txt)   |         3989 |         3989 | [i1000_50_10_cost3989.sol](./solutions/i1000_50_10_cost3989.sol)     |
| [i1000_100_1](./problem_instances/i1000_100_1.txt)   |        71018 |        71012 | [i1000_100_1_cost71012.sol](./solutions/i1000_100_1_cost71012.sol)   |
| [i1000_100_2](./problem_instances/i1000_100_2.txt)   |        75101 |        75181 | [i1000_100_2_cost75181.sol](./solutions/i1000_100_2_cost75181.sol)   |
| [i1000_100_3](./problem_instances/i1000_100_3.txt)   |        25873 |        25594 | [i1000_100_3_cost25594.sol](./solutions/i1000_100_3_cost25594.sol)   |
| [i1000_100_4](./problem_instances/i1000_100_4.txt)   |        36374 |        36376 | [i1000_100_4_cost36376.sol](./solutions/i1000_100_4_cost36376.sol)   |
| [i1000_100_5](./problem_instances/i1000_100_5.txt)   |        67095 |        66419 | [i1000_100_5_cost66419.sol](./solutions/i1000_100_5_cost66419.sol)   |
| [i1000_100_6](./problem_instances/i1000_100_6.txt)   |        47523 |        47541 | [i1000_100_6_cost47541.sol](./solutions/i1000_100_6_cost47541.sol)   |
| [i1000_100_7](./problem_instances/i1000_100_7.txt)   |        44439 |        43437 | [i1000_100_7_cost43437.sol](./solutions/i1000_100_7_cost43437.sol)   |
| [i1000_100_8](./problem_instances/i1000_100_8.txt)   |        52266 |        52268 | [i1000_100_8_cost52268.sol](./solutions/i1000_100_8_cost52268.sol)   |
| [i1000_100_9](./problem_instances/i1000_100_9.txt)   |        23704 |        23690 | [i1000_100_9_cost23690.sol](./solutions/i1000_100_9_cost23690.sol)   |
| [i1000_100_10](./problem_instances/i1000_100_10.txt) |        15605 |        15230 | [i1000_100_10_cost15230.sol](./solutions/i1000_100_10_cost15230.sol) |
