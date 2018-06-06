# Rui
Android一站式开发框架

主要内容是一套简单快捷的开发框架。目的就是打造通用但不侵染业务的基础框架，尽量实现通过修改配置的方式来实现基础结构。这套框架主要对当下最流行，以及谷歌推荐使用的第三方库进行封装处理，从而简单调用。如：网络层的封装、以及其他优秀开源框架的选择，以及谷歌推荐的MVP模式的搭建。基于该框架无需关心大部分基础建设，而只需着手于自己的业务需求。

下列三个版本分别是**基础版、BaseMvp版、谷歌推荐Mvp + Dagger2版**，框架的难度是逐步提升的,**第二版**（BaseMvp版）和**第三版**（谷歌推荐Mvp + Dagger2版）都是基于在基础版的基础上进行封装拓展。

---


| 序号 | 项目名 | 描述 |
|:---|:---:|:---:|
|1|[Purples](https://github.com/djd2088/Purples)|基础版|
|2|[Purples_BaseMvp](https://github.com/djd2088/Purples_BaseMvp)|BaseMvp版|
|3|[Purples_GogMvp_Dagger2](https://github.com/djd2088/Purples_GogMvp_Dagger2)|谷歌推荐Mvp + Dagger2版|

---

使用到的第三方库:

1.网络请求封装 : RxJava + Retrofit

2.图片加载 : [Glide](https://github.com/bumptech/glide)

3.视图注入 : [ButterKnife](https://github.com/JakeWharton/butterknife)

4.动态权限 : [PermissionsDispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher)

5.下拉刷新，上拉加载 : [SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout) + [BaseRecyclerViewAdapterHelper](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)

6.Loading效果 : [AVLoadingIndicatorView](https://github.com/81813780/AVLoadingIndicatorView)

7.WebView交互 :[JsBridge](https://github.com/lzyzsd/JsBridge)

8.沉浸式状态栏 : [StatusBarCompat](https://github.com/niorgai/StatusBarCompat) / [StatusBarUtil](https://github.com/laobie/StatusBarUtil)

9.RxJava网络请求导致的内存泄漏解决方案 : [RxLifecycle](https://github.com/trello/RxLifecycle) （第三版本已经替换）

10.Banner : [ConvenientBanner](https://github.com/Bigkoo/Android-ConvenientBanner) / [Banner](https://github.com/youth5201314/banner)
