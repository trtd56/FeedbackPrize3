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
|||||||
|[exp012_end_bug_fix]|[exp012_inf_1]|0.3081|0.5141|0.580|クソデカバグ修正|
|[exp013_token_type_id]|||||使わないときと変わらず|
|[exp014_bert]|[exp014_inf_1]|0.2303|0.4655|0.124||
|[exp015_dropout]|[exp015_inf_1]|0.3069|0.4921|0.582|若干悪化？|
|[exp016_div_lang]|[exp016_inf_1]|0.3232|0.475|0.544|スコアとlossは平均なのでズレあり|
|[exp017_msd]|[exp017_inf_1]|0.3084|0.4979|0.557||
|[exp018_maxout]|[exp018_inf_1]|0.2937|0.5037|0.611||
|[exp019_rdrop]|[exp019_inf_1]|0.3034|0.508|0.595||
|[exp020_lang_tag]|[exp020_inf_1]|0.2862|0.5108|0.612||
|[exp021_mixout_rdrop_tag]|[exp021_inf_1]|0.2841|0.512|0.620|ここまでの全部のせ|
|[exp022_gap_loss]||0.3226|0.4854||良くない|
|[exp023_reinit1]||0.2924|0.5205|0.615||
|[exp024_reinit2]||0.2955|0.4897|||
|[exp025_gap_loss_fix]|||||変わらず悪い|
|[exp026_add_ml_qa]|||||悪い|
|[exp027_indic_bert]|||||悪い|
|[exp028_weight_lang]||0.2945|0.5063|||
|[exp029_reduction]||0.9161|0.4955||pos weightは微妙そう？|
|[exp030_ml_qa_w01]||0.3907|0.409||悪い|
|[exp031_no_rdrop]|[exp031_inf_1]|0.2847|0.5101|0.622||
|[exp032_no_rdrop_gap]|[exp032_inf_1]|0.8448|0.48|0.561||
|[exp033_no_rdrop_bs16]|[exp033_inf_1]|0.2862|0.5108|0.612||
|[exp033_no_rdrop_bs16]|[exp033_inf_2]|0.2862|0.5108|0.617|後処理|
|[exp034_w_hindi_03]|[exp034_inf_1]|0.301|0.521|0.590||
|[exp034_w_hindi_03]|[exp034_inf_2]|0.301|0.521|0.595|後処理|
|[exp035_mlqa]||||||
|[exp036_rembert]|||||良くない、BSの問題？|
|[exp037_trans_tamil]|[exp037_inf_1]|0.2935|0.5226|0.613||
|||||||
|[exp039_sigmoid]||||||
|[exp040_bce_and_ce]||||||
|[exp041_bce_mask]||||||
|[exp042_load_w_mask]||||||
|||||||
|[exp043_relabel]|[exp043_inf_1]|0.2985|0.5038|0.583|[pseudo](https://www.kaggle.com/takamichitoda/chaii-check-pseudo-answer-start?scriptVersionId=73676867)|
|||||||
|[exp045_muril]||||||

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
[exp012_end_bug_fix]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72783826
[exp012_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer?scriptVersionId=72788418
[exp013_token_type_id]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72789413
[exp014_bert]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72790932
[exp014_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer?scriptVersionId=72793521
[exp015_dropout]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72793933
[exp015_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer?scriptVersionId=72858130
[exp016_div_lang]:https://www.kaggle.com/takamichitoda/chaii-train-with-divided-hindi-and-tamil?scriptVersionId=72857024
[exp016_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer-with-divided-hindi-and-tamil?scriptVersionId=72858643
[exp017_msd]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72859444
[exp017_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer?scriptVersionId=72861175
[exp018_maxout]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72861682
[exp018_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer?scriptVersionId=72863249
[exp019_rdrop]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72874844
[exp019_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer?scriptVersionId=72877471
[exp020_lang_tag]:https://www.kaggle.com/takamichitoda/chaii-starter?scriptVersionId=72877730
[exp020_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer?scriptVersionId=72879477
[exp021_mixout_rdrop_tag]:https://www.kaggle.com/takamichitoda/chaii-train-mixout-and-r-drop?scriptVersionId=72892630
[exp021_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer-mixout-and-r-drop?scriptVersionId=72896948
[exp022_gap_loss]:https://www.kaggle.com/takamichitoda/chaii-train-mixout-and-r-drop?scriptVersionId=72908023
[exp023_reinit1]:https://www.kaggle.com/takamichitoda/chaii-train-mixout-and-r-drop?scriptVersionId=72968767
[exp023_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer-mixout-and-r-drop?scriptVersionId=72972622
[exp024_reinit2]:https://www.kaggle.com/takamichitoda/chaii-train-mixout-and-r-drop?scriptVersionId=72966513
[exp025_gap_loss_fix]:https://www.kaggle.com/takamichitoda/chaii-train-mixout-and-r-drop?scriptVersionId=72975075
[exp026_add_ml_qa]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73001436
[exp027_indic_bert]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73006473
[exp028_weight_lang]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73012917
[exp029_reduction]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73021325
[exp030_ml_qa_w01]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73029100
[exp031_no_rdrop]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73032376
[exp031_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer-external-data?scriptVersionId=73081274
[exp032_no_rdrop_gap]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73080608
[exp032_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer-external-data?scriptVersionId=73082076
[exp033_no_rdrop_bs16]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73082004
[exp033_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer-external-data?scriptVersionId=73084043
[exp033_inf_2]:https://www.kaggle.com/takamichitoda/chaii-infer-external-data?scriptVersionId=73084294
[exp034_w_hindi_03]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73085026
[exp034_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer-external-data?scriptVersionId=73086346
[exp034_inf_2]:https://www.kaggle.com/takamichitoda/chaii-infer-external-data?scriptVersionId=73086673
[exp035_mlqa]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73089102
[exp036_rembert]:https://www.kaggle.com/takamichitoda/chaii-train-rembert?scriptVersionId=73116142
[exp037_trans_tamil]:https://www.kaggle.com/takamichitoda/chaii-train-external-data?scriptVersionId=73123883
[exp037_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer-external-data?scriptVersionId=73216114
[exp039_sigmoid]:https://www.kaggle.com/takamichitoda/chaii-train-sigmoid?scriptVersionId=73581017
[exp040_bce_and_ce]:https://www.kaggle.com/takamichitoda/chaii-train-sigmoid?scriptVersionId=73588387
[exp041_bce_mask]:https://www.kaggle.com/takamichitoda/chaii-train-sigmoid?scriptVersionId=73590579
[exp042_load_w_mask]:https://www.kaggle.com/takamichitoda/chaii-train-sigmoid?scriptVersionId=73610554
[exp043_relabel]:https://www.kaggle.com/takamichitoda/fork-of-chaii-train-sigmoid?scriptVersionId=73678004
[exp043_inf_1]:https://www.kaggle.com/takamichitoda/chaii-infer-relabel?scriptVersionId=73680174

### roberta-large 5 CV

|exp|inf|loss|jaccard|LB|memo|
|--|--|--|--|--|--|
|[exp038_large_f0]|[exp038_inf_f0]|0.2465|0.6388|0.715||
|[exp038_large_f1]|[exp038_inf_f1]|0.2380|0.6560|0.718||
|[exp038_large_f2]|[exp038_inf_f2]|0.1747|0.6862|0.698||
|[exp038_large_f3]|[exp038_inf_f3]|0.2269|0.6765|0.713||
|[exp038_large_f4]|[exp038_inf_f4]|0.2136|0.6452|0.703||
|CV|[exp038_inf_cv_1]|||0.739|AVG|
|CV|[exp038_inf_cv_2]|||0.721|MAX|
|CV|[exp038_inf_cv_3]|||0.748|W AVG|
|||||||
|[exp044_reinit_f0]|[exp044_inf_f0]|0.247|0.6444|0.713||
|[exp044_reinit_f1]|[exp044_inf_f1]|0.235|0.6571|0.722||
|[exp044_reinit_f2]|[exp044_inf_f2]|0.1774|0.7147|0.733||
|[exp044_reinit_f3]|[exp044_inf_f3]|0.2358|0.6703|0.729||
|[exp044_reinit_f4]|[exp044_inf_f4]|0.2149|0.6885|0.713||
|CV|[exp044_inf_cv_1]|||0.739|Now Best AVG|
|CV|[exp044_inf_cv_2]|||0.737|Now Best W AVG|
|CV|[exp044_inf_cv_3]||||This CV AVG|

[exp038_large_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73217640
[exp038_large_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73586001
[exp038_large_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73599928
[exp038_large_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73611319
[exp038_large_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73578107
[exp038_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73233243
[exp038_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73600052
[exp038_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73610863
[exp038_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73671509
[exp038_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73585823
[exp038_inf_cv_1]:https://www.kaggle.com/takamichitoda/chaii-infer-cv?scriptVersionId=73673973
[exp038_inf_cv_2]:https://www.kaggle.com/takamichitoda/chaii-infer-cv?scriptVersionId=73843734
[exp038_inf_cv_3]:https://www.kaggle.com/takamichitoda/chaii-infer-cv?scriptVersionId=73844058
[exp044_reinit_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73788678
[exp044_reinit_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73800613
[exp044_reinit_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73843570
[exp044_reinit_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73847144
[exp044_reinit_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73851257
[exp044_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73800704
[exp044_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73843489
[exp044_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73847112
[exp044_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73851241
[exp044_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73856133
[exp044_inf_cv_1]:https://www.kaggle.com/takamichitoda/chaii-infer-cv?scriptVersionId=73862468
[exp044_inf_cv_2]:https://www.kaggle.com/takamichitoda/chaii-infer-cv?scriptVersionId=73863015
[exp044_inf_cv_3]:xxx
