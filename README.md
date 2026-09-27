# R.I.O.S. 数据包 data-v0.1.0

快照时刻：2026-09-28T00:10:20

这个仓只放**数据**，不放程序。程序在
[Rhodes-Island-Operation-Simulation-Service](https://github.com/Archer76/Rhodes-Island-Operation-Simulation-Service)。

## 里面是什么

| 文件 | 来源 | 说明 |
| --- | --- | --- |
| `enemydb.sqlite` | prts.wiki | 敌人图鉴／逐档数值／抗性／技能／天赋黑板 |
| `theresa/tile_info.json` | theresa.wiki | 地块字典（游戏本体的 gamedata 里**没有**这张表） |

**不含任何游戏本体数据**：不含关卡地图 JSON、不含 `enemy_database.json`、不含 `excel/`。
那部分版权属上海鹰角网络科技有限公司、且镜像站未授权，只能由使用者自行从源站取得。

## 许可

**CC BY-NC-SA 4.0**（署名-非商业性使用-相同方式共享）。详见 `DATA-LICENSE.md`。

## 怎么用

下载 Release 里的 zip，让程序自己装：

```
rios-tui.exe -install-datapack <zip>     （或）
python -m ak_tactic datapack --install <zip>
```

装了就不用再去抓 prts.wiki 与 theresa.wiki —— 但**游戏本体那部分照样要自己取**。
