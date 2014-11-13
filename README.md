imi-samples
===========

共通語彙基盤のボキャブラリによる RDF/Turtle のサンプル集

## About

[共通語彙基盤整備事業](http://goikiban.ipa.go.jp/) は、
「データの組み合わせや横断的利用を容易とする共通の語彙（ボキャブラリ）の基盤の構築に取り組む」
という主旨でスタートした、ボキャブラリを整備する事業です。
米国の [NIEM](https://www.niem.gov/) や欧州の [ISA](https://joinup.ec.europa.eu/) に相当します。

2014年11月現在、[コア語彙2.1(検証版)](http://goikiban.ipa.go.jp/node665) が公開されており、
特にこのバージョンから RDF スキーマが定義されています。

<http://imi.ipa.go.jp/ns/core/210/Core210_schema_rdf.zip>

このレポジトリでは、共通語彙基盤のボキャブラリを使用した
[RDF/Turtle](http://www.w3.org/TR/turtle/) のサンプルを提供します。

## License

![クリエイティブ・コモンズ 表示 4.0 国際 ライセンス](https://i.creativecommons.org/l/by/4.0/88x31.png)

本レポジトリのファイルは特別な記載がない限り、
[クリエイティブ・コモンズ 表示 4.0 国際 ライセンス](http://creativecommons.org/licenses/by/4.0/) 
の下に提供されています。

## Notice

本レポジトリのファイルの一部は、以下のコンテンツを加工して作成しています。

### [国土数値情報](http://nlftp.mlit.go.jp/ksj/index.html)
二次利用に関するライセンスは [国土情報利用約款](http://nlftp.mlit.go.jp/ksj/other/yakkan.html) に定められています。
本サンプルファイル群は以下のデータを利用しています。

* [国土数値情報 バス停留所データ](http://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-P11.html) を加工して作成
* [国土数値情報 バスバスルート](http://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N07.html) を加工して作成
* [国土数値情報　小学校区データ](http://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-A27.html) を加工して作成

### [政府統計の総合窓口(e-Stat)](http://www.e-stat.go.jp/)
二次利用に関するライセンスは [政府統計の総合窓口（e-Stat）利用規約](http://www.e-stat.go.jp/estat/html/spec.html) に定められています。
本サンプルファイル群は以下のデータを利用しています。

* [町丁・字等境界データ](http://e-stat.go.jp/SG2/eStatFlex/help/content/_72.html#002) を加工して作成

## Docs

データやボキャブラリに関する情報は  [Wiki](https://github.com/indigo-lab/imi-samples/wiki) に整理しています

## History

* 2014-11-11 [横浜市金沢区のサンプルデータ](https://github.com/indigo-lab/imi-samples/blob/master/14108kanazawa2014-11-11.ttl)を公開
    このデータセットを活用することで、金沢区「育なび」のデータのうち、緯度経度座標が関連付けられているアイテムに対して、小学校区や小地域などの境界との包含判定や近傍のバス停の探索などが行えます








