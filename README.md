## YGOPro(Server)

一个YGOPro的服务端版本，运行后自动建立主机，并开启端口供YGOPro客户端连接。

这里修改用于测试开发dlpro（YGOPro 的Yu-Gi-Oh! DUEL LINKS版本 ）

使用说明请参考[源仓库](https://github.com/moecube/ygopro/tree/server)

### 已修改内容：

#### ygopro-server设置

    "rule": 2,
    
    "enable_priority": true,
    
    "start_lp": 4000,
    
    "start_hand": 4,


#### gframe

    卡组张数检测：主卡组20～30张，副卡组、额外卡组0～5张
