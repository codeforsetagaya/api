# 世田谷区の選挙情報のAPI 2011年版

## データの出典

- [世田谷区長選挙　開票結果](http://www.city.setagaya.lg.jp/kurashi/107/788/790/d00033393.html)
- [世田谷区議会議員選挙　開票結果](http://www.city.setagaya.lg.jp/kurashi/107/788/790/d00033392.html)

## 元のライセンス

- 世田谷区

## データの更新方法

手動

## 作成者・提案者

- 河村 奨 @cognitom

## APIの使い方

- 区長候補者の得票(CSV): [api/election/2011/candidate-mayor.csv](https://codeforsetagaya.github.io/api/election/2011/candidate-mayor.csv])
- 区長候補者の得票(JSON): [api/election/2011/candidate-mayor.json](https://codeforsetagaya.github.io/api/election/2011/candidate-mayor.json])
- 議員候補者の得票(CSV): [api/election/2011/candidate-member.csv](https://codeforsetagaya.github.io/api/election/2011/candidate-member.csv])
- 議員候補者の得票(JSON): [api/election/2011/candidate-member.json](https://codeforsetagaya.github.io/api/election/2011/candidate-member.json])

### フィールド名

- order: 得票順位
- elected: `true` (当選) or `false` (落選)
- name: 候補者氏名
- party: 党派名
- votes: 得票数
