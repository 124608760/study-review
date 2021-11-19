# dom相关
节点的分类：document、元素节点、文本（包括空格）都是节点

节点类型：文本节点中，注释也是一种节点#comment

节点关系：childNodes查找所有子节点，不包括孙，不仅仅是元素节点
children 子元素节点

定位父级：若本身有定位则是其定位父级，若本身没有定位则是父级

HTMLCollection是元素集合而NodeList是节点集合（既包括元素，也包括节点）

nodelist可以用foreach，HTMLCollection不可以

nodelist中childnodes有动态更新，querySelectAll没有。HTMLCollection每次调用都会动态更新

