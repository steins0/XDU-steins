# 时空数据上的KD树
## 算法描述：
求KD树
1.	对选取的纬度求均值，作为树的划分点
2.	取第一个纬度中值为划分点，大于挂左子树，小于挂右子树
3.	对左子树的经度求平均值，将中值为划分点，大于挂左子树，小于挂右子树
4.	对右子树的经度求平均值，将中值为划分点，大于挂左子树，小于挂右子树
求点：
1.	根据纬度判断第一层子树
2.	根据经度判断第二层子树
3.	KNN查询
