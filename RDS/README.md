# 实验1 10.19
````
+--------------------+-------+-------+
|       Class        |  IoU  |  Acc  |
+--------------------+-------+-------+
|     background     | 94.86 | 97.94 |
|        ship        | 51.02 | 58.82 |
|      store_tank    | 37.57 | 81.02 |#
|  baseball_diamond  | 29.06 | 54.47 |
|    tennis_court    | 49.25 | 56.14 |
|  basketball_court  |  3.02 |  3.54 |#
| Ground_Track_Field | 16.62 | 41.32 |
|       Bridge       |  0.0  |  0.0  |
|   Large_Vehicle    | 20.86 | 21.81 |#
|   Small_Vehicle    |  2.53 |  2.54 |#
|     Helicopter     |  0.0  |  0.0  |
|   Swimming_pool    | 15.76 | 16.33 |#
|     Roundabout     | 34.06 | 50.12 |
| Soccer_ball_field  | 36.52 | 49.94 |
|       plane        | 40.68 | 65.87 |
|       Harbor       | 42.75 | 53.82 |
+--------------------+-------+-------+
2024/10/16 19:03:26 - mmengine - INFO - Iter(val) [4785/4785]    aAcc: 94.5100  mIoU: 29.6600  mAcc: 40.8500  data_time: 0.0010  time: 0.7171

# 加工后的数据集
+--------------------+-------+-------+
|       Class        |  IoU  |  Acc  |
+--------------------+-------+-------+
|     background     | 87.78 | 90.14 |
|        ship        | 50.42 |  62.3 |
|     store_tank     | 47.35 | 83.31 |#
|  baseball_diamond  | 21.62 |  85.5 |
|    tennis_court    | 28.56 | 77.52 |
|  basketball_court  |  7.69 | 90.24 |#
| Ground_Track_Field | 12.03 | 28.34 |
|       Bridge       | 14.44 | 81.67 |
|   Large_Vehicle    | 23.29 | 26.86 |#
|   Small_Vehicle    | 24.41 | 26.47 |#
|     Helicopter     |  0.0  |  0.0  |
|   Swimming_pool    | 21.26 | 25.69 |#
|     Roundabout     |  3.45 |  50.9 |
| Soccer_ball_field  | 39.69 | 54.09 |
|       plane        | 38.15 | 41.27 |
|       Harbor       | 24.67 | 26.07 |
+--------------------+-------+-------+
2024/10/19 18:44:37 - mmengine - INFO - Iter(val) [4785/4785]    aAcc: 87.3000  mIoU: 27.8000  mAcc: 53.1500  data_time: 0.0010  time: 0.7079
````