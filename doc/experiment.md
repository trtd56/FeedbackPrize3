# 実験

|exp|inf|loss|jaccard|LB|memo|
|--|--|--|--|--|--|
|[exp056_cv_mlqa_f0]|[exp056_inf_f0]|1.215|0.6733|0.731||
|[exp056_cv_mlqa_f1]|[exp056_inf_f1]|1.314|0.6598|0.747||
|[exp056_cv_mlqa_f2]|[exp056_inf_f2]|1.301|0.6535|0.726||
|[exp056_cv_mlqa_f3]|[exp056_inf_f3]|1.174|0.6707|0.719||
|[exp056_cv_mlqa_f4]|[exp056_inf_f4]|1.32|0.6764|0.717||
|CV|[exp056_inf_cv_1]||0.6667|0.744||
|CV|[exp056_inf_cv_2]||0.6667|0.738|hindi前処理なし|
|CV|[exp056_inf_cv_3]||0.6667|0.723|score max|
|CV|[exp056_inf_cv_4]||0.6667|0.683|score max, softmax|
|CV|[exp056_inf_cv_5]||0.6667|0.702|softmax|
|CV|[exp056_inf_cv_6]||0.6667|0.748|w = 3:4:2:1:1|
|||||||
|[exp057_reinit2_f0]|[exp057_inf_f0]|1.213|0.6793|0.732||
|[exp057_reinit2_f1]|[exp057_inf_f1]|1.307|0.6548|0.741||
|[exp057_reinit2_f2]|[exp057_inf_f2]|1.299|0.6497|0.731||
|[exp057_reinit2_f3]|[exp057_inf_f3]|1.181|0.6691|0.726||
|[exp057_reinit2_f4]|[exp057_inf_f4]|1.338|0.6731|0.725||
|CV|[exp057_inf_cv]||0.6652|0.739||
|||||||
|[exp058_add_org_f0]|[exp058_inf_f0]|1.221|0.6656|0.738||
|[exp058_add_org_f1]|[exp058_inf_f1]|1.309|0.6718|0.740||
|[exp058_add_org_f2]|[exp058_inf_f2]|1.284|0.6528|0.739||
|[exp058_add_org_f3]|[exp058_inf_f3]|1.186|0.6662|0.732||
|[exp058_add_org_f4]|[exp058_inf_f4]|1.319|0.6826|0.735||
|CV|[exp058_inf_cv]||0.6678|0.742||
|||||||
|CV|[exp058_inf_cv_best_1]|||0.747|f1のみexp056|
|CV|[exp058_inf_cv_best_2]|||0.753|w = 2:3:2:1:1|
|||||||
|[exp059_org_pseudo_f0]|[exp059_inf_f0]|1.208|0.6763|0.733||
|[exp059_org_pseudo_f1]|[exp059_inf_f1]|1.283|0.6554|0.738||
|||||||
|[exp060_pp_train_f0]||1.215|0.6726|||
|||||||
|CV|[exp053_inf_cv_3]|||0.750|xquad best, w=1:1:2:2:1|
|||||||
|[exp061_no_lang_tag_f0]|[exp061_inf_f0]|1.198|0.6647|0.730||
|||||||
|[exp060_tamil_f0]|[exp060_inf_f0]|0.8995|0.6558|0.747||
|[exp060_tamil_f1]|[exp060_inf_f1]|0.9116|0.6605|0.735||
|[exp060_tamil_f2]|[exp060_inf_f2]|0.8449|0.6796|0.748||
|[exp060_tamil_f3]|[exp060_inf_f3]|0.8965|0.653|0.747||
|[exp060_tamil_f4]|[exp060_inf_f4]|0.8849|0.649|0.741||
|CV|[exp060_inf_cv_1]||0.6596|0.747||
|CV|[exp060_inf_cv_2]||0.6596||w=3:1:3:3:2|
|||||||
|[exp062_no_acc_f0]|[exp062_inf_f0]|0.9373|0.6424|0.742||
|[exp062_no_acc_f1]|[exp062_inf_f1]|0.9223|0.651|0.739||
|||||||
|[exp063_no_trans_f0_1]|[exp063_inf_f0_1]|||0.735||
|[exp063_no_trans_f0_2]|[exp063_inf_f0_2]||||sampling * 2|
|[exp063_no_trans_f0_3]|[exp063_inf_f0_3]||||sampling * 4|
|[exp063_no_trans_f0_4]|[exp063_inf_f0_4]||||sampling * 8|
|[exp063_no_trans_f0_5]|[exp063_inf_f0_5]||||sampling * X, acc=8|

[exp056_cv_mlqa_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74703280
[exp056_cv_mlqa_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74706731
[exp056_cv_mlqa_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74718504
[exp056_cv_mlqa_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74724233
[exp056_cv_mlqa_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74779745
[exp056_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74706690
[exp056_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74713322
[exp056_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74724156
[exp056_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74729478
[exp056_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74782199
[exp056_inf_cv_1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74784419
[exp056_inf_cv_2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74946775
[exp056_inf_cv_3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74948489
[exp056_inf_cv_4]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74948839
[exp056_inf_cv_5]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74954348
[exp056_inf_cv_6]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=75027109

[exp057_reinit2_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74782911
[exp057_reinit2_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74788543
[exp057_reinit2_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74792346
[exp057_reinit2_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74949284
[exp057_reinit2_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74953446
[exp057_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74788524
[exp057_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model/output?scriptVersionId=74791457
[exp057_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74947458
[exp057_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75115785
[exp057_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75115989
[exp057_inf_cv]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=75115717

[exp058_add_org_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74861279
[exp058_add_org_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74875155
[exp058_add_org_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74959575
[exp058_add_org_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74970983
[exp058_add_org_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74979717
[exp058_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74866818
[exp058_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74884171
[exp058_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75092001
[exp058_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75091882
[exp058_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75018470
[exp058_inf_cv]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=75091907

[exp058_inf_cv_best_1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=75247315
[exp058_inf_cv_best_2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=75248631

[exp059_org_pseudo_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74883936
[exp059_org_pseudo_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74891704
[exp059_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74891472
[exp059_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74942024

[exp060_pp_train_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74942214

[exp053_inf_cv_3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=75256761

[exp061_no_lang_tag_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74943955
[exp061_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74946865

[exp060_tamil_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=75249890
[exp060_tamil_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=75256991
[exp060_tamil_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=75262525
[exp060_tamil_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=75270891
[exp060_tamil_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=75284364
[exp060_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75256736
[exp060_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75262472
[exp060_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75270812
[exp060_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75284338
[exp060_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model/log?scriptVersionId=75325614
[exp060_inf_cv_1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=75339963
[exp060_inf_cv_2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=75340480

[exp062_no_acc_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=75329609
[exp062_no_acc_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=75340583
[exp062_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75340047
[exp062_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75406692

[exp063_no_trans_f0_1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=75406818
[exp063_no_trans_f0_2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model/log?scriptVersionId=75411155
[exp063_no_trans_f0_3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=75413124
[exp063_no_trans_f0_4]:xxx
[exp063_no_trans_f0_5]:xxx
[exp063_inf_f0_1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75410885
[exp063_inf_f0_2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=75413102
[exp063_inf_f0_3]:xxx
[exp063_inf_f0_4]:xxx
[exp063_inf_f0_5]:xxx

## ToDo

- MSD
- FP16なし


