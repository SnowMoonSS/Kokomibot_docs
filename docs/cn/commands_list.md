## 功能列表

### **❗ `<>` 内的参数是必须的，`[]` 内的参数的可选的**

### **❗ 空格是切割指令参数的关键，请不要随意添加或者删除空格。单个参数（例如船名）之间请不要添加空格，国服ID带空格请加上，已做特殊处理**

 
| 指令                                                     | 示例                                                                                | 功能描述                                                                                                                                                                             |
| -------------------------------------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `kkm bind <服务器> <游戏ID>` | `kkm bind asia Maoyu` | 绑定游戏账号 |
| `kkm me bind` | `kkm mebind` | 查询当前账号的绑定及账户数据 | 
| `kkm lang <语言>` | `kkm lang cn`<br>`kkm lang en` | 切换账户使用的语言 |
| `kkm pr <on/off>` | `kkm pr on`<br>`kkm pr off` | 启用或者关闭PR评分 |
| `kkm recent on` | `kkm recent on` | 启用recent功能 |
| `kkm recents on` | `kkm recents on` | 启用recents功能 |
| `kkm me` | `kkm me`<br>`kkm asia Maoyu` | 查询账号总水表(简略) |
| `kkm me info` | `kkm meinfo `<br>`kkm asia Maoyu info` | 查询账号总水表(详细) |
| `kkm me oper` | `kkm me oper`<br>`kkm asia Maoyu oper` | 查询账号剧情数据 |
| `kkm me cw` | `kkm me cw`<br>`kkm asia Maoyu cw` | 查询自己参加过的cw赛季的数据 |
| `kkm me rank` | `kkm me rank`<br>`kkm asia Maoyu rank` | 查询账号排位赛数据 |
| `kkm me rank <赛季>` | `kkm me rank s14`<br>`kkm asia Maoyu rank s11` | 查询账号指定排位赛季数据 |
| `kkm me ship <船名>` | `kkm me ship 大和`<br>`kkm asia Maoyu ship Slava` | 查询单船数据 |
| `kkm me ships [筛选范围] [战斗类型] [!0] [!old]` | `kkm me ships 9 10`<br>`kkm me ships 战列 三轮车`<br>`kkm me ships 10 !0 !old`<br>`kkm me ships 10 dd usa`<br>`kkm asia Maoyu ships 10 单野` | 查询指定范围内船只的数据<br>`[筛选范围]`: 可以包括船只等级，类型和国家，详细参数可以查看附录<br>`[战斗类型]`: `单野`,`双排`,`三排`<br>`[!0]`: 不显示0场船只<br>`[!old]`:  不显示old船只 |
| `kkm me [pvp/rank] recent [日期]/[时间范围]` | `kkm me recent 7`<br>`kkm me rank recent 30`<br>`kkm me recent 20240501-20240502`<br>`kkm asia Maoyu recent 14` | 查询账号指定时间范围内随机或排位数据<br>`[pvp/rank]`: `pvp`(default),`rank`<br>`[日期]`: `1`(default)-400<br>`[时间范围]`: 时间格式: YYYYMMDD-YYYYMMDD |
| `kkm me ship <船名> recent [日期]/[时间范围]` | `kkm me ship 大和 recent 7`<br>`kkm me ship 大和 recent 20240501-20240502`<br>`kkm asia Maoyu ship 大和 recent 14` | 查询账号指定船只指定时间范围内随机数据<br>`[日期]`: `1`(default)-400<br>`[时间范围]`: 时间格式: YYYYMMDD-YYYYMMDD |
| `kkm me recents` | `kkm me recents`<br>`kkm asia Maoyu recents` | 查询过去24小时单场战斗数据 |
| `kkm me clan` | `kkm me clan`<br>`kkm asia TIF-K clan` | 查询工会信息 |
| `kkm me clan <season>` | `kkm me clan s24`<br>`kkm asia TIF-K clan s22` | 查询工会的指定赛季数据 |
| `kkm me clan history` | `kkm me clan history`<br>`kkm asia TIF-K clan history` | 查询工会参加过的赛季数据 |
| `kkm <服务器> ship rank <ShipName>` | `kkm asia ship rank 大和` | 查询船只在wows number上的排名榜(前50名)  |
| `kkm me ship rank <船名>` | `kkm me ship rank 大和`<br>`kkm asia Maoyu ship rank Vermont` | 查询自己船只数据在wows number上的排名 |
| `kkm online` | `kkm online` | 查询服务器在线人数 |
| `kkm search [筛选范围]` | `kkm search 10 bb` | 查询指定范围内的船只信息(名称，等级) |
| `kkm <服务器> stats [筛选范围]` | `kkm asia stats x cv` | 查询指定服务器指定范围内的船只服务器数据 |

## 附录

### 筛选范围

船只等级: 
- 1-11 / I-XI

船只类型: 
- 航母 (CV) / 战列 (BB) / 巡洋 (CA) / 驱逐 (DD) / 潜艇 (SS)

船只国家: 
- 美国 / 日本 / 欧洲 / 俄国 / 英国 / 泛亚 / 苏联 / 意大利 / 荷兰 / 泛美 / 英联邦 / 西班牙

---
