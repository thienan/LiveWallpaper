# Video LiveWallpaper
使用视频作为壁纸。使用leancloud作为后端云存储视频. 
可以添加一个文件选择器来选择视频文件来作为壁纸
<a href='https://play.google.com/store/apps/details?id=com.i7play.videopapger&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' width="170px"/></a>
 ## 特性
 * 使用kotlin开发, 多语言
 * 可以预览视频,下载视频,设置壁纸
 * 打开本地视频
 * 现拍视频,现用
 
## 使用
 直接下载源码，导入android studio。 添加IAP里面的leancloud的key
 ```
 AVOSCloud.initialize(this, "appkey", "clientkey")
 ```
 新建类class:
 VideoItem, 新增列 img type video name enname like tag即可
 <img src="docs/5.png"/>
### 展示
<img src="docs/4.gif" width="250px"/>
<img src="docs/1.png" width="250px"/>
<img src="docs/2.png" width="250px"/>
<img src="docs/3.png" width="250px"/>


