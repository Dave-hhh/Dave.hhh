# Dave.hhh
in here beging!
RunApp "com.tencent.mm", "plugin.sns.ui.SnsTimeLineUI" //朋友圈
RunApp "com.tencent.mm", "plugin.sns.ui.SnsMsgUI"   //朋友圈回复给我的消息
RunApp "com.tencent.mm", "plugin.sns.ui.SettingSnsBackgroundUI"  //挑选图片或者拍照更换相册封面
RunApp "com.tencent.mm", "plugin.sns.ui.ArtistUI"  //从摄影师作品挑选
RunApp "com.tencent.mm", "plugin.sns.ui.SnsTagUI"  //选择可见范围
RunApp "com.tencent.mm", "plugin.backup.ui.BakChatUI"  //聊天记录备份和恢复
RunApp "com.tencent.mm", "plugin.backup.ui.BakChatRecoverCheckUI"  //恢复聊天记录
RunAPP "com.tencent.mm", "plugin.backup.ui.BakChatUploadSelectUI"  //备份聊天记录，选择联系人
RunApp "com.tencent.mm", "plugin.backup.ui.BakChatUploadingUI"  //上传聊天记录（上传中）
RunApp "com.tencent.mm", "plugin.backup.ui.BakChatRecoveringUI"  //下载聊天记录（下载中）
RunApp "com.tencent.mm", "plugin.backup.ui.BakChatSetCryptUI"  //对上传或下载设置密码
RunApp "com.tencent.mm", "plugin.game.ui.GameCenterUI"  //微信游戏相关
RunApp "com.tencent.mm", "plugin.nearby.ui.NearbyFriendIntroUI" //附近人相关操作
RunApp "com.tencent.mm", "plugin.shake.ui.ShakePersonalInfoUI"  //摇一摇设置
RunApp "com.tencent.mm", "plugin.qqmail.ui.RoomInfoShareQrUI"  //邮箱相关
RunApp "com.tencent.mm", "plugin.mail.ui.MallIndexUI" //我的钱包相关
RunApp "com.tencent.mm"，"plugin.search.ui.FTSAddFriendUI" //添加好友页面
RunApp "com.tencent.mm", "plugin.subapp.ui.pluginapp.AddMoreFriendsUI"  //新版 “添加好友页面”
RunApp "com.tencent.mm", "ui.contact.SayHiEditUI"  //打招呼
RunApp "com.tencent.mm", "plugin.masssend.ui.MassSendSelectContactUI"  //群发助手相关
RunApp "com.tencent.mm", "ui.openapi.AddAppUI"  //添加工具
RunApp "com.tencent.mm", "ui.qrcode.ShowQRCodeStep1UI"  //分享二维码
RunApp "com.tencent.mm", "plugin.scanner.ui.BaseScanUI"  //扫描二维码
RunApp "com.tencent.mm", "plugin.brandservice.ui.BrandServiceIndexUI"  //微信公众号的组件
RunApp "com.tencent.mm", "plugin.bottle.ui.BottleBeachUI" //  漂流瓶
RunApp "com.tencent.mm", "plugin.bottle.ui.BottleWizardStep1"  //漂流瓶第一步
RunApp "com.tencent.mm", "plugin.bottle.ui.BottleWizardStep2"  //漂流瓶第二步
RunApp "com.tencent.mm", "plugin.bottle.ui.BottleBeachUI"  //漂流瓶界面
RunApp "com.tencent.mm", "plugin.bottle.ui.BottleConversationUI"  //我的瓶子
RunApp "com.tencent.mm", "plugin.bottle.ui.BottlePersonalInfoUI" //漂流瓶设置界面
RunApp "com.tencent.mm", "plugin.sns.ui.SnsUploadUI" //发送微信图片朋友圈
RunApp "com.tencent.mm", "plugin.sns.ui.SnsUpLongMsgUI" //发送微信文字朋友圈
RunApp "com.tencent.mm", "plugin.radar.ui.RadarSeachUI" //扫一扫
RunApp "com.tencent.mm", "plugin.nearby.ui.NearbySayHiListUI" //附近打招呼的人
RunApp "com.tencent.mm", "plugin.brandservice.ui.BrandServiceIndexUI"  //微信公众号
RunApp "com.tencent.mm", "plugin.brandservice.ui.SerchOrRecommendBizUI"  //搜索微信公众号
RunApp "com.tencent.mm", "plugin.massend.ui.MassSendMistoryUI"  //群发助手新建群
RunApp "com.tencent.mm", "plugin.sns.ui.SnsMsgUI" //朋友圈消息
RunApp "com.tencent.mm", "ui.bindmobile.MobileFriendUI" //查看手机通讯录
RunApp "com.tencent.mm", "plugin.setting.ui.setting.settingsUI" //设置
RunApp "com.tencent.mm", "plugin.massend.ui.MassSendHistoyUI"  //群发助手

----------------------------------------------------------------------------------------------
QQ type
----------------------------------------------------------------------------------------------

RunApp "com.tencent.mobileqq", "activity.contact.addcontact.searchContactsActivity"  //QQ好友
RunApp "com.tencent.mobileqq", "activity.NearbyActivity"  //附近的人
RunApp "com.tencent.mobileqq", "activity.contact.newfriend.NewFriendActivity"  //新朋友


----------------------------------------------------------------------------------------------
other type
----------------------------------------------------------------------------------------------

Import "shanhai.lua"
TracPrint shanhai.GetTopActivity()






end
