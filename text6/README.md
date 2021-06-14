<p><strong>期末项目设计报告</strong></p>
<table>
<tbody>
<tr>
<td width="255">
<p>题目</p>
</td>
<td colspan="3" width="596">
<p>基于Oracle的水果销售的数据库设计</p>
</td>
</tr>
<tr>
<td width="255">
<p>课程</p>
</td>
<td colspan="3" width="596">
<p>Oracle数据库应用</p>
</td>
</tr>
<tr>
<td width="255">
<p>学院</p>
</td>
<td colspan="3" width="596">
<p>信息科学与工程学院</p>
</td>
</tr>
<tr>
<td width="255">
<p>专业</p>
</td>
<td width="242">
<p>软件工程</p>
</td>
<td width="128">
<p>年级</p>
</td>
<td width="227">
<p>2018级</p>
</td>
</tr>
<tr>
<td width="255">
<p>学生姓名</p>
</td>
<td width="242">
<p>仝若凡</p>
</td>
<td width="128">
<p>学号</p>
</td>
<td width="227">
<p>201710414417</p>
</td>
</tr>
<tr>
<td width="255">
<p>指导教师</p>
</td>
<td width="242">
<p>赵卫东</p>
</td>
<td width="128">
<p>职称</p>
</td>
<td width="227">
<p>副教授</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<table width="836">
<tbody>
<tr>
<td width="142">
<p><strong>评分项</strong></p>
</td>
<td width="553">
<p><strong>评分标准</strong></p>
</td>
<td width="71">
<p><strong>满分</strong></p>
</td>
<td width="71">
<p><strong>得分</strong></p>
</td>
</tr>
<tr>
<td width="142">
<p>文档整体</p>
</td>
<td width="553">
<p>文档内容详实、规范，美观大方</p>
</td>
<td width="71">
<p>10</p>
</td>
<td width="71">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="142">
<p>表设计</p>
</td>
<td width="553">
<p>表，表空间设计合理，数据合理</p>
</td>
<td width="71">
<p>20</p>
</td>
<td width="71">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="142">
<p>用户管理</p>
</td>
<td width="553">
<p>权限及用户分配方案设计正确</p>
</td>
<td width="71">
<p>10</p>
</td>
<td width="71">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="142">
<p>PL/SQL设计</p>
</td>
<td width="553">
<p>存储过程和函数设计正确</p>
</td>
<td width="71">
<p>25</p>
</td>
<td width="71">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="142">
<p>备份方案</p>
</td>
<td width="553">
<p>备份方案设计正确</p>
</td>
<td width="71">
<p>25</p>
</td>
<td width="71">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="142">
<p>容灾方案</p>
</td>
<td width="553">
<p>DataGuard设计正确</p>
</td>
<td width="71">
<p>10</p>
</td>
<td width="71">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td colspan="3" width="766">
<p><strong>得分合计</strong></p>
</td>
<td width="71">
<p>&nbsp;</p>
</td>
</tr>
</tbody>
</table>
<p>2021年6月12 日</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>目录</p>
<p>&nbsp;</p>
<ul>
<li>总述&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;3</li>
</ul>
<p>1.1 编写目的&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;3</p>
<p>1.2背景&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;3</p>
<p>2外部设计&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;3</p>
<p>2.1环境说明&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;3</p>
<p>3 数据库逻辑设计&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;4</p>
<p>3.1 实体模型&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;5</p>
<p>3.2 实体联系模型&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;6</p>
<p>4 表结构设计&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;7</p>
<p>5用户创建与空间分配&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;10</p>
<p>5.1 创建表空间&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;10</p>
<p>5.2 创建用户&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;11</p>
<p>5.3 存储空间的分配&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;11</p>
<p>6 创建表，约束和索引&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;12</p>
<p>7 创建触发器，序列和视图&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;16</p>
<p>7.1 创建触发器&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;16</p>
<p>7.2 创建序列&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;19</p>
<p>7.3 创建视图&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;20</p>
<p>8 创建程序包，函数和过程&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;21</p>
<p>9 数据库测试&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;23</p>
<p>9.1 向表中插入数据&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;23</p>
<p>9.2 调用程序包中的函数&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;25</p>
<p>9.3 调用程序包中的过程&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;26</p>
<p>10 自动联机备份方案设计&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;27</p>
<p>11 容灭方案设计&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;29</p>
<p>12 总结 &hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;35</p>
<p>&nbsp;</p>
<p>1 总述</p>
<ul>
<li>编写目的</li>
</ul>
<p>随着科学的不断进步,计算机应用己经遍布整个社会的每个角落。计算机在商业管理上的应用,使其逐步系统化,完善化。利用计算机帮助企业高效率完成销售管理的日常事务,是适应现代企业制度要求,也是推动企业管理走向科学化,规范化的必要条件。由于销售管理是一项琐碎、复杂而又十分细致的工作,在销售的各个环节中不允许出错,实行手工操作,就会浪费大量的人力资源和资金、时间,而销售系统的使用将可以避免以上的难题,不但能够保证单价,账目核算准确无误,而且还可以利用该系统对有关销售的各种信息进行统计,服务于财务部门和销售部门的业务处理流程的本文档通过对水果批发进销存工作流程的深入了解及进行了可行性分析后,对水果销售管理系统做了需求分析,功能模块划分,数据库的设计与实现。</p>
<ul>
<li>背景</li>
</ul>
<p>现在网络购物现象发展迅速,受网上购买衣服、玩具等没有保质期限制的物品影响,蔬菜水果这类有保质期限制的物品也开始紧跟潮流,逐渐的向着网上进行购买发展,基于此网上购买瓜果蔬菜便成了人们向往的事情。这样的创新尝试将推进网络购物的一个新领域的发展,本系统正是为了应对这一需求而设计的。水果网购是近年才在中国流行,其中最具代表地位的水果销售商是飞果网、百森水果网等进口品牌企业。在电子商务网站中,网上购买瓜果蔬菜是目前应用最人性化的范例之一。给人们的日常生活尤其是现在工作忙碌的年轻人提供了便利。本系统就是针对网络购买蔬菜水果进行设计的,一个以义乌农贸城为背景,进行网络销售蔬菜水果的一个系统,这个系统以Oracle 12c为工具,使用SQLDeveloper数据库进行数据的管理,通过Hibemet与数据库进行交互,通过需求分析设计实现了用户注册、登录、身份验证及用户数据的采集、瓜果蔬菜的浏览,通过浏览进行选择,也可以有针对性的进行查询和选择性的购买等功能,基本上能够满足对蔬菜水果网络的购买的需求。</p>
<ul>
<li>外部设计
<ul>
<li>环境说明</li>
</ul>
</li>
</ul>
<p>Oracle数据库系统是美国Oracle公司（甲骨文）提供的以分布式数据库为核心的一组软件产品，是目前最流行的客户/服务器（client/server）或B/S体系结构的数据库之一，比如SilverStream就是基于数据库的一种中间件。Oracle数据库是目前世界上使用最为广泛的数据库管理系统，作为一个通用的数据库系统，它具有完整的数据管理功能；作为一个关系型数据库，它是一个完备关系的产品；作为分布式数据库它实现了分布式处理功能，但它的所有知识，只要在一种机型上学习了Oracle知识，便能在各种类型的机器上使用它。</p>
<p>Oracle SQL Developer是Oracle公司出品的一个免费的集成开发环境。是一个免费非开源的用以开发数据库应用程序的图形化工具，使用 SQL Developer 可以浏览数据库对象、运行 SQL 语句和脚本、编辑和调试 PL/SQL 语句。另外还可以创建执行和保存报表。该工具可以连接任何 Oracle 9.2.0.1 或者以上版本的 Oracle 数据库，支持 Windows、Linux 和 Mac OS X 系统。Oracle SQL Developer是针对Oracle数据库的交互式开发环境（IDE）。</p>
<p>Oracle SQL Developer简化了Oracle数据库的开发和管理。 SQL Developer提供了PL/SQL程序的端到端开发，运行查询工作表的脚本，管理数据库的DBA控制台，报表接口，完整的数据建模的解决方案，并且能够支持将你的第三方数据库迁移至Oracle。</p>
<p>SQL Developer可以连接到任何Oracle 10g及其后续版本的数据库，并且能在Windows，Linux和Mac OSX上运行。</p>
<p>最新版本的Oracle SQL Developer提供了PL / SQL单元测试，集成了数据模型浏览器和Subversion源代码版本控制系统，CVS（并行版本系统）此外，2.1版包括了许多更新功能，如SQL格式化，模式比较，复制、导出向导和迁移支持。</p>
<p>&nbsp;</p>
<ul>
<li>数据库逻辑设计</li>
</ul>
<p>本系统的应用场景是模拟一个企业销售其商品的过程。该企业的销售活动通过订单进行,企业员工要销售产品给客户,必须要新开一张订单,在订单中记录销售过程的关键信息。比如哪个客户购买了哪些产品,订单的经手员工是谁,何时销售的,订单的应收款是多少等等。</p>
<ul>
<li>实体模型</li>
</ul>
<p>根据应用场景分析,共有3个原始的实体 Entity),它们是部门、员工和产品部门( DEPARTMENTS):部门包括部门D( DEPARTMENT ID)和部门名称DEPARTMENT NAME),如图3-1。</p>

