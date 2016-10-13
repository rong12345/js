## JS学习

JavaScript 是属于网络的脚本语言！

### JavaScript：写入 HTML 输出
```
document.write("<h1>This is a heading</h1>");
document.write("<p>This is a paragraph</p>");
```

只能在 HTML 输出流中使用 document.write。如果您在文档已加载后使用它（比如在函数中），会覆盖整个文档。(意思就是在文档加载过后，如果我们用比方说按钮的方式重新加载文档，就会把文档都覆盖；)
例如：
1. 例子一

```
<!DOCTYPE html>
<html>
<body>
<p>
JavaScript 能够直接写入 HTML 输出流中：
</p>
<script>
document.write("<h1>This is a heading</h1>");
document.write("<p>This is a paragraph.</p>");
</script>
<p>
您只能在 HTML 输出流中使用 <strong>document.write</strong>。
如果您在文档已加载后使用它（比如在函数中），会覆盖整个文档。
</p>
</body>
</html>

```
结果
![]()
