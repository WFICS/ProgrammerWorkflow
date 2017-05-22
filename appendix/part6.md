# Hybrid App 发展史

## 概述

> 
回顾历史，展望未来。认真分析 Hybrid 的诞生原因、发展经历、才能更好的预测 Hybrid 开发的未来前景。
>
问题 产生 技术，无法解决问题的技术是不存在的。
>
提到 Hybrid 开发，必然要提到 Web，首先让我们看一看Web发展史。
    
* 静态网页:展示内容。
    
* 动态网页:支持页面与服务器交互，构建了现在蓬勃发展的互联网的基础。
    
* 客户端异步交互:解决了整个页面刷新的问题，优化了用户体验。
    
* 开发效率提速阶段:各种功能丰富的第三方JS库迅速崛起，提高工作效率。
    
* 移动平台:智能手机飞速发展，需要快速构建App，满足市场需求，Hybrid作为一种解决方案应运而生。
    * Hybrid分类
            Hybrid时间点从2012年开始，陆续出现了三种Hybrid模式 : 多View混合型、单View混合型、Web主体性；按照另一种分类方式分为 : 重架构混合模式、轻架构混合模式。
            其中，多View混合型、单View混合型属于重架构混合模式，Web主体性属于轻架构混合模式。
            当前，最流行的是Web主体性。

    * Hybrid优势
            
        * 跨平台、快速发布、高效开发。
             
    * Hybrid劣势
            
        * 达不到原生平台的流畅体验。
        
----
## Cordova 平台
> 
当前所有的Hybrid框架都是基于Cordova平台进行JS跟原生通讯。
因此Cordova平台支持的调试方式也是通用的。 

* Cordova优质博客列表
            
    * [传智播客][net_cordovablog]
        
    * [极客学院][net_cordovablog1]

    * Cordova教程博客

        * [Cordova 概述][cordova1]

        * [Cordova开发前的准备工作][cordova2]
        
        * [使用Cordova命令行界面(CLI)][cordova3]
        
        * [Cordova应用解析][cordova4]
        
        * [Cordova开发技巧][cordova5]
        
        * [开发Android平台的Cordova应用][cordova6]
        
        * [使用PhoneGap Build][cordova7]
        
        * [使用Cordova API开发(上)][cordova8]
        
        * [使用Cordova API开发(下)][cordova9]
        
        * [创建Cordova插件][cordova10]
        
        * [构建一个完整的Cordova应用][cordova11]
    
        * [使用Android Studio构建Cordova项目][cordova12]
        
* [Cordova 官网地址][cordova_doc]
        
* Cordova平台构成
            
    * Cordova CLI(Command Line Interface)
            
    * Cordova 项目结构

            ProjectName
             ┣ config.xml         **Cordova项目配置文件**
             ┣ merges             **针对ios、android等平台的html文件**
             ┣ hooks              **Cordova CLI使用的项目自定义脚本**
             ┣ platforms
             ┃  ┣ android         **android开发人员工作目录**
             ┃  ┗ ios             **iOS开发人员工作目录**
             ┣ plugins            **插件源码目录**
             ┗ www                **H5开发人员工作目录**

        
[cordova1]: https://segmentfault.com/a/1190000002903546
        
[cordova2]: https://segmentfault.com/a/1190000002911058
        
[cordova3]: https://segmentfault.com/a/1190000002915917
        
[cordova4]: https://segmentfault.com/a/1190000002927103
        
[cordova5]: https://segmentfault.com/a/1190000002933971
        
[cordova6]: https://segmentfault.com/a/1190000002938482
        
[cordova7]: https://segmentfault.com/a/1190000002942222
        
[cordova8]: https://segmentfault.com/a/1190000002964603
        
[cordova9]: https://segmentfault.com/a/1190000003013808
        
[cordova10]: https://segmentfault.com/a/1190000003022593
        
[cordova11]: https://segmentfault.com/a/1190000004188031
        
[cordova12]: https://segmentfault.com/a/1190000004276191