<img src='1.jpg'>

<p>员工 EMPLOYEES):员工包括员工 ID(EMPLOYEE ID),姓名（NAME),照片（POTO）工资 (SALARY)等。员工的属性中还应包括员工所属的部门 ID(DEPARTMENT_ID),部门ID不能为空,表示员工必须属于某一个部门。员工的属性中还有员工的上司( MANAGER_ ID)该属性可以为空,表示没有上司。员工的实体如图3-2。</p>

<img src='2.jpg'>

<p>&nbsp;</p>
<p>产品( PRODUCTS):产品包括3个属性:产品1D( PRODUCT_ID),产品名称PRODUCT_NAME)和产品类型( PRODUCT_TYPE),见图3-3</p>

<img src='3.jpg'>

<p>&nbsp;</p>
<ul>
<li>实体联系模型</li>
</ul>
<p>&nbsp;&nbsp;&nbsp;&nbsp;企业员工的工作是销售产品,因此员工和产品之间就有一个&ldquo;销售&rdquo;的联系,如图3-4所示,员工与产品之间的关系是多对多的关系,如图3-4。</p>

<img src='4.jpg'>

<p>&nbsp;&nbsp;&nbsp;&nbsp; 考虑到销售活动中有一些重要属性,比如折扣,客户信息,销售时间,产品的销售数量和销售价格,我们把销售关系细分为订单和订单详单两个实体,订单中存储:订单ID( ORDER_ID)、折扣 (DISCOUNT)、客户信息( CUSTOMER_NAME, CUSTOMER_TEL)订单时间( ORDER_DATE)以及应收货款总额( TRADE_RECEIVABLE),订单详单中存储订单详单的ID,以及订单中的全部产品信息,包括:销售数量( PRODUCT_NUM)和销售价格( PRODUCT_PRICE),见图3-5。</p>

<img src='5.jpg'>

<p>&nbsp;</p>
<ul>
<li>表结构设计</li>
</ul>
<p>&nbsp;&nbsp;&nbsp;&nbsp;E.R模型建立好以后,就可以设计 Oracle的关系表了,在独立实体中找出主要属性设置为主键,比如在产品表中,产品名称( PRODUCT_NAME)是主键。由关系派生出的实体中要加入外键关系,比如在图3-5中有两个一对多的关系,需要增加外键属性,即在订单表中增加员工D属性( EMPLOYEE_ID),在订单详单中增加产品ID属性(PRODUCT _ID)。部门表( DEPARTMENTS)包括(DEPARTMENT_ID)和(DEPARTMENT_NAME)两个属性,见表4-1。</p>

