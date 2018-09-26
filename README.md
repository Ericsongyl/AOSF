# Android常用优秀开源框架（一）
## 前言
AOSF：全称为Android Open Source Framework，即Android优秀开源框架汇总。包含：网络请求okhttp，图片下载glide，数据库greenDAO，链式框架RxJava，组件路由ARouter，消息传递通信EventBus，热更新Tinker，插件化框架Replugin，文件下载FileDownloaer，图片选择PhotoPicker，图片滤镜/毛玻璃等特效处理，GIF图片展示控件，图片九宫格控件NineGridView，对话框Dialog，导航指示器ViewpagerIndicator，进度条ProgressWheel，下拉刷新SmartRefreshLayout等，应有尽有。

<u>**说明：大家有好的开源框架，热烈欢迎大家提Issue或Pull requests进行补充和完善，我们一起把优秀的框架汇集起来，为自己和他人的开发提供便利，提高效率，避免重复造轮子或耗费查找时间，谢谢🙏**</u>

## 1.网络请求框架

[okhttp](https://github.com/square/okhttp)

[OkGo](https://github.com/jeasonlzy/okhttp-OkGo)

## 2.图片下载框架

[glide](https://github.com/bumptech/glide)

[picasso](https://github.com/square/picasso)

glide和picasso的对比：

|         | 加载一般图片 |    加载gif     | 图片质量细节 | 方法数 |                 缓存                  |
| :-----: | :----------: | :------------: | :----------: | :----: | :-----------------------------------: |
|  glide  |      OK      |  OK且显示动图  |    有锯齿    |  2678  | 根据ImageView尺寸，为不同尺寸缓存图片 |
| picasso |      OK      | OK，但显示静图 |    无锯齿    |  480   |    不管ImageView尺寸，缓存整张图片    |

## 3.轻量级数据库

[greenDAO](https://github.com/greenrobot/greenDAO)

[realm-java](https://github.com/realm/realm-java)

## 4.沉浸式状态栏

[StatusBarUtil](https://github.com/laobie/StatusBarUtil)

这是一个为Android App 设置状态栏的工具类， 可以在4.4及其以上系统中实现 沉浸式状态栏/状态栏变色，支持设置状态栏透明度。

## 5.异步链式框架

[RxJava](https://github.com/ReactiveX/RxJava)

[RxAndroid](https://github.com/ReactiveX/RxAndroid)

[agera](https://github.com/google/agera)

## 6.组件/模块路由，通信框架

[ARouter](https://github.com/alibaba/ARouter)

组件/模块路由框架，阿里巴巴出品。

[EventBus](https://github.com/greenrobot/EventBus)

基于发布-订阅模式的事件总线。

## 7.插件化框架

[RePlugin](https://github.com/Qihoo360/RePlugin)

[atlas](https://github.com/alibaba/atlas)

[dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk)

[Small](https://github.com/wequick/Small)

## 8.热修复框架

[tinker](https://github.com/Tencent/tinker)

## 9.注解

[dagger2](https://github.com/google/dagger)

[butterknife](https://github.com/JakeWharton/butterknife)

[androidannotations](https://github.com/androidannotations/androidannotations)

## 10.JSON解析

[gson](https://github.com/google/gson)

[fastjson](https://github.com/alibaba/fastjson)

## 11.工具类

[AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode)

[android-common](https://github.com/Trinea/android-common)

包含：缓存、公共view、常用工具等。

[android-common](https://github.com/litesuits/android-common)

包含：异步、log、辅助、数据处理、广播接收器、通用服务等工具。

[Lazy](https://github.com/l123456789jy/Lazy)

包含：常用工具类。

## 12.扫码库

[zxing](https://github.com/zxing/zxing)

## 13.适配器

[BaseRecyclerViewAdapterHelper](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)

## 14.检测内存泄露

[leakcanary](https://github.com/square/leakcanary)

## 15.具有头部的ViewPager

[HeaderViewPager](https://github.com/jeasonlzy/HeaderViewPager)

## 16.导航指示器

[ViewPagerIndicator](https://github.com/JakeWharton/ViewPagerIndicator)

[ViewPagerIndicator2](https://github.com/LuckyJayce/ViewPagerIndicator)

## 17.进度条

[ProgressWheel](https://github.com/Todd-Davies/ProgressWheel)

[MaterialProgressBar](https://github.com/DreaminginCodeZH/MaterialProgressBar)

Material Design风格的ProgressBar，支持多种效果。

[Android-ProgressBarWidthNumber](https://github.com/hongyangAndroid/Android-ProgressBarWidthNumber)

[Android-RoundCornerProgressBar](https://github.com/akexorcist/Android-RoundCornerProgressBar)

[LoadingDrawable](https://github.com/dinuscxj/LoadingDrawable)

各式各样创意、风格奇特的进度条。

[CircularProgressBar](https://github.com/lopspower/CircularProgressBar)

[NumberProgressBar](https://github.com/daimajia/NumberProgressBar)

## 18.下拉刷新、上拉加载更多

[XRecyclerView](https://github.com/XRecyclerView/XRecyclerView)

[PullRefreshAndLoadMore](https://github.com/Ericsongyl/PullRefreshAndLoadMore)

[SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)

下拉刷新、上拉加载、二级刷新、淘宝二楼、RefreshLayout、OverScroll，Android智能下拉刷新框架，支持越界回弹、越界拖动，具有极强的扩展性，集成了几十种炫酷的Header和 Footer。

## 19.图表

[Android-Charts](https://github.com/limccn/Android-Charts)

[MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)

[XCL-Charts](https://github.com/xcltapestry/XCL-Charts)

支持数十种图表，总有一个适合你。

[hellocharts-android](https://github.com/lecho/hellocharts-android)

功能强大、支持各式各样的图表控件。

## 20.文件下载引擎

[FileDownloader](https://github.com/lingochamp/FileDownloader)

## 21.文件选择器

[Android-FilePicker](https://github.com/DroidNinja/Android-FilePicker)

## 22.图片选择器

[Matisse](https://github.com/zhihu/Matisse)

[PhotoPicker](https://github.com/donglua/PhotoPicker)

仿微信的图片选择器。

[ImagePicker](https://github.com/jeasonlzy/ImagePicker)

## 23.图片九宫格控件

[NineGridView](https://github.com/jeasonlzy/NineGridView)

## 24.图片展示控件

[PhotoView](https://github.com/chrisbanes/PhotoView)

图片预览、缩放

[CircleImageView](https://github.com/hdodenhof/CircleImageView)

[RoundedImageView](https://github.com/vinc3m1/RoundedImageView)

[android-shape-imageview](https://github.com/siyamed/android-shape-imageview)

将图片按照自定义的形状显示。

[TextDrawable](https://github.com/amulyakhare/TextDrawable)

以Drawable的形式显示字符，类似平时见到的“字符”头像。

## 25图片裁剪

[uCrop](https://github.com/Yalantis/uCrop)

## 26.显示GIF图片的控件

[android-gif-drawable](https://github.com/koral--/android-gif-drawable)

## 27.图片压缩

[Luban](https://github.com/Curzibn/Luban)

## 28.图片滤镜库

[android-gpuimage](https://github.com/CyberAgent/android-gpuimage)

[glide-transformations](https://github.com/wasabeef/glide-transformations)

## 29.图片毛玻璃、模糊处理库

[android-stackblur](https://github.com/kikoso/android-stackblur)

[Blurry](https://github.com/wasabeef/Blurry)

[blurkit-android](https://github.com/wonderkiln/blurkit-android)

[ImageBlurring](https://github.com/qiujuer/ImageBlurring)

## 30.视频播放器

[JiaoZiVideoPlayer](https://github.com/lipangit/JiaoZiVideoPlayer)

[GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer)

[ijkplayer](https://github.com/Bilibili/ijkplayer)

[jjdxm_ijkplayer](https://github.com/jjdxmashl/jjdxm_ijkplayer)

## 31.下拉框

[nice-spinner](https://github.com/arcadefire/nice-spinner)

## 32.自定义Button控件

[android-flat-button](https://github.com/hoang8f/android-flat-button)

[Android-Bootstrap](https://github.com/Bearded-Hen/Android-Bootstrap)

[circular-progress-button](https://github.com/dmytrodanylyk/circular-progress-button)

[android-process-button](https://github.com/dmytrodanylyk/android-process-button)

## 33.自定义Switch（开关）控件

[SwitchButton](https://github.com/kyleduo/SwitchButton)

[JellyToggleButton](https://github.com/Nightonke/JellyToggleButton)

## 34.自定义编辑框（类EditText）控件

[MaterialEditText](https://github.com/rengwuxian/MaterialEditText)

[TagsEditText](https://github.com/mabbas007/TagsEditText)

[CloudEditText](https://github.com/g707175425/CloudEditText)

[AndroidEdit](https://github.com/qinci/AndroidEdit)

为EditText提供撤销、反撤销的功能。

[android-edittext-validator](https://github.com/vekexasia/android-edittext-validator)

带错误校验和提示的EditText。

## 35.自定义文本控件（类TextView）

[ExpandableTextView](https://github.com/Manabu-GT/ExpandableTextView)

可折叠的TextView，类似朋友圈查看全文。

[android-autofittextview](https://github.com/grantland/android-autofittextview)

自适应的TextView，在宽高固定的情况下，文字越多，字体越小。

[emojicon](https://github.com/rockerhieu/emojicon)

支持emoji表情的TextView。

[HTextView](https://github.com/hanks-zyh/HTextView)

支持很多文本特效的TextView。

## 36.动画

[AndroidViewAnimations](https://github.com/daimajia/AndroidViewAnimations)

各种动画

[recyclerview-animators](https://github.com/wasabeef/recyclerview-animators)

[lottie-android](https://github.com/airbnb/lottie-android)

展示 AE 工具所作动画的框架。

[ExplosionField](https://github.com/tyrantgit/ExplosionField)

爆炸动画效果。

[Grav](https://github.com/glomadrian/Grav)

粒子动画效果。

## 37.触摸滑动控件

[AndroidSwipeLayout](https://github.com/daimajia/AndroidSwipeLayout)

非常实用的触摸滑动控件

## 38.拖动条（类SeekBar）控件

[discreteSeekBar](https://github.com/AnderWeb/discreteSeekBar)

拖拽时可显示气泡提示的SeekBar。

[material-range-bar](https://github.com/oli107/material-range-bar)

Material Design风格的、支持区间选取的SeekBar。

## 39.RatingBar评分控件

[MaterialRatingBar](https://github.com/DreaminginCodeZH/MaterialRatingBar)

## 40.拖拽、排序控件

[ItemTouchHelperDemo](https://github.com/YoKeyword/ItemTouchHelperDemo)

## 41.对话框（Dialog、BottomSheet等）控件

[material-dialogs](https://github.com/afollestad/material-dialogs)

可定制化的 Dialog API。

[FlycoDialog_Master](https://github.com/H07000223/FlycoDialog_Master)

一套强大的Dialog集合，提供了类似BottomSheet的效果。

## 42.日历、时间选择控件

[BottomSheetPickers](https://github.com/philliphsu/BottomSheetPickers)

非常不错的日历、时间选择控件。

[SublimePicker](https://github.com/vikramkakkar/SublimePicker)

清爽、漂亮的日历。

[MaterialDateTimePicker](https://github.com/wdullaer/MaterialDateTimePicker)

Material Design风格的日历、时间选择器。

[CalendarListview](https://github.com/traex/CalendarListview)

基于ListView，效果类似原生Android的日历。

## 43.分类选择的控件

[DropDownMenu](https://github.com/dongjunkun/DropDownMenu)

实用的多条件筛选菜单。

## 44.角标、徽章

[SlantedTextView](https://github.com/HeZaiJin/SlantedTextView)

用TextView实现的标签效果。

[ShortcutBadger](https://github.com/leolin310148/ShortcutBadger)

用来生成带有角标的图标。

## 45.富文本编辑控件

[richeditor-android](https://github.com/wasabeef/richeditor-android)

功能强大的富文本编辑器。

[Knife](https://github.com/mthli/Knife)

轻量级的富文本编辑器。

## 46.标签组控件

[ChipsLayoutManager](https://github.com/BelooS/ChipsLayoutManager)

[FlowLayout](https://github.com/hongyangAndroid/FlowLayout)

支持单选、多选。

## 47.App新手引导、高亮

[Highlight](https://github.com/hongyangAndroid/Highlight)

一个引导高亮的库

[HighLightGuideView](https://github.com/jaydenxiao2016/HighLightGuideView)

## 48.固定header、索引的控件

[StickyListHeaders](https://github.com/emilsjolander/StickyListHeaders)

[pinned-section-listview](https://github.com/beworker/pinned-section-listview)

## 49.炫酷菜单控件

[android-floating-action-button](https://github.com/futuresimple/android-floating-action-button)

大名鼎鼎的fab。

[FilterMenu](https://github.com/linroid/FilterMenu)

一个转盘式菜单。

[FlyoutMenus](https://github.com/ShamylZakariya/FlyoutMenus)

一个很酷的弹出菜单。

[ArcLayout](https://github.com/ogaclejapan/ArcLayout)

弧形菜单，支持多种效果。

## 50.广告轮播、垂直公告的控件

[Android-ConvenientBanner](https://github.com/Bigkoo/Android-ConvenientBanner)

基于ViewPager的广告轮播控件，支持循环滚动。

[FlycoBanner_Master](https://github.com/H07000223/FlycoBanner_Master)

又一个广告轮播控件。

[MarqueeView](https://github.com/sunfusheng/MarqueeView)

基于ViewFlipper的垂直公告控件。俗名：可垂直跑、可水平跑的跑马灯；学名：可垂直翻、可水平翻的翻页公告。

## 51.滑动返回（类SwipeBack）控件

[SwipeBackLayout](https://github.com/ikew0ng/SwipeBackLayout)

[SwipeBackFragment](https://github.com/YoKeyword/SwipeBackFragment)

[and_swipeback](https://github.com/XBeats/and_swipeback)

## 52.水平滑动的RecyclerView控件

[RecyclerViewSnap](https://github.com/rubensousa/RecyclerViewSnap)

## 53.侧滑菜单控件

[MaterialDrawer](https://github.com/mikepenz/MaterialDrawer)

侧滑菜单。

[SwipeBackLayout](https://github.com/ikew0ng/SwipeBackLayout)

类似QQ侧滑菜单。

[DragLayout](https://github.com/BlueMor/DragLayout)

使用support.v4包下的ViewDragHelper实现QQ5.0侧滑。

## 54.水波纹效果

[RippleEffect](https://github.com/traex/RippleEffect)

## 55.自定义字体库

[Calligraphy](https://github.com/chrisjenx/Calligraphy)

## 56.KV数据存储框架

[MMKV](https://github.com/Tencent/MMKV)



<u>**这是整理的Android优秀开源框架的第一篇章，后续会继续整理，大家有其他好的框架推荐，请留言。如果你觉的这篇文章对你有帮助，欢迎收藏并转发给身边的朋友，谢谢。**</u>

