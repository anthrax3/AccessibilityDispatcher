# 辅助功能分发器

主要实现各种功能的辅助点击

* 自动配置VPN信息

## 自动配置VPN信息

![](static/gif/auto_create_pptp.gif)


![](static/gif/auto_create_l2tp.gif)


### 使用

1. 下载

```gradle

compile 'io.github.zhitaocai:accessibility-dispatcher:0.1.0'

// or
// 如果你的项目本身已经集成了 support-annotations 那么请移除本类库中本身所依赖的 support-annotations
compile ('io.github.zhitaocai:accessibility-dispatcher:0.1.0') {
    exclude group: 'com.android.support', module: 'support-annotations'
}

```

2. 配置 

```java

```

### FEATURE

目前只支持第一页创建/更新一个VPN


### TO DO LIST

* [ ] 目前只能一页，还没有考虑列表很长的情况，后续考虑滚动处理多页情况
* [ ] 支持一次输入多个VPN创建/修改
