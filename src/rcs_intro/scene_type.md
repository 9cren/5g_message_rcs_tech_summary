# RCS应用场景分类

* 概览
  * ![rcs_5g_message_type](../assets/img/rcs_5g_message_type.png)
  * ![rcs_5g_message_two_scene](../assets/img/rcs_5g_message_two_scene.jpg)
  * ![rcs_5g_message_application_type](../assets/img/rcs_5g_message_application_type.png)
* 包含
  * 个人用户 <-> 个人用户
    * 应用举例
      * ![rcs_application_p2p_example_android](../assets/img/rcs_application_p2p_example_android.gif)
      * ![rcs_application_p2p_many_feature](../assets/img/rcs_application_p2p_many_feature.jpg)
    * 特点
      * 和微信聊天很类似
        * 结局：（国内）很难撼动微信地位
          * ![rcs_china_weixin_public](../assets/img/rcs_china_weixin_public.png)
        * 现状：未来可能主要是处于一个辅助性的地位
    * 媒体格式
      * 文本、图片、音频、视频、表情、位置和联系人等
    * 是否在线
      * 在线消息
      * 离线消息
    * 交互对象
      * 点对点消息
      * 群发消息
      * 群聊消息
    * 相关架构
      * 基于谷歌安卓生态的RCS业务功能
        * ![google_rcs_application_arch](../assets/img/google_rcs_application_arch.jpg)
  * 个人用户 <-> 企业用户(=行业用户=某品牌)
    * 消息类型
      * `MaaP`中的`RCS商业富媒体消息`=`RCS Business Messaging`
        * ![rcs_business_messaging](../assets/img/rcs_business_messaging.jpg)
    * 作用和意义
      * 主要用于 个人<->企业 消息
      * 概述
        * ![rcs_business_msg_usage](../assets/img/rcs_business_msg_usage.png)
      * 作用
        * 为企业和个人用户之间提供消息交互接口
          * 在图片和视频等基础上增加了交互能力
            * 实现一系列轻应用功能
      * 意义
        * 方便企业向用户输出个性化服务
        * 企业可以触达用户
        * 从某种意义上来说，它很像小程序、微信公众号（服务号），甚至电话客服中心
    * 应用举例
      * 视频介绍
        * RCS的一天
          * http://t.cn/Aipds87h
      * 各种应用场景
        * ![rcs_business_msg_multiple_scene](../assets/img/rcs_business_msg_multiple_scene.jpg)
      * 机票酒店预订查询、物流查询、网购订单查询等
        * ![rcs_business_messaging_ticket](../assets/img/rcs_business_messaging_ticket.gif)
        * ![rcs_business_messaging_haidilao_order](../assets/img/rcs_business_messaging_haidilao_order.gif)
        * ![rcs_business_messaging_jd_buy](../assets/img/rcs_business_messaging_jd_buy.gif)
    * 媒体格式
      * 常见
        * 文本、图片、音频、视频、表情、位置和联系人等
      * 富媒体卡片
        * 可携带选项列表
          * 包括`建议回复`和`建议操作`