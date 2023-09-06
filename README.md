# 境界データで逆ジオコーディングする

緯度と経度から市区町村名などを取得する（逆ジオコーディング）ためのリポジトリーです。
都道府県や市区町村、それよりも細かい地区情報が盛り込まれた境界データがあった場合に、それらの境界のどの場所に調べたい緯度・経度が含まれるかを判定します。
APIやGeoPandasなどでも同様の機能を提供していますが、回数制限やネットワーク速度に依存せずに、処理を行うことができます。

