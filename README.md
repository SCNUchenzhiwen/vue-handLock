# handlock

# 手势密码demo

# 效果图

![效果图](https://github.com/SCNUchenzhiwen/vue-handLock/blob/master/draw.jpg)
![效果图](https://github.com/SCNUchenzhiwen/vue-handLock/blob/master/error.jpg)
![效果图](https://github.com/SCNUchenzhiwen/vue-handLock/blob/master/empty.jpg)

### 造轮子

内容宽高默认为屏幕宽度70%
** 手势密码组件 @auth chenzhiwen
* @prop {String} [normalColor='#A0AAAD'] - 未激活状态的圆环颜色
* @prop {String} [pointBgColor='rgba(111, 122, 126, .7)'] - 未激活状态的圆的背景色
* @prop {String} [pointActiveColor='#ffffff'] - 激活的圆点颜色
* @prop {String} [lineActiveColor='rgba(255, 255, 255, .3)'] - 激活的连接线的颜色
* @prop {String} [errorColor='#FF3F3F'] - 显示手势密码错误的时候的颜色
* @prop {String} [errorLineColor='rgba(255, 63, 63, .3)'] - 显示错误的时候的连接线的颜色
* @prop {String} [errorTime='3000'] - 手势密码错误显示时间
* @prop {Number} [canWRatio=0.7] - 手势密码区域占屏幕宽度的比例
* @emit getHandLock - 传递手势密码出来 ex: [0, 1, 3]
* @emit clear - 清空绘制的
* @methods errorDraw - 绘制手势密码错误状态

使用直接下载components/handLock文件即可


> handlock

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


| emoji | 表情  |	emoji | 代码  |	commit | 说明 |
:art: (调色板)	:art:	改进代码结构/代码格式
:zap: (闪电)
:racehorse: (赛马)	:zap:
:racehorse:	提升性能
:fire: (火焰)	:fire:	移除代码或文件
:bug: (bug)	:bug:	修复 bug
:ambulance: (急救车)	:ambulance:	重要补丁
:sparkles: (火花)	:sparkles:	引入新功能
:memo: (备忘录)	:memo:	撰写文档
:rocket: (火箭)	:rocket:	部署功能
:lipstick: (口红)	:lipstick:	更新 UI 和样式文件
:tada: (庆祝)	:tada:	初次提交
:white_check_mark: (白色复选框)	:white_check_mark:	增加测试
:lock: (锁)	:lock:	修复安全问题
:apple: (苹果)	:apple:	修复 macOS 下的内容
:penguin: (企鹅)	:penguin:	修复 Linux 下的内容
:checkered_flag: (旗帜)	:checked_flag:	修复 Windows 下的内容
:robot: (Android机器人)	:robot:	修复Android上的某些内容。
:green_apple: (绿苹果)	:green_apple:	解决iOS上的某些问题。
:bookmark: (书签)	:bookmark:	发行/版本标签
:rotating_light: (警车灯)	:rotating_light:	移除 linter 警告
:construction: (施工)	:construction:	工作进行中
:green_heart: (绿心)	:green_heart:	修复 CI 构建问题
:arrow_down: (下降箭头)	:arrow_down:	降级依赖
:arrow_up: (上升箭头)	:arrow_up:	升级依赖
:pushpin: (图钉)	:pushpin:	将依赖关系固定到特定版本。
:construction_worker: (工人)	:construction_worker:	添加 CI 构建系统
:chart_with_upwards_trend: (上升趋势图)	:chart_with_upwards_trend:	添加分析或跟踪代码
:recycle: (循环箭头)	:recycle:	重构代码。
:hammer: (锤子)	:hammer:	重大重构
:heavy_minus_sign: (减号)	:heavy_minus_sign:	减少一个依赖
:whale: (鲸鱼)	:whale:	Docker 相关工作
:heavy_plus_sign: (加号)	:heavy_plus_sign:	增加一个依赖
:wrench: (扳手)	:wrench:	修改配置文件
:globe_with_meridians: (地球)	:globe_with_meridians:	国际化与本地化
:pencil2: (铅笔)	:pencil2:	修复 typo
:hankey: (瞪眼)	:hankey:	编写需要改进的错误代码。
:rewind: (双左箭头)	:rewind:	恢复更改。
:twisted_rightwards_arrows: (双合并箭头)	:twisted_rightwards_arrows:	合并分支。
:package: (箱子)	:package:	更新编译的文件或包。
:alien: (面具)	:alien:	由于外部API更改而更新代码。
:truck: (面包车)	:truck:	移动或重命名文件。
:page_facing_up: (文档)	:page_facing_up:	添加或更新许可证。
:boom: (爆炸)	:boom:	介绍突破性变化。
:bento: (装满餐盘)	:bento:	添加或更新资产。
:ok_hand: (OK手势)	:ok_hand:	由于代码审查更改而更新代码。
:wheelchair: (坐姿)	:wheelchair:	提高可访问性。
:bulb: (灯泡)	:bulb:	记录源代码。
:beers: (干杯)	:beers:	醉生梦死的写代码。
:speech_balloon: (提示栏)	:speech_balloon:	更新文字和文字。
:card_file_box: (卡片盒子)	:card_file_box:	执行与数据库相关的更改。
:loud_sound: (有声喇叭)	:loud_sound:	添加日志。
:mute: (静音喇叭)	:mute:	删除日志。
:busts_in_silhouette: (两个人头)	:busts_in_silhouette:	添加贡献者。
:children_crossing: (小盆友)	:children_crossing:	改善用户体验/可用性。
:building_construction: (吊车)	:building_construction:	进行架构更改。
:iphone: (手机)	:iphone:	致力于响应式设计。
:clown_face: (小丑)	:clown_face:	嘲笑事物。
:egg: (彩蛋)	:egg:	添加一个复活节彩蛋。
:see_no_evil: (蒙眼猴子)	:see_no_evil:	添加或更新.gitignore文件。
:camera_flash: (照相机)	:camera_flash:	添加或更新快照。
