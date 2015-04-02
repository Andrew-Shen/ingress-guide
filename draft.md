## Ingress 新手入门


### 写在前面
这是一份进阶的新手入门指南. 如果您第一次进行游戏, 请先通过游戏内置的教程以及阅读 Google 官方的新手入门教程学习基本概念与基本操作: https://support.google.com/ingress/?hl=zh-Hans

### 社区准则
在进行游戏之前, 了解社区守则是极为重要的. Ingress 社区准则原文: https://support.google.com/ingress/answer/2808360 建议所有玩家在游戏前均仔细阅读此守则.

此处只强调两点:
- Cheating.
    > Methods of cheating, unfortunately, are limited only by cheaters' imaginations, but include at a minimum the following: using modified or unofficial software, playing with multiple accounts (one account per player, please); sharing accounts; win trading; using tools or techniques to alter or falsify your location; or selling or trading accounts.

    - 请务必从 Google Play (Android) 或者 App Store (iOS) 上获得游戏. 曾经有很多使用第三方市场上的 Ingress 从而被封号的案例.
    - 请务必保持一人一帐号. 任何小号, 包括仓库号, 都是被禁止的.
    - 原则上, 官方不限制一号多机. 但以一号多机的形式与其他玩家分享账号是被禁止的.
    - 请不要伪造地点(俗称"飞机").

