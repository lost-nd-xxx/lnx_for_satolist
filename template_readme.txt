書いた人 → lost_nd_xxx
連絡先 → http://lnx.flop.jp/

----

￥０の頭つつきでメニュー、当たり判定のない箇所でランダムトーク。
￥１の当たり判定のない箇所でその他の機能。
dic_lfs0_の辞書は重要度が高い（独断）です。

----

外部の文字列（ユーザの文字入力、他ゴースト名、他ゴーストの切り替え時の発言、シェル名、バルーン名）から禁句（引数区切り、半角￥記号、バイト値１と２）を問答無用で削除しています。
dic_lfs0_kill_taboo.txtをご一読ください。

----

このテンプレートは以下のページをすごく参考にして作成されました。

里々wiki
http://soliton.sub.jp/satori/

ukadoc
http://ssp.shillest.net/ukadoc/manual/

----

*20150602
-公開開始
*20150604
-話題分野設定とOnTalkのバグを修正
-喋り頻度設定のSSP以外への対応強化
-ユーザによる文字入力への対策の変数名被りを修正
-変数初期化が初期化されていなかったのを修正
-OnTalkでの要らない変数消し忘れを修正
*20150616
-バグ修正
-dic00_system.txtを削除
-ssu.dllの削除とそれに伴う記述の整理
*20150703
-vncall関数を導入（里々のバージョンがMc158-1以上でなければなりません）
-禁句対応の関数名が変化（KillTaboo）
--禁句対応周りの名前が変化しましたので、既にご利用中だった方はご確認ください
-「初期化したい変数リスト」を「削除したい変数リスト」に変更
-「消して閉じる」で\1のバルーンの中身を消していなかったのを修正
-「入力箱を閉じる」でteachboxを閉じていなかったのを修正
-「喋り間隔入力」のベースウェア対応分けの不具合を修正
-「バルーンメニュー」に関する修正
-その他バグ修正
*20170610
-OnUpdateCompleteでの記述間違いを修正
--×「起動前の一括処理」
--○「起動前の処理」
*20170908
-dic_lfs0_common.txtにOnChoiceSelect、OnChoiceSelectExを新設
-dic_lfs0_common.txtにバグ報告などのweb拍手（OnChoiceSelect、OnChoiceSelectEx、OnAnchorSelect、OnAnchorSelectEx）
-dic_lfs0_talk.txtでOnTalkにウェイトを自力で入れる処理を廃止
-dic_lfs1_lab.txtに時刻合わせを追加
-dic_lfs1_lab.txtにウェブ拍手を追加
*20170917
-文字コードをUTF-8へ変更してみた版
--上記に伴いdescript.txtのcharsetをUTF-8へ