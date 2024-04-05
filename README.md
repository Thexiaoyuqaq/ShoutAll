# ShoutALL - V

## 感谢原作者
 这个是基于作者[RimuruChan](https://github.com/RimuruChan/ShoutAll)的ShoutALL项目重置而来。在此向原作者表示感谢！

## 关于本插件
 本插件是基于原作者的RimuruChan插件进行的修改，将其移植到Velocity。它仍然提供了原来的全服邀请功能。

## 如何使用
 通过在配置文件中，配置好相应的服务器对照名后，然后在聊天框中输入指令/hh，发送全服邀请消息。

## 安装说明
  1. 下载本插件的最新版本。
  2. 将插件jar文件放置到服务器的插件目录中。
  3. 重新启动服务器以加载插件。
  4. 配置说明
 本插件没有复杂的配置，你只需确保插件已正确安装并运行即可。

## 权限节点

| 指令                      | 权限                   | 描述                   |
| ------------------------ | ---------------------- | ---------------------- |
| /hh          | shoutall.shout           | 喊话权限           |
| /shoutallreload          | shoutall.reload           | 重载配置文件           |
| -          | shoutall.tp           | 传送权限           |
| -          | shoutall.bypass.<节点>           |  绕过冷却，如果不填节点则0冷却       |



## 配置文件 
```yaml
cooldown:  #冷却
  none: 180  #普通玩家
  vip: 90  #vip节点玩家
  vip_plus: 60  #vip+节点玩家
  mvp: 30  #mvp节点玩家
  mvp_plus: 10   #mvp+节点玩家
msg:  #消息配置
  a: "&c请等待冷却@sec秒"   #冷却中消息文本
  b: "&a喊话成功！您有@permission特权，跳过@msec秒"    #跳过冷却消息文本
server:  #服务器定义，如果没有在此配置将无法使用
  murder-1: 密室杀手    
  murder-2: 密室杀手
  nhwc-1: 你画我猜
```

## 其他
  如果你在使用过程中遇到任何问题或者有任何建议，请随时在Github上提出issue。我们将竭诚为您解决问题和改进插件。
