# 主宰世界（zzsj）

登记名必须写 **主宰世界**，目录名 `zzsj`。
对外品牌固定 **Legend of Element**。充值链接用 `https://payment.joynetgame.com/@loe?utm_pay=kf`。

## 语言表（已入库）

路径：`glossary/zzsj/lang/2026-09-30/y语言表.xlsx`

来源：主宰欧美语言表翻译对照（2026-09-30 同步）。主查工作表 `data`，约 5.6 万行。

有效数据约从第 4 行起：

| 列 | 含义 |
|---|---|
| A | ID |
| B | 中文（查找列） |
| C | key |
| D | 翻译（常与英语相同，不要当权威） |
| E | 英语 en |
| F | 西语 es |
| G | 葡语 pt |
| H | 德语 de |
| I | 法语 fr |
| J | 土语 tr |
| K | 俄语 ru |
| L | 海外中文（可能与 B 列不同，出稿仍以 B 列中文为准） |

查词：用成稿中文对 B 列，取 E–K 列译文。

**US主宰不需要出阿拉伯语、意大利语。** 只出 cn/en/de/fr/ru/es/pt/tr。不要生成 ar/it 文案，也不要为此标黄。

其他 sheet（Sheet1、带斜杠、Sheet2/3/5）不作主查，除非 B 列未命中再作人工备查。

## 往期文案（已入库）

`glossary/zzsj/past/past-events.xlsx`

每期通常两列成稿：长稿（偏 Discord）+ 短公告（偏 VIP）。未见独立 VK 行。
风格规则见 `templates/style/zzsj.md`。

## 出稿时术语怎么用

先写中文成稿，再从成稿抽词。查词顺序：

1. 本目录语言表 data 表（道具名以此为准）
2. 本期 inbox/glossary/
3. glossary/master.csv 中 game=主宰世界 的行
4. 都没有：先翻译并黄标，禁止自译成近义词，也禁止用 lom 的译名
