# plugin-command-numbers
プラグインコマンド番号リスト。デバッグログの解析に活用することができます。

About
---
v14フォーマットの[デバッグログ](http://doc.4d.com/4Dv15R2/4D/15-R2/SET-DATABASE-PARAMETER.301-2544251.ja.html)では，プラグインコマンドの呼び出しが``3;1``のように出力されます。前半の値は[PLUGIN LIST](http://doc.4d.com/4Dv15R2/4D/15-R2/PLUGIN-LIST.301-2544266.ja.html)で列挙される順番に``2``を足したもの，後半の値はプラグインコマンド番号のようです。v14フォーマットのデバッグログを解析するには，

1. PLUGIN LISTより返されるプラグインの名前と順番
1. プラグインコマンドの番号

を知る必要があります。

* [Tech Tip: Enhanced Debug Log recording in v14](http://kb.4d.com/assetid=77076)
* [Tech Tip: New v14 formatting of Debug Log](http://kb.4d.com/assetid=77371)
* [Tech Note: 4D Log Analyzer v1.0 Preview](http://kb.4d.com/assetid=77198) 

Plugins
---

[4D Internet Commands](https://github.com/4D-JP/plugin-command-numbers/blob/master/4d-internet-commands.md)

[4D Pack](https://github.com/4D-JP/plugin-command-numbers/blob/master/4d-pack.md)

[4D ODBC Pro](https://github.com/4D-JP/plugin-command-numbers/blob/master/4d-odbc-pro.md)

[4D for OCI](https://github.com/4D-JP/plugin-command-numbers/blob/master/4d-for-oci.md)

[4D Write](https://github.com/4D-JP/plugin-command-numbers/blob/master/4d-write.md)

[4D View](https://github.com/4D-JP/plugin-command-numbers/blob/master/4d-view.md)
