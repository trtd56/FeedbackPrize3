# 実験

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
|CV|[exp044_inf_cv_3]|||0.736|This CV AVG|
|||||||
|[exp046_tamil_trans_f0]|[exp046_inf_f0]|0.2431|0.6192|0.733||
|[exp046_tamil_trans_f1]|[exp046_inf_f1]|0.2292|0.6738|0.724||
|[exp046_tamil_trans_f2]|[exp046_inf_f2]|0.1752|0.7085|0.730||
|[exp046_tamil_trans_f3]|[exp046_inf_f3]|0.2232|0.674|0.736||
|[exp046_tamil_trans_f4]|[exp046_inf_f4]|0.2109|0.7007|0.745||
|CV|[exp046_inf_cv_1]|||0.744|Now Best AVG|
|CV|[exp044_inf_cv_2]|||0.747|Now Best W AVG|
|CV|[exp046_inf_cv_3]|||0.742|This CV AVG|
|||||||
|[exp048_pre_tamil_nlp_f0]|[exp048_inf_f0]|0.2564|0.6286|0.715||
|[exp048_pre_tamil_nlp_f1]|[exp048_inf_f1]|0.2427|0.6382|0.703||
|||||||
|[exp049_only_tamil_f0]|[exp049_inf_f0]||0.5622|0.728||
|[exp049_only_tamil_f1]|||0.5412|||
|||||||
|[exp050_only_hindi_xquad_f0]|[exp050_inf_f0_loss]|0.2564||0.713||
|[exp050_only_hindi_xquad_f0]|[exp050_inf_f0_jaccard]||0.6701|0.719||
|[exp050_only_hindi_xquad_f1]|[exp050_inf_f1_jaccard]|0.2234|0.7304|0.725||
|[exp050_only_hindi_xquad_f2]|[exp050_inf_f2_jaccard]|0.1542|0.763|0.722||
|[exp050_only_hindi_xquad_f3]|[exp050_inf_f3_jaccard]|0.2098|0.7561|||
|||||||
|[exp051_cv_xquad_f0]|[exp051_inf_f0]|1.253|0.6897|0.715||
|[exp051_cv_xquad_f1]|[exp051_inf_f1]|1.174|0.6992|0.731||
|[exp051_cv_xquad_f2]|[exp051_inf_f2]|0.9595|0.7382|0.741||
|[exp051_cv_xquad_f3]|[exp051_inf_f3]|1.153|0.6878|0.746||
|[exp051_cv_xquad_f4]|[exp051_inf_f4]|1.07|0.7084|0.719||
|CV|[exp051_inf_cv_1]||||tamil only fold-4 -> mem over|
|CV|[exp051_inf_cv_2]||||tamil cv -> mem over|
|CV|[exp051_inf_cv_3]|||0.757|tamil cv fix|
|||||||
|[exp052_mlqa_f0]|[exp052_inf_f0_jaccard]||0.7158|0.735||
|[exp052_mlqa_f0]|[exp052_inf_f0_loss]|1.146||0.734||
|[exp052_mlqa_f1]|[exp052_inf_f1]|1.169|0.6977|0.737||
|[exp052_mlqa_f2]|[exp052_inf_f2_jaccard]||0.7768|0.743||
|[exp052_mlqa_f2]|[exp052_inf_f2_loss]|0.8661||0.739||
|[exp052_mlqa_f3]|[exp052_inf_f3]|1.124|0.7215|0.703||
|[exp052_mlqa_f4]|[exp052_inf_f4]|1.056|0.724|0.722||
|CV|[exp052_inf_cv]|||0.741||
|||||||
|[exp053_del_org_f0]|[exp053_inf_f0]|1.177|0.7228|0.727||
|[exp053_del_org_f1]|[exp053_inf_f1]|1.185|0.7071|0.735||
|[exp053_del_org_f2]|[exp053_inf_f2]|0.8998|0.7677|0.720||
|[exp053_del_org_f3]|[exp053_inf_f3]|1.091|0.7356|0.730||
|[exp053_del_org_f4]|[exp053_inf_f4]|1.057|0.7305|0.737||
|CV|[exp053_inf_cv_1]|||0.742||
|||||||
|Now Best|[exp053_inf_cv_2]|||0.751|f0-52, f1-52, f2-52, f3-51, f4-53|
|||||||
|[exp054_mix_cv_f0]|[exp054_inf_f0]|1.229|0.6612|0.720||
|[exp054_mix_cv_f1]|[exp054_inf_f1]|1.171|0.6628|0.724||
|[exp054_mix_cv_f2]|[exp054_inf_f2]|1.311|0.6618|0.726||
|||||||
|[exp055_reinit_f0]|[exp055_inf_f0]|1.244|0.6626|0.719||
|[exp055_reinit_f1]|[exp055_inf_f1]|1.172|0.6705|0.713||
|||||||
|[exp056_cv_mlqa_f0]|[exp056_inf_f0]|1.215|0.6733|0.731||
|[exp056_cv_mlqa_f1]|[exp056_inf_f1]|1.314|0.6598|0.747||
|[exp056_cv_mlqa_f2]|[exp056_inf_f2]|1.301|0.6535|0.726||
|[exp056_cv_mlqa_f3]|[exp056_inf_f3]|1.174|0.6707|0.719||
|[exp056_cv_mlqa_f4]|[exp056_inf_f4]|1.32|0.6764|0.717||
|CV|[exp056_inf_cv]|||||
|||||||
|[exp057_reinit2_f0]|[exp057_inf_f0]|1.213|0.6793|||
|[exp057_reinit2_f1]|[exp057_inf_f1]|||||

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
[exp044_inf_cv_3]:https://www.kaggle.com/takamichitoda/chaii-infer-cv?scriptVersionId=73876531

