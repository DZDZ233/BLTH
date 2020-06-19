# Bilibili-SGTH
![MIT License](https://img.shields.io/badge/license-MIT-green) ![ECMAScript 6](https://img.shields.io/badge/ECMAScript_6-pass-green.svg) ![ECMAScript 5](https://img.shields.io/badge/ECMAScript_5-unsupport-red.svg) ![TamperMonkey 4.10](https://img.shields.io/badge/TamperMonkey_4.10-pass-green.svg) ![Chromium  83](https://img.shields.io/badge/Chromium_83-pass-green.svg) ![Firefox 77](https://img.shields.io/badge/Firefox_77-pass-green.svg)  
油猴脚本。自动参加抽奖，完成每日任务。  
另含BilibiliAPI_Mod及[OCRAD](https://github.com/antimatter15/ocrad.js)。  
### 点击[Bilibili-SGTH_1](https://raw.githubusercontent.com/andywang425/Bilibili-SGTH/master/B%E7%AB%99%E7%9B%B4%E6%92%AD%E8%87%AA%E5%8A%A8%E6%8A%A2%E8%BE%A3%E6%9D%A1.user.js)或[Bilibili-SGTH_2](https://github.com/andywang425/Bilibili-SGTH/raw/master/B%E7%AB%99%E7%9B%B4%E6%92%AD%E8%87%AA%E5%8A%A8%E6%8A%A2%E8%BE%A3%E6%9D%A1.user.js)安装脚本  

>感谢SeaLoong的BilibiliAPI v1.4.6。本脚本使用的BilibiliAPI_Mod为在此基础上的修改版。  
## 本脚本会自动抢辣条~和亲密度~
_2020.5.14起领取上船奖励不加亲密度改为辣条_  
登陆bilibili后打开任意b站直播间启用脚本。启用脚本后你可以使用win10的多桌面功能，在另一个桌面做其它事情。  
不建议24小时挂着脚本，容易进小黑屋。勾选低调设置可以降低进小黑屋概率。  
启用脚本后不要去抢小时榜房间和广播的礼物，重复抢次数多了会进小黑屋。  
如果开启抽奖附加延迟，可能出现领不到礼物的情况，请降低或取消延迟。  
这个脚本的部分代码来源于[十六夜](https://greasyfork.org/en/users/289469-%E5%8D%81%E5%85%AD%E5%A4%9C)的[B站直播自动抢辣条二代by十六夜](https://greasyfork.org/en/scripts/381907-b%E7%AB%99%E7%9B%B4%E6%92%AD%E8%87%AA%E5%8A%A8%E6%8A%A2%E8%BE%A3%E6%9D%A1%E4%BA%8C%E4%BB%A3by%E5%8D%81%E5%85%AD%E5%A4%9C)和[SeaLoong](https://github.com/SeaLoong)的[Bilibili-LRHH](https://github.com/SeaLoong/Bilibili-LRHH)。  
**部分设置更改后需要刷新才能生效。**  
**使用前建议先关闭广告拦截插件，否则脚本可能无法正常运行。**  
我的b站id:[Andy425](https://space.bilibili.com/358483030)  
辣条交流群:[1106094437](https://jq.qq.com/?_wv=1027&k=fCSfWf1O)，如果有问题可以进群寻求帮助。欢迎进来聊天~  
_如果有什么建议可以给我提Issues或在b站私信我，我会试着改进~_  
## 功能细节 

+ 抽奖前随机延迟  
+ 特定时段不参与抽奖  
+ 随机跳过抽奖  
+ 能设置当天最多抢辣条数量  
+ 抽奖前模拟进入目标房间  
+ 抽奖前概率发送活跃弹幕（防检测）  
+ 点击**直播画面上方**按钮隐藏/显示脚本口和抽奖信息  
+ 进入小黑屋时强制重复抽奖直到成功，最多尝试5次（**危**）  
+ 屏蔽不必要的页面元素防止遮挡界面或按钮（目前有2233模型，端午活动入口）  
+ 自动完成每日任务

   1.登陆主站

   2.观看视频

   3.自动投币
  
   4.分享视频
  
   5.银瓜子换硬币
  
   6.直播区签到
  
   7.应援团签到
  
   8.自动领银瓜子宝箱 

以上功能涉及参数可自定义  
## 更新日志
>### 2.6.1  
>修复检查小时榜的bug
>### 2.6  
>银瓜子宝箱验证码识别模块优化，提高验证码识别准确率；修复点击显示/隐藏按钮后聊天信息滚动问题；脚本内置检查更新源换为github;支持自定义检查小时榜间隔
>### 2.5.7  
>移除不必要的页面元素，防止遮挡按钮;细节调整
>### 2.5.6  
>日常修bug，解决了动态中无视频时分享视频引起的错误；界面微调。
>### 2.5.5  
>修复一些bug；运行日志更加详细；优化了重复运行检测，减少性能消耗。  
>### 2.5.4  
>考虑到有时候油猴检查更新功能会失效，增加检查脚本更新的按钮  
>### 2.5.3  
>解决了禁止重复运行方面的bug；转移脚本到GitHub  
>### 2.5.2  
>界面调整：保存按钮变为全局，重新加入重置统计按钮  
>### 2.5.1  
>增加银瓜子换硬币功能;界面细节优化。  
_中间一段日志丢失_  
>### 2.2  
>加入选项：进黑屋后强制重复抽奖直到成功，最多重试5次(危险)；CACHE优化  
>### 2.1.3  
>重复运行检测，在一个直播间启用脚本后打开其它直播间不会运行此脚本。  
>### 2.1.2  
>播放器为flash时不自动切换为html播放器  
>### 2.1.1  
>应援团签到细节优化  
>### 2.1  
>增加自动应援团签到功能;修复了SC会遮挡弹幕区上方按钮的bug;活跃弹幕池修改,去除无意义的句号和空格改为表情;限制活跃弹幕发送概率必须小于5%  
>### 2.0.2  
>API源调整,为之后更新做准备  
>### 2.0  
>新功能:抽奖前有概率在目标房间发送一条活跃弹幕(概率别调太高，b站限制每秒只能发一条弹幕);jQuery换源，用BilibiliAPI_Mod(自制API，已压缩)代替原SeaLoogn大佬的BilibiliAPI,包含更多B站API及函数(已压缩，加载更快);本脚本也已压缩，提高载入速度;修复部分时段不抽奖输入框写入非常规时间段时脚本无法正确执行的bug，并增加分钟选项，更加精确(3分钟一检测，所以实际会有一点误差);细节上的改进;  
>### 1.8  
>每次抽奖前抽奖模拟一次进入直播间的动作，防检测(所以会产生很多观看历史记录);重新加入亲密度统计(暂时没用);加入银瓜子统计;优化辣条上限检测方法。  
>### 1.7.2  
>现在上船奖励变为辣条，不再统计亲密度;再次优化了抽奖信息滚动。  
>### 1.7.1  
>解决了弹幕聊天记录和抽奖信息滚动异常的问题;修复了一个按钮的css样式;添加一个脚本图标(辣条)。  
>### 1.7  
>礼物信息保存到浏览器缓存，出现重复领取的现象大大降低。修复了开启延时会无法抽奖的bug。  
>### 1.6  
>更新css样式,窗口更好看了。  
>### 1.5.3  
>随机延迟算法优化：随机延时包括最大和最小值;最大最小值相同时延时固定。  
>### 1.5.2  
>增加选项:不抽奖时不重载直播间；左下角显示版本号。  
_更早的日志就不显示了~_
