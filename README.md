# Fractional-Encoding
MDPI誌にて掲載されています。
https://www.mdpi.com/2079-9292/12/15/3211

# 概要：
古典的なNP完全問題であるSAT問題に対する新しいアプローチを紹介しています。
モデル検証や電子回路生成などの様々な現実問題を論理式（SAT）に変換し、SATソルバーによって高速に解を求めることが可能です．
論理式の計算時間においてボトルネックとなるのがAt-Most-K制約です．
これは全体の論理変数のうち最大Kのみが真となる場合にのみ満たされる制約を指します。

本研究では、At-Most-K制約の論理式のサイズを減らす手段として、Fractional Encodingを提案しています。
Fractional Encodingは、変数の集合をm部分に分割し、各部分集合にPairwise Encodingを適用することで、ターゲット変数の数を1/mに減らします。
しかし、単純に集合を分割すると、解となる変数の可能な組み合わせの数が大幅に減少します。
その問題を避けるために、Fractional Encodingは補助変数を使用して分割された集合の間で真の変数の数を増減させます。
従来の方法との比較で、ターゲット変数の数が増えるときに論理式のサイズを減らすことができることが示されています。

# Fractional EncodingはGoogle Colab上で実行可能です。

![lite_fin](https://github.com/mikiyonekura/Fractional-Encoding/assets/125361876/af124242-1bf7-4c4f-818e-b29164d2c72f)


