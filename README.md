家族用のAndroidアプリAutomateによるテザリング制御等の用途。
テザる等が未対応なので、Automateの試行錯誤の一夜マクロです。

当方の力量不足でMainは未完成で、動いたら良いな程度なので期待はしないで下さい。
(RaspberryPiを放置しているので、そちらから片付けないと忙しいので後回し)

ここのテザリングとテザリング確認用の2つは当方環境で動作確認済みで、

Flow beginningのINSTALL HOME SCREEN SHORTCUTからショートカットを作成し、

SMSテザリングとSMSテザリング確認用の2つのショートカットを一緒に実行して利用することで、
SMSからAndroidのWi-FiテザリングがRoot無しで操作可能です。
Privilegesは二つのマクロのテキストメッセージ(SMS)の受信とtethering workaroundに、
access local network, internet and nearbydevicesとSMSメッセージの送信計4つです。

当方の利用環境ではこのマクロはSettingのExtension(Android 5+)以外では動作しませんでした。

キャリア純正のNoRoot環境で動くのがとても魅力で下記の作者様に感謝申し上げます。

Automate
https://play.google.com/store/apps/details?id=com.llamalab.automate
Support & Feedback
Reddit: https://www.reddit.com/r/AutomateUser/
Forum: https://groups.google.com/g/automate-user
E-mail: info@llamalab.com