[net_cordovablog]: http://www.itcast.cn/news/20151228/14522674095.shtml

[net_cordovablog1]: http://wiki.jikexueyuan.com/project/apache-cordova-tutorial/

[cordova_doc]: http://cordova.apache.org

* `React Native、Weex : 即保留了Hybrid应用的优势，力图解决 Hybrid 劣势`


----
## Web 发展史

----
### ->静态网页

* 问题
> 内容分享

* 技术
    * Html
      * 年 : 1995
    
    * CSS
      * 年 : 1996

    * Javascript
      * 年 : 1996
      * 问题 : 客户端脚本语言

----
### ->动态网页
* 问题
> 动态网页问题

* 技术
  * CGI（共用网关接口）
  
  * [Perl](http://baike.baidu.com/view/46614.htm)
    * 年 : 1987
    * 问题 : 服务器端动态网页
  
  * [PHP](http://baike.baidu.com/subview/99/5828265.htm)
    * 年 : 1995
    * 问题 : 服务器端动态网页
  
  * [JSP](http://baike.baidu.com/subview/3387/16963334.htm)
    * 年 : 1996
    * 问题 : 服务器端动态网页
  
  * [ASP](http://baike.baidu.com/subview/2616/14622918.htm)
    * 年 : 1996
    * 问题 : 服务器端动态网页

----
### ->客户端异步交互

* 问题
> 客户端交互->异步、局部页面交互

* 技术
  * [Ajax](http://baike.baidu.com/subview/1641/5762264.htm)
  * 年 : 1998—2005

----
### ->开发效率提速阶段

* 问题
> 加快开发效率

* 技术
  * jQuery
    * 年 : 2006
    * 问题 : JS库、浏览器的兼容性、简化dom操作，加快开发效率
  
  * YUI
    * 2006
    * 问题 :
  
  * Ruby on Rails
    * 年 : 2007
    * 问题 : 开发模式->MVC
  
  * NodeJS
    * 年 : 2009
    * 问题 : 待定
  
  * Prototypejs
    * 年 : 2009
    * 问题 : 待定
  
  * UnderScore
    * 年 : 2009
    * 问题 : 待定
  
  * AngularJS
    * 年 : 2009
    * 问题 : 谷歌 JS 前端框架
  
  * CoffeeScript
    * 年 : 2009-2010
    * 问题 : 作为JavaScript的转译语言
  
  * Backbone
    * 年 : 2010
    * 问题 : JS 前端框架
  
  * Web2.0 Html5
    * 年 : 2010
    * 问题 : 待定
  
  * EmberJS
    * 年 : 2011
    * 问题 : 待定
  
  * Bootstrap
    * 年 : 2011
    * 问题 : 待定
  
  * TypeScript
    * 年 : 2012
    * 问题 : 待定
  
  * React
    * 年 : 2013
    * 问题 : 构建随着时间数据不断变化的大规模应用程序
  
  * Vue
    * 年 : 2013
    * 问题 : 待定

----
### ->移动平台

* 问题
> 移动平台

* 技术
  * Web App
    * 年 : 待定
    * 问题 : Html5移动App开发框架
    * 技术
      * JQuery Mobile
        * 轻量级框架
        * 缺点
          * 没有 MVC 多人协作 开发的概念
          * 项目比较大后 代码不易维护
        * 适用范围
          * 中小项目 1-2 个人开发很适用
    
      * SenchaTouch
        * 重量级的框架(需要 extjs 基础 代码复杂需要较强的程序基础)
        * 优点
          * 兼容性好,基于 MVC 世界上第一个 html5 移动开发框架
          * 可视化开发工具 sencha architect

      * Angularjs
        * 轻量级框架
        * 优点
          * 支持 MVC
          * 支持 数据双向绑定
          * 通过 SASS 构建应用程序,它提供了很多 UI 组件来帮助开发者开发强大的应用
  
  * Hybrid App
    * 年 : 2008-2011
    * 问题 : 解决 html 无法访问设备的问题
  
  * React Native
    * 年 : 2015
    * 问题 : 既拥有Native的用户体验、又保留React的开发效率
  
  * Weex
    * 年 : 2016

----
## Hybrid App 分类一
----
### ->多View混合型

* 描述
> 2012年常见的Hybrid App是Native View与WebView交替的场景出现。这种应用混合逻辑相对简单。
即在需要的时候，将WebView当成一个独立的View（Activity）运行起来，在WebView内完成相关的展示操作。开发难度和Native App基本相当。

* 特点
> 即Native View和Web View独立展示，交替出现。
这种移动应用主体通常是Native App，Web技术只是起到补充作用。

* 开发难度
> 开发难度与native app相当

----
### ->单View混合型

* 描述
> 这种Hybrid App的开发成本较高，开发难度较大，但是体验较好。
如百度搜索为代表的单View混合型移动应用，既可以实现充分的灵活性，又能实现较好的用户体验。

* 特点
> 即在同一个View内，同时包括Native View和Web View。互相之间是覆盖（层叠）的关系。(会牺牲内存，达到显示快的效果)

* 开发难度
> 开发成本较高，难度较大，但是体验较好。

----
### ->Web主体型

* 描述
> 这种类型开发的移动应用体验相对而言存在缺陷，但整体开发难度大幅降低，并且基本可以实现跨平台。Web主体型的移动应用用户体验的好坏，主要取决于底层中间件的交互与跨平台的能力。
从分析可见，Hybrid App中的Web主体型只要能够解决用户体验差的问题，就可以变成最佳Hybrid App解决方案类型。

* 特点
> 即移动应用的主体是Web View，主要以网页语言编写，穿插Native功能的Hybrid App开发类型。

* 开发难度
> 整体开发难度低，基本可以实现跨平台

* 平台
  * appMobi : 除基础的底层能力更多是通过插件（Plugins）扩展的机制实现Hybrid
  * PhoneGap : 除基础的底层能力更多是通过插件（Plugins）扩展的机制实现Hybrid
  * WeX5 : WeX5则在揉合PhoneGap和Bootstrap等主流技术的基础上，对性能进一步做了深度优化，不但完全具备Native App对本地资源的调用能力，性能体验也不输原生；WeX5所开发出来的app具备完全的跨端运行能力，可以无需任何修改直接运行在各种前端环境上。
  * AppCan : 除了插件机制，还提供了大量的单View混合型的接口来完善和弥补Web主体型Hybrid App体验差的问题，接近Native App的体验。

----
### ->多主体共存型（灵活型）

* 描述
> 这是一种新型的开发模式，即支持Web主体型的应用，又支持以Native主体的应用，也支持两者混合的开发模式。

* 平台
  * kerkee : 它具有跨平台、用户体验好、性能高、扩展性好、灵活性强、易维护、规范化、具有Debug环境、彻底解决跨域问题等特点。用户体验与Native App媲美。功能方面，开发者可随意扩展接口。

----
## Hybrid App 分类二
----
### ->重架构混合模式

* 原因
> “重混”架构这种依赖Native UI的混合框架，本着“Web不够，就Native来凑”的核心思路，的确提升了交互体验，但同时也带来了无法回避的显著缺点：Web和Native技术的交叉混杂让开发者的编程和调试都很不方便；尤其是无法直接运行在微信这类超级App平台之上，更是“重混”App的致命硬伤。

----
### ->轻架构混合模式
* 原因
> Hybrid APP就必须坚持几个原则：UI部分必须用纯Web技术，完全采用H5技术；在底层的设备接口上，确实是JS无法完成的原生部分，需要Native技术来弥补的，也必须坚持Native技术不去侵入UI。这样一个框架就是“轻混”Hybrid APP框架。“轻混”框架才是真正的HTML5 APP框架，在技术上更轻量，成本更低、也更容易推广，能真正做到只需一次开发就能跨Android、iOS和微信等各种端发布。“轻混”才是Hybrid APP技术发展的必然方向。

----
### Hybrid 优势

* 跨平台<br/>
  Web内容可以做到开发一次，所有平台生效，诸多产品需要这种能力。

* 快速发布<br/>
  iOS平台，Apple Store平均审核周期1～2周不等，甚至更长，产品的发布周期从2周到1月，这对需要快速发布的产品而言难以接受。

  Android平台，应用商店众多，发布过程烦琐。虽然可以应用内升级，但是带来的问题是新App需要通过应用商店，此外APK体积庞大，2G/3G环境下体验差。

* 高效开发<br/>
  Web开发经过20年的发展，已经将结构（HTML）、表现（CSS）、行为（JavaScript）3部分很好地分离开，在分工协作、开发效率上会具明显优势。

* 丰富的Device API<br/>
  Web（HTML5）强调通用性，受限于标准和浏览器实现，许多有用的系统功能未能得到支持（或部分支持）。而Native最大的优势在于设备API的调用能力，只要桥接Native和Web，Web也就能够拥有这种能力。

----
### Hybrid 劣势

* CPU/GPU密集类应用目前看更适合Native，例如极品飞车这样的游戏。这种劣势是在不断弱化的，正如 “CSS Transform 3D”引入GPU大大缓解了Web动画不流畅的问题。

* 静态资源从服务器端加载导致的UI展示延迟问题。这个问题可以通过Native拦截WebView通信加载已打包的公共库来缓解。

----
## Hybrid 平台调查

|平台         |时间|Native端|JS端|特点|归属|优点|iOS版本|android版本||
|----|----|----|----|----|----|----|----|----|----|
|PhoneGap     |2008-2011/7|Cordova|jQuery Mobile||国外|||||
|Ionic        |2013|Cordova|AngularJS||国外||>=iOS7|>=Android4.1||
|[WeX5](http://docs.wex5.com/)         |2014|Cordova|Knockoutjs(MVVM)、requirejs、bootstrap、jquery等||国内|||||
| | | | | | | | | | |
|APICloud     |2016前|Cordova|[JS前端文档](http://docs.apicloud.com/Front-end-Framework/framework-dev-guide)|APICloud推行“云端一体”的理念，重新定义了移动应用开发。<br/>APICloud为开发者从“云”和“端”两个方向提供API，简化移动应用开发技术，让移动应用的开发周期从一个月缩短到7天。<br/>APICloud由“云API”和“端API”两部分组成，可以帮助开发者快速实现移动应用的开发、测试、发布、管理和运营的全生命周期管理|国内|SuperWebview比基础的webview或phonegap拥有更丰富的功能，支持用HTML5开发具有原生UI和UE体验的界面、同时支持调用二维码等系统功能，并且能很好的把蓝牙、WiFi和智能硬件相连接。||||
|ExMobi       |2014|Cordova|||国内(烽火星空)|||||
|AppCan       |2010|Cordova|||国内(正益无线)|||||
| | | | | | | | | | |
|Titanium |2009-2012|Cordova|||国外(Appcelerator)|||||
|NativeScript |2006|Cordova||||国外(telerik)||||
|Kinvey       |2011|Cordova||||国外||||
| | | | | | | | | | |
|Kerkee       |2015|待定(等待发展)    |||国内|||||
| | | | | | | | | | |
|[React-canvas](https://github.com/Flipboard/react-canvas)       |2015|基于Canvas的UI框，预取代Html标签绘制界面。[技术对比文章](http://www.infoq.com/cn/articles/innovative-high-performance-mobile-ui-framework-canvas)    |||国外|||||
| | | | | | | | | | |
|Pastry       |----|Cordova    |backbone(MVVM)、requirejs、bootstrap、jquery等||--|||||

|平台         |时间|Native端|JS端|特点||||||
|----|----|----|----|----|----|----|----|----|----|
|React Native |2015||||国外|||||
|Weex         |2016||||国内||||-|

----
## Hybrid App 调试方法

----
## ->调试方法汇总

|开发阶段|调试方法|应用场景|设备依赖|设备支持|无线支持|JS调试|编译打包|加密网络请求|优点|缺点|
|----|----|----|----|----|----|----|----|----|----|----|
|UI开发阶段|mockdata|开发H5端UI界面，UI界面显示模拟数据，非网络请求真实数据。|-|web|-|√|-|×| | |
| | | | | | | | | | |
|整个开发阶段|console.log()|将H5日志输出到浏览器、原生端输出窗口、iOS真机日志文件。|-|web<br/>iOS真机/模拟器<br/>android真机/模拟器|-|-|√|-| |依赖开发人员打印日志的完整性|
|原生联调阶段|Ripple仿真|业务开发严重依赖 Cordova API 的测试|[ripple-emulator npm包 教程](http://cordova.apache.org/docs/en/latest/guide/next/index.html#ripple)|web|-|×|×|-|不依赖真机，模拟出真机的API接口|可以使用基于 Safari、Chrome 的调试方法代替|
|原生联调阶段|Weinre|调试JS业务逻辑，监听实时变量|[Weinre npm包 教程](http://cordova.apache.org/docs/en/latest/guide/next/index.html#weinre)|web<br/>iOS真机/模拟器<br/>android真机/模拟器|√|√|√|√<br/>||1 weinre这类调试工具仍属于插件性质，诸如“网络”、“本地资源”等高级调试功能无法支持<br/> 2 需要额外添加代码<br/>|
| | | | | | | | | | |
|-|PhoneGap Developer App|与 PhoneGap Desktop App 配合使用<br/>或者使用 phonegap serve 命令|[PhoneGap Developer App 手机软件 按照教程](http://docs.phonegap.com/getting-started/1-install-phonegap/desktop/)|iOS真机/模拟器<br/> android真机/模拟器<br/>|√|×|×|×|1 无须配置任何iOS、android、nodejs环境<br/> 2 支持 console 输出到 PhoneGap Desktop App 终端|1 严重依赖phoneGap的cordova API <br/>2 热加载效率低 <br/>3 不能使用自定义的cordova插件|
|-|PhoneGap Desktop App|用于给 Cordova 项目开启 serve 命令<br/>与 PhoneGap Developer App 配合使用|[PhoneGapDesktop客户端软件包 安装教程](http://docs.phonegap.com/getting-started/1-install-phonegap/desktop/)|-|-|-|-|-|见 PhoneGap Developer App 优点|1 只是作为 phonegap serve的客户端 <br/>2 热加载效率低|
| | | | | | | | | | |
|原生联调阶段|基于 Safari 的调试|适用 Weinre 应用场景|[safari 教程](http://cordova.apache.org/docs/en/latest/guide/next/index.html#ios-debugging)|iOS真机/模拟器|真机不支持|√|√|√||依赖 Mac、XCode 环境|
|原生联调阶段|基于 Chrome 的调试|适用 Weinre 应用场景|[chrome 教程](http://cordova.apache.org/docs/en/latest/guide/next/index.html#chrome-remote-debugging)|android真机/模拟器|真机不支持|√|√|√||依赖 Android Studio 环境|
|原生联调阶段|GapDebug|适用 Weinre 应用场景|[GapDebug软件包下载](https://www.genuitec.com/products/gapdebug/)|iOS真机<br/> android真机<br/> 模拟器待定|×|√|√|√|不依赖app的开发环境|依赖 console.log() 查看日志|

[更多介绍参考 Debugging Cordova apps](http://cordova.apache.org/docs/en/latest/guide/next/index.html#debugging-cordova-apps)

----
##  ->推荐工作流程 & 调试方法

* **推荐工作流程**

  * 完成UI界面开发 -> 完成原生联调


* **推荐调试方法**

  * **`mockdata & console.log() -> GapDebug -> 基于Safari、Chrome方法 -> Weinre`**
