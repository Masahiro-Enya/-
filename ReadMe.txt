sampleApp       sampleApp.warを展開したもの
└WEB-INF
　└web.xml       WEBアプリケーションの動作を定義づけるファイル。
 └classes/com/excellence/ Javaのソースはここより下。
 　└api          各種API定義クラス
  └dqube/base   内部処理の定義クラス
  └ebase6       画面処理の定義クラス
└control        アプリケーション制御用xmlファイル格納ディレクトリ
　└colname.xml   DBカラム名と画面表示名の変換定義xmlファイル
 └control.xml   アプリケーションIDと処理クラス対応定義xmlファイル
 └init.xml      初期設定値定義xmlファイル
 └msg.xml       メッセージ設定xmlファイル
 └system.xml    アプリケーション動作設定xmlファイル

