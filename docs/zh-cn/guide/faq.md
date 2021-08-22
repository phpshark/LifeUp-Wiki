# 常见问题

目前我们整理了各种比较常见的问题在本文中，**因《人升》属于个人开发应用，两位开发者业余时间很有限**，麻烦先在这里查阅常见问题和应用内的「已知问题（bug）」后再进行反馈和问题咨询（文末或应用内有QQ讨论群）。

由于两位开发者时间精力有限，为了快速实现整个激励体系，应用内还有诸多功能/细节/交互UI不完善的地方，这些都只能通过时间来弥补。

协助我们宣传应用的话（无论是宣传给朋友还是应用市场评价，或者是文章、视频），或许我们能够获取到更多的开发/设计资源，让`人升`更完美。如果你编写了人升的相关文章、视频，请务必告知开发者~！

> 点击右上角可以查看目录并且切换，使用平板、电脑等设备阅览效果更佳。

## 事项

- **如何撤销完成事项？**

1. 在完成时，点击底部提示框的“撤销”按钮。

2. 于`侧边栏`的`历史`页面，点击撤销按钮。

3. 于`日历`页面的`已结束`模块，点击撤销按钮。

   > - 可以撤销任意时刻的无重复待办事项，以及**今天完成的重复事项**。
   > - 因【团队事项】涉及到服务器时间运算和动态发表等功能，不支持撤销。
   
   
- **如何查看历史逾期事项？如何补打卡？**

  当事项逾期时，会自动弹出逾期提示框，在提示框内可直接将逾期事项设置为完成状态。

  关闭提示框后，也随时可以在`侧边栏`-`历史`，或者`日历`-`已结束`页面查看或者更改事项状态（补打卡）。
  
  
  
- **如何创建XX类型的事项？习惯、每周几、艾宾浩斯。**

  习惯就是带有重复功能的待办事项，其他详情可查阅[事项详情相关文档](guide/tasks.md)。
  
   

- **可以设置经验值或者金币惩罚吗？**

  可以的，默认也启用了经验值惩罚（系数0.2）。金币惩罚默认没启用（系数0）。

  可以在`侧边栏`-`设置`-`进阶设置`里自由设定。
  
- **如何理解重复机制？**

  简言之，只需要你手动设置好事项的**首次的**【开始-期限】时间，以及重复频次后，后续的时间都会由应用自动计算得出。



- **如何隐藏掉已经完成的事项（其实是未开始的事项）？**

  有两种情况：
  
  1. 如果事项显示的是`xx日期期限`，那就代表该事项已经开始了。可以按需编辑事项，设置正确的`开始时间`。
  2. 如果事项显示的是`xx日期开始`，并且日期不是当天的话。可以检查下，最底部的折叠按钮是否是折叠状态（▾形状）；再检查首页右上角的菜单栏（三个点），点击`筛选`，检查是否选中`折叠非今日事项`

> 注意：
> 
> （1）智能清单（周、月）清单不支持折叠功能
> 
> （2）默认重复事项的可完成周期是整个周期，比如每21天重复的任务，是21天中的每一天都能完成。如果想要只在最后几天显示的话，可以调整开始时间。（只需要调整一次，应用会自动推算后续的日期）


- **期限日期允许指定具体时间到分钟吗？**

  设置好日期后，点击`时间`按钮即可设置具体时间。




- **如何设置多提醒？**
  
  可以通过创建子任务的形式创建多提醒，并且利用这一点可以为每个提醒设置不同的文案。

  

- **如何建立指定周几的待办事项？如每周一、三。**

  设置`重复频次`时，选择`每周几`。

  

- **【小米】设备在桌面小部件点击计数事项无反应，点击事项空白处无法进入详情？**

  MIUI有个特殊权限“后台应用显示界面”，需要用户手动授权。
  
  
  
- **什么是目标重复次数和计数事项次数？**

  [点击这里查看](guide/tasks.md)




