

##用例图
###公司人员
公司总经理：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/gAVTZxL61d.emhO1UHWayo4UatcFsPYxN9l6pKtIkwQ!/b/dIMAAAAAAAAA&bo=NwIYATcCGAEDACU!&rf=viewer_4"/><br>
公司系统管理员：<br>
<img src="http://a2.qpic.cn/psb?/V11pPhXt45Tccw/JqtPxFj3llig2MWe7wnZDaADkb53xWG*Yk5rCjnQJ8E!/b/dJQAAAAAAAAA&bo=*ALMAfwCzAEDACU!&rf=viewer_4"/><br>
营运中心负责人：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/GZHzT0YcMO8NiNTOt5vVTuAoTcGz8tIpLIeGEMRaycs!/b/dHMBAAAAAAAA&bo=qQEzAgAAAAADALw!&rf=viewer_4"/><br>
员工：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/fFnPbsAL8n6MmGUGQx7JxRSWoWZKxa7UMRN*T0.ullU!/b/dHEAAAAAAAAA&bo=rQIhAq0CIQIDACU!&rf=viewer_4"/><br>
联络员：<br>
<img src="http://a1.qpic.cn/psb?/V11pPhXt45Tccw/DEW2qhqVoeXOLX.8YOQsATD6d2DJGO4BHDq1ZIF.Pd4!/b/dGUBAAAAAAAA&bo=UgMXAlIDFwIDACU!&rf=viewer_4"/><br>
投诉管理员<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/Sjr8tKj2PGJ58SwDrcagKAKMYVQ31ewXROzeC.o*VIc!/b/dJIAAAAAAAAA&bo=IwJVASMCVQEDACU!&rf=viewer_4"/><br>
营运中心出纳：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/Sjr8tKj2PGJ58SwDrcagKAKMYVQ31ewXROzeC.o*VIc!/b/dJIAAAAAAAAA&bo=IwJVASMCVQEDACU!&rf=viewer_4"/><br>
###服务站
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/UnPDTBA52BFU5xZEaZR7gLSSLFn3CjRy7mk8U8qf3Vk!/b/dIMAAAAAAAAA&bo=AgMKAgIDCgIDACU!&rf=viewer_4"/><br>
###政府
<img src="http://a1.qpic.cn/psb?/V11pPhXt45Tccw/YG0*nvSSIHHzePC9GcAtY5hEDZrrs6Ynxa*vANIV4ss!/b/dGUBAAAAAAAA&bo=NgJEATYCRAEDACU!&rf=viewer_4"/><br>
###网站用户
普通消费者：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/*5ZEq.kxswlsYSWVy4OwcF68sBV6EsYgXpVzSkQE4z0!/b/dGQBAAAAAAAA&bo=2AImAtgCJgIDACU!&rf=viewer_4" width="700px" height="900px"/><br>
菜商、餐馆：<br>
<img src="http://a2.qpic.cn/psb?/V11pPhXt45Tccw/PzyrKMW4cDYDutO4*XAoWDwNJG80ECa0kXZocOO82K0!/b/dJQAAAAAAAAA&bo=sAMCArADAgIDACU!&rf=viewer_4"/><br>
供应商：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/ARSa7yvDP3o.YOBzpSz1hTEKxCB.dhpILH5pvFzbAmc!/b/dGQBAAAAAAAA&bo=uQInArkCJwIDACU!&rf=viewer_4"/><br>





##用例描述


|               |                             |                                           |
| ------------- | ----------------------------|----------------------------------------   |
|用例名称	      |放入购物车                   |                                           |
|主要参与者	    |普通用户（餐馆菜贩子）       |                                           |
|前置条件     	|在本系统上注册过，成为会员。 |                                           |
|触发器	        |点击提交订单，用例被触发。   |                                           |
|典型事件过程	  |      参与者动作             |     系统响应                              |
|               | 第一步：用户选择数量后，    |第二步：当用户点击后，系统进行判断，       |
|               |  点击加入购物车，           |若已登录，则直接加入购物车，否则执行下一步 |
|               | 第四步：用户输入登录信息；  |第三步：系统记录用户选择的数量和商品，     |
|               |                             |后跳至用户登录界面，让用户进行登录；       |
|               |                             |第五步：当用户输入后，系统判断成功         |
|               |                             |直接将用户选择的信息加入到购物车中。       |
|后置条件	      |用户加入购物车后，就可以下单购买。                                       |
|业务逻辑       |注册用户才能加入购物车内。                                               |



|               |                             |                                           |
| ------------- | ----------------------------|----------------------------------------   |
|用例名称	      |结算                         |                                           |
|主要参与者	    |普通用户（餐馆菜贩子），银联（支付宝）系统       |                |
|其他感兴趣关联人员	|财务审核，有没有到账。|
|前置条件     	|在本系统上注册过，成为会员。订单提交成功。 |                          |
|触发器	        |点击结算，用例被触发。  |                                           |
|典型事件过程	  |      参与者动作             |     系统响应                              |
|               | 第一步：用户，点击结算，选择结算方式。|第二步：根据用户选择的结算方式，|
|               |       第三步：其他系统操作完后，返回参数    |方式，银联，或者支付宝，跳     |
|               |                             |至其他系统进行相关操作。 |
|               |                             |第四步：根据参数进行判断，    |
|               |                             |用户是否已经成功付款；     |
|               |                             |第五步：当用户输入后，系统      |
|               |                             |判断成功，直接将用户选择的       |
|              |                              |信息加入到购物车中。|
|后置条件	      |下单成功后，等待送货，取货。                     |





|               |                             |                                           |
| ------------- | ----------------------------|----------------------------------------   |
|用例名称	      |服务站取货              |                                           |
|主要参与者	    |普通用户（餐馆菜贩子），服务站（物流司机）   |                                           |
|前置条件     	|已经下过单，并成功付款 |                                           |
|触发器	        |当用户收到取货信息。   |                                           |
|典型事件过程	  |      参与者动作             |     系统响应                              |
|               |第一步：用户去服务站取货。 |第二步：服务站核对信息，查      |
|               | 第四步：用户取货后，在自己         |找该用户对应本服务站下过 |
|               | 的账户中查找该订单，点击收  |的未签收的订单。     |
|               |  到货。到此，用户在服务站取  |第三步：核对成功后，用户签      |
|               |          货完成。             |收，在系统上点击用户已经成        |
|               |                             |功取货。       |
|后置条件	      |用户加入购物车后，就可以下单购买。                                       |
|业务逻辑       |注册用户才能加入购物车内。                                               |



##主要流程图
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/B8eOm0dQpiPwQvq4XrpNPboJOvUhLjNykvFXgNyH0xw!/b/dHMBAAAAAAAA&bo=IgOAAgAAAAADAIY!&rf=viewer_4"/>
<img src="http://a1.qpic.cn/psb?/V11pPhXt45Tccw/.c43yKM.YdFsExjX.AroxgGrzndfZBukB*tU3IEnivs!/b/dHQBAAAAAAAA&bo=wwQ2AgAAAAADANY!&rf=viewer_4"/>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/H90eappu45owOHnsu4FdfJ0s*yuR1FKqIWSQVZUsg*g!/b/dHMBAAAAAAAA&bo=tQI5AgAAAAADAKk!&rf=viewer_4"/>
<img src="http://a1.qpic.cn/psb?/V11pPhXt45Tccw/XTt9yw5Sigdgppud7qqUFBZmAHo5XYZjJEf5kHdCZF0!/b/dHQBAAAAAAAA&bo=VAROAgAAAAADADk!&rf=viewer_4"/>

##部分ER图
商品、商品详情、商品评价、购物车和商品视频：<br>
<img src="http://a1.qpic.cn/psb?/V11pPhXt45Tccw/mPRzNzWYgXZqxDAa*vrFCbyxz60PhbE7Angp7lSa9ws!/b/dHQBAAAAAAAA&bo=.wG0AQAAAAADB20!&rf=viewer_4"/><br>
服务站和服务站绩效评价：<br>
<img src="http://a1.qpic.cn/psb?/V11pPhXt45Tccw/Z3q6ibNpn5Tv.dHAQ0BzTw.Uu0bJVglyLBwVEI2U9DQ!/b/dHQBAAAAAAAA&bo=jwHsAAAAAAADAEc!&rf=viewer_4"/><br>
供应商、供应商需求和供应商竞价：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/Y2hNTLa8gHOlpOS7Ogn0ACj*SS8orbOLXzvs0gA57iw!/b/dHMBAAAAAAAA&bo=fgH0AQAAAAADAK8!&rf=viewer_4"/><br>
部门、员工和角色：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/0kuDAbS84125bxYdWyHKggfx0ca30JtLJwwluWSr8U8!/b/dHMBAAAAAAAA&bo=fgFWAQAAAAADAA0!&rf=viewer_4"/><br>
权限设定：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/fgUg8EV9hNDM7kKV7c940PtWcAwbh.fsQcDVHQrp1IQ!/b/dG4AAAAAAAAA&bo=QgLOAAAAAAADAKs!&rf=viewer_4"/><br>


##部分页面图
首页：<br>
<img src="http://a1.qpic.cn/psb?/V11pPhXt45Tccw/4ewQbii42QQGjF9expiFzEp6lHUJlhwK0UrfAe3XwV4!/b/dHQBAAAAAAAA&bo=cgSAAgAAAAADANE!&rf=viewer_4"/><br>
商品管理页面：<br>
<img src="http://a1.qpic.cn/psb?/V11pPhXt45Tccw/y4H2d73RoigIdQovl9ZmkGaapBes8J5WasqSxB9WpKA!/b/dG8AAAAAAAAA&bo=LAWAAgAAAAADAI4!&rf=viewer_4"/><br>
供应商信息页面：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/5xTjKfhqGstBUs2ek03dBW0aEjEJjrrhTxMztydPAf4!/b/dHMBAAAAAAAA&bo=PAU0AgAAAAADBy0!&rf=viewer_4"/><br>
退货管理：<br>
<img src="http://a3.qpic.cn/psb?/V11pPhXt45Tccw/8x9KEQKWZaJPOGny2uMh8zk3sp94oaQNxsFOe.u0IRs!/b/dG4AAAAAAAAA&bo=QgVSAgAAAAADADI!&rf=viewer_4"/><br>
会员管理：<br>
<img src="http://a1.qpic.cn/psb?/V11pPhXt45Tccw/3Iiawf1e21QmVjjBD*iOO9MhqOijS*.iU5vFNXXO8YE!/b/dHQBAAAAAAAA&bo=LwWAAgAAAAADAI0!&rf=viewer_4"/><br>