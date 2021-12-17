## はじめに

これは[ヒホ](https://twitter.com/hiho_karuta)が開発したテキスト音声合成ソフトウェア「VOICEVOX」の使い方を紹介するドキュメントです。

最初に、インストール（もしくは Zip ファイルを解凍）したディレクトリの中にある README.txt をご確認ください。

[使い方を軽めに紹介した動画](https://youtu.be/4yVpklclxwU)もあるので、よかったらご覧ください。

## 利用規約

ソフトウェア内の「ヘルプ」から、ソフトウェアの利用規約と、音声ライブラリの利用規約をご確認ください。

## 起動方法

初回起動時はAppleに登録されていないアプリケーションとして警告ダイアログが表示されます。
その際は以下の手順で起動してください。

1. MacのFinderで、「VOICEVOX」を検索します。Launchpadは使用しないでください。Launchpadではショートカットメニューにアクセスできません。
2. Controlキーを押しながらアプリケーションアイコンをクリックして、ショートカットメニューから「開く」を選択します。
3. 「開く」をクリックします。

> アプリケーションはセキュリティ設定の例外として保存され、今後は登録済みのアプリケーションと同様に、ダブルクリックすることで開くことができるようになります。

**注記**: また、「セキュリティとプライバシー」環境設定の「一般」パネルで「このまま開く」ボタンをクリックすることで、ブロックされたアプリケーションの例外を許可することもできます。このボタンは、アプリケーションを開こうとした後、約1時間の間使用できます。
Macでこれらの環境設定を変更するには、アップルメニュー  ＞「システム環境設定」と選択して「セキュリティとプライバシー」 をクリックし、「一般」をクリックします。

## 音声合成エンジンの起動

最初に音声合成エンジンが起動します。Mac版ではGPU モードはご利用できません。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image4.png" style="max-height: 8rem" />

## 音声の生成

キャラクターアイコンの右にある空白をクリックしてテキストを入力してみてください。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image19.png" style="max-height: 12rem" />

エンターボタンを押して文章を確定すると、画面の下の方に読みとアクセントが表示されます。（１回目は反映まで数秒ほど時間がかかることがあります。）

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image6.png" style="max-height: 14rem" />

再生ボタンを押すと音声が生成され、音声が再生されます。

## 文章の追加・削除

右下の＋ボタンを押すとテキスト欄が増え、複数の文章を並べることができます。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image10.png" style="max-height: 14rem" />

## キャラクターの変更

テキスト入力欄の左にあるアイコンをクリックすると、テキストを読み上げてくれるキャラクターを変更することができます。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image7.png" style="max-height: 12rem" />

## 単語の接続変更

意図しない箇所で単語が分離していた場合や、意図しない形で結合してしまっている場合は、アクセント項目で文字の間をクリックすることで修正できます。

例えば「ディープラーニング」がこのように分かれてしまった場合は、

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image9.png" style="max-height: 16rem" />

２つの隙間をクリックすると

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image3.png" style="max-height: 8rem" />

このように１語にまとめることができます

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image8.png" style="max-height: 7rem" />

逆に切り離したい場合は、文字の間をクリックして切り離すことができます。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image13.png" style="max-height: 8rem" />

## アクセントの変更

音声の抑揚が意図しないものだった場合に、抑揚を変える方法が２つあります。まずはアクセント箇所を変えてみることをおすすめします。

アクセント箇所を変えるには、読みの上にあるバーを左右に動かします。
例えば「ディープラーニング」を「↑ ディープラ ↓ アニング」と読んでほしい場合は、「ラ」の位置まで丸をスライドします。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image8.png" style="max-height: 8rem" /> → <img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image1.png" style="max-height: 8rem" />

## イントネーションの変更

アクセントを変更してもうまく行かなかったときや、抑揚をより拘りたいときに、文字ごとの音の高さ（イントネーション）を直接変更することができます。

「イントネーション」をクリックして現れる縦線のバーを上下させることで抑揚を表現できます。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image2.png" style="max-height: 8rem" />

イントネーション調整スペースを縦に広くすることで、より細かく抑揚を調整することもできます。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image18.png" style="max-height: 14rem" />

マウスホイールで調整することもできます。Ctrl キーを押しながらマウスホイールを使うと更に細かく調整できます。

また、「キ」や「ツ」や「ス」などが無声化されている場合、バーが灰色になっています。イントネーション欄のテキストをクリックすることで無声化を解くことができます。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image5.png" style="max-height: 10rem" /> → <img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image12.png" style="max-height: 10rem" />

無声化できるものはイ行とウ行だけです。

## 読みの修正

読みが思っているものと違う場合は、アクセント欄で読みをクリックすることで後から修正することもできます。テキスト欄と同様に、ひらがなや句読点、漢字も入力できます。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image20.png" style="max-height: 12rem" />

## スタイルの変更

キャラクターによっては複数のスタイル（喋り方）を変えることができます。キャラクターの変更と同様に、テキスト欄左のアイコンから選択できます。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image21.png" style="max-height: 12rem" />

キャラクターを選択したときに適用されるスタイルは、設定の「デフォルトスタイル」で変更できます。

## 音の長さの変更

文字ごとに、音の長さを変えることが可能です。語尾を少し伸ばしたい、無音の長さを調整したいときなどに便利です。

「長さ」をクリックして現れる縦線のバーを上げるとその音を長く、下げると短くできます。
右のバーが母音、左のバーが子音に対応しています。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image22.png" style="max-height: 12rem" />

## 音声ファイル・テキストファイルの書き出し

書き出しボタンを押すと、全テキスト欄の音声が WAV ファイルとして書き出されます。
ファイル保存時、ファイル名は[何行目]\_[キャラ名]\_[テキスト冒頭].wav として保存されます。テキストファイルも同じファイル名.txt で保存されます。

## テキストファイルの読み込み

読み込みボタンを押すとテキストファイルを読み込めます。テキストは改行または半角コンマ（,）で区切ることで分割できます。また、キャラクター名だけで区切ることで、そのキャラクターとして読み込むことができます。

例えばこのようなテキストを読み込むと、

```txt
四国めたん,おはようございます,こんにちは
ずんだもん,こんばんは
四国めたん,さようなら
```

このように読み込まれます。

<img src="https://raw.githubusercontent.com/Hiroshiba/voicevox/0.9.1/public/res/image17.png" style="max-height: 12rem" />

## プロジェクトファイルの保存・読み込み

入力したテキストやキャラクター、アクセント修正やイントネーションの調整結果は、プロジェクトファイルとして保存し、ソフトウェアを起動し直した後で読み込むことができます。プロジェクトファイルの拡張子は`.vvproj`です。

## 設定画面

右上の歯車マークから設定画面を表示できます。

### エンジン

エンジンの起動モードの起動モードを変更できます。
GPU モードを利用するには、3GB 以上のメモリがある NVIDIA 製 GPU が必要です。

### 保存

#### 文字コード

読み込み・書き込み用の文字コードを選択できます。

#### 書き出し先を固定

音声ファイルを書き出すディレクトリを固定し、毎回ディレクトリを選択しなくても同じディレクトリに書き出し続けるようにします。

#### 上書き防止

同じファイル名のファイルがあった場合に連番として保存します。

## その他

右上のピンボタンでウィンドウを最前面に固定できます。

## ヘルプ

利用規約などを確認することができます。
