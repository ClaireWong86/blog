# 创建/应用License

# 1.创建License
#### 1.1.License从哪儿来
如何授予客户-License数量
-公有云版本
客户呼叫商务——商务线下沟通——商务确认订阅数量&价格——商务在后台系统起给客户购买——客户收到通知
-私有化部署版本
私有化部署也要控制license数量，实现方式是什么？
可能是通过配置“授权码”


#### 1.2.License的类型
-空间资源：固定工位数量、共享工位数量
-用户数量：无限制


#### 1.3.空间创建的入口
1)  新增工位
2）DP系统同步
3）批量导入


#### 1.4.如何购买
-状态：测试版/试用版、正式版、旗舰版
-数量：
-单价：
-时间：年付费/月付费
-金额: 计算出金额
————————————————
-SKU：会议室、工位（固定工位、共享工位）
-费用类型 ：新建/续单
-订阅说明：免费试用、付费订阅
-折扣劵/
-红包额度
-备注
—————————————————
购买日期
收费开始日期
收费结束日期
—————————————————
总价计算方式
SKU1:￥10,000(2个/年)
SKU2:￥5,000(10个/年)
总价：￥15,000


权限确实是开放给公司内部的人操作，但是各种操作记录也是要有数据留存，以后有据可依。


#### 1.5.付款方式
-支付走线下流程
-支付记录+开号记录 线上要留存下来


#### 1.6.版本介绍
目前全员开店有测试版，基础版，高级版和旗舰版。
测试版：工位数量上限：100人／费用：0元
基础版：工位数量上限：10000人／费用：计算规则A
高级版：员工数量上限：50000人／费用：计算规则B
旗舰版：员工数量上限：100000人／费用：计算规则C
共享工位与固定工位的的单价不一样，购买不同级别的license数量单价也不一样。
拆分版本一般情况下是要区分各版本的功能，如果只是不同数量区间的价格不同的点，可以不用区分这么细


#### 1.7.咨询服务
谁来操作
谁来接待
提供什么服务
客户的类型、客户的问题、客户如果购买该怎么往下面推动，客户不购买该如何记录这个客户信息




# 2.应用License
#### 1.License到达数据之后有什么影响
-不能再新增这种类型的有License的工位了
-续费的工位数比以前低了
在产品没有降低到License数量之前，应用端的工位预订&工位绑定的操作不能使用，取消/进行中到还是可以继续进行的。
提示：
#### 2.企业到期之后有什么影响
产品不能使用（具体用什么手段让产品不能使用？待定论）
给3个月的付费期时间：在此期间企业可以续费重新使用，所有数据不会丢，目前是给企业走商务流程留出一部分时间
3个月付费期时间到了：


#### 3.如何提醒续费
设置时间提醒
通过邮箱发送




# 3.解决方案
影响系统：Desking、租户后台系统
### Desking
【空间管理】
新增字段：Licensing


【应用操作与License相关联】
比如License超过了，不能操作预订/分配的操作


### 租户后台系统
【新建】
新用户，第一次购买


【续费】
原来的到期时间往后增加，人数不增/人数增加/人数减少


【升级】
人数增加，到期时间没有变化


【降级】（❎不允许这个操作）
人数降低，到期时间没有变化


【购买历史】【订单记录】
-怎么设置购买历史记录的字段
-私有化部署和公有云版本的订单记录会不会有的有，有的没有


【联系我们】
如需购买、续费、增加授权数量，请点击“联系我们”


【删除】（可以暂时先不做，没那么急）
删除租户


【】


### 私有化部署的License
-暂无-




# 资源
[https://docs.seniverse.com/product/buy/upgrade.html](https://docs.seniverse.com/product/buy/upgrade.html)
[https://hc.qingflow.com/help-center/release/](https://hc.qingflow.com/help-center/release/)
[https://www.e-ducation.cn/question/system_page/13/](https://www.e-ducation.cn/question/system_page/13/)
[https://help.youzan.com/displaylist/detail_4_4-2-291](https://help.youzan.com/displaylist/detail_4_4-2-291)
[https://www.google.com/search?sxsrf=ALeKk00iLm5IRUzq0tMku6_Gjz3flbW07Q:1596599039373&source=univ&tbm=isch&q=%E5%8D%87%E7%BA%A7%E7%BB%AD%E8%B4%B9&sa=X&ved=2ahUKEwimo9z0koPrAhWHdd4KHT9JBowQsAR6BAgKEAE&biw=1392&bih=789#imgrc=1Q6WyaPM71wOVM](https://www.google.com/search?sxsrf=ALeKk00iLm5IRUzq0tMku6_Gjz3flbW07Q:1596599039373&source=univ&tbm=isch&q=%E5%8D%87%E7%BA%A7%E7%BB%AD%E8%B4%B9&sa=X&ved=2ahUKEwimo9z0koPrAhWHdd4KHT9JBowQsAR6BAgKEAE&biw=1392&bih=789#imgrc=1Q6WyaPM71wOVM)


