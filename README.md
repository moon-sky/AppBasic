## AppBasic

每次开发一个新的项目，常用的几个模块都要重新建立，这样十分繁琐，这里就将基础的框架和常用的模块提前准备好，开发新项目时直接加入就可以。

### 网络模块

网络采用的是 Retrofit2 + OkHttp3，这里直接使用最新的框架，在新的好用的框架出现前，可以用上较长的时间。

### 图片加载

使用 Glide ，比较几个图片框架之后，fresco 在加载速度和内存上会稍好一些，但必须使用静态库，在不同设备上局限性较大，并且库的大小上也是最大的。Glide 是 Google 推荐使用的图片加载库，缓存和加载都很 nice ，自己加上失败重试机制也是爽歪歪。

### MVP框架

项目整体使用 MVP 框架，UI 和业务分层，逻辑清晰

### 流程处理

RxJava + RxAndroid 更好的流式函数编程，逻辑清晰，代码简洁

### 工具类

Utils 会独立出来，实现一个 utils 的库，提供常用的一些工具操作，包含LogUtils，NetworkUtils，ArrayUtils，DeviceUtils，AnimationUtils等

