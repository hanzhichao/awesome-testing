收集整理，测试相关工具、资源面试题等，欢迎补充完善


## 功能测试  


### 测试工具
- [XMind](https://xmind.cn/): 思维导图工具，常用来梳理测试点，商业软件，支持免费试用，有功能限制
- [XShell](https://www.xshell.com/zh/free-for-home-school/): Windows平台远程Linux服务器连接及操作工具，商业软件，支持免费试用，有功能限制
- [爱思助手](https://www.i4.cn/): iOS应用测试包安装工具


### 项目/测试管理
- [Jira](https://www.atlassian.com/software/jira): 缺陷跟踪、客户服务、需求收集、流程审批、任务跟踪、项目跟踪和敏捷管理。  
- [Tapd](https://m.tapd.cn/): 腾讯出品的项目管理平台，支持需求、迭代、任务、缺陷、测试用例管理等
- [PingCode](https://pingcode.com/): 新一代研发管理工具
- [TestLink](http://www.testlink.org/): 开源测试用例管理，测试计划，测试执行，测试报告。  
- [禅道](https://www.zentao.net/): ，国产开源工具，记录bug，用例管理，项目管理。  
- [Redmine](http://www.redmine.org/): 用Ruby开发的基于web的项目管理软件  


### 抓包工具

- [Chrome Devtools](https://leeon.gitbooks.io/devtools/content/learn_basic/overview.html): Chrome浏览器自带的开发组工具，Network面板可用于抓包
- [Charles](https://www.charlesproxy.com/): 多平台HTTP接口抓包工具，商业软件，支持免费试用
- [Fiddler](https://www.telerik.com/fiddler): Fiddler是一个HTTP调试抓包工具。它通过代理的方式获取程序HTTP通讯的数据，可以用其检测网页和服务器的交互情况  
- [Wireshark](https://www.wireshark.org/)：基于网卡的抓包工具，支持HTTP、TCP、UDP等各种协议的抓包，支持各种操作系统
- [Mitmtproxy](https://mitmproxy.org/): 开源HTTP抓包工具，支持使用代码编写抓包规则
- [Anyproxy](https://github.com/alibaba/anyproxy): 阿里巴巴开源多HTTP抓包工具
- [Tcpdump](https://linux.die.net/man/8/tcpdump)：Linux服务端抓包命令。  

### 客户端专项

(TODO)

### 稳定性测试
- [Adb](https://developer.android.com/tools/adb?hl=zh-cn):  Android SDK中内置的Android调试工具
- [Monkey](https://developer.android.com/tools?hl=zh-cn): Android SDK中内置的一款Android稳定性测试工具
- [FastMonkey](https://github.com/zhangzhao4444/Fastmonkey): 张昭开发的一款基于Swift的iOS稳定性测试统计
- [SwiftMonkey](https://github.com/zalando/SwiftMonkey): Zalando小组开发的一款iOS稳定性测试工具，以停止维护

### 弱网测试
- [Fiddler](https://www.telerik.com/fiddler)：使用Fiddler抓包工具可以模拟弱网
- [Charles](https://www.charlesproxy.com/): 使用Charles代理可以模拟弱网
- [TC](https://linux.die.net/man/8/tc) Linux上控制网络流量的工具  

#### 音视频质量

- [FFmpeg](https://www.ffmpeg.org/): 开源的音视频转换命令行工具
- [OpenCV](https://opencv.org/): Python开源图像分析转换三方库


## 服务端测试  

### 常用工具
- [Git](https://git-scm.com/): 代码版本管理命令行工具
- [Docker](https://www.docker.com/): 应用容器，轻量化虚拟机

### 接口测试

- [Postman](https://www.getpostman.com/): HTTP接口测试工具，支持HTTP，Websocket，GraphQ， gRPC接口测试，接口管理及Mock等
- [Bruno](https://www.usebruno.com/): 开源免费的HTTP测试工具，类似Postman，数据存在本地
- [JMeter](https://jmeter.apache.org/): 工业级的压力测试工具，也可以做接口测试  
- [SoapUI](https://www.soapui.org/): 基于SOAP协议的Websevice接口测试工具。 


### 接口管理及测试
- [YApi](https://hellosean1025.github.io/yapi/): 爱奇艺YMFE团队开源的接口管理平台，支持Mock接口
- [RAP2](https://github.com/thx/rap2-delos): 阿里开源的接口管理平台，支持Mock接口
- [ShowDoc](https://www.showdoc.com.cn/): 开源接口文档管理工具，自带模版，方便使用
- [MeterSphere](https://github.com/metersphere/metersphere): 一站式开源持续测试平台。  
- [BlazeMeter](https://www.blazemeter.com/): 一站式持续测试平台
- [Apipost](https://apipost.cn/)]: 一款类似Postman的HTTP接口文档、设计、调试、自动化测试一体化协作工具
- [ApiFox](https://apifox.com/):  另一款类似Postman的HTTP接口文档、设计、调试、自动化测试一体化协作工具


### 数据库客户端
- [Navcat](https://www.navicat.com.cn/products): 商业软件，包含MySQL、PostgreSQL、MongoDB、Redis等各种客户端
- [DBeaver](https://dbeaver.io/): 开源的数据库客户端，支持MySQL、PostgreSQL等
- [Another Redis Desktop Manager](https://github.com/qishibo/AnotherRedisDesktopManager): 另一款开源的Redis桌面客户端

### 服务端监控

- [Zabbix](https://github.com/zabbix/zabbix): 经典的开源的Linux服务实时监控工具
- [Prometheus](https://prometheus.io/)]: 开源实时监控、时序数据库，监控数据采集，多和Grafana配合使用
- [Grafana](https://github.com/grafana/grafana): 开源监控表盘系统，多和Prometheus配合使用
- [Nightingale-夜莺监控](https://github.com/ccfos/nightingale): 滴滴开源版监控系统，支持对接各种数据库及监控表盘系统
- [htop](https://hisham.hm/htop/): 实时统计Linux系统资源占用率的Linux命令行工具 
- [iftop](https://en.wikipedia.org/wiki/Iftop): 实时统计Linux网络流量的Linux命令行工具 
- [nload](https://linux.die.net/man/1/nload): Linux网速实时监控的Linux命令行工具 

  
### 代码质量 &代码审查
- [SonarQube](https://www.sonarqube.org/): 开源代码质量和安全的扫描工具，支持Python，Java等多种语言项目
- [Gerrit](https://www.gerritcodereview.com/): 配合Git的代码审查工具

### 代码覆盖率
- [Goc](https://github.com/qiniu/goc/tree/master): 开源的Golang项目代码覆盖率工具
- [Jacoco](https://www.eclemma.org/jacoco/): 开源的Java项目代码覆盖率工具 
- [CodePulse](http://code-pulse.com/): 实时代码覆盖率工具 

### 流量回放

- [GoReplay](https://goreplay.org/): 网络监控工具，可以做流量回放，压力测试，流量分析  
- [TcpCopy](https://github.com/session-replay-tools/tcpcopy): 流量回放工具。  
- [vm-sandbox-repeater](https://github.com/alibaba/jvm-sandbox-repeater): 阿里开源的基于JVM-Sandbox的流量录制回放工具，提供入口请求（HTTP/Dubbo/Java）流量回放、子调用（Java/Dubbo）返回值Mock能力。  


### 安全测试
- [AppScan](https://cloud.appscan.com/): App安全测试工具

### 混沌测试
- [ChaosBlade](https://github.com/chaosblade-io/chaosblade): 阿里巴巴开源的一款简单易用、功能强大的混沌实验注入工具。  
- [ChaosMesh](https://github.com/chaos-mesh/chaos-mesh): 基于 Kubernetes 的云原生混沌工程平台。  

## 性能测试

### 服务端性能测试
- [LoadRunner](https://ssl.www8.hp.com/sg/en/ad/load-runner/load-runner.html): HP的商业性能测试工具  
- [JMeter](https://jmeter.apache.org/)：开源的基于Java的接口压力测试工具
- [Locust](https://www.locust.io/)：基于Python的性能测试工具，Web界面
- [Wrk](https://github.com/wg/wrk): 一款现代HTTP基准测试工具，Linux命令
- [Apache Bench](http://httpd.apache.org/docs/2.4/programs/ab.html): HTTP接口性能测试命令
- [Siege](https://www.joedog.org/): Siege是一个多线程HTTP负载测试和基准测试工具  

### Web页面性能测试
- [Chrome LightHouse](https://developer.chrome.com/docs/lighthouse/overview?hl=zh-cn): Chrome浏览器自带的页面性能测试工具
- [WebPageTest](https://github.com/WPO-Foundation/webpagetest):测量和分析网页性能工具,支持开发者下载源文件搭建私人的内部测试站点  
- [PageSpeed Insights](https://developers.google.cn/speed/pagespeed/insights/):专注于改进网页性能的开发者工具,google出品。  

### App性能测试
- [Perfdog](https://perfdog.qq.com/): App性能监控及分析工具，已转为收费软件

## 自动化测试

### 测试框架

#### Python
- [Pytest](https://docs.pytest.org): 最强大的Python测试框架，可定制性高，插件丰富。  
- [Unittest](https://docs.python.org/3/library/unittest.html): Python官方内置的测试框架。  
- [Robot Framework](https://robotframework.org/): 基于关键字驱动的测试框架，开源，易用  
- [Behave](https://github.com/behave/behave): 基于Python的BDD自动化测试框架  
- [QTAF](https://github.com/Tencent/QTAF): 腾讯推出的测试框架，类似Unittest

#### Java
- [JUnit](https://junit.org): 最著名的xUnit类的单元测试框架，但是不仅仅可以做单元测试。  
- [TestNG](https://testng.org/): 更强大的Java测试框架，灵活可扩展，支持注解和多线程。  
- [Spock](https://github.com/spockframework/spock): Java及Groovy应用的BDD测试框架
- [Cucumber-JVM](https://github.com/cucumber/cucumber-jvm): Java版Cucumber，一款BDD测试框架
- [Rest-assured](https://github.com/rest-assured/rest-assured): Java一款易用的的测试HTTP接口测试框架
- [Maven](https://maven.apache.org/): Java项目构建及依赖管理框架

#### Golang
- [Testify](https://github.com/stretchr/testify)]: Golang三方具单元测试框架，包含测试套件、常用断言及Mock工具等
- [HttpRunner](https://github.com/httprunner/httprunner): 基于YAML测试文件的HTTP及UI测试库

#### C++
- [GoogleTest](https://github.com/google/googletest): 一款C++单元测试框架
- [Bazel](https://bazel.build/about?hl=zh-cn): 一款C++项目构建及测试框架

#### 跨语言测试框架

- [Cucumber](https://github.com/cucumber): BDD测试框架
	- [Cucumber-Ruby](https://github.com/cucumber/cucumber-ruby)： Ruby语言BDD测试框架
	- [Cucumber-JVM](https://github.com/cucumber/cucumber-jvm)：Java语言BDD测试框架
	- [Cucumber-JS](https://github.com/cucumber/cucumber-js): JavaScript语言BDD测试框架
	- [GoDog](https://github.com/cucumber/godog): Golang语言BDD测试框架
	- [SpecFlow](https://github.com/SpecFlowOSS/SpecFlow) : C#语言BDD测试框架
	- [Behave](https://github.com/behave/behave) : Python语言BDD测试框架
	- [Cucumber Rust](https://github.com/cucumber-rs/cucumber)：Rust语言BDD测试框架
	- [Behat](https://docs.behat.org/en/latest/) : PHP语言BDD测试框架

- [Allure](http://allure.qatools.ru/): 测试报告框架，支持Pytest, Cucumber等

#### 其他
- [Gauge](https://gauge.org/index.html): 轻量级的跨平台测试自动化工具，可以以业务语言编写测试用例。  

### WebUI自动化

- [Selenium](https://www.seleniumhq.org/): 业界最有影响力的Web自动化测试工具。 
- [Cypress](https://www.cypress.io/): 自带浏览器，基于Javascript的Web自动化测试工具，较Selenium更快
- [Playwright](https://github.com/microsoft/playwright-python) ：微软开源的一款Python异步Web测试库，支持多种浏览器，较Selenium更快
- [Puppeteer](https://pptr.dev/): 基于Javascript的的异步Web测试库，较Selenium更快

### AppUI自动化

#### Android & iOS自动化
- [Appium](http://appium.io/): 支持android和ios的移动端自动化测试工具
- [STF](https://openstf.io/): STF(smartphone test farm) 移动设备管理工具，通过浏览器控制和管理移动设备。  
- [Macaca](https://macacajs.github.io/zh/): 面向多端的自动化测试工具，由阿里巴巴开源。  
- [Airtest](http://airtest.netease.com/): UI自动化测试工具，支持App和游戏，网易开源。  
- [SoloPi](https://github.com/alipay/SoloPi): Soloπ是一个无线化、非侵入式的Android自动化工具，公测版拥有录制回放、性能测试、一机多控三项主要功能，能为测试开发人员节省宝贵时间。  
- [Uiautomator2](https://github.com/openatx/uiautomator2): Python版Uiautomator封装，Android设备测试框架

#### Flutter App自动化
- [Flutter测试](https://doc.flutterchina.club/testing/): Flutter中文文档-测试 Flutter App

#### 鸿蒙App自动化
(TODO)

#### 微信小程序自动化
- [MiniTest](https://minitest.weixin.qq.com/#/): 属于小程序和小游戏的自动化测试框架


### 桌面客户端自动化
- [Pyautogui](https://pyautogui.readthedocs.io/en/latest/): 基于截图识别等桌面自动化框架
- [Atalon](https://www.katalon.com/): API，Web，移动端的自动化测试工具。  
- [Ranorex](https://www.ranorex.com/): 商业GUI自动化测试工具，支持桌面，Web，移动端。  
- [AutoIT](https://www.autoitscript.com/site/): 用类Basic脚本编写Windows桌面GUI自动化的工具。
- [QTP/UFT](https://en.wikipedia.org/wiki/HP_QuickTest_Professional) 商业GUI桌面，Web的自动化测试工具 

## 持续集成
- [Jenkins](https://www.jenkins.io/): 使用广泛的开源持续集成网站，拥有丰富的插件，支持应用定时打包、构建、自动化测试等
- [GitLab CI](https://docs.gitlab.com/ee/ci/): 开源GitLab平台的基于YAML配置的应用持续集成语法

## 测试开发

### IDE&编辑器
- [PyCharm](https://www.jetbrains.com/pycharm/): Jetbrains推出的Python开发工具，有社区免费版
- [IDEA](https://www.jetbrains.com/zh-cn/idea/): Jetbrains推出的Java开发工具，有社区免费版
- [Viual Studio Code](https://code.visualstudio.com/): 微软推出的代码编辑器，支持多种语言和各种插件
- [Zed](https://zed.dev/): 新一代支持协调编码的代码编辑器


### Python
- [Django](https://www.djangoproject.com/): Python全能Web开发框架
- [Flask](https://flask.palletsprojects.com/en/3.0.x/): Python微型Web开发框架
- [FastAPI](https://fastapi.tiangolo.com/): Python高性能Web接口开发框架
- [Sqlalchemy](https://www.sqlalchemy.org/): Python数据库操作ORM库

### Java
- [Spring Boot](https://spring.io/projects/spring-boot/)：易用的Java Web开发框架
- [Mybatis](https://mybatis.org/mybatis-3/zh_CN/index.html)：Java数据库操作框架

### Golang
- [Gin](https://github.com/gin-gonic/gin): 简单易用的的Golang Web开发框架
- [Gorm](https://github.com/go-gorm/gorm): Golang数据库操作ORM框架

### 前端
- [Vue](https://cn.vuejs.org/): 渐进式Web前端开发框架
- [Element UI](https://element.eleme.cn/#/zh-CN): 饿了么推出的Web前端组件库，支持Vue
- [React](https://react.dev/): Meta推出的前端开发框架
- [AntDesign](https://ant-design.antgroup.com/components/overview-cn)：阿里推出的Web前端组件库，支持React
- [TDesign](https://tdesign.tencent.com/): 腾讯推出的前端组件库，支持Vue，React等


## 其他

### 车载测试
(TODO)

### 大数据测试
- [Apache Hadoop](https://hadoop.apache.org/): 开源大数据计算框架
- [Apache Hive](https://hive.apache.org/): 开源大数据分布式容错数据仓库系统
- [Apache Spark](https://spark.apache.org/): 开源大数据实时计算统一分析引擎

### AI大模型测试
(TODO)

### 用例生成  
- [Graphwalker](https://github.com/GraphWalker): 基于模型的测试用例生成框架  
- [PICT](https://docs.microsoft.com/en-us/previous-versions/software-testing/cc150619(v=msdn.10)): 微软公司开发的pairwise testing的用例生成工具  

### AI辅助测试
- AI辅助用例生成 (TODO)
- AI辅助用例检查 (TODO)

  
## 参考

- [jumper2014/awesome-testing](https://github.com/jumper2014/awesome-testing)
- [TheJambo/awesome-testing](https://github.com/TheJambo/awesome-testing)]
- [atinfo/awesome-test-automation](https://github.com/atinfo/awesome-test-automation)