<p>表4-1</p>
<table>
<tbody>
<tr>
<td width="224">
<p><strong>字段名</strong></p>
</td>
<td width="224">
<p><strong>数据类型</strong></p>
</td>
<td width="224">
<p><strong>可以为空</strong></p>
</td>
<td width="224">
<p><strong>注释</strong></p>
</td>
</tr>
<tr>
<td width="224">
<p>DEPARTMENT_ID</p>
</td>
<td width="224">
<p>NUMBER(6,0)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>部门ID，主键</p>
</td>
</tr>
<tr>
<td width="224">
<p>DEPARTMENT_NAME</p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>部门名称，非空</p>
</td>
</tr>
</tbody>
</table>
<p>产品表 PRODUCTS包括产品DD( PRODUCT_ID)、产品名称( PRODUCT_NAME)和产品类型( PRODUCT_TYPE),见表4-2。注意产品表中的产品类型只能取值:西瓜，猕猴桃，菠萝。</p>
<p>表4_2 产品表 PRODUCTS</p>
<table>
<tbody>
<tr>
<td width="224">
<p><strong>字段名</strong></p>
</td>
<td width="224">
<p><strong>数据类型</strong></p>
</td>
<td width="224">
<p><strong>可以为空</strong></p>
</td>
<td width="224">
<p><strong>注释</strong></p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>PRODUCT_ID</strong></p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>产品ID号，产品表的主键</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>PRODUCT_NAME</strong></p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>产品名称</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>PRODUCT_TYPE</strong></p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>产品类型只能取值:西瓜，猕猴桃，菠萝</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;&nbsp;&nbsp;&nbsp;员工表 EMPLOYEES包括员工的属性,要注意（MANAGER ID）是员工的上司,是员工表(EMPOLYEE_ID)的外键, (MANAGER_ID)不能等于(EMPLOYEE_ID）,即员工的领导不能是自己。主键删除时(MANAGER_ID)设置为空值。见表5-3。订单表 ORDERS是订货信息,见表5-4.表中(TRADE_RECEIVABLE)是订单的应收货款,是从订单详单表中自动汇总过来的。计算公式是: Trade_Receivables=sum(订单详单表.Product_Num*订单详单表.Product_Price)- Discount。</p>
<p>表4_3员工表 EMPLOYEES</p>
<table>
<tbody>
<tr>
<td width="224">
<p><strong>字段名</strong></p>
</td>
<td width="224">
<p><strong>数据类型</strong></p>
</td>
<td width="173">
<p><strong>可以为空</strong></p>
</td>
<td width="274">
<p><strong>注释</strong></p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>EMPLOYEE_ID</strong></p>
</td>
<td width="224">
<p>NUMBER(6,0)</p>
</td>
<td width="173">
<p>NO</p>
</td>
<td width="274">
<p>员工ID，员工表的主键</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>NAME</strong></p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="173">
<p>NO</p>
</td>
<td width="274">
<p>员工姓名，不能为空，创建不唯一B树索引</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>EMAIL</strong></p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="173">
<p>YES</p>
</td>
<td width="274">
<p>电子信箱</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>PHONE_NUMBER</strong></p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="173">
<p>YES</p>
</td>
<td width="274">
<p>电话</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>HIRE_DATE</strong></p>
</td>
<td width="224">
<p>DATE</p>
</td>
<td width="173">
<p>NO</p>
</td>
<td width="274">
<p>雇佣日期</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>SALARY</strong></p>
</td>
<td width="224">
<p>NUMBER(8,2)</p>
</td>
<td width="173">
<p>YES</p>
</td>
<td width="274">
<p>月薪，必须大于零</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>MANAGER_ID</strong></p>
</td>
<td width="224">
<p>NUMBER(6,0)</p>
</td>
<td width="173">
<p>YES</p>
</td>
<td width="274">
<p>员工的上司，员工表EMPLOYEE_ID的外键，MANAGER_ID不能等于EMPLOYEE_ID</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>DEPARTMENT_ID</strong></p>
</td>
<td width="224">
<p>NUMBER(6,0)</p>
</td>
<td width="173">
<p>YES</p>
</td>
<td width="274">
<p>员工所在部门，是部门表DEPARTMENTS的外键</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>PHOTO</strong></p>
</td>
<td width="224">
<p>BLOB</p>
</td>
<td width="173">
<p>YES</p>
</td>
<td width="274">
<p>员工照片</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p>表 4-4 订单表ORDERS</p>
<table>
<tbody>
<tr>
<td width="224">
<p><strong>字段名</strong></p>
</td>
<td width="224">
<p><strong>数据类型</strong></p>
</td>
<td width="224">
<p><strong>可以为空</strong></p>
</td>
<td width="224">
<p><strong>注释</strong></p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>ORDER_ID</strong></p>
</td>
<td width="224">
<p>NUMBER(10,0)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>订单编号,主键。值来自于序列:SEQ_ORDER_ID</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>CUSTOMER_NAME</strong></p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>客户名称,B树索引</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>CUSTOMER_TEL</strong></p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>客户电话</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>ORDER_DATE</strong></p>
</td>
<td width="224">
<p>DATE</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>订货日期,应该采用分区存储方式</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>EMPLOYEE_ID</strong></p>
</td>
<td width="224">
<p>NUMBER(6,0)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>订单经手人，员工表EMPLOYEES的外键</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>DISCOUNT</strong></p>
</td>
<td width="224">
<p>NUMBER(8,2)</p>
</td>
<td width="224">
<p>YES</p>
</td>
<td width="224">
<p>订单整体优惠金额。默认值为0</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>Trade_Receivable</strong></p>
</td>
<td width="224">
<p>NUMBER(8,2)</p>
</td>
<td width="224">
<p>YES</p>
</td>
<td width="224">
<p>订单应收货款，默认为0</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;订单详单表（ORDER_DETAILS）包含订单中全部产品的信息,见表5-5。要注意,件系统要通过触发器将产品的金额汇总到订单表中的(TRADE_RECEIVABLE)属性。</p>
<p>表 4-5 订单详单表ORDER_DETAILS</p>
<table>
<tbody>
<tr>
<td width="224">
<p><strong>字段名</strong></p>
</td>
<td width="224">
<p><strong>数据类型</strong></p>
</td>
<td width="224">
<p><strong>可以为空</strong></p>
</td>
<td width="224">
<p><strong>注释</strong></p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>ID</strong></p>
</td>
<td width="224">
<p>NUMBER(10,0)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>本表的主键，值来自于序列：SEQ_ORDER_DETAILS_ID</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>ORDER_ID</strong></p>
</td>
<td width="224">
<p>NUMBER(10,0)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>所属的订单号，订单表ORDERS的外键</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>PRODUCT_ID</strong></p>
</td>
<td width="224">
<p>VARCHAR2(40 BYTE)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>产品ID，是产品表PRODUCTS的外键</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>PRODUCT_NUM</strong></p>
</td>
<td width="224">
<p>NUMBER(8,2)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>产品销售数量，必须大于0</p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>PRODUCT_PRICE</strong></p>
</td>
<td width="224">
<p>NUMBER(8,2)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>产品销售价格</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;&nbsp;&nbsp;&nbsp;为了使用触发器计算订单的应收货款，需要创建一个临时表ORDER_ID_TEMP，这个表的目的是暂时储存ORDER_ID。见表4-6。</p>
<p>表 4-6 订单ID临时表ORDER_ID_TEMP</p>
<table>
<tbody>
<tr>
<td width="224">
<p><strong>字段名</strong></p>
</td>
<td width="224">
<p><strong>数据类型</strong></p>
</td>
<td width="224">
<p><strong>可以为空</strong></p>
</td>
<td width="224">
<p><strong>注释</strong></p>
</td>
</tr>
<tr>
<td width="224">
<p><strong>ORDER_ID</strong></p>
</td>
<td width="224">
<p>NUMBER(10,0)</p>
</td>
<td width="224">
<p>NO</p>
</td>
<td width="224">
<p>主键</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<ul>
<li>用户创建与空间分配
<ul>
<li>创建表空间</li>
</ul>
</li>
</ul>
<p>&nbsp;&nbsp;&nbsp;&nbsp;表的结构设计好之后,还要考虑用户和空间分配问题。我们需要为系统新建一个用户( STUDY),在磁盘空间方面,考虑将数据存储在PDB上,这里选择 Oracle12c安装时默认的 PDBORCL数据库,另外,还需要为销售系统创建一个新表空间 USERS02用于存储订单记录，下面是 SYSTEM用户创建的一个表空间 USERSI02的命令,注意给 USERS02表空间分配了两个数据文件: pdbtest usen021dbf和 subtest users022dbf,这两个数据文件初始大小都是100M,所以表空间的初始大小是200M。</p>
<p>&nbsp;</p>
<p>表空间创建代码如下：</p>
<p>CREATE TABLESPACE USERS02</p>
<p>DATAFILE</p>
<p>&lsquo;/home/oracle/app/oracle/oradata/orcl/pdborcl/pdbtest_users02_1.dbf&rsquo;</p>
<p>SIZE 100M AUTOEXTEND ON NEXT 256M MAXSIZE UNLIMITED,</p>
<p>&lsquo;/home/oracle/app/oracle/oradata/orcl/pdborcl/pdbtest_users02_2.dbf&rsquo;</p>
<p>SIZE 100M AUTOEXTEND ON NEXT 256M MAXSIZE UNLIMITE</p>
<p>EXTENT MANAGEMENT LOCAL SEGMENT SPACE MANAGEMENT AUTO;</p>
<p>&nbsp;</p>
<ul>
<li>创建用户</li>
</ul>
<p>&nbsp;&nbsp;&nbsp;&nbsp;表空间 USERS02创建完成之后创建用户.我们为本系统设计的用户名称是 STUDY.用户创建之后,给用户 STUDY分配表空间 USERS和 USERS02的使用配额再分配角色 CONNECT和 RESOURCE,以便该用户可以连接数据库,可以创建资源(表,过程,序列等资源对象),最后再分配一个系统权限:&ldquo; CREATE VIEW&rdquo;,以便该用户可以创建视图。</p>
<p>创建角色并分配权限代码如下：</p>
<p>CREATE USER STUDY IDENTIFIED BY 123</p>
<p>DEFAULT TABLESPACE &ldquo;USERS&rdquo;</p>
<p>TEMPORARY TABLESPACE "TEMP&rdquo;;</p>
<p>--QUOTAS</p>
<p>ALTER USER STUDY QUOTA UNLIMITED ON USERS;</p>
<p>ALTER USER STUDY QUOTA UNLIMITED ON USERS02;</p>
<p>--ROLES</p>
<p>GRANT "CONNECT" TO STUDY WITH ADMIN OPTION;</p>
<p>GRANT "RESOURCE" TO STUDY WITH ADMIN OPTION;</p>
<p>ALTER USER STUDY DEFAULT ROLE &ldquo;CONNECT&rdquo;, &ldquo;RESOURCE&rdquo;;</p>
<p>--SYSTEM PRIVILEGES</p>
<p>GRANT CREATE VTEW TO STUDY WITH ADMIN OPTION;</p>
<p>&nbsp;</p>
<ul>
<li>存储空间的分配</li>
</ul>

结果：

<img src='j10.jpg'>

<p>&nbsp;&nbsp;&nbsp;&nbsp;到现在,我们有了两个表空间 USERS(原有的)和 USERS02(新建的)。这里我们假定企业的销售订单非常多,订单表和订单详单表的记录数量非常大,可能上千万条记录,所以我们把 ORDERS和 ORDE_DETAILS两张表设计为基于 ORDER_DATE的分区表,以加快局部时间范围的查询速度。存储空间的分配规划如表5-1所示。</p>
<p>表5-1 存储空间分配</p>
<table>
<tbody>
<tr>
<td width="298">
<p><strong>表</strong></p>
</td>
<td width="298">
<p><strong>表空间USERS</strong></p>
</td>
<td width="298">
<p><strong>表空间USERS02</strong></p>
</td>
</tr>
<tr>
<td width="298">
<p><strong>DEPARTMENTS</strong></p>
</td>
<td width="298">
<p>存储全部数据</p>
</td>
<td width="298">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="298">
<p><strong>EMPLOYEES</strong></p>
</td>
<td width="298">
<p>存储全部数据</p>
</td>
<td width="298">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="298">
<p><strong>PRODUCTS</strong></p>
</td>
<td width="298">
<p>存储全部数据</p>
</td>
<td width="298">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="298">
<p><strong>ORDERS</strong></p>
</td>
<td width="298">
<p>存储2016年之前（不含）的数据</p>
</td>
<td width="298">
<p>存储2016年之后（不含）的数据</p>
</td>
</tr>
<tr>
<td width="298">
<p><strong>ORDER_DETAILS</strong></p>
</td>
<td width="298">
<p>存储2016年之前（不含）的数据</p>
</td>
<td width="298">
<p>存储2016年之后（不含）的数据</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<ul>
<li>创建表，约束和索引</li>
</ul>
<p>本系统包括部门表，员工表，订单表，订单详单表，产品表。以订单表和订单详单表为例。ORDERS表按分区存储，分区类型选择&ldquo;RANG&rdquo;范围分区，按订单时间ORDER_DATE的范围进行分区,分区PARTITION_BEFORE_2016存储订单时间小于2016年的订单记录,这个分区存储在表空间&nbsp;USERS中,而分区PARTITION_BEFORE2021存储的是订单时间小于2021年的订单记录,由于有分区PARTITION_BEFORE_2016的存在,&nbsp;PARTITION_BEFORE_2021分区实际只存储2016 年一年的记录。</p>
<p>创建ORDERS表的部分语句如下：</p>
<p>CREATE TABLE ORDERS</p>
<p>(</p>
<p>ORDER_ID NUMBER(10, 0) NOT NULL</p>
<p>, CUSTOMER_NAME VARCHAR2(40 BYTE) NOT NULL</p>
<p>, CUSTOMER_TEL VARCHAR2(40 BYTE) NOT NULL</p>
<p>, ORDER_DATE DATE NOT NULL</p>
<p>, EMPLOYEE_ID NUMBER(6, 0) NOT NULL</p>
<p>, DISCOUNT NUMBER(8, 2) DEFAULT 0</p>
<p>, TRADE_RECEIVABLE NUMBER(8, 2) DEFAULT 0</p>
<p>, CONSTRAINT ORDERS_PK PRIMARY KEY</p>
<p>(</p>
<p>ORDER_ID</p>
<p>)</p>
<p>USING INDEX</p>
<p>(</p>
<p>CREATE UNIQUE INDEX ORDERS_PK ON ORDERS (ORDER_ID ASC)</p>
<p>LOGGING</p>
<p>TABLESPACE USERS</p>
<p>PCTFREE 10</p>
<p>INITRANS 2</p>
<p>STORAGE</p>
<p>(</p>
<p>BUFFER_POOL DEFAULT</p>
<p>)</p>
<p>NOPARALLEL</p>
<p>)</p>
<p>ENABLE</p>
<p>)</p>
<p>TABLESPACE USERS</p>
<p>PCTFREE 10</p>
<p>INITRANS 1</p>
<p>STORAGE</p>
<p>(</p>
<p>BUFFER_POOL DEFAULT</p>
<p>)</p>
<p>NOCOMPRESS</p>
<p>NOPARALLEL</p>
<p>PARTITION BY RANGE (ORDER_DATE)</p>
<p>(</p>
<p>PARTITION PARTITION_2015 VALUES LESS THAN (TO_DATE(' 2016-01-01 00:00:00', 'SYYYY-MM-DD HH24:MI:SS', 'NLS_CALENDAR=GREGORIAN'))</p>
<p>NOLOGGING</p>
<p>TABLESPACE USERS</p>
<p>PCTFREE 10</p>
<p>INITRANS 1</p>
<p>STORAGE</p>
<p>(</p>
<p>INITIAL 8388608</p>
<p>NEXT 1048576</p>
<p>MINEXTENTS 1</p>
<p>MAXEXTENTS UNLIMITED</p>
<p>BUFFER_POOL DEFAULT</p>
<p>)</p>
<p>NOCOMPRESS NO INMEMORY</p>
<p>, PARTITION PARTITION_2016 VALUES LESS THAN (TO_DATE(' 2021-01-01 00:00:00', 'SYYYY-MM-DD HH24:MI:SS', 'NLS_CALENDAR=GREGORIAN'))</p>
<p>NOLOGGING</p>
<p>TABLESPACE USERS02</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;ORDER_DETAILS是 ORDERS的从表, ORDER_DETAILS的记录数量比ORDERS还多,所以 ORDER_DETAILS表也必须分区存储,但由于 ORDER_DETAILS表中没有订单时间,所以不能按时间分区进行存储。ORDER_DETAILS使用引用分区进行存储。</p>
<p>创建 ORDER_DETAILS表的部分语句如下：</p>
<p>CREATE TABLE order_details (id NUMBER(10, 0) NOT NULL , order_id NUMBER(10, 0) NOT NULL, product_id VARCHAR2(40 BYTE) NOT NULL , product_num NUMBER(8, 2) NOT NULL , product_price NUMBER(8, 2) NOT NULL , CONSTRAINT order_details_fk1 FOREIGN KEY&nbsp; (order_id)REFERENCES orders&nbsp; (&nbsp; order_id&nbsp;&nbsp; )ENABLE ) TABLESPACE USERS PCTFREE 10 INITRANS 1 STORAGE (&nbsp;&nbsp; BUFFER_POOL DEFAULT ) NOCOMPRESS NOPARALLELPARTITION BY REFERENCE (order_details_fk1)(PARTITION PARTITION_BEFORE_2016 NOLOGGING TABLESPACE USERS --必须指定表空间,否则会将分区存储在用户的默认表空间中...) NOCOMPRESS NO INMEMORY, PARTITION PARTITION_BEFORE_2021 NOLOGGING TABLESPACE USERS02...) NOCOMPRESS NO INMEMORY&nbsp; );</p>
<p>创建全局临时表ORDER_ID_TEMP的语句如下：</p>
<p>-- DDL for Table ORDER_ID_TEMP</p>
<p>CREATE GLOBAL TEMPORARY TABLE "ORDER_ID_TEMP"</p>
<p>( "ORDER_ID" NUMBER(10,0) NOT NULL ENABLE,</p>
<p>CONSTRAINT "ORDER_ID_TEMP_PK" PRIMARY KEY ("ORDER_ID") ENABLE</p>
<p>) ON COMMIT DELETE ROWS ;</p>
<p>COMMENT ON TABLE "ORDER_ID_TEMP" IS '用于触发器存储临时ORDER_ID';</p>
<p>结果见图 6-1：</p>
<img src='6.jpg'>

