# Awesome JSON [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Awesome JSON 库和资源的精选列表。

受 [awesome](https://github.com/sindresorhus/awesome) 列表启发

* [Awesome JSON](#awesome-json)
  * [应用](#应用)
  * [二进制序列化](#二进制序列化)
  * [浏览器扩展](#浏览器扩展)
  * [命令行工具](#命令行工具)
  * [数据库](#数据库)
  * [数据集](#数据集)
  * [数据模型](#数据模型)
  * [数据生成](#数据生成)
  * [差异化](#差异化)
  * [编辑器](#编辑器)
  * [格式扩展](#格式扩展)
  * [前端组件](#前端组件)
  * [各语言编解码库](#各语言编解码库)
  * [验证器(Linters)](#验证器(Linters))
  * [在线工具](#在线工具)
  * [Schema规格](#schema规格)
  * [服务](#服务)
  * [超集](#超集)
  * [相关格式](#相关格式)
  * [资源](#资源)
  * [模板](#模板)
  * [测试](#测试)
  * [文本编辑器插件](#文本编辑器插件)
  * [转换](#转换)
  * [教程](#教程)
  * [查询](#查询)
  * [JSON Schema 前端组件](#json-schema-前端组件)
  * [JSON Schema 工具](#json-schema-工具)
  * [JSON Schema 资源](#json-schema-资源)
  * [JSON Schema 校验器](#json-schema-校验器)
  * [贡献](#贡献)

## 应用
**Mac系统**
* [Visual JSON](https://apps.apple.com/app/id488709442) ([github](https://github.com/youknowone/VisualJSON)) - Mac OS X上简单优雅的JSON查看器
* [JSONExport](https://github.com/Ahmed-Ali/JSONExport) - 将对象转换为当前支持的语言的类

## 二进制序列化
* [BSON](http://bsonspec.org/) - 二进制JSON.
* [MessagePack](https://msgpack.org/) - 一个极其高效的对象序列化库.
* [UBJSON](https://ubjson.org/) - 二进制 JSON 的通用兼容格式规范.
* [CBOR](https://tools.ietf.org/html/rfc7049) - 简洁的二进制对象表示.
* [PSON](https://github.com/dcodeIO/PSON) - 协议 JSON，超高效的二进制序列化格式.

## 浏览器扩展程序
**Chrome**
* [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa) ([github](https://github.com/callumlocke/json-formatter)) - 使 JSON 易于阅读(开源)
* [JSON Viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh) ([github](https://github.com/tulios/json-viewer)) - 它是一个用于打印 JSON 和 JSONP 的 Chrome 扩展.
* [JSON Browser](https://chrome.google.com/webstore/detail/json-browser/hngfgkmimoikmpohakflgadcajkfnoba) ([github](https://github.com/platy/json-browser/)) - 借助 JSON 模式浏览 JSON 网络.
* [JSON Finder](https://chrome.google.com/webstore/detail/json-finder/flhdcaebggmmpnnaljiajhihdfconkbj) ([github](https://github.com/rapee/jsonfinder)) - 像在 Finder 中一样浏览.
* [JSON Viewer Pro](https://chrome.google.com/webstore/detail/json-viewer-pro/eifflpmocdbdmepbjaopkkhbfmdgijcc) ([github](https://github.com/rbrahul/Awesome-JSON-Viewer) - 一个开源的 Chrome 扩展，用于通过语法高亮和折叠浏览 JSON，或作为可视化图表
* [Discoverable JSON](https://chrome.google.com/webstore/detail/json-manipulator-json-to/pcakbljjigdafljigcpbmjllkbhlncjg) ([github](https://github.com/noitcudni/discoverable-json)) - Gron 启发扩展。 将 JSON 文档转换为 javascript 表达式。 带有过滤、删除、查找和替换功能.

**Firefox**
* [JSONView](https://addons.mozilla.org/en-US/firefox/addon/jsonview/) ([github](https://github.com/bhollis/jsonview)) - 在浏览器中查看 JSON 文档.

**Safari**
* [JSONAce](https://apps.apple.com/us/story/id1377753262?id=com.acrogenesis.jsonace-56Q494QF3LL) ([github](https://github.com/acrogenesis/JSONAce)) - 在 Web 浏览器中使用使用 ACE 编辑器查看格式和语法高亮的JSON.
* [JSONView](https://apps.apple.com/us/story/id1377753262?id=com.acrogenesis.jsonview-56Q494QF3L) ([github](https://github.com/acrogenesis/jsonview-safari)) - 在 Web 浏览器中查看格式和语法高亮的JSON的FireFox扩展的Safari版本

## 命令行工具
* [fx](https://github.com/antonmedv/fx) - 交互式终端工具.
* [jo](https://github.com/jpmens/jo) - 一个创建 JSON 对象的小工具
* [jsoncat](https://github.com/pantuza/jsoncat) - 在终端中的漂亮地打印带有颜色和可以调整标签大小的Json.
* [jq](http://stedolan.github.io/jq/) - 轻量级、灵活的命令行 JSON 处理器.
* [json](http://trentm.com/json/) - 用于在 Unix 命令行上让JSON优雅显示 的“json”命令.
* [jshon](http://kmkeen.com/jshon/) - 为在 shell 中提供最大便利而设计的解析器.
* [jarg](http://jdp.github.io/jarg/) - shell 中的简写 JSON 和表单编码语法.
* [jsawk](https://github.com/micha/jsawk) - JSON版awk.
* [json-dotenv](https://github.com/decryptus/json-dotenv) - 以 json 格式操作和提取 envfiles.
* [gron](https://github.com/tomnomnom/gron) - 离散分配json,使其方便grep处理.
* [jid](https://github.com/simeji/jid) - 增量挖掘器. 使用过滤查询（如 jq）以交互方式向下钻取 JSON.
* [jiq](https://github.com/fiatjaf/jiq) - 它是使用`jq`的`jid` . 您可以使用 `jq` 过滤查询以交互方式向下钻取。
* [jv](https://github.com/maxzender/jv) - jv（jsonviewer）帮助您查看 JSON。.
* [jl](https://github.com/chrisdone/jl) - jl（“JSON lambda”）是一种用于查询和操作 JSON 的小型函数式语言。
* [oj](https://github.com/ohler55/ojg) - 快速灵活的命令行 JSON 处理器.
* [visidata](https://github.com/saulpw/visidata) - 一个类似终端电子表格的工具，用于交互式探索数据.

## 数据库
* [MongoDB](https://www.mongodb.com/) - 开源文档数据库和领先的 NoSQL 数据库.
* [RethinkDB](https://rethinkdb.com/) - 一个开源的分布式文档数据库，具有令人愉悦且强大的查询语言.
* [EJDB](https://github.com/Softmotions/ejdb) - 在 MIT 许可下发布的嵌入式 JSON 数据库引擎. (C)
* [lowdb](https://github.com/typicode/lowdb) -基于 lodash API 构建的平面文件数据库. (Javascript)
* [Lawnchair](https://github.com/brianleroux/lawnchair) - 轻量级客户端文档存储. (Javascript)
* [JSON ODM](https://github.com/konsultaner/jsonOdm) - 在服务器或浏览器中使用 JavaScript 的对象文档映射器. (Javascript)
* [JSON Server](https://github.com/typicode/json-server) - 在 30 秒内获得零编码的完整的假的 REST API.
* [Kinto](https://github.com/Kinto/kinto) - 具有同步和共享能力的轻量级 JSON 存储服务.
* [CouchDB](https://couchdb.apache.org/) - 无缝多主同步，可从大数据扩展到移动，具有直观的 HTTP/JSON API，专为可靠性而设计.
* [RxDB](https://github.com/pubkey/rxdb) - 具有 JSON-Schema、mango-Query 和 CouchDB-sync 的事件驱动型 JSON 数据库. (Javascript)
* [JSONlite](https://github.com/nodesocket/jsonlite) - 一个简单、自包含、无服务器、零配置、json 文档存储. (Bash)

## 数据集
* [country.io](http://country.io/data/) - 各种国家JSON格式相关数据集，如 公司货币、国家代码、名称等
* [countries](https://github.com/mledoze/countries) - 世界国家.
* [vat-rates](http://jsonvat.com/) - 所有欧盟国家的增值税税率.
* [MTG JSON](https://mtgjson.com/) - 最新的万智牌卡数据.
* [Heartstone JSON](https://hearthstonejson.com/) - 最新炉石卡牌数据.
* [getCountries()](https://peric.github.io/GetCountries/) - 自定义国家数据生成器.

## 数据模型
* [JSONModel](https://github.com/jsonmodel/jsonmodel) - 神奇的数据建模框架. (Objective-C)

## 数据生成
* [jsonymize](https://github.com/cameronhunter/jsonymize) - 从标准输入读取数据，匿名化，然后写入标准输出.
* [dyson](https://github.com/webpro/dyson) - 用于动态、假 JSON 的服务器. (node.js)

## 差异化
* [JSONPatch](http://jsonpatch.com/) - 描述文档更改的格式.
* [JSON-Patch](https://github.com/Starcounter-Jack/JSON-Patch) - JSON-Patch 标准 (RFC 6902) 的精益和平均 Javascript 实现. (Javascript)
* [jiff](https://github.com/cujojs/jiff) - 基于 rfc6902 的 JSON 补丁和差异. (Javascript)
* [json-patch-php](https://github.com/mikemccabe/json-patch-php) - JSON补丁的实现（IETF RFC 6902） (PHP)
* [dffptch](https://github.com/paldepind/dffptch) - 使用紧凑的差异格式进行差异和修补的微库. (Javascript)
* [jsondiffpatch](https://github.com/benjamine/jsondiffpatch) - JavaScript 对象的差异和补丁. (Javascript)

## 编辑器
* [FrontAid CMS](https://frontaid.io/) - 支持任意数据模型结构的内容管理系统.
* [JSONEdit](http://mb21.github.io/JSONedit/) - 作为 AngularJS 指令构建的用户友好的可视化编辑器。

## 格式扩展
* [GeoJSON](https://geojson.org/) - 一种地理空间数据交换格式.
* [JSON-LD](https://json-ld.org/) - 一种轻量级的关联数据格式.
* [JSON-RPC](https://www.jsonrpc.org/) - 一种无状态、轻量级的远程过程调用 (RPC) 协议.
* [JSONP](https://en.wikipedia.org/wiki/JSONP) - 使用 JSON-P/JSONP 更安全的跨域 Ajax.
* [JsonML](http://www.jsonml.org/) - 一种将基于 XML 的标记作为 JSON 传输的紧凑格式，可以无损地将其转换回其原始形式.
* [JSON5](https://json5.org/) - 一个旨在让人类更容易手动编写和维护的扩展.
* [JSON6](https://github.com/d3x0r/json6) - 用于人类的 JSON (ES6).
* [JSON 1.1/JSONX](https://json-next.github.io/) - 具有人类格式扩展的进化版 1.1，包括。注释、不带引号和多行字符串、可选和尾随逗号等等。
* [JSON Resume](https://jsonresume.org/) - 创建简历标准的开源倡议。
* [JSON Web Tokens](https://jwt.io/) - 一种紧凑的 URL 安全方式，表示要在两方之间传输的声明.
* [JSON API](https://jsonapi.org/) - 构建 API 的标准.
* [Collection+JSON](http://amundsen.com/media-types/collection/) - 一种读/写超媒体类型，旨在支持简单集合的管理和查询.
* [hal-json](https://stateless.group/hal_specification.html) - 一组用于在 JSON 或 XML 中表示超链接的约定.
* [JSON Activity Streams](https://activitystrea.ms/) - 一种用于联合网络社交活动的格式.
* [JSON-stat](https://github.com/jsonstat/jsonstat) - 用于数据传播的简单轻量级格式.
* [/contribute.json](https://www.contributejson.org/) - 使开源贡献信息更易于跨项目访问.
* [JSON Table Schema](https://frictionlessdata.io/table-schema/) - 表格数据的简单模式
* [NDJSON](http://ndjson.org/) （换行分隔的 JSON）- 在流协议中分隔 JSON 的标准。
* [survey.js](http://surveyjs.org/) - 基于 JSON 的调查库.
* [JSON Meta Application Protocol (JMAP)](https://jmap.io/) - 一种有效同步基于 JSON 的数据对象的协议，支持推送和带外二进制数据上传/下载.
* [J<sub>ack</sub>SON: JSON secret keeper](https://github.com/r0hi7/jackson) - 在配置文件中存储秘密的 JSONic 方式。

## 前端组件
* [JSON editor jQuery plugin](https://github.com/DavidDurman/FlexiJsonEditor) - 您的网络应用程序/页面的组件. (jQuery)
* [jqTree](http://mbraak.github.io/jqTree/) - 用于在 html 中显示树结构的小部件. (jQuery)
* [jsTree](https://www.jstree.com/docs/json/) - jquery 插件，提供交互式树. (jQuery)
* [Dynatable.js](https://github.com/alfajango/jquery-dynatable) - 一个有趣的、语义的、HTML5+JSON 的交互式表格插件. (jQuery)
* [JSON Formatter](https://github.com/mohsen1/json-formatter) - HTML 中可折叠 JSON 的 Angular 指令. (AngularJS)
* [react-jsonschema-form](https://rjsf-team.github.io/react-jsonschema-form/) - 用于从 JSON Schema 构建 Web 表单的 React 组件. (React)
* [ngx-formly](https://github.com/ngx-formly/ngx-formly) - JSON 驱动/Angular 的动态表单

## 各语言编解码库
**C**
* [Jansson](https://digip.org/jansson/) - 用于编码、解码和操作数据的 C 库.
* [jsmn](https://zserge.com/jsmn.html) - 一个简约的C语言解析器。它可以很容易地集成到资源有限的项目或嵌入式系统中.
* [ojc](https://github.com/ohler55/ojc) - 一个快速的 JSON 解析器.

**C++**
* [ArduinoJson](https://github.com/bblanchon/ArduinoJson) - 一个高效的嵌入式系统库.
* [JSON++](https://github.com/tunnuz/json) - 用于 C++11 的自包含 Flex/Bison 解析器.
* [json11](https://github.com/dropbox/json11) - C++11 的小型库.
* [Nlohmann JSON](https://github.com/nlohmann/json) - 一个只有 C++11 标头的类.
* [RapidJSON](https://github.com/Tencent/rapidjson) - 用于 C++ 的快速 JSON 解析器/生成器，具有 SAX/DOM 样式 API
* [simdjson](https://github.com/simdjson/simdjson) - 每秒解析千兆字节的 JSON。

**Clojure**
* [data.json](https://github.com/clojure/data.json) - 解析器/生成器到/从 Clojure 数据结构.

**Fortran**
* [JSON-Fortran](https://github.com/jacobwilliams/json-fortran) - 用于编写、读取和操作 JSON 文件和数据结构的 Fortran 库.

**Go**
* [ojg](https://github.com/ohler55/ojg) - 一套高性能的 JSON 处理和生成工具.

**Haskell**
* [aeson-qq](https://github.com/sol/aeson-qq) - Haskell 的 JSON 准引用器.
* [json-schema](http://hackage.haskell.org/package/json-schema) - Haskell 的 JSON 模式库
* [hjsonschema](http://hackage.haskell.org/package/hjsonschema) - Haskell 的 JSON Schema Draft 4 库

**Java**
* [JSON-java](https://github.com/stleary/JSON-java) - 参考实现.
* [fastjson](https://github.com/alibaba/fastjson) - 阿里开源的json库
* [Gson](https://github.com/google/gson) - 一个 Java 库，用于将 JSON 转换为 Java 对象，反之亦然.
* [Jackson](https://github.com/FasterXML/jackson) - 用于处理 JSON 数据格式的多用途 Java 库.
* [moshi](https://github.com/square/moshi) - 适用于 Android 和 Java 的现代 JSON 库.
* [essential-json](https://github.com/arkanovicz/essential-json) - 一个用于序列化、解析和操作的轻量级 Java 库，具有干净且精确的 API.
* [dsl-json](https://github.com/ngs-doo/dsl-json) - 一个非常快速的流式 JSON 库。 对字节数组进行操作.
* [mjson](https://github.com/bolerio/mjson) - 用于 Java 的精益 JSON 库，具有紧凑、优雅的 API.

**Javascript**
* [JSON-js](https://github.com/douglascrockford/JSON-js) - JavaScript 中的 JSON.
* [JSON 3](https://bestiejs.github.io/json3/) - 现代实现.
* [oboe.js](http://oboejs.com/) - 一种流式方法，通过在响应完成之前提供解析的对象来加速 Web 应用程序.

**Objective-C**
* [JSONKit](https://github.com/johnezang/JSONKit) - Objective-C 库.
* [SBJson](https://github.com/SBJson/SBJson) - 解析一个或多个数据块.

**Perl**
* [JSON::Tiny](https://github.com/daoswald/JSON-Tiny) - 用于以简约方式编码和解码 JSON 的 Perl 模块.

**PL/SQL**
* [PL/JSON](https://github.com/pljson/pljson) - 用 PL/SQL 编写的通用 JSON 对象.

**PHP**
* [Webmozart JSON](https://github.com/webmozart/json) - 支持模式验证的强大解码器/编码器.

**Python**
* [simplejson](https://github.com/simplejson/simplejson) - 一个简单、快速、可扩展的编码器/解码器
* [jsonpickle](http://jsonpickle.github.io/) - 用于序列化任意对象图的库.
* [metamagic.json](https://pypi.org/project/metamagic.json/) - JSON 编码器的超快速 Python 3 实现.

**Ruby**
* [oj](https://github.com/ohler55/oj) - 作为 Ruby gem 的快速 JSON 解析器和对象编组器。
* [MultiJSON](https://github.com/intridea/multi_json) - 用于 JSON 处理的通用可交换后端.

**React**
* [json2react](https://github.com/txgruppi/json2react) - 使用 JSON 创建 React 无状态组件.

**.NET**
* [jsonfx](https://github.com/jsonfx/jsonfx) - .NET 的序列化框架。
* [jsonapi-consumer](https://github.com/OKTAYKIR/jsonapi-consumer) - 使用基于 JSONAPI 的 API 的客户端框架 [JSON API standard](https://jsonapi.org).

**Scala**
* [spray-json](https://github.com/spray/spray-json) - Scala 中的轻量级、干净和简单的实现.
* [circe](https://github.com/circe/circe) - Scala 的另一个 JSON 库.
* [scala-jsonapi](https://github.com/scala-jsonapi/scala-jsonapi) - 用于将 JSON:API 规范与 Play、Spray 和/或 Circe 后端集成的支持库.
* [jsoniter-scala](https://github.com/plokhotnyuk/jsoniter-scala) - 用于编译时生成超快速 JSON 编解码器的 Scala 宏.

**Swift**
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - 在 Swift 中处理数据的更好方法.

## 验证器(Linters)
* [jsonlint](https://github.com/zaach/jsonlint) - 带有 CLI 的解析器和验证器. (Javascript)
* [JSON Lint](https://github.com/Seldaek/jsonlint) - PHP 验证器. (PHP)

## 在线工具
* [JSONLint](https://jsonlint.com/) - JSON 验证器.
* [JSONCompare](https://jsoncompare.com/) - JSON Linter 的高级版本.
* [JSONMate](https://www.jsonmate.com/) - JSON 编辑器、检查器和美化器.
* [JSON Editor online](http://jsoneditoronline.org/) - 用于查看、编辑和格式化的基于 Web 的工具.
* [Collapsible JSON Formatter](http://www.bodurov.com/JsonFormatter/) - 原始代码的格式化程序和着色器.
* [JSON Formatter and Validator](https://jsonformatter.curiousconcept.com/) - 帮助调试的格式化程序.
* [JSON Generator](https://www.json-generator.com/) - 生成随机数据的工具.
* [FakeJSON](https://fakejson.com/) - Web API 为您的应用程序快速生成假数据.
* [JSON to CSV](https://konklone.io/json/) - 一个免费的浏览器内 JSON 到 CSV 转换器.
* [CSV to JSON](https://mango-is.com/tools/csv-to-json/) - 简单、隐私友好和离线优先的在线 csv 到 json 转换器
* [json2csharp](https://json2csharp.com/) - 从 json 字符串或 url 生成 c# 类。
* [JSON Utils](http://jsonutils.com/) - 用于从 JSON 生成 C#、VB.Net 和 Javascript 类的站点。
* [geojson.io](http://geojson.io/) - 简单编辑 GeoJSON 地图数据.
* [jq play](https://jqplay.org/) - jq 的游乐场.
* [json2yaml](https://www.json2yaml.com/) - 在线将 JSON 转换为 YAML.
* [JSON Selector Generator](http://jsonselector.com/) - 用于生成要访问的选择器的简单 GUI.
* [JSON.fr](https://www.json.fr/) - 完全客户端验证器和格式化程序.
* [ObjGen](http://www.objgen.com/json) - 在线直播 JSON 生成器.
* [JsonStub](https://jsonstub.com/) - 在线 JSON 伪造者.
* [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - 用于测试和原型设计的假在线 REST API.
* [Extends Class](https://extendsclass.com/json-diff.html) - 比较两个文件的差异工具.
* [JSON Schema Validate API](https://assertible.com/json-schema-validation) - 一个简单免费的 JSON Schema Validation API.
* [JSONLog](https://jsonlog.io/docs) - 从任何客户端记录和可视化 JSON.
* [JSONPerf](https://jsonperf.com) - 可视化、公正和最新的 JSON 性能基准.

## Schema规格
* [JSON Schema](http://json-schema.org/) - 一种基于 JSON 的格式，用于定义 JSON 数据的结构.
* [Itemscript](https://code.google.com/archive/p/itemscript/) - 验证和指定值的语言.
* [Kwalify](http://www.kuwata-lab.com/kwalify/) - 解析器、模式验证器和数据绑定工具
* [Rx](http://rx.codesimply.com/) - 简单、可扩展的模式。

## 服务
* [Exchange Rate API](https://www.exchangerate-api.com) - 一个简单免费的货币汇率数据API.
* [ipinfo.io](https://ipinfo.io) - JSON IP 和 GeoIP REST API.
* [JSONProxy](https://github.com/afeld/jsonp) - 简单的 HTTP 代理，支持对任何 JSON API 的跨域请求。.
* [Myjson](http://myjson.com/) -一个简单的 Web 或移动应用商店.
* [Telize](http://www.telize.com/) - JSON IP 和 GeoIP REST API.
* [jsonpad](https://jsonpad.io/) - 一个简单的 JSON 存储平台.

## 超集
* [YAML](https://yaml.org) - 适用于所有编程语言的人性化数据序列化标准
* [HanSON](https://github.com/timjansen/hanson) - 用于人类的 JSON - 带有不带引号的标识符、多行字符串和注释。.
* [μson](https://github.com/burningtree/uson) (uson) - JSON 的简写。.
* [HOCON](https://github.com/lightbend/config/blob/master/HOCON.md) - 人工优化的配置对象表示法
* [ASON](https://github.com/sadmac7000/libason) - 语义上完整的 JSON 超集（草案）
* [TOML](https://github.com/toml-lang/toml) - 一种最小的配置文件格式，由于明显的语义而易于阅读。
* [HCL](https://github.com/hashicorp/hcl) - 一种对人机友好的结构化配置语言。

## 教程
* [JSON官网介绍](http://json.org/)
* [JSON教程](https://www.w3resource.com/JSON/introduction.php) - 关于 JavaScript 对象表示法 (JSON) 的介绍性教程.
* [JSON - Rosetta Code](http://rosettacode.org/wiki/JSON) - 不同语言的基本操作(目前有 57 种语言).
* [什么是JSON,怎么使用](https://ilovecoding.org/lessons/json-what-is-json-and-how-to-use-it) - 初学者视频教程.
* [jq Primer: Munging JSON Data](https://andrew.gibiansky.com/) - jq 如何像传统的 Unix 工具一样有效地处理 JSON 文件.

## 相关格式
* [AXON](https://github.com/intellimath/pyaxon) - 一种简单的基于文本的格式，用于交换对象、文档和数据。 它试图结合 JSON、XML 和 YAML 的优点。.
* [CSON](https://github.com/bevry/cson) - CoffeeScript-Object-Notation. CoffeeScript 对象的 JSON.
* [MSON](https://github.com/apiaryio/mson) - 与描述 JSON 和 JSON Schema 兼容的 Markdown 语法.
* [ArchieML](http://archieml.org/) - 针对人类可写性优化的结构化文本格式.

## 资源
* [Type-o-rama](https://github.com/stereobooster/type-o-rama) - JS 类型系统的互移植性，不同 JS 类型系统的比较和它们之间的转换.
* [Awesome jq](https://github.com/fiatjaf/awesome-jq) - 很棒的 jq 工具和资源的精选列表.

## 模板
* [Jsonnet](https://jsonnet.org/) - 一种特定于域的配置语言，可帮助您定义 JSON 数据。
* [rabl](https://github.com/nesquena/rabl) - 具有 json、bson、xml、plist 和 msgpack 支持的通用 ruby 模板. (Ruby)
* [json2html](http://json2html.com/) - 带有 jQuery 和 Node.js 包装器的 HTML 模板库。 (Javascript)

## 测试
* [JSON Test](http://www.jsontest.com/) - 使用 JavaScript 对象表示法 (JSON) 的服务测试平台。
* [JSONassert](https://github.com/skyscreamer/JSONassert) - 用更少的代码编写 JSON 单元测试。 非常适合测试 REST 接口。 （爪哇）
* [JsonUnit](https://github.com/lukas-krecan/JsonUnit) - 在单元测试中简化 JSON 比较的库。 它受到 XmlUnit 的强烈启发。
* [JSON Parsing Test Suite](https://github.com/nst/JSONTestSuite) - 一个非常完整的测试套件和验证框架。

## 文本编辑器插件
**Emacs**
* [JSON Reformat](https://github.com/gongo/json-reformat) - 重新格式化工具.

**Vim**
* [vim-json](https://github.com/elzr/vim-json) -  Vim 更好的 JSON：关键字与值的明显突出显示，JSON 特定（非 JS）警告，引号隐藏 Pathogen-friendly.

## 转换
* [json-sharp](https://github.com/globocom/json-sharp) - 处理纯 JSON 对象操作的 Javascript 工具。 (Javascript)
* [json2json](https://github.com/joelvh/json2json) - 将结构从一个转换（重新格式化）到另一个。 (Javascript)
* [trans](https://github.com/gabesoft/trans) - 终极对象转换器。 (Javascript)
* [osmtogeojson](https://github.com/tyrasd/osmtogeojson) - 将 OSM 数据转换为 GeoJSON。 (Javascript)
* [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - 快速 XML 到 JSON，反之亦然 javascript/JSON 转换。
* [x2js](https://github.com/abdolence/x2js) - XML 到 JSON，反之亦然 javascript 转换函数。 (Javascript)
* [JSONC](https://github.com/tcorral/JSONC) - JSON 压缩器和解压缩器。 (Javascript)
* [JsonMapper](https://github.com/cweiske/jsonmapper) - 将嵌套结构映射到 PHP 类 (PHP)
* [SassyJSON](https://github.com/KittyGiraudel/SassyJSON) - Sass 驱动的 API。 （Sass）
* [json.human.js](http://marianoguerra.github.io/json.human.js/) - 一个小型库，用于将 JSON 对象转换为人类可读的 HTML 表示，易于为不同目的设置样式。
* [JSONtoFoundation](https://github.com/fmscode/JSONtoFoundation) - 将 JSON 对象转换为可用于 Cocoa/Cocoa Touch 开发的 Foundation 对象的 OS X 实用程序。 （Swift）
* [fanci](https://github.com/liip/fanci) - 基于模板提取、重命名和转换 JSON。 (node.js)
* [Pinch](https://github.com/Baggz/Pinch) - JavaScript 对象的 String.replace。 (Javascript)
* [deepjson](http://deepjson.jacoborus.codes/) - 加载大型 json 配置文件的更好方法。 (node.js)
* [jsontl](https://github.com/DoublePrecisionSoftware/jsontl) - 允许使用基于 JSON 的转换语言进行转换。 (node.js)
* [json-transforms](https://github.com/ColinEberhardt/json-transforms) - 一种递归、模式匹配、转换 JSON 结构的方法。
* [normalizr](https://github.com/paularmstrong/normalizr) - 根据模式规范嵌套的 JSON。 (Javascript)
* [JSON-populate](https://github.com/eiriklv/json-populate) - 使用无限递归循环引用填充 JSON 数据的工具。有点像 Falcor，但对于纯 JSON。
* [CircularJSON](https://github.com/WebReflection/circular-json) - JSON 不处理循环引用。现在确实如此。
* [Sawmill](https://github.com/logzio/sawmill) - JSON 转换库 (Java)
* [nimnjs](https://github.com/nimndata/nimnjs) - JSON 到 nimn 双向转换器。
* [stylops](https://github.com/cruel-intentions/stylops) - CSS 子集到 JSON 的转换。 (node.js)

## 查询
* [dasel](https://github.com/tomwright/dasel) - 从命令行使用选择器查询和更新数据结构。与 [jq](https://github.com/stedolan/jq) / [yq](https://github.com/kislyuk/yq) 类似，但支持 JSON、YAML、TOML 和 XML，运行时依赖性为零。
* [JMESPath](https://jmespath.org/) - JSON 的查询语言。
* [JSON Mask](https://github.com/nemtsov/json-mask) - 用于选择 JS 对象的特定部分并隐藏其余部分的微小语言和引擎。 (Javascript)
* [JSONiq](https://www.jsoniq.org/) - JSON 查询语言。
* [ObjectPath](http://objectpath.org/) - 用于半结构化数据的敏捷查询语言。 （Python）
* [DefiantJS](https://www.defiantjs.com/) - 使用 XPath 表达式进行闪电般的快速搜索，并使用 XSL 进行转换。 (Javascript)
* [JSONSelect](https://github.com/lloyd/JSONSelect) - 类似 CSS 的选择器。 (Javascript)
* [JSONPath](https://goessner.net/articles/JsonPath/) - XPath 实现。 (Javascript/PHP)
* [searchjs](https://github.com/deitch/searchjs) - 基于 json SQL 语言的过滤库。
* [json-rel](https://github.com/slurmulon/json-where) - JSON 中的透明引用。
* [JSONata](https://jsonata.org/) - Node-RED 中使用的查询和转换语言，支持函数表达式。

## JSON Schema 前端组件
* [JSON 编辑器](https://github.com/jdorn/json-editor) - 基于 JSON 模式的编辑器。 (jQuery)
* [angular-schema-form](https://github.com/json-schema-form/angular-schema-form) - 生成表单。 (AngularJS)
* [JSON Schema View](https://github.com/mohsen1/json-schema-view) - 用于在 HTML (AngularJS) 中呈现 JSON Schema 的 AngularJS 指令
* [Angular JSON Schema Form](https://github.com/mohsen1/angular-json-schema-form) - 使用 JSON Schema 制作表单的 Angular 指令。 (AngularJS)
* [AlpacaJS](http://www.alpacajs.org) - 在 Bootstrap、jQuery Mobile、jQuery UI 和 HTML (jQuery) 之上生成 JSON Schema 驱动的表单

## JSON Schema 工具
* [prmd](https://github.com/interagent/prmd) - HTTP API 的工具和文档生成。
* [generate-schema](https://github.com/Nijikokun/generate-schema) - 毫不费力地将您的 JSON 对象转换为 JSON Schema、Mongoose Schema 或通用模板，以实现快速文档/新贵。
* [Docson](https://github.com/lbovet/docson) - 你的类型的文档。
* [Orderly JSON](https://github.com/lloyd/orderly) - 用于描述编译成 JSONSchema 的 JSON 的文本格式。
* [jsonschema2pojo](https://github.com/joelittlejohn/jsonschema2pojo) - 生成 Java 类型并注释这些类型以与 Jackson 1.x 或 2.x、Gson 等进行数据绑定。
* [Matic](https://github.com/mattyod/matic) - 生成 HTML 文档的构建工具。
* [JSON Schema + Faker](https://github.com/json-schema-faker/json-schema-faker) - 伪造你的模式。
* [DLL.js](https://github.com/moll/js-ddl) - 从 PostgreSQL 或 SQLite3 获取 JSON 模式。
* [JSONSchema.net](https://jsonschema.net//) - 来自 JSON 对象的 JSON Schema 生成器。
* [js-schema](https://github.com/molnarg/js-schema) - 一种在 JavaScript 中描述对象模式的新方法。它具有简洁的语法，并且能够序列化到/从流行的 JSON Schema 格式。
* [aptos](https://github.com/pennsignals/aptos) - 一种使用 JSON Schema 验证数据并将 JSON Schema 文档转换为不同数据交换格式的工具。
* [JSON Schema $Ref Parser](https://github.com/APIDevTools/json-schema-ref-parser) - 解析、解析和取消引用 JSON Schema $ref 指针

## JSON Schema 资源
* [了解 JSON Schema](https://spacetelescope.github.io/understanding-json-schema/) - 一个旨在为 JSON 模式提供更易于访问的文档的网站。
* [JSON Schema Store](https://schemastore.org/json/) - 流行模式的集合。
* [使用 JSON Schema](http://usingjsonschema.com/) - Book 和 GitHub 项目，展示如何将 JSON Schema 用于各种任务和不同的编程环境。

## JSON Schema 校验器
**Javascript和Node.js**
* [json-schema-benchmark](https://github.com/ebdrup/json-schema-benchmark) - Node.js 验证器的性能基准。
* [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - 一个使用代码生成速度极快的验证器。
* [jsen](https://github.com/bugventure/jsen) - 为速度而构建的验证器。
* [themis](https://github.com/playlyfe/themis) - 一个超快的验证器。
* [jsck](https://github.com/pandastrike/jsck) - JSON Schema 编译检查。
* [z-schema](https://github.com/zaggino/z-schema) - 用 JavaScript 为 NodeJS 和浏览器编写的验证器。
* [jjv](https://github.com/acornejo/jjv) - 用于模式验证的 Javascript 库。
* [request-validator](https://github.com/bugventure/request-validator) - 用于 express 和 connect 的灵活请求验证器中间件。
* [tv4](https://github.com/geraintluff/tv4) - 微型验证器。
* [ajv](https://github.com/ajv-validator/ajv) - 最快的验证器。 支持 v5/6 提案。

**Java和Kotlin**
* [Medeia Validator](https://github.com/worldturner/medeia-validator) - 用 Kotlin 编写的兼容 (draft-04/06/07) 和快速流式验证器

**PHP**
* [PHP 的 JSON 模式](https://github.com/justinrainbow/json-schema) - JSON 模式的 PHP 实现。
* [JSON Guard](https://json-guard.thephpleague.com) - JSON Schema Draft 4 的验证器。

**Python**
* [jsonschema](https://github.com/Julian/jsonschema) - jsonschema 的 Python 实现。
* [JSON Schema Toolkit](https://github.com/petrounias/json-schema-toolkit) - JSON 模式（递归字段映射）的编程构建，带有验证、Django JSON 字段和本机 PostgreSQL JSON 类型约束。

* **Ruby**
* [Ruby JSON Schema Validator](https://github.com/ruby-json-schema/json-schema) - 针对符合 JSON Schema Draft 4 的 JSON 模式进行验证.

## 贡献
欢迎投稿！ 首先阅读[贡献指南](CONTRIBUTING.md)。

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
