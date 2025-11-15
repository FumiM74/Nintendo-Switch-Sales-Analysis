Pythoin13.11.11利用
パッケージ管理はpip
任天堂（株）決算資料をデータを抽出して分析した際のPythonコード
wii,wiiU,switchのデータを準備したが、今回はswitchのみを説明性の高い回帰で分析
結果レポートは、00_reportフォルダにpdfで格納し、その他分析プロセスで作成したファイルや元データなどはそれぞれ個別フォルダで管理
gitignoreの対象は次のとおり
　ダウンロードした決算資料等の生ファイル
　任天堂（株）からデータをダウンロードにする際に書いたコード
　その他、試行錯誤に使ったファイル群
　分析のための環境


analize_switch_second ファイル
　今回の分析を行った.ipynbファイル
  analize_switch_firstは、前段階の試行錯誤した過程のファイル

00_report フォルダ
　今回の分析結果のレポートを格納したフォルダ

completed_deta フォルダ
　プラットフォーム別タイトルとハードウェアの販売量（積算、四半期別）、四半期ダミーを結合したcsvデータ。
　前処理済みのファイルで、これらを用いて、analize_switch_first, analize_switch_second ファイル内で分析を行った

data フォルダ
　ダウンロードしたファイル
　ダウンロードしたファイルを加工したファイル

titles_sales_data フォルダ
　normalized_titles_sales_data、switch、wii、wiiU は任天堂webサイトからダウンロードしたファイルから抽出・整理したデータ
　その他のファイルは、completed_detaフォルダ内の各ファイルを完成（前処理）するまでのファイル。