[exp046_tamil_trans_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73878014
[exp046_tamil_trans_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73921213
[exp046_tamil_trans_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=73992904
[exp046_tamil_trans_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74060823
[exp046_tamil_trans_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74065527
[exp046_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73921259
[exp046_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=73992951
[exp046_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=74060733
[exp046_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=74065546
[exp046_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=74072740
[exp046_inf_cv_1]:https://www.kaggle.com/takamichitoda/chaii-infer-cv/data?scriptVersionId=74077768
[exp046_inf_cv_2]:https://www.kaggle.com/takamichitoda/chaii-infer-cv?scriptVersionId=74087080
[exp046_inf_cv_3]:https://www.kaggle.com/takamichitoda/chaii-infer-cv?scriptVersionId=74102800

[exp048_pre_tamil_nlp_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74078565
[exp048_pre_tamil_nlp_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74087127
[exp048_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=74087805
[exp048_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-large-model?scriptVersionId=74096160

[exp049_only_tamil_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74146892
[exp049_only_tamil_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74149729
[exp049_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74152155

[exp050_only_hindi_xquad_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74156669
[exp050_only_hindi_xquad_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74161858
[exp050_only_hindi_xquad_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74231130
[exp050_only_hindi_xquad_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74238259
[exp050_inf_f0_loss]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74161409
[exp050_inf_f0_jaccard]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74161622
[exp050_inf_f1_jaccard]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74167256
[exp050_inf_f2_jaccard]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74238158
[exp050_inf_f3_jaccard]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74242855

[exp051_cv_xquad_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74243706
[exp051_cv_xquad_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74248638
[exp051_cv_xquad_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74258397
[exp051_cv_xquad_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74263638
[exp051_cv_xquad_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74314720
[exp051_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74248175
[exp051_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74254089
[exp051_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74263185
[exp051_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74273989
[exp051_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74316967
[exp051_inf_cv_1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74413108
[exp051_inf_cv_2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74413881
[exp051_inf_cv_3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74537931

[exp052_mlqa_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74319003
[exp052_mlqa_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74325328
[exp052_mlqa_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74331044
[exp052_mlqa_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74396613
[exp052_mlqa_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74415417
[exp052_inf_f0_jaccard]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74325276
[exp052_inf_f0_loss]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74327095
[exp052_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74330941
[exp052_inf_f2_jaccard]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74342129
[exp052_inf_f2_loss]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74396835
[exp052_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74405476
[exp052_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74470945
[exp052_inf_cv]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74610132

[exp053_del_org_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74471037
[exp053_del_org_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74472415
[exp053_del_org_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74537971
[exp053_del_org_f3]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74608376
[exp053_del_org_f4]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74609982
[exp053_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74472362
[exp053_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74537559
[exp053_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74608361
[exp053_inf_f3]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74609953
[exp053_inf_f4]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74611556
[exp053_inf_cv_1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74612567
[exp053_inf_cv_2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74621358

[exp054_mix_cv_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74611869
[exp054_mix_cv_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74617758
[exp054_mix_cv_f2]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74621644
[exp054_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74616277
[exp054_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74621501
[exp054_inf_f2]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74621501

[exp055_reinit_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74625660
[exp055_reinit_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74696612
[exp055_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74633842
[exp055_inf_f1]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74700401

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
[exp056_inf_cv]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model-cv?scriptVersionId=74784419

[exp057_reinit2_f0]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74782911
[exp057_reinit2_f1]:https://www.kaggle.com/takamichitoda/chaii-train-large-model?scriptVersionId=74788543
[exp057_inf_f0]:https://www.kaggle.com/takamichitoda/chaii-infer-divide-model?scriptVersionId=74788524
[exp057_inf_f1]:xxx

## ToDo

- tagの有無の実験
- MSD
- reinitの実験
