# :memo: DataScienceStudyNotes
:dart: 这个仓库保管从（数据科学学习手札69）开始的所有代码、数据等相关附件内容
<br>:email: 交流学习请联系邮箱：fefferypzy@gmail.com
<br>:rainbow: 博客地址：https://www.cnblogs.com/feffery/

> :inbox_tray: 推荐高效clone方式：
```bash
git clone https://github.com/CNFeffery/DataScienceStudyNotes.git --depth=1
```

# :carousel_horse: 目录
- :books: [1 已更新博客列表](#first)
- :card_file_box: [2 专题系列](#second)
  - :earth_asia: [2.1 基于geopandas的空间数据分析  🚩 `<完结>`](#second-geopandas)
  - :zap: [2.2 Python+Dash快速web应用开发　🚩 `<完结>` ](#second-dash)
- :man_astronaut: [3 pandas相关](#pandas)
- :ghost: [4 jupyter相关](#jupyter)
- :penguin: [5 kepler.gl相关](#keplergl)
- :wrench: [6 补充勘误内容记录](#third)
- :running: [7 To-do List](#fourth)

***

<a name="first"></a>

## 1 :books: 已更新博客列表：
- [（数据科学学习手札69）详解pandas中的map、apply、applymap、groupby、agg](https://www.cnblogs.com/feffery/p/11468762.html) 　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札69）详解pandas中的map、apply、applymap、groupby、agg)
- [（数据科学学习手札70）面向数据科学的Python多进程简介及应用](https://www.cnblogs.com/feffery/p/11621076.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札70）面向数据科学的Python多进程简介及应用)
- [（数据科学学习手札71）利用Python绘制词云图](https://www.cnblogs.com/feffery/p/11842798.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札71）利用Python绘制词云图)
- [（数据科学学习手札72）用pdpipe搭建pandas数据分析流水线](https://www.cnblogs.com/feffery/p/12179647.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札72）用pdpipe搭建pandas数据分析流水线)
- [（数据科学学习手札73）盘点pandas 1.0.0中的新特性](https://www.cnblogs.com/feffery/p/12214635.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札73）盘点pandas 1.0.0中的新特性)
- [（数据科学学习手札74）基于geopandas的空间数据分析——数据结构篇](https://www.cnblogs.com/feffery/p/11898190.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札74）基于geopandas的空间数据分析——数据结构篇)
- [（数据科学学习手札75）基于geopandas的空间数据分析——坐标参考系篇](https://www.cnblogs.com/feffery/p/12285828.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札75）基于geopandas的空间数据分析——坐标参考系篇)
- [（数据科学学习手札76）基于Python的拐点检测——以新冠肺炎疫情数据为例](https://www.cnblogs.com/feffery/p/12325741.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札76）基于Python的拐点检测——以新冠肺炎疫情数据为例)
- [（数据科学学习手札77）基于geopandas的空间数据分析——文件IO](https://www.cnblogs.com/feffery/p/12301966.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札77）基于geopandas的空间数据分析——文件IO)
- [（数据科学学习手札78）基于geopandas的空间数据分析——基础可视化](https://www.cnblogs.com/feffery/p/12361421.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札78）基于geopandas的空间数据分析——基础可视化)
- [（数据科学学习手札79）基于geopandas的空间数据分析——深入浅出分层设色](https://www.cnblogs.com/feffery/p/12381322.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札79）基于geopandas的空间数据分析——深入浅出分层设色)
- [（数据科学学习手札80）用Python编写小工具下载OSM路网数据](https://www.cnblogs.com/feffery/p/12483967.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札80）用Python编写小工具下载OSM路网数据)
- [（数据科学学习手札81）conda+jupyter玩转数据科学环境搭建](https://www.cnblogs.com/feffery/p/12609118.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札81）conda+jupyter玩转数据科学环境搭建)
- [（数据科学学习手札82）基于geopandas的空间数据分析——geoplot篇(上)](https://www.cnblogs.com/feffery/p/12779150.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札82）基于geopandas的空间数据分析——geoplot篇(上))
- [（数据科学学习手札83）基于geopandas的空间数据分析——geoplot篇(下)](https://www.cnblogs.com/feffery/p/12901334.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札83）基于geopandas的空间数据分析——geoplot篇(下))
- [（数据科学学习手札84）基于geopandas的空间数据分析——空间计算篇（上）](https://www.cnblogs.com/feffery/p/12909284.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札84）基于geopandas的空间数据分析——空间计算篇（上）)
- [（数据科学学习手札85）Python+Kepler.gl轻松制作酷炫路径动画](https://www.cnblogs.com/feffery/p/12987968.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札85）Python+Kepler.gl轻松制作酷炫路径动画)
- [（数据科学学习手札86）全平台支持的pandas运算加速神器](https://www.cnblogs.com/feffery/p/13049547.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札86）全平台支持的pandas运算加速神器)
- [（数据科学学习手札87）利用adjustText解决matplotlib文字标签遮挡问题](https://www.cnblogs.com/feffery/p/13072364.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札87）利用adjustText解决matplotlib文字标签遮挡问题)
- [（数据科学学习手札88）基于geopandas的空间数据分析——空间计算篇（下）](https://www.cnblogs.com/feffery/p/13129271.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札88）基于geopandas的空间数据分析——空间计算篇（下）)
- [（数据科学学习手札89）geopandas&geoplot近期重要更新](https://www.cnblogs.com/feffery/p/13233271.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札89）geopandas&geoplot近期重要更新)
- [（数据科学学习手札90）Python+Kepler.gl轻松制作时间轮播地图](https://www.cnblogs.com/feffery/p/13322067.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札90）Python+Kepler.gl轻松制作时间轮播地图)
- [（数据科学学习手札91）在Python中妥善使用进度条](https://www.cnblogs.com/feffery/p/13392024.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札91）在Python中妥善使用进度条)
- [（数据科学学习手札92）利用query()与eval()优化pandas代码](https://www.cnblogs.com/feffery/p/13440148.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札92）利用query()与eval()优化pandas代码)
- [（数据科学学习手札93）利用geopandas与PostGIS进行交互](https://www.cnblogs.com/feffery/p/13468203.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札93）利用geopandas与PostGIS进行交互)
- [（数据科学学习手札94）QGIS+Conda+jupyter玩转Python GIS](https://www.cnblogs.com/feffery/p/13558608.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札94）QGIS+Conda+jupyter玩转Python GIS)
- [（数据科学学习手札95）elyra——jupyter lab平台最强插件集](https://www.cnblogs.com/feffery/p/13692800.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札95）elyra——jupyter lab平台最强插件集)
- [（数据科学学习手札96）在geopandas中叠加在线地图](https://www.cnblogs.com/feffery/p/13763601.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札96）在geopandas中叠加在线地图)
- [（数据科学学习手札97）掌握pandas中的transform](https://www.cnblogs.com/feffery/p/13816362.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札97）掌握pandas中的transform)
- [（数据科学学习手札98）纯Python绘制满满艺术感的山脊地图](https://www.cnblogs.com/feffery/p/13977871.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札98）纯Python绘制满满艺术感的山脊地图)
- [（数据科学学习手札99）掌握pandas中的时序数据分组运算](https://www.cnblogs.com/feffery/p/14093478.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札99）掌握pandas中的时序数据分组运算)
- [（数据科学学习手札100）搞定matplotlib中的字体设置](https://www.cnblogs.com/feffery/p/14122415.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札100）搞定matplotlib中的字体设置)
- [（数据科学学习手札101）funcy：Python中的函数式编程百宝箱](https://www.cnblogs.com/feffery/p/14208030.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札101）funcy：Python中的函数式编程百宝箱)
- [（数据科学学习手札102）Python+Dash快速web应用开发——基础概念篇](https://www.cnblogs.com/feffery/p/14258438.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/01 基础概念篇)
- [（数据科学学习手札103）Python+Dash快速web应用开发——页面布局篇](https://www.cnblogs.com/feffery/p/14276803.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/02 页面布局篇)
- [（数据科学学习手札104）Python+Dash快速web应用开发——回调交互篇（上）](https://www.cnblogs.com/feffery/p/14313103.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/03 回调交互篇（上）)
- [（数据科学学习手札105）Python+Dash快速web应用开发——回调交互篇（中）](https://www.cnblogs.com/feffery/p/14349206.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/04 回调交互篇（中）)
- [（数据科学学习手札106）Python+Dash快速web应用开发——回调交互篇（下）](https://www.cnblogs.com/feffery/p/14386458.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/05 回调交互篇（下）)
- [（数据科学学习手札107）在Python中利用funct实现链式风格编程](https://www.cnblogs.com/feffery/p/14400938.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札107）在Python中利用funct实现链式风格编程)
- [（数据科学学习手札108）Python+Dash快速web应用开发——静态部件篇（上）](https://www.cnblogs.com/feffery/p/14416390.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/06 静态部件篇（上）)
- [（数据科学学习手札109）Python+Dash快速web应用开发——静态部件篇（中）](https://www.cnblogs.com/feffery/p/14457005.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/07 静态部件篇（中）)
- [（数据科学学习手札110）Python+Dash快速web应用开发——静态部件篇（下）](https://www.cnblogs.com/feffery/p/14492085.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/08 静态部件篇（下）)
- [（数据科学学习手札111）geopandas 0.9.0重要新特性一览](https://www.cnblogs.com/feffery/p/14519824.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札111）geopandas 0.9.0重要新特性一览)
- [（数据科学学习手札112）Python+Dash快速web应用开发——表单控件篇（上）](https://www.cnblogs.com/feffery/p/14532519.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/09 表单控件篇（上）)
- [（数据科学学习手札113）Python+Dash快速web应用开发——表单控件篇（下）](https://www.cnblogs.com/feffery/p/14561303.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/10 表单控件篇（下）)
- [（数据科学学习手札114）Python+Dash快速web应用开发——上传下载篇](https://www.cnblogs.com/feffery/p/14580950.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/11 上传下载篇)
- [（数据科学学习手札115）Python+Dash快速web应用开发——交互表格篇（上）](https://www.cnblogs.com/feffery/p/14616652.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/12 交互表格篇（上）)
- [（数据科学学习手札116）Python+Dash快速web应用开发——交互表格篇（中）](https://www.cnblogs.com/feffery/p/14641943.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/13 交互表格篇（中）)
- [（数据科学学习手札117）Python+Dash快速web应用开发——交互表格篇（下）](https://www.cnblogs.com/feffery/p/14674642.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/14 交互表格篇（下）)
- [（数据科学学习手札118）Python+Dash快速web应用开发——特殊部件篇](https://www.cnblogs.com/feffery/p/14687893.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/15 特殊部件篇)
- [（数据科学学习手札119）Python+Dash快速web应用开发——多页面应用](https://www.cnblogs.com/feffery/p/14724140.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/16 多页面应用)
- [（数据科学学习手札120）Python+Dash快速web应用开发——整合数据库](https://www.cnblogs.com/feffery/p/14748675.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/17 整合数据库)
- [（数据科学学习手札121）Python+Dash快速web应用开发——项目结构篇](https://www.cnblogs.com/feffery/p/14773887.html)　:airplane:[仓库路径](./【Python+Dash快速web应用开发】系列文章/18 项目结构篇)
- [（数据科学学习手札122）Python+Dash快速web应用开发——内网穿透篇](https://www.cnblogs.com/feffery/p/14775704.html)
- [（数据科学学习手札123）Python+Dash快速web应用开发——部署发布篇](https://www.cnblogs.com/feffery/p/14826195.html)
- [（数据科学学习手札124）pandas 1.3版本主要更新内容一览](https://www.cnblogs.com/feffery/p/14993399.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札124）pandas 1.3版本主要更新内容一览)
- [（数据科学学习手札125）在Python中操纵json数据的最佳方式](https://www.cnblogs.com/feffery/p/15087235.html)　:airplane:[仓库路径](./历史文章附件列表/（数据科学学习手札125）在Python中操纵json数据的最佳方式)
***

<a name="second"></a>
## 2 :card_file_box: 专题系列：

<a name="second-geopandas"></a>
### 2.1 :earth_asia: 基于geopandas的空间数据分析　🚩 `<完结>` 
- [课程附件百度云下载地址](https://pan.baidu.com/s/1ZzbxAm-0-udUaLlhM_KP7w)（提取码：1syu）：

<p align="center">
  <img src="https://geopandas.readthedocs.io/en/latest/_static/geopandas_logo_web.svg" width="500"></img>
</p>

  - [（数据科学学习手札74）基于geopandas的空间数据分析——数据结构篇](https://www.cnblogs.com/feffery/p/11898190.html)<br>
  - [（数据科学学习手札75）基于geopandas的空间数据分析——坐标参考系篇](https://www.cnblogs.com/feffery/p/12285828.html)<br>
  - [（数据科学学习手札77）基于geopandas的空间数据分析——文件IO](https://www.cnblogs.com/feffery/p/12301966.html)<br>
  - [（数据科学学习手札78）基于geopandas的空间数据分析——基础可视化](https://www.cnblogs.com/feffery/p/12361421.html)<br>
  - [（数据科学学习手札79）基于geopandas的空间数据分析——深入浅出分层设色](https://www.cnblogs.com/feffery/p/12381322.html)<br>
  - [（数据科学学习手札82）基于geopandas的空间数据分析——geoplot篇(上)](https://www.cnblogs.com/feffery/p/12779150.html)<br>
  - [（数据科学学习手札83）基于geopandas的空间数据分析——geoplot篇(下)](https://www.cnblogs.com/feffery/p/12901334.html)<br>
  - [（数据科学学习手札84）基于geopandas的空间数据分析——空间计算篇（上）](https://www.cnblogs.com/feffery/p/12909284.html)<br>
  - [（数据科学学习手札88）基于geopandas的空间数据分析——空间计算篇（下）](https://www.cnblogs.com/feffery/p/13129271.html)<br>
  - :sparkles: **衍生文章**
    - [（数据科学学习手札89）geopandas&geoplot近期重要更新](https://www.cnblogs.com/feffery/p/13233271.html)
    - [（数据科学学习手札93）利用geopandas与PostGIS进行交互](https://www.cnblogs.com/feffery/p/13468203.html)
    - [（数据科学学习手札96）在geopandas中叠加在线地图](https://www.cnblogs.com/feffery/p/13763601.html)
    - [（数据科学学习手札111）geopandas 0.9.0重要新特性一览](https://www.cnblogs.com/feffery/p/14519824.html)
    

<a name="second-dash"></a>

### 2.2 :zap: Python+Dash快速web应用开发　🚩 `<完结>` 

<p align="center">
  <img src="https://raw.githubusercontent.com/CNFeffery/DataScienceStudyNotes/master/100%E6%9C%9F%E4%B9%8B%E5%90%8E/Plotly_Dash_logo.png" width="450"></img>
</p>

  - [（数据科学学习手札102）Python+Dash快速web应用开发——基础概念篇](https://www.cnblogs.com/feffery/p/14258438.html)<br>
  - [（数据科学学习手札103）Python+Dash快速web应用开发——页面布局篇](https://www.cnblogs.com/feffery/p/14276803.html)<br>
  - [（数据科学学习手札104）Python+Dash快速web应用开发——回调交互篇（上）](https://www.cnblogs.com/feffery/p/14313103.html)<br>
  - [（数据科学学习手札105）Python+Dash快速web应用开发——回调交互篇（中）](https://www.cnblogs.com/feffery/p/14349206.html)<br>
  - [（数据科学学习手札106）Python+Dash快速web应用开发——回调交互篇（下）](https://www.cnblogs.com/feffery/p/14386458.html)<br>
  - [（数据科学学习手札108）Python+Dash快速web应用开发——静态部件篇（上）](https://www.cnblogs.com/feffery/p/14416390.html)<br>
  - [（数据科学学习手札109）Python+Dash快速web应用开发——静态部件篇（中）](https://www.cnblogs.com/feffery/p/14457005.html)<br>
  - [（数据科学学习手札110）Python+Dash快速web应用开发——静态部件篇（下）](https://www.cnblogs.com/feffery/p/14492085.html)<br>
  - [（数据科学学习手札112）Python+Dash快速web应用开发——表单控件篇（上）](https://www.cnblogs.com/feffery/p/14532519.html)<br>
  - [（数据科学学习手札113）Python+Dash快速web应用开发——表单控件篇（下）](https://www.cnblogs.com/feffery/p/14561303.html)<br>
  - [（数据科学学习手札114）Python+Dash快速web应用开发——上传下载篇](https://www.cnblogs.com/feffery/p/14580950.html)<br>
  - [（数据科学学习手札115）Python+Dash快速web应用开发——交互表格篇（上）](https://www.cnblogs.com/feffery/p/14616652.html)<br>
  - [（数据科学学习手札116）Python+Dash快速web应用开发——交互表格篇（中）](https://www.cnblogs.com/feffery/p/14641943.html)<br>
  - [（数据科学学习手札117）Python+Dash快速web应用开发——交互表格篇（下）](https://www.cnblogs.com/feffery/p/14674642.html)<br>
  - [（数据科学学习手札118）Python+Dash快速web应用开发——特殊部件篇](https://www.cnblogs.com/feffery/p/14687893.html)<br>
  - [（数据科学学习手札119）Python+Dash快速web应用开发——多页面应用](https://www.cnblogs.com/feffery/p/14724140.html)<br>
  - [（数据科学学习手札120）Python+Dash快速web应用开发——整合数据库](https://www.cnblogs.com/feffery/p/14748675.html)<br>
  - [（数据科学学习手札121）Python+Dash快速web应用开发——项目结构篇](https://www.cnblogs.com/feffery/p/14773887.html)<br>
  - [（数据科学学习手札122）Python+Dash快速web应用开发——内网穿透篇](https://www.cnblogs.com/feffery/p/14775704.html)<br>
  - [（数据科学学习手札123）Python+Dash快速web应用开发——部署发布篇](https://www.cnblogs.com/feffery/p/14826195.html)<br>

***

<a name="pandas"></a>
## 3 :man_astronaut: pandas相关

<p align="center">
  <img src="https://pandas.pydata.org/docs/_static/pandas.svg" width="350"></img>
</p>

- [（数据科学学习手札69）详解pandas中的map、apply、applymap、groupby、agg](https://www.cnblogs.com/feffery/p/11468762.html)<br>
- [（数据科学学习手札72）用pdpipe搭建pandas数据分析流水线](https://www.cnblogs.com/feffery/p/12179647.html)<br>
- [（数据科学学习手札73）盘点pandas 1.0.0中的新特性](https://www.cnblogs.com/feffery/p/12214635.html)<br>
- [（数据科学学习手札86）全平台支持的pandas运算加速神器](https://www.cnblogs.com/feffery/p/13049547.html)<br>
- [（数据科学学习手札92）利用query()与eval()优化pandas代码](https://www.cnblogs.com/feffery/p/13440148.html)<br>
- [（数据科学学习手札97）掌握pandas中的transform](https://www.cnblogs.com/feffery/p/13816362.html)<br>
- [（数据科学学习手札99）掌握pandas中的时序数据分组运算](https://www.cnblogs.com/feffery/p/14093478.html)<br>
- [（数据科学学习手札124）pandas 1.3版本主要更新内容一览](https://www.cnblogs.com/feffery/p/14993399.html)<br>

***

<a name="jupyter"></a>
## 4 :ghost: jupyter相关

<p align="center">
  <img src="https://jupyter.org/assets/nav_logo.svg" width="320"></img>
</p>

- [（数据科学学习手札81）conda+jupyter玩转数据科学环境搭建](https://www.cnblogs.com/feffery/p/12609118.html)<br>
- [（数据科学学习手札94）QGIS+Conda+jupyter玩转Python GIS](https://www.cnblogs.com/feffery/p/13558608.html)<br>
- [（数据科学学习手札95）elyra——jupyter lab平台最强插件集](https://www.cnblogs.com/feffery/p/13692800.html)<br>

***

<a name="keplergl"></a>
## 5 :penguin: kepler.gl相关

<p align="center">
  <img src="https://d1a3f4spazzrp4.cloudfront.net/kepler.gl/website/icons/kepler.gl-logo.png" width="320"></img>
</p>

- [（数据科学学习手札85）Python+Kepler.gl轻松制作酷炫路径动画](https://www.cnblogs.com/feffery/p/12987968.html)<br>
- [（数据科学学习手札90）Python+Kepler.gl轻松制作时间轮播地图](https://www.cnblogs.com/feffery/p/13322067.html)<br>

***

<a name="third"></a>
## 6 :wrench: 补充&勘误内容记录：
- 2019.10.28 为[（数据科学学习手札69）详解pandas中的map、apply、applymap、groupby、agg](https://www.cnblogs.com/feffery/p/11468762.html)补充`apply()同时返回多列数据的方法`
- 2019.11.26 为[（数据科学学习手札69）详解pandas中的map、apply、applymap、groupby、agg](https://www.cnblogs.com/feffery/p/11468762.html)补充`tqdm_notebook()版apply()进度条的方法`
- 2020.01.15 为[（数据科学学习手札72）用pdpipe搭建pandas数据分析流水线](https://www.cnblogs.com/feffery/p/12179647.html)补充`用算术相加法拼接流水线的方法`
- 2020.08.27 为[（数据科学学习手札94）QGIS+Conda+jupyter玩转Python GIS](https://www.cnblogs.com/feffery/p/13558608.html)勘误：1.`PyQgis`中的**渔网创建工具**无`INPUT`参数；2.现阶段`geopandas`与`PyQgis`之间并无互相**兼容相通**的设定，因此无法将`GeoDataFrame`类型的变量作为`INPUT`参数传入`PyQgis`算法执行过程中
- 2020.09.28 为[（数据科学学习手札69）详解pandas中的map、apply、applymap、groupby、agg](https://www.cnblogs.com/feffery/p/11468762.html)更新：由于`numpy`的版本更新，故将**3.1**章节下`结合apply()`中的`df['name'][np.argmax(df['count'])]`更新为`df['name'][df['count'].idxmax()]`
- 2021.01.12 为[（数据科学学习手札74）基于geopandas的空间数据分析——数据结构篇](https://www.cnblogs.com/feffery/p/11898190.html)即我们的`geopandas`系列教程第一篇开头增加**最新稳定安装geopandas的快捷命令**
- 2021.03.08 为[（数据科学学习手札103）Python+Dash快速web应用开发——页面布局篇](https://www.cnblogs.com/feffery/p/14276803.html)勘误：将`css`文件置于文中所述`assets`路径下时，无需再传入`external_stylesheets`参数，因为`dash`会自动识别并载入`assets`路径下所有文件
- 2021.03.13 为[（数据科学学习手札103）Python+Dash快速web应用开发——页面布局篇](https://www.cnblogs.com/feffery/p/14276803.html)勘误：由于`dash_bootstrap_components`的更新，`Alert()`部件默认参数下没有背景色等样式，需添加`color`参数即可
- 2021.04.24 为[（数据科学学习手札96）在geopandas中叠加在线地图](https://www.cnblogs.com/feffery/p/13763601.html)更新：需将`requests`降级到`2.24.0`才可在**科学上网**的同时正常使用在线地图叠加功能
- 2021.05.09 为[（数据科学学习手札105）Python+Dash快速web应用开发——回调交互篇（中）](https://www.cnblogs.com/feffery/p/14349206.html)更新`app5`，解决了输入值不为数字时的漏洞

***

<a name="fourth"></a>
## 7 :running: To-do List:
- [ ] **基于pysal的地理空间数据分析**

