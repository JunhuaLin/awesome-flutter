# awesome-flutter
A curated list of awesome Flutter frameworks, libraries, software and resources



# 优秀文章

* [深入浅出 Flutter Framework](https://zxfcumtcs.github.io/2020/05/01/deepinto-flutter-widget/) - Flutter Framework系列文章，干货满满，分八篇
从widget、BuildOwner、Element、PaintingContext、Layout、PipelineOwner、RenderObject到自定义widget
* [字节跳动业务在 Flutter 轻量级引擎上的实践与优化](https://my.oschina.net/u/4180867/blog/5395182) - 介绍字节在flutter多引擎方面的研究，其中给到了多引擎内存共享解决方案，图片多引擎共享方案等
* [Flutter 上的内存泄漏监控](https://flutter.cn/community/tutorials/memory-leak-monitoring-on-flutter) - 本文将会带你实现一个 Flutter 可用的 LeakCanary，并讲述我是怎么用该工具检测出了 1.9.1 Framework 上的两个泄漏。



# 优秀库

## Pub管理

* [unpub](https://github.com/pd4d10/unpub) - Unpub 是一个自托管的企业私有 Dart Pub 服务器，具有一个简单的 Web 界面来搜索和查看包信息。


## 路由库

* [Flutter Boost](https://github.com/alibaba/flutter_boost) - 新一代Flutter-Native混合解决方案。 FlutterBoost是一个Flutter插件，它可以轻松地为现有原生应用程序提供Flutter混合集成方案。
* [fluro](https://github.com/lukepighetti/fluro) - 基于Navigater 1.0 api编写的路由库，最明亮、最时尚、最酷的 Flutter 路由器。
* [go_router](https://pub.dev/packages/go_router) - 官方路由框架，基于Navigater 2.0，Flutter 的声明式路由包，使用 Router API 提供方便的、基于 url 的 API，用于在不同屏幕之间导航。您可以定义 URL 模式、使用 URL 进行导航、处理深层链接以及许多其他与导航相关的场景。

## 状态管理

* [getx](https://github.com/jonataslaw/getx) - GetX 是一个超轻且强大的 Flutter 解决方案。它快速实用地结合了高性能状态管理、智能依赖注入和路由管理。
* [provider](https://github.com/rrousselGit/provider) - 对 InheritedWidget 组件的上层封装，使其更易用，更易复用。
* [riverpod](https://github.com/rrousselGit/riverpod) - A reactive caching and data-binding framework. [riverpod.dev](https://riverpod.dev) 。对provider优化。
* [flutter_redux](https://github.com/brianegan/flutter_redux) - A set of utilities that allow you to easily consume a Redux Store to build Flutter Widgets.

## UI库

* [PowerImage](https://github.com/alibaba/power_image) - 一个充分利用原生图片库能力、高扩展性的flutter图片库。
* [flutter_easy_refresh](https://github.com/xuelongqy/flutter_easy_refresh) - EasyRefresh很容易就能在Flutter应用上实现下拉刷新以及上拉加载操作，它支持几乎所有的Flutter滚动组件。它的功能与Android的SmartRefreshLayout很相似，同样也吸取了很多三方库的优点。EasyRefresh中集成了多种风格的Header和Footer，但是它并没有局限性，你可以很轻松的自定义。使用Flutter强大的动画，甚至随便一个简单的控件也可以完成。EasyRefresh的目标是为Flutter打造一个强大，稳定，成熟的下拉刷新框架。
* [flutter_smart_dialog](https://github.com/fluttercandies/flutter_smart_dialog) - Flutter中一个简洁，强大，侵入性极低的Dialog实现库。

## 功能库

* [Beike_AspectD](https://github.com/LianjiaTech/Beike_AspectD) - Beike_AspectD是一个dart面向切面库。闲鱼的AspectD为开发者提供了call/execute/inject三种方式对代码进行操作。除此之外，Beike_AspectD还提供了：Add语法支持为class添加方法；FieldGet语法支持更换变量获取；支持空安全。（null-safety下的分支）支持Flutter for Web；其他的一些问题修复.
* [floor](https://github.com/pinchbv/floor) - Flutter SQLite ORM插件，它带有内存中对象和数据库行之间的自动映射，同时仍然通过使用 SQL 提供对数据库的完全控制。
* [isar](https://github.com/isar/isar) - Flutter SQLite ORM插件，简单好用，功能强大的sql库，专为Flutter打造。

## WebView

* [flutter_inappwebview](https://github.com/pichillilorenzo/flutter_inappwebview) - Flutter WebView封装库，允许您添加内联 Web 视图、使用无头 Web 视图以及打开应用内浏览器窗口。功能完善，文档丰富，开箱即用。
* [webview_flutter](https://pub.dev/packages/webview_flutter) - flutter官方封装的WebView库，功能在不断完善，存在一些问题，提供原生能力，部分功能需要自己实现。

## 其他导航站

* [fluttergems](https://fluttergems.dev/) - Flutter热门插件使用排行。
