## 変更点

- ByteTracker.update() に 渡す Tuple に client data(任意のオブジェクト)を追加
- STrack クラスに cdata_list メンバ変数を追加
  - cdata_list は、STrack を構成する detection 列に対応する client data のリスト
- これにより、ByteTracker.update() が非同期的に返却するトラッカーと detection ソースの紐づけが可能になる
