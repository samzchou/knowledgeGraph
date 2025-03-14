# 知识图谱可视化

[![English](https://img.shields.io/badge/English-Click-yellow)](README.md) [![中文文档](https://img.shields.io/badge/中文文档-点击查看-orange)](README-zh.md)

![](./image_01.png)
------------
![](./image_02.png)

#### 主要框架及技术实现
* HTML
* Javascript
* [echats](https://echarts.apache.org)
* [JQuery](https://jquery.com/)


### 运行
* git clone https://github.com/samzchou/knowledgeGraph.git
* [/example/index.html](./example/index.html)；将此文件置于服务器中可访问
* [模拟数据](./example/jsonData.json)
* 远程读取数据
```javascript
async function initChart() {
	// load data
	$.getJSON('http://server/jsonData.json').then(response => {
		// do something
	})
}
```

## 开发不容易，别忘了点个星