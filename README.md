# Flutter Deer

[CSDN blog star event. WeChat or QQ open, five tickets a day, thank you for your support！](http://m234140.nofollow.ax.mvote.cn/opage/68ea3676-e445-1ca2-162d-3e2915feb14b.html)

<img src="preview/logo.jpg"/>
This project is an exercise project for individuals to learn Flutter.

By setting, modifying, combining built-in parts and customizing to achieve specific design effects, to meet the needs of daily development.

The design drawings of this project can be found in the design catalog. You can practice with the designed drawings provided by me. All implementations are only personal learning and understanding. If there is a better implementation plan, please exchange.

Preview

| ![](./preview/Screenshot_1.png)    |  ![](./preview/Screenshot_2.png)    | ![](./preview/Screenshot_3.png)   |  ![](./preview/Screenshot_4.png)   |
| :--------------------------------: | :---------------------------------: | :-------------------------------: | :-------------------------------:  |
| ![](./preview/Screenshot_5.png)    |  ![](./preview/Screenshot_6.png)    | ![](./preview/Screenshot_7.png)   |  ![](./preview/Screenshot_8.png)   |
| ![](./preview/Screenshot_9.png)    |  ![](./preview/Screenshot_10.png)   | ![](./preview/Screenshot_11.png)  |  ![](./preview/Screenshot_12.png)  |
| ![](./preview/Screenshot_13.png)   |  ![](./preview/Screenshot_14.png)   | ![](./preview/Screenshot_15.png)  |  ![](./preview/Screenshot_17.png)  |
| ![](./preview/Screenshot_18.png)   |  ![](./preview/Screenshot_19.png)   | ![](./preview/Screenshot_20.png)  |  ![](./preview/Screenshot_21.png)  |
| ![](./preview/Screenshot_22.jpg)   |  ![](./preview/Screenshot_23.jpg)   | ![](./preview/Screenshot_24.jpg)  |  ![](./preview/Screenshot_25.jpg)  |
| ![](./preview/Screenshot_26.jpg)   |  ![](./preview/Screenshot_27.jpg)   |  |  |

** If you think it's okay, come to Star and Fork to support it! Questions are welcome to mention Issue. **

## Implementing content

* mvp mode
* Use `provider` (version 4.x) for state management
* Based on `dio` (3.x version) network request encapsulation
* Complete integration testing
* Supports dark mode
* Use `Sliver` series components to achieve complex scrolling effects
* Use Gaode map to locate the address
* Processing packaging of input boxes and other components
* Pull down to refresh + pull up to load more
* Apply check for updates
* PopupWindow
* Scan code function (barcode_scan plugin)
* Easy transition animation
* Slide to delete
* City selection
* Similar to the three-tier linkage of Jingdong's choice city
* Various custom Dialogs
* List head ceiling
* Password input keyboard
* Verification code input box
* Custom simple calendar
* Graph and [pie chart] (https://dartpad.cn/d06f8f737d6eb2d87978eb2d14b87864)
* Modular routing management
* More details optimization

Specific download experience:

Android version installation package: [click to download] (https://www.pgyer.com/gYXj), installation password: `111111`.

iOS needs to download the code to run by itself.

## Project running environment

[![Build Status](https://github.com/simplezhli/flutter_deer/workflows/flutter_deer%20drive/badge.svg?branch=master)](https://github.com/simplezhli/flutter_deer/actions?query=workflow%3A%22flutter_deer+driver%22+branch%3Amaster)

    1. Flutter version 1.12.13+hotfix.7
     
    2. Dart version 2.7.0

## 注意事项

- `debug`模式下会有部分卡顿现象，这属于正常现象。良好的体验需要打`release` 包。
    iOS可以执行命令`flutter build ios` 以创建`release`版本。
    Android可以执行命令`flutter build apk` 以创建`release`版本。

- 由于部分插件的原因，本项目在web上支持不完善（主要为功能方面，UI问题不大）。有兴趣的可自行运行体验。
        
- 因为页面有点多，一开始可能会导致部分页面无法找到。(可以执行集成测试命令`flutter drive --target=test_driver/driver.dart` 查看功能演示)

- 我在代码中有添加设计图的相对路径，可以搜索或查找到对应页面，希望对你有帮助。

- 该插件3.0+版本已不适用本项目。~~FlutterJsonBeanFactory插件使用可以查看[这篇文章](https://www.jianshu.com/p/e909f3f936d6)。~~
    
## 使用到的三方库

| 库                         | 功能             |
| -------------------------- | --------------- |
| [dio](https://github.com/flutterchina/dio)                            | **网络库**       |
| [provider](https://github.com/rrousselGit/provider)                   | **状态管理**     |
| [flutter_2d_amap](https://github.com/simplezhli/flutter_2d_amap)      | **高德2D地图**   |
| [cached_network_image](https://github.com/renefloor/flutter_cached_network_image)       | **图片加载**       |
| [fluro](https://github.com/theyakka/fluro)                            | **路由管理**     |
| [flutter_oktoast](https://github.com/OpenFlutter/flutter_oktoast)     | **Toast**        |
| [common_utils](https://github.com/Sky24n/common_utils)                | **Dart 常用工具类库**     |
| [flutter_slidable](https://github.com/letsar/flutter_slidable)        | **侧滑删除**     |
| [flustars](https://github.com/Sky24n/flustars)                        | **Flutter 常用工具类库**       |
| [flutter_swiper](https://github.com/best-flutter/flutter_swiper)      | **Flutter 轮播组件**       |
| [url_launcher](https://github.com/flutter/plugins/tree/master/packages/url_launcher)   | **启动URL的插件**       |
| [image_picker](https://github.com/flutter/plugins/tree/master/packages/image_picker)   | **图片选择插件** |
| [rxdart](https://github.com/ReactiveX/rxdart)                         | **Dart的响应式扩展** |
| [webview_flutter](https://github.com/flutter/plugins/tree/master/packages/webview_flutter)    | **WebView插件**       |
| [keyboard_actions](https://github.com/diegoveloper/flutter_keyboard_actions)                  | **处理键盘事件**       |
| [sticky_headers](https://github.com/fluttercommunity/flutter_sticky_headers)   | **列表悬浮头**       |
| [azlistview](https://github.com/flutterchina/azlistview)              | **城市选择列表**   |
| [date_utils](https://github.com/apptreesoftware/date_utils)           | **常用的日期工具类** |
| [bezier_chart](https://github.com/aeyrium/bezier-chart)               | **曲线图表**       |
| [sprintf](https://github.com/Naddiseo/dart-sprintf)                   | **格式化String**   |
| [barcode_scan](https://github.com/apptreesoftware/flutter_barcode_reader)     | **扫码功能** |

详细内容可以参看[pubspec.yaml](https://github.com/simplezhli/flutter_deer/blob/master/pubspec.yaml)文件    

## 后续计划：
* [x] Add map function, see [flutter_2d_amap] (https://github.com/simplezhli/flutter_2d_amap)

* [x] pull down to refresh + pull up to load more

* [x] Introduce state management, expect to use [provider] (https://github.com/rrousselGit/provider)

* [x] pages add annotations to the design drawing path to find the corresponding design drawing.

* [x] The use of this set of frameworks and components in the project will fix and optimize the problems encountered synchronously.

* [x] Added integration tests.

* [x] dark mode support.

* [x] Added `Semantics`

* [] Web-side support.

## Known issues:

-1.12.13 + hotfix.5 Known issues (# 47270 # 47137 ~~ # 47462 ~~ ~~ # 47804 ~~ ~~ # 47021 ~~).

-In the case of a ListView without a dividing line, there is an interval of about 1 pixel between individual items ([Pixel Alignment Issue] (https://github.com/flutter/flutter/issues/14288)).

-When the dark mode is turned on on iOS phones, [the status bar text cannot be modified to black] (https://github.com/flutter/flutter/issues/41067).

-1.9.1 is supported. Use `keyboardType: TextInputType.visiblePassword`. ~~ Input box without setting the `obscureText` property (false), [Unable to pop up password mode keyboard] (https://github.com/flutter/flutter/issues/31738), can be temporarily removed using` BlacklistingTextInputFormatter` Possible Chinese input. ~~

-1.12.13 has been fixed. ~~ On 1.9.1, when the text field is Chinese, [the cursor and the input text are not centered] (https://github.com/flutter/flutter/issues/40248), you can temporarily use `textBaseline: TextBaseline .alphabetic` handles this question. ~~

## Experience and problem records

-[Some Tips in Flutter Development (1)] (https://weilu.blog.csdn.net/article/details/90546727)

-[Some Tips in Flutter Development (2)] (https://weilu.blog.csdn.net/article/details/94849020)

-[Some Tips in Flutter Development (3)] (https://weilu.blog.csdn.net/article/details/100108123)

-[Flutter Adapts Dark Mode] (https://weilu.blog.csdn.net/article/details/102531559)

-[Talk about RepaintBoundary in Flutter] (https://weilu.blog.csdn.net/article/details/103452637)

-[Talk about Semantics in Flutter] (https://weilu.blog.csdn.net/article/details/103823259)

-[Flutter Animation Curves List] (https://weilu.blog.csdn.net/article/details/95632571)

## Thanks For

- [flutter-go](https://github.com/alibaba/flutter-go)

- [flutter_wanandroid](https://github.com/Sky24n/flutter_wanandroid)

## License

	Copyright 2019 simplezhli

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
