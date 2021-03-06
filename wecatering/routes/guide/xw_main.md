
### <a name="浏览器">餐厅管理浏览器版本使用说明</a>
> #### 注意：关于浏览器的支持说明
> ####  支持的浏览器
> - 火狐浏览器（推荐使用）
> - 谷歌浏览器（推荐使用）
> - opera浏览器
> - 360浏览器【极速模式】（推荐使用，请参考下文如何打开极速模式）
> - 微信内置浏览器
> - 小米手机内置浏览器
>
> ####  支持不良的浏览器
> - qq浏览器
> - 百度浏览器
> - UC浏览器
> - windows自带IE浏览器(**明确不支持**)

> #### 未在列表中的浏览器尚未测试

#### 目录

1. <a href="#账户注册">账户注册</a>  
2. <a href="#登录">登录</a>  
3. <a href="#编辑餐厅">编辑餐厅</a>  
4. <a href="#添加小号">添加小号</a>  
5. <a href="#编辑菜单">编辑菜单</a>  
6. <a href="#制作餐桌二维码">制作餐桌二维码</a>  
7. <a href="#处理订单">处理订单</a>  
8. <a href="#查看已结订单">查看已结订单</a>  
9. <a href="#查看经营数据">查看经营数据</a>  
10. <a href="#退出登录">退出登录</a>  


#### 具体操作

> **注意：第1-6步为准备工作，完成之后，系统即可投入使用**

#### 1 <a name="账户注册">账户注册</a>
- 打开欣味首页[http://118.89.30.214/](http://118.89.30.214/)
- 点击网页右上角（导航栏右侧）的注册按钮，页面会跳转至注册页面
- 输入用户名、手机号、密码，输入完成，且没有提示错误时，点击提交。提交成功后，页面会跳转至登录页面

#### 2 <a name="登录">登录</a>
- 点击网页右上角（导航栏右侧）的登录按钮，页面会跳转至登录页面
- 输入手机号、密码，点击提交。如果手机号及密码都正确，且网络正常，提交成功后，页面会跳转至管理页面首页（订单处理页面）

> **注意**： 餐厅信息页面，可以对餐厅信息和账户信息进行修改

#### 3 <a name="编辑餐厅">编辑餐厅</a>
- 点击管理页面的“餐厅信息”标签，在餐厅信息框中，点击编辑餐厅，可以更改餐厅信息。
> **注意**：绑定微信订阅号功能暂时未开通

#### 4 <a name="添加小号">添加小号</a>
- 点击管理页面的“餐厅信息”标签，在账户信息框中，点击添加小号按钮，可以添加小号账户。各小号和主帐号同时登录时，各账户对订单的处理状态会实时反馈到其他账户上面。
> **注意**：目前每个账户最多只允许添加3个小号账户

#### 5 <a name="编辑菜单">编辑菜单</a>
- 点击管理页面的“菜谱信息”标签，点击添加菜单按钮，可以添加菜单。添加菜单之后，可以为菜单添加图片。
- 点击“删除”按钮，可以删除菜单
> **注意**
> 目前每个账户最多只允许添加60道菜单
> 请先添加菜单之后，再点击编辑按钮，在编辑框中选择图片，务必要点击上传图片，图片才会保存，图片会保存为100*100像素格式，以适应在微信浏览器中显示

#### 6 <a name="制作餐桌二维码">制作餐桌二维码</a>
为了让食客通过扫码点餐，需要给自己的餐厅制作二维码，二维码的格式如下：

```
样例
http://118.89.30.214/p/15606181258/2

订单地址格式说明：
地址形式：http://118.89.30.214/p/参数1/参数2
参数1前面的内容为固定格式
参数1的内容为商户注册的手机号（如：15606181258）
参数2的内容为餐厅的餐桌号（如：1）
```
将每桌对应的二维码打印出来，粘贴在餐桌显眼位置，既可以用于食客自主点餐，也可以用于餐厅服务人员用于内部点餐管理。

#### 7 <a name="处理订单">处理订单</a>
- 接收订单  
打开管理页面“未结订单”标签页。食客提交订单之后，订单会实时显示在“未结订单”标签页面内。订单按照时间倒序排列，最近接收的订单排列在最前。
> #### 注意：浏览器版本的管理页面每页最多显示20份订单，超过20份之后，订单会在不同页面显示。

- 处理订单  
     - 接收菜单  
     点击接收按钮，表示厨房已经开始加工所选菜品。选择之后，按钮颜色会变成灰白色。
     - 已上菜单  
     点击已上按钮，表示所选菜品已经上桌的数量，菜品上满对应数量之后，按钮颜色会变成灰白色。
     - 结算菜单  
     所有菜品上齐，且食客已经支付结算后，点击去结算按钮，订单会从未结订单页面移出（在已结订单页面可以查看）。

#### 8 <a name="查看已结订单">查看已结订单</a>
打开管理页面“已结订单”标签页。该标签页面会显示已经结算的订单，仅作订单核对使用。

#### 9   <a name="查看经营数据">查看经营数据</a>
打开管理页面“报表”标签页，可以查看餐厅的经营数据。目前开放的数据内容为：
- 昨日经营总额
- 昨日订单总数
- 昨日客单价分布散点图
- 昨日每道菜品销量柱状图

> #### 注意：  
> 此处内容会经常根据情况作出调整，试用阶段对所有店铺开放。试用结束后，不同类型用户可以查看不同精细度的报表数据

#### 10 <a name="退出登录">退出登录</a>
用户结束使用后，请点击页面右上角的“注销”按钮，退出账户。

---
#### 注意事项
- 已使用推荐浏览器，但部分功能应用不正常？

```
如有这种情况，请将所使用浏览器更新为最新版本
```
- 360浏览器页面显示异常？

```
请打开360浏览器极速模式。
方法：
在360浏览器网址输入栏最后，点击浏览器‘e’图标，图标切换为一个圆圈，此时就切换为极速模式了。刷新页面，页面即可正常显示
```


---

### <a name="安卓">餐厅管理安卓版本使用说明</a>


> #### 注意：
>  App目前只提供安卓版本  
>  App目前未提供注册功能，请在浏览器页面中注册账户  
>  App目前只提供当日订单处理的功能。其他功能会随着版本进化逐渐退出  
>
>

#### <a name="app安装">安装</a>
请向客服索取apk安装文件。按照提示步骤安装。
注意：要求安卓系统版本>=6.0

#### <a name="app登录">登录</a>
请输入您注册的账户或者小号登录。登录之后默认进入订单处理页面。

#### <a name="app导航">导航</a>
App可通过在左侧滑动页面来调出导航页面

![image](/static/guideimg/侧滑导航.jpg)

#### <a name="app处理订单">处理订单</a>
系统默认首屏是订单处理页面。如果当日暂时还未接收订单，此页面显示如下：

![image](/static/guideimg/首屏.jpg)

当接收订单之后，页面如下图。订单处理方式与网页版相同。

![image](/static/guideimg/订单处理.jpg)

#### <a name="app查看已结订单">查看已结订单</a>
app页面左侧右滑，调出导航页面，选择已结订单，可在已结订单页面查看已结订单

#### <a name="app查看账户信息">查看账户信息</a>
app页面左侧右滑，调出导航页面，选择账户信息，可以查看登录帐号。

#### <a name="app退出登录">退出登录</a>
app页面左侧右滑，调出导航页面，选择账户信息，点击登出登录，可以退出app。

---

### <a name="食客使用说明">食客使用说明</a>

1. 使用微信扫描餐桌上的二维码
2. 选择菜单
3. 提交订单
4. 查询订单（暂未开放）


