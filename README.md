# movieLens
使用 Spark MLlib 的 ALS 算法的电影推荐系统

## data [数据说明](http://files.grouplens.org/datasets/movielens/ml-latest-small-README.html)

MovieLens数据集

（1）ratings.csv

数据格式：userId,movieId,rating,timestamp


（2）movies.csv

数据格式：movieId,title,genres

## result 结果说明

数据格式：userId, [(movieId, rating)]

userId：用户ID

movieId：电影ID

rating：推荐度
