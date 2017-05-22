# 行业金字塔

```chart
{
    "title": {
    },
    "tooltip": {
        "trigger": "item",
        "formatter": "{a} <br/>{b} : {c}%"
    },
    "toolbox": {
        "feature": {
            "dataView": {"readOnly": false},
            "restore": {},
            "saveAsImage": {}
        }
    },
    "legend": {
        "data": ["行业","服务行业","服务外包行业","软件服务外包行业","ITO、BPO、KPO、DCO","金融服务\n外包行业"]
    },
    "calculable": true,
    "series": [
        {
            "name":"行业模型",
            "type":"funnel",
            "left": "10%",
            "top": 60,
            "bottom": 60,
            "width": "80%",
            "min": 0,
            "max": 100,
            "minSize": "0%",
            "maxSize": "100%",
            "sort": "ascending",
            "gap": 2,
            "label": {
                "normal": {
                    "show": true,
                    "position": "inside"
                },
                "emphasis": {
                    "textStyle": {
                        "fontSize": 20
                    }
                }
            },
            "labelLine": {
                "normal": {
                    "length": 10,
                    "lineStyle": {
                        "width": 1,
                        "type": "solid"
                    }
                }
            },
            "itemStyle": {
                "normal": {
                    "borderColor": "#fff",
                    "borderWidth": 1
                }
            },
            "data": [
                {"value": 16.67, "name": "金融服务\n外包行业"},
                {"value": 33.33, "name": "ITO、BPO、KPO、DCO"},
                {"value": 50, "name": "软件服务外包行业"},
                {"value": 66.67, "name": "服务外包行业"},
                {"value": 83.33, "name": "服务行业"},
                {"value": 100, "name": "行业"}
            ]
        }
    ]
}
```

其中：

* DCO（数字内容外包人才）

* KPO（知识流程外包人才）

* BPO（业务流程外包人才）

* 是指企业通过长期合同的方式，将公司一些重复的非核心或核心业务流程外包给外部专业服务提供商，以达到降低成本、增强企业竞争力的目的。

* ITO（信息技术外包人才）
* 是指企业专注于自己的核心业务，而将其IT系统的全部或部分外包给专业的信息技术服务公司。


# 参考
 
* 服务外包导论
 
* 软件外包质量管理
 
* 服务外包产业链
 
* 印度服务外包发展研究
 
* 中国服务外包竞争力报告