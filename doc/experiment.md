# 実験

- Baseline作成
- fold-0のみ

|exp|inf|loss|jaccard|LB|memo|
|--|--|--|--|--|--|
|[exp000_starter]||5.592|0.09|||
|[exp001_fix_eval]||0.3033|0.1043|||
|[exp002_xquad]||0.2617|0.1127|||
|[exp003_fix_eval]||0.3746|0.1293||`model.eval()`を忘れてたのを修正|
|[exp004_swap_q_c]|||||明らかに悪い|
|[exp005_n_best]||0.3935|0.1499||Linearのinitも追加|
|[exp006_xlm_roberta]||0.4697|0.1768||勾配累積2, lr=2e-5|
|[exp007_fix_score]||0.4697|0.1735|||
|[exp008_large]||0.4181|0.2206|||
|||||||
|[exp009_10fold]|||||変わらない|
|exp010_16fold|||||exp009_10foldに混じっちゃってる|
|exp011_fix_note|||||変わらない|
|[exp012_end_bug_fix]|||||クソデカバグ修正|


[exp000_starter]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72048948
[exp001_fix_eval]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72194536
[exp002_xquad]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72198646
[exp003_fix_eval]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72737553
[exp004_swap_q_c]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72741144
[exp005_n_best]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72744528
[exp006_xlm_roberta]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72748635
[exp007_fix_score]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72753155
[exp008_large]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72754720
[exp009_10fold]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72759526
[exp012_end_bug_fix]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72782040
