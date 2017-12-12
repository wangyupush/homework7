# homework7
## 本次实验采用的windows10的系统，因为我的双系统Ubuntu16.04出了一些问题，提示没有可用磁盘空间
## 本次实验安装的是Hive本地模式，使用的是mysql数据库
### 开启hive后，首先创建表myNewsWord(count int,word string)
![create](https://github.com/wangyupush/homework7/blob/master/create.png)
### 查看表的结构
![create](https://github.com/wangyupush/homework7/blob/master/desc.png)
### 因为Project1跑出的是小数据集文件，所以使用的输出文件内的项较少
#### 输入 load data inpath 'hdfs://localhost:9000/output/part-r-00000' into table myNewsWord;显示如下：
![create](https://github.com/wangyupush/homework7/blob/master/1.png)
![create](https://github.com/wangyupush/homework7/blob/master/2.png)
### 首先判断词频>50的
![create](https://github.com/wangyupush/homework7/blob/master/50.png)
### 输出结果
![create](https://github.com/wangyupush/homework7/blob/master/50-res.png)
### 判断词频>80的
![create](https://github.com/wangyupush/homework7/blob/master/80png)
### 输出结果
![create](https://github.com/wangyupush/homework7/blob/master/80-res.png)
### 判断词频大于50小于80的
![create](https://github.com/wangyupush/homework7/blob/master/50-80.png)
### 输出结果
![create](https://github.com/wangyupush/homework7/blob/master/50-80-res.png)
