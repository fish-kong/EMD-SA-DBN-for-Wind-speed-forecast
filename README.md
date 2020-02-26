# EMD-SA-DBN-for-Wind-speed-forecast
（MATLAB CODE）
Establishing a time series forecasting model for wind speed prediction based on DBN，Due to the autocorrelation of the wind speed sequence, the predicted value and the actual value lag, so EMD is used to decompose the wind speed sequence, and then the decomposed components are modeled in turn. To further mention accuracy, the simulated annealing algorithm is used to optimize the DBN。
(MATLAB代码)采用深度置信网络DBN建立风速预测的时间序列预测模型，由于数据本身的自相关性，导致得到的预测值与实际值存在滞后。针对这个问题，首先对风速序列进行EMD得到imf分量，然后对各分量进行DBN建模。最后为进一步提高精度，采用模拟退火算法的DBN各隐含层节点进行优化，需要的可以加我qq2919218574  ，效果可以看csdn博客https://blog.csdn.net/qq_41043389/article/details/104517495
程序是matlab代码，需要的可以改成python 模拟退火也可换成其他优化算法，如粒子群，遗传等
