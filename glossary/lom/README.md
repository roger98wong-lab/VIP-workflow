# 冒险大作战（lom）

对外品牌名固定 **Legend of Mushroom**。中文稿里的游戏名也写这个英文名，不写「冒险大作战」。

## 语言表（已入库）

路径：glossary/lom/lang/2026-09-24/

来源：US冒险大作战多语言0924（2026-09-24）。按语言分子文件夹，每种语言两份：

- Y 语言表-*.xlsx 主语言表，约 3 万行
- Y 语言表UI-*.xlsx UI 表

主表工作表名：out_language_{lang}（en/de/fr/ru/es/pt/tr/ar/it）

有效数据约从第 9 行起：

| 列 | 含义 |
|---|---|
| A | id |
| B | 该语言文本 |
| C | 中文 |
| D | 部分表有「简中语言表」备份；冲突以表内说明为准 |

查词：用中文对 C 列，取 B 列译文。不要凭印象改锁定译名。

往期 SOP（如何批量查询需要的术语）是把待查中文放一列，再 VLOOKUP 语言表。表内列顺序以当前 xlsx 为准。

## 往期文案

glossary/lom/past/vip-warmup.xlsx（原文件名是 csv，实际是 Excel）

每期一个 sheet，常见三行：

1. DC文案（全语种，可含富文本）
2. VK文案（去粗体斜体；近期常空；历史多为 en+ru）
3. VIP后台文案（简短、去粗体、去 emoji）


下面再跟术语对照行。风格规则见 `templates/style/lom.md`。

## 出稿时术语怎么用

先写中文成稿，再从成稿抽词。查词顺序：

1. 本目录语言表（道具名以此为准）
2. 本期 inbox/glossary/
3. glossary/master.csv 中 game=冒险大作战 的行
4. 都没有：先翻译并黄标，禁止自译成近义词
