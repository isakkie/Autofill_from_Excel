
这是一个商品信息的数据管理系统，需要在对应位置[新建品系]中录入指定列的内容。

页面中包含三种形式的信息：文本框、填充下拉列表和单选按钮。目前需要填充的内容已经在excel中全部整理完毕，需要实现：
1.打开：数据库管理/品系管理/新建品系
2.抓取excel每行内容，一一对应地录入网页表格指定位置中，点击最下方的保存
3.回到上级品系管理页面，点击右上角[新建品系] 
4.重复2,3的过程，直到该excel录完

【注】
（1）表格填充中，下拉列表需要先输入内容进行搜索，然后才能从搜索结果的列表中获取结果确认。输入的搜索内容可在excel中直接抓取
（2）添加属性：需要先点击标签才会弹出下一级填充表格。所以添加属性部分的操作过程为：①网页点击普通属性标签，②抓取excel表格“属性名称”列，③填充网页表格，④网页点击属性值旁边的“+”，⑤抓取excel“属性值”内容，⑥填充网页表格
