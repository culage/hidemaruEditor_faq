#  秀丸エディタＱ＆Ａ集(第８版)

![Hidemaru Q and A](hide_by2.png)


##  はじめに
秀丸エディタＱ＆Ａ集の8版です。
対象は以下になります。

-   秀丸エディタVer.8以降
-   OSはWindows Vista以降

現状では、第7版の内容を、対象の環境に合わせ更新した程度です。
Ver.8までに追加された機能に関してはこれから。

配布ファイルは以下の２つありますが、内容は同じです。
通常は、chm(Microsoft HTML Help)形式 を使用してください。

HTML ハイパーテキスト形式は、ミラーリングや、引用などに使用してください。
(hmindex0.html がトップページになります。)

- chm(Microsoft HTML Help)形式
- HTML ハイパーテキスト形式

###  履歴
####  2016/11/13

-   変更
    -   全体を秀丸エディタVer.8を対象にした内容に変更
    -   @niftyのフォーラムはサービス終了のため、記述を削除
    -   リンク等で接続できない箇所は、リンクを解除
-   新規
    -   [第II部～知っていると便利な秀丸の機能　あいまい検索](2_fuzzy.html)
    -   [第II部～知っていると便利な秀丸の機能　変換モジュール](2_convert.html)
    -   [第III部～秀丸マクロのいろはにほへと　秀丸エディタウィンドウの管理(タブモード編)](3_tabmode.html)
    -   \[HME0097A\] [●ファイルを秀丸エディタで編集したのに、反映されていない](HME0097A.html)
    -   \[HMM0081A\] [●「DLLがロードされてないのにdllfunc関数が使われました」と表示される](HMM0081A.html)

#### 2016/11/19

-   [検索](./2_find.html)
    複数行にマッチする検索についての注意点追加。
-   [正規表現について](./4_regular.html)
    参考文献に「諸説 正規表現」を追加。
-   [HMM0081A](./HMM0081A.html)
    DLLのロード失敗に関して、64bit版での注意点を追加。
-   [Ｑ＆Ａ集その他の原稿の寄稿要領](./youryou.html)
    製作場所を変更。
-   [編集場所について](./hidpatio.html)
    製作場所を変更。
-   画像ファイル(png)を変更。全体のファイルサイズを多少減らす。

#### 2016/11/21

-   [ではでは](./byebye.html)を更新。
-   [HME0001A](./HME0001A.html)を変更。
-   [HME0006A](./HME0006A.html)コミュニテックスのリンク部分修正。

#### 2016/11/22

-   [HME0053A](./HME0053A.html)を更新。画像を追加。

#### 2016/11/23

-   [HME0001A](./HME0001A.html)を更新。「前へ」のリンク先修正
-   [第V部～マクロから呼び出すＤＬＬの作り方](./make_dll.html)を更新。一部画像を変更。

#### 2016/11/24

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を更新。Ver.8.66が公開されたので変更。
-   [HME0097A](./HME0097A.html)を更新。「次へ」のリンク先修正

#### 2016/11/26

-   [HME0047A](./HME0047A.html)を更新。説明修正。
-   [HME0093A](./HME0093A.html)を更新。画像および説明追加。
-   [HMM0003A](./HMM0003A.html)、[HMM0004A](./HMM0004A.html)を更新。マクロパスの設定方法を修正
-   [HME0051A](./HME0051A.html)を更新。画像を変更。バージョンアップで変更した箇所。
-   説明にある「秀丸」を「秀丸エディタ」へなるべく変更。
    (秀丸ファイラーClassicや、秀丸パブリッシャーに関する記述も追加する予定なので)
    
#### 2016/12/01

-   [秀丸エディタの各ＯＳ毎の最新版](./s_saisin.html)を更新。Ver.8.67が公開されたので変更。

#### 2016/12/04

-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](./3_macrov8.html)を更新。Ver.8.67が公開されたので変更。
-   [編集場所について](./hidpatio.html) 閉鎖の経緯を追加。

#### 2016/12/11