<ul>
<li>创建触发器，序列和视图
<ul>
<li>创建触发器</li>
</ul>
</li>
</ul>
<p>本销售系统中订单表ORDERS的TRADE_RECEIVABLE是应收货款,是自动计算字的计算公式是Trade_Receivable=sum(ORDER_DETAILS.Product_Num*ORDER_DETAILS.Produet_ pice)-Discount。从这个公式可以看出,当修改订单表的折扣&nbsp;Discount或者对订单详单表&nbsp;ORDER_DETAILS作任何增加,修改,删除的操作后,都可能需要重新计算Trade_Receivable。所以我们设计了以下3个触发器来实现这个功能,完整的触发器代码如下：</p>
<p>-- DDL for Trigger ORDERS_TRIG_ROW_LEVEL</p>

<p>--------------------------------------------------------</p>
<p>CREATE OR REPLACE EDITIONABLE TRIGGER "ORDERS_TRIG_ROW_LEVEL"</p>
<p>BEFORE INSERT OR UPDATE OF DISCOUNT ON "ORDERS"</p>
<p>FOR EACH ROW --行级触发器</p>
<p>declare</p>
<p>m number(8,2);</p>
<p>BEGIN</p>
<p>if inserting then</p>
<p>:new.TRADE_RECEIVABLE := - :new.discount;</p>
<p>else</p>
<p>select sum(PRODUCT_NUM*PRODUCT_PRICE) into m from ORDER_DETAILS where ORDER_ID=:old.ORDER_ID;</p>
<p>if m is null then</p>
<p>m:=0;</p>
<p>end if;</p>
<p>:new.TRADE_RECEIVABLE := m - :new.discount;</p>
<p>end if;</p>
<p>END;</p>
<p>/</p>
<p>--批量插入订单数据之前，禁用触发器</p>
<p>ALTER TRIGGER "ORDERS_TRIG_ROW_LEVEL" DISABLE;</p>
<p>--------------------------------------------------------</p>
<p>-- DDL for Trigger ORDER_DETAILS_ROW_TRIG</p>
<p>--------------------------------------------------------</p>
<p>CREATE OR REPLACE EDITIONABLE TRIGGER "ORDER_DETAILS_ROW_TRIG"</p>
<p>AFTER DELETE OR INSERT OR UPDATE ON ORDER_DETAILS</p>
<p>FOR EACH ROW</p>
<p>BEGIN</p>
<p>--DBMS_OUTPUT.PUT_LINE(:NEW.ORDER_ID);</p>
<p>IF :NEW.ORDER_ID IS NOT NULL THEN</p>
<p>MERGE INTO ORDER_ID_TEMP A</p>
<p>USING (SELECT 1 FROM DUAL) B</p>
<p>ON (A.ORDER_ID=:NEW.ORDER_ID)</p>
<p>WHEN NOT MATCHED THEN</p>
<p>INSERT (ORDER_ID) VALUES(:NEW.ORDER_ID);</p>
<p>END IF;</p>
<p>IF :OLD.ORDER_ID IS NOT NULL THEN</p>
<p>MERGE INTO ORDER_ID_TEMP A</p>
<p>USING (SELECT 1 FROM DUAL) B</p>
<p>ON (A.ORDER_ID=:OLD.ORDER_ID)</p>
<p>WHEN NOT MATCHED THEN</p>
<p>INSERT (ORDER_ID) VALUES(:OLD.ORDER_ID);</p>
<p>END IF;</p>
<p>END;</p>
<p>/</p>
<p>ALTER TRIGGER "ORDER_DETAILS_ROW_TRIG" DISABLE;</p>
<p>--------------------------------------------------------</p>
<p>-- DDL for Trigger ORDER_DETAILS_SNTNS_TRIG</p>
<p>--------------------------------------------------------</p>
<p>CREATE OR REPLACE EDITIONABLE TRIGGER "ORDER_DETAILS_SNTNS_TRIG"</p>
<p>AFTER DELETE OR INSERT OR UPDATE ON ORDER_DETAILS</p>
<p>declare</p>
<p>m number(8,2);</p>
<p>BEGIN</p>
<p>FOR R IN (SELECT ORDER_ID FROM ORDER_ID_TEMP)</p>
<p>LOOP</p>
<p>--DBMS_OUTPUT.PUT_LINE(R.ORDER_ID);</p>
<p>select sum(PRODUCT_NUM*PRODUCT_PRICE) into m from ORDER_DETAILS</p>
<p>where ORDER_ID=R.ORDER_ID;</p>
<p>if m is null then</p>
<p>m:=0;</p>
<p>end if;</p>
<p>UPDATE ORDERS SET TRADE_RECEIVABLE = m - discount</p>
<p>WHERE ORDER_ID=R.ORDER_ID;</p>
<p>END LOOP;</p>
<p>END;</p>
<p>结果见图 7-1：</p>
<img src='7.jpg'>

