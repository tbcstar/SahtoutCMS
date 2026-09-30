导入 Sahtout_site 数据库：网站数据库。
然后
从这里运行这些 SQL 文件。
例如：
-----acore_auth_sahtout_site.sql------
表示它在 acore_auth 数据库内。

重要：如果你有 spellcharges_1 = 0，请使用 #acore_world_spellcharge# 中的查询，它应该是 spellcharges_1 = -1，
这样当你从商店购买坐骑/宠物时，used=1，然后物品会被删除。