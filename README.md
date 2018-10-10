# 慕课网  量化交易
https://www.imooc.com/learn/1054
## python获取股票数据
#### 安装 pandas_datareader
pip install pandas_datareader
#### 调用Api
df_datacsv = web.DataReader("601233.SS","yahoo",datetime.datetime(2018,1,1),datetime.date.today())
601233 股票代码
- 上证 .SS
- 深证 .SA
## DataFrame 基础练习，文件列表
- Pandas基础
定义DataFrame对象
- DataFrame 访问
数据方法，loc，iloc，ix
- 爬取数据
datareader
- 加载数据
调用APi，将数据保存为CSV文件，方便加载。
pandas加载数据，describe info等函数查看数据。
fillna处理缺失值。
- 数字格式处理
dataframe loc，iloc等函数使用练习。