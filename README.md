# 个人信息
 - 施国鹏 (`seth-shi`)  / 男 / 1996 
 - 大专 / 广西机电职业技术学院 
 - 工作年限：(2017-12 ~ 至今)
 - Github：[https://github.com/seth-shi](https://github.com/seth-shi)
 - 技术博客： [http://www.shiguopeng.cn](http://www.shiguopeng.cn)
 - 期望职位：`PHP`工程师 / `Golang`工程师

- 手机：15678904596
- 邮箱：1033404553@qq.com / seth9shi@gmail.com

# 技能清单
- 编程语言：`PHP` / `Golang` / `JavaScript`
- 语言框架：`Laravel` / `Gin`
- 数据库相关：`MySQL` / `Redis`/ `MongoDB` / `Clickhouse`
- 消息中间件: `Kafka`
- 其他：`Docker` / `Elasticsearch` / `Git`

## 开源项目
- [https://github.com/seth-shi/monday-shop](https://github.com/seth-shi/monday-shop)
    - `PHP` + `Laravel5.5` + `MySQL`
    - `Github`获得`500+ star`
    - 一个网上在线商城、综合网上购物平台
    - 个人商城项目,本是毕业设计项目,工作后有时间也会维护.
- [https://github.com/seth-shi/qrcodeplus](https://github.com/seth-shi/qrcodeplus)
    - 彩色, 背景图片二维码
    - 读写二维码的每一个色块然后替换成想要的色块
- [https://github.com/seth-shi/easy-extends](https://github.com/seth-shi/easy-extends)
    - 快速安装`PHP`扩展
    - 初学者使用`Win`系统安装`PHP`扩展相对麻烦
    - 下载`PECL`对应系统版本的`dll`,然后修改配置文件
## 开源项目贡献
- [https://github.com/laravel/framework](https://github.com/laravel/framework) `Laravel 框架`
    - [https://github.com/laravel/framework/pull/24168](https://github.com/laravel/framework/pull/24168) `修复数据库主键字符串数字整型溢出限制`
- [https://github.com/z-song/laravel-admin](https://github.com/z-song/laravel-admin) `快速构建功能齐全的管理后台`
    - [https://github.com/z-song/laravel-admin/pull/2613](https://github.com/z-song/laravel-admin/pull/2613) `自定义登录验证`
    - [https://github.com/z-song/laravel-admin/pull/2680](https://github.com/z-song/laravel-admin/pull/2680) `增加过滤功能`
- [https://github.com/cosmtrek/air](https://github.com/cosmtrek/air) `Go应用程序的实时重载`
    - [https://github.com/cosmtrek/air/pull/74](https://github.com/cosmtrek/air/pull/74) `windows 下可执行文件配置的支持`
- [https://github.com/jqhph/dcat-admin](https://github.com/jqhph/dcat-admin) `快速构建出一个功能完善的高颜值后台系统`
    - [https://github.com/jqhph/dcat-admin/pull/1268](https://github.com/jqhph/dcat-admin/pull/1268) `Fix: 多应用后台登录后跳转`
## 技术文章
- [Laravel 开发 RESTful API 的一些心得](https://learnku.com/articles/8380/some-of-the-experiences-of-laravel-developing-restful-api)
    - 获得`laravel-china`的`API`开发精选文章
    - 获得`laravel-china`社区用户`2w+`阅读
- [星期一商城。用 Laravel 写了个商城，哈哈](https://learnku.com/articles/6784/the-open-source-project-open-source-project-on-monday-mall-write-a-mall-in-laravel-haha)
    - 获得`laravel-china`社区用户`2w+`阅读
    - `150+`评论互动


# 工作经历

## 西安萌叶网络 / 西安运动数字 （ 2019年10月 ~ 至今 ）
### 儿歌点点启蒙版(TODO)

* 成长
  * **投放归因**, 因投放之后无法追踪到用户留存,播放.新用户内容推送.所以对接了各大广告平台,媒体进行归因.
      1. 用户点击广告
      2. 广告平台发送请求到监测链接
      3. 用户打开应用后进行归因匹配广告平台发送的数据(纠正渠道,防止第三方渠道跳到官方应用市场)
      4. 归因成功将会在应用的首页精准推送内容(获取广告的文案推送内容)
  * **A/B test** 因产品经理需要对产品的发展方向进行调研改进
      1. 使用哈系桶分层用户,保证多个测试同时进行,不会有用户同时参加测试
      2. 测试结束后选定测试方案,后续服务端返回方案结果
      3. 统计平台展示测试指标,主要为播放次数和时长
  * 因实时日志量巨大, 使用`PHP`构建的日志服务压力巨大,改为`Golang`构建日志服务模块(学习了`Golang`)
  * 其它一些离线计算服务也是用`Golang`构建
  * 用户行为日志, 广告日志数据存储到`MongoDB`
  * 广告归因数据存储到`Clickhouse`,配合*Superset*数据报表展示

* 服务架构
    * `API + Admin`
      * `PHP` + `Laravel6`
      * `MySQL` + `Redis` + `Elasticsearch` + `Clickhouse`
      * `Docker` + `Laradock`
    * `Log`服务
      * `Golang` + `Gin `
      *  `Kafka` + `MongoDB`
    * 项目管理
      * `JIRA`, 
      * `API`文档使用[yapi](https://github.com/YMFE/yapi), 
      * 代码管理使用`Git`
### 千千简笔画
* 成长
    * 项目运营要求的搜索算法是,根据日期,浏览量,排序值进行一定的比例得分排序
    * 学习了使用`Elasticsearch`的得分衰减函数控制权重值排序
* 服务架构
    * `API + Admin`
      * `PHP` + `Laravel6`
      * `MySQL` + `Redis` + `Elasticsearch`
### 樱桃少儿英语视频后台
* 成长
    *  项目日志数据太多使用 redis 简单的生产消费已经不好处理
    * 大数据同事建议我直接上`kafka`, 然后在此项目中学习了`kafka`的使用,高阶消费.
*  服务架构
    * `API + Admin`
      * `PHP` + `Laravel5`
      * `MySQL` + `Redis` + `Elasticsearch`
      * `Kafka`

## 南京赤兔网络科技有限公司 （ 2017年12月 ~ 2019年6月 ）
### “交汇点”移动新闻客户端
* 成长
    *  第一份工作,接触到了工作环境中的代码. 
*  服务架构
    * `API`
      * `PHP` + `Laravel5`
      * `MySQL` + `Redis` + `Elasticsearch`

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
