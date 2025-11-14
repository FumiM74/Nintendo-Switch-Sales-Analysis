completed_deta フォルダ
　プラットフォーム別タイトルとハードウェアの販売量（積算、四半期別）、四半期ダミーを結合したcsvデータ。
　前処理済みのファイルで、これらを用いて、analize_switch_first, analize_switch_second ファイル内で分析を行った

data フォルダ
　ダウンロードしたファイル
　ダウンロードしたファイルを加工したファイル

titles_sales_data フォルダ
　normalized_titles_sales_data、switch、wii、wiiU は任天堂webサイトからダウンロードしたファイルから抽出・整理したデータ
　その他のファイルは、completed_detaフォルダ内の各ファイルを完成（前処理）するまでのファイル。

analize_switch_second ファイル
　今回の分析を行った.ipynbファイル
  analize_switch_firstは、前段階の試行錯誤した過程のファイル