<ul>
<li>创建序列</li>
</ul>
<p>&nbsp;&nbsp;&nbsp;&nbsp;在插入订单数据的时候，需要用到自增的ID，所以需要设计两个序列SEQ_ORDER_ID用于给ORDER表的ORDER_ID赋值，SEQ_ORDER_ID用于给ORDER_DETAILS表的ORDER_DETAILS _ID赋值。</p>
<p>创建序列的语句如下：</p>
<p>-- DDL for Sequence SEQ_ORDER_ID</p>
<p>--------------------------------------------------------</p>
<p>CREATE SEQUENCE "SEQ_ORDER_ID" MINVALUE 1 MAXVALUE 9999999999 INCREMENT BY 1 START WITH 1 CACHE 2000 ORDER NOCYCLE NOPARTITION ;</p>
<p>--------------------------------------------------------</p>
<p>-- DDL for Sequence SEQ_ORDER_DETAILS_ID</p>
<p>--------------------------------------------------------</p>
<p>CREATE SEQUENCE "SEQ_ORDER_DETAILS_ID" MINVALUE 1 MAXVALUE 9999999999 INCREMENT BY 1 START WITH 1 CACHE 2000 ORDER NOCYCLE NOPARTITION ;</p>
<p>结果见 图 7-2：</p>
<img src='8.jpg'>

<ul>
<li>创建视图</li>
</ul>
<p>&nbsp;&nbsp;&nbsp;&nbsp;为了方便的查询订单详单中的产品，需要设计一个视图VIEW_ORDER_DETAILS</p>
<p>创建视图VIEW_ORDER_DETAILS的语句如下：</p>
<p>-- DDL for View VIEW_ORDER_DETAILS</p>
<p>--------------------------------------------------------</p>
<p>CREATE OR REPLACE FORCE EDITIONABLE VIEW "VIEW_ORDER_DETAILS" ("ID", "ORDER_ID", "CUSTOMER_NAME", "CUSTOMER_TEL", "ORDER_DATE", "PRODUCT_TYPE", "PRODUCT_NAME", "PRODUCT_NUM", "PRODUCT_PRICE") AS</p>
<p>SELECT</p>
<p>d.ID,</p>
<p>o.ORDER_ID,</p>
<p>o.CUSTOMER_NAME,o.CUSTOMER_TEL,o.ORDER_DATE,</p>
<p>p.PRODUCT_TYPE,</p>
<p>d.PRODUCT_NAME,</p>
<p>d.PRODUCT_NUM,</p>
<p>d.PRODUCT_PRICE</p>
<p>FROM ORDERS o,ORDER_DETAILS d,PRODUCTS p where d.ORDER_ID=o.ORDER_ID and d.PRODUCT_NAME=p.PRODUCT_NAME;</p>
<p>/</p>
<p>结果见 图 7-3：</p>
<img src='9.jpg'>

<ul>
<li>创建程序包，函数和过程</li>
</ul>
<p>&nbsp;&nbsp;&nbsp;&nbsp;本系统设计了一些函数和过程,放在程序包 MyPack中, Get_SaleAmount（）函数的作用是计算并返回一个部门的销售总金额。Get_Employees过程的作用是打印出某个员工的所有下属,含下属的下属, GET EMPLOYEEBYPAGE PO过程的作用是分页查询员工表,返回游标变量. Calc_All_TradeReceivable()过程的作用是更新订单表中每个订单的应收款。代码分为包头和包体两部分。</p>
<p>包头如下：</p>
<p>create or replace PACKAGE MyPack IS</p>
<p>FUNCTION Get_SaleAmount(V_DEPARTMENT_ID NUMBER) RETURN NUMBER;</p>
<p>PROCEDURE Get_Employees(V_EMPLOYEE_ID NUMBER);</p>
<p>END MyPack;</p>
<p>/</p>

<p>包体如下：</p>

