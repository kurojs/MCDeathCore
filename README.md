# MCDeathCore

An advanced Java plugin for Minecraft that adds custom animations and sound effects that trigger when the player dies using a resource pack.

![MCDeathCore Demo](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmtmemdjNjQ3NjlyZmIxbzluYmpoaW1kMzl2ZnU1YW5qcW5mbjQ2eiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/u6OwFS94l8yJCtFVFy/giphy.gif)

## Features

🎨 **Custom Death Animations**: Configure Unicode frames to create unique animations.
🔊 **Sound Effects**: Add immersive audio triggered during the death animation.
⚙️ **Command Integration**: Run custom commands when a player dies.
📋 **Highly Configurable**: Tailor the plugin using the `config.yml` file, including animation speed, sound settings, and more.
🛠️ **Built for Minecraft Java Edition**: Compatible with the latest versions.

## Getting Started

### Installation
1. Download the latest release from the Releases section.
2. Place the `.jar` file in your server's `plugins` directory.
3. Restart the server to generate the default `config.yml`.

### Configuration
Edit the `config.yml` file to customize the plugin. Key settings include:

- **Animation speed** (`velocidad_animacion`)
- **Sound settings** (`sonido.activar`, `volumen`, `pitch`)
- **Commands to execute upon death** (`comandos`)

## Usage
The plugin activates automatically when installed. Players will experience custom death animations and sound effects upon dying.

## Preview
Example of a custom animation:

```yml
unicode_inicial: "\uE000"
numero_de_fotogramas: 92
```

# MCDeathCoreJava (日本語)

リソース パックの助けを借りて、プレイヤーの死亡時にカスタム アニメーションとユニークなサウンド効果を追加する Minecraft Java 用の高度なプラグイン。

## 特徴

🎨 **カスタムアニメーション**: Unicodeフレームを設定してユニークなアニメーションを作成できます。
🔊 **サウンドエフェクト**: 死亡アニメーション中に没入感のあるオーディオを追加します。
⚙️ **コマンド統合**: プレイヤーの死亡時にカスタムコマンドを実行します。
📋 **高いカスタマイズ性**: `config.yml`を使用してアニメーション速度やサウンド設定などを調整可能です。
🛠️ **Minecraft Java Edition向け**: 最新バージョンに対応しています。

## 開始方法

### インストール
1. リリースセクションから最新バージョンをダウンロードします。
2. `.jar`ファイルをサーバーの`plugins`ディレクトリに配置します。
3. サーバーを再起動してデフォルトの`config.yml`を生成します。

### 設定
`config.yml`ファイルを編集してプラグインをカスタマイズします。主な設定は以下の通りです：

- **アニメーション速度** (`velocidad_animacion`)
- **サウンド設定** (`sonido.activar`, `volumen`, `pitch`)
- **死亡時に実行するコマンド** (`comandos`)

## 使用方法
プラグインはインストールすると自動的に有効になります。プレイヤーは死亡時にカスタムアニメーションとサウンドエフェクトを体験できます。

## プレビュー
カスタムアニメーションの例：

```yml
unicode_inicial: "\uE000"
numero_de_fotogramas: 92
```

