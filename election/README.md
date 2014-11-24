# 世田谷区の選挙情報のAPI

| 選挙のID | APIの詳細 |
| :---- | :---- |
| 2015-mayor | [世田谷区長選挙 2015年](2015-mayor/) |
| 2015-council | [世田谷区議会議員選挙 2015年](2015-council/) |
| 2014-lower-house-5 | [衆議院議員総選挙 東京都第5区 2014年](2014-lower-house-5/) |
| 2014-lower-house-6 | [衆議院議員総選挙 東京都第6区 2014年](2014-lower-house-6/) |
| 2011-mayor | [世田谷区長選挙 2011年](2011-mayor/) |
| 2011-council | [世田谷区議会議員選挙 2011年](2011-council/) |

## 共通API

- 基本URI: `api/election/<選挙のID>/`

### 取得できる情報

- 候補者の得票(CSV): candidate.csv
- 候補者の得票(JSON): candidate.json

### フィールド定義

| フィールド名 | 内容 |
| :---- | :---- |
| order | 得票順位 |
| elected | `true` (当選) or `false` (落選) |
| name | 候補者氏名 |
| party | 党派名 |
| votes | 得票数 |
