# Fractional-Encoding
MDPI誌にて掲載されています。
https://www.mdpi.com/2079-9292/12/15/3211

概要：
古典的なNP完全問題であるSAT問題に対する新しいアプローチを紹介しています。
現実世界の問題をSATに変換し、SATソルバーを利用することが一般的で、特にモデル検証や電子回路生成などの分野で広く利用されています。
その計算時間のボトルネックとなるのがAt-Most-K制約で、これは全体の論理変数のうち最大Kのみが真となる場合にのみ満足されます。

本研究では、At-Most-K制約の論理式のサイズを減らす手段として、Fractional Encodingを提案しています。
Fractional Encodingは、変数の集合をm部分に分割し、各部分集合にPairwise Encodingを適用することで、ターゲット変数の数を1/mに減らします。
しかし、単純に集合を分割すると、解となる変数の可能な組み合わせの数が大幅に減少します。
その問題を避けるために、Fractional Encodingは補助変数を使用して分割された集合の間で真の変数の数を増減させます。
従来の方法との比較で、ターゲット変数の数が増えるときに論理式のサイズを減らすことができることが示されています。

Fractional EncodingはGoogle Colab上で実行可能です。

![lite_fin](https://github.com/mikiyonekura/Fractional-Encoding/assets/125361876/af124242-1bf7-4c4f-818e-b29164d2c72f)