- Contact with Users and Bystanders.
    >Unwanted physical contact with anyone while playing the game? Unwanted videotaping or photographing of other players or bystanders? Insults or obscenities directed toward other players or bystanders? Are you kidding? No - don't do it. If someone is being aggressive, trolling, offensive, overly protective of a specific Portal or just plain gets on your nerves; ignore them and don't engage. Temporarily remove yourself from the situation and/or block them in Comm.

    Google 充分保护 Ingress 玩家的隐私. 玩家没有任何义务响应其他玩家的要求: 比如要求在公频中回复信息以自证不是飞机, 或者露面以自证不是飞机. 当遇到此类无理请求, 可直接无视不必响应. 不必担心对方举报, 因为在没有确切的证据时, Google 不会封禁玩家账号.

    >If you suspect someone of cheating, don't call them out in Comm or demand they show their face, just report it via the Help Center and focus on your mission.

    类似地, 当怀疑对方有作弊行为时, 请直接举报(可以通过此页面举报作弊的玩家: https://support.google.com/ingress/#topic=3261401&contact=1&ts=3453649). **不要在公频中@对方或者要求对方露面.**

### 辅助工具
#### Intel Map
从官方的 Intel Map 上, 可以及时查看到世界上任何一处的游戏信息:
https://www.ingress.com/intel 善于使用 Intel Map 可以显著提高游戏效率.

访问 Intel Map 需要翻墙.

##### IITC 插件
IITC 脚本是配合 Intel Map 使用的强有力的工具. 其桌面版的下载和使用请参考: http://iitc.jonatkins.com/?page=desktop 为了保证脚本有效, IITC 必须及时更新.

IITC 由主脚本和其他大量的辅助插件脚本构成. 主脚本必须安装, 插件脚本可以选择性地安装. 下面列举一些常用的脚本:
- Player tracker: 根据 COMM 的信息在地图上推测玩家当前所在位置.
- draw tools: 实用画图工具, 方便规划 link 和 field 等.
- Portal Level Numbers: 显示 Portal 等级.
- Fix Google Map offsets in China: 修正中国地区的地图偏移问题.

需要注意, 上面推荐的均是 IITC 桌面版. 虽然 IITC 也有移动版, 但有传闻显示使用 IITC 移动版有封号风险.

##### COMM 解析
以下操作会被 COMM 记录 (进而显示在 IITC 的 Player tracker 插件中):
- 部署/摧毁 res
- 连接/摧毁 link

但下面这些操作不会被 COMM 记录 (因此不直接显示在 IITC 的 Player tracker 插件中):
- 升级 res
- 部署 mod

善于利用 COMM 的这一特点有时可以起到迷惑对手的作用.

#### App
Android 系统中有一些十分实用的 App 可以配合 Ingress 游戏使用:
- Integrated Timer for Ingress: 记录并自动提示 Hack 的冷却时间/剩余 Hack 次数/ Burnout 冷却时间等.
    https://play.google.com/store/apps/details?id=com.trigonesoft.iti
- Ingress Helper: 运行 Ingress 时保持屏幕常亮/ GPS 活动. 可辅助用于 Trekker 成就的取得.
    https://play.google.com/store/apps/details?id=de.nphardy.ingresshelper
- Ingress Portal Calc:  可以计算一系列与 Portal 有关的参数, 如最长 link 距离等.
    https://play.google.com/store/apps/details?id=com.gombosdev.ingressportalcalc
- Ingress Intel Helper: 适配手机屏幕的移动版 Intel 地图.
    https://play.google.com/store/apps/details?id=com.bb.ingressintel


### 等级解析
### Portal 解析
Mitigation: 盾/ link

Attack Power

Distance of Link Length

Number of Hacks before Burnout

Wait Time between Hacks (cool down time)

Number of Attacks

hack glyph

物品等级的获得 po 出物品等级+2-1
### 物品解析
回收一个 n 级的 Res, XMP, US 以及 Powercube 时, 将得到 (20n) XM.

回收一个 Common/Rare/Very Rare 的 Mod 以及病毒时, 将得到 40/80/100 XM.
#### Resonator
| 等级     |   能量|   部署者 XM 消耗  |
| :--------: | :--------:| :------: |
| L 1    |   1000 XM |50 XM  |
| L 2    |   1500 XM |100 XM  |
| L 3    |   2000 XM| 150 XM  |
| L 4    |   2500 XM | 200 XM  |
| L 5    |   3000 XM  | 250 XM  |
| L 6    |   4000 XM	 | 300 XM  |
| L 7    |   5000 XM	 |  350 XM  |
| L 8    |   6000 XM	 |  400 XM  |
#### 武器
##### XMP
| 等级     |   伤害范围 |   中心区平均伤害   |   释放者 XM 消耗  |
| :--------: | :--------:| :------: | :------: |
| L 1    |   42 m | 150 XM  | 50 XM  |
| L 2    |   48 m | 270 XM	  | 100 XM  |
| L 3    |   58 m | 470 XM	  | 150 XM  |
| L 4    |   72 m | 740 XM	  |200 XM  |
| L 5    |   90 m  | 990 XM  | 250 XM  |
| L 6    |   112 m	 |  1240 XM	 |300 XM  |
| L 7    |   138 m	 |  1580 XM	 |350 XM  |
| L 8    |   168 m	 |  2050 XM	 |400 XM  |

此外 XMP 造成伤害时有一定几率造成双倍于上表的伤害(critical hit). 造成双倍伤害时会数字旁会显示"!"号.

伤害随距离的衰减快于线性, 粗略看与平方衰减更为相似. 不过这一看法并不准确, 因为 XMP 造成的伤害随距离的变化不是连续的, 而是一个分段函数. (比如对于 L8 的 XMP, 距离每增加约 30m 伤害衰减一次. 详见: http://ipas.graphracer.com/analysis.html )

XMP 的伤害模拟, 可以参考网站: http://ipas.graphracer.com/

关于释放 XMP, 一个重要的技巧是长按 Fire 键可以最多提高20%的伤害, 这粗略相当于提升一个 XMP 伤害等级. **如无特殊情况, 尽量长按 Fire 键释放 XMP.**

Portal 实际受到的伤害的计算还要考虑 Portal 本身的防御. 请参考 Portal 解析一节.

附已有的数据:
- 未经官方确认的逆向工程结果:  https://groups.google.com/forum/#!topic/ingress-discuss/jEnHlKMyl5A

    XMP 伤害=(基础值+在此基础上的随机涨落)*0.5^((距离 Res 的距离 ÷ (XMP 最大伤害范围 ÷ 5))).

    | 等级     |    伤害基础值 |  随机涨落最大值   |
    | :--------: | :--------:| :------: |
    | L 1      |   136 |  180  |
    | L 2      |   226 |  300  |
    | L 3      |   406 |  540  |
    | L 4      |   630 |  840  |
    | L 5      |   900 |  1200  |
    | L 6      |   1260 |  1680  |
    | L 7      |   1800 |  2400  |
    | L 8      |   2700 |  3600  |

    XMP 最大伤害范围=40+2*(XMP 等级)^2

    双倍伤害的几率=(XMP 等级)*2%

- 玩家实际实验结果: http://ipas.graphracer.com/analysis.html 与逆向工程结果基本符合.



##### US
| 等级     |   伤害范围 |   最高伤害   |   释放者 XM 消耗  |
| :--------: | :--------:| :------: | :------: |
| L 1    |  10 m | 300 XM  | 50 XM  |
| L 2    |  13 m | 600 XM	  | 100 XM  |
| L 3    |   16 m | 1000 XM	  | 150 XM |
| L 4    |   18 m| 1800 XM	  | 200 XM  |
| L 5    |   21 m | 2400 XM  | 250 XM  |
| L 6    |   24 m	 |  3000 XM	 |300 XM  |
| L 7    |   27 m	 |  3600 XM	 |450 XM  |
| L 8    |   30 m	 |  5400 XM	 |400 XM  |

此外 US 造成伤害时有一定几率造成双倍于上表的伤害(critical hit). 造成双倍伤害时会数字旁会显示"!"号.

与释放 XMP 类似, 也可以通过长按 Fire 键提高最多20%的伤害.

US 的特点是基本伤害高于同等级 XMP, 双倍伤害的几率很高. 但其攻击范围小, 随距离衰减极快. US 最大的用处是在 Portal 中心释放, 可以高效地破除 Portal 上的 Mod. 当 Res 密集在 Portal 中心时, 也可以考虑使用 US.  (这也反向提示在部署 Res 时尽量分散, 不要集中在 Portal 中心. )

##### 病毒
蓝绿病毒可以强行改变 Portal 的所有者. 绿军使用蓝毒, Portal及其上的 Res 和 Mod 的拥有者是 ADA, 蓝军使用绿毒, Portal及其上的 Res 和 Mod 的拥有者是 Javis. 其他情况下拥有者为病毒使用者本人.

病毒本身没有等级, 对使用者也没有直接的等级限制. 但是在 n 级 Portal 上成功使用病毒, 需要 (1000n+1) 的 XM. 而 m 级 (m<=8) 的玩家的 XM 上限是 1000(m+2), 因此 m 级玩家最多可以在 (m+1) 级 Portal 上使用病毒. 比如: 毒掉一个8级 Portal 至少需要一个至少7级的玩家.

病毒虽然强力, 但也并非毫无弱点. 病毒的一个重要特性是被病毒改变阵营的 Portal, 一小时内对任何病毒免疫. 在这一小时的免疫时间内内再次对此 Portal 使用病毒, 无法改变 Portal 阵营且**使用的病毒会消失**. 可以利用此特性提前防御性地使用病毒, 防止对方使用病毒.

病毒在游戏中有广泛的战术应用, 仅受玩家的想象力所限. 下面列举一些常见的应用:
- 强行转变难以攻打的 Portal (大量盾/大量玩家充电/线下防守, 常见于大 Field 顶点等)的阵营. 但此方法可以利用一小时免疫的特性防御.
- 强行建立高级 Portal. 两个不同阵营的玩家配合, 消耗7个病毒就可以建立起8级 Portal; 两个相同阵营的玩家配合, 消耗14个病毒就可以建立起8级 Portal.
- 防守高级 Farm Portal. 对于偏远的高级床 Po/ 工 Po, 当招架不住对方攻势时, 可以使用病毒暂时转变其阵营.
- Anomaly 活动中获得先手优势. 在大陆目前的网络环境下, 防守方的优势大于进攻方. (具体参考对刷一节. ) 因此先手优势极为重要. 在最近的3月28日的广州 Shonin 活动中, 蓝军就采用了提前两小时使用一次病毒(蓝毒), 提前一小时使用一次病毒(绿毒), 活动开始时使用一次病毒(蓝毒)的方式获得先手优势.


#### Mod
每个 Portal 共有4个 Mod 插槽. 每位 Agent 只能在(i)己方 Portal (ii) 插槽有空位 (iii) XM 足够的情形下部署 Mod. 每位 Agent 在同一个Portal上最多部署两个 Mod. Mod 部署后无法直接去除, 因此部署之前应小心谨慎.

Mod 按照稀有程度分为大体分为三级: Common, Rare, Very Rare. 部署这三类 Mod, 分别需要消耗 400 XM, 800 XM, 1000 XM.

- Portal Shield

    | 等级      |    Mitigation |  Stickiness   |
    | :--------: | :--------:| :------: |
    | Common    |   30 | 0  |
    | Rare    |   40 | +15%  |
    | Very  Rare    |   60 | +45%  |
    | Very  Rare (AXA)    |  70 | +80%  |

    - Mitigation 即 Portal Shield 减少 Res 受到的伤害的百分比. 这一数据直接叠加, 比如有两个 C 盾的 Portal 只受到原有伤害的 100-30*2=40% 的伤害. 但起上限为 95. 比如有两个 VR 盾的 Portal 由于 60*2>95, 因此受到原有伤害的 5% 的伤害. 除了 Portal Shield 以外, link 的存在也可以增强 Portal 防御. 请参考 Portal 解析.
    - 尚不清楚 Stickiness 数据的作用. Stickiness 数据最早从 Intel Map 返回的数据中解析获得. 通常认为 Stickiness 代表盾不容易被破除的程度. 以及 Stickiness 越大越好.
    - AXA 盾出现在2014年12月15日,  是 AXA 保险赞助的结果. 它可以从任何 Portal 上通过 Hack 得到, 比 VR 盾更为稀有. 从 AXA 保险的 Portal 上 Hack 得到的几率更大. (大陆范围内暂时没有 AXA 保险 Po) https://plus.google.com/wm/1/+Ingress/posts/6E6wBwsNqC6

- Link Amp

    | 等级      |     Portal Range 增益 |
    | :--------: | :--------:|
    | Rare    |   *2|
    | Very Rare    |   *7 |

    - 与 Force Amp 和 Turret 类似, 当部署第二个 Link Amp 时,  效果减为 1/4. 部署第三和第四个 Link Amp 时, 效果减为 1/8. 与部署先后顺序无关, 以最大的算法为准. (总是认为 Very Rare 的 Link Amp 是先部署的. )
        比如一个8级 Portal, 插满 R 的 Link Amp, 其 Portal Range 为 655.36km*(2+0.5+0.25+0.25)=1966.08km. 插满 VR 的 Link Amp, 其 Portal Range 为 655.36km*(7+1.75+0.875+0.875)=6881.28km. 这也是目前游戏中能进行的最长的 Link.
    - Very Rare 的 Link Amp 无法通过 Hack 取得, 只能通过兑换代码等特殊途径获得.

    Link Amp 通常在大 Field 以及 Artifacts 活动中有用. 平时游戏中很少使用.


- Heat Sink

    | 等级      |   冷却时间减少  |
    | :--------: | :--------:|
    | Common    |   20% |
    | Rare    |   50% |
    | Very  Rare    |   70% |
    - 当部署第二, 第三或第四个 Heat Sink 时, 效果减半. (总是认为最稀有的 Heat Sink 是先部署的. )

        比如插了一个 VR 的 Heat Sink 的 Portal, 其冷却时间为 5min*(1-70%)=1.5min. 插了四个 VR 的 Heat Sink 的 Portal, 其冷却时间为 5min*(1-0.7)*(1-0.35)(1-0.35)(1-0.35)=24s.

    - 一个没有部署 Multi-hack 的 Portal, 玩家在其 Burnout 之前只能 Hack 四次.  Heat Sink 的一个重要作用是, 对于 Heat Sink 的部署者(无论其等级), 其 Hack 计数在部署后清零. 比如在做 Field 时恰好缺一个 key, 但目标 Portal 已经 Burnout. 这时可部署一个 C 的 Heat Sink, 便可以立刻 Hack.

- Mult-hack

    | 等级      |   增加额外的 Hack 次数  |
    | :--------: | :--------:|
    | Common    |   4 |
    | Rare    |   8 |
    | Very  Rare    |  12 |

    - 当部署第二, 第三或第四个 Mult-hack 时, 效果减半. (总是认为最稀有的 Mult-hack 是先部署的. )

        比如插了一个 VR 的 Mult-hack 的 Portal, 在其 Burnout 之前可以 Hack 的次数为 4+12=16次. 插了四个 VR 的 Mult-hack 的 Portal, 在其 Burnout 之前可以 Hack 的次数为 4+12+6+6+6=34次.

    - 配合好 Mult-hack 与 Heat Sink, 可以最大化 Hack 次数. 一种常见的场景是: 先 Hack 四次一个 Portal 至 Burnout, 部署 R 的 Multi-hack, 可再 Hack 八次至 Burnout. 再部署 Heat Sink, (对于部署者)可再 Hack 十二次至 Burnout. 总共 Hack 次数为4+8+12=24次.

- Force Amp
Force Amp 只有 Rare 一种, 可以使 Portal 攻击敌对阵营玩家时造成的伤害翻倍. 与 Link Amp 类似, 当部署第二个 Force Amp 时,  效果减为 1/4. 部署第三和第四个 Force Amp 时, 效果减为 1/8.

- Turret
Turret 只有 Rare 一种, 可以使 Portal 攻击敌对阵营玩家的频率翻倍, 并增加 30% 双倍攻击的概率. 与 Link Amp 和 Force Amp 类似, 当部署第二个 Force Amp 时,  效果减为 1/4. 部署第三和第四个 Force Amp 时, 效果减为 1/8.

    由于部署相同的 Mod 会造成效果的衰减, 为了最大化 Portal 对敌对阵营玩家的攻击效果, 通常一个 Force Amp 与一个 Turret 是比较经济的.

有关 Mod 的部署策略, 请参考 Mod 部署策略一节.

#### Power Cube
| 等级     |   补充能量|
| :--------: | :--------:| :
| L 1    |   1000 XM |
| L 2    |   2000 XM |
| L 3    |   3000 XM|
| L 4    |   4000 XM |
| L 5    |   5000 XM  |
| L 6    |   6000 XM	 |
| L 7    |   7000 XM	 |
| L 8    |   8000 XM	 |

#### Capsule
Capsule 可以用来储存物品.
- 在 Capsule 中的物品无法通过任何方式使用. 可以利用这一特性获得额外的 Portal Key, 参考 Portal Key 一节.
- Capsule 可以方便玩家交换道具. 需要注意 Capsule 本身也需要占用一个仓位. 因此为了接收一个装满道具的 Capsule, 玩家需要101个空仓位.
- Capsule 中不能储存 Capsule.
- 回收 Capsule 可以获得100XM. 同时 Capsule 中的物品也全部消失, 玩家也将一并获得其中物品的 XM.


#### Portal Key
Portal Key 有两个作用:
- 消耗 Portal Key 建立 Link.
- 保有 Portal Key 进行远程充电. 远程充电距离请参考等级解析一节.

如果你没有所 Hack 的 Portal 的 Portal Key, 那么有大约 75% 的概率 Hack 得到 Portal Key. 但如果你已经拥有所 Hack 的 Portal 的 Portal Key, 那么不会 Hack 得到 Portal Key. 因此为了得到更多 Portal Key, 可以:
- 将 Portal 暂时丢在地上, Hack 完成后再捡回来.
- 将 Portal 放进 Capsule 里.

由于 Capsule 糟糕的排序机制, 后者操作起来更为麻烦, 但对于大量 Portal Key 的情形, 两种方法需交替使用.

#### Media
Media 通常指向与游戏剧情或新闻有关的链接. 通常唯一的作用是回收以获得20XM. 但某种程度上说, Media 是不可再生的, 因此也具有一定的收藏价值.

### 升级指南
#### 多重
#### 9-16牌子

### 游戏技巧
- 长按 hack/ fire / recharge
- 多重
- 一些基本的进攻/防守技巧(床 po/对刷 装备配比)
- 插脚尽可能远
- mod 部署指南
    由于部署相同的 Mod 会造成效果的衰减, 为了最大化 Portal 对敌对阵营玩家的攻击效果, 一个 Force Amp 与一个 Turret 是比较经济的. 实际防御时
