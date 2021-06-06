# 金融市场
## 01金融的基本概念
**什么是金融**  
- 狭义的定义：资金融通  
- 广义的定义：研究跨期配置稀缺资源的一门学科  

**金融的分类**  
- 公司金融：研究公司的财务决策、融资行为、IPO等等  
- 资产定价：研究投资者的投资行为、资产收益率等等  

**金融学的四大理论支柱**  
- 有效市场假说
- 均值方差组合
- CAPM模型
- 期权定价BS模型
## 02金融市场与交易制度
**金融市场**  
- 分类
    - 直接融资市场、间接融资市场
    - 一级市场、二级市场
    - 股票市场、债券市场、衍生品市场
- 参与者：银行、券商、保险、基金、信托、私募等等（韭菜）
- 监管机构：央行、证监会、银保监会

**交易制度**  
- T+1：第T天买入的股票，第T+1天及以后才能卖出
- 涨跌停：涨跌幅限制为10%，ST股票5%，创业板/科创板20%
- 卖空限制：只允许做多，不允许卖空
- 交易成本：佣金（0.025%）&印花税（0.1%）
- 竞价原则：价格优先、时间优先
- 竞价方式：集合竞价、连续竞价
- 上海证券交易所：沪市主板、科创板
- 深圳证券交易所：深市主板、中小板、创业板、新三板
- 股票价格指数：上证综指、沪深300、上证50、中证500
## 03金融交易品种
**市场行情软件**  
- Choice东财金融终端
- [东财终端](http://emdesk.eastmoney.com/pc_activity/Pages/VIPTrade/pages/index.html)

**常见品种**  
- 股票
    - SH股：指在上海证券交易所进行交易的股票，股票代码6字开头
    - SZ股：指在深圳证券交易所进行交易的股票，股票代码0或3开头
    - SSE: Shanghai Stock Exchange
    - SZSE: Shenzhen Stock Exchange
- ETF
    - Exchange Traded Funds，交易型开放式指数基金，通常又被称为交易所交易基金
    - ETF在一级市场可以申购和赎回
    - ETF在二级市场的交易价格常常不等于净值——有套利机会
- 商品期货
    - 是一种衍生品，保证金交易，带杠杆（很高），实物交割
    - 上期所、大商所、郑商所
    - 主力合约：成交量最大的期货合约
- 股指期货
    - 8倍-10倍的杠杆，现金交割
    - 中金所
    - IH上证50股指期货、IF沪深300股指期货、IC中证500股指期货
- 期权
- 债券
    - 杠杆更高
    - 不建议碰企业债，垃圾太多
- 外汇
## 04金融市场指数
总体来说，数字越大，股票的市值越小  
- 沪深300（规模大、流动性好的300只股票）
- 中证100（沪深300中规模最大的100只）
- 中证200（沪深300中剩下的200只）
- 中证500（剔除沪深300和总市值前300后，总市值排名靠前的500只股票，反映中小市值公司的股价）
- 中证700（中证500+中证200）
- 中证800（中证500+沪深300）
- 中证1000（剔除中证800后，规模偏小且流动性好的100只股票）

# 量化交易体系的开启姿势
## 量化的历史和发展
量化交易可以被定义为人们通过严谨的研究，系统化地执行交易策略  
量化策略和主观判断型策略的区别只是在于策略如何被制定一级如何被执行  
## 寻找适合自己的量化策略
**自我评估**  
I. 你每天必须在交易上花多少时间？这很重要，因为有多少时问可以利用几乎决定了你必须开发什么样的交易系统。如果你是上班族，老板又盯得很紧，只能每晚看一下市场，那么显然你需要使用一个更长线的系统，而不是一个需要你时时刻刻都必须盯盘的系统。  
II. 在你交易时，你能料到会有多少分心的事？  
III. 你预计需要多少时问来开发你的交易系统，处理个人心理工作以及制定进行交易的业务计划？  
IV. 你的IT技能如何？会不会写代码？在你开始从事交易之前还需要什么样的技能？  
V. 你对统计学了解多少？  
VI. 你对自己的市场知识如何评价？你是否已经形成了一套对市场趋势或者投资品种的评估分析方法？  
VII. 你的心理优势和劣势是什么？尤其是在交易系统开发方面。  
VIII． 你在自我约束方面的优势和劣势是什么？  
IX． 你会不会很容易冲动，被交易的亢奋情绪所左右？你在家庭生活、工作或者过去的交易经历中，是否遇到过冲突？你是否经常感到恐惧、气愤或者突然出现情绪上的问题？  
X. 根据你的个人资源和财力情况，你需要在着手交易之前学习什么，完成什么或者解决什么？你打算怎样去做？  
**个人投资者目标**  
I. 你在交易方面的优势是什么？你能给出这些优势的具体例子吗？  
II. 你有多少资产用于投资？其中有多少你可以输得起？比如，很多基金的平仓线设置在亏损15％或者亏损20％，那么你呢？在一次交易中你能承受多少风险？  
III. 你每年需要赚多少钱？你需要靠那些钱来养家糊口吗？  
IV. 你如果赚的钱不够生活基本开支怎么办？你能赚到超过你生活基本开支所必须的钱，从而使得你的交易资本有所增长吗？你能经受为支付每月的账单而从交易资本中定期取钱吗？  
V. 对于现实你是否能够轻易接受？比如说，假如你有一个不错的交易系统，它有一半时问是对的，并且盈利是亏埙的两倍。在这一系统下，你也可能轻易地连亏10次。你的系统工作依然稳定，可是你无法避免连亏10次，你能忍受这样的系统吗？  
VI. 你有没有时间进行短线交易？  
VII. 你可以日复一日地一个人工作吗？你需要有一两个人在身边，或者需要一大堆人在身边吗？那些人对你的影响有多大？  
VII. 总的来说，你每年期望赚到交易资本的百分之多少？  
IX. 为了达到这个目标，你愿意承受什么样的风险水平？  
XI. 你愿意承受的最大回撤（从最高点到最低点的跌幅〕是多少？  
XI. 你是怎样知道自己的计划是有效的，怎样知道它什么时候是无效的？在各种市场上，你对系统的期望是什么？  
**你的交易观念**  
I. 你想在什么样的市场上交易？你对市场的流动性有什么要求？  
II. 在入市前你需要准备什么条件吗？  
III. 你对入市有什么信念？你认为入市有多重要？  
IV. 在回报与亏损方面给定目标之后，你怎样考虑停止交易的条件？停止交易后你怎样重新返回市场？你想要什么样的止损方式？  
V. 你如何计划实现盈利？是反转止损、跟踪止损、技术止损，还是设定价格目标止盈？  
VI. 你在确定头寸规模方面怎样把握？  
# 打造稳定交易体系的逻辑基础
## 交易体系的关键要素
- 胜率 Percent Profitable：可靠度、胜率或者盈亏时间比例
- 赔率 Odds/P&L：又称盈亏比，在以最小单位进行交易时，相对于亏损而言，你的盈利水平的相对规模
- 成本 Costs：每笔交易的成本
- 频率 Frequency：获得交易机会的频率
- 头寸 Position：头寸规模的确定，或者说，一次交易多少个单位
- 本金 Capital：你的投资资本规模，或者说本金的规模
# Python语言运行配置
**程序语言基础**  
- 编程语言  
  - 解释器：直接执行用编程语言编写的指令的程序
  - 编译器：把源代码转换成（翻译）低级语言的程序
- 命令式语言 (Imperative)
    - 详细的命令机器怎么（How）去处理一件事情以达到你想要的结果（What）
    - Python/C/C++ Java
 - 申明式语言 (Declarative)
    - 只告诉你想要的结果（What），机器自己摸索过程（How）
    - SQL\Prolog\TensorFlow

**人生苦短，我用Python**  
- 解释性语言 Interpretive
- [面向对象](https://www.liaoxuefeng.com/wiki/1016959663602400/1017495723838528) Object Oriented
- 支持[函数式编程](https://www.liaoxuefeng.com/wiki/1016959663602400/1017328525009056) Lambda

**IDE集成开发环境**
- 集成开发环境（IDE，Integrated Development Environment ）是用于提供程序开发环境的应用程序，一般包括代码编辑器、编译器、调试器和图形用户界面等工具。集成了代码编写功能、分析功能、编译功能、调试功能等一体化的开发软件服务套。所有具备这一特性的软件或者软件套（组）都可以叫集成开发环境。
- Jupyter lab/notebook
- Visual Studio Code

# Python语言基础知识
请用空格缩进  
python[关键字](https://www.w3school.com.cn/python/python_ref_keywords.asp)列表可以在keyword[模块](https://www.runoob.com/python/python-modules.html)中找到：  
import keyword as kwd  
print(kwd.kwlist)  
## Python数据类型与结构
推荐阅读文档：http://docs.python.org/3/library/stdtypes.html  
### Python基本内建类型
**字符串 string**  
```
my_string='it is test'  
my_string  
type(my_string)  
my_new_string=my_string.replace('is','will be')  
my_new_string  
your_string='{} is fun'.format('Python')  
your_string  
```
[str.join()](https://www.runoob.com/python/att-string-join.html)  
[str.strip()](https://www.runoob.com/python/att-string-strip.html)  
[str.split()](https://www.runoob.com/python/att-string-split.html)  
**整数 int**  
```
a=2  
b=3  
c=a+b  
print(c)  
```
**浮点数 float**  
**布尔值 bool**  
### Python基本数据结构
**List 列表 []**  
2D list（二维列表）  
```
list_of_list = [[1,2,3],[4,5,6],[7,8,9]]  
```
List comprehension（列表推导）  
```
init_a_list = [i for i in range(9)]  
init_a_list = [i ** 2 for i in range(9)]  
init_2d_list = [[i+j for i in range(5)] for j in range(9)]  
```
Insert/Pop（插入和弹出）  
```
my_list.insert(0,'stuff)  
print(my_list.pop(0))  
```
列表排序  
```
random_list=[3,12,5,6]  
sorted_list=sorted(random_list)  
random_list=[(3,'A'),(12,'D'),(5,'M'),(6,'B')]  
sorted_list=sorted(random_list,key=lambda x:x[1])  
```
**Set (unordered, unique) 集合 {}**  
集合具有集合论的运算方法  
```
my_set={i ** 2 for i in range(10)}  
my_set.add()  
```
用列表初始化集合，返回是无序、无重复的集合  
集合的使用之一就是去掉列表中重复的数据  
aset=set(alist)  
**Dictionary (mapping) 字典 {}**  
Dict Comprehension（字典推导式）  
```
my_dict = {i:i ** 2 for i in range(10)}  
```
Get dictionary keys, values（获取字典的键与值，依据字典的键获取相应的值）  
```
my_dict.keys()  
my_dict.values()  
my_dict[i]  
```
**Tuple 元组 ()**  
```
a_tuple = (1,0.2,'0.3','data')  
a_tuple[3]  
```
tuple只有两种方法count()和index()，计算每个对象出现的次数和某个对象出现的位置  
## Python语句与语法  
**Python程序的组成**  
- Python的程序形式上分解为程序块、语句、表达式和对象  
- 程序由程序块（Block）构成  
- 程序块包含语句（statement）  
- 语句包含表达式（expression）  
- 表达式建立并处理对象（object）  

**条件语句if-elif-else**  
```
val=50   
if val>=100:  
    print('val>=100)  
elif val>10:  
    print('100>val>10')  
else:  
    print('val<=10')  
```
**for循环**  
```
for item in my_list:  
    print(item)  
```
**While循环**  
```
idx = 0  
while idx<len(data):  
    print(data[idx])  
    idx += 1  
```
## Python函数
**函数定义**  
def 函数名(参数):  
**[定义主函数入口](https://blog.konghy.cn/2017/04/24/python-entry-program/)**  
```
if __name__ == '__main__ '  
```
**匿名函数lambda**  
https://book.pythontips.com/en/latest/  
Lambda是一个表达式，而不是一个语句  
map会对一个序列对象中的每一个元素应用被传入的函数，并且返回一个包含所有函数调用结果的一个列表  
```
items = [1,2,3,4,5]  
squared = list(map(lambda x: x ** 2,items))  
```
## Python类与OOP
**什么是类？**  
- 类（Class）：某一类对象的抽象定义  
- 对象（Object）：类的一个实例  
- 属性（Attribute）：类（类属性）或者类实例（实例属性）的特征  
- 方法（Method）：类可以实现的一个操作  
- 参数（Parameters）：影响方法行为的输入  
- 实例化（Instance）：根据某个抽象类创建具体对象的过程  
- 类初始化（Initialize）：使用具体的参数初始化类  
- 实例化（Instantiate）一个类，获得一个实例（Instance）         
- 调用实例的方法（instance method）  
## Python模块
**Python代码组织层次（逻辑上）**  
代码块（Block）->函数（function）->类（class）->包（package）  
**模块（modules）与包（package）**  
- 模块就是*.py结尾Python源文件  
- 包是一个目录，包含__init__.py文件和其它模块与包
- python 通过import语句来引用包

**Pip包管理工具**   
- pip 是python的包管理工具(package manager)
    - pip —version 查看pip版本和安装位置
    - pip list 列出所有的安装的包
- pip install/uninstall 安装/删除包

**Python Debug**  
使用pdb (python debugger)
