"Failed to connect to backoff(async(tcp://13.115.178.247:5044)): dial tcp 13.115.178.247:5044: connectex: No connection could be made because the target machine actively refused it."

backoff への接続に失敗しました (async(tcp://13.115.178.247:5044)): ダイヤル tcp 13.115.178.247 :5044: connectex: ターゲット マシンがアクティブに拒否したため、接続できませんでした。

ミスリードかもしれないけど、WMIってのが関係しているのかもしれない。

Windowsログの出力をするサービスで、ポートがランダムに変動するらしい。
https://www.manageengine.jp/products/OpManager/wmi-monitoring.html
https://www.secuavail.com/kb/tech-blog/tb-20190903_01/