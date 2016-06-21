# -wechatPayment3.0
微信支付V3demo，运行demo后，点击“微信支付Demo”调起支付，

###在Build Setting中设置URL Scheme
设置这个是用于跳到微信后结束支付操作或者取消支付操作后，返回到app时的必要的设置

###在payRequsestHandler.h这个类中,填写相关的信息
APP_ID, APP_SECRET, MCH_ID, PARTNER_ID, NOTIFY_URL,SP_URL另外payRequsestHandler.mm这个类中,可修改展示给用户的名字和金额.
如果没有填写信息或者信息填写不完全，点击“微信支付Demo”会弹出个alert，直到信息无误后方可调起支付。

###为了安全并没有设置默认的这些信息.如果有不懂得地方可以issue我或者加我QQ.