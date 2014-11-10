启用样式yi

1。工具中，更新缓存
2。模块管理--数据调用--新增的模块？/select sql
	新增模板：
		yi幻灯

<div class="carousel-inner">
	[loop]
	[order=1]
	<div class="item active">
		<a href="{url}" {target}><img src="{pic}" alt="{title}" class="img-responsive"></a>
		<div class="carousel-caption">
			{title}
		</div>
	</div>
	[/order]
	<div class="item">
		<a href="{url}" {target}><img src="{pic}" alt="{title}" class="img-responsive"></a>
		<div class="carousel-caption">
			{title}
		</div>
	</div>
	[/loop]
</div>

		
		yi文章标题列表
		
[loop]
<a href="{url}"{target} class="list-group-item">{title}</a>
[/loop]

	新增数据调用
		yi首页幻灯
		yi最新文章列表
		