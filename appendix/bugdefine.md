<!-- toc -->

# 软件缺陷概述

>软件缺陷（Defect），常常又被叫做Bug。所谓软件缺陷，即为计算机软件或程序中存在的某种破坏正常运行能力的问题、错误，或者隐藏的功能缺陷。缺陷的存在会导致软件产品在某种程度上不能满足用户的需要。

>IEEE729-1983对缺陷有一个标准的定义：从产品内部看，缺陷是软件产品开发或维护过程中存在的错误、毛病等各种问题；从产品外部看，缺陷是系统所需要实现的某种功能的失效或违背。

>在软件开发生命周期的后期，修复检测到的软件错误的成本较高。

# 软件缺陷属性

>软件缺陷的属性包括缺陷标识、缺陷类型、缺陷级别（或严重等级）、缺陷产生可能（或概率）、缺陷优先级、缺陷状态、缺陷起源、缺陷来源、缺陷根源（原因）。  
以上属性是为了准确描述缺陷而赋予的，这里分别作介绍：

## 缺陷标识(Identifier)
    
是标记某个缺陷的唯一标识，可以用数字序号表示；

## 缺陷类型(Type)
    
缺陷类型是根据缺陷的自然属性划分的缺陷种类。
功能、用户界面、文档、软件包、性能、接口、兼容性等；
        
### 功能
                
影响了各种系统功能、逻辑的缺陷；

#### 功能类
                    
* 重复的功能
                    
* 多余的功能  
                    
* 功能实现与设计要求不相符
                    
* 功能使用性、方便性、易用性不够
                    
#### 数据类

* 数据有效性检测不合理
                    
* 数据来源不正确
                    
* 数据处理过程不正确
                    
* 数据处理结果不正确
                    
#### 流程类
                
* 流程控制不符和要求
                    
* 流程实现不完整
                    
#### 信息类
                
* 提示信息重复或出现时机不合理
                    
* 提示信息格式不符和要求
                    
* 提示框返回后焦点停留位置不合理
                    
#### 建议类
                
* 功能性建议
                    
* 操作建议
                    
* 校检建议
                    
* 说明建议
                    
### 用户界面
            
影响了用户界面、人机交互特性的缺陷；
                
#### 界面类
                
* 界面不美观
                    
* 控件排列、格式不统一
                    
* 焦点控制不合理或不全面
                    
### 文档
            
影响发布和维护，包括注释、用户手册、设计文档等的缺陷；
                
### 软件包
            
由于软件配置库、变更管理或版本控制引起的错误；
                
###  性能类

* 并发量

* 数据量

* 响应时间

* 执行时间

* 事务处理速率

### 接口

与其他组件、模块、调用参数、控制块等不匹配、冲突；
                
### 兼容性

与工作环境、其他外设，如操作系统、浏览器、网络环境等不匹配、冲突；
                
## 缺陷级别(Severity)
    
缺陷严重程度是指因缺陷引起的故障对软件产品的影响程度。
致命、严重、一般、轻微；（举例）
        
### 致命
        
系统任何一个主要功能完全失效，用户数据受到破坏，系统崩溃、悬挂、 司机或者危机人身安全；
            
示例：
            
* 系统无法安装、登陆或其他主要功能 不可用
            
* 死循环或内存不足等原因导致程序 无法运行
            
* 由于程序引起的系统无法启动、死 机、蓝屏、非法退出
            
* 在数据或安全方面存在重大问题
            
### 严重
        
系统的主要功能部分失效，数据不能保存，系统的次要功能完全丧失， 系统所提供的功能或服务受到明显影响；
            
示例：

* 基本功能存在部分问题或次要功能 无法实现或遗漏
            
* 未进行异常处理
            
* 性能与预期相差很大
            
### 一般
        
系统的次要功能没有完全实现，但不影响用户的正常使用。如提示信息 不准确或用户界面差、操作时间长等。
            
示例：
            
* 次要功能没有完全实现，但不影响用户使用本产品
            
* 界面存在明显缺陷，设计不友好
            
* 提示信息不准确
            
* 一般的性能问题
            
