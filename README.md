

## 

## CSS
base.css  --- 基础公共样式
index.css --- 首页样式
guide --- 引导页样式

## pages --- 所有的页面
* g --- 引导页 guide

  gBinding.html    --- 绑定成功
  
  gBindingFail.html  --- 绑定失败
  
  gAddBabyInfo.html    --- 宝宝设置界面(宝宝管理) 添加宝宝信息
    * 备注
    * 宝宝昵称 输入文字删除图标自动出来
    * 未作
    * 宝宝年龄 弹窗未做
  
  gSetBaby.html    --- 宝宝设置界面1 我的宝宝
  g 删除宝宝确认界面 多了弹窗
    * 备注
    * 删除界面的删除图标不一致 .selBtn .mui
  
    * 未作
    * 弹窗的动画未做
  
  gInitLogin.html  --- 初次登陆未连接设备界面

  g --- 删除宝宝确认界面

  gLoading.html    --- 添加中请稍后
  g 搜索中请稍后 页面
             
  gAddDeviceSuc.html --- 设备添加后的界面
    * 与gInitLogin   ---初次登陆未连接相同 加俩几个类名
    * 更换设备按钮的图标暂未找到用 loop 代替

  gBindingList.html  --- 选择绑定设置界面
    * js 未作 点击色变

* b --- 底部页面 buttom
  bIndex.html --- 地图弹窗 (地点索引列表) index
  
  bNewPlan.html --- 新建服药计划 np
    *  未作
    *  服药时间弹窗 没加
    *  选择药品小图标没加
    *  起始时间和结束时间 的弹窗
    
    * 备注

  bStoreMap.html --- 药店1 (地图) sm
    * 未作
    * 底部导航什么的用做不
  
  bPlanList.html --- 用药计划2 (列表) pl
    * 备注
    * 滑动调用的 mui 原生滑动

  bInfo.html --- 资讯 info
    * 备注
    * PIC 用的 :before 伪元素 
    * 未作
    * 底部导航的图标未用 
    * 底部导航的绿框 有问题

* f --- 主功能页面 function
  fSetWarning.html --- 报警设置
    * 未作
    * 提醒设置 弹窗未作
    * 备注
    * 开关使用的mui原生开关
  
  fContactUs.html --- 联系我们
    * 未作
    * 左侧小图标
  
  fDataAnalyze.html --- 数据分析(图标)
    * 备注
    * &#8451; 摄氏度符号
  
  fTempChart.html --- 温度(图表)
  f 主页面低烧 高烧 正常



  f 点击头像后，出现侧滑页面(个人中心)  
  f 服药功能主界面
  fTempChart1.html --- 温度(图表)
    * 备注
    * 侧滑菜单 向左滑出
    * 蒙版  mui-backrop 默认显示
    * 切换账号 加减 类 active 控制显示隐藏
    
  
  fInfoList.html --- 消息界面1(列表)
    * 备注
    
  fInfoDetails.html --- 消息界面2(消息详情)
    * 备注
    
  fMedicineEdit.html --- 新增药品编辑页面
    * 未作
    * 图标未放

  fChangePassword.html --- 修改密码
    * 备注
    * 使用的是 注册页面的找回密码块，注册面login的css 
    * 未作
    * 提交失败(黑色弹窗)
  fMedicineList.html --- 药品目录页面
    * 备注
    * 
  fMedicineShow.html --- 药品详情页面

* l --- 注册页面 login
  lLogin.html --- 登陆界面
    * 未作
    * 用户名不存在 (黑色弹窗)
    * 备注
    * 输入框 flex-shrink 定义缩小比例
  
  lSignIn.html --- 注册界面
    * 未作
    * 该手机号已注册 (黑色弹框)
    * 备注
    * 输入框 flex-shrink 定义缩小比例
  lFindPassword.html --- 找回密码
    * 未作
    * 请输入正确的手机号 (黑色弹框)
  
  lAddAvatar.html --- 头像设置/添加
    * 备注
    
  lAvatarEdit.html --- 头像编辑
    * 备注
    * 
  
  lSigninSuc.html --- 注册成功
  lFindSuc.html --- 找回成功

哈哈哈 我是测试checkout 检出出错的