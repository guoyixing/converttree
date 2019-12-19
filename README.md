权限树通用解决方案（增强）：https://github.com/guoyixing/converttreex/tree/master
# converttree
权限树通用解决方案
##
1.仅支持java8，id不可重复
###
2.使用方法
###
2.1普通使用
####
ConvertTree<T> convertTree = new ConvertTree<>();<br/> 
List<TreeNode<T>> result= convertTree.getForest(数据List，id字段名，父id字段名);<br/> 
2.2注解使用
####
将@TreeId和@TreeFid分别注解在T的id字段和父id字段上<br/> 
ConvertTree<T> convertTree = new ConvertTree<>();<br/> 
List<TreeNode<T>> result= convertTree.getForest(数据List);<br/> 