- **子任务能否在首页列表显示？**

  暂时不支持，**后续可能会安排配置项**。

  同类产品其实两种方案（首页显示/仅编辑、详情页显示）都有，前者有Google Tasks，后者有滴答清单、微软todo等应用。两种方案各有优劣，与对子任务的定义相关：

  1. 前者的定义是子任务也是个重要的任务，需要提醒关注，好处是操作子任务时比较方便。后者对子任务的定义是个步骤定义、备注，只需要执行任务时进行关注，所以不必在列表中展示。
  2. 当在列表中不折叠展示，如果子任务一多，势必会影响整个列表的展示。
  3. 当在列表中如果折叠显示，那么操作成本与进入详情页面是一致的。




- **艾宾浩斯记忆法的规律：**

  此重复频次基于遗忘曲线，因《人升》的最小频次限制为一天，做了相应的调整，时间表如下：
  当天→1天后→1天后→2天后→4天后→7天后→15天后，总共7次
  
  

---

## 奖励（经验值、商品）

- **如何下架商品？**

  在`商店`页面，长按商品，然后选择顶部的垃圾桶按钮。
  
- **如何清空经验值、金币？**

  在`侧边栏`-`设置`-`数据备份、恢复、清除`界面可以清空对应的数值。

  注意：清空数值后，服务器数据不一定会及时同步。请不要立即重新登录、卸载应用，否则可能会恢复之前的数据。

- **属性的等级上限和经验值梯度是什么样的？**

  可以当作等级无上限（目前是2000+，正常手段几乎达不到）。

  每级所需的经验值会有梯度调整，但目前梯度其实不合理。（因此只看等级上限也是无法评估奖励的，经验值上限约是2^63）。

  很多用户其实都会长期处于2500经验值一级的梯度中，后续会调整整个等级体系（经验值总数不受影响）。

- **如何设置贷款？**
  
  在`商店`页面右上角菜单（三个点），选择`设置`，即可设置贷款金额。

  > 注意：目前的贷款实现只是允许负值，并没有对应的兑款利息的设定（待后续开发）。

- **如何自定义属性？**
  
  在`侧边栏`-`设置`-`进阶`中可自定义属性的名称、描述和图标。

  > 增删暂不支持，后续会上线技能系统来实现该部分扩展。
  
  

---

## 提醒/番茄钟/倒计时


