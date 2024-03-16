# 競プロ用スニペット集(go)
## データ構造

### Priority Queue
 - [ジェネリクスで汎化](https://gist.github.com/ynzwtks/545cad2032f877e87c76672162f56068)<br>
 - [削除可能な優先度付きキュー](https://gist.github.com/ynzwtks/663a8bc97518d45708c9d7cb31413727)<br>
 - [キュー内の要素について昇順または降順でk番目までの和を求める](https://gist.github.com/ynzwtks/54ffc31a806c41d70dcf72287547f4d3)<br>

### セグメント木
- [遅延評価セグメント木(区間加算/区間更新の区間和/最小値/最大値)](https://gist.github.com/ynzwtks/a08d8c2ecb71daf4eacf26bf44843922)<br>
- [双対セグメント木(区間更新(or 区間加算)、点取得)](https://gist.github.com/ynzwtks/4eda2432530318f8e591c9b30b2ccd82)<br>
- [セグメント木版ローリングハッシュ(MOD 2^61-1)(点更新)](https://gist.github.com/ynzwtks/8cfe266bea7570ab06dc8a777ba9bd42)<br>
- [index付きRMQ](https://gist.github.com/ynzwtks/08d5e4b1d410c321749d5c4462303887)<br>

### Fenwick Tree
- [2次元累積和(imos)](https://gist.github.com/ynzwtks/f27cc5cc757e53620495abe713fa5f0e)<br>
- [2次元累積和(BIT)](https://gist.github.com/ynzwtks/6991a45382ec8fd1973267ce30a468a8)<br>

### リスト
- [双方向リスト(要素削除、挿入)](https://gist.github.com/ynzwtks/44b6ea7a5ee52df24e85f50cabce15ae)<br>
- [永続リスト](https://gist.github.com/ynzwtks/93dde62d0ad10a395b3556d5bea47764)<br>

### WaveletMatrix
- [区間のlow以上、high未満の要素数,区間のk番目に大きい(小さい)要素](https://gist.github.com/ynzwtks/62fc0a68e38cb0e9b9535547c6359cef)<br>

### Avl Tree
- [キュー内の要素について昇順または降順でk番目までの和を求める](https://gist.github.com/ynzwtks/9a0792adc0e89d6cf2c14ca847975a2b)<br>

## アルゴリズム
### bit操作
- [2進数でbitの0と1を指定した数分含む値ついて小さいほうからkth番目の値を求める](https://gist.github.com/ynzwtks/3cc4de6c3936e26fdddee979d07d80db)<br>
- [2進数に変換した各桁について、0の場合はbit0,1の場合はbit1で対応する桁の値に置き換える](https://gist.github.com/ynzwtks/3cc4de6c3936e26fdddee979d07d80db)<br>
- [bitが1位置についてスライスの和を取る](https://gist.github.com/ynzwtks/3cc4de6c3936e26fdddee979d07d80db)<br>
- [指定した範囲に含まれるbit1の数をカウントする](https://gist.github.com/ynzwtks/3cc4de6c3936e26fdddee979d07d80db)<br>

### パターン列挙
- [nビットのうち、ビット1がk個となる値のパターンを列挙する](https://gist.github.com/ynzwtks/604549c4ad18cb1ae0c1456957876756)<br>
- [指定した範囲の値からなるn個の要素のスライスを列挙する](https://gist.github.com/ynzwtks/2e7d20473b9452da5907f80e316ff978)<br>
- [nextPermutation()を呼び出すクロージャーを返す](https://gist.github.com/ynzwtks/33e1ff915ddce3ae8e2c8ee0fec4715b)<br>
- [n個の要素で合計がsとなるスライスの組み合わせを返す](https://gist.github.com/ynzwtks/05bd5756443345ce7f25af6cf03599a2)<br>
- [部分列のMod和毎に部分列を指定した個数列挙する](https://gist.github.com/ynzwtks/d88224b3235721524cf9ce2791f37c2c)<br>

### グルーピング
- [単調増加のスライスで隣合う要素の差がd以下のものをグルーピングし開始/終了位置を返す](https://gist.github.com/ynzwtks/84f2a0b0876f047eb0e99d60d127c6df)<br>
- [Pairの片方をキーとしてuniqなPairを抽出する](https://gist.github.com/ynzwtks/7982e0439065455d68ada380c0f4cdf0)<br>
- [連続するbitのidxでグルーピングする](https://gist.github.com/ynzwtks/16f42c67e4e84f7493845441260d9981)<br>
- [連続する区間のグループ分け](https://gist.github.com/ynzwtks/f7d285d81491f95d59603e3898f88a69)<br>

## Math
### Geometry
- [２次元座標のマンハッタン距離の最大値を求める](https://gist.github.com/ynzwtks/0bcb13015a756eb3eebc46b826be612b)<br>
- [直線上にある区間の交差判定](https://gist.github.com/ynzwtks/17d6ca0c41a03680e22beeae8353c0de)<br>

### 分数・整数
- [分数の比較と加算・減算・乗算](https://gist.github.com/ynzwtks/390a3d4de1ac3b1ae6ee7f2cfb173273)<br>
