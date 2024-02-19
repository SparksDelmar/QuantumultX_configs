# QuantumultX 详细懒人教程｜新手入门教程｜圈X懒人规则｜iOS去广告


## 在使用本项目前，请您务必阅读使用规定，您使用本项目即代表您同意并遵守我们的规定。
> ***使用规定：***
  - 1.本项目仅支持中国大陆以外地区使用，您一旦使用本项目即代表您不在中国大陆地区；
  - 2.遵守您所在国家或地区的法律法规和相关不成文规定，为自己的行为负责；
  - 3.坚决拥护中国共产党的领导，坚持爱国爱党爱社会主义相统一；
  - 4.本项目仅供学习交流所用，禁止将本项目用于其他目的，请于下载后24小时内彻底删除；
  - 5.本项目所有内容仅供参考，不代表本项目对此内容的赞同、接受或反对；
  - 6.本项目的所有权归本项目以及被本项目收录的内容的所有者、开发者，您只有本项目的有限使用权；
  - 7.本项目的最终解释权归本项目。
> ***鸣谢：***
  - 本项目鸣谢所有被本项目收录的内容的所有者！如有侵权，请联系删除！


## 项目特色
### 圈X基础配置✅  
   > 1. 总体配置  
     - 圈X支持灵活的服务器配置，包括多种服务器检测URL，以确保连接的稳定性和速度。用户可以根据需要选择最佳的服务器。  
   > 2. 安全DNS  
     - 通过自定义DNS设置，圈X能够防止DNS劫持，提升浏览安全性。支持DoH (DNS-over-HTTPS) 服务，默认使用阿里DoH进行DNS加密处理，保护DNS查询不被篡改。本项目还配置了部分DNS分流功能，在使用某些常用服务时速度会更快。  
   > 3. 本地任务  
     - 圈X能够在本地执行任务，默认包含流媒体查询，此外您还可以导入各种签到脚本等等。  
   > 4. more...  
     -   

### 高效分流✅  
   > 1. 地区策略  
     - CN (中国)：直连中国大陆的服务，确保本地服务访问的速度和稳定性；您还可以自己配置国内的代理节点，进一步增强安全性，或是进行“免流”操作。  
     - Global (全球)：包括TW (台湾)、HK (香港)、JP (日本)、SG (新加坡)、US (美国)等地区的代理节点，用于国际流量的智能分流。  
     - Apple：为访问Apple服务优化的策略，结合US (美国)和CN (中国)节点，自主选择访问更安全还是更快速。由于美国节点无法访问由高德地图api提供的iOS地图，我们特别将这一策略设置为CN连接，但其他iOS服务仍然遵循您的选择。  
   > 2. 应用策略  
     - Discord、Emby、Github、Google、Microsoft（包含Copilot）、Paypal、Meta系列、Line、Telegram、Whatsapp、X、ChatGPT等：为这些常用国际服务提供专门的策略，通过JP、HK、TW、SG、US等地区的节点进行智能分流，保证服务的访问速度和稳定性。  
     - YouTube、Netflix、Disney、BiliBili、Spotify、NetEaseMusic等流媒体服务：专门为这些流媒体平台配置的策略，通过分流确保用户能够享受流畅的娱乐体验。注意TikTok地区解锁服务需要同时修改分流规则和重写规则，默认均为JP。  
   > 3. 特殊策略  
     - Google Voice：由于GV保号要求严格，特别默认设置为拒绝策略，避免垃圾节点经过导致GV账号风控；使用者可以自己添加固定节点，进行安全保号。  
     - Black and White：兜底分流、漏网之鱼，当所有CN规则和国外规则都不包含您访问的服务时，选择节点。  
     - Failover：故障转移策略，当主要策略无法连接时自动切换，保证服务的连续性。  
     - DataSaver-A、DataSaver-B：数据节省策略，用户可以自行添加大流量便宜的节点，进行某些流媒体观看或是下载超大文件，以节省专线机场的流量。  
   > 4. 广告屏蔽  
     - 尽可能多的屏蔽广告地址  
     - 尽可能多的屏蔽钓鱼网站、菠菜网站、诈骗网站、病毒网站，全力保障使用者的财产安全  
     - 尽可能多的屏蔽无良外媒、邪教以及某些伤害中华民族感情的网站  
     - 屏蔽iOS系统更新  
     - 不屏蔽正规色情网站 :)  
   > 6. 延迟基准测试  
     - url-latency-benchmark：通过特定地区的服务器标签正则表达式，周期性检测节点延迟，自动选择最佳节点。  
   > 7. 根据您的需要，可以自行增加额外的分流规则  
     -   

