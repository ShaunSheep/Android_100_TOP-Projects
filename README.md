[博客原文链接](http://www.cnblogs.com/jincheng-yangchaofan/articles/7018780.html "Permalink to 2017年Android百大框架排行榜 - 杨超凡_金诚先生 - 博客园")
>说明：
>无聊之时作的一篇笔记式文章，
>精力有限，很多错误之处，受时间与能力限制，没能及时修改，隐隐懊悔，
>受读者启发，遂将此文公之于众，旨在号召大家共同编辑、共同参与，让此排行榜帮助更多的Android开发者。
>
>读者参与方式：
>1.在博客原文站点进行评论，提出对文章内容的修改意见，请务必描述准确。
>2.使用Github的Pull requests，clone本地->重新编辑->提交。请务必核查准确。
>3.提Issues，我每周末会统一解决Issues（这种会影响关注者的时间线，最末推荐）。
><div id="cnblogs_post_body">

> # <span style="font-family: 宋体; background-color: #ff9900"> 框架：提供一定能力的小段程序</span>


# 一.榜单介绍

<span style="font-size: 15px">排行榜包括四大类：</span>

<span style="font-size: 15px">单一框架：仅提供路由、网络层、UI层、通信层或其他**单一功能**的框架</span>

<span style="font-size: 15px">混合开发框架：提供开发**hybrid app、h5与webview结合能力、web app能力**的框架</span>

<span style="font-size: 15px">企业级开源项目：可以独立运行的app，有极高的学习价值、思路借鉴意义</span>

<span style="font-size: 15px">书籍类开源项目：类似Open-sourc-project这样的导航类项目；大型公司的Android课程的学习目录 tips</span>

<span style="font-size: 16px; font-family: 宋体">榜单排序依据：</span>

<span style="font-size: 15px">1.项目开源</span>

<span style="font-size: 15px">2.github上该项目的star个数</span>

<span style="font-size: 15px">3.开发团队、作者的实力</span>

为了保证榜单内容的多样性，榜单上尽可能的不重复同类型框架（比如多款listview增强框架）

<span style="font-family: 黑体; font-size: 18px">适用读者范围：</span>

*   <span style="font-size: 16px">正在入门Android的新手~~~Android初级开发工程师  初出茅庐</span>

　<span style="font-size: 15px">　**熟读**《书籍导航类项目排行榜》，勤加练习进步会更大；**编译运行并动脑思考**《企业级开源项目》中的案例，可以提升开发完整项目的能力；;**略读**《框架百大排行榜》，最大的作用是的是拓展视野，可以看到很多时下流行的名词概念术语</span>

*   <span style="font-size: 16px">Android初级开发工程师~~~中级开发工程师    知其然知其所以然</span>

　<span style="font-size: 15px">　熟练、快速、高效的默写出《企业级开源项目》中的（自己感兴趣）典型案例，对提高书写代码的自信，提升项目功能整体设计能力；深究《框架百大排行榜》排名靠前框架的**原理**，会让自己在与家人、同事、同学聚会之时多了一些炫耀的资本；如果你能熟练运用《框架百大排行榜》里所提到的框架，在遇到某种需求的时候，立刻会拿出**“最优秀的框架”**去解决，意味着你离中级工程师不太远了</span>

*   <span style="font-size: 16px">中级、高级、资深工程师   知其然知其不可然</span>

<span style="font-size: 15px">　　　《框架百大排行榜》里所提到的流行词、流行术语——使用能力、融会贯通其原理、讲解框架能力的高低，将让你不断的在这三个级别徘徊；</span>

<span style="font-size: 15px">　　　会有意识的合并榜单里多款同类型框架，来弥补单一框架的某些缺陷，比如将同为网络请求框架的Volley和Okhttp封装到一起应对不同场面的需求；</span>

<span style="font-size: 15px">　　　会有意识的二次开发、修改源码来扩展榜单所提到的大型框架；</span>

<span style="font-size: 15px">　　　能够在开发团队里推动、部署某些框架的能力——比如要在一个新加入的陌生团队说服leader和项目成员使用热更新、插件化、组件化、hybrid 开发等多种开发模式，你是否有这个实力?</span>

<span style="font-size: 15px">　　</span>

 <span style="font-size: 16px">框架名次越靠前，值得使用的优先级就越高、研究原理得到的收获会更多、对读者启发的价值就越大</span>

# 二.百大框架排行榜

快速索引

| 框架名称                             | 上榜关键字  |
| -------------------------------- | ------ |
| 1.Retrofit                       | 网络     |
| 2.okhttp                         | 网络     |
| 3.Butter Knife                   | 代码模板   |
| 4.MPAndroidChart                 | 图表     |
| 5.Glide                          | 图片     |
| 6.leakcanary                     | 内存     |
| 7.Android-Universal-Image-Loader | 图片     |
| 8.EventBus                       | 事件消息   |
| 9.zxing                          | 条码扫描   |
| 10.picasso                       | 图片     |
| 11.lottie-android                | 动画     |
| 12.fresco                        | 图片     |
| 13.RxAndroid                     | 异步     |
| 14.SlidingMenu                   | 菜单     |
| 15.PhotoView                     | 图片     |
| 16.material-dialogs              | UI     |
| 17.android-async-http            | 网络     |
| 18.androidannotations            | 注解     |
| 19.fastjson                      | json   |
| 20.Material-Animations           | 动画     |
| 21.tinker                        | 热修复    |
| 22.ViewPagerIndicator            | UI     |
| 23.Android-CleanArchitecture     | 架构     |
| 24.Android-PullToRefresh         | 刷新     |
| 25.flexbox-layout                | UI     |
| 26.AndroidSwipeLayout            | UI     |
| 27.realm-java                    | 数据库    |
| 28.greenDAO                      | 数据     |
| 29.stetho                        | 调试     |
| 30.BaseRecyclerViewAdapterHelper | UI     |
| 31.AndroidViewAnimations         | 动画     |
| 32.MaterialDrawer                | 菜单     |
| 33.Android-ObservableScrollView  | UI     |
| 34.CircleImageView               | 图片     |
| 35.logger                        | 调试     |
| 32.MaterialDrawer                | 菜单     |
| 36.agera                         | 异步     |
| 37.BottomBar                     | 菜单     |
| 38.Calligraphy                   | 字体     |
| 39.AndroidSlidingUpPanel         | UI     |
| 40.AppIntro                      | UI     |
| 41.recyclerview-animators        | 动画     |
| 42.dagger                        | 依赖注入   |
| 43.Android-Bootstrap             | UI     |
| 44.RxBinding                     | 响应式    |
| 45.ListViewAnimations            | 动画     |
| 46.UItimateRecyclerView          | 图片     |
| 47.uCrop                         | UI     |
| 48.RxJava-Android-Samples        | 用例     |
| 49.AndroidAutoLayout             | 适配     |
| 50.EffectiveAndroidUI            | 性能     |
| 51.Luban                         | 图片     |
| 52.DroidPlugin                   | 插件化    |
| 53.otto                          | 响应式    |
| 54.u2020                         | 用例     |
| 55.buck                          | 构建     |
| 56.PermissionsDispatcher         | 权限     |
| 57.android-gif-drawable          | GIF    |
| 58.Apktool                       | 反编译    |
| 59.dynamic-load-apk              | 插件化    |
| 60.atlas                         | 插件化    |
| 61.volley                        | 网络     |
| 62.androidmvp                    | 用例     |
| 63.SwipeBackLayout               | 手势     |
| 64.FlycoTabLayout                | UI     |
| 65.android-testing               | 测试     |
| 66.FileDownloader                | 下载     |
| 67.JieCaoVideoPlayer             | 多媒体    |
| 68.glide-transformations         | 图片     |
| 69.android-gpuimage              | 图片     |
| 70.RxPermissions                 | 权限     |
| 71.freeline                      | 编译     |
| 72.RxLifecycle                   | 生命周期   |
| 73.classyshark                   | 反编译    |
| 74.acra                          | 崩溃日志   |
| 75.DiskLruCache                  | 文件     |
| 76.dexposed                      | 热修复    |
| 77.Litho                         | 性能     |
| 78.mosby                         | MVP    |
| 79.AndResGuard                   | 混淆     |
| 80.StatusBarUtil                 | 状态栏    |
| 81.robolectric                   | 测试     |
| 82.Fragmentation                 | 嵌套     |
| 83.Small                         | 插件化    |
| 84.JsBridge                      | hybrid |
| 85.richeditor-android            | UI     |
| 86.Transitions-Everywhere        | 动画     |
| 87.android-viewbadger            | 勋章     |
| 88.AndroidWiFiADB                | 调试     |
| 89.emojicon                      | 表情包    |
| 90.packer-ng-plugin              | 多渠道    |
| 91.android-priority-jobqueue     | 多线程    |
| 92.Android-Debug-Database        | 调试     |
| 93.conceal                       | 加密     |
| 94.ARouter                       | 页面路由   |
| 95.MagicaSakura                  | 多主题    |
| 96.CustomActivityOnCrash         | 崩溃     |
| 97.XhsEmoticonsKeyboard          | 键盘     |





## 1\. Retrofit　　

<span style="font-size: 15px">一句话介绍：Retrofit是一款类型安全的网络框架，基于HTTP协议，服务于Android和java语言</span>

<span style="font-size: 15px">上榜理由：Retrofit以21.8k的stars量雄踞github中android子标题榜首，第一当之无愧。</span>

<span style="font-size: 15px">官网地址 [http://square.github.io/retrofit/](http://square.github.io/retrofit/)</span>

<span style="font-size: 15px">github  <a target="_blank"> https://github.com/square/retrofit</a></span>

<span style="font-size: 15px">作者：square团队</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.squareup.retrofit2:retrofit:2.3.0</span><span style="color: #800000">'</span></pre>

</div>

## 2.okhttp

<span style="font-size: 15px">一句话介绍：okhttp是一款基于HTTP和HTTP2.0协议的网络框架，服务于java和android客户端</span>

<span style="font-size: 15px">上榜理由，okhttp以20.4k的stars量雄踞github中android子标题第二名。大型公司比如淘宝也封装的是okhttp。Retrofit2.0开始内置okhttp框架，Retrofit专注封装接口完成业务需求，okhttp专注网络请求的安全高效，笔者将两者区分开，是想让后来学习者知道，这是两套框架，学习框架原理时可以分开学习，以免理解混乱。</span>

<span style="font-size: 15px">官网地址   [http://square.github.io/okhttp/](https://github.com/JakeWharton/butterknife)</span>

<span style="font-size: 15px">github    [https://github.com/square/okhttp](https://github.com/square/okhttp)</span>

<span style="font-size: 15px">作者：square团队</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.squareup.okhttp3:okhttp:3.8.0</span><span style="color: #800000">'</span></pre>

</div>

## 3.Butter Knife

<span style="font-size: 15px">一句话介绍：Butter Knife所提供了一种能力——使用注解生成模板代码，将view与方法和参数绑定。</span>

<span style="font-size: 15px">上榜理由：github上16.5K个star，配合Androidstudio提供的Butter Knife插件，帮助开发者省却了频繁findviewbyid的烦恼，最新的Butter Knife还提供了onclick绑定以及字符串的初始化，初学者可以查阅Butter Knife以及Butter Knife插件进一步学习！</span>

<span style="font-size: 15px">官网地址：[http://jakewharton.github.io/butterknife/](http://jakewharton.github.io/butterknife/)</span>

<span style="font-size: 15px">github：[https://github.com/JakeWharton/butterknife](https://github.com/JakeWharton/butterknife)</span>

<span style="font-size: 15px">作者：JakeWharton ，也是square团队成员之一</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
  compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.jakewharton:butterknife:8.6.0</span><span style="color: #800000">'</span> <span style="color: #000000">annotationProcessor</span> <span style="color: #800000">'</span><span style="color: #800000">com.jakewharton:butterknife-compiler:8.6.0</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

## 4.MPAndroidChart

<span style="font-size: 15px">一句话介绍：MPAndroidChart是一款图表框架</span>

<span style="font-size: 15px">上榜理由：github上16.1K个star，以快速、简洁。强大著称的图表框架</span>

<span style="font-size: 15px">官网地址 [https://github.com/PhilJay/MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)  </span>

<span style="font-size: 15px">github  https://github.com/PhilJay/MPAndroidChart</span>

<span style="font-size: 15px">作者：PhilJay</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">1\. 在AS中加入Gradle依赖</span>

*   <span style="font-size: 15px">在根目录的 `build.gradle上加入`:</span>
* <div class="cnblogs_code">

    <pre><span style="color: #000000">allprojects {
        repositories {
            maven { url</span> <span style="color: #800000">"</span><span style="color: #800000">https://jitpack.io</span><span style="color: #800000">"</span> <span style="color: #000000">}
        }
    }</span></pre>

    </div>

* <span style="font-size: 15px">在app的build.gradle上加入：</span>
* <div class="cnblogs_code">

    <pre><span style="color: #000000">dependencies {
        compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.PhilJay:MPAndroidChart:v3.0.2</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

    </div>

## 5\. glide

<span style="font-size: 15px">一句话介绍：glide是一款专注于提供**流畅划动能力**的“图片加载和缓存框架”</span>

<span style="font-size: 15px">上榜理由：15.9k个star，图片加载类框架排名第一的框架，google 在2014开发者大会上演示的camera app就是基于gilde框架开发的</span>

<span style="font-size: 15px">github [https://github.com/bumptech/glide](https://github.com/bumptech/glide)</span>

<span style="font-size: 15px">作者 Bump Technologies团队</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
  mavenCentral()
}

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.bumptech.glide:glide:3.8.0</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.android.support:support-v4:19.1.0</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 6.leakcanary

<span style="font-size: 15px">一句话介绍：一款内存检测框架，服务于java和android客户端</span>

<span style="font-size: 15px">上榜理由：方便，简洁是leakcanary最大的特点，只需在应用的apllication中集成，就可以直接使用它；15.5k个star说明了它有多么受欢迎</span>

<span style="font-size: 15px">github https://github.com/square/leakcanary</span>

<span style="font-size: 15px">作者 square团队</span>

<span style="font-size: 15px">使用</span>：

<div class="cnblogs_code">

<pre> <span style="color: #000000">dependencies {
   debugCompile</span> <span style="color: #800000">'</span><span style="color: #800000">com.squareup.leakcanary:leakcanary-android:1.5.1</span><span style="color: #800000">'</span> <span style="color: #000000">releaseCompile</span> <span style="color: #800000">'</span><span style="color: #800000">com.squareup.leakcanary:leakcanary-android-no-op:1.5.1</span><span style="color: #800000">'</span> <span style="color: #000000">testCompile</span> <span style="color: #800000">'</span><span style="color: #800000">com.squareup.leakcanary:leakcanary-android-no-op:1.5.1</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

<span style="font-size: 15px">在 `Application` 中写入:</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #0000ff">public</span> <span style="color: #0000ff">class</span> <span style="color: #000000">ExampleApplication extends Application {

  @Override</span> <span style="color: #0000ff">public</span> <span style="color: #0000ff">void</span> <span style="color: #000000">onCreate() {
    super.onCreate();</span> <span style="color: #0000ff">if</span> (LeakCanary.isInAnalyzerProcess(<span style="color: #0000ff">this</span><span style="color: #000000">)) {</span> <span style="color: #008000">//</span> <span style="color: #008000">This process is dedicated to LeakCanary for heap analysis.</span> <span style="color: #008000">//</span> <span style="color: #008000">You should not init your app in this process.</span>
      <span style="color: #0000ff">return</span><span style="color: #000000">;
    }
    LeakCanary.install(</span><span style="color: #0000ff">this</span><span style="color: #000000">);</span> <span style="color: #008000">//</span> <span style="color: #008000">Normal app init code...</span>
 <span style="color: #000000">}
}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 7.Android-Universal-Image-Loader

<span style="font-size: 15px">一句话介绍：曾经的图片加载框架王者，android开发老手都用过它</span>

<span style="font-size: 15px">上榜理由:android端图片加载框架的老大哥了，15.3k个star足以证明它的热门，UIL与gilde最大区别是可定制，UIL提供了大量配置方式，图片加载状态的回调（成功，失败，进行中），加载动画等；以及提供了移动端图片加载框架的缓存思路：三级缓存策略 sd卡-内存-网络；值得注意的是，UIL以及两年未更新了，但笔者仍推荐各位使用！</span>

<span style="font-size: 15px">github [https://github.com/nostra13/Android-Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)</span>

<span style="font-size: 15px">作者 nostra13</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">下载地址  [universal-image-loader-1.9.5.jar](https://github.com/nostra13/Android-Universal-Image-Loader/raw/master/downloads/universal-image-loader-1.9.5.jar)</span>

<span style="font-size: 15px"> </span>

## 8.EventBus

<span style="font-size: 15px">一句话介绍：EventBus是一款本地组件间通信框架</span>

<span style="font-size: 15px">上榜理由：组件间通信框架star量第一：14.8k，在大型项目的Activities，fragments，Threads，Services都可以看到它的使用场景，尽管EventBus在向未创建的组件传递事件时有些局限，仅适合在“活着的”组件间传递消息，但仍不妨碍它活跃在各个大型项目各个场景里。</span>

<span style="font-size: 15px">官网地址 [http://greenrobot.org/eventbus/documentation/how-to-get-started/](http://greenrobot.org/eventbus/documentation/how-to-get-started/)</span>

<span style="font-size: 15px">github  [https://github.com/greenrobot/EventBus](https://github.com/greenrobot/EventBus)</span>

<span style="font-size: 15px">作者 greenrobot </span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">org.greenrobot:eventbus:3.0.0</span><span style="color: #800000">'</span></pre>

</div>

## 9.zxing

<span style="font-size: 15px">一句话介绍：条码图像处理库</span>

<span style="font-size: 15px">上榜理由：如果你用过二维码，你肯定已经间接使用过大名鼎鼎的zxing了。13.9K的star量，让它排在本榜单第九，实至名归，如果你有了解二维码的需求，不妨从了解、修改它源码入手。</span>

<span style="font-size: 15px">github [ https://github.com/zxing/zxing](https://github.com/zxing/zxing)</span>

<span style="font-size: 15px">作者  Sean Owen</span>

## 10.picasso

<span style="font-size: 15px">一句话介绍：强力的图片下载、缓存框架</span>

<span style="font-size: 15px">上榜理由：本榜单出现的第三款图片类框架，不同的是picasso更强调图片下载，你可以将picasso集成进你的项目中，你也可以结合gilde和UIL与picasso，三者一齐封装至你的项目中，按需所用。</span>

<span style="font-size: 15px">官网地址 [http://square.github.io/picasso/](http://square.github.io/picasso/)</span>

<span style="font-size: 15px">github  [https://github.com/square/picasso](https://github.com/square/picasso)</span>

<span style="font-size: 15px">作者 square团队</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.squareup.picasso:picasso:2.5.2</span><span style="color: #800000">'</span></pre>

</div>

<span style="font-size: 15px">或者下载</span>

<span style="font-size: 15px">[jar包](https://search.maven.org/remote_content?g=com.squareup.picasso&a=picasso&v=LATEST)</span>

## 11.lottie-android

<span style="font-size: 15px">一句话介绍：一款可以在Android端快速展示Adobe Afeter Effect（AE）工具所作动画的框架</span>

<span style="font-size: 15px">上榜理由：动画类框架第一名，github上13.3k个star证明了他的优越性，利用json文件快速实现动画效果是它最大的便利，而这个json文件也是由Adobe提供的After Effects（AE）工具制作的，在AE中装一个Bodymovin的插件，使用这个插件最终将动画效果生成json文件，这个json文件即可由LottieAnimationView解析并生成绚丽的动画效果。而且它还支持跨平台哟。</span>

<span style="font-size: 15px">github  [https://github.com/airbnb/lottie-android](https://github.com/airbnb/lottie-android)</span>

<span style="font-size: 15px">作者：Airbnb 团队</span>

## 12.fresco

<span style="font-size: 15px">一句话介绍：一款可以管理图片内存的框架</span>

<span style="font-size: 15px">上榜理由:github上12.8k个star，图片类排行榜第四名，facebook的出身证明了它并非是重复造的轮子，在管理图片内存领域上有着它的一片天地，渐进式加载、加载gif都是它与前三位相比独有的特性</span>

<span style="font-size: 15px">官网地址： [https://www.fresco-cn.org/](https://www.fresco-cn.org/)</span>

<span style="font-size: 15px">github  [https://github.com/facebook/fresco](https://github.com/facebook/fresco)</span>

<span style="font-size: 15px">作者 facebook</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {</span> <span style="color: #008000">//</span> <span style="color: #008000">其他依赖</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.fresco:fresco:0.12.0</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

<span style="font-size: 15px">下面的依赖需要根据需求添加：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">dependencies {</span> <span style="color: #008000">//</span> <span style="color: #008000">在 API < 14 上的机器支持 WebP 时，需要添加</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.fresco:animated-base-support:0.12.0</span><span style="color: #800000">'</span>

  <span style="color: #008000">//</span> <span style="color: #008000">支持 GIF 动图，需要添加</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.fresco:animated-gif:0.12.0</span><span style="color: #800000">'</span>

  <span style="color: #008000">//</span> <span style="color: #008000">支持 WebP （静态图+动图），需要添加</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.fresco:animated-webp:0.12.0</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.facebook.fresco:webpsupport:0.12.0</span><span style="color: #800000">'</span>

  <span style="color: #008000">//</span> <span style="color: #008000">仅支持 WebP 静态图，需要添加</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.fresco:webpsupport:0.12.0</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 13.RxAndroid

<span style="font-size: 15px">一句话介绍：一款Android客户端组件间异步通信的框架</span>

<span style="font-size: 15px">上榜理由：github上12.7k个star，位居组件通信框架的第二名，仅在EventBus之后，如果要问两者的区别，Eventbus是用来取代组件间繁琐的interface，RxAndroid是用来取代AnsyTask的，并不冲突；当然RxAndroid的优点并不仅限于此，更多优雅的实现，可以去官网查阅！</span>

<span style="font-size: 15px">github  [https://github.com/ReactiveX/RxAndroid](https://github.com/ReactiveX/RxAndroid)</span>

<span style="font-size: 15px">作者 JakeWharton</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">io.reactivex.rxjava2:rxandroid:2.0.1</span><span style="color: #800000">'</span>
compile <span style="color: #800000">'</span><span style="color: #800000">io.reactivex.rxjava2:rxjava:2.1.0</span><span style="color: #800000">'</span></pre>

</div>

## 14.SlidingMenu

<span style="font-size: 15px">一句话介绍：侧滑菜单栏框架</span>

<span style="font-size: 15px">上榜理由：与Userval-Image-loader 齐名的上古神器框架——为你的app提供侧滑菜单栏的功能；github闪更有10.5k个star，证明了它的经久不衰，即使在Google推出了NavigationDrawer，仍然没有减少开发者对SildingMenu的拥簇，经典总是经得起考验的，这个上古神兽已经四年没有更新了；有太多太多的app使用过它，这些都可以在软件的开源许可上看到！</span>

<span style="font-size: 15px">github [https://github.com/jfeinstein10/SlidingMenu](https://github.com/jfeinstein10/SlidingMenu)</span>

<span style="font-size: 15px">作者 Jeremy Feinstein</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">在gihub上fork源码，集成进项目中</span>

## 15.PhotoView

<span style="font-size: 15px">一句话介绍：一款ImageView展示框架，支持缩放，响应手势</span>

<span style="font-size: 15px">上榜理由：10.3k的star数量，位于图片类框架排行榜第五位，PhotoView与前四位不同的是这次带来的是图片的展示能力，你一定好奇微信的头像点击放大是如何实现的，很多App的图片显示响应手势按压是如何实现的，了解PhotoView，你一定会开心的！（笔者也不会告诉你ImageView的点击放大效果在Android的sample也有）</span>

<span style="font-size: 15px">github  [https://github.com/chrisbanes/PhotoView](https://github.com/chrisbanes/PhotoView)</span>

<span style="font-size: 15px">作者：chrisbanes</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">在app根目录的build.gradle中加入：
allprojects {
    repositories {
        maven { url</span> <span style="color: #800000">"</span><span style="color: #800000">https://jitpack.io</span><span style="color: #800000">"</span> <span style="color: #000000">}
    }
}
在app的module目录的build.gralde中加入：

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.chrisbanes:PhotoView:latest.release.here</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

<span style="font-size: 15px">使用</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><<span style="color: #000000">com.github.chrisbanes.photoview.PhotoView
    android:id</span>=<span style="color: #800000">"</span><span style="color: #800000">@+id/photo_view</span><span style="color: #800000">"</span> <span style="color: #000000">android:layout_width</span>=<span style="color: #800000">"</span><span style="color: #800000">match_parent</span><span style="color: #800000">"</span> <span style="color: #000000">android:layout_height</span>=<span style="color: #800000">"</span><span style="color: #800000">match_parent</span><span style="color: #800000">"</span>/>

 <span style="color: #000000">PhotoView photoView</span> = <span style="color: #000000">(PhotoView) findViewById(R.id.photo_view);
photoView.setImageResource(R.drawable.image);</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 16.material-dialogs

<span style="font-size: 15px">一句话介绍：一款自定义dialog框架</span>

<span style="font-size: 15px">上榜理由：9.9k个star，也是继PhotoView，SlidingMenu之后第三款自定义View框架，也许你还是自定义View的新人，对Dialog使用的还有点生疏，你可以通过它提升你的Dilaog使用能力</span>

<span style="font-size: 15px">github  [https://github.com/afollestad/material-dialogs](https://github.com/afollestad/material-dialogs)</span>

<span style="font-size: 15px">作者：Aidan Follestad</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {</span> <span style="color: #008000">//</span> <span style="color: #008000">... other dependencies here</span>
    compile <span style="color: #800000">'</span><span style="color: #800000">com.afollestad.material-dialogs:core:0.9.4.5</span><span style="color: #800000">'
}</span></pre>

</div>

## 17.Android-async-http

<span style="font-size: 15px"> 一句话介绍：一款基于Http协议的异步请求的网络框架，</span>

<span style="font-size: 15px">上榜理由：虽然你有无数个使用retrofit+okhttp的理由，但9.8k个star，证明它仍然值得你深入学习。值得注意的是，它也已经有两年没更新了，你尽管拿去当你懒惰的理由！</span>

<span style="font-size: 15px">github   [https://github.com/loopj/android-async-http](https://github.com/loopj/android-async-http)</span>

<span style="font-size: 15px">作者：James Smith</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
  maven {
    url</span> <span style="color: #800000">'</span><span style="color: #800000">https://oss.sonatype.org/content/repositories/snapshots/</span><span style="color: #800000">'</span> <span style="color: #000000">}
}
dependencies {
  compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.loopj.android:android-async-http:1.5.0-SNAPSHOT</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 18.androidannotations

<span style="font-size: 15px">一句话介绍：一款基于注解的快速开发框架</span>

<span style="font-size: 15px">上榜理由：与Butterknife一样基于注解，利用注解快速完成view的初始化，不同的是androidannotations提供了更多的能力：简单的线程模型等；笔者只接触过Butterknife，无法更进一步叙述androidannotations的优势，如果你志在深入了解注解的妙用，可以尝试探索一下！</span>

<span style="font-size: 15px">官网地址 [http://androidannotations.org/](http://androidannotations.org/)</span>

<span style="font-size: 15px">github [https://github.com/androidannotations/androidannotations](https://github.com/androidannotations/androidannotations)</span>

<span style="font-size: 15px">作者： WonderCsabo</span>

## 19.fastjson

<span style="font-size: 15px">一句话介绍:一款基于json解析、生成的框架</span>

<span style="font-size: 15px">上榜理由：从它的名字不难看出，快速是它最大的特性，阿里巴巴的出身保证了代码的质量和优越，9.4k的star数量，也是榜单里第一个出现的中国开源框架，涉及网络的app都会用到json，fastjson值得作为你的首选！</span>

<span style="font-size: 15px">github  [https://github.com/alibaba/fastjson](https://github.com/alibaba/fastjson)</span>

<span style="font-size: 15px">作者：alibaba</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.alibaba:fastjson:1.1.58.android</span><span style="color: #800000">'</span></pre>

</div>

## 20.Material-Animations

<span style="font-size: 15px">一句话介绍：一款提供场景转换过渡能力的动画框架</span>

<span style="font-size: 15px">上榜理由：Android动画框架排行榜第二名，9.3k个star数量，与动画框架榜单第一名lottie-android不同的是，Material-Animations提供的是场景切换的动画效果。Android 官网sample中已经提供了部分Transition （转场动画）的展示，作为初学者很难快速拓展到自己项目中，Material-Animations的示例出现为开发者省去了此类麻烦，直接照搬应用到自己的App中吧。</span>

<span style="font-size: 15px"> github  [https://github.com/lgvalle/Material-Animations](https://github.com/lgvalle/Material-Animations)</span>

<span style="font-size: 15px">作者：Luis G. Valle</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">down源码，修改学习</span>

## 21.tinker

<span style="font-size: 15px">一句话介绍：它是微信官网的Android热补丁解决方案</span>

<span style="font-size: 15px">上榜理由：9.1k个star，微信在用的热补丁方案，心动不如行动</span>

<span style="font-size: 15px">官网地址  [http://www.tinkerpatch.com/Docs/intro](http://www.tinkerpatch.com/Docs/intro)</span>

<span style="font-size: 15px">github   [https://github.com/Tencent/tinker](https://github.com/Tencent/tinker)</span>

<span style="font-size: 15px">作者：Tencent</span>

## 22.ViewPagerIndicator

<span style="font-size: 15px">一句话介绍：一款基于ViewPager的页面指示器开源框架</span>

<span style="font-size: 15px">上榜理由：上古神器，尽管已经五年未更新了，但你仍然可以在淘宝等app中看到它的使用场景，8.9K的star量让它不愠不火的在矗立在榜单里</span>

<span style="font-size: 15px">官网地址 [http://viewpagerindicator.com/](http://viewpagerindicator.com/)</span>

<span style="font-size: 15px">github  [https://github.com/JakeWharton/ViewPagerIndicator](https://github.com/JakeWharton/ViewPagerIndicator)</span>

<span style="font-size: 15px">作者：JakeWharton </span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px"> 下载 地址[ https://github.com/JakeWharton/Android-ViewPagerIndicator/zipball/master](https://github.com/JakeWharton/Android-ViewPagerIndicator/zipball/master)</span>

<span style="font-size: 15px"> </span>

## 23.Android-CleanArchitecture

<span style="font-size: 15px">一句话介绍：一个讲解设计框架的demo</span>

<span style="font-size: 15px">上榜理由：它不是框架，你可以把它当作一本书，它将教会你如何设计简洁的架构，工程里有一个sample app，配合图文讲解，你将对Android客户端的架构有更深一层的认识。8.8k的star数量，证明了它是一本“好书”哟。</span>

<span style="font-size: 15px">github  [https://github.com/android10/Android-CleanArchitecture](https://github.com/android10/Android-CleanArchitecture)</span>

<span style="font-size: 15px">作者：Fernando Cejas</span>

## 24..Android-PullToRefresh

<span style="font-size: 15px">一句话介绍：一款为普通视图提供刷新UI的视图框架</span>

<span style="font-size: 15px">上榜理由：8.2K的star数量使它位居刷新类UI框架榜首，强大的兼容能力，该框架支持ListView，GrdiView，WebViewScrollView，ViewPager等众多View增加刷新的能力，如果你有增加上拉加载，下拉加载的需求，你应该考虑它了！</span>

<span style="font-size: 15px">github [https://github.com/chrisbanes/Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh)</span>

<span style="font-size: 15px">作者：Chris Banes</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">github fork源码，集成到项目中</span>

## 25.flexbox-layout

<span style="font-size: 15px">一句话介绍：一款弹性伸缩布局</span>

<span style="font-size: 15px">上榜理由：8.1k个star，前端H5开发者转Android开发的福音，FlexboxLayout作为`LinearLayout`和`RelativeLayout的替代者，值得各位一试，与其一同推出的还有ConstraintLayout。`</span>

<span style="font-size: 15px">github  [https://github.com/google/flexbox-layout](https://github.com/google/flexbox-layout)</span>

<span style="font-size: 15px">作者：Google</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.android:flexbox:0.3.0-alpha3</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

## 26.AndroidSwipeLayout

<span style="font-size: 15px">一句话介绍：非常强大滑动式布局</span>

<span style="font-size: 15px">上榜理由:滑动删除是国产app常见需求，商品详情的上下滑动需求作为开发者的我们也经常遇到，AndroidSwipeLayout在github上拥有8K个star，证明它经受住了检验，各位值得一试</span>

<span style="font-size: 15px">github [https://github.com/daimajia/AndroidSwipeLayout](https://github.com/daimajia/AndroidSwipeLayout)</span>

<span style="font-size: 15px">作者：daimajia</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.android.support:recyclerview-v7:21.0.0</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.android.support:support-v4:20.+</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">"</span><span style="color: #800000">com.daimajia.swipelayout:library:1.2.0@aar</span><span style="color: #800000">"</span> <span style="color: #000000">}</span></pre>

</div>

<span style="font-size: 15px">或下载 </span>

<span style="font-size: 15px">[AndroidSwipeLayout-v1.1.8.jar](https://github.com/daimajia/AndroidSwipeLayout/releases/download/v1.1.8/AndroidSwipeLayout-v1.1.8.jar)</span>

## 27.realm-java

<span style="font-size: 15px">一句话介绍：Realm是一款移动端数据库框架</span>

<span style="font-size: 15px">上榜理由：核心数据引擎C++打造，比普通的Sqlite型数据库快的多。笔者猜测正是如此，realm以7892个star数让它位于大名鼎鼎的数据库框架GreenDao（7877）之前</span>

<span style="font-size: 15px">官网地址：[https://realm.io/cn/](https://realm.io/cn/)</span>

<span style="font-size: 15px">github [https://github.com/realm/realm-java](https://github.com/realm/realm-java)</span>

<span style="font-size: 15px">作者：Realm团队 </span>

<span style="font-size: 15px">使用：[https://realm.io/docs/java/latest/](https://realm.io/docs/java/latest/)</span>

## 28.greenDAO

<span style="font-size: 15px">一句话介绍：greenDAO是一款高效、快速的SQLite型数据库</span>

<span style="font-size: 15px">上榜理由：greenDAO的star数量与Realm不相上下，且与EventBus师出同门，也是由greenrobot团队开发维护的，质量有所保证，但若拷问笔者Realm与greenDao两者的优劣性，只能具体到实际使用当中，模拟线上的使用情形，进行高强度测试后才能下判断，故在此不能一言两语说完，深表遗憾</span>

<span style="font-size: 15px">官网地址：[http://greenrobot.org/greendao/](http://greenrobot.org/greendao/)</span>

<span style="font-size: 15px">github  [https://github.com/greenrobot/greenDAO](https://github.com/greenrobot/greenDAO)</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">buildscript {
    repositories {
        jcenter()
        mavenCentral()</span> <span style="color: #008000">//</span> <span style="color: #008000">add repository</span>
 <span style="color: #000000">}
    dependencies {
        classpath</span> <span style="color: #800000">'</span><span style="color: #800000">com.android.tools.build:gradle:2.3.1</span><span style="color: #800000">'</span> <span style="color: #000000">classpath</span> <span style="color: #800000">'</span><span style="color: #800000">org.greenrobot:greendao-gradle-plugin:3.2.2</span><span style="color: #800000">'</span> <span style="color: #008000">//</span> <span style="color: #008000">add plugin</span>
 <span style="color: #000000">}
}</span> -----

apply plugin: <span style="color: #800000">'</span><span style="color: #800000">com.android.application</span><span style="color: #800000">'</span> <span style="color: #000000">apply plugin:</span> <span style="color: #800000">'</span><span style="color: #800000">org.greenrobot.greendao</span><span style="color: #800000">'</span> <span style="color: #008000">//</span> <span style="color: #008000">apply plugin</span>
 <span style="color: #000000">dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">org.greenrobot:greendao:3.2.2</span><span style="color: #800000">'</span> <span style="color: #008000">//</span> <span style="color: #008000">add library</span>
}</pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 29.stetho

<span style="font-size: 15px">一句话介绍：一款提供在Chrome开发者工具上调试Android app能力的开源框架</span>

<span style="font-size: 15px">上榜理由：上古时期Android程序员要调试本地数据库，需要进入Android Device Monitor找到/data/data/com.xxx.xxx/databases里面的db文件，导出到PC端，用PC的数据工具查看，现在使用stetho省却了如此的麻烦；如今的Android程序员如果想调试网络请求响应过程中的报文段，需要在请求中加入Log语句，一个信息一个信息打印出来，相当繁琐，现在请使用stetho，省却诸如此类的麻烦把！7.8K个star数，广大Android开发者调试的福音，你值得拥有！</span>

<span style="font-size: 15px">作者：FaceBook</span>

<span style="font-size: 15px">官网地址：<a target="_blank"> http://facebook.github.io/stetho/</a></span>

<span style="font-size: 15px">github   [https://github.com/facebook/stetho](https://github.com/facebook/stetho)</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.stetho:stetho:1.5.0</span><span style="color: #800000">'</span></pre>

</div>

## 30.BaseRecyclerViewAdapterHelper

<span style="font-size: 15px">一句话介绍：强大、流畅的Recyvlerview通用适配器</span>

<span style="font-size: 15px">上榜理由：如果你是RecyclerView的拥簇者，你一定要体验这款专门服务该view的适配器，7.7K个star，让这个家伙位于github上Android 适配器排行榜第一，还有很多惊喜等你去探寻！</span>

<span style="font-size: 15px">官网地址：[http://www.recyclerview.org/](http://www.recyclerview.org/)</span>

<span style="font-size: 15px">作者：陈宇明以及他的小伙伴</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">allprojects {
    repositories {
        ...
        maven { url</span> <span style="color: #800000">"</span><span style="color: #800000">https://jitpack.io</span><span style="color: #800000">"</span> <span style="color: #000000">}
    }
}

dependencies {
        compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.CymChad:BaseRecyclerViewAdapterHelper:VERSION_CODE</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 31.AndroidViewAnimations

<span style="font-size: 15px">一句话介绍：一款提供可爱动画集合的框架</span>

<span style="font-size: 15px">上榜理由：正如作者所说，它囊括了开发需求过程中所有的动画效果，集成进了这个简洁可爱的动画框架。7.6K的star数，证明了它在动画框架领域的战斗力，让它仅仅位列lottie-android和Material-Animations两个动画框架霸主之后，屈居第三名</span>

<span style="font-size: 15px">github [https://github.com/daimajia/AndroidViewAnimations](https://github.com/daimajia/AndroidViewAnimations)</span>

<span style="font-size: 15px">作者：daimajia</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
        compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.android.support:support-compat:25.1.1</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.daimajia.easing:library:2.0@aar</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.daimajia.androidanimations:library:2.2@aar</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

<span style="font-size: 15px">sample：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">YoYo.with(Techniques.Tada)
    .duration(</span><span style="color: #800080">700</span><span style="color: #000000">)
    .repeat(</span><span style="color: #800080">5</span><span style="color: #000000">)
    .playOn(findViewById(R.id.edit_area));</span></pre>

</div>

## 32. MaterialDrawer

<span style="font-size: 15px">一句话介绍：强大的塑料风格的抽屉框架</span>

<span style="font-size: 15px">上榜理由：7.6K的star数量，作者的持续更新状态，如果你还在犹豫上手SlidingMenu遇到bug没人管的困境，那么你可以入手它作为你的抽屉布局 </span>

<span style="font-size: 15px">github  https://github.com/mikepenz/MaterialDrawer</span>

<span style="font-size: 15px">作者：Mike Penz</span>

<span style="font-size: 15px">使用:</span>

<div class="cnblogs_code">

<pre>compile(<span style="color: #800000">'</span><span style="color: #800000">com.mikepenz:materialdrawer:5.9.2@aar</span><span style="color: #800000">'</span><span style="color: #000000">) {
    transitive</span> = <span style="color: #0000ff">true</span> <span style="color: #000000">}</span></pre>

</div>

<div class="cnblogs_code">

<pre><span style="color: #0000ff">new</span> DrawerBuilder().withActivity(<span style="color: #0000ff">this</span>).build();</pre>

</div>

##  33.Android-ObservableScrollView

<span style="font-size: 15px">一句话介绍：一款让视图滑动更具有视觉效果的滑动式框架</span>

<span style="font-size: 15px">上榜理由：7.5K的star数量，证明了它曾经的价值，github上提供了12种滑动效果，你可以用它弥补其他框架的不足，提升你的App体验！</span>

<span style="font-size: 15px">github [https://github.com/ksoichiro/Android-ObservableScrollView](https://github.com/ksoichiro/Android-ObservableScrollView)</span>

<span style="font-size: 15px">作者：Soichiro Kashima</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile com.github.ksoichiro:android-observablescrollview</pre>

</div>

## 34.CircleImageView

<span style="font-size: 15px">一句话介绍：圆角ImageView</span>

<span style="font-size: 15px">上榜理由：也许你已经听说过无数种展示圆角图片的方法，但如果你不尝试尝试CircleImageView，那么你的知识库会因为少了它黯然失色，有的时候完成需求是开发者优先考虑的，不同实现方法牵扯到的性能差异更值得让人深思，如果你有心在**图片性能**上有所涉猎，那么CircleImageView绝对不会让你败兴而归。最后别忘了记得去看Romain Guy的建议哟。</span>

<span style="font-size: 15px">github [https://github.com/hdodenhof/CircleImageView](https://github.com/hdodenhof/CircleImageView)</span>

<span style="font-size: 15px">作者：Henning Dodenhof</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
    ...
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">de.hdodenhof:circleimageview:2.1.0</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><<span style="color: #000000">de.hdodenhof.circleimageview.CircleImageView
    xmlns:app</span>=<span style="color: #800000">"</span><span style="color: #800000">http://schemas.android.com/apk/res-auto</span><span style="color: #800000">"</span> <span style="color: #000000">android:id</span>=<span style="color: #800000">"</span><span style="color: #800000">@+id/profile_image</span><span style="color: #800000">"</span> <span style="color: #000000">android:layout_width</span>=<span style="color: #800000">"</span><span style="color: #800000">96dp</span><span style="color: #800000">"</span> <span style="color: #000000">android:layout_height</span>=<span style="color: #800000">"</span><span style="color: #800000">96dp</span><span style="color: #800000">"</span> <span style="color: #000000">android:src</span>=<span style="color: #800000">"</span><span style="color: #800000">@drawable/profile</span><span style="color: #800000">"</span> <span style="color: #000000">app:civ_border_width</span>=<span style="color: #800000">"</span><span style="color: #800000">2dp</span><span style="color: #800000">"</span> <span style="color: #000000">app:civ_border_color</span>=<span style="color: #800000">"</span><span style="color: #800000">#FF000000</span><span style="color: #800000">"</span>/></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 35.logger

<span style="font-size: 15px">一句话介绍：一款让log日志优雅显示的框架</span>

<span style="font-size: 15px">上榜理由：logger作为调试框架，并未给出很强大的能力，它最大的亮点是优雅的输出log信息，并且支持多种格式：线程、Json、Xml、List、Map等，如果你整日沉迷于汪洋大海般的log信息不能自拔，logger就是你的指路明灯！6.6k个star让他位列调试框架第二名，屈居facebook的stetho之后</span>

<span style="font-size: 15px">github [https://github.com/orhanobut/logger](https://github.com/orhanobut/logger)</span>

<span style="font-size: 15px">作者：Orhan Obut</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.orhanobut:logger:2.1.1</span><span style="color: #800000">'</span></pre>

</div>

<div class="cnblogs_code">

<pre><span style="color: #000000">Logger.d(MAP);
Logger.d(SET);
Logger.d(LIST);
Logger.d(ARRAY);</span> <span style="color: #000000">Logger.json(JSON_CONTENT);
Logger.xml(XML_CONTENT);</span></pre>

</div>

## 36.agera

<span style="font-size: 15px">一句话介绍:一款服务于Android平台的响应式编程框架</span>

<span style="font-size: 15px">上榜理由：google专门推出一套响应式编程框架服务于Android开发者，相比于之响应式编程框架榜首的 RxJava RxAndroid，它更轻量，两者最大的不同点在于agera基于push event、pull data （VS Rx系列 push data）。</span>

<span style="font-size: 15px">github [https://github.com/google/agera](https://github.com/google/agera)</span>

<span style="font-size: 15px">作者：Google</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>  compile <span style="color: #800000">'</span><span style="color: #800000">com.google.android.agera:agera:1.3.0</span><span style="color: #800000">'</span></pre>

</div>

扩展能力

<div class="cnblogs_code">

<pre>  compile <span style="color: #800000">'</span><span style="color: #800000">com.google.android.agera:content:1.3.0</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.android.agera:database:1.3.0</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.android.agera:net:1.3.0</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.android.agera:rvadapter:1.3.0</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.android.agera:rvdatabinding:1.3.0</span><span style="color: #800000">'</span></pre>

</div>

## 37.BottomBar

<span style="font-size: 15px">一句话介绍：一款底部导航栏视图框架</span>

<span style="font-size: 15px">上榜理由：底部栏里的王者框架，6.3K的star数量，证明了它的优秀，完全遵循材料设计规范，上手非常方便。如果说缺点，无法设置icon与titile的间距，无法自定义视图的大小等，但这些都可以通过修改源代码解决，笔者献丑也修改了一套符合国内开发者的底部导航框架，即将开源。</span>

<span style="font-size: 15px">github  [https://github.com/roughike/BottomBar](https://github.com/roughike/BottomBar)</span>

<span style="font-size: 15px">作者：Iiro Krankka</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.roughike:bottom-bar:2.3.1</span><span style="color: #800000">'</span></pre>

</div>

## 38.Calligraphy

<span style="font-size: 15px">一句话介绍：一款自定义字体框架</span>

<span style="font-size: 15px">上榜理由：如果你还在为一键修改App内所有字体样式而烦恼，6.3K个star的Calligraphy就值得你拥有，它可以同时修改整个整个项目的Textview字体，也可以单独 设置某个Textview的字体，还在等什么，快来试试吧！</span>

<span style="font-size: 15px">github  [https://github.com/chrisjenx/Calligraphy](https://github.com/chrisjenx/Calligraphy)</span>

<span style="font-size: 15px">作者：Christopher Jenkins</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">uk.co.chrisjenx:calligraphy:2.3.0</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

## 39.AndroidSlidingUpPanel

<span style="font-size: 15px">一句话介绍：可拖动的滑动面板视图框架</span>

<span style="font-size: 15px">上榜理由：如果你的项目需要一个可拖拽的滑动式面板（展示某些详情信息，播放音乐，地图信息等），那么推荐你使用它，6.3k个star，来自创业公司umano的作品，证明它是用心推出的杰作</span>

<span style="font-size: 15px">github [https://github.com/umano/AndroidSlidingUpPanel](https://github.com/umano/AndroidSlidingUpPanel)</span>

<span style="font-size: 15px">作者：umano<span class="author">[
](https://github.com/umano)</span></span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">dependencies {
    repositories {
        mavenCentral()
    }
    
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.sothree.slidinguppanel:library:3.3.1</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 40.AppIntro

<span style="font-size: 15px">一句话介绍：一款提供快速制作欢迎页的框架</span>

<span style="font-size: 15px">上榜理由：笔者从未把打算把欢迎页框架纳入排行榜当中，作为国内开发者，ViewPager开发App的欢迎页已经是手到擒来的需求，为何一个开源的欢迎页框架会在github上拥有6.3k个star？也许你会不屑一顾，是的，往往就在不屑一顾的瞬间，机遇就悄悄溜走了。</span>

<span style="font-size: 15px">github [https://github.com/apl-devs/AppIntro](https://github.com/apl-devs/AppIntro)</span>

<span style="font-size: 15px">作者：Paolo Rotolo</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre> <span style="color: #000000">allprojects {
        repositories {
            ...
            maven { url</span> <span style="color: #800000">'</span><span style="color: #800000">https://jitpack.io</span><span style="color: #800000">'</span> <span style="color: #000000">}
        }
    }
    
    dependencies {
            compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.apl-devs:appintro:v4.2.0</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 41.recyclerview-animators

<span style="font-size: 15px">一句话介绍：一款为Recyclerview提供扩展动画能力的框架</span>

<span style="font-size: 15px">上榜理由：有一句老话：如果有天你失去对新事物的兴趣，那就说明你老了。recyclerview已经推出快三年了，还在用listview的人们，是否已经发掘自己渐渐变老；不要灰心，快为你的项目加入recyclerview-animators框架吧，为“自己”加入新鲜的血液和能量！（笔者备注：6.2K个star）</span>

<span style="font-size: 15px">github  [https://github.com/wasabeef/recyclerview-animators](https://github.com/wasabeef/recyclerview-animators)</span>

<span style="font-size: 15px">作者；[https://github.com/wasabeef](https://github.com/wasabeef)</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {</span> <span style="color: #008000">//</span> <span style="color: #008000">jCenter</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">jp.wasabeef:recyclerview-animators:2.2.6</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

## 42.dagger

<span style="font-size: 15px">一句话介绍：一款通过依赖注入降低程序间耦合的开发框架</span>

<span style="font-size: 15px">上榜理由：github 上dagger1版本 有6.2k个star ， dagger2版本有7.3k个；由square完成的dagger1版本，到如今google团队接手的dagger2版本，强力开发团队保证了代码在设计上的优越性；如果你想探究Android 领域的设计模式，这也是不错的选择。</span>

<span style="font-size: 15px">官网地址：[https://google.github.io/dagger/](https://google.github.io/dagger/)</span>

<span style="font-size: 15px">github ：[https://github.com/google/dagger](https://github.com/google/dagger)</span>

<span style="font-size: 15px">作者：google</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">dependencies {
  compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.dagger:dagger:2.x</span><span style="color: #800000">'</span> <span style="color: #000000">annotationProcessor</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.dagger:dagger-compiler:2.x</span><span style="color: #800000">'</span> <span style="color: #000000">}
If you</span><span style="color: #800000">'</span><span style="color: #800000">re using classes in dagger.android you</span><span style="color: #800000">'</span><span style="color: #000000">ll also want to include:

compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.dagger:dagger-android:2.x</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.dagger:dagger-android-support:2.x</span><span style="color: #800000">'</span>
annotationProcessor <span style="color: #800000">'</span><span style="color: #800000">com.google.dagger:dagger-android-processor:2.x</span><span style="color: #800000">'</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 43.Android-Bootstarp

<span style="font-size: 15px">一句话介绍：一款提供在Android应用上实现Bootstrap（web框架）所作出效果的框架</span>

<span style="font-size: 15px">上榜理由：榜单上第二款响应web技术的Android 端框架，还记得第一名是谁吗——flexbox-layout，作为Android开发者，你有必要去了解Web技术了。5.9k个star，证明它不容小觑</span>

<span style="font-size: 15px">github [https://github.com/Bearded-Hen/Android-Bootstrap](https://github.com/Bearded-Hen/Android-Bootstrap)</span>

<span style="font-size: 15px">作者:Bearded-Hen团队</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
   compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.beardedhen:androidbootstrap:{X.X.X}</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

## 44.RxBinding

<span style="font-size: 15px">一句话介绍：一款提供UI组件事件响应能力的框架</span>

<span style="font-size: 15px">上榜理由：如果你还未开始RxAndroid 之旅，RxBinding可以作为你的第一站，通过RXBinding，你将理解响应式编程的快乐，让项目里的事件流程更清晰。5.6K个star，RxAndroid作者亲自操刀，快来试用吧！</span>

<span style="font-size: 15px">github  [https://github.com/JakeWharton/RxBinding](https://github.com/JakeWharton/RxBinding)</span>

<span style="font-size: 15px">作者：JakeWharton</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">Platform bindings:

compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.jakewharton.rxbinding2:rxbinding:2.0.0</span><span style="color: #800000">'</span>
<span style="color: #800000">'</span><span style="color: #800000">support-v4</span><span style="color: #800000">'</span> <span style="color: #000000">library bindings:

compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.jakewharton.rxbinding2:rxbinding-support-v4:2.0.0</span><span style="color: #800000">'</span>
<span style="color: #800000">'</span><span style="color: #800000">appcompat-v7</span><span style="color: #800000">'</span> <span style="color: #000000">library bindings:

compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.jakewharton.rxbinding2:rxbinding-appcompat-v7:2.0.0</span><span style="color: #800000">'</span>
<span style="color: #800000">'</span><span style="color: #800000">design</span><span style="color: #800000">'</span> <span style="color: #000000">library bindings:

compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.jakewharton.rxbinding2:rxbinding-design:2.0.0</span><span style="color: #800000">'</span>
<span style="color: #800000">'</span><span style="color: #800000">recyclerview-v7</span><span style="color: #800000">'</span> <span style="color: #000000">library bindings:

compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.jakewharton.rxbinding2:rxbinding-recyclerview-v7:2.0.0</span><span style="color: #800000">'</span>
<span style="color: #800000">'</span><span style="color: #800000">leanback-v17</span><span style="color: #800000">'</span> <span style="color: #000000">library bindings:

compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.jakewharton.rxbinding2:rxbinding-leanback-v17:2.0.0</span><span style="color: #800000">'</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 45.ListViewAnimations

<span style="font-size: 15px">一句话介绍：一款为ListView提供动展示画效果能力的框架</span>

<span style="font-size: 15px">上榜理由：如果有一天我承认自己老了，我还会排排我的兄弟——ListView，证明我和它一起战斗过。ListViewAnimations的存在就是证明我们这些“老年人”仍有用武之地，也许你有说不出口的难处，无法体会到RecyclerView里动画的快乐，拥有ListViewAnimations，你一样可以骄傲的说，我的孩子（每个item）也有自己的动效啦。（笔者备注 5.6K个star）</span>

<span style="font-size: 15px">github  [https://github.com/nhaarman/ListViewAnimations](https://github.com/nhaarman/ListViewAnimations)</span>

<span style="font-size: 15px">作者：nhaarman</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
    mavenCentral()
}

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.nhaarman.listviewanimations:lib-core:3.1.0@aar</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.nhaarman.listviewanimations:lib-manipulation:3.1.0@aar</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.nhaarman.listviewanimations:lib-core-slh:3.1.0@aar</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 46.UItimateRecyclerView

<span style="font-size: 15px">一句话介绍：一款提供刷新、加载更多、动画特效等额外能力的RecyclerView框架</span>

<span style="font-size: 15px">上榜理由：榜单上第三次出现RecyclerView的身影，足以证明RecyclerView的优异性，5.5K个star，框架里所提供众多的能力，如果你是个功利开发者，那么此框架会为你节省很多学习时间，它可以完成多item式布局的大多数需求，值得注意的是，这个项目也是在其他项目的思路上二次开发的。</span>

<span style="font-size: 15px">github  [https://github.com/cymcsg/UltimateRecyclerView](https://github.com/cymcsg/UltimateRecyclerView)</span>

<span style="font-size: 15px">作者：MarshalChen</span>

<span style="font-size: 15px">使用</span>：

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
    jcenter()
    }
dependencies {
    ...
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.marshalchen.ultimaterecyclerview:library:0.7.2</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 47.uCrop

<span style="font-size: 15px">一句话介绍：一款优雅的图片裁剪框架</span>

<span style="font-size: 15px">上榜理由：5.3K个star，图片编辑模块单独拎出来也是一款优雅的App。</span>

<span style="font-size: 15px">github  [https://github.com/Yalantis/uCrop](https://github.com/Yalantis/uCrop)</span>

<span style="font-size: 15px">作者：Yalantis</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">allprojects {
   repositories {
      jcenter()
      maven { url</span> <span style="color: #800000">"</span><span style="color: #800000">https://jitpack.io</span><span style="color: #800000">"</span> <span style="color: #000000">}
   }
}

compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.yalantis:ucrop:2.2.1</span><span style="color: #800000">'</span> </pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 48.RxJava-Android-Samples

<span style="font-size: 15px">一句话介绍：一款介绍RxJava使用场景的app</span>

<span style="font-size: 15px">上榜理由：榜单出现的第一个**“仅仅为告诉你如何使用另一个项目”**的开源项目，它可以说是RxJava的用例，你想得到的想不到的RxJava用法这里都有，这就是为什么它以5.2k个star矗立在这份榜单里的原因。遗憾自己没有创作这么一个受人追捧的demo？赶快动手写个其他的“XX项目用例吧”</span>

<span style="font-size: 15px">github  [https://github.com/kaushikgopal/RxJava-Android-Samples](https://github.com/kaushikgopal/RxJava-Android-Samples)</span>

<span style="font-size: 15px">作者：kaushikgopal</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone到本地慢慢探索吧</span>

## 49.AndroidAutoLayout

<span style="font-size: 15px">一句话介绍：一个提供适配能力的框架</span>

<span style="font-size: 15px">上榜理由：5.2K个star，鸿洋老弟的作品，适合小项目的开发团队，拿到设计MM的px像素设计稿是不是很头疼捏？这个框架一键式搞定你的问题，它有很多的不足，但在追求完美适配的路上，你值得探索和了解它！笔者并不推荐把它应用到已经成熟运行的项目中，毕竟市面上已经有太多的适配解决方案了，适配问题就像是个大杂烩，想炒一盘好菜，就得备好各种佐料（适配小方案），当你把各种小佐料用的炉火纯青的时候，你离美食大厨就不远了。</span>

<span style="font-size: 15px">github [https://github.com/hongyangAndroid/AndroidAutoLayout](https://github.com/hongyangAndroid/AndroidAutoLayout)</span>

<span style="font-size: 15px">作者：张鸿洋</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.zhy:autolayout:1.4.5</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

## 50.EffectiveAndroidUI

<span style="font-size: 15px">一句话介绍：一款讲解高效展示UI的教学型App</span>

<span style="font-size: 15px">上榜理由：编程新手很难对MVC MVP,MVVM等模式有深刻的理解，如果有一个示例型app，那对初学者会有很大裨益，笔者在遇到它时也是相见恨晚。4.8K个star，证明了它经受了广大开发者的考验与审视，其中Effective UI的编程思想更是与Android官方课程里的Effective UI课程不谋而合，并且，此项目还包含了fragment、dagger、主题样式、Butterknife等众多小知识点，作为编程初学者的学习用例再适合不过了</span>

<span style="font-size: 15px">github  [https://github.com/pedrovgs/EffectiveAndroidUI](https://github.com/pedrovgs/EffectiveAndroidUI)</span>

<span style="font-size: 15px">作者：Pedro Vicente </span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone项目到本地</span>

## 51.Luban

<span style="font-size: 15px">一句话介绍：最接近微信的图片压缩框架</span>

<span style="font-size: 15px">上榜理由：好的思路总是可以让你大放异彩，Luban仅以图片压缩单一功能，俘获了4.8K个star，证明了它在图片压缩上的造诣，它可能不是最优秀的，但它是让你我最接近伟大的项目</span>

<span style="font-size: 15px">github  [https://github.com/Curzibn/Luban](https://github.com/Curzibn/Luban)</span>

<span style="font-size: 15px">作者：Curzibn</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">top.zibin:Luban:1.1.1</span><span style="color: #800000">'</span></pre>

</div>

## 52.DroidPlugin

一句话介绍：一款热门的插件化开发框架

上榜理由：4.8K个star，插件化框架榜单第一名，，360团队出品，框架质量有保证，有成功案例——360手机助手，并且持续维护着

github [https://github.com/DroidPluginTeam/DroidPlugin/blob/master/readme_cn.md](https://github.com/DroidPluginTeam/DroidPlugin/blob/master/readme_cn.md)

作者：Andy Zhang

使用:

clone项目到本地

## 53\. otto

<span style="font-size: 15px">一句话介绍:一款老旧且强大的事件总线框架</span>

<span style="font-size: 15px">上榜理由：4.8K个star，是square团队早先推出的事件响应型框架，淘宝app的事件驱动也是基于此框架封装的，如今square已经建议开发者采用RxJava RxAndroid来代替otto了。但otto仍有与EventBus横向对比的价值，纵向来说，otto与square自家开发的Rx系列框架的差异同样值得开发者们去探究。</span>

<span style="font-size: 15px">github [https://github.com/square/otto](https://github.com/square/otto)</span>

<span style="font-size: 15px">作者：square</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">repositories {
    mavenCentral()
    maven { url</span> <span style="color: #800000">"</span><span style="color: #800000">https://oss.sonatype.org/content/repositories/snapshots/</span><span style="color: #800000">"</span> <span style="color: #000000">}
}

compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.michaelpardo:activeandroid:3.1.0-SNAPSHOT</span><span style="color: #800000">'</span></pre>

</div>

## 54.u2020

<span style="font-size: 15px">一句话介绍：一款提供**Dagger的高级教学示例**的app（额，名字是有点绕）</span>

<span style="font-size: 15px">上榜理由：4.7K个star，JakeWharton牵头开发的教学类app，教你使用Dagger在其他高级框架的用法，它展示了Dagger与ButterKnife、Retrofit、Moshi、Picasso、Okhttp、RxJava、Timber、Madge、LeakCanar等众多优秀框架结合起来的高级用法，你也可以借鉴到自己的项目当中</span>

<span style="font-size: 15px">github  [https://github.com/JakeWharton/u2020](https://github.com/JakeWharton/u2020)</span>

<span style="font-size: 15px">作者：JakeWharton</span>

<span style="font-size: 15px"> </span>

## 55.buck

<span style="font-size: 15px">一句话介绍：buck是一个快速构建系统</span>

<span style="font-size: 15px">上榜理由：facebook+google出身的作者，对构建代码的出色理解，加上大型团队的维护，以及增量更新时的快速高效，让buck成为了微信Android团队构建项目的首选，构建大型项目时，它比gradle更快，然而中小公司并不适合此框架，但作为立志在框架设计领域有一番作为的人们，欢迎来一探究竟</span>

<span style="font-size: 15px">官网地址：[https://buckbuild.com/](https://buckbuild.com/)</span>

<span style="font-size: 15px">github  [https://github.com/facebook/buck](https://github.com/facebook/buck)</span>

<span style="font-size: 15px">作者：facebook</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>linux or mac system  +docs</pre>

</div>

## 56.PermissionsDispatcher

<span style="font-size: 15px">一句话介绍：一款基于注解的提供**解决运行时危险权限**方案的框架</span>

<span style="font-size: 15px">上榜理由：自Android6.0 Google提出危险权限一词起，用户安全性被提到一定的高度，一些运行时对用户较为危险的权限将不再自动被开发者获取，需要经过用户批准，开发者才可以继续使用该权限，如果你曾经被权限问题搞的抓耳挠腮，建议你试试这个框架，它足够解决你的问题</span>

<span style="font-size: 15px">官网地址：[https://hotchemi.github.io/PermissionsDispatcher/](https://hotchemi.github.io/PermissionsDispatcher/)</span>

<span style="font-size: 15px">github [https://github.com/hotchemi/PermissionsDispatcher](https://github.com/hotchemi/PermissionsDispatcher)</span>

<span style="font-size: 15px">作者：Shintaro Katafuchi</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">dependencies {
  compile(</span><span style="color: #800000">'</span><span style="color: #800000">com.github.hotchemi:permissionsdispatcher:${latest.version}</span><span style="color: #800000">'</span><span style="color: #000000">) {</span>
      exclude module: <span style="color: #800000">"</span><span style="color: #800000">support-v13</span><span style="color: #800000">"</span> <span style="color: #000000">}
  annotationProcessor</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.hotchemi:permissionsdispatcher-processor:${latest.version}</span><span style="color: #800000">'</span> <span style="color: #000000">}</span>  <span style="color: #000000">repositories {
  jcenter()
  maven { url</span> <span style="color: #800000">'</span><span style="color: #800000">http://oss.jfrog.org/artifactory/oss-snapshot-local/</span><span style="color: #800000">'</span> <span style="color: #000000">}
}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 57.android-gif-drawable

<span style="font-size: 15px">一句话介绍:一款提供展示GIF动画能力的视图框架</span>

<span style="font-size: 15px">上榜理由：据我所查国内著名App——知乎使用了android-gif-drawable，因此证明了它的存在价值，尽管在榜单第十一位介绍了lottie-android直接应用AE动画的示例，但AE设计师不是每个公司都配备的，GIF的存在，就必然存在了展示GIF的需要，它值得你拥有！</span>

<span style="font-size: 15px">github [https://github.com/koral--/android-gif-drawable](https://github.com/koral--/android-gif-drawable)</span>

<span style="font-size: 15px">作者：Karol Wrótniak</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
    mavenCentral()
    maven { url</span> <span style="color: #800000">"</span><span style="color: #800000">https://oss.sonatype.org/content/repositories/snapshots</span><span style="color: #800000">"</span> <span style="color: #000000">}
}
dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">pl.droidsonroids.gif:android-gif-drawable:1.2.+</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 58.Apktool

<span style="font-size: 15px">一句话介绍：一款反编译apk的工具</span>

<span style="font-size: 15px">上榜理由：开源的反编译工具，对于志在了解apk逆向破解的诸位，值得拥有，4.5k个star，逆向破解apk神器！</span>

<span style="font-size: 15px">github  [https://github.com/iBotPeaches/Apktool](https://github.com/iBotPeaches/Apktool)</span>

<span style="font-size: 15px">官网地址：[https://ibotpeaches.github.io/Apktool/](https://ibotpeaches.github.io/Apktool/)</span>

<span style="font-size: 15px">作者：Connor Tumbleson</span>

## 59.dynamic-load-apk

<span style="font-size: 15px">一句话介绍：插件化开发框架</span>

<span style="font-size: 15px">上榜理由：4.5k个star，位于插件化开发框架第二名（第一名来自360团队），全面的文档介绍让你很快就能上手插件化开发，如果你喜欢大段文字讲解，那么这个项目一定适合你</span>

<span style="font-size: 15px">github：[https://github.com/singwhatiwanna/dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk)</span>

<span style="font-size: 15px">作者：singwhatiwanna</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">github上的文档配合作者博客更配哟</span>

## 60.atlas

<span style="font-size: 15px">一句话介绍：淘宝推出的组件化开发框架</span>

<span style="font-size: 15px">上榜理由：淘宝团队所出的精品，atlas框架提供了解耦、组件、动态的开发能力，4.5k个star让他位列组件化开发框架第一名</span>

<span style="font-size: 15px">github [https://github.com/alibaba/atlas](https://github.com/alibaba/atlas)</span>

<span style="font-size: 15px">作者：alibaba</span>

##  61.volley

<span style="font-size: 15px">一句话介绍：google推荐使用的Android端网络请求框架</span>

<span style="font-size: 15px">上榜理由：4.4k个star，并不是他不够优秀，而是使用volley已经渐渐成为广大开发者的习惯</span>

<span style="font-size: 15px">github h<a target="_blank">ttps://github.com/google/volley</a>（新版volley地址）</span>

<span style="font-size: 15px">作者：google</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone源码到本地</span>

## 62.androidmvp

<span style="font-size: 15px">一句话介绍：一款展示Android端Mvp设计的demo</span>

<span style="font-size: 15px">上榜理由：榜单里为数不多、仅凭展示某种设计模式就获得4.2K个star的项目，如果你有尝试mvp的打算，androidmvp可以作为你的前哨站</span>

<span style="font-size: 15px">github  [https://github.com/antoniolg/androidmvp](https://github.com/antoniolg/androidmvp)</span>

<span style="font-size: 15px">作者：Antonio Leiva</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone到本地</span>

## 63.SwipeBackLayout

<span style="font-size: 15px">一句话介绍:一款可以让你通过滑动手势关闭页面的的框架</span>

<span style="font-size: 15px">上榜理由：仿微信滑动退出当前聊天界面的效果，提供了activity的滑动关闭能力，通过这种思路，实现fragment的滑动关闭轻而易举;笔者坚持建议诸位clone源码到本地探索一番；4.2k个star证明很多人都喜爱它</span>

<span style="font-size: 15px">github [https://github.com/ikew0ng/SwipeBackLayout](https://github.com/ikew0ng/SwipeBackLayout)</span>

<span style="font-size: 15px">作者：ike_w0ng</span>

<span style="font-size: 15px"> 使用:</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">me.imid.swipebacklayout.lib:library:1.0.0</span><span style="color: #800000">'</span></pre>

</div>

## 64.FlycoTabLayout

<span style="font-size: 15px">一句话介绍：一款可以让作出多种多样指示器效果的框架</span>

<span style="font-size: 15px">上榜理由：尽管我们没有理由为了给app加入页面指示器功能就集成2.5M的依赖库，但是作为了解viewpager或swip views的指示器设计原理的优秀框架，你值得打开它试试，笔者建议单独拆分所需源码，加入到自己的项目中去。4.1K个star，二次开发的作品，仍然推荐！</span>

<span style="font-size: 15px">github  [https://github.com/H07000223/FlycoTabLayout](https://github.com/ikew0ng/SwipeBackLayout)</span>

<span style="font-size: 15px">作者：Flyco</span>

## 65.android-testing

<span style="font-size: 15px">一句话介绍：一款展示四大自动化测试框架用例的demo（Espresso，UiAutomator，AndroidJunitRunner，JUnit4）</span>

<span style="font-size: 15px">上榜理由：学习者经常会陷入似懂非懂的境地，如果你有幸学习过Android Testing Support Library site的课程，那么你一定对android的四大测试框架迫不及待，这款demo非常适合你，快来学习这个4.1k个star的明星项目吧</span>

<span style="font-size: 15px">github [https://github.com/googlesamples/android-testing](https://github.com/googlesamples/android-testing)</span>

<span style="font-size: 15px">作者：googlesampes团队</span>

## 66.FileDownloader

<span style="font-size: 15px">一句话介绍：一款高效、稳定、灵活、易用的**文件下载引擎**</span>

<span style="font-size: 15px">上榜理由：4.1k证明了它有多受人喜爱，文件下载看似简单的背后暗藏了多少的坑坑点点，我知道你有能力自己实现文件下载功能，但优秀的框架可以提升你的设计编码能力，这款框架可以提升你的实力！</span>

<span style="font-size: 15px">github [https://github.com/lingochamp/FileDownloader](https://github.com/lingochamp/FileDownloader)</span>

<span style="font-size: 15px">作者:LingoChamp团队</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.liulishuo.filedownloader:library:1.5.5</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

##  67.JieCaoVideoPlayer

<span style="font-size: 15px">一句话介绍：基于MediaPlayer api——VideoView 的多媒体播放框架</span>

<span style="font-size: 15px">上榜理由：榜单里第三款多媒体播放框架，它以灵巧的身姿挤入本榜单，精巧是它最大的优点，不到100k，拥有它，你就可以快速开发类似今日头条那样的视频播放效果，4k个star，证明它值得一试</span>

<span style="font-size: 15px">github [https://github.com/lipangit/JieCaoVideoPlayer](https://github.com/lipangit/JieCaoVideoPlayer)</span>

<span style="font-size: 15px">作者：Nathen</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">fm.jiecao:jiecaovideoplayer:5.5.4</span><span style="color: #800000">'</span></pre>

</div>

## 68.glide-transformations

<span style="font-size: 15px">一句话介绍：为众多著名图片加载框架**提供图片形状变幻能力**的框架</span>

<span style="font-size: 15px">上榜理由：在榜单靠前的部分已经介绍过glide，Picasso，Fresco等图片加载框架，glide-transformations就是一款为他们提供图片变形能力的框架，使用起来非常简单，因此受到了大家的喜爱，github上有3.8K个star</span>

<span style="font-size: 15px">github  [https://github.com/wasabeef/glide-transformations](https://github.com/wasabeef/glide-transformations)</span>

<span style="font-size: 15px">作者：Daichi Furiya</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
    jcenter()
}

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">jp.wasabeef:glide-transformations:2.0.2</span><span style="color: #800000">'</span>
    <span style="color: #008000">//</span> <span style="color: #008000">If you want to use the GPU Filters</span>
    compile <span style="color: #800000">'</span><span style="color: #800000">jp.co.cyberagent.android.gpuimage:gpuimage-library:1.4.1</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

<span style="font-size: 15px">在Glide里设置变幻效果</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">Set Glide Transform.

Glide.with(</span><span style="color: #0000ff">this</span><span style="color: #000000">).load(R.drawable.demo)
        .bitmapTransform(</span><span style="color: #0000ff">new</span> <span style="color: #000000">BlurTransformation(context))
        .into((ImageView) findViewById(R.id.image));</span></pre>

</div>

## 69.android-gpuimage

<span style="font-size: 15px">一句话介绍：一款基于OpenGL的图片渲染引擎</span>

<span style="font-size: 15px">上榜理由：放下GpuImage在IOS平台的荣誉不谈，Android版的android-gpuimage就提供多达70多种图片渲染效果，你还在好奇美图秀秀是如何实现图片变幻的？有了它，一切都不是问题。如果你是美图工具类的工程师，此框架的建设思路也会对你大有裨益。笔者也是通过android-gpuimage仿造了美图App并俘获女友芳心的，再次为它的实力点赞。ios版+android版一共19k个star，已经证明了它的实力，还在等什么呢？</span>

<span style="font-size: 15px">github：[https://github.com/CyberAgent/android-gpuimage](https://github.com/CyberAgent/android-gpuimage)</span>

<span style="font-size: 15px">作者：CyberAgent 团队</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
    jcenter()
}

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">jp.co.cyberagent.android.gpuimage:gpuimage-library:1.4.1</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

<span style="font-size: 15px">更多的改造方法，还需要阅读Ios的编程文档，对于有毅力的小伙伴强力推荐！</span>

## 70.RxPermissions

<span style="font-size: 15px">一句话介绍：一款基于RxJava完成权限申请的框架</span>

<span style="font-size: 15px">上榜理由：榜单里第二款提供权服务的框架，基于RxJava的设计，让你可以专心写业务，3.7K个star已经证明了它的实用价值</span>

<span style="font-size: 15px">github [https://github.com/tbruyelle/RxPermissions](https://github.com/tbruyelle/RxPermissions)</span>

<span style="font-size: 15px">作者：Thomas Bruyelle</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
    jcenter()</span> <span style="color: #008000">//</span> <span style="color: #008000">If not already there</span>
<span style="color: #000000">}

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.tbruyelle.rxpermissions:rxpermissions:0.9.4@aar</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

<span style="font-size: 15px">优雅的使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre>RxPermissions rxPermissions = <span style="color: #0000ff">new</span> RxPermissions(<span style="color: #0000ff">this</span>);

<span style="color: #000000">rxPermissions
    .request(Manifest.permission.CAMERA)
    .subscribe(granted</span> -> <span style="color: #000000">{</span> <span style="color: #0000ff">if</span> (granted) { <span style="color: #008000">//</span> <span style="color: #008000">I can control the camera now</span>
        } <span style="color: #0000ff">else</span> <span style="color: #000000">{</span> <span style="color: #008000">//</span> <span style="color: #008000">Oups permission denied</span>
 <span style="color: #000000">}
    });</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 71.freeline

<span style="font-size: 15px">一句话介绍：一款动态替换的编译构建框架</span>

<span style="font-size: 15px">上榜理由：继Facebook的Buck，Androdi官方的InstRun之后，蚂蚁金服推出了Freeline编译框架，官网宣称**Freeline与业内主流构建方式相比仍然有数倍的速度领先;**排行有先后，编译速度并不在本榜单排序的考据因素中，因此freeline以3.7个star，暂列编译框架第二名</span>

<span style="font-size: 15px">官网地址：[https://www.freelinebuild.com/](https://www.freelinebuild.com/)</span>

<span style="font-size: 15px">github：[https://github.com/alibaba/freeline](https://github.com/alibaba/freeline)</span>

<span style="font-size: 15px">作者：alibaba</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">buildscript {
    repositories {
        jcenter()
    }
    dependencies {
        classpath</span> <span style="color: #800000">'</span><span style="color: #800000">com.antfortune.freeline:gradle:0.8.7</span><span style="color: #800000">'</span> <span style="color: #000000">}
}</span></pre>

<pre>apply <span class="pl-c1">plugin: <span class="pl-s"><span class="pl-pds">'com.antfortune.freeline<span class="pl-pds">'

<span class="pl-en">android {
    <span class="pl-k">...
}</span></span></span></span></span></span></pre>

File → Settings... → Plugins → Browse repositories →freeline.

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 72.RxLifecycle

<span style="font-size: 15px">一句话介绍：一款提供在**使用RxJava过程中管理Activity和Fragment生命周期能力**的框架</span>

<span style="font-size: 15px">上榜理由：在榜单靠前的部分，你已经了解RxJava和RxAndroid的强大之处，但部分粗心的开发者因为没有及时取消订阅而产生严重的内存泄漏，不要担心，RxLifecycle可以为你解决难题，在gtihub上拥有3.7K个star，国内知名软件——知乎和淘宝也都在使用它</span>

<span style="font-size: 15px">github  [https://github.com/trello/RxLifecycle](https://github.com/trello/RxLifecycle)</span>

<span style="font-size: 15px">作者：trello团队</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone源码到本地</span>

## 73.classyshark

<span style="font-size: 15px">一句话介绍：一款可执行文件浏览器</span>

<span style="font-size: 15px">上榜理由：榜单里继Apktool之后第二款apk逆向工具，如果你喜欢优雅的图形数据展示，那么你一定不能错过他，classyshark可以将破解的结果以图形化展示用户，方便分析，3.7K个star，让它暂列apk逆向工具第二位！</span>

<span style="font-size: 15px">github  [https://github.com/google/android-classyshark](https://github.com/google/android-classyshark)</span>

<span style="font-size: 15px">作者：google</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px"><span style="color: #24292e; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;">下载 </span>[JAR](https://github.com/google/android-classyshark/releases)<span style="color: #24292e; font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;"> </span></span>

## 74.acra

<span style="font-size: 15px">一句话介绍：一款提供**记录****APP崩溃日志能力**的框架</span>

<span style="font-size: 15px">上榜理由：如果你面临着收集APP崩溃日志的需求，那么acra是个不错的选择。3.7K个star，让acra位列崩溃日志框架排行榜第一名，acra有足够的能力记录线上APP，并且发回服务端，acra也提供了相当棒的崩溃日志统计服务端框架<span style="background-color: #f5f8fd; font-family: monospace; text-indent: 28px">Acralyzer</span>，cralyzer工作在Apache CouchDB之上，所以除了CouchDB之外，没有必要安装任何额外的软件，移动端开发者也可以借此学习服务端的建设，一举两得！</span>

<span style="font-size: 15px">github [https://github.com/ACRA/acra](https://github.com/ACRA/acra)</span>

<span style="font-size: 15px">服务端github  [https://github.com/ACRA/acralyzer](https://github.com/ACRA/acralyzer)</span>

<span style="font-size: 15px">作者：acra团队</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">没有什么方法比clone源码到本地更方便了</span>

## 75.DiskLruCache

<span style="font-size: 15px">一句话介绍：一款提供**磁盘文件缓存管理能力**的框架</span>

<span style="font-size: 15px">上榜理由：3.7k个star并不足以说明DiskLruCache的优秀，仅仅以管理磁盘文件能力单独拎出来成为一个框架，作者需要很大的勇气，很幸运，作者做到了，并且也成为Google官网提倡的缓存  ；如还记得上次做“一键清除缓存”、“查看缓存文件大小”功能是什么时候吗？DiskLruCache一句话就可以搞定！</span>

<span style="font-size: 15px">github [https://github.com/JakeWharton/DiskLruCache](https://github.com/JakeWharton/DiskLruCache)</span>

<span style="font-size: 15px">作者：JakeWharton</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.jakewharton:disklrucache:2.0.2</span><span style="color: #800000">'</span></pre>

</div>

<span style="font-size: 15px">或者下载 [latest .jar](https://search.maven.org/remote_content?g=com.jakewharton&a=disklrucache&v=LATEST)</span>

## 76.dexposed

<span style="font-size: 15px">一句话介绍：一款支撑阿里大部分App客户端热修复、线上调试能力的框架</span>

<span style="font-size: 15px">上榜理由：榜单上再次出现热修复框架的身影，证明App热修复技术的火热，dexposed提供图形化的性能监控、在线热修复bug漏洞、支持AOP编程思想等，不论你是企业热修复技术的设计者还是打算在热修复领域一探究竟的新人，这款框架很适合你。3.5k个star，证明它作为一门技术框架的存在，是多么令人喜爱！</span>

<span style="font-size: 15px">github  [https://github.com/alibaba/dexposed](https://github.com/alibaba/dexposed)</span>

<span style="font-size: 15px">作者：alibaba</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
        compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.taobao.android:dexposed:0.1.1@aar</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

## 77.Litho

<span style="font-size: 15px">一句话介绍：一款提供**高效构建UI能力**的框架 </span>

<span style="font-size: 15px">上榜理由：作为一款专门构建UI的框架，Litho高效的地方在于：单独开辟了用于渲染和布局的线程，然后将创建好的组件传递给UI线程去完成最终的渲染，使用更少的视图层级，来提升界面的滚动速度，值得注意的是，它仅支持开发者作出**不可改变的UI组件** **,**3.5K个star，证明了它在构建UI领域的价值，更多的妙处，期待你亲自去发掘！</span>

<span style="font-size: 15px">github  [https://github.com/facebook/litho](https://github.com/facebook/litho)</span>

<span style="font-size: 15px">作者：facebook</span>

<span style="font-size: 15px"> 使用</span>：

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">ependencies {</span> <span style="color: #008000">//</span> <span style="color: #008000">...</span> <span style="color: #008000">//</span> <span style="color: #008000">Litho</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.litho:litho-core:0.3.1</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.facebook.litho:litho-widget:0.3.1</span><span style="color: #800000">'</span> <span style="color: #000000">provided</span> <span style="color: #800000">'</span><span style="color: #800000">com.facebook.litho:litho-annotations:0.3.1</span><span style="color: #800000">'</span> <span style="color: #000000">annotationProcessor</span> <span style="color: #800000">'</span><span style="color: #800000">com.facebook.litho:litho-processor:0.3.1</span><span style="color: #800000">'</span>

  <span style="color: #008000">//</span> <span style="color: #008000">SoLoader</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.soloader:soloader:0.2.0</span><span style="color: #800000">'</span>

  <span style="color: #008000">//</span> <span style="color: #008000">Optional</span> <span style="color: #008000">//</span> <span style="color: #008000">For debugging</span>
  debugCompile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.litho:litho-stetho:0.3.1</span><span style="color: #800000">'</span>

  <span style="color: #008000">//</span> <span style="color: #008000">For integration with Fresco</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.litho:litho-fresco:0.3.1</span><span style="color: #800000">'</span>

  <span style="color: #008000">//</span> <span style="color: #008000">For testing</span>
  testCompile <span style="color: #800000">'</span><span style="color: #800000">com.facebook.litho:litho-testing:0.3.1</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 78.mosby

<span style="font-size: 15px">一句话介绍：一款提供**构建MVP项目能力**的框架</span>

<span style="font-size: 15px">上榜理由：榜单靠前的部分已经介绍了MVC,MVVM,MVP的框架项目，想必此时你在构建企业项目架构上，选择或者开发一款合适的MVP框架迫在眉睫，mosby可以作为你的第一步参考，你可以封装它，也可以照抄它，无论如何，3.4K个star，证明了它在框架设计上有多受开发者的喜爱</span>

<span style="font-size: 15px">github [https://github.com/sockeqwe/mosby](https://github.com/sockeqwe/mosby)</span>

<span style="font-size: 15px">作者：Hannes Dorfmann</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">dependencies {

  compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.hannesdorfmann.mosby3:mvi:3.0.4</span><span style="color: #800000">'</span> <span style="color: #008000">//</span> <span style="color: #008000">Model-View-Intent</span> <span style="color: #008000">//</span> <span style="color: #008000">or</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.hannesdorfmann.mosby3:mvp:3.0.4</span><span style="color: #800000">'</span> <span style="color: #008000">//</span> <span style="color: #008000">Plain MVP</span> <span style="color: #008000">//</span> <span style="color: #008000">or</span>
  compile <span style="color: #800000">'</span><span style="color: #800000">com.hannesdorfmann.mosby3:viewstate:3.0.4</span><span style="color: #800000">'</span> <span style="color: #008000">//</span> <span style="color: #008000">MVP + ViewState support</span>
}</pre>

<pre><span class="pl-en">allprojects {
  repositories {
    <span class="pl-k">...

    maven { url <span class="pl-s"><span class="pl-pds">"https://oss.sonatype.org/content/repositories/snapshots/<span class="pl-pds">" }
}</span></span></span></span></span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 79.AndResGuard

<span style="font-size: 15px">一句话介绍：一款提供资源文件路径混淆 的工具</span>

<span style="font-size: 15px">上榜理由：如果你是个对APK大小很敏感的人，那么AndResGuard一定适合你，它的原理类似Java Proguard，但是只针对资源。他会将原本冗长的资源路径变短，例如将`res/drawable/wechat`变为`r/d/a，3.4K个star，证明了在优化APK道路上，你不是一个人在战斗！`</span>

<span style="font-size: 15px">github  [https://github.com/shwenzhang/AndResGuard](https://github.com/shwenzhang/AndResGuard)</span>

<span style="font-size: 15px">作者：wechat team</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone项目到本地，其实也就是个三两句话的文档</span>

## 80.StatusBarUtil

<span style="font-size: 15px">一句话介绍：一款提供**设置沉浸式状态栏样式**能力的框架</span>

<span style="font-size: 15px">上榜理由：设计师MM总是抱怨系统状态栏不优雅？那就给她一个完美的沉浸式状态栏。StatusBarUtil可以随心所欲的设置状态栏样式，3.3K个star，足以说明它有多受设计MM的喜爱</span>

<span style="font-size: 15px">github [https://github.com/laobie/StatusBarUtil](https://github.com/laobie/StatusBarUtil)</span>

<span style="font-size: 15px">作者：Jaeger</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.jaeger.statusbarutil:library:1.4.0</span><span style="color: #800000">'</span></pre>

</div>

## 81.robolectric

<span style="font-size: 15px">一句话介绍：一款不依赖于Android设备的单元测试框架，</span>

<span style="font-size: 15px">上榜理由：sample中列举了如何对Android四大组件和常见功能测试的用例，3.2K个star，值得充满好奇心的人尝试</span>

<span style="font-size: 15px">官网地址：[http://robolectric.org/](http://robolectric.org/)</span>

<span style="font-size: 15px">github  [https://github.com/robolectric/robolectric](https://github.com/robolectric/robolectric)</span>

<span style="font-size: 15px">作者：robolectric</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>testCompile <span style="color: #800000">"</span><span style="color: #800000">org.robolectric:robolectric:3.3.2</span><span style="color: #800000">"</span></pre>

</div>

## 82.Fragmentation

<span style="font-size: 15px">一句话介绍:一款提供**管理Fragmen嵌套**t能力的框架</span>

<span style="font-size: 15px">上榜理由：对于Activity和Fragment使用，你一定得心应手，但如果要做一套通用的Activity&Fragment嵌套设计，想必你有点手足无措了，Fragmentation可以作为你设计Fragment管理上的第一步，3.2K个star，笔者认为有点名副其实了，项目介绍里说的是Fragment的管理能力，但并未提供Fragment&Activity生命周期、任务栈的管理能力，因此很难直接应用到企业项目当中，但源码当中的设计思路，值得笔者与诸位借鉴，拾人牙慧留有余香！</span>

<span style="font-size: 15px">github：[https://github.com/YoKeyword/Fragmentation](https://github.com/YoKeyword/Fragmentation)</span>

<span style="font-size: 15px">作者：YoKey</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #008000">//</span> <span style="color: #008000">appcompat v7包是必须的</span>
compile <span style="color: #800000">'</span><span style="color: #800000">me.yokeyword:fragmentation:0.10.7</span><span style="color: #800000">'</span>
<span style="color: #008000">//</span> <span style="color: #008000">如果想使用SwipeBack 滑动边缘退出Fragment/Activity功能，请再添加下面的库</span> <span style="color: #008000">//</span> <span style="color: #008000">compile 'me.yokeyword:fragmentation-swipeback:0.10.4'</span></pre>

</div>

## 83.Small

<span style="font-size: 15px">一句话介绍：轻巧的插件化框架</span>

<span style="font-size: 15px">上榜理由：作为插件框架榜单的新成员，Small的优点是轻巧，适合作为小团队的插件开发方案，3.1K个star，让它获得了**酷狗音乐**等著名开发团队的青睐，如果你们的团队想逐步实施插件化开发，Small是个不错的选择！</span>

<span style="font-size: 15px"> 官网地址：[http://code.wequick.net/Small/cn/cases](http://code.wequick.net/Small/cn/cases)</span>

<span style="font-size: 15px">github  [https://github.com/wequick/Small](https://github.com/wequick/Small)</span>

<span style="font-size: 15px">作者：wequick 团队</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">buildscript  {
    dependencies {
        classpath</span> <span style="color: #800000">'</span><span style="color: #800000">net.wequick.tools.build:gradle-small:1.2.0-alpha6</span><span style="color: #800000">'</span> <span style="color: #000000">}
}

apply plugin:</span> <span style="color: #800000">'</span><span style="color: #800000">net.wequick.small</span><span style="color: #800000">'</span> <span style="color: #000000">small {
    aarVersion</span> = <span style="color: #800000">'</span><span style="color: #800000">1.2.0-alpha6</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 84.JsBridge

<span style="font-size: 15px">一句话介绍：一款提供WebView和Javascript通信能力的框架</span>

<span style="font-size: 15px">上榜理由：该框架提供给了**允许H5页面调用通过JS调用App方法的能力；**3.1K个star，简洁的通讯方式，值得每一个Web\Hybrid App开发者尝试</span>

<span style="font-size: 15px">gtihub [https://github.com/lzyzsd/JsBridge](https://github.com/lzyzsd/JsBridge)</span>

<span style="font-size: 15px">作者：hi大头鬼hi</span>

<span style="font-size: 15px">使用</span>：

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {</span> <span style="color: #008000">//</span> <span style="color: #008000">...</span>
    maven { url <span style="color: #800000">"</span><span style="color: #800000">https://jitpack.io</span><span style="color: #800000">"</span> <span style="color: #000000">}
}

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.lzyzsd:jsbridge:1.0.4</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 85.richeditor-android

<span style="font-size: 15px">一句话介绍：一款强大的富文本编辑框架 </span>

<span style="font-size: 15px">上榜理由：2.8k个star，榜单里第一个为TextView提供扩展能力的框架，你暂时不需要它，但不能不知道它</span>

<span style="font-size: 15px">github  [https://github.com/wasabeef/richeditor-android](https://github.com/wasabeef/richeditor-android)</span>

<span style="font-size: 15px">作者：Daichi Furiya</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
    jcenter()
}

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">jp.wasabeef:richeditor-android:1.2.2</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 86.Transitions-Everywhere

<span style="font-size: 15px">一句话介绍：一款教你正确使用Transitions API（Android 转场动画API）的教学型项目</span>

<span style="font-size: 15px">上榜理由：你可能还未尝试过Android API的Transitions 框架，可能听过，但却无法做出优雅奇妙的动效——别担心，Transitions-Everywhere正如它的名字一样，它将带你全面体验Transitions 的强大之处</span>

<span style="font-size: 15px">github  [https://github.com/andkulikov/Transitions-Everywhere](https://github.com/andkulikov/Transitions-Everywhere)</span>

<span style="font-size: 15px">作者：Andrey Kulikov</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
    compile</span> <span style="color: #800000">"</span><span style="color: #800000">com.andkulikov:transitionseverywhere:1.7.4</span><span style="color: #800000">"</span> <span style="color: #000000">}</span></pre>

</div>

## 87.android-viewbadger

<span style="font-size: 15px">一句话介绍：能够快速的**为Android 视图加入“勋章**”能力的框架</span>

<span style="font-size: 15px">上榜理由：如果说勋章一词听起来陌生，那么显示已读未读个数、小红点标记信息这一类词语你一定不太陌生，笔者相信在诸位实际开发中经常遇到为某些item加入小红点标记的需求，聪明的各位一定有着各种实现方案，为什么不能快速优雅的完成呢？android-viewbadger可以帮你实现，当然，在某些情况下，你需要具备修改源码的能力，以符合设计MM的需求！值得注意的是，这宽项目已经五年没有更新了！</span>

<span style="font-size: 15px">github [https://github.com/jgilfelt/android-viewbadger](https://github.com/jgilfelt/android-viewbadger)</span>

<span style="font-size: 15px">作者：Jeff Gilfelt</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone源码到本地</span>

<div class="cnblogs_code">

<pre>View target = <span style="color: #000000">findViewById(R.id.target_view);
BadgeView badge</span> = <span style="color: #0000ff">new</span> BadgeView(<span style="color: #0000ff">this</span><span style="color: #000000">, target);
badge.setText(</span><span style="color: #800000">"</span><span style="color: #800000">1</span><span style="color: #800000">"</span><span style="color: #000000">);
badge.show();</span></pre>

</div>

## 88.AndroidWiFiADB

<span style="font-size: 15px">一句话介绍：一款不用数据线也可以让你调试手机设备APP的插件项目</span>

<span style="font-size: 15px">上榜理由：你是否还在担心测试过程中**高强度的拔插数据线**对手机电池和USB端口**造成**终生难以弥补**的损害**？别担心，有wifi有AndroidWiFiADB，无须数据线也可以调试应用了，更有趣的是，在测试工程师一边拿着手机一边找你聊bug的时候，你已经偷偷在它的手机上修复了bug，深藏功与名！</span>

<span style="font-size: 15px">github [https://github.com/pedrovgs/AndroidWiFiADB](https://github.com/pedrovgs/AndroidWiFiADB)</span>

<span style="font-size: 15px">作者：Pedro Vicente Gómez Sánchez</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>Preferences/Settings->Plugins->Browse Repositories->serch AndroidWiFiADB</pre>

</div>

## 89.emojicon

<span style="font-size: 15px">一句话介绍：一款提供在TextView、EdiText展示表情包能力的框架</span>

<span style="font-size: 15px">上榜理由：2.7k个star，,榜单第二款增强TextView显示能力的框架，这款专为表情包设计，如果你曾经好奇微信、QQ的表情显示是如何做到的？这款框架一定能满足你的求知欲。</span>

## 90.packer-ng-plugin

<span style="font-size: 15px">一句话介绍：一款打爆工具插件</span>

<span style="font-size: 15px">上榜利用：笔者尽力维护榜单涉及范围的全面性，因此引入此插件项目——项目号称完成100个渠道包只需要10秒钟，在市面上各种各样多渠道打包方案的今天，选择一款适合自己团队的，才是上上选择</span>

<span style="font-size: 15px">github [https://github.com/mcxiaoke/packer-ng-plugin](https://github.com/mcxiaoke/packer-ng-plugin)</span>

<span style="font-size: 15px">作者：Xiaoke Zhang</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">buildscript {
    ......
    dependencies{</span> <span style="color: #008000">//</span> <span style="color: #008000">add packer-ng</span>
        classpath <span style="color: #800000">'</span><span style="color: #800000">com.mcxiaoke.gradle:packer-ng:1.0.9</span><span style="color: #800000">'</span> <span style="color: #000000">}
}</span> </pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre>apply plugin: <span style="color: #800000">'</span><span style="color: #800000">packer</span><span style="color: #800000">'</span> <span style="color: #000000">dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.mcxiaoke.gradle:packer-helper:1.0.9</span><span style="color: #800000">'</span> <span style="color: #000000">}

 android {</span> <span style="color: #008000">//</span><span style="color: #008000">...</span>
 <span style="color: #000000">signingConfigs {
      release {</span> <span style="color: #008000">//</span> <span style="color: #008000">满足下面两个条件时需要此配置</span> <span style="color: #008000">//</span> <span style="color: #008000">1\. Gradle版本 >= 2.14.1</span> <span style="color: #008000">//</span> <span style="color: #008000">2\. Android Gradle Plugin 版本 >= 2.2.0</span> <span style="color: #008000">//</span> <span style="color: #008000">作用是只使用旧版签名，禁用V2版签名模式</span>
        v2SigningEnabled <span style="color: #0000ff">false</span> <span style="color: #000000">}
    }
  }</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 91.android-priority-jobqueue

<span style="font-size: 15px">一句话介绍：一款提供后台任务管理能力的框架</span>

<span style="font-size: 15px">上榜理由：如果你是个志在深入研究多线程操作的开发者，这个项目一定不要错过，不论是Activity重新加载、Service使用线程池时的任务优先级和并发问题，都不要担心，Job Manage会照顾优先级，持久性，负载平衡，延迟，网络控制，分组，2.4K个star，优秀的多线程管理能力，况且它依赖的第三方框架很少，值得你一试</span>

<span style="font-size: 15px">github  [https://github.com/yigit/android-priority-jobqueue](https://github.com/yigit/android-priority-jobqueue)</span>

<span style="font-size: 15px">作者：Yigit Boyar</span>

## 92.Android-Debug-Database

<span style="font-size: 15px">一句话介绍：一款提供测试App内部数据库能力的框架</span>

<span style="font-size: 15px">上榜理由：榜单里第二款针对**调试数据库**的框架，一行代码集成，直接在浏览器增删改查App的数据库，2.3k个star，心动不如行动！</span>

<span style="font-size: 15px">github  [https://github.com/amitshekhariitbhu/Android-Debug-Database](https://github.com/amitshekhariitbhu/Android-Debug-Database)</span>

<span style="font-size: 15px">作者：AMIT SHEKHAR</span>

<span style="font-size: 15px">使用</span>：

<div class="cnblogs_code">

<pre>debugCompile <span style="color: #800000">'</span><span style="color: #800000">com.amitshekhar.android:debug-db:1.0.0</span><span style="color: #800000">'</span></pre>

</div>

<span style="font-size: 15px">浏览器键入</span>

<div class="cnblogs_code">

<pre> http:<span style="color: #008000">//</span><span style="color: #008000">XXX.XXX.X.XXX:8080</span></pre>

</div>

## 93.conceal

<span style="font-size: 15px">一句话介绍：一款facebook提供的加密本地大文件的框架</span>

<span style="font-size: 15px">上榜理由：如果还在担心App内的图片的隐私问题，这款facebook提供的文件加密框架足以解决你的问题，facebook客户端的图片和数据都是使用conceal加密的</span>

<span style="font-size: 15px">官网地址：[http://facebook.github.io/conceal/](http://facebook.github.io/conceal/)</span>

<span style="font-size: 15px">github [https://github.com/facebook/conceal](https://github.com/facebook/conceal)</span>

<span style="font-size: 15px">作者;facebook</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone项目到本地/官网下载jar</span>

## 94.ARouter

<span style="font-size: 15px">一句话介绍：一款提供服务、页面跳转路由的框架</span>

<span style="font-size: 15px">上榜理由：正如作者宣称的那样，该框架提供：从外部URL映射到内部页面、跨模块的页面跳转（页面解耦）、拦截跳转过程等能力，还有更多功能等你去发掘，2.1K个star，值得为企业级的框架喝彩</span>

<span style="font-size: 15px">github  [https://github.com/alibaba/ARouter](https://github.com/alibaba/ARouter)</span>

<span style="font-size: 15px">作者：alibaba </span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">ndroid {
    defaultConfig {
    ...
    javaCompileOptions {
        annotationProcessorOptions {
        arguments</span> = <span style="color: #000000">[ moduleName : project.getName() ]
        }
    }
    }
}

dependencies {</span> <span style="color: #008000">//</span> <span style="color: #008000">替换成最新版本, 需要注意的是api</span> <span style="color: #008000">//</span> <span style="color: #008000">要与compiler匹配使用，均使用最新版可以保证兼容</span>
    compile <span style="color: #800000">'</span><span style="color: #800000">com.alibaba:arouter-api:x.x.x</span><span style="color: #800000">'</span> <span style="color: #000000">annotationProcessor</span> <span style="color: #800000">'</span><span style="color: #800000">com.alibaba:arouter-compiler:x.x.x</span><span style="color: #800000">'</span> <span style="color: #000000">...
}</span> <span style="color: #008000">//</span> <span style="color: #008000">旧版本gradle插件(< 2.2)，可以使用apt插件，配置方法见文末'其他#4'</span> <span style="color: #008000">//</span> <span style="color: #008000">Kotlin配置参考文末'其他#5'</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 95.MagicaSakura

<span style="font-size: 15px">一句话介绍：一款提供多主题切换能力的框架</span>

<span style="font-size: 15px">上榜理由：框架所提供的能力，一直是本榜单所看重的，这款由bilibili提供的多主题框架，作为榜单所涉及范围能补充，1.9个star，感谢bilibili团队所作出的贡献！</span>

<span style="font-size: 15px">github [https://github.com/Bilibili/MagicaSakura](https://github.com/Bilibili/MagicaSakura)</span>

<span style="font-size: 15px">作者:Bilibili</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">com.bilibili:magicasakura:0.1.6@aar</span><span style="color: #800000">'</span></pre>

</div>

## 96.CustomActivityOnCrash

<span style="font-size: 15px">一句话介绍：一款当APP crash的时候自动载入某个Activity的框架（而不是显示Unfortunately, X has stopped）</span>

<span style="font-size: 15px">上榜理由：新奇的创意是榜单所需要的，所以它赢得了1.8K个star；作为开发者应该拥有考虑到各种潜伏的bug的能力，但我们不能总是面面俱到，其他系统端的同事也可能造成程序的意外crash，因此，如何让程序优雅的crash->重启值得我们思考，这款框架就提供了这种能力</span>

<span style="font-size: 15px">github  [https://github.com/Ereza/CustomActivityOnCrash](https://github.com/Ereza/CustomActivityOnCrash)</span>

<span style="font-size: 15px">作者：Eduard Ereza Martínez</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre><span style="color: #000000">dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">cat.ereza:customactivityoncrash:2.1.0</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

</div>

```source-groovy-gradle
添加到 Application class:
```

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre> <span style="color: #000000">@Override</span> <span style="color: #0000ff">public</span> <span style="color: #0000ff">void</span> <span style="color: #000000">onCreate() {
    super.onCreate();

    CaocConfig.Builder.create()
        .backgroundMode(CaocConfig.BACKGROUND_MODE_SILENT)</span>
        .enabled(<span style="color: #0000ff">false</span>) <span style="color: #008000">//</span><span style="color: #008000">default: true</span>
        .showErrorDetails(<span style="color: #0000ff">false</span>) <span style="color: #008000">//</span><span style="color: #008000">default: true</span>
        .showRestartButton(<span style="color: #0000ff">false</span>) <span style="color: #008000">//</span><span style="color: #008000">default: true</span>
        .trackActivities(<span style="color: #0000ff">true</span>) <span style="color: #008000">//</span><span style="color: #008000">default: false</span>
        .minTimeBetweenCrashesMs(<span style="color: #800080">2000</span>) <span style="color: #008000">//</span><span style="color: #008000">default: 3000</span>
        .errorDrawable(R.drawable.ic_custom_drawable) <span style="color: #008000">//</span><span style="color: #008000">default: bug image</span>
        .restartActivity(YourCustomActivity.<span style="color: #0000ff">class</span>) <span style="color: #008000">//</span><span style="color: #008000">default: null (your app's launch activity)</span>
        .errorActivity(YourCustomErrorActivity.<span style="color: #0000ff">class</span>) <span style="color: #008000">//</span><span style="color: #008000">default: null (default error activity)</span>
        .eventListener(<span style="color: #0000ff">new</span> YourCustomEventListener()) <span style="color: #008000">//</span><span style="color: #008000">default: null</span>
 <span style="color: #000000">.apply();
}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 97.XhsEmoticonsKeyboard

<span style="font-size: 15px">一句话介绍：最开心的开源表情解决方案</span>

<span style="font-size: 15px">上榜理由：如果你还在发愁如何为你的APP自制键盘，那么此框架非常适合你，而且还提供表情包展示能力，1.7个star证明了它的独特。此外作者还附赠了高仿微信键盘，QQ键盘的demo，分享给诸位</span>

<span style="font-size: 15px">github [https://github.com/w446108264/XhsEmoticonsKeyboard](https://github.com/w446108264/XhsEmoticonsKeyboard)</span>

<span style="font-size: 15px">作者：zhongdaxia</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">allprojects {
    repositories {
        jcenter()
        maven { url</span> <span style="color: #800000">"</span><span style="color: #800000">https://jitpack.io</span><span style="color: #800000">"</span> <span style="color: #000000">}
    }
}

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.w446108264:XhsEmoticonsKeyboard:2.0.4</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

# 三.完整项目

## 1.iosche

<span style="font-size: 15px">一句话介绍：谷歌2016开发者大会的展示项目</span>

<span style="font-size: 15px">上榜理由：github上有13.4k个star，位居企业级项目排行榜第一位，牛逼的开发者，权威的设计模式，标准的项目写法，值得一试；笔者建议初学者down下源码，找到app入口，每个页面走一通，配合设计模式的概念加深理解。</span>

<span style="font-size: 15px">github [https://github.com/google/iosched](https://github.com/google/iosched)</span>

<span style="font-size: 15px">作者： Google</span>

<span style="font-size: 15px"> </span>

## 2.Plaid

<span style="font-size: 15px">一句话介绍：提供设计新闻和灵感的开源app</span>

<span style="font-size: 15px">上榜理由：标准的material design设计，新闻类app，github上9k的star量值得你摒弃市面上参差不齐的新闻app，快点下手研究它吧！</span>

<span style="font-size: 15px">github  [https://github.com/nickbutcher/plaid](https://github.com/nickbutcher/plaid)</span>

<span style="font-size: 15px"> 作者： Nick Butcher</span>

## 3.PocketHub

<span style="font-size: 15px">一句话介绍：Github的Android版</span>

<span style="font-size: 15px">上榜理由：8.7K的star数量，Github的亲生儿子，开放的源码值得各位一探究竟</span>

<span style="font-size: 15px">github [https://github.com/pockethub/PocketHub](https://github.com/pockethub/PocketHub)</span>

<span style="font-size: 15px">作者:Fadil Sutomo</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">down下所有源码</span>

## 4.Signal Android

<span style="font-size: 15px">一句话介绍：Signal是一款安全通讯的短信类app，</span>

<span style="font-size: 15px">上榜理由：7.9K的star数量，工具类app的标签属性，让它在排行榜中独一无二，如果你对短信app有兴趣，可以深入探究一番</span>

<span style="font-size: 15px">github [https://github.com/WhisperSystems/Signal-Android](https://github.com/WhisperSystems/Signal-Android)</span>

<span style="font-size: 15px">作者：WhisperSystems</span>

<span style="font-size: 15px">使用：github上down源码</span>

## 5.android-UniversalMusicPlayer

<span style="font-size: 15px">一句话介绍：一款跨设备运行的多媒体app</span>

<span style="font-size: 15px">上榜理由：googlesamples良心推荐，github拥有7.9k个star，可以在Android手机，汽车，平板，穿戴设备上使用，对于仅仅体验过Android手机开发的程序员，会不会很新奇呢？你值得一试！</span>

<span style="font-size: 15px">github [https://github.com/googlesamples/android-UniversalMusicPlayer](https://github.com/googlesamples/android-UniversalMusicPlayer)</span>

<span style="font-size: 15px">作者：Google</span>

<span style="font-size: 15px">使用：github上down源码</span>

## 6.HomeMirror

<span style="font-size: 15px"> 一句话介绍：如果你是个爱美的家伙那么你一定需要这面镜子！</span>

<span style="font-size: 15px">上榜理由：工具类App很难再github上有一席之地，除非它提供特别新奇的功能，比如HomeMirror，github上有用7599个star，仅仅因为它提供了镜子的功能。从现在起，Android 手机、pad，都将成为你旅游居家神器，值得拥有！</span>

<span style="font-size: 15px">github  [https://github.com/HannahMitt/HomeMirror](https://github.com/HannahMitt/HomeMirror)</span>

<span style="font-size: 15px">作者：Hannah Mittens </span>

<span style="font-size: 15px">HomeMirror初体验：</span>

![](http://images2015.cnblogs.com/blog/1149134/201706/1149134-20170616104729165-546624366.png)

## 7.ExoPlayer

<span style="font-size: 15px">一句话介绍：一款 替代Android原生MediaPlayer的媒体播放器</span>

<span style="font-size: 15px">上榜理由：也许是Google对自家MediaPlayer API不甚满意，所以诞生了ExoPlayer，ExoPlayer提供了强大的扩展API，使用它来制作多媒体播放器更快捷，更容易扩展，对多媒体播放器感兴趣的同仁们可以用它来大展身手了！6.9K个star，证明它有多受开发者们喜爱，更难能可贵的是，google还在更新维护着！</span>

<span style="font-size: 15px">官网地址：[https://google.github.io/ExoPlayer/](https://google.github.io/ExoPlayer/)</span>

<span style="font-size: 15px">github  [https://github.com/google/ExoPlayer](https://github.com/google/ExoPlayer)</span>

<span style="font-size: 15px">作者：google</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
    jcenter()
}
compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.android.exoplayer:exoplayer:r2.X.X</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.android.exoplayer:exoplayer-core:r2.X.X</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.android.exoplayer:exoplayer-dash:r2.X.X</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.google.android.exoplayer:exoplayer-ui:r2.X.X</span><span style="color: #800000">'</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 8.cheesesquare

<span style="font-size: 15px">一句话介绍：Android 材料设计的展示性项目</span>

<span style="font-size: 15px">上榜理由:作者被称为是Android Support Lib背后的男人，他写出的展示性项目，怎能不推荐上榜？材料设计已经炒了好几年了，但作为最权威的展示项目，你一定需要它，6.7个star证明了它是多么的受欢迎。</span>

<span style="font-size: 15px">github  [https://github.com/chrisbanes/cheesesquare](https://github.com/chrisbanes/cheesesquare)</span>

<span style="font-size: 15px">作者：Chris Banes</span>

## 9.DanmakuFlameMaster

<span style="font-size: 15px">一句话介绍：android端开源弹幕引擎</span>

<span style="font-size: 15px">上榜理由：bilibili出品，保证了它的纯种品质，并且ndk源码也一并开源，可谓业界良心，该弹幕引擎的开源节省了很多视频直播小伙伴的开发成本，笔者强力推荐！</span>

<span style="font-size: 15px">github [https://github.com/Bilibili/DanmakuFlameMaster](https://github.com/Bilibili/DanmakuFlameMaster)</span>

<span style="font-size: 15px">作者：bilibili</span>

<span style="font-size: 15px">使用</span>：

<div class="cnblogs_code">

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

<pre><span style="color: #000000">repositories {
    jcenter()
}

dependencies {
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.ctiao:DanmakuFlameMaster:0.8.3</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.ctiao:ndkbitmap-armv7a:0.8.3</span><span style="color: #800000">'</span> <span style="color: #000000"># Other ABIs: optional
    compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.ctiao:ndkbitmap-armv5:0.8.3</span><span style="color: #800000">'</span> <span style="color: #000000">compile</span> <span style="color: #800000">'</span><span style="color: #800000">com.github.ctiao:ndkbitmap-x86:0.8.3</span><span style="color: #800000">'</span> <span style="color: #000000">}</span></pre>

<div class="cnblogs_code_toolbar"><span class="cnblogs_code_copy">[![复制代码](//common.cnblogs.com/images/copycode.gif)](javascript:void(0); "复制代码")</span></div>

</div>

## 10.facebook-android-sdk

<span class="pl-en" style="font-size: 15px"> 一句话介绍：一款提供**接入facebook平台能力**的框架</span>

<span style="font-size: 15px">上榜理由：无论是你有接入facebook的需求，还是有学习自制sdk的需求，这都是很棒的途径；如何开发一套企业级sdk，是进阶优秀开发工程师的必须之路，4.1k个star，facebook持久更新质量保证，你值得拥有！</span>

<span style="font-size: 15px">github [https://github.com/facebook/facebook-android-sdk](https://github.com/facebook/facebook-android-sdk)</span>

<span style="font-size: 15px">作者：facebook</span>

<span style="font-size: 15px">使用</span>：

<div class="cnblogs_code">

<pre> https:<span style="color: #008000">//</span><span style="color: #008000">developers.facebook.com/docs/android</span></pre>

</div>

## 11.android-oss

<span style="font-size: 15px">一句话介绍：国外创意社区Kickstarter 开源的Android版客户端</span>

<span style="font-size: 15px">上榜理由：精致的企业级APP，每个页面处理得都很棒，如果你志在成为一个优雅工程师，这款开源项目一定适合你，3.8k个star证明了它不俗的生命力</span>

<span style="font-size: 15px">github：[https://github.com/kickstarter/android-oss](https://github.com/kickstarter/android-oss)</span>

<span style="font-size: 15px">作者：kickstarter</span>

<span style="font-size: 15px">使用;</span>

<span style="font-size: 15px">clone源码到本地</span>

## 12.k-9

<span style="font-size: 15px">一句话介绍：Android端客户端邮件App</span>

<span style="font-size: 15px">上榜理由：还记得张小龙的成名作——FoxMail吗？如果你想做一款移动端Email App，k-9具有很好的借鉴价值，此外对于应用层协议你也会有更深的认识</span>

<span style="font-size: 15px">官网地址： [https://k9mail.github.io/](https://k9mail.github.io/)</span>

<span style="font-size: 15px">github  [https://github.com/k9mail/k-9](https://github.com/k9mail/k-9)</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone项目到本地</span>

## 13.Timber

<span style="font-size: 15px">一句话介绍：一款音乐播放器类App</span>

<span style="font-size: 15px"> 上榜理由：3K个star，完全按照材料设计规范，提供十几种播放特性，而且还提供App的通用设置能力，这一点做的同样优秀，对于志在提升开发技术的同学值得一试</span>

<span style="font-size: 15px">github [https://github.com/naman14/Timber](https://github.com/naman14/Timber)</span>

<span style="font-size: 15px">作者：Naman Dwivedi</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone源码是一个好习惯</span>

## 14.remusic

<span style="font-size: 15px">一句话介绍：仿网易云音乐Android版App</span>

<span style="font-size: 15px">上榜理由：学习完Timer，是否还不太满足你的胃口？remusic可以满足你的胃口——它甚至可以拿去直接当上线项目了！2.9K个star，基于Timber的设计（入手的前提是先搞懂Timber）值得入手；有一个问题：如果由你重构，你会如何做呢？</span>

<span style="font-size: 15px">github [https://github.com/aa112901/remusic](https://github.com/aa112901/remusic)</span>

<span style="font-size: 15px">作者：MW</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone项目</span>

## 15.Douya

<span style="font-size: 15px">一句话介绍：开源豆瓣客户端</span>

<span style="font-size: 15px">上榜理由：一款功能全面、架构设计不俗的开源APP；仅仅是对豆瓣APP设计思路不满而进行的重构项目，可见作者对产品的痴迷和热爱，2.9K个star，证明该项目并不是头脑发热一时兴起的作品，如果每一个idea都能实现，那我们的世界将会多么美妙！</span>

<span style="font-size: 15px">github  [https://github.com/DreaminginCodeZH/Douya](https://github.com/DreaminginCodeZH/Douya)</span>

<span style="font-size: 15px">作者：Zhang Hai</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone项目到本地</span>

## 16.BookReader

<span style="font-size: 15px">一句话介绍：开源小说阅读器</span>

<span style="font-size: 15px">上榜理由：2.7K个star，榜单里第一款阅读器APP，具有很高的学习价值（针对有兴趣往阅读工具类方向发展的同学）</span>

<span style="font-size: 15px">github [https://github.com/JustWayward/BookReader](https://github.com/JustWayward/BookReader)</span>

<span style="font-size: 15px">作者：JustWayward 团队</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone到本地 </span>

## 17.bilibili-android-client

<span style="font-size: 15px">一句话介绍:高仿bilibili的Android客户端</span>

<span style="font-size: 15px">上榜理由：2.5K个star，榜单里第一款视频直播开源App；适合对视频直播、社区互动感兴趣的同学；bilibili-android-client里使用了很多大型框架，此项目并不适合基础薄弱的同学，不要灰心，学习页面的布局设计也是值得的！</span>

<span style="font-size: 15px">github  [https://github.com/HotBitmapGG/bilibili-android-client](https://github.com/HotBitmapGG/bilibili-android-client)</span>

<span style="font-size: 15px">作者：Hcc</span>

<span style="font-size: 15px">使用：clone到本地</span>

## 18.AndroidChromium

<span style="font-size: 15px">一句话介绍：Android版chrome浏览器</span>

<span style="font-size: 15px">上榜理由：正如作者宣称的那样:</span>

*   <span style="font-size: 15px">谷歌浏览器安卓版源码项目</span>
*   <span style="font-size: 15px">世界级的安卓架构</span>
*   <span style="font-size: 15px">理清本项目业务逻辑完全可以胜任国内一线公司工程师</span>

<span style="font-size: 15px">　　对于志在梳理浏览器框架的你，值得拥有</span>

<span style="font-size: 15px">github [https://github.com/JackyAndroid/AndroidChromium](https://github.com/JackyAndroid/AndroidChromium)</span>

<span style="font-size: 15px">作者：JackYAndroid</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone源码到本地</span>

# 四.开发框架：

# <span style="font-size: 16px">（排名无先后、只按类型划分）</span>

## 1.libgdx(https://github.com/libgdx/libgdx)
<span style="font-size: 15px">一句话介绍：一款跨平台的android端游戏开发框架</span>

<span style="font-size: 15px">上榜理由：android端开发框架类第一名，11.7K的star量，游戏框架是它的专属标签，更重要的是它是跨平台的</span>

<span style="font-size: 15px">官网地址  [http://libgdx.badlogicgames.com/](http://libgdx.badlogicgames.com/)</span>

<span style="font-size: 15px">github [https://github.com/libgdx/libgdx](https://github.com/libgdx/libgdx)</span>

## 2.xUtils

<span style="font-size: 15px">一句话介绍：老牌企业级开发框架</span>

<span style="font-size: 15px">上榜理由：4.9K个star，xUtils作为上古时期程序员备受推崇的开发框架，最大的原因——省事。xUtls包含四大模块，与之而来的是提供四大操作能力：数据操作、UI操作、Http协议操作、图片操作。xUtils作为笔者初学Android框架设计的导师型项目，在笔者多年经验中，看到xUtils作为众多中小银行Android端框架方案首选，足以证明它的受欢迎程度。该框架现在已经更新到了xUtils3，如果你对Android框架涉及有一定的想法，可以从xUtils入手，进阶为框架大师行列。虽然框架中很多引擎已经过时，各个模块的做法都可以用其他框架替代，但xUtils作为国内开发者的骄傲，上古时期的框架宠儿，值得你拥有！</span>

<span style="font-size: 15px">github  [https://github.com/wyouflf/xUtils](https://github.com/wyouflf/xUtils)</span>

<span style="font-size: 15px">作者：wyouflf</span>

<span style="font-size: 15px">使用：</span>

<div class="cnblogs_code">

<pre>compile <span style="color: #800000">'</span><span style="color: #800000">org.xutils:xutils:3.5.0</span><span style="color: #800000">'</span></pre>

</div>

## 3.android-common

<span style="font-size: 15px">一句话介绍： 一款android快速开发框架</span>

<span style="font-size: 15px">上榜理由：滴滴资深级Android工程师出品，历经多年开发者的检验，以4.3K屹立于快速开发框架榜第三名，该框架提供了图片缓存、Http缓存、DropDownListView、下载模块、开发常用工具类等，作为上古时期程序员最早的**总结性开发框架**，它是一代人智慧的结晶，值得我们为作者Trinea鼓掌喝彩</span>

<span style="font-size: 15px">github  https://github.com/Trinea/android-common</span>

<span style="font-size: 15px">作者：Trinea</span>

<span style="font-size: 15px">使用：</span>

clone代码到本地

## 4.Vitamio

<span style="font-size: 15px">一句话介绍：一款支持跨平台的Android多媒体开发框架</span>

<span style="font-size: 15px">上榜理由：如果之前提到的exoplayer不能满足你开发多媒体的需求，那我保证vitamio值得你一试</span>

<span style="font-size: 15px">官网地址：[https://www.vitamio.org/](https://www.vitamio.org/)</span>

<span style="font-size: 15px">github [https://github.com/yixia/VitamioBundle](https://github.com/yixia/VitamioBundle)</span>

<span style="font-size: 15px">作者：yixia团队</span>

<span style="font-size: 15px">使用：</span>

<span style="font-size: 15px">clone源码到本地</span>

<span style="font-size: 15px"> </span>

## 5.Weex

一句话介绍：移动端跨平台开发的解决方案

上榜理由：14.4K个star，有成熟应用案例的企业级混合开发框架，阿里巴巴出品，为什么不试试呢？

官网地址：[https://weex.apache.org/cn/](https://weex.apache.org/cn/)

github  [https://github.com/alibaba/weex](https://github.com/alibaba/weex)

作者：alibaba

## 6.cordova-android（Hybrid 开发框架、WebApp开发框架）

一句话介绍：跨平台的开发框架

上榜理由：cordova有足够的能力完成混合开发、WebApp开发的需求：不论你是Web开发者，或者是Native开发者，使用cordova都可以作出跨平台的App

官网地址：[http://cordova.axuer.com/docs/zh-cn/latest/guide/overview/index.html](http://cordova.axuer.com/docs/zh-cn/latest/guide/overview/index.html)

github [https://github.com/apache/cordova-android](https://github.com/apache/cordova-android)

## 7.react-native

一句话介绍：一款以Javascript的语言来操作多个系统语言（Ios、Android）的框架

上榜理由：很难讲react-native属于什么类别，它适合前端工程师开发移动端App，也适合Native开发者进行跨平台的开发，但对于Navitve开发者来说陡峭的学习曲线会吓走一大批“框架爱好者”；前端界有一句名言：Web代表着未来，Native代表着现在，而我们处在现在与未来的道路上；49K个star，似乎让我们离未来更进一步

官网地址： [http://facebook.github.io/react-native/docs/getting-started.html](http://facebook.github.io/react-native/docs/getting-started.html)

github  [https://github.com/facebook/react-native](https://github.com/facebook/react-native)

作者：facebook

# 五.其他：

## 1.AndroidUtilCode

<span style="font-size: 15px">一句话介绍：提供了数量庞大的工具类</span>

<span style="font-size: 15px">上榜理由：10.8K的star个数，足以证明它是多么受欢迎，欢迎你提供常用的工具类壮大它！</span>

<span style="font-size: 15px">github [https://github.com/Blankj/AndroidUtilCode/blob/master/README-CN.md](https://github.com/Blankj/AndroidUtilCode/blob/master/README-CN.md)</span>

> File → Settings... → Plugins → Browse repositories...

and search for `freeline`.

## <span>2.kotiln</span>

一句话介绍：Google推出的Android编程语言

上榜理由：就像AndroidStudio取代Eclipse那样，Google将kotiln作为Android的官方编程语言，也许此举是为了避免同Oracle的专利诉讼，但kotlin 100%兼容java，大幅精简java代码量，以及函数式编程的思想这些优异的特性同意值得我们注意，还记得在榜单之前说过的吗？未来是kotlin的，当下是java的，但我们处在当下通往未来的道路上——学习未来的编程语言，提升自己的工作效率，早点下班打豆豆，何乐而不为？

官网地址：[http://kotlinlang.org/](http://kotlinlang.org/)

github：[https://github.com/JetBrains/kotlin](https://github.com/JetBrains/kotlin)

 使用：

[http://kotlinlang.org/docs/reference/](http://kotlinlang.org/docs/reference/%20)   提供了 api-android用例-书籍等资源

# 六.书籍类项目

# <span style="font-size: 16px">（排序无先后）</span>

## 1.Android developer中国官网培训课程

<span style="font-size: 15px">一句话介绍：符合中国国情的Google开发者官网的子产品——Android开发者官网</span>

<span style="font-size: 15px">上榜理由：这里有培训课程、API用例课程、Sample用例、依赖库介绍、AndroidStudio官网...等等一系列公开免费的课程，尽管大部分内容还是英文讲解，可是你肯靠着英语词典一篇一篇啃完，相信我，你的Android知识水平将秒杀国内市面上大部分的Android书籍</span>

<span style="font-size: 15px">官网地址：[https://developer.android.google.cn/training/index.html](https://developer.android.google.cn/training/index.html)</span>

<span style="font-size: 15px">作者：google</span>

## 2.android-architecture

<span style="font-size: 15px">一句话介绍：google提供的Android当下各种基本框架</span>

<span style="font-size: 15px">上榜理由：看完它，mvp，mvvm都将入切瓜砍菜，秋风扫落叶一般...</span>

<span style="font-size: 15px">github [https://github.com/googlesamples/android-architecture](https://github.com/googlesamples/android-architecture)</span>

<span style="font-size: 15px">作者：google</span>

## 3.andorid-open-project

<span style="font-size: 15px">一句话介绍：囊括Android几乎所有的开源项目的导航类目录</span>

<span style="font-size: 15px">上榜理由：23k个star的导航类目录，与其盛名不符的是，该项目的导航、浏览阅读体验做的非常差，建议消遣之余阅读；推荐理由——中国人做的最全的Android 开源项目导航目录</span>

<span style="font-size: 15px">github [https://github.com/Trinea/android-open-project](https://github.com/Trinea/android-open-project)</span>

<span style="font-size: 15px">作者：Trinea</span>

## 4.awesome-android-ui

一句话介绍：Android的开源项目目录

上榜理由：国外的一款导航目录，23k个star

github  [https://github.com/wasabeef/awesome-android-ui](https://github.com/wasabeef/awesome-android-ui)

# 笔者寄语:

<span style="font-size: 15px">今年我们的权威框架之旅就结束了，是否感觉到意犹未尽？那太好了，欢迎各位读者加入《Android百大框架排行榜》的讨论之中，可以来[原文链接](http://www.cnblogs.com/jincheng-yangchaofan/articles/7018780.html "Permalink to 2017年Android百大框架排行榜 - 杨超凡_金诚先生 - 博客园")评论留言，也可以参与维护此项目：</span>

<span style="font-size: 15px">1.我认为XX框架应该上榜，理由XX</span>

<span style="font-size: 15px">2.我发现文章有几处错误，在XX部分</span>

<span style="font-size: 15px">3.对于笔者的某些观点我不能苟同，比如XX，我认为XX</span>

...

<span style="font-size: 15px">笔者希望收到**有理有据**的评论和未上榜的**框架推荐**，届时笔者会抽取一部分参与评论的小伙伴将，发放共计100RMB的物质奖励！</span>

　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　 　　　　　                                            2017-10-25   北京

</div>
