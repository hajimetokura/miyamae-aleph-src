# miyamae-aleph-src — 一時ホスティング

Runway Aleph 2.0（OpenRouter video-to-video）にソース動画と参照画像を渡すための
**一時的な公開ホスト**。OpenRouter は data URI を拒否し https 公開URLのみ受け付けるため、
やむを得ず公開している。

- `input_5s_360.mp4` — 宮前小 詳細モデルのターンテーブル（1280×720 / 30fps / 5.000s / 150frames）
  1周360°を5秒で回りながら、60°〜300°で2階と屋根が 24m 持ち上がる分解表示
- `kf_000.png` / `kf_330.png` — 実写調スタイル参照（Nano Banana 生成、方位 0° / 330°）

いずれも PLATEAU 由来のマッシング＋簡易ディテールの検討用モデルであり、実施設計情報は含まない。

**生成が終わったらこのリポジトリは削除すること。**

出典: 目黒区立宮前小学校 / PLATEAU（国土交通省）CityGML より作成
