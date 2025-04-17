---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
调用方 ^XfhlNxFW

服务提供方 ^euyErX0T

服务定义方 ^022cXZfg

实现类A ^jumNDg9w

实现类B ^IK3PeRRe

服务接口 ^qClO1nOc

服务加载机制 ^AkVJmLmM

实现继承 ^gICvsy6n

发现加载 ^Q4ozYuEa

调用 ^PteXBX14

实现 ^FYnIrTID

调用方 ^U9HhBjyQ

服务提供方 ^Dl8NKeXq

服务定义方 ^TjCzuf5e

com.mysql.cj.jdbc.Driver ^yt2OuheY

org.postgresql.Driver ^Eqo6rFK0

java.sql.Driver ^DhvEi7pZ

DriverManager.getConnection(...) ^XUuCMEvH

实现继承 ^RODktrKb

发现加载 ^QBP30de5

调用 ^6NrhdJdW

实现 ^sf1eNdWB

调用方 ^jvscEwvq

服务提供方 ^ec842X7D

服务定义方 ^VDoa2Ahi

org.apache.logging.log4j.jcl.Log4jLog ^Rj7Fg4Ca

org.apache.commons.logging.impl.SLF4JLog ^cVAsJQIL

org.apache.commons.logging.Log ^e9WieR27

LogFactory.getLog(...) ^6oCrsho8

实现继承 ^WzJ6M6RJ

发现加载 ^OIU3Tvpj

调用 ^Wvfd0kvP

实现 ^3AFv12r5

SPI ^nfbcDaHS

JDBC ^G8KA448o

JCL ^1derDddG

1.定义服务接口:
  org.apache.commons.logging.Log 是服务接口。
2.加载服务提供者:
  JCL 的 LogFactory  会通过 SPI 机制加载所有注册的
  Log 实现类，并根据优先级选择合适的实现。 ^VnNjucLQ

1.实现服务接口:
  具体的日志框架（如 Log4j、SLF4J 等）会提供 Log 接口的实现类。
