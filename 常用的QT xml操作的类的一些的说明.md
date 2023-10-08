常用的QXML类的一些的说明



**1.QDomAttr**--------  表示QDomElement的一个属性

​	1.1 name：属性名
​	1.2 value：属性值
​	1.3 ownerElement：所属元素

**2.QDomDocument**--------------表示一个 XML 文档,从概念上讲，它是文档树的根，并提供对文档数据的主要访问。

2.1. createAttribute、createComment、createElement、createTextNode等：创建对应的数据类型对象。

**3.QDomElement** -----------------代表 DOM 树中的一个元素

​	3.1 attribute、attributeNode、attributes：根据属性名获取属性值、根据属性名获取属性节点、获取该节点的属性节点列表

​	3.2 setAttribute、removeAttribute：添加(修改)属性、删除属性

​	3.3 setAttribute、removeAttribute：添加(修改)属性、删除属性

**4.QDomNamedNodeMap** --------------包含可以通过名称访问的节点集合

**5.QDomNode** ----------------------DOM 树中所有节点的基类

​	5.1  appendChild、insertAfter、insertBefore、removeChild、replaceChild：在最后插入一个新的子节点、在指定子节点之后插入新的子节点、在指定子节点之前插入新的子节点、删除子节点、替换子节点。

​	5.2 childNodes：返回字节的列表。

**6.QDomNodeList** ---------------------QDomNode 对象列表

**7.QDomProcessingInstruction** -----------------表示一条 XML 处理指令

**8.QDomText**			----------------------表示解析的 XML 文档中的文本数据

​	