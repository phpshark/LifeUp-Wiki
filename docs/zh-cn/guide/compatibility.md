# 兼容性配置

## 事项提醒不生效？

应用默认使用系统通知的方式发送提醒。因为早年间很多应用滥用定时任务机制，导致目前除系统应用和部分【国民级】应用外的所有应用都没法正确执行定时任务，**这可能会导致你无法接收到提醒。**

如果你经常性接收不到提醒，可以考虑：

1. 在系统的电量管理、多任务管理中，关闭对《人升》的后台限制和电池优化，以便让《人升》更稳定地后台运行。
2. **（推荐）或者在「设置」中的「事项设置」中更改为系统日历提醒（需要额外的日历读写权限）。**



## 后台运行【华为、荣耀、VIVO】

这类设备很容易出现在息屏，或者切换其他应用后，番茄钟或者倒计时功能不再运行的异常。打开应用后才能够接收到结束的提醒。

需要配置[后台运行权限](https://consumer.huawei.com/cn/support/content/zh-cn00426500/)，才能保证番茄钟和倒计时在后台/息屏后正常运行。



## 小米

需要配置“允许后台显示界面”的权限，才能在桌面小部件上完成计数事项和进入详情页面。

并且可能是由于MIUI本身的问题，导致设备重启后，桌面小部件无法正常刷新。可以尝试重新启用一个新的桌面小部件。



## OPPO系 ColorOS

有ColorOS用户反馈：使用系统日历提醒，应用创建的日历账号会在退出应用后被移除。

应该是ColorOS的一刀切手段，目前我们并不清楚解决方案。请先尝试捣鼓日历读写权限和系统日历APP的相关日志，**并且尝试向ColorOS的系统工程师进行反馈。**


## 一加

一加的番茄钟在后台运行可能也会出现被`冻结`的情形：

进入应用后才能接收到番茄钟结束的提示。

**解决方式：**

在应用管理中，关闭对《人升》的电池优化。