-   [「第II部～知っていると便利な秀丸の機能　置換」](2_replace.html)-
    [「変換モジュールを使った置換」](2_replace.html#SUPPLEMENTATION-3)で変換モジュールの多重化について追記。

#### 2016/12/23

-   8版リリース

-----------------------------------------------------------------------------------------------------------------


#### 2016/12/31

-   [第VI部～秀丸エディタ拡張モジュール](hmindex6.html) を追加。
-   [第VI部～秀丸エディタ拡張モジュール　秀丸パブリッシャーについて](6_publisher.html) を追加。

#### 2017/01/04

-   [第II部～知っていると便利な秀丸の機能　ファイルマネージャ枠](2_filemanager.html) を追加。

#### 2017/01/09

-   [第III部～秀丸マクロのいろはにほへと　マクロ内での「\\」や特殊文字の使い方](3_yenmk.html) を修正。
    chm作成用makeファイル修正。
    
    元のmarkdownファイルは、Shift_JISに含まれない文字を数値文字参照で記述していたが、
    html変換時に文字に変換されていたため、chm作成用にShift_JIS変換するときに削除されてしまっていた。
    (html変換時に、数値文字参照のままだと思ってた。)
    
-   [第VI部～秀丸エディタ拡張モジュール　秀丸パブリッシャーについて](6_publisher.html) を修正。
    画像ファイルを修正。BOXの制限を追加。

#### 2017/01/12

-   [第II部～知っていると便利な秀丸の機能　ファイルマネージャ枠](2_filemanager.html) を修正。

#### 2017/02/17

-   [第II部～知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を追加。

#### 2017/02/18

-   [第III部～秀丸マクロのいろはにほへと　マクロ内での「\\」や特殊文字の使い方](3_yenmk.html) を修正。
    Ver.8.66以降から使える、「Raw文字列リテラル」や、「逐語的リテラル文字列」について追記

#### 2017/02/26

-   [第II部～知っていると便利な秀丸の機能　アウトプット枠](2_output.html) を追加。

#### 2017/03/05

-   [HME0031A](./HME0031A.html)を更新。説明修正、画像変更。
-   [HME0058A](./HME0058A.html)を更新。説明修正、画像変更。

#### 2017/03/06

-   [HME0058A](./HME0058A.html)を更新。画像変更。

#### 2017/03/07

-   [HME0091A](./HME0091A.html)を更新。誤記修正。

#### 2017/03/12

-   [第III部～秀丸マクロのいろはにほへと　秀丸エディタウィンドウの管理(タブモード編)](3_tabmode.html)を更新。H1～4のID属性修正。

#### 2017/04/02

-   [第III部～秀丸マクロのいろはにほへと　自動起動マクロ](3_autostartmacro.html)を追加。

#### 2017/04/03

-   [第II部～知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を修正。誤記修正。
-   [\[HME0060A\] ●カーソル行を下線で強調表示したい？](HME0060A.html) を修正。
-   [\[HME0079A\] ●.hilight に \\t や \\n は使えるか？](HME0079A.html) を修正。

#### 2017/04/10

-   [第II部～知っていると便利な秀丸の機能　文字数の計算](2_wordcount.html) を追加。

#### 2017/04/16

-   [第VI部～秀丸エディタ拡張モジュール　秀丸パブリッシャーについて](6_publisher.html) を変更。
-   [第II部～知っていると便利な秀丸の機能　grep/タグジャンプ](2_grep.html)を変更
-   [第V部～マクロから呼び出すＤＬＬの作り方](make_dll.html)を変更。リンクを修正。
-   [\[HME0097A\]●ファイルを秀丸エディタで編集したのに、反映されていない](HME0097A.html)を修正。

#### 2017/04/17
-   [\[HMM0081A\]●「DLLがロードされてないのにdllfunc関数が使われました」と表示される](./HMM0081A.html)を変更。
    DLLを実行するためのファイルが足りない場合を追加。

#### 2017/04/19
-   [第Ⅰ部～秀丸エディタＱ＆Ａ集　Ｑ＆Ａ集の表記について](s_hyouki.html)を変更。
-   [第V部～マクロから呼び出すＤＬＬの作り方](make_dll.html)を変更。リンクを追加。
-   [\[HME0035A\]●縦書きや段組みなど、きめ細かな設定で印刷したい](HME0035A.html)を変更。

#### 2017/04/20

-   [第II部～知っていると便利な秀丸の機能　文字数の計算](2_wordcount.html) を変更。

#### 2017/04/25

-   [秀丸エディタの各ＯＳ毎の最新版](s_saisin.html) を変更。
-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](3_macrov8.html)を変更。

#### 2017/04/29

-   [\[HME0078B\]●設定を他のパソコンに移行したい](HME0078B.html)を修正。

#### 2017/04/30

-   [\[HME0078A\]●各種設定を移行するためファイルに保存したい](HME0078A.html)を修正。

#### 2017/05/03

-   [第VI部～秀丸エディタ拡張モジュール　秀丸パブリッシャーについて](6_publisher.html) を変更。テンプレートの保存場所の確認方法追加。
-   [\[HME0078A\]●各種設定を移行するためファイルに保存したい](HME0078A.html)を修正。秀丸パブリッシャーについて追加。
-   [第IV部～テキスト編集を極める！！　正規表現について](./4_regular.html)を変更。後方一致指定(肯定先読み)を使った、条件の論理積を追加。

#### 2017/05/06

-   [第II部～知っていると便利な秀丸の機能　複数選択](2_multiselect.html) を追加。

#### 2017/05/07

-   [第III部～秀丸マクロのいろはにほへと　マクロ登録数の制限突破大作戦](3_moremacro.html) を変更。キーの表記を修正。

#### 2017/05/17

-   [第II部～知っていると便利な秀丸の機能　カラーマーカー](2_colormarker.html) を追加。

#### 2017/05/19

-   [\[HMM0014A\]●「\¥」の使い方](HMM0014A.html)を修正。Raw文字列リテラル/逐語的リテラル文字列へのリンクを追加。
-   [\[HMM0060A\]●「キーワード」とは？](HMM0060A.html)を修正。ヘルプサイトへのリンクを追加。
-   [第II部～知っていると便利な秀丸の機能　カラーマーカー](2_colormarker.html) を修正。

#### 2017/05/21

-   [第II部～知っていると便利な秀丸の機能　あいまい検索](2_fuzzy.html)を修正。

#### 2017/05/23

-   [第II部～知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を修正。折りたたみと、部分編集の説明と画像を追加。

#### 2017/05/28

-   内容に変更なし。html5の構文チェックの内容を反映。

#### 2017/05/30

-   [秀丸エディタＱ＆Ａ集～はじめに　このヘルプの内容](s_naiyou.html) を変更。
-   [第VI部～秀丸エディタ拡張モジュール　秀丸パブリッシャーについて](6_publisher.html) を変更。

#### 2017/06/02

-   [\[HME0074A\]●特定のファイルを開くと文字化けする](HME0074A.html)を修正。イメージ部分変更。
-   [\[HMM0069A\]●マクロ処理中にダイアログボックスを出す方法](HMM0069A.html)を修正。

#### 2017/06/06

-   [第III部～秀丸マクロのいろはにほへと　マクロを実行してみよう](3_macro.html)を修正。【１】導入前の準備を修正。
-   [\[HMM0003A\]●マクロファイルの置き場所](HMM0003A.html)を修正。
-   [\[HMM0004A\]●マクロファイルの管理](HMM0004A.html)を修正。
-   [\[HMM0005A\]●マクロファイル用のフォルダは必須か？](HMM0005A.html)を修正。

#### 2017/06/12

-   [第II部～知っていると便利な秀丸の機能　文字数の計算](2_wordcount.html) を変更。

#### 2017/06/17

-   [\[HME0018B\]●瞬間起動機能がメモリやシステムリソースを圧迫する](HME0018B.html)を修正。
-   [\[HME0026A\]●スタートアップフォルダが見つからない](HME0026A.html)を修正。
-   [\[HME0027A\]●起動時に秀丸が現れて邪魔だ](HME0027A.html)を修正。
-   [\[HME0040A\]●外部ヘルプファイルの起動方法](HME0040A.html)を修正。
-   [\[HME0042A\]●拡張子が「KEY」のファイルは何？](HME0042A.html)を修正。
-   [\[HME0047A\]●外部ヘルプファイルの起動方法](HME0047A.html)を修正。
-   [\[HME0048A\]●「ワード」や「一太郎」等のファイルを開きたい](HME0048A.html)を修正。
-   [\[HME0051A\]●漢字コードの使い分け](HME0051A.html)を修正。
-   [\[HME0065A\]●改行だけの行を削除したい](HME0065A.html)を修正。
-   [\[HMM0014A\]●「\¥」の使い方](HMM0014A.html)を修正。

#### 2017/06/24

-   8.1版リリース

-----------------------------------------------------------------------------------------------------------------

#### 2017/07/09

-   [第II部～知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を追加。

#### 2017/07/10

-   [第II部～知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。

#### 2017/07/14

-   [第II部～知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。
-   markdown -> html 変換makefileを変更。
    chm作成用にUTF-8 -> Shift_JIS変換するときに、半角カナが全角カナに変換されていたのを修正。
    
    -   [第II部～知っていると便利な秀丸の機能　あいまい検索](2_fuzzy.html)
    -   [第II部～知っていると便利な秀丸の機能　変換モジュール](2_convert.html)

#### 2017/07/21

-   [第II部～知っていると便利な秀丸の機能　検索](2_find.html)を修正。
-   [第II部～知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。
-   [秀丸エディタVer.8.00 マクロ関連の変更履歴](3_macrov8.html)を修正。V.8.73を追加。

#### 2017/07/31

-   [第II部～知っていると便利な秀丸の機能　検索](2_find.html)を修正。
-   [第II部～知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。

#### 2017/08/11

-   [秀丸スペルチェックアドインについて](6_spellcheck.html) を追加。

#### 2017/08/12

-   [秀丸スペルチェックアドインについて](6_spellcheck.html) を修正。
-   [\[HME0006A\]●質問したい時にはどうするの？](HME0006A.html)コミュニテックスのリンク部分修正。

#### 2017/08/14

-   [\[HMM0032A\]●「検索での表示」の設定による動作の違い](HMM0032A.html)を修正。タイトル変更および、説明を追加。
-   [\[HMM0041A\]●文字列型変数の扱う文字列の限界](HMM0041A.html)を修正。
-   [\[HMM0044A\]●文字列型変数中の半角小文字を大文字に](HMM0044A.html)を修正。
-   [\[HMM0045A\]●文字列型変数中の半角大文字を小文字に](HMM0045A.html)を修正。

#### 2017/08/20

-   [第II部～知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を修正。
-   [第III部～秀丸マクロのいろはにほへと　COMオブジェクト操作関連](3_com_object.html) を追加。

#### 2017/08/21

-   [第II部～知っていると便利な秀丸の機能　アウトライン解析の枠](2_outline.html) を修正。
-   [第II部～知っていると便利な秀丸の機能　単語補完](2_wordcomplete.html) を修正。誤記修正。
-   [第IV部～テキスト編集を極める！！　正規表現について](4_regular.html)を修正。誤記修正。

#### 2017/08/22

-   [第IV部～テキスト編集を極める！！　タグ付き正規表現とは?](4_tagreg.html)を修正。

#### 2017/08/26

-   [第III部～秀丸マクロのいろはにほへと　秀丸マクロで文字列を編集する](3_string.html)を修正。

#### 2017/08/29

-   [第II部～知っていると便利な秀丸の機能　検索](2_find.html)を修正。
-   [第II部～知っていると便利な秀丸の機能　置換](2_replace.html)を修正。

#### 2017/08/30

-   [秀丸スペルチェックアドインについて](6_spellcheck.html) を修正。
