### 基本设置

import matplotlib.pyplot as plt

plt.rcParams['font.sans-serif']=['SimHei'] #用来正常显示中文标签，属于全局设定

plt.rcParams['axes.unicode_minus']=False #用来正常显示负号

jupyter notebook正常显示图像

%matplotlib inline

###  matplotlib中的对象

figure

axes:坐标系

axis：坐标轴

xtick（刻度值，刻度标签）

xlabel

title

plt.plot(x,y,label=)

### 绘图区域

subplot(3,2,1)

### 坐标范围

plt.xlim

plt.ylim

### plt.plot

参数：颜色、线条风格、线宽、alpha:透明度

### 文本显示

xlabel、ylabel

title

text

### 个性化中文显示

from matplotlib import font_manager

my_font =font_manager.FontProperties(fname="C:\Windows\Fonts\STKAITI.TTF",size=20)

legend:图例

grid：网格

### 各种图形的应用：

折线图：plot一般是和时间有关的变化趋势

散点图：scatter可观测两个变量之间的关系，顺便找离群点

条形图：bar  适用于离散型数据，那种已经统计好的数据可以用条形图 表达出直方图的效果。

直方图：hist 适用于连续性数据。

条形图和直方图  刻度的设置  

echart : 前端展示的多一些
饼状图：pie
