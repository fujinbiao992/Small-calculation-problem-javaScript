创建一个coding2.html文件，基础代码如下：

~~~~javascript
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title>Page Title</title>
</head>
<body>
    <div id="sourceinfos"></div>
</body>
<script>
</script>
</html>
~~~~

- 给定数据集如下
  - var source1 = "19 32 3 41 57 62 1 23 34";
  - var source2 = "99 83 2 13 62 51 32 14 23";
- 对数据集进行分析，获取交集数据(交集就是两个数据集共同包含的内容)
- 将获取到的交集内容进行升序排列，要求如下：
  - 不允许存在undifined 或空字符串或空格
- 将升序排列后结果通过console进行输出打印