### 轻微
        
使操作者不方便或遇到麻烦，但它不影响功能的操作和执行，如个别不影响理解的错别字、排布不整齐等。
            
示例：

* 界面格式显示不规范
            
* 建议性的改进要求
       
## 缺陷产生可能性
    
必现、通常、有时、很少；
        
### 必现
        
按照一定路径必定出现，其产生概率为100%；
            
### 通常
        
按照测试用例（即已知步骤），通常情况下回产生这个缺陷，其产生频 率大概是80%；
            
### 有时
        
按照测试用例，有时候产生这个缺陷，其产生频率大概是30%；
            
### 很少
        
按照测试用例，很少产生这个缺陷，其产生概率大概是1%以下；实际测试中，仅出现过一次后无法复现的缺陷也划分到此类；
         
## 缺陷的优先级(Priority)
    
缺陷的优先级指缺陷必须被修复的紧急程度。
        
### 立即解决
        
缺陷导致系统几乎不能使用或者测试不能继续，需立即修复；
            
### 高优先级
        
缺陷严重，影响测试，需要优先考虑；
            
### 正常排队
        
缺陷需要正常排队等待修复；
            
### 低优先级
        
缺陷可以在开发人员有时间的时候被纠正。
    
## 缺陷状态(Status)
    
缺陷状态指缺陷通过一个跟踪修复过程的进展情况。
打开、已修复、关闭、拒绝、重复、重新打开、推迟、保留、不能重现； （可根据实际情况增加或减少使用的缺陷状态）
        
### 打开
        
问题还没有解决，确认“提交的缺陷”，等待处理，如新报的缺陷；
            
### 已修复
        
已被开发人员检查、修复过的缺陷，通过单元测试，认为已经解决但 还没有被测试人员验证；
            
### 关闭
        
测试人员验证后，确认缺陷不存在之后的状态；
            
### 拒绝
        
开发人员认为不是缺陷；
            
### 重复
        
开发人员认为此缺陷与某打开的缺陷重复；
            
### 重新打开
        
测试人员验证后，确认缺陷仍然存在后的状态；
            
### 推迟
        
这个软件缺陷可以在下一个版本中解决；

### 保留
        
由于技术原因或者第三方软件的缺陷，开发人员不能修复的缺陷；
            
### 不能重现
        
开发人员不能再现这个缺陷，需要测试人员确认缺陷再现的步骤；
            
## 缺陷的起源(Origin)

缺陷来源指缺陷引起的故障或事件第一次被检测到的阶段。
在软件生命周期中，缺陷所占比例：需求和架构阶段54%、设计阶段25%、编码阶段15%、其他6%；
        
### 需求
        
### 架构
        
### 设计
        
### 编码
        
### 测试
        
### 用户
        
## 缺陷的来源(Source)
    
缺陷来源指引起缺陷的起因。
        
### 需求说明书
        
需求的错误或不清楚引起的问题；
            
### 设计文档
        
设计文档描述不准确，与需求说明书不一致的问题；
            
### 系统集成接口
        
系统各模块参数不匹配、开发组之间缺乏协调引起的缺陷；
            
### 数据流（库）
        
由于数据字典、数据库中的错误引起的缺陷；
            
### 程序代码
        
纯粹由编码引起的缺陷；
            
## 缺陷的根源(Root Cause)
    
缺陷根源指发生错误的根本因素。
        
### 测试策略
        
错误的测试范围，误解测试目标，超越测试能力等；
            
### 过程、工具和方法
        
无效的需求收集过程，过失的风险管理过程，不适用的项 目管理方法，无效的变更控制过程等；
            
### 团队/人
        
项目团队职责较差，缺乏培训，没有经验的项目团队，缺乏士气等；
            
### 缺乏组织和沟通
        
缺乏用户参与，职责不明确、管理失败等；
            
### 硬件
        
硬件配置不对、缺乏等；
            
### 软件
        
软件配置不对、缺乏，或操作系统错误导致无法释放资源，工具软件错误，编译器错误等；
            
### 工作环境
        
组织机构调整，预算改变，工作环境恶劣等。
