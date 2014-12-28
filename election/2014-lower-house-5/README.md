# 衆議院議員総選挙 東京都第5区 2014年

## データについて

- 出典: [開票結果 衆議院(小選挙区選出)議員選挙(東京都第5区)](http://www.city.setagaya.lg.jp/kurashi/107/788/790/d00136862.html)
- ライセンス: 世田谷区
- APIの更新方法: 手動
- APIの作成者・提案者: 河村 奨 @cognitom

## API

- 基本URI: `api/election/2014-lower-house-5/`

### 取得できる情報

- 候補者の得票(CSV): [candidate.csv](https://codeforsetagaya.github.io/api/election/2014-lower-house-5/candidate.csv)
- 候補者の得票(JSON): [candidate.json](https://codeforsetagaya.github.io/api/election/2014-lower-house-5/candidate.json)

### フィールド定義

| フィールド名 | 内容 |
| :---- | :---- |
| order | 得票順位 |
| elected | `true` (当選) or `false` (落選) |
| name | 候補者氏名 |
| party | 党派名 |
| votes | 得票数 |
