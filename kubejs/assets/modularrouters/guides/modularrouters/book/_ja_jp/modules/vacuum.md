---
navigation:
  title: "吸引モジュール"
  icon: "modularrouters:vacuum_module"
  parent: modularrouters:modules.md
item_ids:
  - modularrouters:vacuum_module
---

# 吸引モジュール

このモジュールはルーターの周囲の13x13x13立方体領域(つまり、各方向に最大6ブロック)内でドロップされたアイテムをスキャンし、可能であればルーターのバッファに吸収します。

範囲は[範囲拡大オーグメント](../augments/range_up.md)を使用して最大25x25x25(各方向に12ブロック)まで拡大するか、[範囲縮小オーグメント](../augments/range_down.md)を使用して3x3x3まで縮小できます。

モジュールの[設定方向](../intro/modules.md#direction)が**「全て」**(デフォルト)の場合、スキャンされる領域はルーターを中心に配置されます。

モジュールに実際の方向が設定されている場合はその方向に領域が6ブロック分ずらされ、インストールされている範囲拡大オーグメントごとに1ブロックが加算され、インストールされている範囲縮小オーグメントごとに1ブロックが減算されます。

たとえば方向が**「上」**の場合、モジュールはルーターの真上の領域のみをスキャンします。



<Recipe id="modularrouters:vacuum_module" />

