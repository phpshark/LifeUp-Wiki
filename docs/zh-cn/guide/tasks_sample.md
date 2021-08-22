# 事项范例

这里会讲解事项相关的内容~
比如怎么创建工作日事项、计数事项如何使用以及各种使用案例。


人升的事项依靠着**开始时间、期限时间和重复频次**的配合，可以建立出各种复杂情况的待办事项。


**以下是一些情况的例子：**

<br />

## 1. 琐事

![](_media/tasks/task_01.jpg ':size=30%')

如果你把《人升》当作一款ToDo应用，而不是倾向于习惯养成应用的话，`单次`待办事项可能是最普遍的事项类型了。

现实生活中的任何一件事情，都可以创建为一件待办事项：

- 今晚10点去某个地方
- 周末记得带伞
- 计划开发某个功能
- 购物清单
- 今晚有个特殊会议
- 等等等等...

`单次`待办事项可以没有期限时间（即截止时间），所以在创建时十分简单。

最简单的待办事项只需要输入`待办事项`内容即可。

其他选项可以按需设置：如果有期限时间，那么可以设置期限时间；如果需要提醒，那么设置提醒时间即可。

---

## 2. 习惯养成（每日早起、每周跑步等）

![](_media/tasks/task_02.jpg ':size=30%')

调整**“重复频次”**为相应的“每日”或者“每周”后，再根据情况看要不要调整**“期限日期”**。

当“重复频次”不为“单次”或者“无限”的情况下，期限日期会默认为“当天”。（每周事项会默认期限时间为“周日”）

对于“每日”、“每周”事项来说，这样设置一般是合理的。

而对于重复频次并非“每日”、“每周”的事项，可以根据具体情况调整期限：

> 1. 比如1号的时候建立“每10天”事项，不改期限日期。那么下一次的事项的时间会在2-10号。
> 2. 如果你调整期限日期到2号。那么下一次的事项时间就会在3-11号。（相当于延后一天）

### 习惯样例1：每日早起

**如果你不需要约束打卡时间的话**，只需要创建一个内容为`早起`，重复频次为`每日`的事项即可。

![](_media/tasks/sample_01.jpg ':size=30%')

**如果你想要约束打卡时间为`早上7:00-10:00`的话**，按以下步骤设置事项：

1. 输入待办事项内容为`早起`
2. 重复频次调整到`每日`
3. 点击更多选项，将「开始时间」设置为`第二天 07:00:00`
4. 将「首次期限日期」设置为`第二天 10:00:00`

### 习惯样例2：每周跑步一次，持续4周。

可以按以下步骤创建事项：

1. 输入待办事项内容为`跑步`
2. 重复频次调整到`每周`
3. 点击更多选项，设置目标重复次数为`4`


### 习惯样例3：每周跑步3次

目前应用还没有在重复周期内至少、至多完成多少次的设置项。
实现这类设置有多种方式：

【1】第一种方式是使用计数事项，缺点是只有在结算时才能统一获得奖励。

可以按以下步骤创建事项：

1. 输入待办事项内容为`跑步`
2. 重复频次调整到`每周`
3. 修改事项类型为`计数事项`，输入次数为3

【2】第二种方式是使用无限事项+目标重复次数，好处是每一次完成都能直接获取奖励，缺点是每一周都需要设置一次事项。

可以按以下步骤创建事项：
1. 输入待办事项内容为`跑步`
2. 重复频次调整到`无限`
3. 点击更多选项，设置目标重复次数为`3`
4. 期限日期设置为`周末`
5. 下周时，重新创建一个相同设置的事项。

### 习惯样例4：每天喝8杯水

这类事项也有多种设置方式。

【1】第一种方式是使用计数事项，设置步骤如下：

1. 输入待办事项内容为`喝8杯水`
2. 重复频次调整到`每日`
3. 修改事项类型为`计数事项`，输入次数为8

【2】第二种方式是使用子任务，可以为每个子任务设置金币奖励和提醒时间，设置步骤如下：

![](_media/tasks/sample_02.jpg ':size=30%')

1. 输入待办事项内容为`喝8杯水`
2. 重复频次调整到`每日`
3. 输入子任务，设置每个子任务的奖励

### 习惯样例5：当天23:00-第二天2:00

![](_media/tasks/task_04.jpg ':size=30%')

通过开始时间、期限时间和重复频次的配合，你能轻松地设置出情况很复杂的待办事项。

只需要设置**开始时间为具体的“当天23：00”**，期限时间为**具体的“第二天2：00”**，**重复频次为“每日”**即可。


### 习惯样例6： 指定每周几（仅工作日、仅周末等）

![](_media/tasks/task_06.jpg ':size=30%')

<del>设置“重复频次”为“每日”后，在“重复频次”的输入框右侧点击“设置忽略”。然后就能指定每周几重复了。</del>

在设置“重复频次”时，直接选择“每周几”即可设置。

---

## 3. 进阶用法

### 坏习惯惩罚

虽然《人升》并没有专门的「坏习惯」板块，**但其实是支持经验值/金币惩罚的（可以在`自定义设置`中更改惩罚系数，金币默认为不惩罚）。**

**要实现坏习惯惩罚的效果的话，只需要逆向创建事项即可。**

<br />

**比如：**

你想当自己「贪食」的时候，给予自己惩罚。

那么，完全可以创建一个**“每日坚持不贪食”**的待办事项。

**当你犯错的时候，只要不完成这个事项，或者直接放弃当天这个事项就能接受惩罚了。**

![](_media/tasks/sp_01.jpg ':size=30%')

还有一些特殊做法，比如，直接使用商品来管理坏习惯惩罚。配合商品的使用效果，也可以很自由地设置好惩罚的经验值数值和金币数值。

![](_media/tasks/sp_02.jpg ':size=30%')


### 比例奖励

![](_media/tasks/sp_03.jpg ':size=30%')

计数事项支持按比例结算奖励，利用这个机制，你可以手动实现自我评价功能。

比如创建一个计数目标次数为10的事项，完成事项时，可以把这个计数次数当作评分使用。

当觉得自己的事项完成满意度一般般，可以打个5分，只收取50%的奖励。

![](_media/tasks/sp_04.jpg ':size=30%')


### 阶段性奖励

![](_media/tasks/sp_06.jpg ':size=30%')

比如有一个每日事项「人升签到」，你想要设置完成该事项50次、100次、150次时有特殊奖励的话。

![](_media/tasks/sp_05.jpg ':size=30%')

因为事项本身的奖励设置是针对每一次而言的，所以纯使用事项目前达不到这种效果，但可以使用「自定义成就」机制来实现该效果。
