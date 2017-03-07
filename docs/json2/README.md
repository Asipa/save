“JSON”未定义解决办法
将JavaScript对象类型的参数通过JSON.stringify转换成字符串传递时，IE6、7、8会报：“JSON”未定义 的错误。可以通过在html文件的head头内引入json2.js文件来解决
<script type="text/javascript" src="json2.js"></script>