<p>create or replace PACKAGE BODY MyPack IS</p>
<p>FUNCTION Get_SaleAmount(V_DEPARTMENT_ID NUMBER) RETURN NUMBER</p>
<p>AS</p>
<p>N NUMBER(20,2); --注意，订单ORDERS.TRADE_RECEIVABLE的类型是NUMBER(8,2),汇总之后，数据要大得多。</p>
<p>BEGIN</p>
<p>SELECT SUM(O.TRADE_RECEIVABLE) into N FROM ORDERS O,EMPLOYEES E</p>
<p>WHERE O.EMPLOYEE_ID=E.EMPLOYEE_ID AND E.DEPARTMENT_ID =V_DEPARTMENT_ID;</p>
<p>RETURN N;</p>
<p>END;</p>
</td>
</tr>
<tr>
<td>&nbsp;</td>
<p>PROCEDURE GET_EMPLOYEES(V_EMPLOYEE_ID NUMBER)</p>
<p>AS</p>
<p>LEFTSPACE VARCHAR(2000);</p>
<p>begin</p>
<p>--通过LEVEL判断递归的级别</p>
<p>LEFTSPACE:=' ';</p>
<p>--使用游标</p>
<p>for v in</p>
<p>(SELECT LEVEL,EMPLOYEE_ID,NAME,MANAGER_ID FROM employees</p>
<p>START WITH EMPLOYEE_ID = V_EMPLOYEE_ID</p>
<p>CONNECT BY PRIOR EMPLOYEE_ID = MANAGER_ID)</p>
<p>LOOP</p>
<p>DBMS_OUTPUT.PUT_LINE(LPAD(LEFTSPACE,(V.LEVEL-1)*4,' ')||</p>
<p>V.EMPLOYEE_ID||' '||v.NAME);</p>
<p>END LOOP;</p>
<p>END;</p>
<p>END MyPack;</p>
<p>/</p>
<p>结果见 图 8-1</p>
<img src='10jpg.jpg'>

<ul>
<li>数据库测试
<ul>
<li>向表中插入数据</li>
</ul>
</li>
</ul>
<p>&nbsp;&nbsp;&nbsp;&nbsp;以批量插入订单数据为例，其他表的数据插入语句省略，其中ORDERS.TRADE_RECEIVABLE（订单应收款）自动计算,语句如下：</p>

<p>declare</p>
<p>dt date;</p>
<p>m number(8,2);</p>
<p>V_EMPLOYEE_ID NUMBER(6);</p>
<p>v_order_id number(10);</p>
<p>v_name varchar2(100);</p>
<p>v_tel varchar2(100);</p>
<p>v_number(10,2);</p>
<p>begin</p>
<p>for i in 1..50000</p>
<p>loop</p>
<p>if i mod 2 =0 then</p>
<p>dt:=to_date('2015-3-2','yyyy-mm-dd')+(i mod 60);</p>
<p>else</p>
<p>dt:=to_date('2016-3-2','yyyy-mm-dd')+(i mod 60);</p>
<p>end if;</p>
<p>V_EMPLOYEE_ID:=CASE I MOD 6 WHEN 0 THEN 11 WHEN 1 THEN 111 WHEN 2 THEN 112</p>
<p>WHEN 3 THEN 12 WHEN 4 THEN 121 ELSE 122 END;</p>
<p>--插入订单</p>
<p>v_order_id:=SEQ_ORDER_ID.nextval; --应该将SEQ_ORDER_ID.nextval保存到变量中。</p>
<p>v_name := 'aa'|| 'aa';</p>
<p>v_name := 'zhang' || i;</p>
<p>v_tel := '139888883' || i;</p>
<p>insert /*+append*/ into ORDERS (ORDER_ID,CUSTOMER_NAME,CUSTOMER_TEL,ORDER_DATE,EMPLOYEE_ID,DISCOUNT)</p>
<p>values (v_order_id,v_name,v_tel,dt,V_EMPLOYEE_ID,dbms_random.value(100,0));</p>
<p>--插入订单y一个订单包括3个产品</p>
<p>v:=dbms_random.value(10000,4000);</p>
<p>v_name:='computer'|| (i mod 3 + 1);</p>
<p>insert /*+append*/ into ORDER_DETAILS(ID,ORDER_ID,PRODUCT_NAME,PRODUCT_NUM,PRODUCT_PRICE)</p>
<p>values (SEQ_ORDER_DETAILS_ID.NEXTVAL,v_order_id,v_name,2,v);</p>
<p>v:=dbms_random.value(1000,50);</p>
<p>v_name:='paper'|| (i mod 3 + 1);</p>
<p>insert /*+append*/ into ORDER_DETAILS(ID,ORDER_ID,PRODUCT_NAME,PRODUCT_NUM,PRODUCT_PRICE)</p>
<p>values (SEQ_ORDER_DETAILS_ID.NEXTVAL,v_order_id,v_name,3,v);</p>
<p>v:=dbms_random.value(9000,2000);</p>
<p>v_name:='phone'|| (i mod 3 + 1);</p>
<p>insert /*+append*/ into ORDER_DETAILS(ID,ORDER_ID,PRODUCT_NAME,PRODUCT_NUM,PRODUCT_PRICE)</p>
<p>values (SEQ_ORDER_DETAILS_ID.NEXTVAL,v_order_id,v_name,1,v);</p>
<p>--在触发器关闭的情况下，需要手工计算每个订单的应收金额：</p>
<p>select sum(PRODUCT_NUM*PRODUCT_PRICE) into m from ORDER_DETAILS where ORDER_ID=v_order_id;</p>
<p>if m is null then</p>
<p>m:=0;</p>
<p>end if;</p>
<p>UPDATE ORDERS SET TRADE_RECEIVABLE = m - discount WHERE ORDER_ID=v_order_id;</p>
<p>IF I MOD 1000 =0 THEN</p>
<p>commit; --每次提交会加快插入数据的速度</p>
<p>END IF;</p>
<p>end loop;</p>
<p>结果见图 9-1</p>
<img src='11.jpg'>

<ul>
<li>调用程序包中的函数</li>
</ul>
<p>调用MyPack.Get_SaleAmount()函数，计算部门11的销售总金额，语句如下：</p>
<p>select count(*) from orders;</p>
<p>select MyPack.Get_SaleAmount(11) AS 部门11应收金额,MyPack.Get_SaleAmount(12) AS 部门12应收金额 from dual;</p>
<p>结果如图 9-2：</p>
<img src='12.jpg'>

