# CEC2017-8-
1.CEC2017测试集测试了模拟退火（SA）算法、状态转移（STA）算法、实数编码遗传（RCGA）算法、差分进化（DE）算法、免疫（IA）算法、粒子群（PSO）算法、蚁群（ACO）算法和多种自适应策略粒子群（MAPSO）算法。当各测试问题的维度D=10时，8种典型的算法从优到差的排序依次为DE、IA、MAPSO、ACO、RCGA、PSO、STA、SA算法。

2.优化算法代码为matlab语言，CEC2017测试集为C++语言。

3.由于github限制上传包不得大于25M，故仅保留了DE32算法中input_data，运行其他优化算法前请将DE32文件夹下的input_data文件夹复制到各个算法文件夹下。

4.运行环境为matlab2016。

5.优化结果请参考各文件夹下自动生成的Log.DAT，将之整理到Excel中，再通过findbetterAlgMeanStd2.m代码即可整理出各算法排名。