2.注册服务提供者:
  在 META-INF/services/ 目录下创建一个文件，文件名为
  org.apache.commons.logging.Log，内容为实现类的全限定名。 ^v5NOm8qb

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.25",
	"elements": [
		{
			"id": "Ba-rrEbC8UKdYRuH7jPpU",
			"type": "rectangle",
			"x": -204.25,
			"y": 74.7578125,
			"width": 114,
			"height": 35,
			"angle": 0,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"seed": 1154980633,
			"version": 87,
			"versionNonce": 52291353,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "XfhlNxFW"
				},
				{
					"id": "aBQ3Q_SaqIqzEdmS0qQH4",
					"type": "arrow"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false
		},
		{
			"id": "XfhlNxFW",
			"type": "text",
			"x": -177.25,
			"y": 80.2578125,
			"width": 60,
			"height": 24,
			"angle": 0,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1895566169,
			"version": 103,
			"versionNonce": 862614263,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"text": "调用方",
			"rawText": "调用方",
			"fontSize": 20,
			"fontFamily": 4,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 19,
			"containerId": "Ba-rrEbC8UKdYRuH7jPpU",
			"originalText": "调用方",
			"lineHeight": 1.2
		},
		{
			"type": "rectangle",
			"version": 135,
			"versionNonce": 1692638201,
			"isDeleted": false,
			"id": "i756Pa0wdvc_iNXacZPct",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -67.25,
			"y": -62.7421875,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 34,
			"seed": 764935639,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "euyErX0T"
				},
				{
					"id": "mpPv9IXF7WV8xeva13RuJ",
					"type": "arrow"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 162,
			"versionNonce": 28245015,
			"isDeleted": false,
			"id": "euyErX0T",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -60.25,
			"y": -57.7421875,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 24,
			"seed": 933767927,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "服务提供方",
			"rawText": "服务提供方",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "i756Pa0wdvc_iNXacZPct",
			"originalText": "服务提供方",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 124,
			"versionNonce": 1910486233,
			"isDeleted": false,
			"id": "kaTviWdqb4yGWo-09WQU2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -351.25,
			"y": -60.7421875,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 34,
			"seed": 699767767,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "022cXZfg"
				},
				{
					"id": "aBQ3Q_SaqIqzEdmS0qQH4",
					"type": "arrow"
				},
				{
					"id": "mpPv9IXF7WV8xeva13RuJ",
					"type": "arrow"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 154,
			"versionNonce": 1690657079,
			"isDeleted": false,
			"id": "022cXZfg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -344.25,
			"y": -55.7421875,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 24,
			"seed": 1516374263,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "服务定义方",
			"rawText": "服务定义方",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "kaTviWdqb4yGWo-09WQU2",
			"originalText": "服务定义方",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"id": "8I7LHivg38B8TcOmjBoVg",
			"type": "rectangle",
			"x": 43.75,
			"y": -206.2421875,
			"width": 118,
			"height": 123,
			"angle": 0,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"exia3XxAQ13TSClWdKAA0"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"seed": 578160119,
			"version": 225,
			"versionNonce": 1034269113,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "DPtYTystyJmTrXElw1-nz",
					"type": "arrow"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false
		},
		{
			"id": "SttWzHFYCLvkrGdFpp-FJ",
			"type": "rectangle",
			"x": 54.8458904109589,
			"y": -192.18739297945206,
			"width": 95.8904109589041,
			"height": 34,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"exia3XxAQ13TSClWdKAA0"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"seed": 1577652919,
			"version": 181,
			"versionNonce": 504504919,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "jumNDg9w"
				},
				{
					"id": "MViSBIosE4oletgyFyWEL",
					"type": "arrow"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false
		},
		{
			"id": "jumNDg9w",
			"type": "text",
			"x": 69.16872040212971,
			"y": -186.69424229452054,
			"width": 67.2447509765625,
			"height": 23.013698630136982,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"exia3XxAQ13TSClWdKAA0"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1639390199,
			"version": 166,
			"versionNonce": 492376729,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"text": "实现类A",
			"rawText": "实现类A",
			"fontSize": 19.17808219178082,
			"fontFamily": 4,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 18,
			"containerId": "SttWzHFYCLvkrGdFpp-FJ",
			"originalText": "实现类A",
			"lineHeight": 1.2
		},
		{
			"type": "rectangle",
			"version": 179,
			"versionNonce": 1315553143,
			"isDeleted": false,
			"id": "Pn-Ya_i3JZbwDLXWmYMNw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 54.8458904109589,
			"y": -130.8175299657534,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 95.8904109589041,
			"height": 34,
			"seed": 1391294935,
			"groupIds": [
				"exia3XxAQ13TSClWdKAA0"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "IK3PeRRe"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 166,
			"versionNonce": 1974294393,
			"isDeleted": false,
			"id": "IK3PeRRe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 69.37464538992268,
			"y": -125.3243792808219,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 66.83290100097656,
			"height": 23.013698630136982,
			"seed": 216934135,
			"groupIds": [
				"exia3XxAQ13TSClWdKAA0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"fontSize": 19.17808219178082,
			"fontFamily": 4,
			"text": "实现类B",
			"rawText": "实现类B",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Pn-Ya_i3JZbwDLXWmYMNw",
			"originalText": "实现类B",
			"lineHeight": 1.2,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 202,
			"versionNonce": 135313559,
			"isDeleted": false,
			"id": "z4bwiCeUAJF7pgzwijkLm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -457.25,
			"y": -204.2421875,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 153.99999999999997,
			"height": 124,
			"seed": 781426135,
			"groupIds": [
				"UHCTO9TA5UQOenw74Ih_y"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1740817685092,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 168,
			"versionNonce": 1223032921,
			"isDeleted": false,
			"id": "J3N87LB1GQwEl2Ze29E_M",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -443.25,
			"y": -194.2421875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 34,
			"seed": 1479527159,
			"groupIds": [
				"UHCTO9TA5UQOenw74Ih_y"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "qClO1nOc"
				},
				{
					"id": "MViSBIosE4oletgyFyWEL",
					"type": "arrow"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 180,
			"versionNonce": 549162423,
			"isDeleted": false,
			"id": "qClO1nOc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -433.25,
			"y": -189.2421875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 24,
			"seed": 336155671,
			"groupIds": [
				"UHCTO9TA5UQOenw74Ih_y"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "服务接口",
			"rawText": "服务接口",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "J3N87LB1GQwEl2Ze29E_M",
			"originalText": "服务接口",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 196,
			"versionNonce": 81169721,
			"isDeleted": false,
			"id": "MPqqWmhHEyyLzACjaHOaf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -443.25,
			"y": -130.2421875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132,
			"height": 43,
			"seed": 1779743031,
			"groupIds": [
				"UHCTO9TA5UQOenw74Ih_y"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "AkVJmLmM"
				},
				{
					"id": "DPtYTystyJmTrXElw1-nz",
					"type": "arrow"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 202,
			"versionNonce": 1133428439,
			"isDeleted": false,
			"id": "AkVJmLmM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -437.25,
			"y": -120.7421875,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120,
			"height": 24,
			"seed": 1874229847,
			"groupIds": [
				"UHCTO9TA5UQOenw74Ih_y"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "服务加载机制",
			"rawText": "服务加载机制",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "MPqqWmhHEyyLzACjaHOaf",
			"originalText": "服务加载机制",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"id": "MViSBIosE4oletgyFyWEL",
			"type": "arrow",
			"x": 51.75,
			"y": -179.63013713191202,
			"width": 390,
			"height": 4.6672048206309,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1068178039,
			"version": 122,
			"versionNonce": 283278873,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "gICvsy6n"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-390,
					4.6672048206309
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "SttWzHFYCLvkrGdFpp-FJ",
				"gap": 3.0958904109589085,
				"focus": 0.28756282180147275
			},
			"endBinding": {
				"elementId": "J3N87LB1GQwEl2Ze29E_M",
				"gap": 5,
				"focus": 0.16691616766467066
			},
			"startArrowhead": null,
			"endArrowhead": "triangle"
		},
		{
			"id": "gICvsy6n",
			"type": "text",
			"x": -183.25,
			"y": -192.7421875,
			"width": 80,
			"height": 24,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 359514649,
			"version": 28,
			"versionNonce": 1126091767,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"text": "实现继承",
			"rawText": "实现继承",
			"fontSize": 20,
			"fontFamily": 4,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 19,
			"containerId": "MViSBIosE4oletgyFyWEL",
			"originalText": "实现继承",
			"lineHeight": 1.2
		},
		{
			"id": "DPtYTystyJmTrXElw1-nz",
			"type": "arrow",
			"x": -308.25,
			"y": -108.2421875,
			"width": 346,
			"height": 0.9999999999999858,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1166560119,
			"version": 72,
			"versionNonce": 469586681,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "Q4ozYuEa"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					346,
					0.9999999999999858
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "MPqqWmhHEyyLzACjaHOaf",
				"gap": 3,
				"focus": 0.013857428381079282
			},
			"endBinding": {
				"elementId": "8I7LHivg38B8TcOmjBoVg",
				"gap": 6,
				"focus": -0.6111163183053706
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "Q4ozYuEa",
			"type": "text",
			"x": -175.25,
			"y": -119.7421875,
			"width": 80,
			"height": 24,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1971625015,
			"version": 26,
			"versionNonce": 728773911,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"text": "发现加载",
			"rawText": "发现加载",
			"fontSize": 20,
			"fontFamily": 4,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 19,
			"containerId": "DPtYTystyJmTrXElw1-nz",
			"originalText": "发现加载",
			"lineHeight": 1.2
		},
		{
			"id": "aBQ3Q_SaqIqzEdmS0qQH4",
			"type": "arrow",
			"x": -153.8350320255871,
			"y": 73.7578125,
			"width": 130.43033597219227,
			"height": 95,
			"angle": 0,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1906880889,
			"version": 100,
			"versionNonce": 715819993,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "PteXBX14"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-130.43033597219227,
					-95
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "Ba-rrEbC8UKdYRuH7jPpU",
				"gap": 1,
				"focus": 0.2322022621423819
			},
			"endBinding": {
				"elementId": "kaTviWdqb4yGWo-09WQU2",
				"gap": 5.5,
				"focus": 0.2602280348759222
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "PteXBX14",
			"type": "text",
			"x": -246.25,
			"y": 14.2578125,
			"width": 40,
			"height": 24,
			"angle": 0,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 858742551,
			"version": 24,
			"versionNonce": 334985783,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"text": "调用",
			"rawText": "调用",
			"fontSize": 20,
			"fontFamily": 4,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 19,
			"containerId": "aBQ3Q_SaqIqzEdmS0qQH4",
			"originalText": "调用",
			"lineHeight": 1.2
		},
		{
			"id": "mpPv9IXF7WV8xeva13RuJ",
			"type": "arrow",
			"x": -68.25,
			"y": -47.24218750000001,
			"width": 162,
			"height": 1.000000000000007,
			"angle": 0,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 716065977,
			"version": 78,
			"versionNonce": 1694345401,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "FYnIrTID"
				}
			],
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-162,
					1.000000000000007
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "i756Pa0wdvc_iNXacZPct",
				"gap": 1,
				"focus": 0.10707933119886162
			},
			"endBinding": {
				"elementId": "kaTviWdqb4yGWo-09WQU2",
				"gap": 7,
				"focus": -0.12130914265385985
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "FYnIrTID",
			"type": "text",
			"x": -169.25,
			"y": -58.7421875,
			"width": 40,
			"height": 24,
			"angle": 0,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 998899191,
			"version": 20,
			"versionNonce": 832117591,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1740817685092,
			"link": null,
			"locked": false,
			"text": "实现",
			"rawText": "实现",
			"fontSize": 20,
			"fontFamily": 4,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 19,
			"containerId": "mpPv9IXF7WV8xeva13RuJ",
			"originalText": "实现",
			"lineHeight": 1.2
		},
		{
			"type": "rectangle",
			"version": 322,
			"versionNonce": 372367065,
			"isDeleted": false,
			"id": "ypZN0mp3DViB7E-jhWh4L",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -667.75,
			"y": 433.4244689941406,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 35,
			"seed": 1596804025,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "U9HhBjyQ"
				},
				{
					"id": "GFZxoY2Hx0dkFxww7cJsB",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 338,
			"versionNonce": 2124987545,
			"isDeleted": false,
			"id": "U9HhBjyQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -640.75,
			"y": 438.9244689941406,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 24,
			"seed": 517827737,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "调用方",
			"rawText": "调用方",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ypZN0mp3DViB7E-jhWh4L",
			"originalText": "调用方",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 374,
			"versionNonce": 595050873,
			"isDeleted": false,
			"id": "6L9u9uVzESME3k6yDnC9y",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -526.75,
			"y": 295.9244689941406,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 34,
			"seed": 966160761,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Dl8NKeXq"
				},
				{
					"id": "qoYLKEm_OOvLrlmUY7E7B",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 406,
			"versionNonce": 512653113,
			"isDeleted": false,
			"id": "Dl8NKeXq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -519.75,
			"y": 300.9244689941406,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 24,
			"seed": 614193753,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "服务提供方",
			"rawText": "服务提供方",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "6L9u9uVzESME3k6yDnC9y",
			"originalText": "服务提供方",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 363,
			"versionNonce": 1074604057,
			"isDeleted": false,
			"id": "puoZ1koOLYKNZBxG8a-DE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -810.75,
			"y": 297.9244689941406,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 34,
			"seed": 1623271225,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "TjCzuf5e"
				},
				{
					"id": "GFZxoY2Hx0dkFxww7cJsB",
					"type": "arrow"
				},
				{
					"id": "qoYLKEm_OOvLrlmUY7E7B",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 397,
			"versionNonce": 913347257,
			"isDeleted": false,
			"id": "TjCzuf5e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -803.75,
			"y": 302.9244689941406,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 24,
			"seed": 141154329,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "服务定义方",
			"rawText": "服务定义方",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "puoZ1koOLYKNZBxG8a-DE",
			"originalText": "服务定义方",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 527,
			"versionNonce": 1545589657,
			"isDeleted": false,
			"id": "RSp9OrgQiYe0RSt_zgm3h",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -415.75,
			"y": 156.42446899414062,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 241.99999999999997,
			"height": 111,
			"seed": 495545593,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "nKgMLcTYEag-7zPwBGrcl",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 501,
			"versionNonce": 61899097,
			"isDeleted": false,
			"id": "W6pDKpriKf5OtgjnSqC_4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -404.65410958904107,
			"y": 170.47926351468857,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 225.8904109589041,
			"height": 33.99999999999997,
			"seed": 396584409,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "yt2OuheY"
				},
				{
					"id": "bC7mAijI95EE3ELLg3IMz",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 590,
			"versionNonce": 1774239513,
			"isDeleted": false,
			"id": "yt2OuheY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -388.55100616037026,
			"y": 175.97241419962006,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 193.6842041015625,
			"height": 23.013698630136982,
			"seed": 835404473,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 19.17808219178082,
			"fontFamily": 4,
			"text": "com.mysql.cj.jdbc.Driver",
			"rawText": "com.mysql.cj.jdbc.Driver",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "W6pDKpriKf5OtgjnSqC_4",
			"originalText": "com.mysql.cj.jdbc.Driver",
			"lineHeight": 1.2,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 507,
			"versionNonce": 560690169,
			"isDeleted": false,
			"id": "u-uczylwFECxRTqgkPmmP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -404.65410958904107,
			"y": 224.84912652838716,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 224.89041095890408,
			"height": 33.013698630136986,
			"seed": 2024047513,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Eqo6rFK0"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 621,
			"versionNonce": 2142014681,
			"isDeleted": false,
			"id": "Eqo6rFK0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -380.45820983468667,
			"y": 229.84912652838716,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 176.4986114501953,
			"height": 23.013698630136982,
			"seed": 409118841,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 19.17808219178082,
			"fontFamily": 4,
			"text": "org.postgresql.Driver",
			"rawText": "org.postgresql.Driver",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "u-uczylwFECxRTqgkPmmP",
			"originalText": "org.postgresql.Driver",
			"lineHeight": 1.2,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 536,
			"versionNonce": 739740089,
			"isDeleted": false,
			"id": "DOgq0aB_eTxhrQA1IcGzm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1097.75,
			"y": 150.42446899414062,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 335.00000000000006,
			"height": 124,
			"seed": 1791570265,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 482,
			"versionNonce": 265284249,
			"isDeleted": false,
			"id": "qUhjGSbXn68DpKuR7zkJj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -950.75,
			"y": 165.42446899414062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 150,
			"height": 40,
			"seed": 1160486457,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "DhvEi7pZ"
				},
				{
					"id": "bC7mAijI95EE3ELLg3IMz",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 563,
			"versionNonce": 2105989209,
			"isDeleted": false,
			"id": "DhvEi7pZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -940.5546875,
			"y": 173.42446899414062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 129.609375,
			"height": 24,
			"seed": 107835161,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "java.sql.Driver",
			"rawText": "java.sql.Driver",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "qUhjGSbXn68DpKuR7zkJj",
			"originalText": "java.sql.Driver",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 537,
			"versionNonce": 530343225,
			"isDeleted": false,
			"id": "_hRKnzkIar5zi1cdhbFMU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1078.75,
			"y": 218.42446899414062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 308,
			"height": 45,
			"seed": 1694639097,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "XUuCMEvH"
				},
				{
					"id": "nKgMLcTYEag-7zPwBGrcl",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 695,
			"versionNonce": 1898785529,
			"isDeleted": false,
			"id": "XUuCMEvH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1067.77734375,
			"y": 228.92446899414062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 286.0546875,
			"height": 24,
			"seed": 2095922393,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "DriverManager.getConnection(...)",
			"rawText": "DriverManager.getConnection(...)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "_hRKnzkIar5zi1cdhbFMU",
			"originalText": "DriverManager.getConnection(...)",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 1257,
			"versionNonce": 1444247929,
			"isDeleted": false,
			"id": "bC7mAijI95EE3ELLg3IMz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -407.75,
			"y": 183.54748158206326,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 388,
			"height": 4.442642613054431,
			"seed": 499268025,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "RODktrKb"
				}
			],
			"updated": 1740817735197,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "W6pDKpriKf5OtgjnSqC_4",
				"focus": 0.287563420192861,
				"gap": 3.09589041095893
			},
			"endBinding": {
				"elementId": "qUhjGSbXn68DpKuR7zkJj",
				"focus": 0.16691616766467066,
				"gap": 5
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-388,
					4.442642613054431
				]
			]
		},
		{
			"type": "text",
			"version": 169,
			"versionNonce": 1645707449,
			"isDeleted": false,
			"id": "RODktrKb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -157.75,
			"y": 140.41321711214914,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 24,
			"seed": 1487182489,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "实现继承",
			"rawText": "实现继承",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "bC7mAijI95EE3ELLg3IMz",
			"originalText": "实现继承",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 1219,
			"versionNonce": 522071865,
			"isDeleted": false,
			"id": "nKgMLcTYEag-7zPwBGrcl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -767.75,
			"y": 242.5698080934833,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 346,
			"height": 2.8366504452226877,
			"seed": 1313333113,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "QBP30de5"
				}
			],
			"updated": 1740817735197,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "_hRKnzkIar5zi1cdhbFMU",
				"focus": 0.015073650866122059,
				"gap": 3
			},
			"endBinding": {
				"elementId": "RSp9OrgQiYe0RSt_zgm3h",
				"focus": -0.6111163183053709,
				"gap": 6.000000000000014
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					346,
					2.8366504452226877
				]
			]
		},
		{
			"type": "text",
			"version": 166,
			"versionNonce": 1966564985,
			"isDeleted": false,
			"id": "QBP30de5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -149.75,
			"y": 209.92446899414062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 24,
			"seed": 1022330969,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "发现加载",
			"rawText": "发现加载",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "nKgMLcTYEag-7zPwBGrcl",
			"originalText": "发现加载",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 897,
			"versionNonce": 507802873,
			"isDeleted": false,
			"id": "GFZxoY2Hx0dkFxww7cJsB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -616.882168159761,
			"y": 432.4244689941406,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"width": 127.45023794094573,
			"height": 95,
			"seed": 1315902777,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "6NrhdJdW"
				}
			],
			"updated": 1740817735197,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ypZN0mp3DViB7E-jhWh4L",
				"focus": 0.2322021431058963,
				"gap": 1
			},
			"endBinding": {
				"elementId": "puoZ1koOLYKNZBxG8a-DE",
				"focus": 0.2602280348759227,
				"gap": 5.5
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-127.45023794094573,
					-95
				]
			]
		},
		{
			"type": "text",
			"version": 164,
			"versionNonce": 644406329,
			"isDeleted": false,
			"id": "6NrhdJdW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -220.75,
			"y": 343.9244689941406,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 24,
			"seed": 640288281,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "调用",
			"rawText": "调用",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "GFZxoY2Hx0dkFxww7cJsB",
			"originalText": "调用",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 885,
			"versionNonce": 1969507001,
			"isDeleted": false,
			"id": "qoYLKEm_OOvLrlmUY7E7B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -527.75,
			"y": 311.4244689941406,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"width": 162,
			"height": 1.0000000000000568,
			"seed": 789830393,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "sf1eNdWB"
				}
			],
			"updated": 1740817735197,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "6L9u9uVzESME3k6yDnC9y",
				"focus": 0.10707933119886266,
				"gap": 1
			},
			"endBinding": {
				"elementId": "puoZ1koOLYKNZBxG8a-DE",
				"focus": -0.12130914265385512,
				"gap": 7
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-162,
					1.0000000000000568
				]
			]
		},
		{
			"type": "text",
			"version": 160,
			"versionNonce": 713548281,
			"isDeleted": false,
			"id": "sf1eNdWB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -143.75,
			"y": 270.9244689941406,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 24,
			"seed": 699405273,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "实现",
			"rawText": "实现",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "qoYLKEm_OOvLrlmUY7E7B",
			"originalText": "实现",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 334,
			"versionNonce": 1191918297,
			"isDeleted": false,
			"id": "_3F6Gku4PWY0Fdhg64akm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 307.75,
			"y": 435.4244689941406,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 35,
			"seed": 1277430647,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "jvscEwvq"
				},
				{
					"id": "eT3H9pMRIwbySM_wdALy_",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 350,
			"versionNonce": 1440422041,
			"isDeleted": false,
			"id": "jvscEwvq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 334.75,
			"y": 440.9244689941406,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 60,
			"height": 24,
			"seed": 1889633431,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "调用方",
			"rawText": "调用方",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "_3F6Gku4PWY0Fdhg64akm",
			"originalText": "调用方",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 383,
			"versionNonce": 469671289,
			"isDeleted": false,
			"id": "I6QibT35SQIp6p3DW-o4T",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 445.75,
			"y": 297.9244689941406,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 34,
			"seed": 1431493047,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ec842X7D"
				},
				{
					"id": "0J_157tYYFiMP8sCLNiqB",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 415,
			"versionNonce": 1343116089,
			"isDeleted": false,
			"id": "ec842X7D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 452.75,
			"y": 302.9244689941406,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 24,
			"seed": 2136771287,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "服务提供方",
			"rawText": "服务提供方",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "I6QibT35SQIp6p3DW-o4T",
			"originalText": "服务提供方",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 372,
			"versionNonce": 1831961625,
			"isDeleted": false,
			"id": "3EZqAbTu51wkY1dDq9uN5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 161.75,
			"y": 299.9244689941406,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 34,
			"seed": 1532172279,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "VDoa2Ahi"
				},
				{
					"id": "eT3H9pMRIwbySM_wdALy_",
					"type": "arrow"
				},
				{
					"id": "0J_157tYYFiMP8sCLNiqB",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 406,
			"versionNonce": 1797418681,
			"isDeleted": false,
			"id": "VDoa2Ahi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 168.75,
			"y": 304.9244689941406,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 24,
			"seed": 1329266967,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "服务定义方",
			"rawText": "服务定义方",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "3EZqAbTu51wkY1dDq9uN5",
			"originalText": "服务定义方",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 573,
			"versionNonce": 1446391705,
			"isDeleted": false,
			"id": "BPVGeXAaOCu3-Ehrc0Z-C",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 556.75,
			"y": 158.42446899414062,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 386,
			"height": 111,
			"seed": 210290231,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "fobwBRsKVVPCzObx3-Q2A",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 565,
			"versionNonce": 786355321,
			"isDeleted": false,
			"id": "_Webag0Tpfuc0QkNnhlSD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 567.8458904109589,
			"y": 170.47926351468857,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 333.8904109589041,
			"height": 39,
			"seed": 572581719,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Rj7Fg4Ca"
				},
				{
					"id": "aMhVe-1rF05cbdlrXgV_B",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 686,
			"versionNonce": 1938606649,
			"isDeleted": false,
			"id": "Rj7Fg4Ca",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 579.4468118327937,
			"y": 178.4724141996201,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 310.6885681152344,
			"height": 23.013698630136982,
			"seed": 1314382967,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 19.17808219178082,
			"fontFamily": 4,
			"text": "org.apache.logging.log4j.jcl.Log4jLog",
			"rawText": "org.apache.logging.log4j.jcl.Log4jLog",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "_Webag0Tpfuc0QkNnhlSD",
			"originalText": "org.apache.logging.log4j.jcl.Log4jLog",
			"lineHeight": 1.2,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 579,
			"versionNonce": 667491097,
			"isDeleted": false,
			"id": "aNepbNxZ3tGU3-USkLRW4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 567.8458904109589,
			"y": 219.84912652838716,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 364.8904109589041,
			"height": 40.99999999999999,
			"seed": 284310935,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "cVAsJQIL"
				},
				{
					"id": "fobwBRsKVVPCzObx3-Q2A",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 730,
			"versionNonce": 609085657,
			"isDeleted": false,
			"id": "cVAsJQIL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 579.0716897624812,
			"y": 228.84227721331865,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 342.4388122558594,
			"height": 23.013698630136982,
			"seed": 2099540663,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 19.17808219178082,
			"fontFamily": 4,
			"text": "org.apache.commons.logging.impl.SLF4JLog",
			"rawText": "org.apache.commons.logging.impl.SLF4JLog",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "aNepbNxZ3tGU3-USkLRW4",
			"originalText": "org.apache.commons.logging.impl.SLF4JLog",
			"lineHeight": 1.2,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 545,
			"versionNonce": 1814914489,
			"isDeleted": false,
			"id": "BpEAiR17KYw4n03aGA6dO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -125.25,
			"y": 152.42446899414062,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 335.00000000000006,
			"height": 124,
			"seed": 1267925975,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 560,
			"versionNonce": 147474073,
			"isDeleted": false,
			"id": "EMi2C-6XIY7qd__WpE6jC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -106.25,
			"y": 167.42446899414062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 278,
			"height": 40,
			"seed": 743600375,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "e9WieR27"
				},
				{
					"id": "aMhVe-1rF05cbdlrXgV_B",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 659,
			"versionNonce": 1218065497,
			"isDeleted": false,
			"id": "e9WieR27",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -100.19921875,
			"y": 175.42446899414062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 265.8984375,
			"height": 24,
			"seed": 1491548695,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "org.apache.commons.logging.Log",
			"rawText": "org.apache.commons.logging.Log",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "EMi2C-6XIY7qd__WpE6jC",
			"originalText": "org.apache.commons.logging.Log",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 575,
			"versionNonce": 1743012153,
			"isDeleted": false,
			"id": "_WheCHKgmr22bF8PEyQZ1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -25.25,
			"y": 220.42446899414062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 227,
			"height": 45,
			"seed": 1715855159,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "6oCrsho8"
				},
				{
					"id": "fobwBRsKVVPCzObx3-Q2A",
					"type": "arrow"
				}
			],
			"updated": 1740817735121,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 737,
			"versionNonce": 908986105,
			"isDeleted": false,
			"id": "6oCrsho8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -6.8671875,
			"y": 230.92446899414062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 190.234375,
			"height": 24,
			"seed": 1456660567,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "LogFactory.getLog(...)",
			"rawText": "LogFactory.getLog(...)",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "_WheCHKgmr22bF8PEyQZ1",
			"originalText": "LogFactory.getLog(...)",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 1518,
			"versionNonce": 2136584313,
			"isDeleted": false,
			"id": "aMhVe-1rF05cbdlrXgV_B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 564.7500000000001,
			"y": 185.60826759444785,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 388.0000000000001,
			"height": 3.930740762710002,
			"seed": 1818410359,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "WzJ6M6RJ"
				}
			],
			"updated": 1740817735197,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "_Webag0Tpfuc0QkNnhlSD",
				"focus": 0.28755425734843787,
				"gap": 3.0958904109587593
			},
			"endBinding": {
				"elementId": "EMi2C-6XIY7qd__WpE6jC",
				"focus": 0.16691616766467016,
				"gap": 5
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-388.0000000000001,
					3.930740762710002
				]
			]
		},
		{
			"type": "text",
			"version": 116,
			"versionNonce": 160521401,
			"isDeleted": false,
			"id": "WzJ6M6RJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -163.25,
			"y": 447.7557339750342,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 24,
			"seed": 976877207,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "实现继承",
			"rawText": "实现继承",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "aMhVe-1rF05cbdlrXgV_B",
			"originalText": "实现继承",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 1382,
			"versionNonce": 268478009,
			"isDeleted": false,
			"id": "fobwBRsKVVPCzObx3-Q2A",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 204.75,
			"y": 244.2567006868419,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 358,
			"height": 1.095653252971033,
			"seed": 1997343671,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "OIU3Tvpj"
				}
			],
			"updated": 1740817735197,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "_WheCHKgmr22bF8PEyQZ1",
				"focus": 0.07391566063890716,
				"gap": 3
			},
			"endBinding": {
				"elementId": "aNepbNxZ3tGU3-USkLRW4",
				"focus": -0.10627386288570406,
				"gap": 5.095890410958873
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					358,
					-1.095653252971033
				]
			]
		},
		{
			"type": "text",
			"version": 113,
			"versionNonce": 1961509497,
			"isDeleted": false,
			"id": "OIU3Tvpj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -156.25,
			"y": 507.05795070613465,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80,
			"height": 24,
			"seed": 251690199,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "发现加载",
			"rawText": "发现加载",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "fobwBRsKVVPCzObx3-Q2A",
			"originalText": "发现加载",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 910,
			"versionNonce": 875899897,
			"isDeleted": false,
			"id": "eT3H9pMRIwbySM_wdALy_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 358.2781839408695,
			"y": 434.4244689941406,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"width": 129.68531146438073,
			"height": 95,
			"seed": 1973996023,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Wvfd0kvP"
				}
			],
			"updated": 1740817735197,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "_3F6Gku4PWY0Fdhg64akm",
				"focus": 0.23220214371178952,
				"gap": 1
			},
			"endBinding": {
				"elementId": "3EZqAbTu51wkY1dDq9uN5",
				"focus": 0.2602280348759227,
				"gap": 5.5
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-129.68531146438073,
					-95
				]
			]
		},
		{
			"type": "text",
			"version": 111,
			"versionNonce": 68466745,
			"isDeleted": false,
			"id": "Wvfd0kvP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -227.25,
			"y": 646.9244689941406,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 24,
			"seed": 940208919,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735121,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "调用",
			"rawText": "调用",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "eT3H9pMRIwbySM_wdALy_",
			"originalText": "调用",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 892,
			"versionNonce": 1909670329,
			"isDeleted": false,
			"id": "0J_157tYYFiMP8sCLNiqB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 444.75,
			"y": 313.4244689941406,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"width": 162,
			"height": 1.0000000000000568,
			"seed": 1318713399,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "3AFv12r5"
				}
			],
			"updated": 1740817735197,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "I6QibT35SQIp6p3DW-o4T",
				"focus": 0.10707933119886266,
				"gap": 1
			},
			"endBinding": {
				"elementId": "3EZqAbTu51wkY1dDq9uN5",
				"focus": -0.12130914265385512,
				"gap": 7
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-162,
					1.0000000000000568
				]
			]
		},
		{
			"type": "text",
			"version": 107,
			"versionNonce": 2079112697,
			"isDeleted": false,
			"id": "3AFv12r5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -150.25,
			"y": 573.9244689941406,
			"strokeColor": "#9c36b5",
			"backgroundColor": "transparent",
			"width": 40,
			"height": 24,
			"seed": 792451415,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735122,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "实现",
			"rawText": "实现",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "0J_157tYYFiMP8sCLNiqB",
			"originalText": "实现",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"id": "nfbcDaHS",
			"type": "text",
			"x": -174.25,
			"y": -9.842187499999998,
			"width": 53.296875,
			"height": 43.199999999999996,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 634438775,
			"version": 43,
			"versionNonce": 531852953,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1740817685093,
			"link": null,
			"locked": false,
			"text": "SPI",
			"rawText": "SPI",
			"fontSize": 36,
			"fontFamily": 4,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 34,
			"containerId": null,
			"originalText": "SPI",
			"lineHeight": 1.2
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1333040857,
			"isDeleted": false,
			"id": "G8KA448o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -641.8984375,
			"y": 352.1578125,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 72.3515625,
			"height": 43.199999999999996,
			"seed": 36243129,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735122,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 4,
			"text": "JDBC",
			"rawText": "JDBC",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "JDBC",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 179,
			"versionNonce": 441340857,
			"isDeleted": false,
			"id": "1derDddG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 332.57421875,
			"y": 351.4911407470703,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 54.984375,
			"height": 43.199999999999996,
			"seed": 1842670807,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817735122,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 4,
			"text": "JCL",
			"rawText": "JCL",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "JCL",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"id": "VnNjucLQ",
			"type": "text",
			"x": -947.828947368421,
			"y": -196.31938556871933,
			"width": 478.4375,
			"height": 120,
			"angle": 0,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1740798103,
			"version": 287,
			"versionNonce": 894278807,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1740817685093,
			"link": null,
			"locked": false,
			"text": "1.定义服务接口:\n  org.apache.commons.logging.Log 是服务接口。\n2.加载服务提供者:\n  JCL 的 LogFactory  会通过 SPI 机制加载所有注册的\n  Log 实现类，并根据优先级选择合适的实现。",
			"rawText": "1.定义服务接口:\n  org.apache.commons.logging.Log 是服务接口。\n2.加载服务提供者:\n  JCL 的 LogFactory  会通过 SPI 机制加载所有注册的\n  Log 实现类，并根据优先级选择合适的实现。",
			"fontSize": 20,
			"fontFamily": 4,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 115,
			"containerId": null,
			"originalText": "1.定义服务接口:\n  org.apache.commons.logging.Log 是服务接口。\n2.加载服务提供者:\n  JCL 的 LogFactory  会通过 SPI 机制加载所有注册的\n  Log 实现类，并根据优先级选择合适的实现。",
			"lineHeight": 1.2
		},
		{
			"type": "text",
			"version": 333,
			"versionNonce": 1163484249,
			"isDeleted": false,
			"id": "v5NOm8qb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 189.2023026315794,
			"y": -200.11938556871922,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 616.796875,
			"height": 120,
			"seed": 1113010105,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1740817685093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 4,
			"text": "1.实现服务接口:\n  具体的日志框架（如 Log4j、SLF4J 等）会提供 Log 接口的实现类。\n2.注册服务提供者:\n  在 META-INF/services/ 目录下创建一个文件，文件名为\n  org.apache.commons.logging.Log，内容为实现类的全限定名。",
			"rawText": "1.实现服务接口:\n  具体的日志框架（如 Log4j、SLF4J 等）会提供 Log 接口的实现类。\n2.注册服务提供者:\n  在 META-INF/services/ 目录下创建一个文件，文件名为\n  org.apache.commons.logging.Log，内容为实现类的全限定名。",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1.实现服务接口:\n  具体的日志框架（如 Log4j、SLF4J 等）会提供 Log 接口的实现类。\n2.注册服务提供者:\n  在 META-INF/services/ 目录下创建一个文件，文件名为\n  org.apache.commons.logging.Log，内容为实现类的全限定名。",
			"lineHeight": 1.2,
			"baseline": 115
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1971c2",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 4,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1148.2776653171395,
		"scrollY": 466.1658599276934,
		"zoom": {
			"value": 0.7499999999999998
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%