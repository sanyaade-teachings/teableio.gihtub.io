# 表格

每个数据库可以包含多张表格。表格是一种结构化数据存储方式，用于存储数据库内相关数据的集合。 &#x20;

每个表格通常会包含多个行和列，其中每一列代表一个字段及其属性，而每一行代表一个记录或数据项。表格是数据库的核心组成部分，用于收集、存储和处理数据以便后续的检索、操作和构建数据库。

Teable的表格等同于数据库中表的概念，这个概念有助于理解[Teable和传统电子表格之间的差异](../../heng-xiang-dui-bi/teable-shu-ju-biao-he-dian-zi-biao-ge-de-cha-yi.md)，以便更好地掌握Teable。

### 添加表格

1. 进入特定数据库
2. 点击目录中的+号按钮

<figure><img src="../../.gitbook/assets/image (13) (1).png" alt="" width="320"><figcaption></figcaption></figure>

你可以选择

1. 创建一个新表格
2. 从  Csv 文件中导入表格
3. 从 Excel 文件中导入表格

具体导入过程可查看[导入章节](dao-ru.md)

### 修改表格名称

1. 在应用中，双击目录中表格名称
2. 修改表格名称
3. 点击输入框外任意区域

<figure><img src="../../.gitbook/assets/image (14) (1).png" alt="" width="317"><figcaption></figcaption></figure>

### 删除表格

1. 数据悬浮在目录中的表格上，点击「…」按钮打开菜单
2. 点击菜单中的删除按钮

<figure><img src="../../.gitbook/assets/image (15) (1).png" alt="" width="315"><figcaption></figcaption></figure>



### 回收站

点击数据库左上方回收站按钮，即可进入表格回收站界面并执行以下操作。

> 回收站中的表格数据仍可被数据库连接所访问

* 清空回收站：永久删除所有的表格数据
* 恢复：将表格恢复到数据库中去

<figure><img src="../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

### 设计表格

点击菜单中的设计按钮，可以进入表格设计页面，在表格设计页面可以查看表格的基础属性，包括：

**表格相关**

* 表格所属数据库 Schema
* 表格名称，以及在物理表中的名称
* 表格描述
* 修改时间

**数据库连接**

这里显示了如何通过数据库连接来直接访问当前的数据库

* 数据库连接
* 数据库连接数

**字段信息**

字段的详细属性

* id 字段 ID
* name 字段名称
* dbFieldName 字段在物理数据库中的名称
* type 字段类型
* description 字段描述
* graph 查看当前字段依赖关系
* cellValueType 当前字段值类型
* isLookup 是否为从关联表查找出来的字段
* isMultipleCellValue 是否为[数组值字段](../zi-duan/tong-yong/dan-zhi-yu-duo-zhi.md)
* isComputed 是否为计算字段（计算字段的记录值不可修改）
* isPending 是否为计算中
* hasError 是否存在计算错误
* notNull 是否启用非空校验
* unique 是否启用唯一值校验

<figure><img src="../../.gitbook/assets/image (17) (1).png" alt=""><figcaption></figcaption></figure>

### 访问表格的方式

用户可以通过三种方式访问表格：

* [视图](../shi-tu/)
* [API](../../kai-fa-zhe/api/)
* [SQL查询语句](../../kai-fa-zhe/shu-ju-ku-lian-jie.md)

视图是上述方式中最直观的一种。用户可以通过各种视图对表格进行检索、操作，并以此构建出复杂的应用。

新添加的表格都会默认包含一个[表格视图](../shi-tu/biao-ge-shi-tu.md)便于用户快速开始开始处理数据。

### 表格的功能

创建视图：用户可以创建多种视图来对表格进行操作，不同视图用于满足不同场景需求。例如：表格视图数据密度最高，操作方式接近电子表格，上手难度最低。而看板则为项目管理场景提供更好的支持。

关于视图的详细介绍请参考[视图的相关章节](../shi-tu/)
