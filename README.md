# Visualization of Knowledge Graph

[![English](https://img.shields.io/badge/English-Click-yellow)](README.md) [![中文文档](https://img.shields.io/badge/中文文档-点击查看-orange)](README-zh.md)

![](./image_01.png)
------------
![](./image_02.png)

#### Main framework and technical implementation
* HTML
* Javascript
* [echats](https://echarts.apache.org)
* [JQuery](https://jquery.com/)


### Run
* git clone https://github.com/samzchou/knowledgeGraph.git
* [/example/index.html](./example/index.html)；Place this file accessible on the server
* [analog data](./example/jsonData.json)
* Remote reading of data
```javascript
async function initChart() {
	// load data
	$.getJSON('http://server/jsonData.json').then(response => {
		// do something
	})
}
```

## Developing is not easy, don't forget to star