## 5. Model risk and governance

- machine learningモデルはいくつもあって，それぞれ長所短所がある.

#### Model Chioce
いわゆる機械学習でよく使われるモデルは大きく分けて4つ
1. Trees
1. clustering (unsupervised approaches)
1. neural network
1. regression

##### Trees
最もよく用いられるモデルの一つ．

decision tree(決定木):　アルゴリズム簡単だか，オーバーフィットしてしまう．ただ，サンプルとしては多く用いられている．（データを過剰にフィットしてしまうので，判別のthresholdが高いモデルになる？？）

random forest:最も多く用いられているアルゴリズム

Gradient boosted trees(GBTs):木が前の木(gradient descentと呼ばれる)から学ぶ．平均絶対誤差(mean absolute error)を最小にするアルゴリズム.(誤差の絶対値の和をサンプル数で割った値:回帰モデルの誤差を評価するのに用いられる)

treeのアルゴリズムは最もよく用いられている．

ある銀行:tree basedのアルゴリズムは，バケットわけとかランクわけをしないで機械学習できるので，情報ロスがない．

ある２つの銀行：あまり整っていないデータを元にして協力なpredictiveなモデルを作っているらしい．(どんな題材だろう...)
