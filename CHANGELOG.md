# 版本更新说明:

## v1.0.1 @ 2017-07-17

### Feature

* [sdk] 新增加入聊天室接口(joinChatRoom)
* [sdk] 新增成员加入聊天室的回调(memberJoinChatRoomSuccess)
* [demo] 新增发送位置消息功能
* [demo] 新增浏览收到的小视频功能

## v1.1.0 @ 2019-03-22
### Feature
+ [sdk] [demo] 增加token登录
+ [demo] 新版demo，修改ui
+ [demo] 增加搜索功能
+ [demo] 增加联系人按字母排序
+ [demo] 增加最近聊天按时间排序
+ [demo] 增加群组消息提醒
+ [demo] 增加测滑删除功能
+ [demo] 增加聊天历史分页
+ [demo] 增加用户名不区分大小写
+ [demo] 增加接收文件消息提示
+ [demo] 适配iphonex，以及 xs max等机型
+ [demo] 主页面由联系人页改为聊天页
+ [bug] 修改A给好友B发语音消息，B没有显示语音的未读消息数
+ [bug] iOS聊天界点击输入框进行输入时历史消息展示不合理
+ [bug] iOS端小程序收到消息时，会话界面来消息的提醒有时会没有提醒，只显示消息数
+ [bug] 语音消息时长为0

## v1.1.1 @ 2019-04-10
### Feature
+ [sdk] 增加重连机制
+ [demo] 实时更新联系人列表
+ [bug] 修复部分已知bug

## v1.2.0 @ 2019-06-22
### Feature
+ 增加消息状态，比如断网时发的消息显示失败。
+ 增加socket连接成功的提示
+ 修改了语音消息播放时再下载
+ 修复聊天页面切后台，再切前台收到的离线消息有重复
+ 由rest1迁移到rest2后开始校验token,导致附件消息收不到
+ 语音发送成功后点击听取后，语音依然闪烁动画
+ 联系人分类为#，显示问题。
+ sdk增加onSocketConnected事件 – socket连接成功
+ sdk onError 增加type='sendMsgError'发送消息失败
+ sdk 重连时关闭上次的socket
