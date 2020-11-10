## Script脚本列表

1.  京东水果([jd_fruit.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_fruit.js))
2.  东东萌宠([jd_pet.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_pet.js))
4.  种豆得豆([jd_plantBean.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_plantBean.js))
5.  天天加速([jd_speed.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_speed.js))
6.  摇钱树([jd_moneyTree.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_moneyTree.js))
6.  宠汪汪([jd_joy.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_joy.js))
7.  宠汪汪偷好友狗粮与积分([jd_joy_steal.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_joy_steal.js))
8.  宠汪汪单独喂食([jd_joy_feedPets.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_joy_feedPets.js))
9.  宠汪汪兑换奖品([jd_joy_reward.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_joy_reward.js))
10.  宠汪汪强制为好友助力(刷好友)([jd_joy_help.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_joy_help.js))
11.  宠汪汪赛跑助力([jd_joy_run.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_joy_run.js))
12.  宠汪汪聚宝盆辅助脚本([jd_petTreasureBox.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_petTreasureBox.js))
13.  取关京东店铺和商品([jd_unsubscribe.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_unsubscribe.js))
14.  京小超([jd_superMarket.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_superMarket.js))
15.  京小超兑换奖品([jd_blueCoin.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_blueCoin.js))
16.  进店领豆([jd_shop.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_shop.js))
17.  摇京豆([jd_club_lottery.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_club_lottery.js))
18.  全名开红包([jd_redPacket.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_redPacket.js))
19.  京东多合一签到([jd_bean_sign.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_bean_sign.js)) 【可N个京东账号，Node.js专用，核心脚本是JD_DailyBonus.js， IOS软件用户请使用NobyDa的 [JD_DailyBonus.js](https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js) 】
20.  京豆变动通知([jd_bean_change.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_bean_change.js))
21.  以及其他一部分在特定时间可用的薅京豆脚本，如 [手机狂欢城](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_818.js) 、[星推官](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_xtg.js) 等。

**脚本兼容: [QuantumultX](https://apps.apple.com/us/app/quantumult-x/id1443988620), [Surge](https://apps.apple.com/us/app/surge-4/id1442620678), [Loon](https://apps.apple.com/us/app/loon/id1373567447), 小火箭, JSBox, Node.js**

**TODO**

- [x] 完善京小超脚本[jd_superMarket.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_superMarket.js)
- [x] 京小超商圈助力功能[jd_superMarket.js](https://raw.githubusercontent.com/yuanshaocheng/myJdScript/master/jd_superMarket.js)

## 食用方法

### 方法一：本地安装Node.js，下载本库脚本

  - 教程请见：[EvineDeng/jd-base](https://github.com/EvineDeng/jd-base)

### 方法二：云服务器、腾讯云函数等等

  - 需自行有云服务器，云函数等

  - 腾云云函数使用 [教程说明](iCloud.md)
        
### 方法三：GitHub Action（推荐）

 - 使用教程看 [GitHub Action教程](githubAction.md)
 - GitHub Action 定时运行会有延迟(大概15分钟左右),故一些需要抢购(对时间要求比较严格)脚本不适合使用(例如`jd_joy_reward.js`, `jd_blueCoin.js`, `jd_xtg.js`等脚本)
 - GitHub Action需要用到的[Secrets集合](https://github.com/yuanshaocheng/myJdScript/blob/master/githubAction.md#%E4%B8%8B%E6%96%B9%E6%8F%90%E4%BE%9B%E4%BD%BF%E7%94%A8%E5%88%B0%E7%9A%84-secrets%E5%85%A8%E9%9B%86%E5%90%88)
 
### 方法四：Docker（NAS或VPS用户）

 - 可以精确控制任务运行时间，有三种办法：[docker办法一](https://github.com/yuanshaocheng/myJdScript/tree/master/docker)、[docker办法二（和本地安装Node.js有点类似）](https://github.com/EvineDeng/jd-base)、[docker办法三](https://github.com/chinnkarahoi/jd-scripts-docker)
 - [环境变量](https://github.com/yuanshaocheng/myJdScript/blob/master/githubAction.md#%E4%B8%8B%E6%96%B9%E6%8F%90%E4%BE%9B%E4%BD%BF%E7%94%A8%E5%88%B0%E7%9A%84-secrets%E5%85%A8%E9%9B%86%E5%90%88)
 
#### 注：以上四种运行机制都是Node.js，故您需仔细阅读下面几点


  - 如果使用方法一与方法二，需自行提供京东cookie填写到 [jdCookie.js](https://github.com/yuanshaocheng/myJdScript/blob/master/jdCookie.js) 里面

  - 方法三京东cookie不要！不要！不要！填写到 [jdCookie.js](https://github.com/yuanshaocheng/myJdScript/blob/master/jdCookie.js) 里面
   
  - 获取京东cookie教程可参考 [浏览器获取京东cookie教程](https://github.com/yuanshaocheng/myJdScript/blob/master/backUp/GetJdCookie.md) , [插件获取京东cookie教程](https://github.com/yuanshaocheng/myJdScript/blob/master/backUp/GetJdCookie2.md)

  - 方法四Docker安装Cookie请见各自的说明。