<ul>
<li>调用程序包中的过程</li>
</ul>
<p>&nbsp;&nbsp;&nbsp;&nbsp;在Sql developer 中调用MYPACK.Get_Employees()过程，输出1号员工所有下属及子下属，语句如下：</p>
<p>set serveroutput on</p>
<p>DECLARE</p>
<p>V_EMPLOYEE_ID NUMBER;</p>
<p>BEGIN</p>
<p>V_EMPLOYEE_ID := 1;</p>
<p>MYPACK.Get_Employees ( V_EMPLOYEE_ID =&gt; V_EMPLOYEE_ID) ;</p>
<p>V_EMPLOYEE_ID := 11;</p>
<p>MYPACK.Get_Employees ( V_EMPLOYEE_ID =&gt; V_EMPLOYEE_ID) ;</p>
<p>END;</p>
<p>/</p>
<p>结果见图9-3</p>
<img src='13.jpg'>
<p>图9-3</p>
<ul>
<li>自动联机备份方案设计</li>
</ul>
<p>每周7天为一个循环,每天23点钟都作一个备份:每周日23点钟作一次针对整个数据库的0级完整备份,每周的其余6天(周一到周六)每天都作一次1级增量备份,每次备份之后都要清除过期和失效的备份和归档日志。</p>
<p>先创建一个用存储备份文件和日志的目录: home/oracle/man_backup,然后新建两个shell文件: /home/oracle/rman_leve0.sh和 /home/oracle/man_levell.sh. rman_level0. sh是0级备份的脚本文件, rman_levell.sh是一级备份的脚本文件。要保证这两个文件可执行</p>
<p>rman_level0.sh内容如下:</p>
<p>#rman_level0.sh</p>
<p>#!/bin/sh</p>
<p>export NLS_LANG=&rsquo;SIMPLIFIED CHINESE_CHINA. AL32UTF8&rsquo;</p>
<p>export ORACLE_HOME=/home/oracle/app/oracle/product /12. 1.0/dbhome_1</p>
<p>export ORACLE_SID=orcl</p>
<p>export $PATH=SORACLE HOME/bin: $PATH</p>
<p>rman target/ nocatalog msglog=/home/oracle/rman_backup/lvo0_date+%Y%m%d-%H%M%S~_L0.log&lt;&lt;EOF</p>
<p>run{</p>
<p>configure retention policy to redundancy 1;</p>
<p>configure controlfile autobackup on;</p>
<p>configure controlfile autobackup format for device type disk to</p>
<p>&lsquo;/home/oracle/rman_backup/%F&rsquo;;</p>
<p>configure &nbsp;default device type to disk;</p>
<p>crosscheck archivelog all;</p>
<p>allocate channel cl device type disk;</p>
<p>backup as compressed backupset incremental level 0 database format</p>
<p>&lsquo;/home /oracle/rman_backup/dblv0_%d_%T_ %U. bak&rsquo;</p>
<p>Plus archivelog format /home /oracle/rman_backup/dblv0_%d_%T_ %U. bak&rsquo;;</p>
<p>Report obsolete;</p>
<p>delete noprompt obsolete;</p>
<p>delete noprompt expired backup;</p>
<p>delete noprompt expired archivelog all;</p>
<p>release channel c1;</p>
<p>}</p>
<p>EOF</p>
<p>exit</p>
<p>&nbsp;</p>
<p>rman_level1.sh内容如下:</p>
<p>&nbsp;</p>
<p>#rman_level1.sh</p>
<p>#!/bin/sh</p>
<p>export NLS_LANG=&rsquo;SIMPLIFIED CHINESE_CHINA. AL32UTF8&rsquo;</p>
<p>export ORACLE_HOME=/home/oracle/app/oracle/product /12. 1.0/dbhome_1</p>
<p>export ORACLE_SID=orcl</p>
<p>export $PATH=SORACLE HOME/bin: $PATH</p>
<p>rman target/ nocatalog msglog=/home/oracle/rman_backup/lvo0_date+%Y%m%d-%H%M%S~_L0.log&lt;&lt;EOF</p>
<p>run{</p>
<p>configure retention policy to redundancy 1;</p>
<p>configure controlfile autobackup on;</p>
<p>configure controlfile autobackup format for device type disk to</p>
<p>&lsquo;/home/oracle/rman_backup/%F&rsquo;;</p>
<p>configure &nbsp;default device type to disk;</p>
<p>crosscheck archivelog all;</p>
<p>allocate channel cl device type disk;</p>
<p>backup as compressed backupset incremental level 1 database format</p>
<p>&lsquo;/home /oracle/rman_backup/dblv1_%d_%T_ %U. bak&rsquo;</p>
<p>Plus archivelog format /home /oracle/rman_backup/dblv1_%d_%T_ %U. bak&rsquo;;</p>
<p>Report obsolete;</p>
<p>delete noprompt obsolete;</p>
<p>delete noprompt expired backup;</p>
<p>delete noprompt expired archivelog all;</p>
<p>release channel c1;</p>
<p>}</p>
<p>EOF</p>
<p>Exit</p>
<p>&nbsp;</p>
<p>下面通过linux的crontab命令创建自动执行脚本文件的调度：</p>

<img src='14.jpg'>


