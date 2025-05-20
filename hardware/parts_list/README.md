# このディレクトリについて

- このディレクトリに部品表を入れてください。</br>
#プリント基板への部品実装のために必要な部品表と構成部品表が保存されます。</br>
#構成部品表は現状google sheetsで管理されているので、URLリンクをこのreadmeに記入するようにします。</br>

（google sheetsをexcelフォーマットでエクスポートしてもいいが、互換性や保守性が気になるところ）
#
複数の部品表が関連する場合、その関連性（親子関係）をこのREADMEに記述する様にしてください。
VScodeでAscii Tree Generatorを使うと便利です。

例：

## 構成


# [本体](URL)：説明
## [モジュール１](URL):説明
## [モジュール2](URL):説明
### [モジュール2](URL):説明
↑ cmd + shift + P, "Revert Tree String to Text"
↓ 選択ー右クリック "Format Text to Tree String"
.
└── [本体](URL)：説明
    ├── [モジュール１](URL):説明
    └── [モジュール2](URL):説明
        └── [モジュール2](URL):説明
