# ssrenamer

スクリーンショットを自動でリネームするWindows向けソフトウェア。

リネーム先は撮影時に最前面に開いているアプリケーション名を使う。

インストールしなくても使用可能（WebView2が必要、デフォルトでインストール済みの可能性大）。移動先フォルダ名などを保存するコンフィグファイルは、`C:\Users\<USERNAME>\AppData\Roaming\com.ikappio.ssrenamer`に格納される。


ダウンロードは、[Releases](https://github.com/ikapper/ssrenamer/releases)ページから。


最近のWindowsはデフォルトでインストール済みなのでほぼ不要だが、必要であれば、WebView2のダウンロード・インストールは、[microsoft公式ページ](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)から。


## 更新履歴

* v0.1.0: 公開
* v0.1.1: コンテキストメニューを非表示にした。
* v0.1.2: 表記ミスを修正した。
* v0.1.3: 内部動作を改修した。
* v0.1.4: オートスタートのとき、ウィンドウを表示せずにシステムトレイにアイコンを設定するようにした。