<ul>
<li>容灭方案设计</li>
</ul>
<p>主机设置如下：</p>
<p>在备库oracle用户创建归档目录，数据目录并设置权限</p>
<p>mkdir -p /home/oracle/app/oracle/diag/orcl</p>
<p>mkdir -p /home/oracle/app/oracle/oradata/stdorcl/</p>
<p>mkdir -p /home/oracle/app/oracle/oradata/stdorcl/pdborcl</p>
<p>mkdir -p /home/oracle/arch</p>
<p>mkdir -p /home/oracle/rman</p>
<p>mkdir -p /home/oracle/app/oracle/oradata/stdorcl/pdbseed/</p>
<p>mkdir -p /home/oracle/app/oracle/oradata/stdorcl/pdb/</p>
<p>删除原有数据库:</p>
<p>$sqlplus / as sysdba</p>
<p>shutdown immediate;</p>
<p>startup mount exclusive restrict;</p>
<p>drop database;</p>
<p>启动到nomount</p>
<p>$sqlplus / as sysdba</p>
<p>startup nomount</p>
<p>$sqlplus /&nbsp; sysdba</p>
<p>select group#,thread#,members,status from v$log;</p>
<p>增加standbylogfile：</p>
<p>&nbsp;</p>
<p>alter database add standby logfile&nbsp; group 5 '/home/oracle/app/oracle/oradata/orcl/stdredo1.log' size 50m;</p>
<p>alter database add standby logfile&nbsp; group 6 '/home/oracle/app/oracle/oradata/orcl/stdredo2.log' size 50m;</p>
<p>alter database add standby logfile&nbsp; group 7 '/home/oracle/app/oracle/oradata/orcl/stdredo3.log' size 50m;</p>
<p>alter database add standby logfile&nbsp; group 8 '/home/oracle/app/oracle/oradata/orcl/stdredo4.log' size 50m;</p>
<p>主库环境开启强制归档</p>
<p>ALTER DATABASE FORCE LOGGING;</p>
<p>&nbsp;</p>
<p>alter system set LOG_ARCHIVE_CONFIG='DG_CONFIG=(orcl,stdorcl)' scope=both sid='*';&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p>
<p>alter system set log_archive_dest_1='LOCATION=/home/oracle/arch VALID_FOR=(ALL_LOGFILES,ALL_ROLES) DB_UNIQUE_NAME=orcl' scope=spfile;</p>
<p>alter system set LOG_ARCHIVE_DEST_2='SERVICE=stdorcl LGWR ASYNC&nbsp; VALID_FOR=(ONLINE_LOGFILES,PRIMARY_ROLE) DB_UNIQUE_NAME=stdorcl' scope=both sid='*';</p>
<p>alter system set fal_client='orcl' scope=both sid='*';&nbsp;&nbsp;&nbsp;</p>
<p>alter system set FAL_SERVER='stdorcl' scope=both sid='*';&nbsp;</p>
<p>alter system set standby_file_management=AUTO scope=both sid='*';</p>
<p>alter system set DB_FILE_NAME_CONVERT='/home/oracle/app/oracle/oradata/stdorcl/','/home/oracle/app/oracle/oradata/orcl/' scope=spfile sid='*';&nbsp;</p>
<p>alter system set LOG_FILE_NAME_CONVERT='/home/oracle/app/oracle/oradata/stdorcl/','/home/oracle/app/oracle/oradata/orcl/' scope=spfile sid='*';</p>
<p>alter system set log_archive_format='%t_%s_%r.arc' scope=spfile sid='*';</p>
<p>alter system set remote_login_passwordfile='EXCLUSIVE' scope=spfile;</p>
<p>alter system set PARALLEL_EXECUTION_MESSAGE_SIZE=8192 scope=spfile;</p>
<p>编辑主库以及备库的/home/oracle/app/oracle/product/12.1.0/dbhome_1/network/admin/tnsnames.ora文件</p>
<p>$gedit /home/oracle/app/oracle/product/12.1.0/dbhome_1/network/admin/tnsnames.ora</p>
<p>&nbsp;</p>
<p>ORCL =</p>
<p>&nbsp; (DESCRIPTION =</p>
<p>&nbsp;&nbsp;&nbsp; (ADDRESS_LIST =</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (ADDRESS = (PROTOCOL = TCP)(HOST = 192.168.206.131)(PORT = 1521))</p>
<p>&nbsp;&nbsp;&nbsp; )</p>
<p>&nbsp;&nbsp;&nbsp; (CONNECT_DATA =</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (SERVER = DEDICATED)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (SERVICE_NAME = orcl)</p>
<p>&nbsp;&nbsp;&nbsp; )</p>
<p>&nbsp; )</p>
<p>&nbsp;</p>
<p>stdorcl =</p>
<p>&nbsp; (DESCRIPTION =</p>
<p>&nbsp;&nbsp;&nbsp; (ADDRESS = (PROTOCOL = TCP)(HOST = 192.168.206.132)(PORT = 1521))</p>
<p>&nbsp;&nbsp;&nbsp; (CONNECT_DATA =</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (SERVER = DEDICATED)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (SID = orcl)</p>
<p>&nbsp;&nbsp;&nbsp; )</p>
<p>&nbsp; )</p>
<p>在主库上生成备库的参数文件:</p>
<p>SQL&gt;create pfile from spfile;</p>
<p>生成/home/oracle/app/oracle/product/12.1.0/dbhome_1/dbs/initorcl.ora</p>
<p>将主库的参数文件，密码文件拷贝到备库:</p>
<p>scp /home/oracle/app/oracle/product/12.1.0/dbhome_1/dbs/initorcl.ora 192.168.206.132:/home/oracle/app/oracle/product/12.1.0/dbhome_1/dbs/</p>
<p>scp /home/oracle/app/oracle/product/12.1.0/dbhome_1/dbs/orapworcl 192.168.206.132:/home/oracle/app/oracle/product/12.1.0/dbhome_1/dbs/</p>
<p>将主库复制到备库</p>
<p>$rman target sys/123@orcl auxiliary sys/123@stdorcl</p>
<p>执行duplicate:</p>
<p>run{</p>
<p>allocate channel c1 type disk;</p>
<p>allocate channel c2 type disk;</p>
<p>allocate channel c3 type disk;</p>
<p>allocate AUXILIARY channel c4 type disk;</p>
<p>allocate AUXILIARY channel c5 type disk;</p>
<p>allocate AUXILIARY channel c6 type disk;</p>
<p>DUPLICATE TARGET DATABASE</p>
<p>&nbsp; FOR STANDBY</p>
<p>&nbsp; FROM ACTIVE DATABASE</p>
<p>&nbsp; DORECOVER</p>
<p>&nbsp; NOFILENAMECHECK;</p>
<p>release channel c1;</p>
<p>release channel c2;</p>
<p>release channel c3;</p>
<p>release channel c4;</p>
<p>release channel c5;</p>
<p>release channel c6;</p>
<p>}</p>
<p>在备库上更改参数文件</p>
<p>$gedit /home/oracle/app/oracle/product/12.1.0/dbhome_1/dbs/initorcl.ora</p>
<p>文件内容是：</p>
<p>orcl.__data_transfer_cache_size=0</p>
<p>orcl.__db_cache_size=671088640</p>
<p>orcl.__java_pool_size=16777216</p>
<p>orcl.__large_pool_size=33554432</p>
<p>orcl.__oracle_base='/home/oracle/app/oracle'#ORACLE_BASE set from environment</p>
<p>orcl.__pga_aggregate_target=536870912</p>
<p>orcl.__sga_target=1258291200</p>
<p>orcl.__shared_io_pool_size=50331648</p>
<p>orcl.__shared_pool_size=301989888</p>
<p>orcl.__streams_pool_size=0</p>
<p>*._allow_resetlogs_corruption=TRUE</p>
<p>*._catalog_foreign_restore=FALSE</p>
<p>*.audit_file_dest='/home/oracle/app/oracle/admin/orcl/adump'</p>
<p>*.audit_trail='db'</p>
<p>*.compatible='12.1.0.2.0'</p>
<p>*.control_files='/home/oracle/app/oracle/oradata/orcl/control01.ctl','/home/oracle/app/oracle/fast_recovery_area/orcl/control02.ctl','/home/oracle/app/oracle/fast_recovery_area/orcl/control03.ctl'</p>
<p>*.db_block_size=8192</p>
<p>*.db_domain=''</p>
<p>*.db_file_name_convert='/home/oracle/app/oracle/oradata/orcl/','/home/oracle/app/oracle/oradata/stdorcl/'</p>
<p>*.db_name='orcl'</p>
<p>*.db_unique_name='stdorcl'</p>
<p>*.db_recovery_file_dest='/home/oracle/app/oracle/fast_recovery_area'</p>
<p>*.db_recovery_file_dest_size=4823449600</p>
<p>*.diagnostic_dest='/home/oracle/app/oracle'</p>
<p>*.dispatchers='(PROTOCOL=TCP)(dispatchers=1)(pool=on)(ticks=1)(connections=500)(sessions=1000)'</p>
<p>*.enable_pluggable_database=true</p>
<p>*.fal_client='stdorcl'</p>
<p>*.fal_server='orcl'</p>
<p>*.inmemory_max_populate_servers=2</p>
<p>*.inmemory_size=157286400</p>
<p>*.local_listener=''</p>
<p>*.log_archive_config='DG_CONFIG=(stdorcl,orcl)'</p>
<p>*.log_archive_dest_1='LOCATION=/home/oracle/arch VALID_FOR=(ALL_LOGFILES,ALL_ROLES) DB_UNIQUE_NAME=stdorcl'</p>
<p>*.log_archive_dest_2='SERVICE=orcl LGWR ASYNC&nbsp; VALID_FOR=(ONLINE_LOGFILES,PRIMARY_ROLE) DB_UNIQUE_NAME=orcl'</p>
<p>*.log_archive_format='%t_%s_%r.arc'</p>
<p>*.log_file_name_convert='/home/oracle/app/oracle/oradata/orcl/','/home/oracle/app/oracle/oradata/stdorcl/'</p>
<p>*.max_dispatchers=5</p>
<p>*.max_shared_servers=20</p>
<p>*.open_cursors=400</p>
<p>*.parallel_execution_message_size=8192</p>
<p>*.pga_aggregate_target=511m</p>
<p>*.processes=300</p>
<p>*.recovery_parallelism=0</p>
<p>*.remote_login_passwordfile='EXCLUSIVE'</p>
<p>*.service_names='ORCL'</p>
<p>*.sga_max_size=1572864000</p>
<p>*.sga_target=1258291200</p>
<p>*.shared_server_sessions=200</p>
<p>*.standby_file_management='AUTO'</p>
<p>*.undo_tablespace='UNDOTBS1'</p>
<p>在备库增加静态监听</p>
<p>$gedit /home/oracle/app/oracle/product/12.1.0/dbhome_1/network/admin/listener.ora</p>
<p>SID_LIST_LISTENER =</p>
<p>&nbsp; (SID_LIST =</p>
<p>&nbsp;&nbsp;&nbsp; (SID_DESC =</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (ORACLE_HOME = /home/oracle/app/oracle/product/12.1.0/db_1)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (SID_NAME = orcl)</p>
<p>&nbsp;&nbsp;&nbsp; )</p>
<p>&nbsp; )</p>
<p>重新启动,备库开启实时应用模式:：</p>
<p>$sqlplus / as sysdba</p>
<p>shutdown immediate</p>
<p>startup</p>
<p>alter database recover managed standby database disconnect;</p>
<p>可以把语句alter database recover managed standby database disconnect;放到触发器中去，开机启动：</p>
<p>在主库修改数据，在备库查询修改。 Select Name,Sequence#,applied,completion_time From v$archived_log Order By Sequence# Desc;</p>
<p>&nbsp;</p>
<ul>
<li>总结</li>
</ul>
<p>该水果销售系统的数据库设计包括表设计，用户管理，PL/SQL设计，备份方案设计以及容灭方案设计，难度逐渐增加，同时也将本学期所学的oracle的知识点全部串接起来了，将它们一起运用便完成了一个数据库系统设计。将理论与实际结合了起来，不仅让我明白了可以干什么，还让我知道了该怎么去用。不是学习了轻飘飘了理论知识，而是学习了如何掌握使用这些技能。</p>