### 高效重写✅  
   > 1. Crack GitHub  
     - 解锁GitHub的高级功能，提升用户体验。  
   > 2. Modify NetEaseMusic  
     - 优化网易云音乐体验，解锁部分音乐播放限制。  
   > 3. Modify Fileball  
     - 改善Fileball网站的使用体验，提高访问速度和功能可用性。  
   > 4. Modify Baidu  
     - 优化百度搜索结果，提升搜索效率和结果的相关性。  
   > 5. Crack BaiduCloud  
     - 增强百度云服务的体验，可能包括提高下载速度或绕过某些限制。  
   > 6. Crack Spotify Premium  
     - 提供Spotify音乐服务的部分高级功能，改善音乐听歌体验。（音质不能设置为超高，否则会出现无限循环跳歌）  
   > 7. Crack YouTube Premium  
     - 为YouTube视频服务解锁高级功能，如无广告播放、后台播放等。（已在配置中写入drop 443端口 的udp，来保证规则生效）  
   > 8. Activate Tiktok  
     - 解除TikTok的地区限制，访问全球内容。（默认为JP）  
   > 9. Modify TestFlight RegionLimit  
     - 绕过TestFlight的区域限制，允许下载更多应用进行测试。  
   > 10. Modify Netflix  
     - 改进Netflix观看体验。  
   > 11. Ban HttpDNS  
     - 阻止HttpDNS服务，增强网络安全性和隐私保护。  
   > 12. Ban Ads by yfamily  
     - 屏蔽由yfamily指定的广告源，提供更清洁的浏览体验。  
   > 13. Modify 12306  
     - 优化中国铁路客户服务平台12306的使用体验。  
   > 14. Ban WechatAds  
     - 屏蔽微信内的广告，包括朋友圈和公众号文章中的广告。  
   > 15. Ban WeiboAds  
     - 屏蔽微博内的广告，包括信息流和侧边栏广告。  
   > 16. Modify ZhiHu  
     - 改进知乎的浏览体验，可能包括屏蔽广告或优化页面布局。  
   > 17. Ban Ads by DE  
     - 使用DivineEngine规则集屏蔽广告，提供广泛的广告屏蔽覆盖。  
   > 18. Ban Ads by lhie1  
     - 应用lhie1的规则集屏蔽广告，清理网络环境。  
   > 19. Redirect by DE  
     - 使用DivineEngine的规则进行特定请求的重定向，优化网络请求。  
   > 20. Ban Adsense  
     - 屏蔽广告联盟的广告。  
   > 21. Modify apps/lite-programs  
     - 优化应用和轻量级程序的性能，提升响应速度和用户体验。  
   > 22. Ban OnScreenAds by MoYu  
     - 屏蔽开屏广告。  
   > 23. Ban Ads by DE (AdvertisingPlus)  
     - 使用DivineEngine的扩展广告屏蔽规则，增强广告拦截能力。  
   > 24. Ban Ads by fmz200  
     - 应用fmz200的广告屏蔽规则，针对特定广告源进行屏蔽。  
   > 25. Ban Ads by yfamily (ultra plus)  
     - 使用yfamily的超级广告屏蔽规则，针对顽固广告进行拦截。  
   > 26. 其他高级功能不在这里过多介绍  
     -   




## 使用教程  
<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/1.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/2.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/3.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/4.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;

<p>链接地址为<a href="https://github.com/SparksDelmar/QuantumultX_configs/raw/main/MyConfig.conf">https://github.com/SparksDelmar/QuantumultX_configs/raw/main/MyConfig.conf</a></p>


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/5.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/6.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/7.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/8.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/9.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/10.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/11.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/12.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/13.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/14.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/15.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/16.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/17.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/18.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/19.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/20.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/21.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/22.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/23.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/24.jpg" width="48%"/>
</p>


&nbsp;
&nbsp;
&nbsp;


<p align="center">
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/25.jpg" width="48%"/>
  <img src="https://github.com/SparksDelmar/QuantumultX_configs/blob/main/res/26.jpg" width="48%"/>
</p>
