# GIS
## GIS概述  
### GIS概念  
Geographic Information System 简称GIS，地理信息系统  
### GIS观点  
- 地图观  
景观学派与制图学派认为GIS是底图处理和显示系统  
- 数据库观
计算机学派强调数据库理论和技术方法  
- 空间分析观  
地理学派强调空间分析和模拟  
### GIS演化  
- S-system
新诠释:  
- S-science  
- S-service  
- S-society  
### GIS 相关学科关系  
地理信息系统与计算机辅助系统   
- CAD  制图
- MIS 管理信息系统
- RS  遥感
- 计量地理学，空间研究  
### GIS的功能  
- 数据采集与编辑  
- 数据的存储与管理  
- 产品的制作与显示  
- 空间查询与分析
- 二次开发与编程  
### GIS应用领域  
- 区域范围
- 专业领域  
- 解决问题  
- 提供服务  
- 技术方法  
### GIS发展趋势  
- 标准化  
- 数据多维化  
- 系统专门化  
- GIS网络化  
- 应用社会化  
### 空间量化分析模型  
- 空间缓冲分析  
道路噪音，河流缓冲，高压电缓冲区  
- 空间网络分析   
河流水系，道路管网，电力网络  
- 空间叠加分析  
多要素分析  
- 空间统计分析  
空间位置分布属性，布局  
- 空间三维分析  
填挖方，地形分析，可视化  
- 空间句法分析  
依托网络结构看集成值  
- 空间遥感分析  
影像数据分析识别提取     
### 景区相关研究  
- 选址评价分析  
集散地、新增景点、服务设施  
*权重的确定 yaahp*  
- 空间格局分析  
景点可达性，结构关系，空间分异，空间格局  
*社会网络模型Ucinet和Gephi  
空间句法SDNA，Depthmap，Fragstats*  
- 旅游线路分析
网络分析算法，线路设计  
*Network Analysis：多模式网络*  
- 服务配置分析  
吃住行游购娱服务设施网络分析  
*Location-allocation*  
- 景观结构分析  
地形和三维视线视域分析，可视性分析  
*3D Analysis*  
- 旅游区划分析  
网络分析多因素叠加，解析点线面内在关系和主次关系  
*Weighted—Overlay*  
- 驱动因素分析  
GIS空间可视化表达  
*自变量、因变量  
回归方程  
Logit模型*  
- 灾害危险分析  
避难场所，人群分散  
*供需关系，可达性*  
- 行为模式分析  
空间分析+可视化，GPS游线  
*GPS，文化，类型化，聚类分析*  
- 信息服务分析  
智慧景区，虚拟体验，信息集成  
*智慧旅游，个性化*    
## 城乡规划新技术发展  
### 个人视角看发展  
这一节主要讲李渊老师个人与GIS的渊源  
### 数据获取  
#### 规划数据分类  
- 基础测量数据  
- 遥感影像数据  
- 规划成果数据  
- 规划管理数据  
- 人口统计数据  
- 经济、环保、生态、旅游、教育等产生的数据  
#### 美国数据获取  
- [美国地质调查局（USGS）](http://glovis.usgs.gov/
)   
- [美国国家航空航天局（NASA)](http://neo.sci.gsfc.nasa.gov)
- 美国人口普查局（U.S. Census Bureau）
- 美国联邦应急管理局（FEMA）
- 美国渔类及野生动植物管理局（USFWS）
- 美国国家公园管理局（NPS）
- 美国林务局（USFS）
- 美国国家大地测量局（NGS）
- 美国运输统计局（BTS）
- 美国联邦地理数据委员会（FGDC）  
- [OpenStreetMap](http://wiki.openstreetmap.org/wiki/Downloading_data)   
直接从[网站下载](http://download.geofabrik.de/)，通过GIS插件下载，网站下载+插件工具转换，QGIS获取，FME->OSMDownload    
- GLCF数据获取  
卫星衍生数据，LandSat，Modis等遥感影像   
- [TIGER数据获取](http://www.census.gov/geo/maps-data/data/tiger.html)  
美国人口普查局提供拓扑统一地理编码格式TIGER数据文件，包含 了行政和统计区界限，可以链接到人口普查数据，以及道路、铁路、河流、水体、电网和管线资料。  
### 国内数据  
- [国家地球系统科学数据共享服务平台数据获](http://www.geodata.cn/index.html)   
- [地理空间数据云](http://www.gscloud.cn/)    
## 规划分析模型  
**空间句法模型**
space syntax  
是关于空间与社会一系列理论和技术的概念  
- 理论基础：1.空间的自然法则（空间的分割，再现，连接等基本几何关系）  
2.个人的空间认知与社会对空间的影响  
3.空间对个人饿社会的影响  
- 扩展理论：自然交通，犯罪空间模型，交通与用地的互动，空间自组织结构，空间模式语言，空间结构的不同吸引点  
- 分析方法：凸形分析法，轴线法，视域分析法  
通过连接值，控制值，平均深度，集成度，智能度等形态分析变量来表达空间之间的相互关系  
- 空间句法软件：Axwoman（Arc Gis10），UCL Depthmap，SDNA（可达性，人流预测）
**系统动力学模型**    
- 基本概念：System Dynamic，是一门分析研究信息反馈系统的学科，是认识与解决系统问题，沟通自然科学与社会科学的边缘学科。  
- 基本要素  
结构  
因果关系  
反馈回路  
水平变量  
流率变量  
常量  
辅助变量  
延迟  
- 系统动力学软件  
DYNAMO  
Stella  
Vensim  
**元胞自动机**  
- 基本概念  
时间，空间和状态都离散，相互作用及因故关系皆局部的网格动力学模型。  
- 模型  
SLEUTH  
**多主体模型**  
- 基本概念  
系统建模的离散数据模型。基于格网空间的主体模型  
- 软件  
Netlogo
（类似python画图？turtle）  
### 规划支持系统  
#### 背景   
GIS并不能满足解决实际工作需要   
#### 规划观  
#### 系统观  
#### 决策观  
#### 定义  
以数据库为核心，集成各项技术   
GIS,SDSS，PSS  
#### 软件  
- TRAUNS，UrbanSim  大尺度  
- INDEX  规则模型  
- LEAM  系统动力学  
- what if  土地利用  
GIS数据库+土地适宜性分析模型+增长分析模型+土地分配模型  
- CommunityViz  
适宜性分析  
同步创建3D效果  
- INDEX  
基于ArcMap扩展模块
发掘社区规划与可持续发展之间的关系和纽带  
## ArcGIS工具  
### 背景  
- ArcCatlog  
浏览数据、创建定义管理数据、创建元数据
- ArcMap  
制图、编辑、查询、分析、绘图
- ArcToolBox  
地理操作命令、创建工具和分析模型  
- ArcMap——ArcView
图层、菜单条、工具条、状态栏、图形显示区
- ArcScence/ArcGlobe  
三维动态  
### ArcGIS与CAD  
- 湘源，飞时达  
- CAD与ArcGIS  
CAD的潜在要素
point点，line线  
- CAD转SHP：ArcGIS  
- CAD转SHP：飞时达  
多规合一平台  
- [GIS转CAD](https://www.icourse163.org/learn/XMU-1002835009?tid=1205946205#/learn/content?type=detail&id=1210395620&cid=1212440591)  
容差转换，将CAD未闭合的线段设置容差范围，将线转换为面  
工具箱中的Feature，Feature to polygon
![20200803_101854_30](image/20200803_101854_30.png)
- CAD文字转点带属性    
工具箱中的数据管理Feature,Feature to point

![20200803_102321_72](image/20200803_102321_72.png)   

- GIS转CAD  
Conversion——toCAD  

![20200803_102552_83](image/20200803_102552_83.png)   
### ArcMap中加载互联网地图
- ArcGIS自带的online
文件file  

![20200803_103614_12](image/20200803_103614_12.png)

可以打开Google地图，必应地图及ESRI和网友共享的各种地图数据   
- ArcGIS自带的BaseMap  
file中打开    
- GIS Server 加载地图  
利用地理空间位置数据制作地图，将地图定义为地理数据的可视化表现，能根据用户请求返回相应的地图，包括PNG、GIF、JPEG等栅格图或SVG、WEB、CGM等矢量图
通过WMS，如天地图
- 地图下载器  