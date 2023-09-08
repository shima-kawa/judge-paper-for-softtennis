# judge-paper-for-softtennis / ソフトテニス用ジャッジペーパー（採点票）
- ソフトテニスで使われるジャッジペーパー（ダブルス・シングルス採点票）をhtmlとcssで書く。
- ジャッジペーパーを私の浅いhtmlとcssの知識で再現する。  
- 参考にするジャッジペーパーは、(公財)日本ソフトテニス連盟が発行する「ダブルス・シングルス採点票」とする。  
- jsp等で利用できればいいなと。
- 初学者が浅い知識で、調べながら実装しているため、醜いコードになっています。
- 表示環境はGoogle Chromeを想定しています。

## 参考
- 鹿児島県ソフトテニス連盟
  - https://www.soft-tennis.com/kagoshima/gradingvote.pdf
- 日本ソフトテニス連盟
  - https://www.jsta.or.jp/wp-content/uploads/rule/gradingvote_2.pdf
- そろそろ真面目に、HTMLで帳票を描く話をしようか
  - https://qiita.com/cognitom/items/d39d5f19054c8c8fd592
- その他HTML,CSS解説サイト多数

## このリポジトリをご覧の方へ
- より良い実装等ありましたら、Issue等でご教示いただけますと飛んで喜びますのでよろしくお願いいたします。
- 問題等あればご連絡ください。

## 課題
- 全体的なclass名のつけ方
- `!important`の多様(4か所)
- ブラウザの使用上1px未満の枠線は表示されないため（参考:[Qiita記事](https://qiita.com/cognitom/items/d39d5f19054c8c8fd592)）、参考ジャッペに比べ全体的に枠線が太くなっている。
