# TranspondSmsWeb
TranspondSms Tsms的web端的开源实现(不涉及消息相关操作，如果想管理消息请使用[消息中心项目MyMessageCenter](https://github.com/xiaoyuanhost/MyMessageCenter.git))
1. 主要定义功能、交互标准、交互接口
2. 前后端分离
3. 提供简单实现用于用户自搭建
4. 提供一个在线的站点

### 功能列表：
|  功能   | 描述  |
|  ----  | ----  |
| 接口设计  | - |
| 前端页面  | done |
| 接口实现  | 简单PHP实现[pneedle-framework](https://github.com/timsengit/pneedle-framework)， |


# 整体架构及相关API接口设计  
## 接口使用RESTful  
> 鉴权相关  
>> /user/login  
>> /user/logout  
>> /user/info  
  
> 配置相关  
>> 转发规则
>>> /rule  
  
> 设备相关在线查看管理  
>> /device