- **指定时间没收到提醒【大部分设备】？或番茄钟不会响铃【华为、VIVO设备】？或者桌面小部件数据加载异常【华为设备】？OPPO设备（ColorOS）插入日历账号被移除？**

  应用内其实也有说明，由于独立应用权限有限，默认的提醒方式会受系统限制，可能关了后台就失效了。

  可以尝试**更换为系统日历提醒方式（`设置`-`事项设置`）**，更换后，可以查看系统日历app有没有成功插入提醒时间。 

  如果是番茄钟息屏后不能响铃，那么有可能是应用后台被系统杀掉了。可以设置系统的后台管理，将《人升》设置为不管理，并且设置后台权限。（各个系统操作步骤不一，可参考[后台运行](guide/background_running.md)）。

  【如果是华为】，可以查看[官方的操作步骤](https://consumer.huawei.com/cn/support/content/zh-cn00426500/)

  【如果是ColorOS设备】，有用户反馈应用创建的日历账号会被移除。目前暂不清楚解决方案，可以尝试向系统工程师反馈或者捣鼓权限和日历APP设置。有解决方案欢迎向我们反馈。

- **商品倒计时如何使用？**

  商品倒计时会以应用通知的形式进行。可以先确认应用通知权限正常。
  
- **番茄钟是否有正计时/自动下一个功能？**

  目前一个工作计时结束后，**会在页面中继续进行正计时**，你可以抉择是否要将这段时间加入到专注时长内。

  专门的正计时模式也会在后续规划开发。
  
- **番茄钟是否有类似专业的番茄钟APP的汇总统计功能？**

  **目前《人升》的番茄钟功能属于次要功能且在前期开发阶段（还在实验内，只是默认开启），暂不支持复杂的汇总统计，后续会安排开发。**

  暂仅支持：每次专注的详细记录和「状态」页面内有今日的简单汇总统计。

  > 且由于番茄钟模块相对比较独立，如果你有意协助开发可联系开发者。可以接口对接的形式接受协助开发。

---

## 备份与恢复

- **如何进行备份？**
  
  请查阅[备份介绍文档](guide/backup.md)。


- **为什么不能进行服务器云同步？**
  
  > 摘自《纯纯写作》的手册：
  > 云同步必然要伴随着同步冲突、同步失败、覆盖丢失等问题，这基本上是无解的，特别是要在手机上处理冲突......想想最经得起考验的git，都需要程序员参手和繁琐解决各种冲突，因此完全自动化的云同步可以说几乎不可能，除非各个端能够保持高速实时连接，瞬间同步...

  增量同步涉及到复杂的差异计算问题，目前的服务器难以支撑这些计算量，并且云同步涉及到隐私安全等问题。
  
  就算抛开这一点来讲，，我们除了待办事项外，还涉及了感想、附件等图片资源消耗，全部使用对象存储服务的话，这将是一笔不菲的开支。
  
  **对于我们一款买断制付费、0资本介入的应用而言，更是需要节省服务器资源，否则直接原地破产。**

  目前完善的增量同步功能基本都是大公司提供，或者干脆就是Web产品（所有数据都直接存在服务器，不支持离线使用）。

  亦或者只是免费提供一小部分功能，其他消耗服务器资源的功能都通通需要订阅制（每月、每年付费）。

- **为什么没有百度云备份？**
  
  因为百度云是私有协议，封闭且不允许第三方接入。

---

## 杂项

- **为什么不能自定义所有设置项？**

  > 摘自《纯纯写作》的手册：
  > 如果什么都开放给用户自定义，只会使得软件设置页面变得密密麻麻，像飞机仪表盘一样，令人无所适从，心生恐惧，同时也会使得更关键的设置项可达性下降。好用的用户体验应该帮用户考虑好、设计好，开箱即用。

  以上描述也很符合绝大多数应用，做加法容易，做减法难。因为0.1%的需求增加的设置项，会影响到100%所有的用户。因此我们只会综合考虑，只做普遍适用的设置项，尽量提高设置的覆盖面。

  **当然，你随时可以表达，你想要什么样的设置项。**我们会进行综合评估，但无法保证一定会加上。

  更何况，我们并不是**定制开发**，如果你有特殊需求，其实更应该去请求定制开发或者自行开发属于自己的应用（其实，这并没有你想象中的那么难）。
  
  人升的初衷其实就是想开源，允许社区贡献共通的需求提升应用，也允许个人拿去修改满足个人需求。但很可惜，由于环境恶劣，我们不得不取消了开源。

- **为什么xx功能要这么设计？**
  
  其实并没有这么多为什么。

  因为定下来的需求、技术实现方案和最终实现的成果并不可能保持完全一致，也更不可能永远与你的期望一致。

  即便是一些我们定下来的完善需求，也会因为技术不成熟，无法实现出期望的效果，这是不可避免的，只能一步步优化。

- **我不想用世界模块，可以隐藏吗？**

  可以前往`侧边栏`-`设置`-`显示设置`-`模块配置`内隐藏世界模块或者切换至其他模块~

- **如何初始化“我的”页面中的逾期、放弃数**

  这里的数字统计是基于历史记录的，可以前往`侧边栏`-`历史`页面，删除相应的错误记录。

  后续也会重构这个页面，也可以选择忽略该数值。

- **步数统计不精准？**
  
  **如应用新手指引所述，目前安卓系统没有提供统一的获取步数的方式，只能获取总步数。若接入各家厂商的运动SDK，会对应用的体积和权限获取有所影响，目前看来得不偿失，暂不会接入。**

  目前是通过计算差值统计的数据，因此数据的准确性与启动应用的时机、手机重启时机有关系（最佳的场景是每一天晚上23:59分打开一次应用，并且尽量不重启设备）。如果有手环等设备，可能需要特定的软件将步数同步到传感器，应用才能获取到。

  若不精准，可以尝试手动输入步数，或者直接在`设置`-`显示`中隐藏计步模块。

- **为什么没有番茄钟排行榜功能？**

  如果是全员的排行榜，意义不大，总会有人刷榜或者尝试打广告。

  如果是好友间的排行榜，现在的服务器支撑不起。之前世界模块做过积分排行榜功能，但很遗憾，服务器完全撑不住。

  并且当前是离线应用，番茄钟或者其他数据偏隐私，上报也有隐私安全风险。

- **有没有多平台版本（iOS、PC、WEB）？**
  
  暂时没有多平台版本。
  
  《人升》仅由两名开发者在课余和业余时间进行维护开发，并且开发和运营工作已经耗费了我们绝大多数时间。
  
  为了更佳的用户体验，目前人升是使用安卓原生框架进行开发的，代码逻辑无法在多平台进行复用。目前应用体量较小，盈利也非常薄弱，我们也缺少人力、技术和精力学习和专注于跨平台版本开发。将目前人升两三年的开发成果移植到其他端，就算是已经掌握了对应的开发技术，大概率也需要大半年以上的开发时间成本（完全专注开发其他端，停止维护安卓端的预估时间），我们目前承受不了这种风险。

  目前的规划只能在以在业余时间继续维护安卓版本为主的基础上，进行对跨平台版本开发的尝试，一步步搭积木。

  如果你有意参与跨平台版本的开发工作（目前规划是使用flutter），也欢迎联系我们。

-  **为什么没有教学视频？**

   因为缺少人力，但我们欢迎社区贡献视频。

   一款应用从诞生到上架，已经需要产品、UI设计、交互设计、项目管理、开发、市场管理、运营等数个职位了。

   而《人升》一直以来只有两位开发者，使用业余时间同时分担这些额外的职位工作，我们实在没办法面面俱到。

- **我想要了解某个具体功能的作用？比如：属性等级有什么作用？**

  建议查询本文档中的相关文档，如[事项](guide/tasks.md)、[属性](guide/attributes.md)、[商品](guide/shop_item.md)

- **我想参与《人升》的维护工作**

  感谢拥有类似的想法，目前《人升》很缺失人力资源。

  **答疑、文档维护：**无论是QQ群内答疑、文档维护、参与翻译校对、文案修改都能对我们有很大帮助。

  **开发：**因《人升》在开源方面吃过亏（被恶意打包上架），不开放源代码，因此在代码开发上未考虑好如何开放合作（而且目前还有很多老代码）。如有意也可以联系探讨。

  **UI、设计：**我们非常缺少专业的UI设计师，如果你有意参与《人升》的图标设计、内置图标贡献、界面UI设计的话，非常欢迎联系。**目前意愿上提供署名和购买两种合作模式。**

  ---

  ## 规划

  - **番茄钟会加入锁机/应用黑白名单功能吗？**

    我们不会考虑加入该功能，建议使用系统自带的功能替代或者专门的APP，如`《不做手机控》`。
    
    **原因如下：**

    1. **锁机等强制功能，与应用所倡导的激励、自驱力理念不符合。**以应用的理念开发该功能应该是支持用户划分积极、消极应用，然后根据时长分别执行奖励或惩罚。
    2. “锁机”功能属于应用功能的灰色地带，会影响其他应用的使用，会严重影响应用的市场审核、上架等流程。并且“锁机”需要大量的权限，不同的机型设备也需要专门适配开发。就像`《不做手机控》`维护了多年仍可能有大量的兼容问题，评论区甚至会同时出现“锁机”太严重和“锁机”有漏洞两种截然不同的差评理由，显得该能力有些伪需求。
    3. “锁机”有可能影响到设备的正常使用，紧急通话或者消息等，甚至可能存在法律风险。
    4. 现在越来越多的系统其实已内嵌了相应的数字健康能力，并且由于是系统级别的应用，兼容性方面不容易存在问题。
  
  ---
  
  
  
  ## 其他问题请考虑在QQ群咨询
  
  ![](http://cdn.lifeupapp.fun/qq_group_qrcode.png ':size=30%')