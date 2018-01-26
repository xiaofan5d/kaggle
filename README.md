# 预测泰坦尼克号乘客幸存率
### 对泰坦尼克号乘客幸存率进行预测
* 历史数据:[titanic_train.csv](https://github.com/xiaofan5d/kaggle/blob/master/titanic_train.csv)
* 需要预测的数据:[test.csv](https://github.com/xiaofan5d/kaggle/blob/master/test.csv)
### 代码使用为python3.6,以及主要安装以下python库
* numpy
* pandas
* scikit-learn
# 代码
[泰坦尼克代码.py](https://github.com/xiaofan5d/kaggle/blob/master/泰坦尼克代码.py)
# 数据
​ 这个项目的数据包含在 titanic_train.csv 文件中。文件包含下列特征：
* Survived：是否存活（0代表否，1代表是)
* Pclass：社会阶级（1代表上层阶级，2代表中层阶级，3代表底层阶级）
* Name：船上乘客的名字
* Sex：船上乘客的性别
* Age：船上乘客的年龄（可能存在 NaN）
* SibSp：乘客在船上的兄弟姐妹和配偶的数量
* Parch：乘客在船上的父母以及小孩的数量
* Ticket：乘客船票的编号
* Fare：乘客为船票支付的费用
* Cabin：乘客所在船舱的编号（可能存在 NaN）
* Embarked：乘客上船的港口（C 代表从 Cherbourg 登船，Q 代表从 Queenstown 登船，S 代表从 Southampton 登船）
# 预测结果
预测正确率分数为0.79
