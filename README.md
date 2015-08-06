#plan

優先度順

- [ ]パッケージ購入
- [ ]CD焼く
- [ ]パッケージ詰め
- [ ]コード
- [ ]演出指定
- [x]シナリオ（ヒイラギ）
- [x]シナリオ（タチバナユウキ）
- [ ]背景
- [ ]イベント絵
- [ ]音楽

時間あれば
```
- [ ]立ち絵
- [ ]シナリオ（ハヤブサ）
- [ ]シナリオ（のっぺ）
- [ ]効果音
```

##パッケージ購入
- [ ] CD-ROM
- [ ] CDケース
- [ ] CD入れるビニール
- [ ] CDにいれる表紙の紙

##CD焼く
- [ ]ゲームデータをCDに書き込む

##パッケージ詰め
- [ ]CDをケースに詰め、表紙をいれてビニールで包む

##コード
- [ ]Artemisのコード

##演出指定（詳細後述）
- [ ]背景表示箇所にマーク
- [ ]音楽再生・停止位置にマーク

##背景
- [ ]背景写真を集める（ダウンロードorカメラ）
- [ ]背景写真にエフェクトをかける

##イベント絵（詳細後述）
- [ ]シナリオ中の重要な場面の絵

##音楽
- [x]音楽を集める

###演出指定に関して

ファイル名は

背景・イベント絵を「bg_xx.png」とする
音楽は「bgm_xx.mp3」とする。

xx部分は数字とする。`例：bgm_001.mp3`

数字は適当でいいが、追加した順にしてくれると分かりやすい。

背景・イベント絵を表示させる部分は
`[bg file="bg_xx.png"]`
と記入

音楽は`[bgm file="bgm_xx.mp3"]`と記入。

以下は例
```
ここは…目を開けると遊園地だった
[bg file="bg_001.png"]
そしてかすかに音楽が聞こえる
[bgm file="bgm_001.mp3"]
```

これらをシナリオに直接書く。

###イベント絵について

サイズは640x1136（横長）

上下は切り取る可能性有り
