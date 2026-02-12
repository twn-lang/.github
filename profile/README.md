# twn-lang

twn-langは、Rustで実装された独自のスタックベース仮想マシンおよびアセンブラを中心としたエコシステムです。

## 主要プロジェクト

### 1. [twn](https://github.com/twn-lang/twn)

エコシステムのコアとなるスタックベース仮想マシンとアセンブラのセットです。

- **twnc**: 独自の命令セット (`.twn`) をバイトコード (`.twnd`) にコンパイルします。
- **twnvm**: 飽和演算やシステムコールを備えた256バイトメモリの仮想マシンです。
- **twn**: アセンブルから実行までを一括で行うドライバコマンドです。

### 2. [twn-zed](https://www.google.com/search?q=https://github.com/twn-lang/twn-zed)

[Zedエディタ](https://zed.dev)でtwn言語を快適に開発するための拡張機能です。

- `.twn` ファイルのシンタックスハイライトを提供します。
- Tree-sitterによる高速な構文解析を利用しています。

### 3. [tree-sitter-twn](https://github.com/twn-lang/tree-sitter-twn)

twn言語のためのTree-sitter文法定義です。

- エディタ拡張やコード解析ツールなどの基盤として機能します。

## ライセンス

本Organization下の各プロジェクトは、MITライセンスの下で公開されています。
