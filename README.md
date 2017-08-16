# これは何？
日本 厚生労働省が毎月公開しているブラック企業の一覧を、TSVファイルにしたものです。

* [長時間労働削減に向けた取組](http://www.mhlw.go.jp/kinkyu/151106.html)
* [労働基準関係法令違反に係る公表事案](http://www.mhlw.go.jp/kinkyu/dl/170510-01.pdf)

# このTSVデータのライセンス
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.ja)

# ファイルの解説とディレクトリ構造
* company_list_yyyymmdd_to_yyyymmdd.tsv:
* TOPに配置されているTSVファイルが、現在作業が完了している最新版です。
* yyyymmddは、オリジナルのPDF内に示されている、公開対象になっている期間を代入しています。
* テキストはタブ区切りのTSVファイルになっています。違反法条のカラム内は複数の情報が含まれており、カンマで区切られています。

* 170510-01.pdf:
* オリジナルのPDFファイルです。同じディレクトリ内に配置されているTSVはこのファイルから作成されています。

* 00n-yyyymmdd_to_yyyymmddディレクトリ:
* 過去分のTSVおよびその時点のオリジナルとなったPDFファイルを格納しています。

# どうやって作っているの？
PDFからコピペしたテキストを、改行1つ1つ、丹精を込めて手作りで整形していま----した。

現在は @frogcat氏の作成したスクリプトにより、PDFから半自動化して情報を抜き出しています。Thank you!

## 作成手順
1. オリジナルのPDFをWord2016で開き、htmlで保存する
2. 保存したhtmlをgistにアップロード
3. frogcat氏の[変換用gist](https://gist.github.com/frogcat/73470779606cfe2046cefa468a7c85c5)スクリプトをForkし、index.html内に含まれる対象gistのURLを、適切なgist（のRAWのURL）に変更
4. bl.ocks.org経由で、変換用gistのアドレスを表示させる
5. できあがったCSVに含まれる改行などを適度に処理する

* [htmlに変換したファイルのgist例](https://bl.ocks.org/frogcat/raw/a7f18b4fb7375a18297d17abe63aa764/)
* [@frogcat氏の変換用gist](https://gist.github.com/frogcat/73470779606cfe2046cefa468a7c85c5)
* [変換後のbl.ocks.orgページ例](https://bl.ocks.org/frogcat/73470779606cfe2046cefa468a7c85c5)

# リクエストなどなど
Issueまでお寄せください

# 利活用事例
* [ブラック・ブラック企業](http://structure-and-representation.com/works/blackCorporate/)
* [IT media: 厚労省の“ブラック企業リスト”をグラフで可視化　Webサイト「ブラック・ブラック企業」登場](http://www.itmedia.co.jp/news/articles/1708/07/news055.html)

# 出典表記
[労働基準関係法令違反に係る公表事案](http://www.mhlw.go.jp/kinkyu/dl/170510-01.pdf)（厚生労働省） (http://www.mhlw.go.jp/kinkyu/dl/170510-01.pdf) を加工して作成
