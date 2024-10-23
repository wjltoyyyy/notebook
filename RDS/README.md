# 实验1 10.19
````
# 使用原始数据
# val
+--------------------+-------+-------+
|       Class        |  IoU  |  Acc  |
+--------------------+-------+-------+
|     background     | 94.86 | 97.94 |
|        ship        | 51.02 | 58.82 |
|      store_tank    | 37.57 | 81.02 |
|  baseball_diamond  | 29.06 | 54.47 |
|    tennis_court    | 49.25 | 56.14 |
|  basketball_court  |  3.02 |  3.54 |
| Ground_Track_Field | 16.62 | 41.32 |
|       Bridge       |  0.0  |  0.0  |
|   Large_Vehicle    | 20.86 | 21.81 |
|   Small_Vehicle    |  2.53 |  2.54 |
|     Helicopter     |  0.0  |  0.0  |
|   Swimming_pool    | 15.76 | 16.33 |
|     Roundabout     | 34.06 | 50.12 |
| Soccer_ball_field  | 36.52 | 49.94 |
|       plane        | 40.68 | 65.87 |
|       Harbor       | 42.75 | 53.82 |
+--------------------+-------+-------+
## test
+--------------------+-------+-------+
|       Class        |  IoU  |  Acc  |
+--------------------+-------+-------+
|     background     | 93.69 | 97.87 |
|        ship        | 41.74 | 48.53 |
|     store_tank     | 20.06 | 53.63 |
|  baseball_diamond  | 30.17 | 72.47 |
|    tennis_court    | 44.59 | 51.33 |
|  basketball_court  | 13.41 | 13.73 |
| Ground_Track_Field |  12.9 | 27.53 |
|       Bridge       |  0.0  |  0.0  |
|   Large_Vehicle    |  6.29 |  6.51 |
|   Small_Vehicle    |  0.73 |  0.73 |
|     Helicopter     |  0.0  |  0.0  |
|   Swimming_pool    | 14.73 | 14.78 |
|     Roundabout     | 13.06 | 18.83 |
| Soccer_ball_field  | 15.81 | 19.18 |
|       plane        | 47.03 | 64.77 |
|       Harbor       | 23.83 | 27.42 |
+--------------------+-------+-------+

2024/10/16 19:03:26 - mmengine - INFO - Iter(val) [4785/4785]    aAcc: 94.5100  mIoU: 29.6600  mAcc: 40.8500  data_time: 0.0010  time: 0.7171

# 加工后的数据集，对train和val分别添加item
## val
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
## test
+--------------------+-------+-------+
|       Class        |  IoU  |  Acc  |
+--------------------+-------+-------+
|     background     |  89.6 | 92.12 |
|        ship        | 46.82 | 59.47 |
|     store_tank     | 44.01 | 85.87 |
|  baseball_diamond  | 10.76 | 76.97 |
|    tennis_court    | 24.55 | 81.68 |
|  basketball_court  |  8.17 | 69.33 |
| Ground_Track_Field | 14.01 |  30.8 |
|       Bridge       |  0.5  | 45.25 |
|   Large_Vehicle    | 10.07 | 10.81 |
|   Small_Vehicle    | 21.51 | 24.77 |
|     Helicopter     |  0.0  |  0.0  |
|   Swimming_pool    | 23.19 | 24.36 |
|     Roundabout     |  9.91 | 30.34 |
| Soccer_ball_field  |  31.9 | 45.27 |
|       plane        |  44.9 | 47.81 |
|       Harbor       | 25.76 | 27.47 |
+--------------------+-------+-------+

2024/10/19 18:44:37 - mmengine - INFO - Iter(val) [4785/4785]    aAcc: 87.3000  mIoU: 27.8000  mAcc: 53.1500  data_time: 0.0010  time: 0.7079

# 加工后的数据集v2，只对train添加items
## val
+--------------------+-------+-------+
|       Class        |  IoU  |  Acc  |
+--------------------+-------+-------+
|     background     | 84.06 | 85.75 |
|        ship        | 45.83 | 61.08 |
|     store_tank     | 44.81 | 90.12 |#
|  baseball_diamond  | 54.96 | 68.75 |#
|    tennis_court    |  61.1 | 82.58 |#
|  basketball_court  |  25.4 | 53.88 |#
| Ground_Track_Field | 12.83 | 26.74 |
|       Bridge       |  0.0  |  0.0  |
|   Large_Vehicle    | 40.28 | 62.26 |#
|   Small_Vehicle    | 36.14 | 48.36 |#
|     Helicopter     |  5.6  |  5.94 |#
|   Swimming_pool    |  24.1 | 28.28 |#
|     Roundabout     |  0.66 | 78.09 |
| Soccer_ball_field  |  54.6 | 66.81 |#
|       plane        | 39.07 | 46.82 |
|       Harbor       | 37.21 | 52.57 |
+--------------------+-------+-------+
## test
+--------------------+-------+-------+
|       Class        |  IoU  |  Acc  |
+--------------------+-------+-------+
|     background     | 84.39 | 87.05 |
|        ship        | 41.87 | 56.84 |#
|     store_tank     |  34.9 | 74.82 |#
|  baseball_diamond  | 37.05 | 63.31 |#
|    tennis_court    | 61.15 | 73.97 |#
|  basketball_court  | 50.15 | 63.36 |#
| Ground_Track_Field |  15.1 | 29.32 |#
|       Bridge       |  0.0  |  0.0  |
|   Large_Vehicle    | 21.82 | 26.29 |#
|   Small_Vehicle    | 27.01 | 33.58 |#
|     Helicopter     |  4.16 |  5.65 |#
|   Swimming_pool    | 30.64 | 32.32 |#
|     Roundabout     |  0.47 | 81.12 |
| Soccer_ball_field  | 40.14 | 42.92 |#
|       plane        | 44.37 | 47.87 |#
|       Harbor       | 30.74 | 38.56 |#
+--------------------+-------+-------+

````