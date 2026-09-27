# 逐文件来源（数据包 data-v0.1.0，快照 2026-09-28T00:10:20）

| 包内文件 | 来源 | 抓取/建库时刻 | 处理 |
| --- | --- | --- | --- |
| `enemydb.sqlite` | prts.wiki | 2026-09-24 00:56:31 | 敌人图鉴/逐档数值/抗性/技能（分类:敌人） |
| `theresa/tile_info.json` | theresa.wiki | 2026-09-28T00:10:20 | 地块字典（游戏本体没有这张表） |

库内自述（`enemydb.sqlite` 的 `meta` 表）：

- `built_at` = 2026-09-24 00:56:31
- `db_version` = 3
- `enemy_source` = prts.wiki 分类:敌人
- `schema_note` = 只含战斗相关数据；见 ak_tactic/db/enemy_schema.py 顶部说明

抓取工具：R.I.O.S. 的 `ak_tactic` 取数层；源站以抓取时刻的页面为准。
