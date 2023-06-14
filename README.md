# 2023-seminar-previous.term
2023前期のゼミの実装結果をまとめるレポジトリ<br>
【最終目標】<br>
音声認識を行い、カラオケの採点システムのようなものを実装する

[実験サイト](http://www.sap.ist.i.kyoto-u.ac.jp/members/inoue/le4-audio/)  <br>
[授業PDF](https://drive.google.com/file/d/1kUTLW88KxTm--3_VQFFObd-vioAEgRci/view)  <br>
[実装colab](https://colab.research.google.com/drive/1npe5XEhCqQaWDQRtWXWtYRGTwpfrGlK-?usp=sharing)
[NMF実装colab](https://colab.research.google.com/drive/1XC-Fa54Lu52Mqn1iJz524WV4HCKecOfe#scrollTo=78YuAno_mU0E)


## タイムライン

- ゼミでの実装課題にしようと思い立つ (2023.04.12)
- 「あいうえお」の音声ファイルをcolabで読み込み、スペクトルの波形を表示させることに成功 (2023.04.24)  <br>
- colab上で録音を行い、それをwavファイルに変換するプログラムを作成(2023.05.09)<br>
- github上に上げたwavデータをDLしてcolabのcontentに格納するプログラムを作成(2023.05.09)<br>
（一回一回colabにファイルをアップロードしなくても、githubに上げておけば、そこからデータを引っ張ってこれる！）
- ついでにwavを再生するプログラムも作成(2023.05.09)
- 音声分離を機械学習で行うための論文読みを進めていく(2023.05.10)

### メモ 

普通にcolabオンリーでできそう  <br>

スペクトル:フーリエ変換を用いて音声波形を周波数成分に分解したもの   <br>
スペクトログラム: 周波数分析を時間的に連続して行い、色によって強さを表すことで、強さ、周波数、時間の３次元表示を行う


### KEYWORD
音声分離<br>
（カラオケは「背景音楽」＋「歌声」で構成されているので、それを分離したい）<br>
[3]参照


### 参考になりそうなサイト

[1] [colabを用いた音声ファイルの認識](https://zenn.dev/tam_tam/articles/d59250ecf25628)  <br>

[2] [colab音声録音コード](https://gist.github.com/tam17aki/8bfa2a42dab0061ee2641aed32dd1d30) <br>

[3] [深層学習→音声分離](https://olaris.jp/poststag/PPrQHWLo)
