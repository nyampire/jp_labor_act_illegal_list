# これは何？
日本 厚生労働省が毎月公開しているブラック企業の一覧を、TSVファイルにしたものです。

* [長時間労働削減に向けた取組](http://www.mhlw.go.jp/kinkyu/151106.html)
* [労働基準関係法令違反に係る公表事案](http://www.mhlw.go.jp/kinkyu/dl/170510-01.pdf)

# どうやって作っているの？
PDFからコピペしたテキストを、改行1つ1つ、丹精を込めて手作りで整形しています。

そのため、TSVには作業ミスが含まれる可能性があります。

# このTSVデータのライセンス
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.ja)

# 出典表記
[労働基準関係法令違反に係る公表事案](http://www.mhlw.go.jp/kinkyu/dl/170510-01.pdf)（厚生労働省） (http://www.mhlw.go.jp/kinkyu/dl/170510-01.pdf) を加工して作成

# リクエストなどなど
Issueまでお寄せください

# 利活用事例
* [ブラック・ブラック企業](http://structure-and-representation.com/works/blackCorporate/)
* [IT media: 厚労省の“ブラック企業リスト”をグラフで可視化　Webサイト「ブラック・ブラック企業」登場](http://www.itmedia.co.jp/news/articles/1708/07/news055.html)

# ファイルの解説とディレクトリ構造
* company_list_yyyymmdd_to_yyyymmdd.tsv: TOPに配置されているTSVファイルが、現在作業が完了している最新版です。yyyymmddは、オリジナルのPDF内に示されている、公開対象になっている期間を代入しています。

* 170510-01.pdf: 同じディレクトリ内に配置されているTSVのもととなった、オリジナルのPDFファイルです。

* 00n-yyyymmdd_to_yyyymmddディレクトリ: 過去分のTSVおよびオリジナルのPDFファイルを格納しています。


