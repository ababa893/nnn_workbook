# 02 First time HTML (in Japanese)

既に身に着けている内容はスキップ．練習問題の答案は基本的に載せる．

## 学習メモ

### VS Codeで書くHTML

VSCodeでHTMLのテンプレートを入力する場合は，`html:5`を入力して`Tab`キーを押す．カーソル横に出現する候補の中から選んでも良い．

### HTMLのしくみ

HTML: **H**yper **T**ext **M**arkup **L**anguage

マークアップ言語: 機械が読めるように，内容に目印を付ける(mark up)ことで構造を表現する言語．<br>
(HTML, XML等)

マークアップ言語で記述することで
- 内容の意味を決める
- リンクを作成する
- 内容を装飾する

等を実現できる．

## 個人的メモ

作成したHTMLをコマンドライン入力でブラウザ表示させる方法．

[参考](https://qiita.com/hkato/items/9ed477788633d1a62a7a)

### MacOSX

```
$ open hoge.html
```

### Linux

```
$ firefox hoge.html &
$ chrome hoge.html &
$ opera hoge.html &
```

等

### あとで調べる

Vagrantを介して，LinuxをCLIで動かしている場合はどうする？
とりあえず，Linux仮想環境とホストPC(Mac)で共有フォルダを設定して，ホストPC側のブラウザで表示させることにする．


## 練習問題

ファイル名: `haiku.html`<br>
タイトル: `高浜虚子の俳句`<br>
内容:

```
春風や
闘志いだきて
丘に立つ
```

と表示されるHTMLファイルを作成せよ．

### 答案

`./02_first_time_html/haiku.html`にある．

### 模範解答との比較

考え方に相違ない．正解．

## 気になる点

練習問題でいきなり`<br>`タグが使われているが，テキストに解説あった？

（動画では扱っていたのかもしれない．既知なので，解答には支障なかった．）