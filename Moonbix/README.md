# 简介
* [Moonbix](https://t.me/Binance_Moonbix_bot/start?startapp=ref_6579684395&startApp=ref_6579684395)是币安亲自下场做的TG零撸小游戏，且名牌空投，币安实力不用多说，属于必冲项目
# 准备
* **[AdsPower](https://share.adspower.net/lywjfE)**，其它指纹浏览器支不支持咱也不知道，可以参考逻辑自行修改，应该大差不差</br>
* **socks5代理**，[Moonbix](https://t.me/Binance_Moonbix_bot/start?startapp=ref_6579684395&startApp=ref_6579684395)屏蔽了很多国家，所以需要自备法国、台湾、印尼、东南亚等地区的IP
# 使用
* 使用前需要在指纹浏览器中打开一次[Moonbix](https://t.me/Binance_Moonbix_bot/start?startapp=ref_6579684395&startApp=ref_6579684395)小游戏地址，自己大拉小。配置代理新建环境啥的都是撸毛的不多说，应该都懂</br>
* 打开AdsPower>自动化>RPA>新建流程>导入，将[AdsPower.josn](https://github.com/web3xiaotiancai/web3script/blob/main/Moonbix/AdsPower.json)导入即可</br>
* 导入后点开调试，将浏览器调整到合适的窗口，我是把浏览器宽度拉到最窄，这样金币更集中，好抓一点</br>
# 定时执行
* 在AdsPowe计划管理里面，新建计划，选中要执行的指纹环境，设置每1个小时执行一轮</br>
* 流程管理右上角有个设置，可以设置线程，就是同时打开几个指纹
# 注意事项
* 计划最好用随机顺序执行，避免交互线路雷同被女巫</br>
* 默认使用的是电脑网页环境，如果想要模拟手机运行环境，可以新建内核为手机的指纹环境（特别注意，不要直接修改以前的指纹环境内核，会导致数据丢失）</br>
* 注意防女巫，除了屏蔽IP，看游戏接口，连钩子的速度每次都不一样，查女巫的力度可能比较大</br>
* 由于没被屏蔽国家的IP比较慢，所以脚本中设置的延迟比较大，可以根据你的代理速度自行调整</br>
* 钩子点击速度也可以自己设置，和开的窗口大小有关，如果你跑起来发现分数很低，请调整窗口或者调整点击速度，一般平均每把挖150分左右
