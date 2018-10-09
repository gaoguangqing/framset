# framset
framset例子

效果链接https://gaoguangqing.github.io/framset/

## 定义和用法
>frameset 元素可定义一个框架集。它被用来组织多个窗口（框架）。
>每个框架存有独立的文档。
>在其最简单的应用中，frameset 元素仅仅会规定在框架集中存在多少列或多少行。您必须使用 cols 或 rows 属性。

## 例子
```
<frameset rows="10%,*">
	<frame src="top.html" name="top"/>
	<frameset cols="10%,*">
		<frame src="left.html" name="left" />
		<frame src="right.html" name="right"/>
	</frameset>
</frameset>
```


