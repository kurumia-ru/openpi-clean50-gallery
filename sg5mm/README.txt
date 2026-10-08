Full FT + stategauss 5mm 報告用クリップ（2026-10-07 評価）

【数値】
- clean50 5mm 標準 eval: 2% (1/50)  — SUCCESS は ep20 のみ
- clean50 5mm 学習init: 0% (0/50)   — transport まで行く例あり、place 0
- clean100 5mm 標準: 0% (0/50)
- clean100 5mm 学習init: 0% (0/100) — place_near 3回あるが success 0

【動画】
1. clean50_5mm_std_SUCCESS_ep20.mp4 — 唯一の成功（標準 init）
2. clean50_5mm_std_transport_ep28.mp4 — 標準・transport まで失敗
3-4. clean50_5mm_traininit_transport_*.mp4 — 学習デモ init でも place 失敗
5-6. clean100_5mm_traininit_place_near_*.mp4 — データ倍でも place 近傍止まり
7. clean100_5mm_std_place_near_ep13.mp4

表: https://kurumia-ru.github.io/openpi-clean50-gallery/conditions/
生動画全部: p-ws-40:/share7/yui.muranaka/openpi_appearance/videos/
