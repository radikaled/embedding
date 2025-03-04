---
language:
- en
license: apache-2.0
library_name: sentence-transformers
tags:
- language
- granite
- embeddings
- mteb
- transformers
model-index:
- name: ibm-granite/granite-embedding-30m-english
  results:
  - dataset:
      config: en-ext
      name: MTEB AmazonCounterfactualClassification (en-ext)
      revision: e8379541af4e31359cca9fbcf4b00f2671dba205
      split: test
      type: mteb/amazon_counterfactual
    metrics:
    - type: accuracy
      value: 62.856100000000005
    - type: f1
      value: 51.5046
    - type: f1_weighted
      value: 69.9775
    - type: ap
      value: 15.4995
    - type: ap_weighted
      value: 15.4995
    - type: main_score
      value: 62.856100000000005
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB AmazonCounterfactualClassification (en)
      revision: e8379541af4e31359cca9fbcf4b00f2671dba205
      split: test
      type: mteb/amazon_counterfactual
    metrics:
    - type: accuracy
      value: 60.925399999999996
    - type: f1
      value: 55.0092
    - type: f1_weighted
      value: 64.8014
    - type: ap
      value: 25.0517
    - type: ap_weighted
      value: 25.0517
    - type: main_score
      value: 60.925399999999996
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB AmazonPolarityClassification (default)
      revision: e2d317d38cd51312af73b3d32a06d1a08b442046
      split: test
      type: mteb/amazon_polarity
    metrics:
    - type: accuracy
      value: 62.983599999999996
    - type: f1
      value: 62.553599999999996
    - type: f1_weighted
      value: 62.553599999999996
    - type: ap
      value: 58.3423
    - type: ap_weighted
      value: 58.3423
    - type: main_score
      value: 62.983599999999996
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB AmazonReviewsClassification (en)
      revision: 1399c76144fd37290681b995c656ef9b2e06e26d
      split: test
      type: mteb/amazon_reviews_multi
    metrics:
    - type: accuracy
      value: 32.178000000000004
    - type: f1
      value: 31.5201
    - type: f1_weighted
      value: 31.5201
    - type: main_score
      value: 32.178000000000004
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB AppsRetrieval (default)
      revision: f22508f96b7a36c2415181ed8bb76f76e04ae2d5
      split: test
      type: CoIR-Retrieval/apps
    metrics:
    - type: ndcg_at_1
      value: 3.5060000000000002
    - type: ndcg_at_3
      value: 4.789000000000001
    - type: ndcg_at_5
      value: 5.314
    - type: ndcg_at_10
      value: 6.203
    - type: ndcg_at_20
      value: 6.801
    - type: ndcg_at_100
      value: 8.588
    - type: ndcg_at_1000
      value: 12.418999999999999
    - type: map_at_1
      value: 3.5060000000000002
    - type: map_at_3
      value: 4.471
    - type: map_at_5
      value: 4.7620000000000005
    - type: map_at_10
      value: 5.117
    - type: map_at_20
      value: 5.281000000000001
    - type: map_at_100
      value: 5.501
    - type: map_at_1000
      value: 5.611
    - type: recall_at_1
      value: 3.5060000000000002
    - type: recall_at_3
      value: 5.71
    - type: recall_at_5
      value: 6.984999999999999
    - type: recall_at_10
      value: 9.801
    - type: recall_at_20
      value: 12.165
    - type: recall_at_100
      value: 22.205
    - type: recall_at_1000
      value: 54.396
    - type: precision_at_1
      value: 3.5060000000000002
    - type: precision_at_3
      value: 1.9029999999999998
    - type: precision_at_5
      value: 1.397
    - type: precision_at_10
      value: 0.98
    - type: precision_at_20
      value: 0.608
    - type: precision_at_100
      value: 0.22200000000000003
    - type: precision_at_1000
      value: 0.054
    - type: mrr_at_1
      value: 3.5060000000000002
    - type: mrr_at_3
      value: 4.471
    - type: mrr_at_5
      value: 4.7618
    - type: mrr_at_10
      value: 5.1166
    - type: mrr_at_20
      value: 5.2806
    - type: mrr_at_100
      value: 5.5014
    - type: mrr_at_1000
      value: 5.6113
    - type: nauc_ndcg_at_1_max
      value: 32.8089
    - type: nauc_ndcg_at_1_std
      value: 13.0518
    - type: nauc_ndcg_at_1_diff1
      value: 44.3602
    - type: nauc_ndcg_at_3_max
      value: 28.5037
    - type: nauc_ndcg_at_3_std
      value: 12.1308
    - type: nauc_ndcg_at_3_diff1
      value: 33.0191
    - type: nauc_ndcg_at_5_max
      value: 25.970100000000002
    - type: nauc_ndcg_at_5_std
      value: 12.089500000000001
    - type: nauc_ndcg_at_5_diff1
      value: 30.098200000000002
    - type: nauc_ndcg_at_10_max
      value: 23.9177
    - type: nauc_ndcg_at_10_std
      value: 12.1279
    - type: nauc_ndcg_at_10_diff1
      value: 26.3951
    - type: nauc_ndcg_at_20_max
      value: 22.2086
    - type: nauc_ndcg_at_20_std
      value: 11.355
    - type: nauc_ndcg_at_20_diff1
      value: 24.9668
    - type: nauc_ndcg_at_100_max
      value: 20.1961
    - type: nauc_ndcg_at_100_std
      value: 11.368300000000001
    - type: nauc_ndcg_at_100_diff1
      value: 21.654200000000003
    - type: nauc_ndcg_at_1000_max
      value: 19.7802
    - type: nauc_ndcg_at_1000_std
      value: 11.9399
    - type: nauc_ndcg_at_1000_diff1
      value: 19.8429
    - type: nauc_map_at_1_max
      value: 32.8089
    - type: nauc_map_at_1_std
      value: 13.0518
    - type: nauc_map_at_1_diff1
      value: 44.3602
    - type: nauc_map_at_3_max
      value: 29.285600000000002
    - type: nauc_map_at_3_std
      value: 12.4277
    - type: nauc_map_at_3_diff1
      value: 35.2678
    - type: nauc_map_at_5_max
      value: 27.6754
    - type: nauc_map_at_5_std
      value: 12.4042
    - type: nauc_map_at_5_diff1
      value: 33.330799999999996
    - type: nauc_map_at_10_max
      value: 26.571299999999997
    - type: nauc_map_at_10_std
      value: 12.439400000000001
    - type: nauc_map_at_10_diff1
      value: 31.275399999999998
    - type: nauc_map_at_20_max
      value: 25.8795
    - type: nauc_map_at_20_std
      value: 12.1596
    - type: nauc_map_at_20_diff1
      value: 30.6354
    - type: nauc_map_at_100_max
      value: 25.3369
    - type: nauc_map_at_100_std
      value: 12.0245
    - type: nauc_map_at_100_diff1
      value: 29.8703
    - type: nauc_map_at_1000_max
      value: 25.239800000000002
    - type: nauc_map_at_1000_std
      value: 12.0242
    - type: nauc_map_at_1000_diff1
      value: 29.7235
    - type: nauc_recall_at_1_max
      value: 32.8089
    - type: nauc_recall_at_1_std
      value: 13.0518
    - type: nauc_recall_at_1_diff1
      value: 44.3602
    - type: nauc_recall_at_3_max
      value: 26.747700000000002
    - type: nauc_recall_at_3_std
      value: 11.4203
    - type: nauc_recall_at_3_diff1
      value: 27.9047
    - type: nauc_recall_at_5_max
      value: 22.3707
    - type: nauc_recall_at_5_std
      value: 11.4164
    - type: nauc_recall_at_5_diff1
      value: 23.4182
    - type: nauc_recall_at_10_max
      value: 19.2758
    - type: nauc_recall_at_10_std
      value: 11.578800000000001
    - type: nauc_recall_at_10_diff1
      value: 18.030099999999997
    - type: nauc_recall_at_20_max
      value: 16.1643
    - type: nauc_recall_at_20_std
      value: 9.9037
    - type: nauc_recall_at_20_diff1
      value: 16.0833
    - type: nauc_recall_at_100_max
      value: 13.644700000000002
    - type: nauc_recall_at_100_std
      value: 10.986799999999999
    - type: nauc_recall_at_100_diff1
      value: 11.0515
    - type: nauc_recall_at_1000_max
      value: 13.9712
    - type: nauc_recall_at_1000_std
      value: 13.4048
    - type: nauc_recall_at_1000_diff1
      value: 6.569500000000001
    - type: nauc_precision_at_1_max
      value: 32.8089
    - type: nauc_precision_at_1_std
      value: 13.0518
    - type: nauc_precision_at_1_diff1
      value: 44.3602
    - type: nauc_precision_at_3_max
      value: 26.747700000000002
    - type: nauc_precision_at_3_std
      value: 11.4203
    - type: nauc_precision_at_3_diff1
      value: 27.9047
    - type: nauc_precision_at_5_max
      value: 22.3707
    - type: nauc_precision_at_5_std
      value: 11.4164
    - type: nauc_precision_at_5_diff1
      value: 23.4182
    - type: nauc_precision_at_10_max
      value: 19.2758
    - type: nauc_precision_at_10_std
      value: 11.578800000000001
    - type: nauc_precision_at_10_diff1
      value: 18.030099999999997
    - type: nauc_precision_at_20_max
      value: 16.1643
    - type: nauc_precision_at_20_std
      value: 9.9037
    - type: nauc_precision_at_20_diff1
      value: 16.0833
    - type: nauc_precision_at_100_max
      value: 13.644700000000002
    - type: nauc_precision_at_100_std
      value: 10.986799999999999
    - type: nauc_precision_at_100_diff1
      value: 11.0515
    - type: nauc_precision_at_1000_max
      value: 13.9712
    - type: nauc_precision_at_1000_std
      value: 13.4048
    - type: nauc_precision_at_1000_diff1
      value: 6.569500000000001
    - type: nauc_mrr_at_1_max
      value: 32.8089
    - type: nauc_mrr_at_1_std
      value: 13.0518
    - type: nauc_mrr_at_1_diff1
      value: 44.3602
    - type: nauc_mrr_at_3_max
      value: 29.285600000000002
    - type: nauc_mrr_at_3_std
      value: 12.4277
    - type: nauc_mrr_at_3_diff1
      value: 35.2678
    - type: nauc_mrr_at_5_max
      value: 27.6754
    - type: nauc_mrr_at_5_std
      value: 12.4042
    - type: nauc_mrr_at_5_diff1
      value: 33.330799999999996
    - type: nauc_mrr_at_10_max
      value: 26.571299999999997
    - type: nauc_mrr_at_10_std
      value: 12.439400000000001
    - type: nauc_mrr_at_10_diff1
      value: 31.275399999999998
    - type: nauc_mrr_at_20_max
      value: 25.8795
    - type: nauc_mrr_at_20_std
      value: 12.1596
    - type: nauc_mrr_at_20_diff1
      value: 30.6354
    - type: nauc_mrr_at_100_max
      value: 25.337
    - type: nauc_mrr_at_100_std
      value: 12.0245
    - type: nauc_mrr_at_100_diff1
      value: 29.870400000000004
    - type: nauc_mrr_at_1000_max
      value: 25.2399
    - type: nauc_mrr_at_1000_std
      value: 12.0242
    - type: nauc_mrr_at_1000_diff1
      value: 29.7236
    - type: main_score
      value: 6.203
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB ArguAna (default)
      revision: c22ab2a51041ffd869aaddef7af8d8215647e41a
      split: test
      type: mteb/arguana
    metrics:
    - type: ndcg_at_1
      value: 31.791999999999998
    - type: ndcg_at_3
      value: 46.453
    - type: ndcg_at_5
      value: 51.623
    - type: ndcg_at_10
      value: 56.355999999999995
    - type: ndcg_at_20
      value: 58.757000000000005
    - type: ndcg_at_100
      value: 59.789
    - type: ndcg_at_1000
      value: 59.857000000000006
    - type: map_at_1
      value: 31.791999999999998
    - type: map_at_3
      value: 42.757
    - type: map_at_5
      value: 45.634
    - type: map_at_10
      value: 47.599000000000004
    - type: map_at_20
      value: 48.271
    - type: map_at_100
      value: 48.425000000000004
    - type: map_at_1000
      value: 48.427
    - type: recall_at_1
      value: 31.791999999999998
    - type: recall_at_3
      value: 57.18299999999999
    - type: recall_at_5
      value: 69.70100000000001
    - type: recall_at_10
      value: 84.282
    - type: recall_at_20
      value: 93.67
    - type: recall_at_100
      value: 99.075
    - type: recall_at_1000
      value: 99.644
    - type: precision_at_1
      value: 31.791999999999998
    - type: precision_at_3
      value: 19.061
    - type: precision_at_5
      value: 13.94
    - type: precision_at_10
      value: 8.427999999999999
    - type: precision_at_20
      value: 4.683
    - type: precision_at_100
      value: 0.991
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 32.3613
    - type: mrr_at_3
      value: 42.935
    - type: mrr_at_5
      value: 45.844
    - type: mrr_at_10
      value: 47.808099999999996
    - type: mrr_at_20
      value: 48.4844
    - type: mrr_at_100
      value: 48.6345
    - type: mrr_at_1000
      value: 48.6364
    - type: nauc_ndcg_at_1_max
      value: -8.274099999999999
    - type: nauc_ndcg_at_1_std
      value: -8.1976
    - type: nauc_ndcg_at_1_diff1
      value: 14.155100000000001
    - type: nauc_ndcg_at_3_max
      value: -4.6223
    - type: nauc_ndcg_at_3_std
      value: -10.198500000000001
    - type: nauc_ndcg_at_3_diff1
      value: 14.516499999999999
    - type: nauc_ndcg_at_5_max
      value: -4.9834000000000005
    - type: nauc_ndcg_at_5_std
      value: -9.6634
    - type: nauc_ndcg_at_5_diff1
      value: 12.9298
    - type: nauc_ndcg_at_10_max
      value: -4.3251
    - type: nauc_ndcg_at_10_std
      value: -8.3068
    - type: nauc_ndcg_at_10_diff1
      value: 12.2939
    - type: nauc_ndcg_at_20_max
      value: -3.8912000000000004
    - type: nauc_ndcg_at_20_std
      value: -8.1821
    - type: nauc_ndcg_at_20_diff1
      value: 12.673599999999999
    - type: nauc_ndcg_at_100_max
      value: -5.0274
    - type: nauc_ndcg_at_100_std
      value: -8.450000000000001
    - type: nauc_ndcg_at_100_diff1
      value: 12.787399999999998
    - type: nauc_ndcg_at_1000_max
      value: -5.1416
    - type: nauc_ndcg_at_1000_std
      value: -8.6044
    - type: nauc_ndcg_at_1000_diff1
      value: 12.858600000000001
    - type: nauc_map_at_1_max
      value: -8.274099999999999
    - type: nauc_map_at_1_std
      value: -8.1976
    - type: nauc_map_at_1_diff1
      value: 14.155100000000001
    - type: nauc_map_at_3_max
      value: -5.6403
    - type: nauc_map_at_3_std
      value: -9.7092
    - type: nauc_map_at_3_diff1
      value: 14.0705
    - type: nauc_map_at_5_max
      value: -5.8896999999999995
    - type: nauc_map_at_5_std
      value: -9.3946
    - type: nauc_map_at_5_diff1
      value: 13.208
    - type: nauc_map_at_10_max
      value: -5.7523
    - type: nauc_map_at_10_std
      value: -8.9262
    - type: nauc_map_at_10_diff1
      value: 12.961500000000001
    - type: nauc_map_at_20_max
      value: -5.7103
    - type: nauc_map_at_20_std
      value: -8.9336
    - type: nauc_map_at_20_diff1
      value: 13.0351
    - type: nauc_map_at_100_max
      value: -5.8204
    - type: nauc_map_at_100_std
      value: -8.9441
    - type: nauc_map_at_100_diff1
      value: 13.0722
    - type: nauc_map_at_1000_max
      value: -5.8239
    - type: nauc_map_at_1000_std
      value: -8.9463
    - type: nauc_map_at_1000_diff1
      value: 13.0724
    - type: nauc_recall_at_1_max
      value: -8.274099999999999
    - type: nauc_recall_at_1_std
      value: -8.1976
    - type: nauc_recall_at_1_diff1
      value: 14.155100000000001
    - type: nauc_recall_at_3_max
      value: -1.4792
    - type: nauc_recall_at_3_std
      value: -11.6828
    - type: nauc_recall_at_3_diff1
      value: 16.026
    - type: nauc_recall_at_5_max
      value: -1.6868999999999998
    - type: nauc_recall_at_5_std
      value: -10.5497
    - type: nauc_recall_at_5_diff1
      value: 11.826
    - type: nauc_recall_at_10_max
      value: 5.1425
    - type: nauc_recall_at_10_std
      value: -3.1008999999999998
    - type: nauc_recall_at_10_diff1
      value: 7.6911
    - type: nauc_recall_at_20_max
      value: 25.921499999999998
    - type: nauc_recall_at_20_std
      value: 6.812600000000001
    - type: nauc_recall_at_20_diff1
      value: 8.311300000000001
    - type: nauc_recall_at_100_max
      value: 28.425299999999996
    - type: nauc_recall_at_100_std
      value: 45.9592
    - type: nauc_recall_at_100_diff1
      value: -11.801
    - type: nauc_recall_at_1000_max
      value: 21.834500000000002
    - type: nauc_recall_at_1000_std
      value: 38.804
    - type: nauc_recall_at_1000_diff1
      value: -3.5484
    - type: nauc_precision_at_1_max
      value: -8.274099999999999
    - type: nauc_precision_at_1_std
      value: -8.1976
    - type: nauc_precision_at_1_diff1
      value: 14.155100000000001
    - type: nauc_precision_at_3_max
      value: -1.4792
    - type: nauc_precision_at_3_std
      value: -11.6828
    - type: nauc_precision_at_3_diff1
      value: 16.026
    - type: nauc_precision_at_5_max
      value: -1.6868999999999998
    - type: nauc_precision_at_5_std
      value: -10.5497
    - type: nauc_precision_at_5_diff1
      value: 11.826
    - type: nauc_precision_at_10_max
      value: 5.1425
    - type: nauc_precision_at_10_std
      value: -3.1008999999999998
    - type: nauc_precision_at_10_diff1
      value: 7.6911
    - type: nauc_precision_at_20_max
      value: 25.921499999999998
    - type: nauc_precision_at_20_std
      value: 6.812600000000001
    - type: nauc_precision_at_20_diff1
      value: 8.311300000000001
    - type: nauc_precision_at_100_max
      value: 28.425299999999996
    - type: nauc_precision_at_100_std
      value: 45.9592
    - type: nauc_precision_at_100_diff1
      value: -11.801
    - type: nauc_precision_at_1000_max
      value: 21.834500000000002
    - type: nauc_precision_at_1000_std
      value: 38.804
    - type: nauc_precision_at_1000_diff1
      value: -3.5484
    - type: nauc_mrr_at_1_max
      value: -8.6929
    - type: nauc_mrr_at_1_std
      value: -7.7584
    - type: nauc_mrr_at_1_diff1
      value: 12.488100000000001
    - type: nauc_mrr_at_3_max
      value: -6.6954
    - type: nauc_mrr_at_3_std
      value: -9.7075
    - type: nauc_mrr_at_3_diff1
      value: 12.2994
    - type: nauc_mrr_at_5_max
      value: -6.7945
    - type: nauc_mrr_at_5_std
      value: -9.3751
    - type: nauc_mrr_at_5_diff1
      value: 11.544699999999999
    - type: nauc_mrr_at_10_max
      value: -6.6614
    - type: nauc_mrr_at_10_std
      value: -8.859200000000001
    - type: nauc_mrr_at_10_diff1
      value: 11.2614
    - type: nauc_mrr_at_20_max
      value: -6.6408
    - type: nauc_mrr_at_20_std
      value: -8.8599
    - type: nauc_mrr_at_20_diff1
      value: 11.3125
    - type: nauc_mrr_at_100_max
      value: -6.7582
    - type: nauc_mrr_at_100_std
      value: -8.876299999999999
    - type: nauc_mrr_at_100_diff1
      value: 11.325000000000001
    - type: nauc_mrr_at_1000_max
      value: -6.7619
    - type: nauc_mrr_at_1000_std
      value: -8.878400000000001
    - type: nauc_mrr_at_1000_diff1
      value: 11.3251
    - type: main_score
      value: 56.355999999999995
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB ArxivClusteringP2P (default)
      revision: a122ad7f3f0291bf49cc6f4d32aa80929df69d5d
      split: test
      type: mteb/arxiv-clustering-p2p
    metrics:
    - type: v_measure
      value: 46.813
    - type: v_measure_std
      value: 13.830899999999998
    - type: main_score
      value: 46.813
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB ArxivClusteringS2S (default)
      revision: f910caf1a6075f7329cdf8c1a6135696f37dbd53
      split: test
      type: mteb/arxiv-clustering-s2s
    metrics:
    - type: v_measure
      value: 41.9895
    - type: v_measure_std
      value: 14.3004
    - type: main_score
      value: 41.9895
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB AskUbuntuDupQuestions (default)
      revision: 2000358ca161889fa9c082cb41daa8dcfb161a54
      split: test
      type: mteb/askubuntudupquestions-reranking
    metrics:
    - type: map
      value: 64.1329
    - type: mrr
      value: 76.8303
    - type: nAUC_map_max
      value: 23.5323
    - type: nAUC_map_std
      value: 14.7567
    - type: nAUC_map_diff1
      value: 11.6783
    - type: nAUC_mrr_max
      value: 32.3309
    - type: nAUC_mrr_std
      value: 19.1617
    - type: nAUC_mrr_diff1
      value: 23.508699999999997
    - type: main_score
      value: 64.1329
    task:
      type: Reranking
  - dataset:
      config: default
      name: MTEB BIOSSES (default)
      revision: d3fb88f8f02e40887cd149695127462bbcf29b4a
      split: test
      type: mteb/biosses-sts
    metrics:
    - type: pearson
      value: 90.2058
    - type: spearman
      value: 88.1641
    - type: cosine_pearson
      value: 90.2058
    - type: cosine_spearman
      value: 88.1641
    - type: manhattan_pearson
      value: 87.7579
    - type: manhattan_spearman
      value: 87.6249
    - type: euclidean_pearson
      value: 88.3667
    - type: euclidean_spearman
      value: 88.1641
    - type: main_score
      value: 88.1641
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB Banking77Classification (default)
      revision: 0fd18e25b25c072e09e0d92ab615fda904d66300
      split: test
      type: mteb/banking77
    metrics:
    - type: accuracy
      value: 77.3247
    - type: f1
      value: 76.3532
    - type: f1_weighted
      value: 76.3532
    - type: main_score
      value: 77.3247
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB BiorxivClusteringP2P (default)
      revision: 65b79d1d13f80053f67aca9498d9402c2d9f1f40
      split: test
      type: mteb/biorxiv-clustering-p2p
    metrics:
    - type: v_measure
      value: 39.018
    - type: v_measure_std
      value: 0.7512
    - type: main_score
      value: 39.018
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB BiorxivClusteringS2S (default)
      revision: 258694dd0231531bc1fd9de6ceb52a0853c6d908
      split: test
      type: mteb/biorxiv-clustering-s2s
    metrics:
    - type: v_measure
      value: 36.8097
    - type: v_measure_std
      value: 0.9368
    - type: main_score
      value: 36.8097
    task:
      type: Clustering
  - dataset:
      config: python
      name: MTEB COIRCodeSearchNetRetrieval (python)
      revision: 4adc7bc41202b5c13543c9c886a25f340634dab3
      split: test
      type: CoIR-Retrieval/CodeSearchNet
    metrics:
    - type: ndcg_at_1
      value: 85.353
    - type: ndcg_at_3
      value: 89.493
    - type: ndcg_at_5
      value: 90.347
    - type: ndcg_at_10
      value: 90.89699999999999
    - type: ndcg_at_20
      value: 91.20899999999999
    - type: ndcg_at_100
      value: 91.506
    - type: ndcg_at_1000
      value: 91.62400000000001
    - type: map_at_1
      value: 85.353
    - type: map_at_3
      value: 88.532
    - type: map_at_5
      value: 89.008
    - type: map_at_10
      value: 89.238
    - type: map_at_20
      value: 89.323
    - type: map_at_100
      value: 89.366
    - type: map_at_1000
      value: 89.371
    - type: recall_at_1
      value: 85.353
    - type: recall_at_3
      value: 92.251
    - type: recall_at_5
      value: 94.316
    - type: recall_at_10
      value: 95.998
    - type: recall_at_20
      value: 97.238
    - type: recall_at_100
      value: 98.81400000000001
    - type: recall_at_1000
      value: 99.725
    - type: precision_at_1
      value: 85.353
    - type: precision_at_3
      value: 30.75
    - type: precision_at_5
      value: 18.863
    - type: precision_at_10
      value: 9.6
    - type: precision_at_20
      value: 4.862
    - type: precision_at_100
      value: 0.988
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 85.3533
    - type: mrr_at_3
      value: 88.5318
    - type: mrr_at_5
      value: 89.0077
    - type: mrr_at_10
      value: 89.2381
    - type: mrr_at_20
      value: 89.3231
    - type: mrr_at_100
      value: 89.3659
    - type: mrr_at_1000
      value: 89.3707
    - type: nauc_ndcg_at_1_max
      value: 79.05529999999999
    - type: nauc_ndcg_at_1_std
      value: 6.6982
    - type: nauc_ndcg_at_1_diff1
      value: 89.6212
    - type: nauc_ndcg_at_3_max
      value: 82.5612
    - type: nauc_ndcg_at_3_std
      value: 10.379199999999999
    - type: nauc_ndcg_at_3_diff1
      value: 87.809
    - type: nauc_ndcg_at_5_max
      value: 82.4315
    - type: nauc_ndcg_at_5_std
      value: 10.5113
    - type: nauc_ndcg_at_5_diff1
      value: 88.0763
    - type: nauc_ndcg_at_10_max
      value: 82.4135
    - type: nauc_ndcg_at_10_std
      value: 11.046
    - type: nauc_ndcg_at_10_diff1
      value: 88.2008
    - type: nauc_ndcg_at_20_max
      value: 82.3276
    - type: nauc_ndcg_at_20_std
      value: 11.4306
    - type: nauc_ndcg_at_20_diff1
      value: 88.2525
    - type: nauc_ndcg_at_100_max
      value: 82.1023
    - type: nauc_ndcg_at_100_std
      value: 11.2119
    - type: nauc_ndcg_at_100_diff1
      value: 88.3149
    - type: nauc_ndcg_at_1000_max
      value: 81.91720000000001
    - type: nauc_ndcg_at_1000_std
      value: 10.7203
    - type: nauc_ndcg_at_1000_diff1
      value: 88.349
    - type: nauc_map_at_1_max
      value: 79.05529999999999
    - type: nauc_map_at_1_std
      value: 6.6982
    - type: nauc_map_at_1_diff1
      value: 89.6212
    - type: nauc_map_at_3_max
      value: 81.5856
    - type: nauc_map_at_3_std
      value: 9.3626
    - type: nauc_map_at_3_diff1
      value: 88.2364
    - type: nauc_map_at_5_max
      value: 81.4778
    - type: nauc_map_at_5_std
      value: 9.3662
    - type: nauc_map_at_5_diff1
      value: 88.3865
    - type: nauc_map_at_10_max
      value: 81.447
    - type: nauc_map_at_10_std
      value: 9.5111
    - type: nauc_map_at_10_diff1
      value: 88.43469999999999
    - type: nauc_map_at_20_max
      value: 81.4196
    - type: nauc_map_at_20_std
      value: 9.593
    - type: nauc_map_at_20_diff1
      value: 88.4473
    - type: nauc_map_at_100_max
      value: 81.3925
    - type: nauc_map_at_100_std
      value: 9.5683
    - type: nauc_map_at_100_diff1
      value: 88.4559
    - type: nauc_map_at_1000_max
      value: 81.3865
    - type: nauc_map_at_1000_std
      value: 9.554
    - type: nauc_map_at_1000_diff1
      value: 88.457
    - type: nauc_recall_at_1_max
      value: 79.05529999999999
    - type: nauc_recall_at_1_std
      value: 6.6982
    - type: nauc_recall_at_1_diff1
      value: 89.6212
    - type: nauc_recall_at_3_max
      value: 86.56580000000001
    - type: nauc_recall_at_3_std
      value: 14.5464
    - type: nauc_recall_at_3_diff1
      value: 86.1047
    - type: nauc_recall_at_5_max
      value: 87.5044
    - type: nauc_recall_at_5_std
      value: 16.7155
    - type: nauc_recall_at_5_diff1
      value: 86.5603
    - type: nauc_recall_at_10_max
      value: 89.5625
    - type: nauc_recall_at_10_std
      value: 23.230700000000002
    - type: nauc_recall_at_10_diff1
      value: 86.8079
    - type: nauc_recall_at_20_max
      value: 91.7174
    - type: nauc_recall_at_20_std
      value: 33.203700000000005
    - type: nauc_recall_at_20_diff1
      value: 86.8468
    - type: nauc_recall_at_100_max
      value: 95.55160000000001
    - type: nauc_recall_at_100_std
      value: 53.0169
    - type: nauc_recall_at_100_diff1
      value: 87.1867
    - type: nauc_recall_at_1000_max
      value: 97.0907
    - type: nauc_recall_at_1000_std
      value: 75.0177
    - type: nauc_recall_at_1000_diff1
      value: 91.3005
    - type: nauc_precision_at_1_max
      value: 79.05529999999999
    - type: nauc_precision_at_1_std
      value: 6.6982
    - type: nauc_precision_at_1_diff1
      value: 89.6212
    - type: nauc_precision_at_3_max
      value: 86.56580000000001
    - type: nauc_precision_at_3_std
      value: 14.5464
    - type: nauc_precision_at_3_diff1
      value: 86.1047
    - type: nauc_precision_at_5_max
      value: 87.5044
    - type: nauc_precision_at_5_std
      value: 16.7155
    - type: nauc_precision_at_5_diff1
      value: 86.5603
    - type: nauc_precision_at_10_max
      value: 89.5625
    - type: nauc_precision_at_10_std
      value: 23.230700000000002
    - type: nauc_precision_at_10_diff1
      value: 86.8079
    - type: nauc_precision_at_20_max
      value: 91.7174
    - type: nauc_precision_at_20_std
      value: 33.203700000000005
    - type: nauc_precision_at_20_diff1
      value: 86.8468
    - type: nauc_precision_at_100_max
      value: 95.55160000000001
    - type: nauc_precision_at_100_std
      value: 53.0169
    - type: nauc_precision_at_100_diff1
      value: 87.1867
    - type: nauc_precision_at_1000_max
      value: 97.0907
    - type: nauc_precision_at_1000_std
      value: 75.0177
    - type: nauc_precision_at_1000_diff1
      value: 91.3005
    - type: nauc_mrr_at_1_max
      value: 79.05529999999999
    - type: nauc_mrr_at_1_std
      value: 6.6982
    - type: nauc_mrr_at_1_diff1
      value: 89.6212
    - type: nauc_mrr_at_3_max
      value: 81.5856
    - type: nauc_mrr_at_3_std
      value: 9.3626
    - type: nauc_mrr_at_3_diff1
      value: 88.2364
    - type: nauc_mrr_at_5_max
      value: 81.4778
    - type: nauc_mrr_at_5_std
      value: 9.3662
    - type: nauc_mrr_at_5_diff1
      value: 88.3865
    - type: nauc_mrr_at_10_max
      value: 81.447
    - type: nauc_mrr_at_10_std
      value: 9.5111
    - type: nauc_mrr_at_10_diff1
      value: 88.43469999999999
    - type: nauc_mrr_at_20_max
      value: 81.4196
    - type: nauc_mrr_at_20_std
      value: 9.593
    - type: nauc_mrr_at_20_diff1
      value: 88.4473
    - type: nauc_mrr_at_100_max
      value: 81.3925
    - type: nauc_mrr_at_100_std
      value: 9.5683
    - type: nauc_mrr_at_100_diff1
      value: 88.4559
    - type: nauc_mrr_at_1000_max
      value: 81.3865
    - type: nauc_mrr_at_1000_std
      value: 9.554
    - type: nauc_mrr_at_1000_diff1
      value: 88.457
    - type: main_score
      value: 90.89699999999999
    task:
      type: Retrieval
  - dataset:
      config: javascript
      name: MTEB COIRCodeSearchNetRetrieval (javascript)
      revision: 4adc7bc41202b5c13543c9c886a25f340634dab3
      split: test
      type: CoIR-Retrieval/CodeSearchNet
    metrics:
    - type: ndcg_at_1
      value: 35.46
    - type: ndcg_at_3
      value: 42.799
    - type: ndcg_at_5
      value: 44.64
    - type: ndcg_at_10
      value: 46.54
    - type: ndcg_at_20
      value: 48.025
    - type: ndcg_at_100
      value: 50.307
    - type: ndcg_at_1000
      value: 51.925
    - type: map_at_1
      value: 35.46
    - type: map_at_3
      value: 41.016000000000005
    - type: map_at_5
      value: 42.038
    - type: map_at_10
      value: 42.825
    - type: map_at_20
      value: 43.233
    - type: map_at_100
      value: 43.541999999999994
    - type: map_at_1000
      value: 43.599
    - type: recall_at_1
      value: 35.46
    - type: recall_at_3
      value: 47.949000000000005
    - type: recall_at_5
      value: 52.416
    - type: recall_at_10
      value: 58.28
    - type: recall_at_20
      value: 64.145
    - type: recall_at_100
      value: 76.542
    - type: recall_at_1000
      value: 89.547
    - type: precision_at_1
      value: 35.46
    - type: precision_at_3
      value: 15.983
    - type: precision_at_5
      value: 10.483
    - type: precision_at_10
      value: 5.827999999999999
    - type: precision_at_20
      value: 3.2070000000000003
    - type: precision_at_100
      value: 0.765
    - type: precision_at_1000
      value: 0.09
    - type: mrr_at_1
      value: 35.460300000000004
    - type: mrr_at_3
      value: 41.0159
    - type: mrr_at_5
      value: 42.038399999999996
    - type: mrr_at_10
      value: 42.8251
    - type: mrr_at_20
      value: 43.2333
    - type: mrr_at_100
      value: 43.542199999999994
    - type: mrr_at_1000
      value: 43.5986
    - type: nauc_ndcg_at_1_max
      value: 48.2915
    - type: nauc_ndcg_at_1_std
      value: 2.4132000000000002
    - type: nauc_ndcg_at_1_diff1
      value: 64.10810000000001
    - type: nauc_ndcg_at_3_max
      value: 51.357
    - type: nauc_ndcg_at_3_std
      value: 4.9681999999999995
    - type: nauc_ndcg_at_3_diff1
      value: 58.012600000000006
    - type: nauc_ndcg_at_5_max
      value: 51.8888
    - type: nauc_ndcg_at_5_std
      value: 6.2654000000000005
    - type: nauc_ndcg_at_5_diff1
      value: 57.103
    - type: nauc_ndcg_at_10_max
      value: 51.9571
    - type: nauc_ndcg_at_10_std
      value: 7.446
    - type: nauc_ndcg_at_10_diff1
      value: 56.505700000000004
    - type: nauc_ndcg_at_20_max
      value: 51.638799999999996
    - type: nauc_ndcg_at_20_std
      value: 7.7742
    - type: nauc_ndcg_at_20_diff1
      value: 55.9805
    - type: nauc_ndcg_at_100_max
      value: 51.3786
    - type: nauc_ndcg_at_100_std
      value: 8.1191
    - type: nauc_ndcg_at_100_diff1
      value: 56.3265
    - type: nauc_ndcg_at_1000_max
      value: 51.162
    - type: nauc_ndcg_at_1000_std
      value: 7.6863
    - type: nauc_ndcg_at_1000_diff1
      value: 56.6531
    - type: nauc_map_at_1_max
      value: 48.2915
    - type: nauc_map_at_1_std
      value: 2.4132000000000002
    - type: nauc_map_at_1_diff1
      value: 64.10810000000001
    - type: nauc_map_at_3_max
      value: 50.6599
    - type: nauc_map_at_3_std
      value: 4.3285
    - type: nauc_map_at_3_diff1
      value: 59.453100000000006
    - type: nauc_map_at_5_max
      value: 50.9502
    - type: nauc_map_at_5_std
      value: 5.0428
    - type: nauc_map_at_5_diff1
      value: 58.9452
    - type: nauc_map_at_10_max
      value: 50.9749
    - type: nauc_map_at_10_std
      value: 5.5069
    - type: nauc_map_at_10_diff1
      value: 58.7167
    - type: nauc_map_at_20_max
      value: 50.8815
    - type: nauc_map_at_20_std
      value: 5.5846
    - type: nauc_map_at_20_diff1
      value: 58.5793
    - type: nauc_map_at_100_max
      value: 50.8454
    - type: nauc_map_at_100_std
      value: 5.6249
    - type: nauc_map_at_100_diff1
      value: 58.6352
    - type: nauc_map_at_1000_max
      value: 50.8377
    - type: nauc_map_at_1000_std
      value: 5.6119
    - type: nauc_map_at_1000_diff1
      value: 58.6477
    - type: nauc_recall_at_1_max
      value: 48.2915
    - type: nauc_recall_at_1_std
      value: 2.4132000000000002
    - type: nauc_recall_at_1_diff1
      value: 64.10810000000001
    - type: nauc_recall_at_3_max
      value: 53.3613
    - type: nauc_recall_at_3_std
      value: 6.833699999999999
    - type: nauc_recall_at_3_diff1
      value: 53.8466
    - type: nauc_recall_at_5_max
      value: 54.7395
    - type: nauc_recall_at_5_std
      value: 10.1014
    - type: nauc_recall_at_5_diff1
      value: 51.520900000000005
    - type: nauc_recall_at_10_max
      value: 55.125299999999996
    - type: nauc_recall_at_10_std
      value: 14.277899999999999
    - type: nauc_recall_at_10_diff1
      value: 49.1874
    - type: nauc_recall_at_20_max
      value: 54.0194
    - type: nauc_recall_at_20_std
      value: 16.4329
    - type: nauc_recall_at_20_diff1
      value: 46.1551
    - type: nauc_recall_at_100_max
      value: 52.7898
    - type: nauc_recall_at_100_std
      value: 22.375600000000002
    - type: nauc_recall_at_100_diff1
      value: 45.351
    - type: nauc_recall_at_1000_max
      value: 49.0379
    - type: nauc_recall_at_1000_std
      value: 26.0579
    - type: nauc_recall_at_1000_diff1
      value: 41.7849
    - type: nauc_precision_at_1_max
      value: 48.2915
    - type: nauc_precision_at_1_std
      value: 2.4132000000000002
    - type: nauc_precision_at_1_diff1
      value: 64.10810000000001
    - type: nauc_precision_at_3_max
      value: 53.3613
    - type: nauc_precision_at_3_std
      value: 6.833699999999999
    - type: nauc_precision_at_3_diff1
      value: 53.8466
    - type: nauc_precision_at_5_max
      value: 54.7395
    - type: nauc_precision_at_5_std
      value: 10.1014
    - type: nauc_precision_at_5_diff1
      value: 51.520900000000005
    - type: nauc_precision_at_10_max
      value: 55.125299999999996
    - type: nauc_precision_at_10_std
      value: 14.277899999999999
    - type: nauc_precision_at_10_diff1
      value: 49.1874
    - type: nauc_precision_at_20_max
      value: 54.0194
    - type: nauc_precision_at_20_std
      value: 16.4329
    - type: nauc_precision_at_20_diff1
      value: 46.1551
    - type: nauc_precision_at_100_max
      value: 52.7898
    - type: nauc_precision_at_100_std
      value: 22.375600000000002
    - type: nauc_precision_at_100_diff1
      value: 45.351
    - type: nauc_precision_at_1000_max
      value: 49.0379
    - type: nauc_precision_at_1000_std
      value: 26.0579
    - type: nauc_precision_at_1000_diff1
      value: 41.7849
    - type: nauc_mrr_at_1_max
      value: 48.2915
    - type: nauc_mrr_at_1_std
      value: 2.4132000000000002
    - type: nauc_mrr_at_1_diff1
      value: 64.10810000000001
    - type: nauc_mrr_at_3_max
      value: 50.6599
    - type: nauc_mrr_at_3_std
      value: 4.3285
    - type: nauc_mrr_at_3_diff1
      value: 59.453100000000006
    - type: nauc_mrr_at_5_max
      value: 50.9502
    - type: nauc_mrr_at_5_std
      value: 5.0428
    - type: nauc_mrr_at_5_diff1
      value: 58.9452
    - type: nauc_mrr_at_10_max
      value: 50.9749
    - type: nauc_mrr_at_10_std
      value: 5.5069
    - type: nauc_mrr_at_10_diff1
      value: 58.7167
    - type: nauc_mrr_at_20_max
      value: 50.8815
    - type: nauc_mrr_at_20_std
      value: 5.5846
    - type: nauc_mrr_at_20_diff1
      value: 58.5793
    - type: nauc_mrr_at_100_max
      value: 50.8454
    - type: nauc_mrr_at_100_std
      value: 5.6249
    - type: nauc_mrr_at_100_diff1
      value: 58.6352
    - type: nauc_mrr_at_1000_max
      value: 50.8377
    - type: nauc_mrr_at_1000_std
      value: 5.6119
    - type: nauc_mrr_at_1000_diff1
      value: 58.6477
    - type: main_score
      value: 46.54
    task:
      type: Retrieval
  - dataset:
      config: go
      name: MTEB COIRCodeSearchNetRetrieval (go)
      revision: 4adc7bc41202b5c13543c9c886a25f340634dab3
      split: test
      type: CoIR-Retrieval/CodeSearchNet
    metrics:
    - type: ndcg_at_1
      value: 45.728
    - type: ndcg_at_3
      value: 54.942
    - type: ndcg_at_5
      value: 57.19499999999999
    - type: ndcg_at_10
      value: 59.471
    - type: ndcg_at_20
      value: 60.888
    - type: ndcg_at_100
      value: 62.67700000000001
    - type: ndcg_at_1000
      value: 63.654999999999994
    - type: map_at_1
      value: 45.728
    - type: map_at_3
      value: 52.717000000000006
    - type: map_at_5
      value: 53.968
    - type: map_at_10
      value: 54.921
    - type: map_at_20
      value: 55.31
    - type: map_at_100
      value: 55.555
    - type: map_at_1000
      value: 55.589999999999996
    - type: recall_at_1
      value: 45.728
    - type: recall_at_3
      value: 61.364
    - type: recall_at_5
      value: 66.83099999999999
    - type: recall_at_10
      value: 73.8
    - type: recall_at_20
      value: 79.402
    - type: recall_at_100
      value: 89.079
    - type: recall_at_1000
      value: 96.885
    - type: precision_at_1
      value: 45.728
    - type: precision_at_3
      value: 20.455000000000002
    - type: precision_at_5
      value: 13.366
    - type: precision_at_10
      value: 7.380000000000001
    - type: precision_at_20
      value: 3.9699999999999998
    - type: precision_at_100
      value: 0.8909999999999999
    - type: precision_at_1000
      value: 0.097
    - type: mrr_at_1
      value: 45.7277
    - type: mrr_at_3
      value: 52.7169
    - type: mrr_at_5
      value: 53.9678
    - type: mrr_at_10
      value: 54.920500000000004
    - type: mrr_at_20
      value: 55.3099
    - type: mrr_at_100
      value: 55.5546
    - type: mrr_at_1000
      value: 55.5896
    - type: nauc_ndcg_at_1_max
      value: 40.5391
    - type: nauc_ndcg_at_1_std
      value: -2.9052000000000002
    - type: nauc_ndcg_at_1_diff1
      value: 63.2351
    - type: nauc_ndcg_at_3_max
      value: 43.8365
    - type: nauc_ndcg_at_3_std
      value: -0.6831
    - type: nauc_ndcg_at_3_diff1
      value: 57.782599999999995
    - type: nauc_ndcg_at_5_max
      value: 43.851600000000005
    - type: nauc_ndcg_at_5_std
      value: -0.3032
    - type: nauc_ndcg_at_5_diff1
      value: 57.0763
    - type: nauc_ndcg_at_10_max
      value: 44.1492
    - type: nauc_ndcg_at_10_std
      value: 0.6748
    - type: nauc_ndcg_at_10_diff1
      value: 56.8967
    - type: nauc_ndcg_at_20_max
      value: 44.1367
    - type: nauc_ndcg_at_20_std
      value: 0.8896
    - type: nauc_ndcg_at_20_diff1
      value: 56.97560000000001
    - type: nauc_ndcg_at_100_max
      value: 43.9934
    - type: nauc_ndcg_at_100_std
      value: 1.0534
    - type: nauc_ndcg_at_100_diff1
      value: 57.347899999999996
    - type: nauc_ndcg_at_1000_max
      value: 43.8679
    - type: nauc_ndcg_at_1000_std
      value: 0.6431
    - type: nauc_ndcg_at_1000_diff1
      value: 57.6967
    - type: nauc_map_at_1_max
      value: 40.5391
    - type: nauc_map_at_1_std
      value: -2.9052000000000002
    - type: nauc_map_at_1_diff1
      value: 63.2351
    - type: nauc_map_at_3_max
      value: 43.0286
    - type: nauc_map_at_3_std
      value: -1.2933
    - type: nauc_map_at_3_diff1
      value: 59.065
    - type: nauc_map_at_5_max
      value: 43.0224
    - type: nauc_map_at_5_std
      value: -1.1081
    - type: nauc_map_at_5_diff1
      value: 58.7146
    - type: nauc_map_at_10_max
      value: 43.127500000000005
    - type: nauc_map_at_10_std
      value: -0.7247
    - type: nauc_map_at_10_diff1
      value: 58.6619
    - type: nauc_map_at_20_max
      value: 43.1213
    - type: nauc_map_at_20_std
      value: -0.6853
    - type: nauc_map_at_20_diff1
      value: 58.704299999999996
    - type: nauc_map_at_100_max
      value: 43.0908
    - type: nauc_map_at_100_std
      value: -0.6792
    - type: nauc_map_at_100_diff1
      value: 58.7592
    - type: nauc_map_at_1000_max
      value: 43.085499999999996
    - type: nauc_map_at_1000_std
      value: -0.6897
    - type: nauc_map_at_1000_diff1
      value: 58.7689
    - type: nauc_recall_at_1_max
      value: 40.5391
    - type: nauc_recall_at_1_std
      value: -2.9052000000000002
    - type: nauc_recall_at_1_diff1
      value: 63.2351
    - type: nauc_recall_at_3_max
      value: 46.3617
    - type: nauc_recall_at_3_std
      value: 1.2550999999999999
    - type: nauc_recall_at_3_diff1
      value: 53.7993
    - type: nauc_recall_at_5_max
      value: 46.6666
    - type: nauc_recall_at_5_std
      value: 2.5401
    - type: nauc_recall_at_5_diff1
      value: 51.413799999999995
    - type: nauc_recall_at_10_max
      value: 48.3645
    - type: nauc_recall_at_10_std
      value: 6.8622000000000005
    - type: nauc_recall_at_10_diff1
      value: 49.6971
    - type: nauc_recall_at_20_max
      value: 49.1074
    - type: nauc_recall_at_20_std
      value: 9.4846
    - type: nauc_recall_at_20_diff1
      value: 48.5587
    - type: nauc_recall_at_100_max
      value: 51.2638
    - type: nauc_recall_at_100_std
      value: 18.4911
    - type: nauc_recall_at_100_diff1
      value: 47.2445
    - type: nauc_recall_at_1000_max
      value: 61.0283
    - type: nauc_recall_at_1000_std
      value: 31.5949
    - type: nauc_recall_at_1000_diff1
      value: 47.239599999999996
    - type: nauc_precision_at_1_max
      value: 40.5391
    - type: nauc_precision_at_1_std
      value: -2.9052000000000002
    - type: nauc_precision_at_1_diff1
      value: 63.2351
    - type: nauc_precision_at_3_max
      value: 46.3617
    - type: nauc_precision_at_3_std
      value: 1.2550999999999999
    - type: nauc_precision_at_3_diff1
      value: 53.7993
    - type: nauc_precision_at_5_max
      value: 46.6666
    - type: nauc_precision_at_5_std
      value: 2.5401
    - type: nauc_precision_at_5_diff1
      value: 51.413799999999995
    - type: nauc_precision_at_10_max
      value: 48.3645
    - type: nauc_precision_at_10_std
      value: 6.8622000000000005
    - type: nauc_precision_at_10_diff1
      value: 49.6971
    - type: nauc_precision_at_20_max
      value: 49.1074
    - type: nauc_precision_at_20_std
      value: 9.4846
    - type: nauc_precision_at_20_diff1
      value: 48.5587
    - type: nauc_precision_at_100_max
      value: 51.2638
    - type: nauc_precision_at_100_std
      value: 18.4911
    - type: nauc_precision_at_100_diff1
      value: 47.2445
    - type: nauc_precision_at_1000_max
      value: 61.0283
    - type: nauc_precision_at_1000_std
      value: 31.5949
    - type: nauc_precision_at_1000_diff1
      value: 47.239599999999996
    - type: nauc_mrr_at_1_max
      value: 40.5391
    - type: nauc_mrr_at_1_std
      value: -2.9052000000000002
    - type: nauc_mrr_at_1_diff1
      value: 63.2351
    - type: nauc_mrr_at_3_max
      value: 43.0286
    - type: nauc_mrr_at_3_std
      value: -1.2933
    - type: nauc_mrr_at_3_diff1
      value: 59.065
    - type: nauc_mrr_at_5_max
      value: 43.0224
    - type: nauc_mrr_at_5_std
      value: -1.1081
    - type: nauc_mrr_at_5_diff1
      value: 58.7146
    - type: nauc_mrr_at_10_max
      value: 43.127500000000005
    - type: nauc_mrr_at_10_std
      value: -0.7247
    - type: nauc_mrr_at_10_diff1
      value: 58.6619
    - type: nauc_mrr_at_20_max
      value: 43.1213
    - type: nauc_mrr_at_20_std
      value: -0.6853
    - type: nauc_mrr_at_20_diff1
      value: 58.704299999999996
    - type: nauc_mrr_at_100_max
      value: 43.0908
    - type: nauc_mrr_at_100_std
      value: -0.6792
    - type: nauc_mrr_at_100_diff1
      value: 58.7592
    - type: nauc_mrr_at_1000_max
      value: 43.085499999999996
    - type: nauc_mrr_at_1000_std
      value: -0.6897
    - type: nauc_mrr_at_1000_diff1
      value: 58.7689
    - type: main_score
      value: 59.471
    task:
      type: Retrieval
  - dataset:
      config: ruby
      name: MTEB COIRCodeSearchNetRetrieval (ruby)
      revision: 4adc7bc41202b5c13543c9c886a25f340634dab3
      split: test
      type: CoIR-Retrieval/CodeSearchNet
    metrics:
    - type: ndcg_at_1
      value: 38.144
    - type: ndcg_at_3
      value: 46.086
    - type: ndcg_at_5
      value: 48.13
    - type: ndcg_at_10
      value: 50.166
    - type: ndcg_at_20
      value: 51.672
    - type: ndcg_at_100
      value: 53.81
    - type: ndcg_at_1000
      value: 55.401999999999994
    - type: map_at_1
      value: 38.144
    - type: map_at_3
      value: 44.118
    - type: map_at_5
      value: 45.245000000000005
    - type: map_at_10
      value: 46.061
    - type: map_at_20
      value: 46.475
    - type: map_at_100
      value: 46.761
    - type: map_at_1000
      value: 46.815
    - type: recall_at_1
      value: 38.144
    - type: recall_at_3
      value: 51.784
    - type: recall_at_5
      value: 56.779999999999994
    - type: recall_at_10
      value: 63.20400000000001
    - type: recall_at_20
      value: 69.151
    - type: recall_at_100
      value: 80.809
    - type: recall_at_1000
      value: 93.65599999999999
    - type: precision_at_1
      value: 38.144
    - type: precision_at_3
      value: 17.261000000000003
    - type: precision_at_5
      value: 11.356
    - type: precision_at_10
      value: 6.32
    - type: precision_at_20
      value: 3.458
    - type: precision_at_100
      value: 0.808
    - type: precision_at_1000
      value: 0.094
    - type: mrr_at_1
      value: 38.1443
    - type: mrr_at_3
      value: 44.1184
    - type: mrr_at_5
      value: 45.2445
    - type: mrr_at_10
      value: 46.0607
    - type: mrr_at_20
      value: 46.475
    - type: mrr_at_100
      value: 46.7611
    - type: mrr_at_1000
      value: 46.8146
    - type: nauc_ndcg_at_1_max
      value: 49.8526
    - type: nauc_ndcg_at_1_std
      value: 6.944500000000001
    - type: nauc_ndcg_at_1_diff1
      value: 59.0325
    - type: nauc_ndcg_at_3_max
      value: 48.8152
    - type: nauc_ndcg_at_3_std
      value: 6.2506
    - type: nauc_ndcg_at_3_diff1
      value: 51.7373
    - type: nauc_ndcg_at_5_max
      value: 48.4399
    - type: nauc_ndcg_at_5_std
      value: 6.687
    - type: nauc_ndcg_at_5_diff1
      value: 50.569900000000004
    - type: nauc_ndcg_at_10_max
      value: 47.2669
    - type: nauc_ndcg_at_10_std
      value: 6.703
    - type: nauc_ndcg_at_10_diff1
      value: 49.3867
    - type: nauc_ndcg_at_20_max
      value: 47.1761
    - type: nauc_ndcg_at_20_std
      value: 7.0552
    - type: nauc_ndcg_at_20_diff1
      value: 49.3528
    - type: nauc_ndcg_at_100_max
      value: 47.196
    - type: nauc_ndcg_at_100_std
      value: 7.697
    - type: nauc_ndcg_at_100_diff1
      value: 49.9359
    - type: nauc_ndcg_at_1000_max
      value: 47.4306
    - type: nauc_ndcg_at_1000_std
      value: 7.3536
    - type: nauc_ndcg_at_1000_diff1
      value: 50.365700000000004
    - type: nauc_map_at_1_max
      value: 49.8526
    - type: nauc_map_at_1_std
      value: 6.944500000000001
    - type: nauc_map_at_1_diff1
      value: 59.0325
    - type: nauc_map_at_3_max
      value: 48.932900000000004
    - type: nauc_map_at_3_std
      value: 6.285499999999999
    - type: nauc_map_at_3_diff1
      value: 53.4821
    - type: nauc_map_at_5_max
      value: 48.709799999999994
    - type: nauc_map_at_5_std
      value: 6.5305
    - type: nauc_map_at_5_diff1
      value: 52.8586
    - type: nauc_map_at_10_max
      value: 48.2504
    - type: nauc_map_at_10_std
      value: 6.535299999999999
    - type: nauc_map_at_10_diff1
      value: 52.410000000000004
    - type: nauc_map_at_20_max
      value: 48.2424
    - type: nauc_map_at_20_std
      value: 6.6425
    - type: nauc_map_at_20_diff1
      value: 52.4289
    - type: nauc_map_at_100_max
      value: 48.254999999999995
    - type: nauc_map_at_100_std
      value: 6.7272
    - type: nauc_map_at_100_diff1
      value: 52.517199999999995
    - type: nauc_map_at_1000_max
      value: 48.2618
    - type: nauc_map_at_1000_std
      value: 6.7179
    - type: nauc_map_at_1000_diff1
      value: 52.5296
    - type: nauc_recall_at_1_max
      value: 49.8526
    - type: nauc_recall_at_1_std
      value: 6.944500000000001
    - type: nauc_recall_at_1_diff1
      value: 59.0325
    - type: nauc_recall_at_3_max
      value: 48.5241
    - type: nauc_recall_at_3_std
      value: 6.2048
    - type: nauc_recall_at_3_diff1
      value: 46.5818
    - type: nauc_recall_at_5_max
      value: 47.6347
    - type: nauc_recall_at_5_std
      value: 7.290299999999999
    - type: nauc_recall_at_5_diff1
      value: 43.3392
    - type: nauc_recall_at_10_max
      value: 43.4268
    - type: nauc_recall_at_10_std
      value: 7.4028
    - type: nauc_recall_at_10_diff1
      value: 38.508700000000005
    - type: nauc_recall_at_20_max
      value: 42.416199999999996
    - type: nauc_recall_at_20_std
      value: 9.0454
    - type: nauc_recall_at_20_diff1
      value: 36.9086
    - type: nauc_recall_at_100_max
      value: 40.23
    - type: nauc_recall_at_100_std
      value: 15.776000000000002
    - type: nauc_recall_at_100_diff1
      value: 36.492599999999996
    - type: nauc_recall_at_1000_max
      value: 36.7611
    - type: nauc_recall_at_1000_std
      value: 16.9938
    - type: nauc_recall_at_1000_diff1
      value: 29.5398
    - type: nauc_precision_at_1_max
      value: 49.8526
    - type: nauc_precision_at_1_std
      value: 6.944500000000001
    - type: nauc_precision_at_1_diff1
      value: 59.0325
    - type: nauc_precision_at_3_max
      value: 48.5241
    - type: nauc_precision_at_3_std
      value: 6.2048
    - type: nauc_precision_at_3_diff1
      value: 46.5818
    - type: nauc_precision_at_5_max
      value: 47.6347
    - type: nauc_precision_at_5_std
      value: 7.290299999999999
    - type: nauc_precision_at_5_diff1
      value: 43.3392
    - type: nauc_precision_at_10_max
      value: 43.4268
    - type: nauc_precision_at_10_std
      value: 7.4028
    - type: nauc_precision_at_10_diff1
      value: 38.508700000000005
    - type: nauc_precision_at_20_max
      value: 42.416199999999996
    - type: nauc_precision_at_20_std
      value: 9.0454
    - type: nauc_precision_at_20_diff1
      value: 36.9086
    - type: nauc_precision_at_100_max
      value: 40.23
    - type: nauc_precision_at_100_std
      value: 15.776000000000002
    - type: nauc_precision_at_100_diff1
      value: 36.492599999999996
    - type: nauc_precision_at_1000_max
      value: 36.7611
    - type: nauc_precision_at_1000_std
      value: 16.9938
    - type: nauc_precision_at_1000_diff1
      value: 29.5398
    - type: nauc_mrr_at_1_max
      value: 49.8526
    - type: nauc_mrr_at_1_std
      value: 6.944500000000001
    - type: nauc_mrr_at_1_diff1
      value: 59.0325
    - type: nauc_mrr_at_3_max
      value: 48.932900000000004
    - type: nauc_mrr_at_3_std
      value: 6.285499999999999
    - type: nauc_mrr_at_3_diff1
      value: 53.4821
    - type: nauc_mrr_at_5_max
      value: 48.709799999999994
    - type: nauc_mrr_at_5_std
      value: 6.5305
    - type: nauc_mrr_at_5_diff1
      value: 52.8586
    - type: nauc_mrr_at_10_max
      value: 48.2504
    - type: nauc_mrr_at_10_std
      value: 6.535299999999999
    - type: nauc_mrr_at_10_diff1
      value: 52.410000000000004
    - type: nauc_mrr_at_20_max
      value: 48.2424
    - type: nauc_mrr_at_20_std
      value: 6.6425
    - type: nauc_mrr_at_20_diff1
      value: 52.4289
    - type: nauc_mrr_at_100_max
      value: 48.254999999999995
    - type: nauc_mrr_at_100_std
      value: 6.7272
    - type: nauc_mrr_at_100_diff1
      value: 52.517199999999995
    - type: nauc_mrr_at_1000_max
      value: 48.2618
    - type: nauc_mrr_at_1000_std
      value: 6.7179
    - type: nauc_mrr_at_1000_diff1
      value: 52.5296
    - type: main_score
      value: 50.166
    task:
      type: Retrieval
  - dataset:
      config: java
      name: MTEB COIRCodeSearchNetRetrieval (java)
      revision: 4adc7bc41202b5c13543c9c886a25f340634dab3
      split: test
      type: CoIR-Retrieval/CodeSearchNet
    metrics:
    - type: ndcg_at_1
      value: 42.355
    - type: ndcg_at_3
      value: 50.89
    - type: ndcg_at_5
      value: 53.089
    - type: ndcg_at_10
      value: 55.062
    - type: ndcg_at_20
      value: 56.373
    - type: ndcg_at_100
      value: 58.268
    - type: ndcg_at_1000
      value: 59.367999999999995
    - type: map_at_1
      value: 42.355
    - type: map_at_3
      value: 48.825
    - type: map_at_5
      value: 50.05
    - type: map_at_10
      value: 50.866
    - type: map_at_20
      value: 51.227999999999994
    - type: map_at_100
      value: 51.486
    - type: map_at_1000
      value: 51.525
    - type: recall_at_1
      value: 42.355
    - type: recall_at_3
      value: 56.851
    - type: recall_at_5
      value: 62.173
    - type: recall_at_10
      value: 68.26100000000001
    - type: recall_at_20
      value: 73.437
    - type: recall_at_100
      value: 83.706
    - type: recall_at_1000
      value: 92.506
    - type: precision_at_1
      value: 42.355
    - type: precision_at_3
      value: 18.95
    - type: precision_at_5
      value: 12.435
    - type: precision_at_10
      value: 6.8260000000000005
    - type: precision_at_20
      value: 3.672
    - type: precision_at_100
      value: 0.8370000000000001
    - type: precision_at_1000
      value: 0.093
    - type: mrr_at_1
      value: 42.3551
    - type: mrr_at_3
      value: 48.8255
    - type: mrr_at_5
      value: 50.049600000000005
    - type: mrr_at_10
      value: 50.8665
    - type: mrr_at_20
      value: 51.227999999999994
    - type: mrr_at_100
      value: 51.486
    - type: mrr_at_1000
      value: 51.525200000000005
    - type: nauc_ndcg_at_1_max
      value: 41.261700000000005
    - type: nauc_ndcg_at_1_std
      value: -4.1932
    - type: nauc_ndcg_at_1_diff1
      value: 62.1792
    - type: nauc_ndcg_at_3_max
      value: 43.6389
    - type: nauc_ndcg_at_3_std
      value: -2.7453000000000003
    - type: nauc_ndcg_at_3_diff1
      value: 56.621
    - type: nauc_ndcg_at_5_max
      value: 43.5895
    - type: nauc_ndcg_at_5_std
      value: -2.1214
    - type: nauc_ndcg_at_5_diff1
      value: 55.7216
    - type: nauc_ndcg_at_10_max
      value: 43.56
    - type: nauc_ndcg_at_10_std
      value: -1.2124
    - type: nauc_ndcg_at_10_diff1
      value: 55.1817
    - type: nauc_ndcg_at_20_max
      value: 43.6918
    - type: nauc_ndcg_at_20_std
      value: -0.4332
    - type: nauc_ndcg_at_20_diff1
      value: 54.9887
    - type: nauc_ndcg_at_100_max
      value: 43.945499999999996
    - type: nauc_ndcg_at_100_std
      value: 0.3674
    - type: nauc_ndcg_at_100_diff1
      value: 55.237899999999996
    - type: nauc_ndcg_at_1000_max
      value: 43.8498
    - type: nauc_ndcg_at_1000_std
      value: 0.1663
    - type: nauc_ndcg_at_1000_diff1
      value: 55.6509
    - type: nauc_map_at_1_max
      value: 41.261700000000005
    - type: nauc_map_at_1_std
      value: -4.1932
    - type: nauc_map_at_1_diff1
      value: 62.1792
    - type: nauc_map_at_3_max
      value: 43.0699
    - type: nauc_map_at_3_std
      value: -3.1619
    - type: nauc_map_at_3_diff1
      value: 57.961600000000004
    - type: nauc_map_at_5_max
      value: 43.0235
    - type: nauc_map_at_5_std
      value: -2.8471
    - type: nauc_map_at_5_diff1
      value: 57.492399999999996
    - type: nauc_map_at_10_max
      value: 43.0155
    - type: nauc_map_at_10_std
      value: -2.4906
    - type: nauc_map_at_10_diff1
      value: 57.308899999999994
    - type: nauc_map_at_20_max
      value: 43.0405
    - type: nauc_map_at_20_std
      value: -2.299
    - type: nauc_map_at_20_diff1
      value: 57.262
    - type: nauc_map_at_100_max
      value: 43.0606
    - type: nauc_map_at_100_std
      value: -2.2096
    - type: nauc_map_at_100_diff1
      value: 57.2982
    - type: nauc_map_at_1000_max
      value: 43.0566
    - type: nauc_map_at_1000_std
      value: -2.2155
    - type: nauc_map_at_1000_diff1
      value: 57.312
    - type: nauc_recall_at_1_max
      value: 41.261700000000005
    - type: nauc_recall_at_1_std
      value: -4.1932
    - type: nauc_recall_at_1_diff1
      value: 62.1792
    - type: nauc_recall_at_3_max
      value: 45.368199999999995
    - type: nauc_recall_at_3_std
      value: -1.4471
    - type: nauc_recall_at_3_diff1
      value: 52.5416
    - type: nauc_recall_at_5_max
      value: 45.421299999999995
    - type: nauc_recall_at_5_std
      value: 0.3829
    - type: nauc_recall_at_5_diff1
      value: 49.8591
    - type: nauc_recall_at_10_max
      value: 45.4698
    - type: nauc_recall_at_10_std
      value: 3.9899999999999998
    - type: nauc_recall_at_10_diff1
      value: 47.100500000000004
    - type: nauc_recall_at_20_max
      value: 46.4998
    - type: nauc_recall_at_20_std
      value: 8.8468
    - type: nauc_recall_at_20_diff1
      value: 45.027899999999995
    - type: nauc_recall_at_100_max
      value: 50.79559999999999
    - type: nauc_recall_at_100_std
      value: 21.8125
    - type: nauc_recall_at_100_diff1
      value: 42.735099999999996
    - type: nauc_recall_at_1000_max
      value: 55.116
    - type: nauc_recall_at_1000_std
      value: 37.5788
    - type: nauc_recall_at_1000_diff1
      value: 42.2857
    - type: nauc_precision_at_1_max
      value: 41.261700000000005
    - type: nauc_precision_at_1_std
      value: -4.1932
    - type: nauc_precision_at_1_diff1
      value: 62.1792
    - type: nauc_precision_at_3_max
      value: 45.368199999999995
    - type: nauc_precision_at_3_std
      value: -1.4471
    - type: nauc_precision_at_3_diff1
      value: 52.5416
    - type: nauc_precision_at_5_max
      value: 45.421299999999995
    - type: nauc_precision_at_5_std
      value: 0.3829
    - type: nauc_precision_at_5_diff1
      value: 49.8591
    - type: nauc_precision_at_10_max
      value: 45.4698
    - type: nauc_precision_at_10_std
      value: 3.9899999999999998
    - type: nauc_precision_at_10_diff1
      value: 47.100500000000004
    - type: nauc_precision_at_20_max
      value: 46.4998
    - type: nauc_precision_at_20_std
      value: 8.8468
    - type: nauc_precision_at_20_diff1
      value: 45.027899999999995
    - type: nauc_precision_at_100_max
      value: 50.79559999999999
    - type: nauc_precision_at_100_std
      value: 21.8125
    - type: nauc_precision_at_100_diff1
      value: 42.735099999999996
    - type: nauc_precision_at_1000_max
      value: 55.116
    - type: nauc_precision_at_1000_std
      value: 37.5788
    - type: nauc_precision_at_1000_diff1
      value: 42.2857
    - type: nauc_mrr_at_1_max
      value: 41.261700000000005
    - type: nauc_mrr_at_1_std
      value: -4.1932
    - type: nauc_mrr_at_1_diff1
      value: 62.1792
    - type: nauc_mrr_at_3_max
      value: 43.0699
    - type: nauc_mrr_at_3_std
      value: -3.1619
    - type: nauc_mrr_at_3_diff1
      value: 57.961600000000004
    - type: nauc_mrr_at_5_max
      value: 43.0235
    - type: nauc_mrr_at_5_std
      value: -2.8471
    - type: nauc_mrr_at_5_diff1
      value: 57.492399999999996
    - type: nauc_mrr_at_10_max
      value: 43.0155
    - type: nauc_mrr_at_10_std
      value: -2.4906
    - type: nauc_mrr_at_10_diff1
      value: 57.308899999999994
    - type: nauc_mrr_at_20_max
      value: 43.0405
    - type: nauc_mrr_at_20_std
      value: -2.299
    - type: nauc_mrr_at_20_diff1
      value: 57.262
    - type: nauc_mrr_at_100_max
      value: 43.0606
    - type: nauc_mrr_at_100_std
      value: -2.2096
    - type: nauc_mrr_at_100_diff1
      value: 57.2982
    - type: nauc_mrr_at_1000_max
      value: 43.0566
    - type: nauc_mrr_at_1000_std
      value: -2.2155
    - type: nauc_mrr_at_1000_diff1
      value: 57.312
    - type: main_score
      value: 55.062
    task:
      type: Retrieval
  - dataset:
      config: php
      name: MTEB COIRCodeSearchNetRetrieval (php)
      revision: 4adc7bc41202b5c13543c9c886a25f340634dab3
      split: test
      type: CoIR-Retrieval/CodeSearchNet
    metrics:
    - type: ndcg_at_1
      value: 36.835
    - type: ndcg_at_3
      value: 45.147999999999996
    - type: ndcg_at_5
      value: 47.497
    - type: ndcg_at_10
      value: 49.784
    - type: ndcg_at_20
      value: 51.410999999999994
    - type: ndcg_at_100
      value: 53.715
    - type: ndcg_at_1000
      value: 55.102
    - type: map_at_1
      value: 36.835
    - type: map_at_3
      value: 43.126
    - type: map_at_5
      value: 44.429
    - type: map_at_10
      value: 45.377
    - type: map_at_20
      value: 45.821
    - type: map_at_100
      value: 46.139
    - type: map_at_1000
      value: 46.188
    - type: recall_at_1
      value: 36.835
    - type: recall_at_3
      value: 50.992000000000004
    - type: recall_at_5
      value: 56.693000000000005
    - type: recall_at_10
      value: 63.743
    - type: recall_at_20
      value: 70.194
    - type: recall_at_100
      value: 82.65299999999999
    - type: recall_at_1000
      value: 93.728
    - type: precision_at_1
      value: 36.835
    - type: precision_at_3
      value: 16.997
    - type: precision_at_5
      value: 11.339
    - type: precision_at_10
      value: 6.3740000000000006
    - type: precision_at_20
      value: 3.51
    - type: precision_at_100
      value: 0.827
    - type: precision_at_1000
      value: 0.094
    - type: mrr_at_1
      value: 36.8346
    - type: mrr_at_3
      value: 43.1259
    - type: mrr_at_5
      value: 44.4289
    - type: mrr_at_10
      value: 45.3769
    - type: mrr_at_20
      value: 45.8215
    - type: mrr_at_100
      value: 46.138600000000004
    - type: mrr_at_1000
      value: 46.1881
    - type: nauc_ndcg_at_1_max
      value: 36.9844
    - type: nauc_ndcg_at_1_std
      value: -3.2222
    - type: nauc_ndcg_at_1_diff1
      value: 58.896
    - type: nauc_ndcg_at_3_max
      value: 37.6355
    - type: nauc_ndcg_at_3_std
      value: -2.2689
    - type: nauc_ndcg_at_3_diff1
      value: 52.771100000000004
    - type: nauc_ndcg_at_5_max
      value: 38.175599999999996
    - type: nauc_ndcg_at_5_std
      value: -1.5131999999999999
    - type: nauc_ndcg_at_5_diff1
      value: 52.0101
    - type: nauc_ndcg_at_10_max
      value: 38.2873
    - type: nauc_ndcg_at_10_std
      value: -0.5444
    - type: nauc_ndcg_at_10_diff1
      value: 51.3992
    - type: nauc_ndcg_at_20_max
      value: 38.324200000000005
    - type: nauc_ndcg_at_20_std
      value: 0.1328
    - type: nauc_ndcg_at_20_diff1
      value: 51.2346
    - type: nauc_ndcg_at_100_max
      value: 38.6313
    - type: nauc_ndcg_at_100_std
      value: 0.9426
    - type: nauc_ndcg_at_100_diff1
      value: 51.65729999999999
    - type: nauc_ndcg_at_1000_max
      value: 38.6274
    - type: nauc_ndcg_at_1000_std
      value: 0.69
    - type: nauc_ndcg_at_1000_diff1
      value: 52.1029
    - type: nauc_map_at_1_max
      value: 36.9844
    - type: nauc_map_at_1_std
      value: -3.2222
    - type: nauc_map_at_1_diff1
      value: 58.896
    - type: nauc_map_at_3_max
      value: 37.523
    - type: nauc_map_at_3_std
      value: -2.5115
    - type: nauc_map_at_3_diff1
      value: 54.17960000000001
    - type: nauc_map_at_5_max
      value: 37.8191
    - type: nauc_map_at_5_std
      value: -2.1073
    - type: nauc_map_at_5_diff1
      value: 53.780499999999996
    - type: nauc_map_at_10_max
      value: 37.8581
    - type: nauc_map_at_10_std
      value: -1.7191999999999998
    - type: nauc_map_at_10_diff1
      value: 53.541700000000006
    - type: nauc_map_at_20_max
      value: 37.8684
    - type: nauc_map_at_20_std
      value: -1.5565
    - type: nauc_map_at_20_diff1
      value: 53.5155
    - type: nauc_map_at_100_max
      value: 37.9101
    - type: nauc_map_at_100_std
      value: -1.4577
    - type: nauc_map_at_100_diff1
      value: 53.5894
    - type: nauc_map_at_1000_max
      value: 37.9109
    - type: nauc_map_at_1000_std
      value: -1.4617
    - type: nauc_map_at_1000_diff1
      value: 53.6044
    - type: nauc_recall_at_1_max
      value: 36.9844
    - type: nauc_recall_at_1_std
      value: -3.2222
    - type: nauc_recall_at_1_diff1
      value: 58.896
    - type: nauc_recall_at_3_max
      value: 37.9468
    - type: nauc_recall_at_3_std
      value: -1.5512
    - type: nauc_recall_at_3_diff1
      value: 48.6655
    - type: nauc_recall_at_5_max
      value: 39.3342
    - type: nauc_recall_at_5_std
      value: 0.44739999999999996
    - type: nauc_recall_at_5_diff1
      value: 46.475100000000005
    - type: nauc_recall_at_10_max
      value: 39.8619
    - type: nauc_recall_at_10_std
      value: 4.0042
    - type: nauc_recall_at_10_diff1
      value: 43.8251
    - type: nauc_recall_at_20_max
      value: 40.226299999999995
    - type: nauc_recall_at_20_std
      value: 8.052299999999999
    - type: nauc_recall_at_20_diff1
      value: 41.937400000000004
    - type: nauc_recall_at_100_max
      value: 44.221
    - type: nauc_recall_at_100_std
      value: 20.433699999999998
    - type: nauc_recall_at_100_diff1
      value: 40.745599999999996
    - type: nauc_recall_at_1000_max
      value: 52.6045
    - type: nauc_recall_at_1000_std
      value: 40.3497
    - type: nauc_recall_at_1000_diff1
      value: 40.248
    - type: nauc_precision_at_1_max
      value: 36.9844
    - type: nauc_precision_at_1_std
      value: -3.2222
    - type: nauc_precision_at_1_diff1
      value: 58.896
    - type: nauc_precision_at_3_max
      value: 37.9468
    - type: nauc_precision_at_3_std
      value: -1.5512
    - type: nauc_precision_at_3_diff1
      value: 48.6655
    - type: nauc_precision_at_5_max
      value: 39.3342
    - type: nauc_precision_at_5_std
      value: 0.44739999999999996
    - type: nauc_precision_at_5_diff1
      value: 46.475100000000005
    - type: nauc_precision_at_10_max
      value: 39.8619
    - type: nauc_precision_at_10_std
      value: 4.0042
    - type: nauc_precision_at_10_diff1
      value: 43.8251
    - type: nauc_precision_at_20_max
      value: 40.226299999999995
    - type: nauc_precision_at_20_std
      value: 8.052299999999999
    - type: nauc_precision_at_20_diff1
      value: 41.937400000000004
    - type: nauc_precision_at_100_max
      value: 44.221
    - type: nauc_precision_at_100_std
      value: 20.433699999999998
    - type: nauc_precision_at_100_diff1
      value: 40.745599999999996
    - type: nauc_precision_at_1000_max
      value: 52.6045
    - type: nauc_precision_at_1000_std
      value: 40.3497
    - type: nauc_precision_at_1000_diff1
      value: 40.248
    - type: nauc_mrr_at_1_max
      value: 36.9844
    - type: nauc_mrr_at_1_std
      value: -3.2222
    - type: nauc_mrr_at_1_diff1
      value: 58.896
    - type: nauc_mrr_at_3_max
      value: 37.523
    - type: nauc_mrr_at_3_std
      value: -2.5115
    - type: nauc_mrr_at_3_diff1
      value: 54.17960000000001
    - type: nauc_mrr_at_5_max
      value: 37.8191
    - type: nauc_mrr_at_5_std
      value: -2.1073
    - type: nauc_mrr_at_5_diff1
      value: 53.780499999999996
    - type: nauc_mrr_at_10_max
      value: 37.8581
    - type: nauc_mrr_at_10_std
      value: -1.7191999999999998
    - type: nauc_mrr_at_10_diff1
      value: 53.541700000000006
    - type: nauc_mrr_at_20_max
      value: 37.8684
    - type: nauc_mrr_at_20_std
      value: -1.5565
    - type: nauc_mrr_at_20_diff1
      value: 53.5155
    - type: nauc_mrr_at_100_max
      value: 37.9101
    - type: nauc_mrr_at_100_std
      value: -1.4577
    - type: nauc_mrr_at_100_diff1
      value: 53.5894
    - type: nauc_mrr_at_1000_max
      value: 37.9109
    - type: nauc_mrr_at_1000_std
      value: -1.4617
    - type: nauc_mrr_at_1000_diff1
      value: 53.6044
    - type: main_score
      value: 49.784
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackAndroidRetrieval (default)
      revision: f46a197baaae43b4f621051089b82a364682dfeb
      split: test
      type: mteb/cqadupstack-android
    metrics:
    - type: ndcg_at_1
      value: 44.206
    - type: ndcg_at_3
      value: 49.364999999999995
    - type: ndcg_at_5
      value: 51.429
    - type: ndcg_at_10
      value: 54.106
    - type: ndcg_at_20
      value: 56.271
    - type: ndcg_at_100
      value: 59.33500000000001
    - type: ndcg_at_1000
      value: 61.015
    - type: map_at_1
      value: 35.797000000000004
    - type: map_at_3
      value: 44.137
    - type: map_at_5
      value: 46.062999999999995
    - type: map_at_10
      value: 47.793
    - type: map_at_20
      value: 48.730000000000004
    - type: map_at_100
      value: 49.422
    - type: map_at_1000
      value: 49.546
    - type: recall_at_1
      value: 35.797000000000004
    - type: recall_at_3
      value: 51.224000000000004
    - type: recall_at_5
      value: 57.218999999999994
    - type: recall_at_10
      value: 65.182
    - type: recall_at_20
      value: 72.76700000000001
    - type: recall_at_100
      value: 86.654
    - type: recall_at_1000
      value: 97.131
    - type: precision_at_1
      value: 44.206
    - type: precision_at_3
      value: 23.653
    - type: precision_at_5
      value: 16.91
    - type: precision_at_10
      value: 10.443
    - type: precision_at_20
      value: 6.194999999999999
    - type: precision_at_100
      value: 1.6310000000000002
    - type: precision_at_1000
      value: 0.214
    - type: mrr_at_1
      value: 44.206
    - type: mrr_at_3
      value: 51.430600000000005
    - type: mrr_at_5
      value: 52.839800000000004
    - type: mrr_at_10
      value: 53.808
    - type: mrr_at_20
      value: 54.2585
    - type: mrr_at_100
      value: 54.540200000000006
    - type: mrr_at_1000
      value: 54.577799999999996
    - type: nauc_ndcg_at_1_max
      value: 45.573
    - type: nauc_ndcg_at_1_std
      value: -5.092300000000001
    - type: nauc_ndcg_at_1_diff1
      value: 50.8011
    - type: nauc_ndcg_at_3_max
      value: 44.7194
    - type: nauc_ndcg_at_3_std
      value: -2.979
    - type: nauc_ndcg_at_3_diff1
      value: 49.4014
    - type: nauc_ndcg_at_5_max
      value: 45.9838
    - type: nauc_ndcg_at_5_std
      value: -2.4417999999999997
    - type: nauc_ndcg_at_5_diff1
      value: 48.2985
    - type: nauc_ndcg_at_10_max
      value: 45.6755
    - type: nauc_ndcg_at_10_std
      value: -2.1826000000000003
    - type: nauc_ndcg_at_10_diff1
      value: 48.443799999999996
    - type: nauc_ndcg_at_20_max
      value: 45.967200000000005
    - type: nauc_ndcg_at_20_std
      value: -0.3553
    - type: nauc_ndcg_at_20_diff1
      value: 48.0216
    - type: nauc_ndcg_at_100_max
      value: 46.3459
    - type: nauc_ndcg_at_100_std
      value: 0.6947
    - type: nauc_ndcg_at_100_diff1
      value: 48.3313
    - type: nauc_ndcg_at_1000_max
      value: 46.245599999999996
    - type: nauc_ndcg_at_1000_std
      value: -0.3032
    - type: nauc_ndcg_at_1000_diff1
      value: 48.3821
    - type: nauc_map_at_1_max
      value: 38.896
    - type: nauc_map_at_1_std
      value: -5.7093
    - type: nauc_map_at_1_diff1
      value: 54.4608
    - type: nauc_map_at_3_max
      value: 42.6164
    - type: nauc_map_at_3_std
      value: -4.6751000000000005
    - type: nauc_map_at_3_diff1
      value: 52.23759999999999
    - type: nauc_map_at_5_max
      value: 43.9491
    - type: nauc_map_at_5_std
      value: -3.8674
    - type: nauc_map_at_5_diff1
      value: 51.03189999999999
    - type: nauc_map_at_10_max
      value: 44.4192
    - type: nauc_map_at_10_std
      value: -3.4564999999999997
    - type: nauc_map_at_10_diff1
      value: 50.6846
    - type: nauc_map_at_20_max
      value: 44.8404
    - type: nauc_map_at_20_std
      value: -2.67
    - type: nauc_map_at_20_diff1
      value: 50.3892
    - type: nauc_map_at_100_max
      value: 44.9988
    - type: nauc_map_at_100_std
      value: -2.4528000000000003
    - type: nauc_map_at_100_diff1
      value: 50.2602
    - type: nauc_map_at_1000_max
      value: 45.0043
    - type: nauc_map_at_1000_std
      value: -2.5084
    - type: nauc_map_at_1000_diff1
      value: 50.2302
    - type: nauc_recall_at_1_max
      value: 38.896
    - type: nauc_recall_at_1_std
      value: -5.7093
    - type: nauc_recall_at_1_diff1
      value: 54.4608
    - type: nauc_recall_at_3_max
      value: 40.917500000000004
    - type: nauc_recall_at_3_std
      value: -2.9875
    - type: nauc_recall_at_3_diff1
      value: 47.935
    - type: nauc_recall_at_5_max
      value: 43.578
    - type: nauc_recall_at_5_std
      value: -0.0832
    - type: nauc_recall_at_5_diff1
      value: 43.924800000000005
    - type: nauc_recall_at_10_max
      value: 42.3348
    - type: nauc_recall_at_10_std
      value: 1.2774
    - type: nauc_recall_at_10_diff1
      value: 42.5842
    - type: nauc_recall_at_20_max
      value: 43.4429
    - type: nauc_recall_at_20_std
      value: 9.6387
    - type: nauc_recall_at_20_diff1
      value: 40.1222
    - type: nauc_recall_at_100_max
      value: 47.6245
    - type: nauc_recall_at_100_std
      value: 28.7436
    - type: nauc_recall_at_100_diff1
      value: 42.3728
    - type: nauc_recall_at_1000_max
      value: 57.4835
    - type: nauc_recall_at_1000_std
      value: 66.6109
    - type: nauc_recall_at_1000_diff1
      value: 48.025
    - type: nauc_precision_at_1_max
      value: 45.573
    - type: nauc_precision_at_1_std
      value: -5.092300000000001
    - type: nauc_precision_at_1_diff1
      value: 50.8011
    - type: nauc_precision_at_3_max
      value: 39.7982
    - type: nauc_precision_at_3_std
      value: 1.3032
    - type: nauc_precision_at_3_diff1
      value: 26.422600000000003
    - type: nauc_precision_at_5_max
      value: 36.86
    - type: nauc_precision_at_5_std
      value: 3.9888
    - type: nauc_precision_at_5_diff1
      value: 13.4191
    - type: nauc_precision_at_10_max
      value: 26.663199999999996
    - type: nauc_precision_at_10_std
      value: 6.388299999999999
    - type: nauc_precision_at_10_diff1
      value: 2.1197
    - type: nauc_precision_at_20_max
      value: 19.8196
    - type: nauc_precision_at_20_std
      value: 9.0818
    - type: nauc_precision_at_20_diff1
      value: -6.483999999999999
    - type: nauc_precision_at_100_max
      value: 5.6951
    - type: nauc_precision_at_100_std
      value: 5.3285
    - type: nauc_precision_at_100_diff1
      value: -17.9036
    - type: nauc_precision_at_1000_max
      value: -9.107999999999999
    - type: nauc_precision_at_1000_std
      value: -7.5626999999999995
    - type: nauc_precision_at_1000_diff1
      value: -27.7189
    - type: nauc_mrr_at_1_max
      value: 45.573
    - type: nauc_mrr_at_1_std
      value: -5.092300000000001
    - type: nauc_mrr_at_1_diff1
      value: 50.8011
    - type: nauc_mrr_at_3_max
      value: 46.394800000000004
    - type: nauc_mrr_at_3_std
      value: -3.6457
    - type: nauc_mrr_at_3_diff1
      value: 48.8878
    - type: nauc_mrr_at_5_max
      value: 46.7342
    - type: nauc_mrr_at_5_std
      value: -3.2079999999999997
    - type: nauc_mrr_at_5_diff1
      value: 47.9827
    - type: nauc_mrr_at_10_max
      value: 46.4047
    - type: nauc_mrr_at_10_std
      value: -2.9571
    - type: nauc_mrr_at_10_diff1
      value: 48.036
    - type: nauc_mrr_at_20_max
      value: 46.3645
    - type: nauc_mrr_at_20_std
      value: -2.6208
    - type: nauc_mrr_at_20_diff1
      value: 48.030699999999996
    - type: nauc_mrr_at_100_max
      value: 46.3951
    - type: nauc_mrr_at_100_std
      value: -2.693
    - type: nauc_mrr_at_100_diff1
      value: 48.128
    - type: nauc_mrr_at_1000_max
      value: 46.403299999999994
    - type: nauc_mrr_at_1000_std
      value: -2.7043999999999997
    - type: nauc_mrr_at_1000_diff1
      value: 48.1413
    - type: main_score
      value: 54.106
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackEnglishRetrieval (default)
      revision: ad9991cb51e31e31e430383c75ffb2885547b5f0
      split: test
      type: mteb/cqadupstack-english
    metrics:
    - type: ndcg_at_1
      value: 41.274
    - type: ndcg_at_3
      value: 46.022999999999996
    - type: ndcg_at_5
      value: 47.882999999999996
    - type: ndcg_at_10
      value: 50.251000000000005
    - type: ndcg_at_20
      value: 51.93
    - type: ndcg_at_100
      value: 54.725
    - type: ndcg_at_1000
      value: 56.635000000000005
    - type: map_at_1
      value: 32.748
    - type: map_at_3
      value: 40.916000000000004
    - type: map_at_5
      value: 42.620999999999995
    - type: map_at_10
      value: 44.138
    - type: map_at_20
      value: 44.911
    - type: map_at_100
      value: 45.565
    - type: map_at_1000
      value: 45.698
    - type: recall_at_1
      value: 32.748
    - type: recall_at_3
      value: 47.522999999999996
    - type: recall_at_5
      value: 52.957
    - type: recall_at_10
      value: 60.321999999999996
    - type: recall_at_20
      value: 66.506
    - type: recall_at_100
      value: 79.669
    - type: recall_at_1000
      value: 91.73
    - type: precision_at_1
      value: 41.274
    - type: precision_at_3
      value: 22.718
    - type: precision_at_5
      value: 16.064
    - type: precision_at_10
      value: 9.828000000000001
    - type: precision_at_20
      value: 5.783
    - type: precision_at_100
      value: 1.5730000000000002
    - type: precision_at_1000
      value: 0.202
    - type: mrr_at_1
      value: 41.273900000000005
    - type: mrr_at_3
      value: 48.2378
    - type: mrr_at_5
      value: 49.5626
    - type: mrr_at_10
      value: 50.459900000000005
    - type: mrr_at_20
      value: 50.805
    - type: mrr_at_100
      value: 51.069900000000004
    - type: mrr_at_1000
      value: 51.1088
    - type: nauc_ndcg_at_1_max
      value: 44.7657
    - type: nauc_ndcg_at_1_std
      value: 3.7028
    - type: nauc_ndcg_at_1_diff1
      value: 52.017199999999995
    - type: nauc_ndcg_at_3_max
      value: 45.2602
    - type: nauc_ndcg_at_3_std
      value: 3.9891
    - type: nauc_ndcg_at_3_diff1
      value: 48.9746
    - type: nauc_ndcg_at_5_max
      value: 45.0766
    - type: nauc_ndcg_at_5_std
      value: 4.1764
    - type: nauc_ndcg_at_5_diff1
      value: 48.5708
    - type: nauc_ndcg_at_10_max
      value: 45.0325
    - type: nauc_ndcg_at_10_std
      value: 4.8281
    - type: nauc_ndcg_at_10_diff1
      value: 47.6424
    - type: nauc_ndcg_at_20_max
      value: 45.2904
    - type: nauc_ndcg_at_20_std
      value: 5.739
    - type: nauc_ndcg_at_20_diff1
      value: 47.7781
    - type: nauc_ndcg_at_100_max
      value: 45.6547
    - type: nauc_ndcg_at_100_std
      value: 7.6744
    - type: nauc_ndcg_at_100_diff1
      value: 47.2483
    - type: nauc_ndcg_at_1000_max
      value: 45.5879
    - type: nauc_ndcg_at_1000_std
      value: 7.919
    - type: nauc_ndcg_at_1000_diff1
      value: 47.172799999999995
    - type: nauc_map_at_1_max
      value: 35.7481
    - type: nauc_map_at_1_std
      value: -6.451
    - type: nauc_map_at_1_diff1
      value: 55.3994
    - type: nauc_map_at_3_max
      value: 41.4679
    - type: nauc_map_at_3_std
      value: -2.2265
    - type: nauc_map_at_3_diff1
      value: 51.9234
    - type: nauc_map_at_5_max
      value: 42.2532
    - type: nauc_map_at_5_std
      value: -0.9950000000000001
    - type: nauc_map_at_5_diff1
      value: 51.172200000000004
    - type: nauc_map_at_10_max
      value: 43.0496
    - type: nauc_map_at_10_std
      value: 0.3319
    - type: nauc_map_at_10_diff1
      value: 50.3961
    - type: nauc_map_at_20_max
      value: 43.6286
    - type: nauc_map_at_20_std
      value: 1.2991000000000001
    - type: nauc_map_at_20_diff1
      value: 50.2938
    - type: nauc_map_at_100_max
      value: 43.906800000000004
    - type: nauc_map_at_100_std
      value: 2.1626
    - type: nauc_map_at_100_diff1
      value: 50.1124
    - type: nauc_map_at_1000_max
      value: 43.9529
    - type: nauc_map_at_1000_std
      value: 2.309
    - type: nauc_map_at_1000_diff1
      value: 50.0859
    - type: nauc_recall_at_1_max
      value: 35.7481
    - type: nauc_recall_at_1_std
      value: -6.451
    - type: nauc_recall_at_1_diff1
      value: 55.3994
    - type: nauc_recall_at_3_max
      value: 40.739
    - type: nauc_recall_at_3_std
      value: -0.9688
    - type: nauc_recall_at_3_diff1
      value: 47.1898
    - type: nauc_recall_at_5_max
      value: 41.494
    - type: nauc_recall_at_5_std
      value: 2.1174
    - type: nauc_recall_at_5_diff1
      value: 44.5816
    - type: nauc_recall_at_10_max
      value: 41.739
    - type: nauc_recall_at_10_std
      value: 5.7603
    - type: nauc_recall_at_10_diff1
      value: 39.9929
    - type: nauc_recall_at_20_max
      value: 42.9217
    - type: nauc_recall_at_20_std
      value: 10.6088
    - type: nauc_recall_at_20_diff1
      value: 39.1455
    - type: nauc_recall_at_100_max
      value: 45.1375
    - type: nauc_recall_at_100_std
      value: 25.986700000000003
    - type: nauc_recall_at_100_diff1
      value: 33.972
    - type: nauc_recall_at_1000_max
      value: 46.050200000000004
    - type: nauc_recall_at_1000_std
      value: 44.597300000000004
    - type: nauc_recall_at_1000_diff1
      value: 26.326100000000004
    - type: nauc_precision_at_1_max
      value: 44.7657
    - type: nauc_precision_at_1_std
      value: 3.7028
    - type: nauc_precision_at_1_diff1
      value: 52.017199999999995
    - type: nauc_precision_at_3_max
      value: 44.291799999999995
    - type: nauc_precision_at_3_std
      value: 18.334500000000002
    - type: nauc_precision_at_3_diff1
      value: 25.625500000000002
    - type: nauc_precision_at_5_max
      value: 40.8025
    - type: nauc_precision_at_5_std
      value: 23.6687
    - type: nauc_precision_at_5_diff1
      value: 16.6574
    - type: nauc_precision_at_10_max
      value: 35.7196
    - type: nauc_precision_at_10_std
      value: 29.852099999999997
    - type: nauc_precision_at_10_diff1
      value: 5.6891
    - type: nauc_precision_at_20_max
      value: 30.119
    - type: nauc_precision_at_20_std
      value: 33.204
    - type: nauc_precision_at_20_diff1
      value: -0.23509999999999998
    - type: nauc_precision_at_100_max
      value: 18.7797
    - type: nauc_precision_at_100_std
      value: 38.9405
    - type: nauc_precision_at_100_diff1
      value: -10.8005
    - type: nauc_precision_at_1000_max
      value: 9.0466
    - type: nauc_precision_at_1000_std
      value: 35.3392
    - type: nauc_precision_at_1000_diff1
      value: -16.3137
    - type: nauc_mrr_at_1_max
      value: 44.7657
    - type: nauc_mrr_at_1_std
      value: 3.7028
    - type: nauc_mrr_at_1_diff1
      value: 52.017199999999995
    - type: nauc_mrr_at_3_max
      value: 45.8134
    - type: nauc_mrr_at_3_std
      value: 5.6788
    - type: nauc_mrr_at_3_diff1
      value: 48.666199999999996
    - type: nauc_mrr_at_5_max
      value: 45.8823
    - type: nauc_mrr_at_5_std
      value: 6.4417
    - type: nauc_mrr_at_5_diff1
      value: 48.1545
    - type: nauc_mrr_at_10_max
      value: 45.813500000000005
    - type: nauc_mrr_at_10_std
      value: 6.7535
    - type: nauc_mrr_at_10_diff1
      value: 47.726400000000005
    - type: nauc_mrr_at_20_max
      value: 45.792500000000004
    - type: nauc_mrr_at_20_std
      value: 6.8521
    - type: nauc_mrr_at_20_diff1
      value: 47.7553
    - type: nauc_mrr_at_100_max
      value: 45.8482
    - type: nauc_mrr_at_100_std
      value: 6.979399999999999
    - type: nauc_mrr_at_100_diff1
      value: 47.7743
    - type: nauc_mrr_at_1000_max
      value: 45.8456
    - type: nauc_mrr_at_1000_std
      value: 6.9712
    - type: nauc_mrr_at_1000_diff1
      value: 47.7803
    - type: main_score
      value: 50.251000000000005
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackGamingRetrieval (default)
      revision: 4885aa143210c98657558c04aaf3dc47cfb54340
      split: test
      type: mteb/cqadupstack-gaming
    metrics:
    - type: ndcg_at_1
      value: 47.147
    - type: ndcg_at_3
      value: 53.969
    - type: ndcg_at_5
      value: 56.743
    - type: ndcg_at_10
      value: 59.318000000000005
    - type: ndcg_at_20
      value: 60.897999999999996
    - type: ndcg_at_100
      value: 62.971999999999994
    - type: ndcg_at_1000
      value: 64.033
    - type: map_at_1
      value: 41.126000000000005
    - type: map_at_3
      value: 50.388999999999996
    - type: map_at_5
      value: 52.286
    - type: map_at_10
      value: 53.661
    - type: map_at_20
      value: 54.228
    - type: map_at_100
      value: 54.588
    - type: map_at_1000
      value: 54.638
    - type: recall_at_1
      value: 41.126000000000005
    - type: recall_at_3
      value: 58.374
    - type: recall_at_5
      value: 65.226
    - type: recall_at_10
      value: 72.69099999999999
    - type: recall_at_20
      value: 78.62
    - type: recall_at_100
      value: 88.69200000000001
    - type: recall_at_1000
      value: 96.232
    - type: precision_at_1
      value: 47.147
    - type: precision_at_3
      value: 24.159
    - type: precision_at_5
      value: 16.577
    - type: precision_at_10
      value: 9.549000000000001
    - type: precision_at_20
      value: 5.276
    - type: precision_at_100
      value: 1.224
    - type: precision_at_1000
      value: 0.135
    - type: mrr_at_1
      value: 47.147299999999994
    - type: mrr_at_3
      value: 54.4305
    - type: mrr_at_5
      value: 55.95719999999999
    - type: mrr_at_10
      value: 56.8499
    - type: mrr_at_20
      value: 57.230000000000004
    - type: mrr_at_100
      value: 57.4584
    - type: mrr_at_1000
      value: 57.4867
    - type: nauc_ndcg_at_1_max
      value: 43.5129
    - type: nauc_ndcg_at_1_std
      value: -3.5116
    - type: nauc_ndcg_at_1_diff1
      value: 52.717000000000006
    - type: nauc_ndcg_at_3_max
      value: 43.6514
    - type: nauc_ndcg_at_3_std
      value: -3.7903
    - type: nauc_ndcg_at_3_diff1
      value: 48.7913
    - type: nauc_ndcg_at_5_max
      value: 44.465700000000005
    - type: nauc_ndcg_at_5_std
      value: -3.3794999999999997
    - type: nauc_ndcg_at_5_diff1
      value: 48.8527
    - type: nauc_ndcg_at_10_max
      value: 46.0891
    - type: nauc_ndcg_at_10_std
      value: -0.5534
    - type: nauc_ndcg_at_10_diff1
      value: 48.857099999999996
    - type: nauc_ndcg_at_20_max
      value: 46.1334
    - type: nauc_ndcg_at_20_std
      value: 0.2072
    - type: nauc_ndcg_at_20_diff1
      value: 48.8269
    - type: nauc_ndcg_at_100_max
      value: 46.2793
    - type: nauc_ndcg_at_100_std
      value: 1.2965
    - type: nauc_ndcg_at_100_diff1
      value: 48.6421
    - type: nauc_ndcg_at_1000_max
      value: 46.1606
    - type: nauc_ndcg_at_1000_std
      value: 0.5259
    - type: nauc_ndcg_at_1000_diff1
      value: 48.9864
    - type: nauc_map_at_1_max
      value: 36.4337
    - type: nauc_map_at_1_std
      value: -5.6848
    - type: nauc_map_at_1_diff1
      value: 53.42360000000001
    - type: nauc_map_at_3_max
      value: 41.6669
    - type: nauc_map_at_3_std
      value: -5.6545
    - type: nauc_map_at_3_diff1
      value: 49.6128
    - type: nauc_map_at_5_max
      value: 42.6809
    - type: nauc_map_at_5_std
      value: -4.9988
    - type: nauc_map_at_5_diff1
      value: 49.645
    - type: nauc_map_at_10_max
      value: 43.7393
    - type: nauc_map_at_10_std
      value: -3.3649
    - type: nauc_map_at_10_diff1
      value: 49.574
    - type: nauc_map_at_20_max
      value: 43.9855
    - type: nauc_map_at_20_std
      value: -2.8590999999999998
    - type: nauc_map_at_20_diff1
      value: 49.5139
    - type: nauc_map_at_100_max
      value: 44.0978
    - type: nauc_map_at_100_std
      value: -2.604
    - type: nauc_map_at_100_diff1
      value: 49.4857
    - type: nauc_map_at_1000_max
      value: 44.114399999999996
    - type: nauc_map_at_1000_std
      value: -2.6081
    - type: nauc_map_at_1000_diff1
      value: 49.508799999999994
    - type: nauc_recall_at_1_max
      value: 36.4337
    - type: nauc_recall_at_1_std
      value: -5.6848
    - type: nauc_recall_at_1_diff1
      value: 53.42360000000001
    - type: nauc_recall_at_3_max
      value: 41.320299999999996
    - type: nauc_recall_at_3_std
      value: -5.7135
    - type: nauc_recall_at_3_diff1
      value: 45.0436
    - type: nauc_recall_at_5_max
      value: 43.1656
    - type: nauc_recall_at_5_std
      value: -3.8888
    - type: nauc_recall_at_5_diff1
      value: 44.3304
    - type: nauc_recall_at_10_max
      value: 48.9816
    - type: nauc_recall_at_10_std
      value: 5.9506000000000006
    - type: nauc_recall_at_10_diff1
      value: 43.9217
    - type: nauc_recall_at_20_max
      value: 50.5525
    - type: nauc_recall_at_20_std
      value: 11.8017
    - type: nauc_recall_at_20_diff1
      value: 43.4987
    - type: nauc_recall_at_100_max
      value: 54.654
    - type: nauc_recall_at_100_std
      value: 31.634800000000002
    - type: nauc_recall_at_100_diff1
      value: 38.7139
    - type: nauc_recall_at_1000_max
      value: 62.253
    - type: nauc_recall_at_1000_std
      value: 42.6522
    - type: nauc_recall_at_1000_diff1
      value: 38.3715
    - type: nauc_precision_at_1_max
      value: 43.5129
    - type: nauc_precision_at_1_std
      value: -3.5116
    - type: nauc_precision_at_1_diff1
      value: 52.717000000000006
    - type: nauc_precision_at_3_max
      value: 41.983399999999996
    - type: nauc_precision_at_3_std
      value: 2.4643
    - type: nauc_precision_at_3_diff1
      value: 28.185
    - type: nauc_precision_at_5_max
      value: 39.8061
    - type: nauc_precision_at_5_std
      value: 6.4715
    - type: nauc_precision_at_5_diff1
      value: 21.333199999999998
    - type: nauc_precision_at_10_max
      value: 37.914500000000004
    - type: nauc_precision_at_10_std
      value: 17.1485
    - type: nauc_precision_at_10_diff1
      value: 12.6277
    - type: nauc_precision_at_20_max
      value: 34.0432
    - type: nauc_precision_at_20_std
      value: 23.0425
    - type: nauc_precision_at_20_diff1
      value: 5.551699999999999
    - type: nauc_precision_at_100_max
      value: 26.0405
    - type: nauc_precision_at_100_std
      value: 28.572599999999998
    - type: nauc_precision_at_100_diff1
      value: -4.2162
    - type: nauc_precision_at_1000_max
      value: 20.176099999999998
    - type: nauc_precision_at_1000_std
      value: 27.293499999999998
    - type: nauc_precision_at_1000_diff1
      value: -7.4514
    - type: nauc_mrr_at_1_max
      value: 43.5129
    - type: nauc_mrr_at_1_std
      value: -3.5116
    - type: nauc_mrr_at_1_diff1
      value: 52.717000000000006
    - type: nauc_mrr_at_3_max
      value: 44.9785
    - type: nauc_mrr_at_3_std
      value: -2.2618
    - type: nauc_mrr_at_3_diff1
      value: 49.8663
    - type: nauc_mrr_at_5_max
      value: 45.1749
    - type: nauc_mrr_at_5_std
      value: -2.1027
    - type: nauc_mrr_at_5_diff1
      value: 49.8332
    - type: nauc_mrr_at_10_max
      value: 45.6015
    - type: nauc_mrr_at_10_std
      value: -1.3832
    - type: nauc_mrr_at_10_diff1
      value: 49.9586
    - type: nauc_mrr_at_20_max
      value: 45.535399999999996
    - type: nauc_mrr_at_20_std
      value: -1.2799
    - type: nauc_mrr_at_20_diff1
      value: 49.9829
    - type: nauc_mrr_at_100_max
      value: 45.5168
    - type: nauc_mrr_at_100_std
      value: -1.2195
    - type: nauc_mrr_at_100_diff1
      value: 49.9728
    - type: nauc_mrr_at_1000_max
      value: 45.5076
    - type: nauc_mrr_at_1000_std
      value: -1.2494
    - type: nauc_mrr_at_1000_diff1
      value: 49.977
    - type: main_score
      value: 59.318000000000005
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackGisRetrieval (default)
      revision: 5003b3064772da1887988e05400cf3806fe491f2
      split: test
      type: mteb/cqadupstack-gis
    metrics:
    - type: ndcg_at_1
      value: 30.734
    - type: ndcg_at_3
      value: 38.672000000000004
    - type: ndcg_at_5
      value: 40.954
    - type: ndcg_at_10
      value: 43.564
    - type: ndcg_at_20
      value: 45.48
    - type: ndcg_at_100
      value: 48.419000000000004
    - type: ndcg_at_1000
      value: 50.404
    - type: map_at_1
      value: 28.464
    - type: map_at_3
      value: 35.704
    - type: map_at_5
      value: 37.116
    - type: map_at_10
      value: 38.279999999999994
    - type: map_at_20
      value: 38.834
    - type: map_at_100
      value: 39.277
    - type: map_at_1000
      value: 39.355000000000004
    - type: recall_at_1
      value: 28.464
    - type: recall_at_3
      value: 44.588
    - type: recall_at_5
      value: 50.031000000000006
    - type: recall_at_10
      value: 57.621
    - type: recall_at_20
      value: 64.85499999999999
    - type: recall_at_100
      value: 79.66
    - type: recall_at_1000
      value: 94.633
    - type: precision_at_1
      value: 30.734
    - type: precision_at_3
      value: 16.497
    - type: precision_at_5
      value: 11.254
    - type: precision_at_10
      value: 6.633
    - type: precision_at_20
      value: 3.757
    - type: precision_at_100
      value: 0.9560000000000001
    - type: precision_at_1000
      value: 0.116
    - type: mrr_at_1
      value: 30.734499999999997
    - type: mrr_at_3
      value: 38.1356
    - type: mrr_at_5
      value: 39.3616
    - type: mrr_at_10
      value: 40.4225
    - type: mrr_at_20
      value: 40.9334
    - type: mrr_at_100
      value: 41.297200000000004
    - type: mrr_at_1000
      value: 41.354600000000005
    - type: nauc_ndcg_at_1_max
      value: 30.2094
    - type: nauc_ndcg_at_1_std
      value: -6.9741
    - type: nauc_ndcg_at_1_diff1
      value: 47.5543
    - type: nauc_ndcg_at_3_max
      value: 31.4334
    - type: nauc_ndcg_at_3_std
      value: -4.7826
    - type: nauc_ndcg_at_3_diff1
      value: 41.1025
    - type: nauc_ndcg_at_5_max
      value: 32.3557
    - type: nauc_ndcg_at_5_std
      value: -4.1379
    - type: nauc_ndcg_at_5_diff1
      value: 40.81
    - type: nauc_ndcg_at_10_max
      value: 32.3949
    - type: nauc_ndcg_at_10_std
      value: -2.3524
    - type: nauc_ndcg_at_10_diff1
      value: 39.5175
    - type: nauc_ndcg_at_20_max
      value: 31.680500000000002
    - type: nauc_ndcg_at_20_std
      value: -1.7559000000000002
    - type: nauc_ndcg_at_20_diff1
      value: 38.1515
    - type: nauc_ndcg_at_100_max
      value: 31.4167
    - type: nauc_ndcg_at_100_std
      value: -1.0329
    - type: nauc_ndcg_at_100_diff1
      value: 37.8268
    - type: nauc_ndcg_at_1000_max
      value: 31.736900000000002
    - type: nauc_ndcg_at_1000_std
      value: -1.8415000000000001
    - type: nauc_ndcg_at_1000_diff1
      value: 39.0335
    - type: nauc_map_at_1_max
      value: 28.260099999999998
    - type: nauc_map_at_1_std
      value: -9.0806
    - type: nauc_map_at_1_diff1
      value: 47.6706
    - type: nauc_map_at_3_max
      value: 30.551000000000002
    - type: nauc_map_at_3_std
      value: -6.0257
    - type: nauc_map_at_3_diff1
      value: 42.8155
    - type: nauc_map_at_5_max
      value: 31.285800000000002
    - type: nauc_map_at_5_std
      value: -5.671600000000001
    - type: nauc_map_at_5_diff1
      value: 42.5887
    - type: nauc_map_at_10_max
      value: 31.329800000000002
    - type: nauc_map_at_10_std
      value: -4.8092999999999995
    - type: nauc_map_at_10_diff1
      value: 41.9856
    - type: nauc_map_at_20_max
      value: 31.2046
    - type: nauc_map_at_20_std
      value: -4.612
    - type: nauc_map_at_20_diff1
      value: 41.658699999999996
    - type: nauc_map_at_100_max
      value: 31.181399999999996
    - type: nauc_map_at_100_std
      value: -4.4687
    - type: nauc_map_at_100_diff1
      value: 41.5836
    - type: nauc_map_at_1000_max
      value: 31.1979
    - type: nauc_map_at_1000_std
      value: -4.4772
    - type: nauc_map_at_1000_diff1
      value: 41.627900000000004
    - type: nauc_recall_at_1_max
      value: 28.260099999999998
    - type: nauc_recall_at_1_std
      value: -9.0806
    - type: nauc_recall_at_1_diff1
      value: 47.6706
    - type: nauc_recall_at_3_max
      value: 31.129800000000003
    - type: nauc_recall_at_3_std
      value: -3.2782
    - type: nauc_recall_at_3_diff1
      value: 35.4529
    - type: nauc_recall_at_5_max
      value: 33.6541
    - type: nauc_recall_at_5_std
      value: -1.7704999999999997
    - type: nauc_recall_at_5_diff1
      value: 34.9944
    - type: nauc_recall_at_10_max
      value: 33.536100000000005
    - type: nauc_recall_at_10_std
      value: 3.4567
    - type: nauc_recall_at_10_diff1
      value: 30.553599999999996
    - type: nauc_recall_at_20_max
      value: 29.889100000000003
    - type: nauc_recall_at_20_std
      value: 6.5926
    - type: nauc_recall_at_20_diff1
      value: 23.217
    - type: nauc_recall_at_100_max
      value: 27.4646
    - type: nauc_recall_at_100_std
      value: 15.746199999999998
    - type: nauc_recall_at_100_diff1
      value: 15.1327
    - type: nauc_recall_at_1000_max
      value: 32.294200000000004
    - type: nauc_recall_at_1000_std
      value: 21.6293
    - type: nauc_recall_at_1000_diff1
      value: 11.265600000000001
    - type: nauc_precision_at_1_max
      value: 30.2094
    - type: nauc_precision_at_1_std
      value: -6.9741
    - type: nauc_precision_at_1_diff1
      value: 47.5543
    - type: nauc_precision_at_3_max
      value: 34.3053
    - type: nauc_precision_at_3_std
      value: 0.42760000000000004
    - type: nauc_precision_at_3_diff1
      value: 33.4827
    - type: nauc_precision_at_5_max
      value: 35.4035
    - type: nauc_precision_at_5_std
      value: 2.3141
    - type: nauc_precision_at_5_diff1
      value: 30.8004
    - type: nauc_precision_at_10_max
      value: 33.4042
    - type: nauc_precision_at_10_std
      value: 8.6847
    - type: nauc_precision_at_10_diff1
      value: 23.558200000000003
    - type: nauc_precision_at_20_max
      value: 29.015200000000004
    - type: nauc_precision_at_20_std
      value: 11.3556
    - type: nauc_precision_at_20_diff1
      value: 15.774099999999999
    - type: nauc_precision_at_100_max
      value: 16.663700000000002
    - type: nauc_precision_at_100_std
      value: 14.666100000000002
    - type: nauc_precision_at_100_diff1
      value: 2.1911
    - type: nauc_precision_at_1000_max
      value: 7.348599999999999
    - type: nauc_precision_at_1000_std
      value: 8.8804
    - type: nauc_precision_at_1000_diff1
      value: -7.026599999999999
    - type: nauc_mrr_at_1_max
      value: 30.2094
    - type: nauc_mrr_at_1_std
      value: -6.9741
    - type: nauc_mrr_at_1_diff1
      value: 47.5543
    - type: nauc_mrr_at_3_max
      value: 31.831500000000002
    - type: nauc_mrr_at_3_std
      value: -3.6407000000000003
    - type: nauc_mrr_at_3_diff1
      value: 42.445
    - type: nauc_mrr_at_5_max
      value: 32.273
    - type: nauc_mrr_at_5_std
      value: -3.5416000000000003
    - type: nauc_mrr_at_5_diff1
      value: 42.5464
    - type: nauc_mrr_at_10_max
      value: 32.3297
    - type: nauc_mrr_at_10_std
      value: -2.9149000000000003
    - type: nauc_mrr_at_10_diff1
      value: 42.0233
    - type: nauc_mrr_at_20_max
      value: 32.124
    - type: nauc_mrr_at_20_std
      value: -2.7826
    - type: nauc_mrr_at_20_diff1
      value: 41.652
    - type: nauc_mrr_at_100_max
      value: 32.0994
    - type: nauc_mrr_at_100_std
      value: -2.7182999999999997
    - type: nauc_mrr_at_100_diff1
      value: 41.6024
    - type: nauc_mrr_at_1000_max
      value: 32.1058
    - type: nauc_mrr_at_1000_std
      value: -2.7332
    - type: nauc_mrr_at_1000_diff1
      value: 41.652899999999995
    - type: main_score
      value: 43.564
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackMathematicaRetrieval (default)
      revision: 90fceea13679c63fe563ded68f3b6f06e50061de
      split: test
      type: mteb/cqadupstack-mathematica
    metrics:
    - type: ndcg_at_1
      value: 22.886
    - type: ndcg_at_3
      value: 27.864
    - type: ndcg_at_5
      value: 30.177
    - type: ndcg_at_10
      value: 32.749
    - type: ndcg_at_20
      value: 35.343
    - type: ndcg_at_100
      value: 39.095
    - type: ndcg_at_1000
      value: 41.656
    - type: map_at_1
      value: 18.119
    - type: map_at_3
      value: 24.340999999999998
    - type: map_at_5
      value: 25.861
    - type: map_at_10
      value: 27.055
    - type: map_at_20
      value: 27.855
    - type: map_at_100
      value: 28.461
    - type: map_at_1000
      value: 28.577
    - type: recall_at_1
      value: 18.119
    - type: recall_at_3
      value: 31.633
    - type: recall_at_5
      value: 37.532
    - type: recall_at_10
      value: 44.983000000000004
    - type: recall_at_20
      value: 54.234
    - type: recall_at_100
      value: 72.396
    - type: recall_at_1000
      value: 90.223
    - type: precision_at_1
      value: 22.886
    - type: precision_at_3
      value: 13.682
    - type: precision_at_5
      value: 9.950000000000001
    - type: precision_at_10
      value: 6.1690000000000005
    - type: precision_at_20
      value: 3.8120000000000003
    - type: precision_at_100
      value: 1.0699999999999998
    - type: precision_at_1000
      value: 0.14300000000000002
    - type: mrr_at_1
      value: 22.8856
    - type: mrr_at_3
      value: 29.6642
    - type: mrr_at_5
      value: 31.107000000000003
    - type: mrr_at_10
      value: 32.2342
    - type: mrr_at_20
      value: 32.8971
    - type: mrr_at_100
      value: 33.2804
    - type: mrr_at_1000
      value: 33.3395
    - type: nauc_ndcg_at_1_max
      value: 24.8022
    - type: nauc_ndcg_at_1_std
      value: -0.5363
    - type: nauc_ndcg_at_1_diff1
      value: 33.1639
    - type: nauc_ndcg_at_3_max
      value: 22.0142
    - type: nauc_ndcg_at_3_std
      value: 0.9467
    - type: nauc_ndcg_at_3_diff1
      value: 28.9545
    - type: nauc_ndcg_at_5_max
      value: 21.9949
    - type: nauc_ndcg_at_5_std
      value: 2.2558000000000002
    - type: nauc_ndcg_at_5_diff1
      value: 27.4516
    - type: nauc_ndcg_at_10_max
      value: 21.5958
    - type: nauc_ndcg_at_10_std
      value: 3.5044
    - type: nauc_ndcg_at_10_diff1
      value: 26.9835
    - type: nauc_ndcg_at_20_max
      value: 21.940299999999997
    - type: nauc_ndcg_at_20_std
      value: 4.6913
    - type: nauc_ndcg_at_20_diff1
      value: 26.8386
    - type: nauc_ndcg_at_100_max
      value: 22.4749
    - type: nauc_ndcg_at_100_std
      value: 6.1636999999999995
    - type: nauc_ndcg_at_100_diff1
      value: 27.4132
    - type: nauc_ndcg_at_1000_max
      value: 23.034299999999998
    - type: nauc_ndcg_at_1000_std
      value: 5.7944
    - type: nauc_ndcg_at_1000_diff1
      value: 27.3963
    - type: nauc_map_at_1_max
      value: 21.4135
    - type: nauc_map_at_1_std
      value: 0.649
    - type: nauc_map_at_1_diff1
      value: 32.1954
    - type: nauc_map_at_3_max
      value: 20.8778
    - type: nauc_map_at_3_std
      value: 1.0705
    - type: nauc_map_at_3_diff1
      value: 28.5319
    - type: nauc_map_at_5_max
      value: 21.0234
    - type: nauc_map_at_5_std
      value: 1.5574
    - type: nauc_map_at_5_diff1
      value: 27.996399999999998
    - type: nauc_map_at_10_max
      value: 20.9927
    - type: nauc_map_at_10_std
      value: 2.2451
    - type: nauc_map_at_10_diff1
      value: 27.8283
    - type: nauc_map_at_20_max
      value: 21.16
    - type: nauc_map_at_20_std
      value: 2.6176999999999997
    - type: nauc_map_at_20_diff1
      value: 27.7722
    - type: nauc_map_at_100_max
      value: 21.3551
    - type: nauc_map_at_100_std
      value: 2.8299000000000003
    - type: nauc_map_at_100_diff1
      value: 27.8752
    - type: nauc_map_at_1000_max
      value: 21.3871
    - type: nauc_map_at_1000_std
      value: 2.7986
    - type: nauc_map_at_1000_diff1
      value: 27.8709
    - type: nauc_recall_at_1_max
      value: 21.4135
    - type: nauc_recall_at_1_std
      value: 0.649
    - type: nauc_recall_at_1_diff1
      value: 32.1954
    - type: nauc_recall_at_3_max
      value: 19.3537
    - type: nauc_recall_at_3_std
      value: 1.4591
    - type: nauc_recall_at_3_diff1
      value: 25.1911
    - type: nauc_recall_at_5_max
      value: 19.6154
    - type: nauc_recall_at_5_std
      value: 3.5305000000000004
    - type: nauc_recall_at_5_diff1
      value: 22.6218
    - type: nauc_recall_at_10_max
      value: 18.3048
    - type: nauc_recall_at_10_std
      value: 6.1244
    - type: nauc_recall_at_10_diff1
      value: 21.6834
    - type: nauc_recall_at_20_max
      value: 18.4913
    - type: nauc_recall_at_20_std
      value: 10.083599999999999
    - type: nauc_recall_at_20_diff1
      value: 20.502200000000002
    - type: nauc_recall_at_100_max
      value: 19.0212
    - type: nauc_recall_at_100_std
      value: 21.8101
    - type: nauc_recall_at_100_diff1
      value: 21.2653
    - type: nauc_recall_at_1000_max
      value: 29.3582
    - type: nauc_recall_at_1000_std
      value: 42.8902
    - type: nauc_recall_at_1000_diff1
      value: 14.060900000000002
    - type: nauc_precision_at_1_max
      value: 24.8022
    - type: nauc_precision_at_1_std
      value: -0.5363
    - type: nauc_precision_at_1_diff1
      value: 33.1639
    - type: nauc_precision_at_3_max
      value: 23.9746
    - type: nauc_precision_at_3_std
      value: 0.9273999999999999
    - type: nauc_precision_at_3_diff1
      value: 26.0507
    - type: nauc_precision_at_5_max
      value: 23.5487
    - type: nauc_precision_at_5_std
      value: 2.8788
    - type: nauc_precision_at_5_diff1
      value: 22.439799999999998
    - type: nauc_precision_at_10_max
      value: 21.826999999999998
    - type: nauc_precision_at_10_std
      value: 5.6201
    - type: nauc_precision_at_10_diff1
      value: 19.8703
    - type: nauc_precision_at_20_max
      value: 21.199399999999997
    - type: nauc_precision_at_20_std
      value: 8.9305
    - type: nauc_precision_at_20_diff1
      value: 18.043
    - type: nauc_precision_at_100_max
      value: 17.2345
    - type: nauc_precision_at_100_std
      value: 10.0714
    - type: nauc_precision_at_100_diff1
      value: 14.521999999999998
    - type: nauc_precision_at_1000_max
      value: 7.5709
    - type: nauc_precision_at_1000_std
      value: 0.2689
    - type: nauc_precision_at_1000_diff1
      value: 4.4733
    - type: nauc_mrr_at_1_max
      value: 24.8022
    - type: nauc_mrr_at_1_std
      value: -0.5363
    - type: nauc_mrr_at_1_diff1
      value: 33.1639
    - type: nauc_mrr_at_3_max
      value: 24.435499999999998
    - type: nauc_mrr_at_3_std
      value: 0.9502999999999999
    - type: nauc_mrr_at_3_diff1
      value: 30.7875
    - type: nauc_mrr_at_5_max
      value: 24.7103
    - type: nauc_mrr_at_5_std
      value: 1.8724999999999998
    - type: nauc_mrr_at_5_diff1
      value: 30.086000000000002
    - type: nauc_mrr_at_10_max
      value: 24.5685
    - type: nauc_mrr_at_10_std
      value: 2.1533
    - type: nauc_mrr_at_10_diff1
      value: 29.862899999999996
    - type: nauc_mrr_at_20_max
      value: 24.662100000000002
    - type: nauc_mrr_at_20_std
      value: 2.3742
    - type: nauc_mrr_at_20_diff1
      value: 29.751300000000004
    - type: nauc_mrr_at_100_max
      value: 24.635099999999998
    - type: nauc_mrr_at_100_std
      value: 2.4393000000000002
    - type: nauc_mrr_at_100_diff1
      value: 29.741
    - type: nauc_mrr_at_1000_max
      value: 24.651699999999998
    - type: nauc_mrr_at_1000_std
      value: 2.4291
    - type: nauc_mrr_at_1000_diff1
      value: 29.7639
    - type: main_score
      value: 32.749
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackPhysicsRetrieval (default)
      revision: 79531abbd1fb92d06c6d6315a0cbbbf5bb247ea4
      split: test
      type: mteb/cqadupstack-physics
    metrics:
    - type: ndcg_at_1
      value: 38.114
    - type: ndcg_at_3
      value: 42.986000000000004
    - type: ndcg_at_5
      value: 45.893
    - type: ndcg_at_10
      value: 48.339999999999996
    - type: ndcg_at_20
      value: 50.617000000000004
    - type: ndcg_at_100
      value: 53.861000000000004
    - type: ndcg_at_1000
      value: 55.701
    - type: map_at_1
      value: 30.517
    - type: map_at_3
      value: 38.443
    - type: map_at_5
      value: 40.685
    - type: map_at_10
      value: 42.031
    - type: map_at_20
      value: 42.79
    - type: map_at_100
      value: 43.415
    - type: map_at_1000
      value: 43.525000000000006
    - type: recall_at_1
      value: 30.517
    - type: recall_at_3
      value: 46.015
    - type: recall_at_5
      value: 53.801
    - type: recall_at_10
      value: 61.332
    - type: recall_at_20
      value: 69.274
    - type: recall_at_100
      value: 84.051
    - type: recall_at_1000
      value: 95.826
    - type: precision_at_1
      value: 38.114
    - type: precision_at_3
      value: 20.821
    - type: precision_at_5
      value: 15.034
    - type: precision_at_10
      value: 8.892999999999999
    - type: precision_at_20
      value: 5.231
    - type: precision_at_100
      value: 1.375
    - type: precision_at_1000
      value: 0.172
    - type: mrr_at_1
      value: 38.1136
    - type: mrr_at_3
      value: 45.1716
    - type: mrr_at_5
      value: 46.8175
    - type: mrr_at_10
      value: 47.7831
    - type: mrr_at_20
      value: 48.329
    - type: mrr_at_100
      value: 48.6471
    - type: mrr_at_1000
      value: 48.6877
    - type: nauc_ndcg_at_1_max
      value: 40.1541
    - type: nauc_ndcg_at_1_std
      value: 1.4596
    - type: nauc_ndcg_at_1_diff1
      value: 56.6442
    - type: nauc_ndcg_at_3_max
      value: 38.9776
    - type: nauc_ndcg_at_3_std
      value: 1.464
    - type: nauc_ndcg_at_3_diff1
      value: 51.5596
    - type: nauc_ndcg_at_5_max
      value: 38.8678
    - type: nauc_ndcg_at_5_std
      value: 2.5537
    - type: nauc_ndcg_at_5_diff1
      value: 50.522
    - type: nauc_ndcg_at_10_max
      value: 38.698100000000004
    - type: nauc_ndcg_at_10_std
      value: 2.7959
    - type: nauc_ndcg_at_10_diff1
      value: 49.8331
    - type: nauc_ndcg_at_20_max
      value: 39.7247
    - type: nauc_ndcg_at_20_std
      value: 4.1737
    - type: nauc_ndcg_at_20_diff1
      value: 49.5233
    - type: nauc_ndcg_at_100_max
      value: 40.649
    - type: nauc_ndcg_at_100_std
      value: 5.7359
    - type: nauc_ndcg_at_100_diff1
      value: 50.0626
    - type: nauc_ndcg_at_1000_max
      value: 40.765299999999996
    - type: nauc_ndcg_at_1000_std
      value: 5.5551
    - type: nauc_ndcg_at_1000_diff1
      value: 50.3599
    - type: nauc_map_at_1_max
      value: 35.659
    - type: nauc_map_at_1_std
      value: -3.8913
    - type: nauc_map_at_1_diff1
      value: 57.7115
    - type: nauc_map_at_3_max
      value: 37.3901
    - type: nauc_map_at_3_std
      value: -0.88
    - type: nauc_map_at_3_diff1
      value: 52.9203
    - type: nauc_map_at_5_max
      value: 38.0129
    - type: nauc_map_at_5_std
      value: 0.1544
    - type: nauc_map_at_5_diff1
      value: 52.1596
    - type: nauc_map_at_10_max
      value: 38.3708
    - type: nauc_map_at_10_std
      value: 0.7947
    - type: nauc_map_at_10_diff1
      value: 51.909000000000006
    - type: nauc_map_at_20_max
      value: 38.690200000000004
    - type: nauc_map_at_20_std
      value: 1.2379
    - type: nauc_map_at_20_diff1
      value: 51.775000000000006
    - type: nauc_map_at_100_max
      value: 38.9637
    - type: nauc_map_at_100_std
      value: 1.5914000000000001
    - type: nauc_map_at_100_diff1
      value: 51.90820000000001
    - type: nauc_map_at_1000_max
      value: 38.9784
    - type: nauc_map_at_1000_std
      value: 1.6184
    - type: nauc_map_at_1000_diff1
      value: 51.909000000000006
    - type: nauc_recall_at_1_max
      value: 35.659
    - type: nauc_recall_at_1_std
      value: -3.8913
    - type: nauc_recall_at_1_diff1
      value: 57.7115
    - type: nauc_recall_at_3_max
      value: 34.6073
    - type: nauc_recall_at_3_std
      value: 0.0162
    - type: nauc_recall_at_3_diff1
      value: 47.0539
    - type: nauc_recall_at_5_max
      value: 34.3868
    - type: nauc_recall_at_5_std
      value: 3.1425
    - type: nauc_recall_at_5_diff1
      value: 43.1625
    - type: nauc_recall_at_10_max
      value: 33.6467
    - type: nauc_recall_at_10_std
      value: 4.1808
    - type: nauc_recall_at_10_diff1
      value: 39.711600000000004
    - type: nauc_recall_at_20_max
      value: 36.3449
    - type: nauc_recall_at_20_std
      value: 9.7358
    - type: nauc_recall_at_20_diff1
      value: 36.5764
    - type: nauc_recall_at_100_max
      value: 40.563500000000005
    - type: nauc_recall_at_100_std
      value: 23.5405
    - type: nauc_recall_at_100_diff1
      value: 34.2152
    - type: nauc_recall_at_1000_max
      value: 57.387699999999995
    - type: nauc_recall_at_1000_std
      value: 50.897999999999996
    - type: nauc_recall_at_1000_diff1
      value: 32.9321
    - type: nauc_precision_at_1_max
      value: 40.1541
    - type: nauc_precision_at_1_std
      value: 1.4596
    - type: nauc_precision_at_1_diff1
      value: 56.6442
    - type: nauc_precision_at_3_max
      value: 36.586600000000004
    - type: nauc_precision_at_3_std
      value: 9.7112
    - type: nauc_precision_at_3_diff1
      value: 33.8758
    - type: nauc_precision_at_5_max
      value: 34.1914
    - type: nauc_precision_at_5_std
      value: 13.7515
    - type: nauc_precision_at_5_diff1
      value: 24.6272
    - type: nauc_precision_at_10_max
      value: 30.764999999999997
    - type: nauc_precision_at_10_std
      value: 16.9823
    - type: nauc_precision_at_10_diff1
      value: 15.954799999999999
    - type: nauc_precision_at_20_max
      value: 27.976699999999997
    - type: nauc_precision_at_20_std
      value: 21.465999999999998
    - type: nauc_precision_at_20_diff1
      value: 7.0363999999999995
    - type: nauc_precision_at_100_max
      value: 17.6394
    - type: nauc_precision_at_100_std
      value: 23.4207
    - type: nauc_precision_at_100_diff1
      value: -4.0614
    - type: nauc_precision_at_1000_max
      value: 3.8186999999999998
    - type: nauc_precision_at_1000_std
      value: 16.0902
    - type: nauc_precision_at_1000_diff1
      value: -14.5093
    - type: nauc_mrr_at_1_max
      value: 40.1541
    - type: nauc_mrr_at_1_std
      value: 1.4596
    - type: nauc_mrr_at_1_diff1
      value: 56.6442
    - type: nauc_mrr_at_3_max
      value: 40.4577
    - type: nauc_mrr_at_3_std
      value: 3.558
    - type: nauc_mrr_at_3_diff1
      value: 53.0569
    - type: nauc_mrr_at_5_max
      value: 40.6135
    - type: nauc_mrr_at_5_std
      value: 4.3164
    - type: nauc_mrr_at_5_diff1
      value: 52.3585
    - type: nauc_mrr_at_10_max
      value: 40.6563
    - type: nauc_mrr_at_10_std
      value: 4.3038
    - type: nauc_mrr_at_10_diff1
      value: 52.2149
    - type: nauc_mrr_at_20_max
      value: 40.914
    - type: nauc_mrr_at_20_std
      value: 4.5423
    - type: nauc_mrr_at_20_diff1
      value: 52.2729
    - type: nauc_mrr_at_100_max
      value: 40.8944
    - type: nauc_mrr_at_100_std
      value: 4.546
    - type: nauc_mrr_at_100_diff1
      value: 52.315400000000004
    - type: nauc_mrr_at_1000_max
      value: 40.893499999999996
    - type: nauc_mrr_at_1000_std
      value: 4.5310999999999995
    - type: nauc_mrr_at_1000_diff1
      value: 52.337500000000006
    - type: main_score
      value: 48.339999999999996
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackProgrammersRetrieval (default)
      revision: 6184bc1440d2dbc7612be22b50686b8826d22b32
      split: test
      type: mteb/cqadupstack-programmers
    metrics:
    - type: ndcg_at_1
      value: 34.247
    - type: ndcg_at_3
      value: 38.976
    - type: ndcg_at_5
      value: 41.332
    - type: ndcg_at_10
      value: 44.065
    - type: ndcg_at_20
      value: 46.312999999999995
    - type: ndcg_at_100
      value: 49.434
    - type: ndcg_at_1000
      value: 51.681999999999995
    - type: map_at_1
      value: 27.395999999999997
    - type: map_at_3
      value: 34.782999999999994
    - type: map_at_5
      value: 36.63
    - type: map_at_10
      value: 38.043
    - type: map_at_20
      value: 38.783
    - type: map_at_100
      value: 39.341
    - type: map_at_1000
      value: 39.454
    - type: recall_at_1
      value: 27.395999999999997
    - type: recall_at_3
      value: 41.785
    - type: recall_at_5
      value: 48.303000000000004
    - type: recall_at_10
      value: 56.481
    - type: recall_at_20
      value: 64.473
    - type: recall_at_100
      value: 79.012
    - type: recall_at_1000
      value: 94.182
    - type: precision_at_1
      value: 34.247
    - type: precision_at_3
      value: 18.759999999999998
    - type: precision_at_5
      value: 13.333
    - type: precision_at_10
      value: 8.059
    - type: precision_at_20
      value: 4.766
    - type: precision_at_100
      value: 1.258
    - type: precision_at_1000
      value: 0.16199999999999998
    - type: mrr_at_1
      value: 34.2466
    - type: mrr_at_3
      value: 41.172
    - type: mrr_at_5
      value: 42.701699999999995
    - type: mrr_at_10
      value: 43.6807
    - type: mrr_at_20
      value: 44.1991
    - type: mrr_at_100
      value: 44.5097
    - type: mrr_at_1000
      value: 44.5693
    - type: nauc_ndcg_at_1_max
      value: 38.232
    - type: nauc_ndcg_at_1_std
      value: 3.374
    - type: nauc_ndcg_at_1_diff1
      value: 51.223200000000006
    - type: nauc_ndcg_at_3_max
      value: 38.839800000000004
    - type: nauc_ndcg_at_3_std
      value: 6.529
    - type: nauc_ndcg_at_3_diff1
      value: 44.2371
    - type: nauc_ndcg_at_5_max
      value: 39.0094
    - type: nauc_ndcg_at_5_std
      value: 8.2202
    - type: nauc_ndcg_at_5_diff1
      value: 44.8305
    - type: nauc_ndcg_at_10_max
      value: 40.1918
    - type: nauc_ndcg_at_10_std
      value: 9.9826
    - type: nauc_ndcg_at_10_diff1
      value: 43.5034
    - type: nauc_ndcg_at_20_max
      value: 40.7846
    - type: nauc_ndcg_at_20_std
      value: 11.0178
    - type: nauc_ndcg_at_20_diff1
      value: 43.176199999999994
    - type: nauc_ndcg_at_100_max
      value: 40.5507
    - type: nauc_ndcg_at_100_std
      value: 13.0203
    - type: nauc_ndcg_at_100_diff1
      value: 43.2445
    - type: nauc_ndcg_at_1000_max
      value: 40.8071
    - type: nauc_ndcg_at_1000_std
      value: 11.7945
    - type: nauc_ndcg_at_1000_diff1
      value: 43.8587
    - type: nauc_map_at_1_max
      value: 33.517599999999995
    - type: nauc_map_at_1_std
      value: -0.7517
    - type: nauc_map_at_1_diff1
      value: 52.92059999999999
    - type: nauc_map_at_3_max
      value: 36.8937
    - type: nauc_map_at_3_std
      value: 4.0335
    - type: nauc_map_at_3_diff1
      value: 46.4322
    - type: nauc_map_at_5_max
      value: 37.602000000000004
    - type: nauc_map_at_5_std
      value: 5.3923
    - type: nauc_map_at_5_diff1
      value: 46.6764
    - type: nauc_map_at_10_max
      value: 38.3082
    - type: nauc_map_at_10_std
      value: 6.483600000000001
    - type: nauc_map_at_10_diff1
      value: 46.0255
    - type: nauc_map_at_20_max
      value: 38.655899999999995
    - type: nauc_map_at_20_std
      value: 6.8814
    - type: nauc_map_at_20_diff1
      value: 45.8245
    - type: nauc_map_at_100_max
      value: 38.7492
    - type: nauc_map_at_100_std
      value: 7.327100000000001
    - type: nauc_map_at_100_diff1
      value: 45.8365
    - type: nauc_map_at_1000_max
      value: 38.7584
    - type: nauc_map_at_1000_std
      value: 7.2851
    - type: nauc_map_at_1000_diff1
      value: 45.8479
    - type: nauc_recall_at_1_max
      value: 33.517599999999995
    - type: nauc_recall_at_1_std
      value: -0.7517
    - type: nauc_recall_at_1_diff1
      value: 52.92059999999999
    - type: nauc_recall_at_3_max
      value: 37.0749
    - type: nauc_recall_at_3_std
      value: 7.466399999999999
    - type: nauc_recall_at_3_diff1
      value: 39.454
    - type: nauc_recall_at_5_max
      value: 37.227199999999996
    - type: nauc_recall_at_5_std
      value: 11.7497
    - type: nauc_recall_at_5_diff1
      value: 39.402
    - type: nauc_recall_at_10_max
      value: 39.901199999999996
    - type: nauc_recall_at_10_std
      value: 16.7381
    - type: nauc_recall_at_10_diff1
      value: 34.3843
    - type: nauc_recall_at_20_max
      value: 41.0603
    - type: nauc_recall_at_20_std
      value: 20.78
    - type: nauc_recall_at_20_diff1
      value: 32.2975
    - type: nauc_recall_at_100_max
      value: 38.3499
    - type: nauc_recall_at_100_std
      value: 38.7219
    - type: nauc_recall_at_100_diff1
      value: 29.078100000000003
    - type: nauc_recall_at_1000_max
      value: 48.2277
    - type: nauc_recall_at_1000_std
      value: 55.4646
    - type: nauc_recall_at_1000_diff1
      value: 26.919900000000002
    - type: nauc_precision_at_1_max
      value: 38.232
    - type: nauc_precision_at_1_std
      value: 3.374
    - type: nauc_precision_at_1_diff1
      value: 51.223200000000006
    - type: nauc_precision_at_3_max
      value: 39.8718
    - type: nauc_precision_at_3_std
      value: 14.112
    - type: nauc_precision_at_3_diff1
      value: 28.971200000000003
    - type: nauc_precision_at_5_max
      value: 38.7064
    - type: nauc_precision_at_5_std
      value: 18.1345
    - type: nauc_precision_at_5_diff1
      value: 26.5685
    - type: nauc_precision_at_10_max
      value: 36.4352
    - type: nauc_precision_at_10_std
      value: 22.331500000000002
    - type: nauc_precision_at_10_diff1
      value: 17.163600000000002
    - type: nauc_precision_at_20_max
      value: 33.2221
    - type: nauc_precision_at_20_std
      value: 24.252000000000002
    - type: nauc_precision_at_20_diff1
      value: 9.0445
    - type: nauc_precision_at_100_max
      value: 16.5544
    - type: nauc_precision_at_100_std
      value: 22.867199999999997
    - type: nauc_precision_at_100_diff1
      value: -3.8588999999999998
    - type: nauc_precision_at_1000_max
      value: 1.7690000000000001
    - type: nauc_precision_at_1000_std
      value: 8.2609
    - type: nauc_precision_at_1000_diff1
      value: -13.8927
    - type: nauc_mrr_at_1_max
      value: 38.232
    - type: nauc_mrr_at_1_std
      value: 3.374
    - type: nauc_mrr_at_1_diff1
      value: 51.223200000000006
    - type: nauc_mrr_at_3_max
      value: 40.2699
    - type: nauc_mrr_at_3_std
      value: 7.6
    - type: nauc_mrr_at_3_diff1
      value: 45.1804
    - type: nauc_mrr_at_5_max
      value: 40.1434
    - type: nauc_mrr_at_5_std
      value: 8.3698
    - type: nauc_mrr_at_5_diff1
      value: 45.1772
    - type: nauc_mrr_at_10_max
      value: 40.6102
    - type: nauc_mrr_at_10_std
      value: 8.9793
    - type: nauc_mrr_at_10_diff1
      value: 44.6458
    - type: nauc_mrr_at_20_max
      value: 40.5002
    - type: nauc_mrr_at_20_std
      value: 9.003
    - type: nauc_mrr_at_20_diff1
      value: 44.671
    - type: nauc_mrr_at_100_max
      value: 40.4429
    - type: nauc_mrr_at_100_std
      value: 9.131
    - type: nauc_mrr_at_100_diff1
      value: 44.728899999999996
    - type: nauc_mrr_at_1000_max
      value: 40.4634
    - type: nauc_mrr_at_1000_std
      value: 9.1018
    - type: nauc_mrr_at_1000_diff1
      value: 44.7656
    - type: main_score
      value: 44.065
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackRetrieval (default)
      revision: 160c094312a0e1facb97e55eeddb698c0abe3571
      split: test
      type: CQADupstackRetrieval_is_a_combined_dataset
    metrics:
    - type: ndcg_at_1
      value: 33.917750000000005
    - type: ndcg_at_3
      value: 39.253750000000004
    - type: ndcg_at_5
      value: 41.62250000000001
    - type: ndcg_at_10
      value: 44.29191666666667
    - type: ndcg_at_20
      value: 46.318083333333334
    - type: ndcg_at_100
      value: 49.489000000000004
    - type: ndcg_at_1000
      value: 51.534083333333335
    - type: map_at_1
      value: 28.50841666666667
    - type: map_at_3
      value: 35.52141666666667
    - type: map_at_5
      value: 37.228500000000004
    - type: map_at_10
      value: 38.61175
    - type: map_at_20
      value: 39.3125
    - type: map_at_100
      value: 39.882083333333334
    - type: map_at_1000
      value: 39.995916666666666
    - type: recall_at_1
      value: 28.50841666666667
    - type: recall_at_3
      value: 42.46875000000001
    - type: recall_at_5
      value: 48.59916666666667
    - type: recall_at_10
      value: 56.56024999999999
    - type: recall_at_20
      value: 63.96383333333333
    - type: recall_at_100
      value: 79.2645
    - type: recall_at_1000
      value: 93.25150000000002
    - type: precision_at_1
      value: 33.917750000000005
    - type: precision_at_3
      value: 18.19558333333333
    - type: precision_at_5
      value: 12.950166666666668
    - type: precision_at_10
      value: 7.866333333333333
    - type: precision_at_20
      value: 4.614749999999999
    - type: precision_at_100
      value: 1.2374166666666666
    - type: precision_at_1000
      value: 0.16091666666666668
    - type: mrr_at_1
      value: 33.917699999999996
    - type: mrr_at_3
      value: 40.448166666666665
    - type: mrr_at_5
      value: 41.903483333333334
    - type: mrr_at_10
      value: 42.944941666666665
    - type: mrr_at_20
      value: 43.43391666666666
    - type: mrr_at_100
      value: 43.782399999999996
    - type: mrr_at_1000
      value: 43.832325
    - type: nauc_ndcg_at_1_max
      value: 38.768750000000004
    - type: nauc_ndcg_at_1_std
      value: 0.5314750000000001
    - type: nauc_ndcg_at_1_diff1
      value: 50.18021666666667
    - type: nauc_ndcg_at_3_max
      value: 37.73569166666667
    - type: nauc_ndcg_at_3_std
      value: 1.9756250000000004
    - type: nauc_ndcg_at_3_diff1
      value: 45.217191666666665
    - type: nauc_ndcg_at_5_max
      value: 38.19843333333333
    - type: nauc_ndcg_at_5_std
      value: 2.760133333333333
    - type: nauc_ndcg_at_5_diff1
      value: 44.559908333333325
    - type: nauc_ndcg_at_10_max
      value: 38.34826666666667
    - type: nauc_ndcg_at_10_std
      value: 3.8177249999999994
    - type: nauc_ndcg_at_10_diff1
      value: 43.772149999999996
    - type: nauc_ndcg_at_20_max
      value: 38.53288333333333
    - type: nauc_ndcg_at_20_std
      value: 4.801466666666668
    - type: nauc_ndcg_at_20_diff1
      value: 43.312774999999995
    - type: nauc_ndcg_at_100_max
      value: 38.912774999999996
    - type: nauc_ndcg_at_100_std
      value: 6.39795
    - type: nauc_ndcg_at_100_diff1
      value: 43.38179166666667
    - type: nauc_ndcg_at_1000_max
      value: 39.0197
    - type: nauc_ndcg_at_1000_std
      value: 5.861708333333333
    - type: nauc_ndcg_at_1000_diff1
      value: 43.78785833333334
    - type: nauc_map_at_1_max
      value: 34.808508333333336
    - type: nauc_map_at_1_std
      value: -2.4239916666666663
    - type: nauc_map_at_1_diff1
      value: 51.88476666666666
    - type: nauc_map_at_3_max
      value: 36.516549999999995
    - type: nauc_map_at_3_std
      value: 0.008974999999999955
    - type: nauc_map_at_3_diff1
      value: 47.11013333333332
    - type: nauc_map_at_5_max
      value: 37.17583333333333
    - type: nauc_map_at_5_std
      value: 0.7668083333333334
    - type: nauc_map_at_5_diff1
      value: 46.496975
    - type: nauc_map_at_10_max
      value: 37.54620833333333
    - type: nauc_map_at_10_std
      value: 1.5577166666666666
    - type: nauc_map_at_10_diff1
      value: 46.02030833333334
    - type: nauc_map_at_20_max
      value: 37.738058333333335
    - type: nauc_map_at_20_std
      value: 2.0228750000000004
    - type: nauc_map_at_20_diff1
      value: 45.837608333333336
    - type: nauc_map_at_100_max
      value: 37.864575
    - type: nauc_map_at_100_std
      value: 2.3781916666666665
    - type: nauc_map_at_100_diff1
      value: 45.818783333333336
    - type: nauc_map_at_1000_max
      value: 37.8704
    - type: nauc_map_at_1000_std
      value: 2.403341666666667
    - type: nauc_map_at_1000_diff1
      value: 45.83103333333333
    - type: nauc_recall_at_1_max
      value: 34.808508333333336
    - type: nauc_recall_at_1_std
      value: -2.4239916666666663
    - type: nauc_recall_at_1_diff1
      value: 51.88476666666666
    - type: nauc_recall_at_3_max
      value: 35.12659166666666
    - type: nauc_recall_at_3_std
      value: 1.5866916666666664
    - type: nauc_recall_at_3_diff1
      value: 41.56113333333334
    - type: nauc_recall_at_5_max
      value: 36.147058333333334
    - type: nauc_recall_at_5_std
      value: 3.803583333333333
    - type: nauc_recall_at_5_diff1
      value: 39.051366666666674
    - type: nauc_recall_at_10_max
      value: 36.10466666666667
    - type: nauc_recall_at_10_std
      value: 7.102541666666666
    - type: nauc_recall_at_10_diff1
      value: 35.79460833333333
    - type: nauc_recall_at_20_max
      value: 36.25878333333333
    - type: nauc_recall_at_20_std
      value: 11.494475000000001
    - type: nauc_recall_at_20_diff1
      value: 33.06425833333333
    - type: nauc_recall_at_100_max
      value: 38.00966666666667
    - type: nauc_recall_at_100_std
      value: 27.040050000000004
    - type: nauc_recall_at_100_diff1
      value: 29.968625
    - type: nauc_recall_at_1000_max
      value: 45.32993333333334
    - type: nauc_recall_at_1000_std
      value: 45.327316666666675
    - type: nauc_recall_at_1000_diff1
      value: 28.088641666666668
    - type: nauc_precision_at_1_max
      value: 38.768750000000004
    - type: nauc_precision_at_1_std
      value: 0.5314750000000001
    - type: nauc_precision_at_1_diff1
      value: 50.18021666666667
    - type: nauc_precision_at_3_max
      value: 36.52460833333333
    - type: nauc_precision_at_3_std
      value: 7.665850000000001
    - type: nauc_precision_at_3_diff1
      value: 31.133191666666672
    - type: nauc_precision_at_5_max
      value: 35.20106666666667
    - type: nauc_precision_at_5_std
      value: 10.746766666666666
    - type: nauc_precision_at_5_diff1
      value: 24.582291666666663
    - type: nauc_precision_at_10_max
      value: 31.465108333333337
    - type: nauc_precision_at_10_std
      value: 15.019074999999999
    - type: nauc_precision_at_10_diff1
      value: 16.25574166666667
    - type: nauc_precision_at_20_max
      value: 27.589949999999995
    - type: nauc_precision_at_20_std
      value: 18.108775
    - type: nauc_precision_at_20_diff1
      value: 9.511666666666668
    - type: nauc_precision_at_100_max
      value: 17.18691666666667
    - type: nauc_precision_at_100_std
      value: 21.440466666666666
    - type: nauc_precision_at_100_diff1
      value: -1.2442166666666667
    - type: nauc_precision_at_1000_max
      value: 5.215425
    - type: nauc_precision_at_1000_std
      value: 13.896516666666663
    - type: nauc_precision_at_1000_diff1
      value: -10.446258333333335
    - type: nauc_mrr_at_1_max
      value: 38.768750000000004
    - type: nauc_mrr_at_1_std
      value: 0.5314750000000001
    - type: nauc_mrr_at_1_diff1
      value: 50.18021666666667
    - type: nauc_mrr_at_3_max
      value: 38.979308333333336
    - type: nauc_mrr_at_3_std
      value: 2.755991666666666
    - type: nauc_mrr_at_3_diff1
      value: 45.991875
    - type: nauc_mrr_at_5_max
      value: 39.26664166666667
    - type: nauc_mrr_at_5_std
      value: 3.2105333333333332
    - type: nauc_mrr_at_5_diff1
      value: 45.54448333333333
    - type: nauc_mrr_at_10_max
      value: 39.239558333333335
    - type: nauc_mrr_at_10_std
      value: 3.57125
    - type: nauc_mrr_at_10_diff1
      value: 45.24083333333333
    - type: nauc_mrr_at_20_max
      value: 39.212075
    - type: nauc_mrr_at_20_std
      value: 3.7281833333333334
    - type: nauc_mrr_at_20_diff1
      value: 45.153083333333335
    - type: nauc_mrr_at_100_max
      value: 39.221091666666666
    - type: nauc_mrr_at_100_std
      value: 3.823533333333333
    - type: nauc_mrr_at_100_diff1
      value: 45.19413333333333
    - type: nauc_mrr_at_1000_max
      value: 39.22478333333333
    - type: nauc_mrr_at_1000_std
      value: 3.8052833333333327
    - type: nauc_mrr_at_1000_diff1
      value: 45.21384166666667
    - type: main_score
      value: 44.29191666666667
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackRetrieval (default)
      revision: CQADupstackRetrieval_is_a_combined_dataset
      split: test
      type: CQADupstackRetrieval_is_a_combined_dataset
    metrics:
    - type: main_score
      value: 44.29191666666667
    - type: ndcg_at_10
      value: 44.29191666666667
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackStatsRetrieval (default)
      revision: 65ac3a16b8e91f9cee4c9828cc7c335575432a2a
      split: test
      type: mteb/cqadupstack-stats
    metrics:
    - type: ndcg_at_1
      value: 29.141000000000002
    - type: ndcg_at_3
      value: 33.861000000000004
    - type: ndcg_at_5
      value: 35.887
    - type: ndcg_at_10
      value: 38.596000000000004
    - type: ndcg_at_20
      value: 40.172000000000004
    - type: ndcg_at_100
      value: 43.375
    - type: ndcg_at_1000
      value: 45.562000000000005
    - type: map_at_1
      value: 25.728
    - type: map_at_3
      value: 31.268
    - type: map_at_5
      value: 32.596000000000004
    - type: map_at_10
      value: 33.903
    - type: map_at_20
      value: 34.392
    - type: map_at_100
      value: 34.853
    - type: map_at_1000
      value: 34.943999999999996
    - type: recall_at_1
      value: 25.728
    - type: recall_at_3
      value: 36.638
    - type: recall_at_5
      value: 41.689
    - type: recall_at_10
      value: 50.121
    - type: recall_at_20
      value: 56.043
    - type: recall_at_100
      value: 72.382
    - type: recall_at_1000
      value: 88.306
    - type: precision_at_1
      value: 29.141000000000002
    - type: precision_at_3
      value: 14.826
    - type: precision_at_5
      value: 10.428999999999998
    - type: precision_at_10
      value: 6.334
    - type: precision_at_20
      value: 3.589
    - type: precision_at_100
      value: 0.9520000000000001
    - type: precision_at_1000
      value: 0.121
    - type: mrr_at_1
      value: 29.141099999999998
    - type: mrr_at_3
      value: 34.407
    - type: mrr_at_5
      value: 35.68
    - type: mrr_at_10
      value: 36.739
    - type: mrr_at_20
      value: 37.1572
    - type: mrr_at_100
      value: 37.5448
    - type: mrr_at_1000
      value: 37.607600000000005
    - type: nauc_ndcg_at_1_max
      value: 43.0703
    - type: nauc_ndcg_at_1_std
      value: 7.8586
    - type: nauc_ndcg_at_1_diff1
      value: 57.5204
    - type: nauc_ndcg_at_3_max
      value: 41.7529
    - type: nauc_ndcg_at_3_std
      value: 8.549800000000001
    - type: nauc_ndcg_at_3_diff1
      value: 52.7211
    - type: nauc_ndcg_at_5_max
      value: 43.404399999999995
    - type: nauc_ndcg_at_5_std
      value: 9.117799999999999
    - type: nauc_ndcg_at_5_diff1
      value: 52.607400000000005
    - type: nauc_ndcg_at_10_max
      value: 43.8638
    - type: nauc_ndcg_at_10_std
      value: 10.7135
    - type: nauc_ndcg_at_10_diff1
      value: 50.7607
    - type: nauc_ndcg_at_20_max
      value: 43.3389
    - type: nauc_ndcg_at_20_std
      value: 11.7901
    - type: nauc_ndcg_at_20_diff1
      value: 50.056900000000006
    - type: nauc_ndcg_at_100_max
      value: 43.580600000000004
    - type: nauc_ndcg_at_100_std
      value: 13.616900000000001
    - type: nauc_ndcg_at_100_diff1
      value: 49.359700000000004
    - type: nauc_ndcg_at_1000_max
      value: 43.6164
    - type: nauc_ndcg_at_1000_std
      value: 13.5428
    - type: nauc_ndcg_at_1000_diff1
      value: 50.0821
    - type: nauc_map_at_1_max
      value: 40.5495
    - type: nauc_map_at_1_std
      value: 3.5229999999999997
    - type: nauc_map_at_1_diff1
      value: 59.7723
    - type: nauc_map_at_3_max
      value: 41.2977
    - type: nauc_map_at_3_std
      value: 6.9411000000000005
    - type: nauc_map_at_3_diff1
      value: 54.879999999999995
    - type: nauc_map_at_5_max
      value: 42.5686
    - type: nauc_map_at_5_std
      value: 7.8032
    - type: nauc_map_at_5_diff1
      value: 54.4624
    - type: nauc_map_at_10_max
      value: 43.1361
    - type: nauc_map_at_10_std
      value: 8.8783
    - type: nauc_map_at_10_diff1
      value: 53.747
    - type: nauc_map_at_20_max
      value: 42.9941
    - type: nauc_map_at_20_std
      value: 9.1777
    - type: nauc_map_at_20_diff1
      value: 53.5394
    - type: nauc_map_at_100_max
      value: 42.960300000000004
    - type: nauc_map_at_100_std
      value: 9.3584
    - type: nauc_map_at_100_diff1
      value: 53.3856
    - type: nauc_map_at_1000_max
      value: 42.9595
    - type: nauc_map_at_1000_std
      value: 9.3575
    - type: nauc_map_at_1000_diff1
      value: 53.4136
    - type: nauc_recall_at_1_max
      value: 40.5495
    - type: nauc_recall_at_1_std
      value: 3.5229999999999997
    - type: nauc_recall_at_1_diff1
      value: 59.7723
    - type: nauc_recall_at_3_max
      value: 39.5622
    - type: nauc_recall_at_3_std
      value: 7.614
    - type: nauc_recall_at_3_diff1
      value: 49.469
    - type: nauc_recall_at_5_max
      value: 43.086400000000005
    - type: nauc_recall_at_5_std
      value: 9.1332
    - type: nauc_recall_at_5_diff1
      value: 47.8829
    - type: nauc_recall_at_10_max
      value: 43.054700000000004
    - type: nauc_recall_at_10_std
      value: 13.116900000000001
    - type: nauc_recall_at_10_diff1
      value: 40.804
    - type: nauc_recall_at_20_max
      value: 40.8398
    - type: nauc_recall_at_20_std
      value: 17.099600000000002
    - type: nauc_recall_at_20_diff1
      value: 37.8978
    - type: nauc_recall_at_100_max
      value: 41.8268
    - type: nauc_recall_at_100_std
      value: 31.5507
    - type: nauc_recall_at_100_diff1
      value: 28.8246
    - type: nauc_recall_at_1000_max
      value: 44.7113
    - type: nauc_recall_at_1000_std
      value: 49.8697
    - type: nauc_recall_at_1000_diff1
      value: 26.7287
    - type: nauc_precision_at_1_max
      value: 43.0703
    - type: nauc_precision_at_1_std
      value: 7.8586
    - type: nauc_precision_at_1_diff1
      value: 57.5204
    - type: nauc_precision_at_3_max
      value: 41.098
    - type: nauc_precision_at_3_std
      value: 16.1082
    - type: nauc_precision_at_3_diff1
      value: 40.5806
    - type: nauc_precision_at_5_max
      value: 43.8705
    - type: nauc_precision_at_5_std
      value: 19.470299999999998
    - type: nauc_precision_at_5_diff1
      value: 36.9411
    - type: nauc_precision_at_10_max
      value: 41.5225
    - type: nauc_precision_at_10_std
      value: 22.9023
    - type: nauc_precision_at_10_diff1
      value: 28.0016
    - type: nauc_precision_at_20_max
      value: 36.68
    - type: nauc_precision_at_20_std
      value: 25.5411
    - type: nauc_precision_at_20_diff1
      value: 22.3414
    - type: nauc_precision_at_100_max
      value: 25.8805
    - type: nauc_precision_at_100_std
      value: 29.0719
    - type: nauc_precision_at_100_diff1
      value: 7.4353
    - type: nauc_precision_at_1000_max
      value: 12.2406
    - type: nauc_precision_at_1000_std
      value: 22.909
    - type: nauc_precision_at_1000_diff1
      value: -4.0427
    - type: nauc_mrr_at_1_max
      value: 43.0703
    - type: nauc_mrr_at_1_std
      value: 7.8586
    - type: nauc_mrr_at_1_diff1
      value: 57.5204
    - type: nauc_mrr_at_3_max
      value: 42.4962
    - type: nauc_mrr_at_3_std
      value: 9.9083
    - type: nauc_mrr_at_3_diff1
      value: 52.81
    - type: nauc_mrr_at_5_max
      value: 43.7188
    - type: nauc_mrr_at_5_std
      value: 10.2951
    - type: nauc_mrr_at_5_diff1
      value: 52.9848
    - type: nauc_mrr_at_10_max
      value: 43.6725
    - type: nauc_mrr_at_10_std
      value: 10.8946
    - type: nauc_mrr_at_10_diff1
      value: 52.037
    - type: nauc_mrr_at_20_max
      value: 43.4857
    - type: nauc_mrr_at_20_std
      value: 11.097700000000001
    - type: nauc_mrr_at_20_diff1
      value: 51.83560000000001
    - type: nauc_mrr_at_100_max
      value: 43.4906
    - type: nauc_mrr_at_100_std
      value: 11.2695
    - type: nauc_mrr_at_100_diff1
      value: 51.783500000000004
    - type: nauc_mrr_at_1000_max
      value: 43.490899999999996
    - type: nauc_mrr_at_1000_std
      value: 11.2507
    - type: nauc_mrr_at_1000_diff1
      value: 51.8107
    - type: main_score
      value: 38.596000000000004
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackTexRetrieval (default)
      revision: 46989137a86843e03a6195de44b09deda022eec7
      split: test
      type: mteb/cqadupstack-tex
    metrics:
    - type: ndcg_at_1
      value: 24.054000000000002
    - type: ndcg_at_3
      value: 29.115999999999996
    - type: ndcg_at_5
      value: 31.286
    - type: ndcg_at_10
      value: 33.722
    - type: ndcg_at_20
      value: 35.844
    - type: ndcg_at_100
      value: 39.361000000000004
    - type: ndcg_at_1000
      value: 42.064
    - type: map_at_1
      value: 19.911
    - type: map_at_3
      value: 25.874999999999996
    - type: map_at_5
      value: 27.403
    - type: map_at_10
      value: 28.559
    - type: map_at_20
      value: 29.213
    - type: map_at_100
      value: 29.784
    - type: map_at_1000
      value: 29.909999999999997
    - type: recall_at_1
      value: 19.911
    - type: recall_at_3
      value: 32.195
    - type: recall_at_5
      value: 37.818000000000005
    - type: recall_at_10
      value: 45.183
    - type: recall_at_20
      value: 53.081999999999994
    - type: recall_at_100
      value: 70.25
    - type: recall_at_1000
      value: 89.22200000000001
    - type: precision_at_1
      value: 24.054000000000002
    - type: precision_at_3
      value: 13.914000000000001
    - type: precision_at_5
      value: 10.069
    - type: precision_at_10
      value: 6.194
    - type: precision_at_20
      value: 3.7060000000000004
    - type: precision_at_100
      value: 1.058
    - type: precision_at_1000
      value: 0.148
    - type: mrr_at_1
      value: 24.0537
    - type: mrr_at_3
      value: 30.161700000000003
    - type: mrr_at_5
      value: 31.505499999999998
    - type: mrr_at_10
      value: 32.4828
    - type: mrr_at_20
      value: 33.054899999999996
    - type: mrr_at_100
      value: 33.4643
    - type: mrr_at_1000
      value: 33.534000000000006
    - type: nauc_ndcg_at_1_max
      value: 30.663200000000003
    - type: nauc_ndcg_at_1_std
      value: 1.6019999999999999
    - type: nauc_ndcg_at_1_diff1
      value: 45.730199999999996
    - type: nauc_ndcg_at_3_max
      value: 28.5124
    - type: nauc_ndcg_at_3_std
      value: 3.4572
    - type: nauc_ndcg_at_3_diff1
      value: 37.109500000000004
    - type: nauc_ndcg_at_5_max
      value: 28.8788
    - type: nauc_ndcg_at_5_std
      value: 4.5551
    - type: nauc_ndcg_at_5_diff1
      value: 36.1603
    - type: nauc_ndcg_at_10_max
      value: 28.4392
    - type: nauc_ndcg_at_10_std
      value: 5.1365
    - type: nauc_ndcg_at_10_diff1
      value: 34.6232
    - type: nauc_ndcg_at_20_max
      value: 28.4854
    - type: nauc_ndcg_at_20_std
      value: 6.6366
    - type: nauc_ndcg_at_20_diff1
      value: 34.5488
    - type: nauc_ndcg_at_100_max
      value: 29.17
    - type: nauc_ndcg_at_100_std
      value: 7.904
    - type: nauc_ndcg_at_100_diff1
      value: 34.7771
    - type: nauc_ndcg_at_1000_max
      value: 29.437
    - type: nauc_ndcg_at_1000_std
      value: 7.5479
    - type: nauc_ndcg_at_1000_diff1
      value: 35.605399999999996
    - type: nauc_map_at_1_max
      value: 28.6015
    - type: nauc_map_at_1_std
      value: 1.6265
    - type: nauc_map_at_1_diff1
      value: 46.170899999999996
    - type: nauc_map_at_3_max
      value: 27.931099999999997
    - type: nauc_map_at_3_std
      value: 3.3492
    - type: nauc_map_at_3_diff1
      value: 39.2592
    - type: nauc_map_at_5_max
      value: 28.268700000000003
    - type: nauc_map_at_5_std
      value: 3.9050000000000002
    - type: nauc_map_at_5_diff1
      value: 38.488299999999995
    - type: nauc_map_at_10_max
      value: 28.197400000000002
    - type: nauc_map_at_10_std
      value: 4.1464
    - type: nauc_map_at_10_diff1
      value: 37.7547
    - type: nauc_map_at_20_max
      value: 28.27
    - type: nauc_map_at_20_std
      value: 4.5844000000000005
    - type: nauc_map_at_20_diff1
      value: 37.7547
    - type: nauc_map_at_100_max
      value: 28.458
    - type: nauc_map_at_100_std
      value: 4.786300000000001
    - type: nauc_map_at_100_diff1
      value: 37.782199999999996
    - type: nauc_map_at_1000_max
      value: 28.4996
    - type: nauc_map_at_1000_std
      value: 4.7852
    - type: nauc_map_at_1000_diff1
      value: 37.816300000000005
    - type: nauc_recall_at_1_max
      value: 28.6015
    - type: nauc_recall_at_1_std
      value: 1.6265
    - type: nauc_recall_at_1_diff1
      value: 46.170899999999996
    - type: nauc_recall_at_3_max
      value: 25.9988
    - type: nauc_recall_at_3_std
      value: 4.1643
    - type: nauc_recall_at_3_diff1
      value: 31.9357
    - type: nauc_recall_at_5_max
      value: 26.6721
    - type: nauc_recall_at_5_std
      value: 6.1122000000000005
    - type: nauc_recall_at_5_diff1
      value: 29.1941
    - type: nauc_recall_at_10_max
      value: 24.9394
    - type: nauc_recall_at_10_std
      value: 7.313
    - type: nauc_recall_at_10_diff1
      value: 24.283099999999997
    - type: nauc_recall_at_20_max
      value: 24.3242
    - type: nauc_recall_at_20_std
      value: 12.6805
    - type: nauc_recall_at_20_diff1
      value: 22.8247
    - type: nauc_recall_at_100_max
      value: 26.917799999999996
    - type: nauc_recall_at_100_std
      value: 21.5069
    - type: nauc_recall_at_100_diff1
      value: 21.205
    - type: nauc_recall_at_1000_max
      value: 29.8594
    - type: nauc_recall_at_1000_std
      value: 31.4363
    - type: nauc_recall_at_1000_diff1
      value: 23.8707
    - type: nauc_precision_at_1_max
      value: 30.663200000000003
    - type: nauc_precision_at_1_std
      value: 1.6019999999999999
    - type: nauc_precision_at_1_diff1
      value: 45.730199999999996
    - type: nauc_precision_at_3_max
      value: 28.3435
    - type: nauc_precision_at_3_std
      value: 4.1368
    - type: nauc_precision_at_3_diff1
      value: 28.5551
    - type: nauc_precision_at_5_max
      value: 28.49
    - type: nauc_precision_at_5_std
      value: 5.8044
    - type: nauc_precision_at_5_diff1
      value: 24.5061
    - type: nauc_precision_at_10_max
      value: 26.255699999999997
    - type: nauc_precision_at_10_std
      value: 6.998799999999999
    - type: nauc_precision_at_10_diff1
      value: 18.3038
    - type: nauc_precision_at_20_max
      value: 25.217699999999997
    - type: nauc_precision_at_20_std
      value: 9.9304
    - type: nauc_precision_at_20_diff1
      value: 15.4876
    - type: nauc_precision_at_100_max
      value: 21.865499999999997
    - type: nauc_precision_at_100_std
      value: 10.746500000000001
    - type: nauc_precision_at_100_diff1
      value: 7.4687
    - type: nauc_precision_at_1000_max
      value: 18.4782
    - type: nauc_precision_at_1000_std
      value: 3.0096000000000003
    - type: nauc_precision_at_1000_diff1
      value: 3.3539
    - type: nauc_mrr_at_1_max
      value: 30.663200000000003
    - type: nauc_mrr_at_1_std
      value: 1.6019999999999999
    - type: nauc_mrr_at_1_diff1
      value: 45.730199999999996
    - type: nauc_mrr_at_3_max
      value: 29.9128
    - type: nauc_mrr_at_3_std
      value: 3.4235
    - type: nauc_mrr_at_3_diff1
      value: 39.1412
    - type: nauc_mrr_at_5_max
      value: 30.3311
    - type: nauc_mrr_at_5_std
      value: 4.0177
    - type: nauc_mrr_at_5_diff1
      value: 38.7065
    - type: nauc_mrr_at_10_max
      value: 30.144399999999997
    - type: nauc_mrr_at_10_std
      value: 4.2534
    - type: nauc_mrr_at_10_diff1
      value: 38.0266
    - type: nauc_mrr_at_20_max
      value: 30.1249
    - type: nauc_mrr_at_20_std
      value: 4.6181
    - type: nauc_mrr_at_20_diff1
      value: 38.002
    - type: nauc_mrr_at_100_max
      value: 30.1948
    - type: nauc_mrr_at_100_std
      value: 4.7099
    - type: nauc_mrr_at_100_diff1
      value: 38.0455
    - type: nauc_mrr_at_1000_max
      value: 30.1966
    - type: nauc_mrr_at_1000_std
      value: 4.6948
    - type: nauc_mrr_at_1000_diff1
      value: 38.0747
    - type: main_score
      value: 33.722
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackUnixRetrieval (default)
      revision: 6c6430d3a6d36f8d2a829195bc5dc94d7e063e53
      split: test
      type: mteb/cqadupstack-unix
    metrics:
    - type: ndcg_at_1
      value: 35.168
    - type: ndcg_at_3
      value: 39.972
    - type: ndcg_at_5
      value: 42.586
    - type: ndcg_at_10
      value: 46.071
    - type: ndcg_at_20
      value: 48.028999999999996
    - type: ndcg_at_100
      value: 51.351
    - type: ndcg_at_1000
      value: 53.169999999999995
    - type: map_at_1
      value: 29.819000000000003
    - type: map_at_3
      value: 36.571999999999996
    - type: map_at_5
      value: 38.385999999999996
    - type: map_at_10
      value: 40.073
    - type: map_at_20
      value: 40.72
    - type: map_at_100
      value: 41.289
    - type: map_at_1000
      value: 41.375
    - type: recall_at_1
      value: 29.819000000000003
    - type: recall_at_3
      value: 43.245
    - type: recall_at_5
      value: 49.931
    - type: recall_at_10
      value: 60.075
    - type: recall_at_20
      value: 67.118
    - type: recall_at_100
      value: 82.771
    - type: recall_at_1000
      value: 95.219
    - type: precision_at_1
      value: 35.168
    - type: precision_at_3
      value: 18.221
    - type: precision_at_5
      value: 12.892000000000001
    - type: precision_at_10
      value: 7.985
    - type: precision_at_20
      value: 4.529
    - type: precision_at_100
      value: 1.185
    - type: precision_at_1000
      value: 0.14400000000000002
    - type: mrr_at_1
      value: 35.1679
    - type: mrr_at_3
      value: 41.4024
    - type: mrr_at_5
      value: 43.039500000000004
    - type: mrr_at_10
      value: 44.3808
    - type: mrr_at_20
      value: 44.823299999999996
    - type: mrr_at_100
      value: 45.1914
    - type: mrr_at_1000
      value: 45.2339
    - type: nauc_ndcg_at_1_max
      value: 43.9321
    - type: nauc_ndcg_at_1_std
      value: -6.0145
    - type: nauc_ndcg_at_1_diff1
      value: 53.6293
    - type: nauc_ndcg_at_3_max
      value: 42.0025
    - type: nauc_ndcg_at_3_std
      value: -5.6881
    - type: nauc_ndcg_at_3_diff1
      value: 47.9461
    - type: nauc_ndcg_at_5_max
      value: 42.916900000000005
    - type: nauc_ndcg_at_5_std
      value: -4.2002999999999995
    - type: nauc_ndcg_at_5_diff1
      value: 48.0738
    - type: nauc_ndcg_at_10_max
      value: 42.6014
    - type: nauc_ndcg_at_10_std
      value: -2.8179
    - type: nauc_ndcg_at_10_diff1
      value: 46.792899999999996
    - type: nauc_ndcg_at_20_max
      value: 41.9182
    - type: nauc_ndcg_at_20_std
      value: -2.6714
    - type: nauc_ndcg_at_20_diff1
      value: 46.111000000000004
    - type: nauc_ndcg_at_100_max
      value: 42.6218
    - type: nauc_ndcg_at_100_std
      value: -1.6882000000000001
    - type: nauc_ndcg_at_100_diff1
      value: 46.3204
    - type: nauc_ndcg_at_1000_max
      value: 42.6413
    - type: nauc_ndcg_at_1000_std
      value: -2.2983
    - type: nauc_ndcg_at_1000_diff1
      value: 46.840399999999995
    - type: nauc_map_at_1_max
      value: 41.256
    - type: nauc_map_at_1_std
      value: -7.5877
    - type: nauc_map_at_1_diff1
      value: 56.383300000000006
    - type: nauc_map_at_3_max
      value: 41.904
    - type: nauc_map_at_3_std
      value: -6.548
    - type: nauc_map_at_3_diff1
      value: 50.7949
    - type: nauc_map_at_5_max
      value: 42.568400000000004
    - type: nauc_map_at_5_std
      value: -5.3873999999999995
    - type: nauc_map_at_5_diff1
      value: 50.3791
    - type: nauc_map_at_10_max
      value: 42.6619
    - type: nauc_map_at_10_std
      value: -4.8052
    - type: nauc_map_at_10_diff1
      value: 49.5933
    - type: nauc_map_at_20_max
      value: 42.4985
    - type: nauc_map_at_20_std
      value: -4.7620000000000005
    - type: nauc_map_at_20_diff1
      value: 49.3214
    - type: nauc_map_at_100_max
      value: 42.6165
    - type: nauc_map_at_100_std
      value: -4.595599999999999
    - type: nauc_map_at_100_diff1
      value: 49.277100000000004
    - type: nauc_map_at_1000_max
      value: 42.6146
    - type: nauc_map_at_1000_std
      value: -4.5920000000000005
    - type: nauc_map_at_1000_diff1
      value: 49.2815
    - type: nauc_recall_at_1_max
      value: 41.256
    - type: nauc_recall_at_1_std
      value: -7.5877
    - type: nauc_recall_at_1_diff1
      value: 56.383300000000006
    - type: nauc_recall_at_3_max
      value: 39.626099999999994
    - type: nauc_recall_at_3_std
      value: -5.973
    - type: nauc_recall_at_3_diff1
      value: 44.651
    - type: nauc_recall_at_5_max
      value: 41.4392
    - type: nauc_recall_at_5_std
      value: -1.8328
    - type: nauc_recall_at_5_diff1
      value: 42.928399999999996
    - type: nauc_recall_at_10_max
      value: 38.807
    - type: nauc_recall_at_10_std
      value: 2.863
    - type: nauc_recall_at_10_diff1
      value: 37.6663
    - type: nauc_recall_at_20_max
      value: 34.9705
    - type: nauc_recall_at_20_std
      value: 4.1407
    - type: nauc_recall_at_20_diff1
      value: 33.6156
    - type: nauc_recall_at_100_max
      value: 38.4049
    - type: nauc_recall_at_100_std
      value: 16.7735
    - type: nauc_recall_at_100_diff1
      value: 30.724800000000002
    - type: nauc_recall_at_1000_max
      value: 42.9152
    - type: nauc_recall_at_1000_std
      value: 32.1176
    - type: nauc_recall_at_1000_diff1
      value: 33.2582
    - type: nauc_precision_at_1_max
      value: 43.9321
    - type: nauc_precision_at_1_std
      value: -6.0145
    - type: nauc_precision_at_1_diff1
      value: 53.6293
    - type: nauc_precision_at_3_max
      value: 38.1748
    - type: nauc_precision_at_3_std
      value: -2.3163
    - type: nauc_precision_at_3_diff1
      value: 31.2502
    - type: nauc_precision_at_5_max
      value: 36.503
    - type: nauc_precision_at_5_std
      value: 2.0892
    - type: nauc_precision_at_5_diff1
      value: 25.249100000000002
    - type: nauc_precision_at_10_max
      value: 30.2104
    - type: nauc_precision_at_10_std
      value: 6.6937999999999995
    - type: nauc_precision_at_10_diff1
      value: 14.0684
    - type: nauc_precision_at_20_max
      value: 23.6494
    - type: nauc_precision_at_20_std
      value: 7.216500000000001
    - type: nauc_precision_at_20_diff1
      value: 6.7953
    - type: nauc_precision_at_100_max
      value: 11.2361
    - type: nauc_precision_at_100_std
      value: 11.824
    - type: nauc_precision_at_100_diff1
      value: -7.6405
    - type: nauc_precision_at_1000_max
      value: -3.8651
    - type: nauc_precision_at_1000_std
      value: 5.367999999999999
    - type: nauc_precision_at_1000_diff1
      value: -17.473
    - type: nauc_mrr_at_1_max
      value: 43.9321
    - type: nauc_mrr_at_1_std
      value: -6.0145
    - type: nauc_mrr_at_1_diff1
      value: 53.6293
    - type: nauc_mrr_at_3_max
      value: 42.8188
    - type: nauc_mrr_at_3_std
      value: -5.1393
    - type: nauc_mrr_at_3_diff1
      value: 48.3128
    - type: nauc_mrr_at_5_max
      value: 43.5383
    - type: nauc_mrr_at_5_std
      value: -4.2538
    - type: nauc_mrr_at_5_diff1
      value: 48.0319
    - type: nauc_mrr_at_10_max
      value: 43.121700000000004
    - type: nauc_mrr_at_10_std
      value: -3.7823
    - type: nauc_mrr_at_10_diff1
      value: 47.6064
    - type: nauc_mrr_at_20_max
      value: 42.8886
    - type: nauc_mrr_at_20_std
      value: -3.8175
    - type: nauc_mrr_at_20_diff1
      value: 47.5437
    - type: nauc_mrr_at_100_max
      value: 42.9514
    - type: nauc_mrr_at_100_std
      value: -3.8205000000000005
    - type: nauc_mrr_at_100_diff1
      value: 47.6513
    - type: nauc_mrr_at_1000_max
      value: 42.9567
    - type: nauc_mrr_at_1000_std
      value: -3.8327
    - type: nauc_mrr_at_1000_diff1
      value: 47.6603
    - type: main_score
      value: 46.071
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackWebmastersRetrieval (default)
      revision: 160c094312a0e1facb97e55eeddb698c0abe3571
      split: test
      type: mteb/cqadupstack-webmasters
    metrics:
    - type: ndcg_at_1
      value: 33.794000000000004
    - type: ndcg_at_3
      value: 38.442
    - type: ndcg_at_5
      value: 40.737
    - type: ndcg_at_10
      value: 43.832
    - type: ndcg_at_20
      value: 45.589
    - type: ndcg_at_100
      value: 49.514
    - type: ndcg_at_1000
      value: 51.742
    - type: map_at_1
      value: 28.409000000000002
    - type: map_at_3
      value: 34.337
    - type: map_at_5
      value: 35.985
    - type: map_at_10
      value: 37.621
    - type: map_at_20
      value: 38.391
    - type: map_at_100
      value: 39.233000000000004
    - type: map_at_1000
      value: 39.471000000000004
    - type: recall_at_1
      value: 28.409000000000002
    - type: recall_at_3
      value: 40.133
    - type: recall_at_5
      value: 45.913
    - type: recall_at_10
      value: 55.388000000000005
    - type: recall_at_20
      value: 62.134
    - type: recall_at_100
      value: 81.517
    - type: recall_at_1000
      value: 95.038
    - type: precision_at_1
      value: 33.794000000000004
    - type: precision_at_3
      value: 17.787
    - type: precision_at_5
      value: 13.241
    - type: precision_at_10
      value: 8.597000000000001
    - type: precision_at_20
      value: 5.267
    - type: precision_at_100
      value: 1.652
    - type: precision_at_1000
      value: 0.251
    - type: mrr_at_1
      value: 33.7945
    - type: mrr_at_3
      value: 39.5257
    - type: mrr_at_5
      value: 41.087
    - type: mrr_at_10
      value: 42.3491
    - type: mrr_at_20
      value: 42.7479
    - type: mrr_at_100
      value: 43.1961
    - type: mrr_at_1000
      value: 43.2373
    - type: nauc_ndcg_at_1_max
      value: 43.9886
    - type: nauc_ndcg_at_1_std
      value: 9.8923
    - type: nauc_ndcg_at_1_diff1
      value: 50.394000000000005
    - type: nauc_ndcg_at_3_max
      value: 43.074200000000005
    - type: nauc_ndcg_at_3_std
      value: 13.5108
    - type: nauc_ndcg_at_3_diff1
      value: 47.0674
    - type: nauc_ndcg_at_5_max
      value: 42.810700000000004
    - type: nauc_ndcg_at_5_std
      value: 14.119499999999999
    - type: nauc_ndcg_at_5_diff1
      value: 46.822
    - type: nauc_ndcg_at_10_max
      value: 43.533699999999996
    - type: nauc_ndcg_at_10_std
      value: 14.009599999999999
    - type: nauc_ndcg_at_10_diff1
      value: 47.3163
    - type: nauc_ndcg_at_20_max
      value: 44.4973
    - type: nauc_ndcg_at_20_std
      value: 14.5044
    - type: nauc_ndcg_at_20_diff1
      value: 47.2833
    - type: nauc_ndcg_at_100_max
      value: 44.7593
    - type: nauc_ndcg_at_100_std
      value: 16.833000000000002
    - type: nauc_ndcg_at_100_diff1
      value: 47.251599999999996
    - type: nauc_ndcg_at_1000_max
      value: 44.790600000000005
    - type: nauc_ndcg_at_1000_std
      value: 15.987199999999998
    - type: nauc_ndcg_at_1000_diff1
      value: 47.4071
    - type: nauc_map_at_1_max
      value: 43.4155
    - type: nauc_map_at_1_std
      value: 6.3514
    - type: nauc_map_at_1_diff1
      value: 54.8257
    - type: nauc_map_at_3_max
      value: 43.1906
    - type: nauc_map_at_3_std
      value: 9.823
    - type: nauc_map_at_3_diff1
      value: 49.5974
    - type: nauc_map_at_5_max
      value: 43.1564
    - type: nauc_map_at_5_std
      value: 10.3498
    - type: nauc_map_at_5_diff1
      value: 48.7876
    - type: nauc_map_at_10_max
      value: 43.6805
    - type: nauc_map_at_10_std
      value: 10.844199999999999
    - type: nauc_map_at_10_diff1
      value: 48.5759
    - type: nauc_map_at_20_max
      value: 44.121700000000004
    - type: nauc_map_at_20_std
      value: 11.6161
    - type: nauc_map_at_20_diff1
      value: 48.4631
    - type: nauc_map_at_100_max
      value: 44.1124
    - type: nauc_map_at_100_std
      value: 12.439
    - type: nauc_map_at_100_diff1
      value: 48.4742
    - type: nauc_map_at_1000_max
      value: 44.0146
    - type: nauc_map_at_1000_std
      value: 12.708
    - type: nauc_map_at_1000_diff1
      value: 48.5587
    - type: nauc_recall_at_1_max
      value: 43.4155
    - type: nauc_recall_at_1_std
      value: 6.3514
    - type: nauc_recall_at_1_diff1
      value: 54.8257
    - type: nauc_recall_at_3_max
      value: 40.941300000000005
    - type: nauc_recall_at_3_std
      value: 12.864700000000001
    - type: nauc_recall_at_3_diff1
      value: 44.642900000000004
    - type: nauc_recall_at_5_max
      value: 39.6961
    - type: nauc_recall_at_5_std
      value: 13.6938
    - type: nauc_recall_at_5_diff1
      value: 42.142
    - type: nauc_recall_at_10_max
      value: 40.2068
    - type: nauc_recall_at_10_std
      value: 14.1258
    - type: nauc_recall_at_10_diff1
      value: 42.244
    - type: nauc_recall_at_20_max
      value: 42.7956
    - type: nauc_recall_at_20_std
      value: 17.518
    - type: nauc_recall_at_20_diff1
      value: 42.3104
    - type: nauc_recall_at_100_max
      value: 43.4746
    - type: nauc_recall_at_100_std
      value: 39.7613
    - type: nauc_recall_at_100_diff1
      value: 40.5005
    - type: nauc_recall_at_1000_max
      value: 58.044
    - type: nauc_recall_at_1000_std
      value: 56.4975
    - type: nauc_recall_at_1000_diff1
      value: 40.238600000000005
    - type: nauc_precision_at_1_max
      value: 43.9886
    - type: nauc_precision_at_1_std
      value: 9.8923
    - type: nauc_precision_at_1_diff1
      value: 50.394000000000005
    - type: nauc_precision_at_3_max
      value: 37.436
    - type: nauc_precision_at_3_std
      value: 19.9652
    - type: nauc_precision_at_3_diff1
      value: 31.1933
    - type: nauc_precision_at_5_max
      value: 32.124900000000004
    - type: nauc_precision_at_5_std
      value: 22.8439
    - type: nauc_precision_at_5_diff1
      value: 23.325699999999998
    - type: nauc_precision_at_10_max
      value: 26.956200000000003
    - type: nauc_precision_at_10_std
      value: 24.7414
    - type: nauc_precision_at_10_diff1
      value: 15.1951
    - type: nauc_precision_at_20_max
      value: 20.924799999999998
    - type: nauc_precision_at_20_std
      value: 27.1802
    - type: nauc_precision_at_20_diff1
      value: 8.575800000000001
    - type: nauc_precision_at_100_max
      value: 3.8554
    - type: nauc_precision_at_100_std
      value: 32.46
    - type: nauc_precision_at_100_diff1
      value: 1.1094
    - type: nauc_precision_at_1000_max
      value: -4.0572
    - type: nauc_precision_at_1000_std
      value: 29.813499999999998
    - type: nauc_precision_at_1000_diff1
      value: 0.7384
    - type: nauc_mrr_at_1_max
      value: 43.9886
    - type: nauc_mrr_at_1_std
      value: 9.8923
    - type: nauc_mrr_at_1_diff1
      value: 50.394000000000005
    - type: nauc_mrr_at_3_max
      value: 43.5962
    - type: nauc_mrr_at_3_std
      value: 13.738
    - type: nauc_mrr_at_3_diff1
      value: 46.9918
    - type: nauc_mrr_at_5_max
      value: 43.6259
    - type: nauc_mrr_at_5_std
      value: 13.3696
    - type: nauc_mrr_at_5_diff1
      value: 46.7241
    - type: nauc_mrr_at_10_max
      value: 43.7969
    - type: nauc_mrr_at_10_std
      value: 13.477500000000001
    - type: nauc_mrr_at_10_diff1
      value: 47.125499999999995
    - type: nauc_mrr_at_20_max
      value: 43.8469
    - type: nauc_mrr_at_20_std
      value: 13.5156
    - type: nauc_mrr_at_20_diff1
      value: 47.088
    - type: nauc_mrr_at_100_max
      value: 43.8068
    - type: nauc_mrr_at_100_std
      value: 13.7051
    - type: nauc_mrr_at_100_diff1
      value: 47.153600000000004
    - type: nauc_mrr_at_1000_max
      value: 43.8016
    - type: nauc_mrr_at_1000_std
      value: 13.661999999999999
    - type: nauc_mrr_at_1000_diff1
      value: 47.1571
    - type: main_score
      value: 43.832
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CQADupstackWordpressRetrieval (default)
      revision: 4ffe81d471b1924886b33c7567bfb200e9eec5c4
      split: test
      type: mteb/cqadupstack-wordpress
    metrics:
    - type: ndcg_at_1
      value: 26.247999999999998
    - type: ndcg_at_3
      value: 31.799
    - type: ndcg_at_5
      value: 34.563
    - type: ndcg_at_10
      value: 36.889
    - type: ndcg_at_20
      value: 39.330999999999996
    - type: ndcg_at_100
      value: 42.426
    - type: ndcg_at_1000
      value: 44.745000000000005
    - type: map_at_1
      value: 24.067
    - type: map_at_3
      value: 29.492
    - type: map_at_5
      value: 31.11
    - type: map_at_10
      value: 32.184000000000005
    - type: map_at_20
      value: 32.903
    - type: map_at_100
      value: 33.357
    - type: map_at_1000
      value: 33.458
    - type: recall_at_1
      value: 24.067
    - type: recall_at_3
      value: 36.272
    - type: recall_at_5
      value: 42.77
    - type: recall_at_10
      value: 49.344
    - type: recall_at_20
      value: 58.46
    - type: recall_at_100
      value: 74.11999999999999
    - type: recall_at_1000
      value: 91.276
    - type: precision_at_1
      value: 26.247999999999998
    - type: precision_at_3
      value: 13.309000000000001
    - type: precision_at_5
      value: 9.649000000000001
    - type: precision_at_10
      value: 5.712
    - type: precision_at_20
      value: 3.466
    - type: precision_at_100
      value: 0.915
    - type: precision_at_1000
      value: 0.123
    - type: mrr_at_1
      value: 26.247700000000002
    - type: mrr_at_3
      value: 31.638899999999996
    - type: mrr_at_5
      value: 33.1824
    - type: mrr_at_10
      value: 34.1493
    - type: mrr_at_20
      value: 34.7716
    - type: mrr_at_100
      value: 35.1893
    - type: mrr_at_1000
      value: 35.2507
    - type: nauc_ndcg_at_1_max
      value: 36.3215
    - type: nauc_ndcg_at_1_std
      value: 0.6172000000000001
    - type: nauc_ndcg_at_1_diff1
      value: 50.767799999999994
    - type: nauc_ndcg_at_3_max
      value: 32.5903
    - type: nauc_ndcg_at_3_std
      value: 2.5009
    - type: nauc_ndcg_at_3_diff1
      value: 44.7412
    - type: nauc_ndcg_at_5_max
      value: 32.616499999999995
    - type: nauc_ndcg_at_5_std
      value: 2.2826
    - type: nauc_ndcg_at_5_diff1
      value: 41.7193
    - type: nauc_ndcg_at_10_max
      value: 32.063399999999994
    - type: nauc_ndcg_at_10_std
      value: 2.7484
    - type: nauc_ndcg_at_10_diff1
      value: 40.9919
    - type: nauc_ndcg_at_20_max
      value: 32.6337
    - type: nauc_ndcg_at_20_std
      value: 3.6401000000000003
    - type: nauc_ndcg_at_20_diff1
      value: 39.4371
    - type: nauc_ndcg_at_100_max
      value: 33.4504
    - type: nauc_ndcg_at_100_std
      value: 6.5571
    - type: nauc_ndcg_at_100_diff1
      value: 40.103899999999996
    - type: nauc_ndcg_at_1000_max
      value: 33.413399999999996
    - type: nauc_ndcg_at_1000_std
      value: 6.1167
    - type: nauc_ndcg_at_1000_diff1
      value: 40.3296
    - type: nauc_map_at_1_max
      value: 33.9516
    - type: nauc_map_at_1_std
      value: -2.0814
    - type: nauc_map_at_1_diff1
      value: 51.6831
    - type: nauc_map_at_3_max
      value: 32.4114
    - type: nauc_map_at_3_std
      value: 0.9002
    - type: nauc_map_at_3_diff1
      value: 46.3164
    - type: nauc_map_at_5_max
      value: 32.7406
    - type: nauc_map_at_5_std
      value: 0.9598000000000001
    - type: nauc_map_at_5_diff1
      value: 44.576100000000004
    - type: nauc_map_at_10_max
      value: 32.669
    - type: nauc_map_at_10_std
      value: 1.4043
    - type: nauc_map_at_10_diff1
      value: 44.1697
    - type: nauc_map_at_20_max
      value: 32.807199999999995
    - type: nauc_map_at_20_std
      value: 1.7632999999999999
    - type: nauc_map_at_20_diff1
      value: 43.745400000000004
    - type: nauc_map_at_100_max
      value: 32.9749
    - type: nauc_map_at_100_std
      value: 2.1647
    - type: nauc_map_at_100_diff1
      value: 43.8445
    - type: nauc_map_at_1000_max
      value: 32.9631
    - type: nauc_map_at_1000_std
      value: 2.164
    - type: nauc_map_at_1000_diff1
      value: 43.8217
    - type: nauc_recall_at_1_max
      value: 33.9516
    - type: nauc_recall_at_1_std
      value: -2.0814
    - type: nauc_recall_at_1_diff1
      value: 51.6831
    - type: nauc_recall_at_3_max
      value: 30.248199999999997
    - type: nauc_recall_at_3_std
      value: 4.3766
    - type: nauc_recall_at_3_diff1
      value: 40.7147
    - type: nauc_recall_at_5_max
      value: 29.749799999999997
    - type: nauc_recall_at_5_std
      value: 3.739
    - type: nauc_recall_at_5_diff1
      value: 33.4515
    - type: nauc_recall_at_10_max
      value: 27.8039
    - type: nauc_recall_at_10_std
      value: 4.3235
    - type: nauc_recall_at_10_diff1
      value: 31.706200000000003
    - type: nauc_recall_at_20_max
      value: 29.4726
    - type: nauc_recall_at_20_std
      value: 7.2537
    - type: nauc_recall_at_20_diff1
      value: 24.763099999999998
    - type: nauc_recall_at_100_max
      value: 32.6767
    - type: nauc_recall_at_100_std
      value: 28.704400000000003
    - type: nauc_recall_at_100_diff1
      value: 23.6186
    - type: nauc_recall_at_1000_max
      value: 35.3748
    - type: nauc_recall_at_1000_std
      value: 49.2642
    - type: nauc_recall_at_1000_diff1
      value: 15.0664
    - type: nauc_precision_at_1_max
      value: 36.3215
    - type: nauc_precision_at_1_std
      value: 0.6172000000000001
    - type: nauc_precision_at_1_diff1
      value: 50.767799999999994
    - type: nauc_precision_at_3_max
      value: 32.4313
    - type: nauc_precision_at_3_std
      value: 6.8161
    - type: nauc_precision_at_3_diff1
      value: 39.4056
    - type: nauc_precision_at_5_max
      value: 32.1058
    - type: nauc_precision_at_5_std
      value: 7.5455
    - type: nauc_precision_at_5_diff1
      value: 29.119899999999998
    - type: nauc_precision_at_10_max
      value: 29.9078
    - type: nauc_precision_at_10_std
      value: 11.8851
    - type: nauc_precision_at_10_diff1
      value: 22.5166
    - type: nauc_precision_at_20_max
      value: 29.212300000000003
    - type: nauc_precision_at_20_std
      value: 16.1047
    - type: nauc_precision_at_20_diff1
      value: 12.209299999999999
    - type: nauc_precision_at_100_max
      value: 24.7982
    - type: nauc_precision_at_100_std
      value: 29.3162
    - type: nauc_precision_at_100_diff1
      value: 0.8240000000000001
    - type: nauc_precision_at_1000_max
      value: -0.8333
    - type: nauc_precision_at_1000_std
      value: 17.0877
    - type: nauc_precision_at_1000_diff1
      value: -25.4924
    - type: nauc_mrr_at_1_max
      value: 36.3215
    - type: nauc_mrr_at_1_std
      value: 0.6172000000000001
    - type: nauc_mrr_at_1_diff1
      value: 50.767799999999994
    - type: nauc_mrr_at_3_max
      value: 34.7464
    - type: nauc_mrr_at_3_std
      value: 2.9025
    - type: nauc_mrr_at_3_diff1
      value: 45.7566
    - type: nauc_mrr_at_5_max
      value: 34.454
    - type: nauc_mrr_at_5_std
      value: 2.9497
    - type: nauc_mrr_at_5_diff1
      value: 43.948
    - type: nauc_mrr_at_10_max
      value: 34.1548
    - type: nauc_mrr_at_10_std
      value: 3.0771
    - type: nauc_mrr_at_10_diff1
      value: 43.626599999999996
    - type: nauc_mrr_at_20_max
      value: 34.3061
    - type: nauc_mrr_at_20_std
      value: 3.2359999999999998
    - type: nauc_mrr_at_20_diff1
      value: 43.2516
    - type: nauc_mrr_at_100_max
      value: 34.3776
    - type: nauc_mrr_at_100_std
      value: 3.5534999999999997
    - type: nauc_mrr_at_100_diff1
      value: 43.432900000000004
    - type: nauc_mrr_at_1000_max
      value: 34.3807
    - type: nauc_mrr_at_1000_std
      value: 3.5423999999999998
    - type: nauc_mrr_at_1000_diff1
      value: 43.4448
    - type: main_score
      value: 36.889
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB ClimateFEVER (default)
      revision: 47f2ac6acb640fc46020b02a5b59fdda04d39380
      split: test
      type: mteb/climate-fever
    metrics:
    - type: ndcg_at_1
      value: 29.837000000000003
    - type: ndcg_at_3
      value: 25.392
    - type: ndcg_at_5
      value: 27.153
    - type: ndcg_at_10
      value: 30.263
    - type: ndcg_at_20
      value: 33.073
    - type: ndcg_at_100
      value: 37.228
    - type: ndcg_at_1000
      value: 40.677
    - type: map_at_1
      value: 13.189
    - type: map_at_3
      value: 18.512999999999998
    - type: map_at_5
      value: 20.212
    - type: map_at_10
      value: 21.789
    - type: map_at_20
      value: 22.787
    - type: map_at_100
      value: 23.580000000000002
    - type: map_at_1000
      value: 23.772
    - type: recall_at_1
      value: 13.189
    - type: recall_at_3
      value: 23.255
    - type: recall_at_5
      value: 28.445999999999998
    - type: recall_at_10
      value: 35.355
    - type: recall_at_20
      value: 43.187999999999995
    - type: recall_at_100
      value: 59.255
    - type: recall_at_1000
      value: 78.637
    - type: precision_at_1
      value: 29.837000000000003
    - type: precision_at_3
      value: 18.545
    - type: precision_at_5
      value: 14.241000000000001
    - type: precision_at_10
      value: 9.179
    - type: precision_at_20
      value: 5.808
    - type: precision_at_100
      value: 1.659
    - type: precision_at_1000
      value: 0.22999999999999998
    - type: mrr_at_1
      value: 29.8371
    - type: mrr_at_3
      value: 38.2845
    - type: mrr_at_5
      value: 40.300799999999995
    - type: mrr_at_10
      value: 41.3765
    - type: mrr_at_20
      value: 41.958400000000005
    - type: mrr_at_100
      value: 42.281600000000005
    - type: mrr_at_1000
      value: 42.3193
    - type: nauc_ndcg_at_1_max
      value: 29.676000000000002
    - type: nauc_ndcg_at_1_std
      value: 20.4771
    - type: nauc_ndcg_at_1_diff1
      value: 22.0866
    - type: nauc_ndcg_at_3_max
      value: 34.3256
    - type: nauc_ndcg_at_3_std
      value: 18.886400000000002
    - type: nauc_ndcg_at_3_diff1
      value: 19.692999999999998
    - type: nauc_ndcg_at_5_max
      value: 36.709599999999995
    - type: nauc_ndcg_at_5_std
      value: 21.857
    - type: nauc_ndcg_at_5_diff1
      value: 20.2605
    - type: nauc_ndcg_at_10_max
      value: 36.951699999999995
    - type: nauc_ndcg_at_10_std
      value: 24.1201
    - type: nauc_ndcg_at_10_diff1
      value: 19.5268
    - type: nauc_ndcg_at_20_max
      value: 37.2598
    - type: nauc_ndcg_at_20_std
      value: 26.072699999999998
    - type: nauc_ndcg_at_20_diff1
      value: 18.5947
    - type: nauc_ndcg_at_100_max
      value: 37.5131
    - type: nauc_ndcg_at_100_std
      value: 27.3519
    - type: nauc_ndcg_at_100_diff1
      value: 18.7028
    - type: nauc_ndcg_at_1000_max
      value: 37.4262
    - type: nauc_ndcg_at_1000_std
      value: 27.158700000000003
    - type: nauc_ndcg_at_1000_diff1
      value: 19.2395
    - type: nauc_map_at_1_max
      value: 32.2132
    - type: nauc_map_at_1_std
      value: 15.244
    - type: nauc_map_at_1_diff1
      value: 26.2965
    - type: nauc_map_at_3_max
      value: 35.157
    - type: nauc_map_at_3_std
      value: 16.8008
    - type: nauc_map_at_3_diff1
      value: 21.7011
    - type: nauc_map_at_5_max
      value: 36.0907
    - type: nauc_map_at_5_std
      value: 19.0433
    - type: nauc_map_at_5_diff1
      value: 21.5595
    - type: nauc_map_at_10_max
      value: 36.1498
    - type: nauc_map_at_10_std
      value: 20.7259
    - type: nauc_map_at_10_diff1
      value: 20.816599999999998
    - type: nauc_map_at_20_max
      value: 36.365199999999994
    - type: nauc_map_at_20_std
      value: 21.6367
    - type: nauc_map_at_20_diff1
      value: 20.4563
    - type: nauc_map_at_100_max
      value: 36.503600000000006
    - type: nauc_map_at_100_std
      value: 22.020200000000003
    - type: nauc_map_at_100_diff1
      value: 20.5135
    - type: nauc_map_at_1000_max
      value: 36.4843
    - type: nauc_map_at_1000_std
      value: 22.0155
    - type: nauc_map_at_1000_diff1
      value: 20.5659
    - type: nauc_recall_at_1_max
      value: 32.2132
    - type: nauc_recall_at_1_std
      value: 15.244
    - type: nauc_recall_at_1_diff1
      value: 26.2965
    - type: nauc_recall_at_3_max
      value: 34.6294
    - type: nauc_recall_at_3_std
      value: 16.517200000000003
    - type: nauc_recall_at_3_diff1
      value: 16.6413
    - type: nauc_recall_at_5_max
      value: 35.938700000000004
    - type: nauc_recall_at_5_std
      value: 21.1943
    - type: nauc_recall_at_5_diff1
      value: 16.702
    - type: nauc_recall_at_10_max
      value: 34.956900000000005
    - type: nauc_recall_at_10_std
      value: 24.6739
    - type: nauc_recall_at_10_diff1
      value: 14.4465
    - type: nauc_recall_at_20_max
      value: 33.873799999999996
    - type: nauc_recall_at_20_std
      value: 27.9903
    - type: nauc_recall_at_20_diff1
      value: 11.1114
    - type: nauc_recall_at_100_max
      value: 33.123799999999996
    - type: nauc_recall_at_100_std
      value: 31.4933
    - type: nauc_recall_at_100_diff1
      value: 10.3246
    - type: nauc_recall_at_1000_max
      value: 32.9304
    - type: nauc_recall_at_1000_std
      value: 33.5144
    - type: nauc_recall_at_1000_diff1
      value: 10.810699999999999
    - type: nauc_precision_at_1_max
      value: 29.676000000000002
    - type: nauc_precision_at_1_std
      value: 20.4771
    - type: nauc_precision_at_1_diff1
      value: 22.0866
    - type: nauc_precision_at_3_max
      value: 32.0765
    - type: nauc_precision_at_3_std
      value: 20.6039
    - type: nauc_precision_at_3_diff1
      value: 13.585700000000001
    - type: nauc_precision_at_5_max
      value: 33.5445
    - type: nauc_precision_at_5_std
      value: 26.567400000000003
    - type: nauc_precision_at_5_diff1
      value: 14.421700000000001
    - type: nauc_precision_at_10_max
      value: 29.520200000000003
    - type: nauc_precision_at_10_std
      value: 28.8453
    - type: nauc_precision_at_10_diff1
      value: 11.2529
    - type: nauc_precision_at_20_max
      value: 25.610300000000002
    - type: nauc_precision_at_20_std
      value: 30.6799
    - type: nauc_precision_at_20_diff1
      value: 6.8877
    - type: nauc_precision_at_100_max
      value: 18.3639
    - type: nauc_precision_at_100_std
      value: 28.2568
    - type: nauc_precision_at_100_diff1
      value: 3.8568
    - type: nauc_precision_at_1000_max
      value: 6.9706
    - type: nauc_precision_at_1000_std
      value: 18.9339
    - type: nauc_precision_at_1000_diff1
      value: 0.6999
    - type: nauc_mrr_at_1_max
      value: 29.676000000000002
    - type: nauc_mrr_at_1_std
      value: 20.4771
    - type: nauc_mrr_at_1_diff1
      value: 22.0866
    - type: nauc_mrr_at_3_max
      value: 32.559900000000006
    - type: nauc_mrr_at_3_std
      value: 22.1817
    - type: nauc_mrr_at_3_diff1
      value: 19.1362
    - type: nauc_mrr_at_5_max
      value: 33.692299999999996
    - type: nauc_mrr_at_5_std
      value: 23.5179
    - type: nauc_mrr_at_5_diff1
      value: 19.9908
    - type: nauc_mrr_at_10_max
      value: 33.6748
    - type: nauc_mrr_at_10_std
      value: 23.624200000000002
    - type: nauc_mrr_at_10_diff1
      value: 19.969
    - type: nauc_mrr_at_20_max
      value: 33.562599999999996
    - type: nauc_mrr_at_20_std
      value: 23.776
    - type: nauc_mrr_at_20_diff1
      value: 19.8259
    - type: nauc_mrr_at_100_max
      value: 33.4998
    - type: nauc_mrr_at_100_std
      value: 23.7432
    - type: nauc_mrr_at_100_diff1
      value: 19.8137
    - type: nauc_mrr_at_1000_max
      value: 33.4876
    - type: nauc_mrr_at_1000_std
      value: 23.719199999999997
    - type: nauc_mrr_at_1000_diff1
      value: 19.817
    - type: main_score
      value: 30.263
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CodeFeedbackMT (default)
      revision: b0f12fa0c0dd67f59c95a5c33d02aeeb4c398c5f
      split: test
      type: CoIR-Retrieval/codefeedback-mt
    metrics:
    - type: ndcg_at_1
      value: 27.002
    - type: ndcg_at_3
      value: 33.597
    - type: ndcg_at_5
      value: 35.75
    - type: ndcg_at_10
      value: 37.757000000000005
    - type: ndcg_at_20
      value: 39.36
    - type: ndcg_at_100
      value: 41.806
    - type: ndcg_at_1000
      value: 43.675000000000004
    - type: map_at_1
      value: 27.002
    - type: map_at_3
      value: 31.964
    - type: map_at_5
      value: 33.158
    - type: map_at_10
      value: 33.988
    - type: map_at_20
      value: 34.43
    - type: map_at_100
      value: 34.760000000000005
    - type: map_at_1000
      value: 34.821999999999996
    - type: recall_at_1
      value: 27.002
    - type: recall_at_3
      value: 38.329
    - type: recall_at_5
      value: 43.557
    - type: recall_at_10
      value: 49.755
    - type: recall_at_20
      value: 56.082
    - type: recall_at_100
      value: 69.376
    - type: recall_at_1000
      value: 84.56
    - type: precision_at_1
      value: 27.002
    - type: precision_at_3
      value: 12.776000000000002
    - type: precision_at_5
      value: 8.711
    - type: precision_at_10
      value: 4.976
    - type: precision_at_20
      value: 2.804
    - type: precision_at_100
      value: 0.694
    - type: precision_at_1000
      value: 0.08499999999999999
    - type: mrr_at_1
      value: 27.001599999999996
    - type: mrr_at_3
      value: 31.9638
    - type: mrr_at_5
      value: 33.158300000000004
    - type: mrr_at_10
      value: 33.9877
    - type: mrr_at_20
      value: 34.429700000000004
    - type: mrr_at_100
      value: 34.760200000000005
    - type: mrr_at_1000
      value: 34.822399999999995
    - type: nauc_ndcg_at_1_max
      value: 14.691199999999998
    - type: nauc_ndcg_at_1_std
      value: -18.2481
    - type: nauc_ndcg_at_1_diff1
      value: 51.82940000000001
    - type: nauc_ndcg_at_3_max
      value: 15.9155
    - type: nauc_ndcg_at_3_std
      value: -18.21
    - type: nauc_ndcg_at_3_diff1
      value: 46.4667
    - type: nauc_ndcg_at_5_max
      value: 16.2958
    - type: nauc_ndcg_at_5_std
      value: -17.8939
    - type: nauc_ndcg_at_5_diff1
      value: 45.4591
    - type: nauc_ndcg_at_10_max
      value: 16.6542
    - type: nauc_ndcg_at_10_std
      value: -17.121
    - type: nauc_ndcg_at_10_diff1
      value: 44.5803
    - type: nauc_ndcg_at_20_max
      value: 17.210800000000003
    - type: nauc_ndcg_at_20_std
      value: -16.3918
    - type: nauc_ndcg_at_20_diff1
      value: 44.0927
    - type: nauc_ndcg_at_100_max
      value: 17.8597
    - type: nauc_ndcg_at_100_std
      value: -14.35
    - type: nauc_ndcg_at_100_diff1
      value: 43.561
    - type: nauc_ndcg_at_1000_max
      value: 18.0753
    - type: nauc_ndcg_at_1000_std
      value: -13.827300000000001
    - type: nauc_ndcg_at_1000_diff1
      value: 43.9433
    - type: nauc_map_at_1_max
      value: 14.691199999999998
    - type: nauc_map_at_1_std
      value: -18.2481
    - type: nauc_map_at_1_diff1
      value: 51.82940000000001
    - type: nauc_map_at_3_max
      value: 15.657099999999998
    - type: nauc_map_at_3_std
      value: -18.253700000000002
    - type: nauc_map_at_3_diff1
      value: 47.749399999999994
    - type: nauc_map_at_5_max
      value: 15.8683
    - type: nauc_map_at_5_std
      value: -18.0718
    - type: nauc_map_at_5_diff1
      value: 47.176899999999996
    - type: nauc_map_at_10_max
      value: 16.0118
    - type: nauc_map_at_10_std
      value: -17.7494
    - type: nauc_map_at_10_diff1
      value: 46.818799999999996
    - type: nauc_map_at_20_max
      value: 16.1658
    - type: nauc_map_at_20_std
      value: -17.552400000000002
    - type: nauc_map_at_20_diff1
      value: 46.694
    - type: nauc_map_at_100_max
      value: 16.2407
    - type: nauc_map_at_100_std
      value: -17.289099999999998
    - type: nauc_map_at_100_diff1
      value: 46.6325
    - type: nauc_map_at_1000_max
      value: 16.2491
    - type: nauc_map_at_1000_std
      value: -17.2655
    - type: nauc_map_at_1000_diff1
      value: 46.646300000000004
    - type: nauc_recall_at_1_max
      value: 14.691199999999998
    - type: nauc_recall_at_1_std
      value: -18.2481
    - type: nauc_recall_at_1_diff1
      value: 51.82940000000001
    - type: nauc_recall_at_3_max
      value: 16.6167
    - type: nauc_recall_at_3_std
      value: -18.0762
    - type: nauc_recall_at_3_diff1
      value: 42.9204
    - type: nauc_recall_at_5_max
      value: 17.522299999999998
    - type: nauc_recall_at_5_std
      value: -17.349899999999998
    - type: nauc_recall_at_5_diff1
      value: 40.5682
    - type: nauc_recall_at_10_max
      value: 18.6573
    - type: nauc_recall_at_10_std
      value: -14.9976
    - type: nauc_recall_at_10_diff1
      value: 37.7799
    - type: nauc_recall_at_20_max
      value: 21.0226
    - type: nauc_recall_at_20_std
      value: -11.8854
    - type: nauc_recall_at_20_diff1
      value: 35.3475
    - type: nauc_recall_at_100_max
      value: 26.442300000000003
    - type: nauc_recall_at_100_std
      value: 2.9998
    - type: nauc_recall_at_100_diff1
      value: 29.618699999999997
    - type: nauc_recall_at_1000_max
      value: 36.3607
    - type: nauc_recall_at_1000_std
      value: 24.0336
    - type: nauc_recall_at_1000_diff1
      value: 25.6114
    - type: nauc_precision_at_1_max
      value: 14.691199999999998
    - type: nauc_precision_at_1_std
      value: -18.2481
    - type: nauc_precision_at_1_diff1
      value: 51.82940000000001
    - type: nauc_precision_at_3_max
      value: 16.6167
    - type: nauc_precision_at_3_std
      value: -18.0762
    - type: nauc_precision_at_3_diff1
      value: 42.9204
    - type: nauc_precision_at_5_max
      value: 17.522299999999998
    - type: nauc_precision_at_5_std
      value: -17.349899999999998
    - type: nauc_precision_at_5_diff1
      value: 40.5682
    - type: nauc_precision_at_10_max
      value: 18.6573
    - type: nauc_precision_at_10_std
      value: -14.9976
    - type: nauc_precision_at_10_diff1
      value: 37.7799
    - type: nauc_precision_at_20_max
      value: 21.0226
    - type: nauc_precision_at_20_std
      value: -11.8854
    - type: nauc_precision_at_20_diff1
      value: 35.3475
    - type: nauc_precision_at_100_max
      value: 26.442300000000003
    - type: nauc_precision_at_100_std
      value: 2.9998
    - type: nauc_precision_at_100_diff1
      value: 29.618699999999997
    - type: nauc_precision_at_1000_max
      value: 36.3607
    - type: nauc_precision_at_1000_std
      value: 24.0336
    - type: nauc_precision_at_1000_diff1
      value: 25.6114
    - type: nauc_mrr_at_1_max
      value: 14.691199999999998
    - type: nauc_mrr_at_1_std
      value: -18.2481
    - type: nauc_mrr_at_1_diff1
      value: 51.82940000000001
    - type: nauc_mrr_at_3_max
      value: 15.657099999999998
    - type: nauc_mrr_at_3_std
      value: -18.253700000000002
    - type: nauc_mrr_at_3_diff1
      value: 47.749399999999994
    - type: nauc_mrr_at_5_max
      value: 15.8683
    - type: nauc_mrr_at_5_std
      value: -18.0718
    - type: nauc_mrr_at_5_diff1
      value: 47.176899999999996
    - type: nauc_mrr_at_10_max
      value: 16.0118
    - type: nauc_mrr_at_10_std
      value: -17.7494
    - type: nauc_mrr_at_10_diff1
      value: 46.818799999999996
    - type: nauc_mrr_at_20_max
      value: 16.1658
    - type: nauc_mrr_at_20_std
      value: -17.552400000000002
    - type: nauc_mrr_at_20_diff1
      value: 46.694
    - type: nauc_mrr_at_100_max
      value: 16.2407
    - type: nauc_mrr_at_100_std
      value: -17.289099999999998
    - type: nauc_mrr_at_100_diff1
      value: 46.6325
    - type: nauc_mrr_at_1000_max
      value: 16.2491
    - type: nauc_mrr_at_1000_std
      value: -17.2655
    - type: nauc_mrr_at_1000_diff1
      value: 46.646300000000004
    - type: main_score
      value: 37.757000000000005
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CodeFeedbackST (default)
      revision: d213819e87aab9010628da8b73ab4eb337c89340
      split: test
      type: CoIR-Retrieval/codefeedback-st
    metrics:
    - type: ndcg_at_1
      value: 53.335
    - type: ndcg_at_3
      value: 64.78399999999999
    - type: ndcg_at_5
      value: 67.418
    - type: ndcg_at_10
      value: 69.425
    - type: ndcg_at_20
      value: 70.513
    - type: ndcg_at_100
      value: 71.709
    - type: ndcg_at_1000
      value: 72.139
    - type: map_at_1
      value: 53.335
    - type: map_at_3
      value: 62.0
    - type: map_at_5
      value: 63.467
    - type: map_at_10
      value: 64.306
    - type: map_at_20
      value: 64.608
    - type: map_at_100
      value: 64.776
    - type: map_at_1000
      value: 64.793
    - type: recall_at_1
      value: 53.335
    - type: recall_at_3
      value: 72.82600000000001
    - type: recall_at_5
      value: 79.199
    - type: recall_at_10
      value: 85.354
    - type: recall_at_20
      value: 89.628
    - type: recall_at_100
      value: 96.039
    - type: recall_at_1000
      value: 99.368
    - type: precision_at_1
      value: 53.335
    - type: precision_at_3
      value: 24.275
    - type: precision_at_5
      value: 15.840000000000002
    - type: precision_at_10
      value: 8.535
    - type: precision_at_20
      value: 4.481
    - type: precision_at_100
      value: 0.96
    - type: precision_at_1000
      value: 0.099
    - type: mrr_at_1
      value: 53.31249999999999
    - type: mrr_at_3
      value: 62.0217
    - type: mrr_at_5
      value: 63.489700000000006
    - type: mrr_at_10
      value: 64.3214
    - type: mrr_at_20
      value: 64.6232
    - type: mrr_at_100
      value: 64.7915
    - type: mrr_at_1000
      value: 64.8086
    - type: nauc_ndcg_at_1_max
      value: 4.5411
    - type: nauc_ndcg_at_1_std
      value: -27.4357
    - type: nauc_ndcg_at_1_diff1
      value: 70.331
    - type: nauc_ndcg_at_3_max
      value: 9.293899999999999
    - type: nauc_ndcg_at_3_std
      value: -30.4201
    - type: nauc_ndcg_at_3_diff1
      value: 64.90599999999999
    - type: nauc_ndcg_at_5_max
      value: 9.725
    - type: nauc_ndcg_at_5_std
      value: -30.8448
    - type: nauc_ndcg_at_5_diff1
      value: 64.2796
    - type: nauc_ndcg_at_10_max
      value: 9.4302
    - type: nauc_ndcg_at_10_std
      value: -30.5425
    - type: nauc_ndcg_at_10_diff1
      value: 64.5211
    - type: nauc_ndcg_at_20_max
      value: 9.019
    - type: nauc_ndcg_at_20_std
      value: -29.986800000000002
    - type: nauc_ndcg_at_20_diff1
      value: 64.7995
    - type: nauc_ndcg_at_100_max
      value: 8.780100000000001
    - type: nauc_ndcg_at_100_std
      value: -29.4587
    - type: nauc_ndcg_at_100_diff1
      value: 65.3485
    - type: nauc_ndcg_at_1000_max
      value: 8.5933
    - type: nauc_ndcg_at_1000_std
      value: -29.462300000000003
    - type: nauc_ndcg_at_1000_diff1
      value: 65.5513
    - type: nauc_map_at_1_max
      value: 4.5411
    - type: nauc_map_at_1_std
      value: -27.4357
    - type: nauc_map_at_1_diff1
      value: 70.331
    - type: nauc_map_at_3_max
      value: 7.9982
    - type: nauc_map_at_3_std
      value: -29.5826
    - type: nauc_map_at_3_diff1
      value: 66.2961
    - type: nauc_map_at_5_max
      value: 8.1756
    - type: nauc_map_at_5_std
      value: -29.765900000000002
    - type: nauc_map_at_5_diff1
      value: 66.0248
    - type: nauc_map_at_10_max
      value: 8.0296
    - type: nauc_map_at_10_std
      value: -29.6458
    - type: nauc_map_at_10_diff1
      value: 66.158
    - type: nauc_map_at_20_max
      value: 7.919099999999999
    - type: nauc_map_at_20_std
      value: -29.505799999999997
    - type: nauc_map_at_20_diff1
      value: 66.24029999999999
    - type: nauc_map_at_100_max
      value: 7.8803
    - type: nauc_map_at_100_std
      value: -29.442600000000002
    - type: nauc_map_at_100_diff1
      value: 66.3125
    - type: nauc_map_at_1000_max
      value: 7.8752
    - type: nauc_map_at_1000_std
      value: -29.438399999999998
    - type: nauc_map_at_1000_diff1
      value: 66.3195
    - type: nauc_recall_at_1_max
      value: 4.5411
    - type: nauc_recall_at_1_std
      value: -27.4357
    - type: nauc_recall_at_1_diff1
      value: 70.331
    - type: nauc_recall_at_3_max
      value: 13.911000000000001
    - type: nauc_recall_at_3_std
      value: -33.4167
    - type: nauc_recall_at_3_diff1
      value: 59.9986
    - type: nauc_recall_at_5_max
      value: 16.401
    - type: nauc_recall_at_5_std
      value: -35.5473
    - type: nauc_recall_at_5_diff1
      value: 56.781000000000006
    - type: nauc_recall_at_10_max
      value: 17.2917
    - type: nauc_recall_at_10_std
      value: -35.4908
    - type: nauc_recall_at_10_diff1
      value: 55.279199999999996
    - type: nauc_recall_at_20_max
      value: 16.4243
    - type: nauc_recall_at_20_std
      value: -32.2776
    - type: nauc_recall_at_20_diff1
      value: 54.4386
    - type: nauc_recall_at_100_max
      value: 21.5949
    - type: nauc_recall_at_100_std
      value: -19.9444
    - type: nauc_recall_at_100_diff1
      value: 54.3502
    - type: nauc_recall_at_1000_max
      value: 35.8557
    - type: nauc_recall_at_1000_std
      value: 18.242
    - type: nauc_recall_at_1000_diff1
      value: 50.969699999999996
    - type: nauc_precision_at_1_max
      value: 4.5411
    - type: nauc_precision_at_1_std
      value: -27.4357
    - type: nauc_precision_at_1_diff1
      value: 70.331
    - type: nauc_precision_at_3_max
      value: 13.911000000000001
    - type: nauc_precision_at_3_std
      value: -33.4167
    - type: nauc_precision_at_3_diff1
      value: 59.9986
    - type: nauc_precision_at_5_max
      value: 16.401
    - type: nauc_precision_at_5_std
      value: -35.5473
    - type: nauc_precision_at_5_diff1
      value: 56.781000000000006
    - type: nauc_precision_at_10_max
      value: 17.2917
    - type: nauc_precision_at_10_std
      value: -35.4908
    - type: nauc_precision_at_10_diff1
      value: 55.279199999999996
    - type: nauc_precision_at_20_max
      value: 16.4243
    - type: nauc_precision_at_20_std
      value: -32.2776
    - type: nauc_precision_at_20_diff1
      value: 54.4386
    - type: nauc_precision_at_100_max
      value: 21.5949
    - type: nauc_precision_at_100_std
      value: -19.9444
    - type: nauc_precision_at_100_diff1
      value: 54.3502
    - type: nauc_precision_at_1000_max
      value: 35.8557
    - type: nauc_precision_at_1000_std
      value: 18.242
    - type: nauc_precision_at_1000_diff1
      value: 50.969699999999996
    - type: nauc_mrr_at_1_max
      value: 4.045
    - type: nauc_mrr_at_1_std
      value: -27.371299999999998
    - type: nauc_mrr_at_1_diff1
      value: 70.3681
    - type: nauc_mrr_at_3_max
      value: 7.7906
    - type: nauc_mrr_at_3_std
      value: -29.488999999999997
    - type: nauc_mrr_at_3_diff1
      value: 66.2574
    - type: nauc_mrr_at_5_max
      value: 7.8858999999999995
    - type: nauc_mrr_at_5_std
      value: -29.7336
    - type: nauc_mrr_at_5_diff1
      value: 66.0274
    - type: nauc_mrr_at_10_max
      value: 7.7456
    - type: nauc_mrr_at_10_std
      value: -29.5912
    - type: nauc_mrr_at_10_diff1
      value: 66.1546
    - type: nauc_mrr_at_20_max
      value: 7.6305
    - type: nauc_mrr_at_20_std
      value: -29.4551
    - type: nauc_mrr_at_20_diff1
      value: 66.2342
    - type: nauc_mrr_at_100_max
      value: 7.589799999999999
    - type: nauc_mrr_at_100_std
      value: -29.392400000000002
    - type: nauc_mrr_at_100_diff1
      value: 66.3072
    - type: nauc_mrr_at_1000_max
      value: 7.584499999999999
    - type: nauc_mrr_at_1000_std
      value: -29.3881
    - type: nauc_mrr_at_1000_diff1
      value: 66.3142
    - type: main_score
      value: 69.425
    task:
      type: Retrieval
  - dataset:
      config: python
      name: MTEB CodeSearchNetCCRetrieval (python)
      revision: 6e1effa2c03723c5fde48ee912b5ee08d4f211e8
      split: test
      type: CoIR-Retrieval/CodeSearchNet-ccr
    metrics:
    - type: ndcg_at_1
      value: 39.395
    - type: ndcg_at_3
      value: 49.038
    - type: ndcg_at_5
      value: 51.398999999999994
    - type: ndcg_at_10
      value: 53.593999999999994
    - type: ndcg_at_20
      value: 55.013
    - type: ndcg_at_100
      value: 56.940999999999995
    - type: ndcg_at_1000
      value: 58.126999999999995
    - type: map_at_1
      value: 39.395
    - type: map_at_3
      value: 46.687
    - type: map_at_5
      value: 48.003
    - type: map_at_10
      value: 48.911
    - type: map_at_20
      value: 49.305
    - type: map_at_100
      value: 49.571
    - type: map_at_1000
      value: 49.612
    - type: recall_at_1
      value: 39.395
    - type: recall_at_3
      value: 55.832
    - type: recall_at_5
      value: 61.543000000000006
    - type: recall_at_10
      value: 68.313
    - type: recall_at_20
      value: 73.897
    - type: recall_at_100
      value: 84.308
    - type: recall_at_1000
      value: 93.866
    - type: precision_at_1
      value: 39.395
    - type: precision_at_3
      value: 18.611
    - type: precision_at_5
      value: 12.309000000000001
    - type: precision_at_10
      value: 6.8309999999999995
    - type: precision_at_20
      value: 3.695
    - type: precision_at_100
      value: 0.843
    - type: precision_at_1000
      value: 0.094
    - type: mrr_at_1
      value: 39.402100000000004
    - type: mrr_at_3
      value: 46.690799999999996
    - type: mrr_at_5
      value: 48.0073
    - type: mrr_at_10
      value: 48.9156
    - type: mrr_at_20
      value: 49.3097
    - type: mrr_at_100
      value: 49.5752
    - type: mrr_at_1000
      value: 49.6159
    - type: nauc_ndcg_at_1_max
      value: 29.945899999999998
    - type: nauc_ndcg_at_1_std
      value: -7.957
    - type: nauc_ndcg_at_1_diff1
      value: 55.8451
    - type: nauc_ndcg_at_3_max
      value: 31.5415
    - type: nauc_ndcg_at_3_std
      value: -8.2198
    - type: nauc_ndcg_at_3_diff1
      value: 51.75959999999999
    - type: nauc_ndcg_at_5_max
      value: 31.6664
    - type: nauc_ndcg_at_5_std
      value: -7.1463
    - type: nauc_ndcg_at_5_diff1
      value: 51.0188
    - type: nauc_ndcg_at_10_max
      value: 31.616
    - type: nauc_ndcg_at_10_std
      value: -6.575699999999999
    - type: nauc_ndcg_at_10_diff1
      value: 50.7344
    - type: nauc_ndcg_at_20_max
      value: 31.626199999999997
    - type: nauc_ndcg_at_20_std
      value: -6.0725
    - type: nauc_ndcg_at_20_diff1
      value: 50.77159999999999
    - type: nauc_ndcg_at_100_max
      value: 31.6639
    - type: nauc_ndcg_at_100_std
      value: -5.4948999999999995
    - type: nauc_ndcg_at_100_diff1
      value: 50.790800000000004
    - type: nauc_ndcg_at_1000_max
      value: 31.5161
    - type: nauc_ndcg_at_1000_std
      value: -5.748600000000001
    - type: nauc_ndcg_at_1000_diff1
      value: 51.062799999999996
    - type: nauc_map_at_1_max
      value: 29.945899999999998
    - type: nauc_map_at_1_std
      value: -7.957
    - type: nauc_map_at_1_diff1
      value: 55.8451
    - type: nauc_map_at_3_max
      value: 31.1851
    - type: nauc_map_at_3_std
      value: -8.1706
    - type: nauc_map_at_3_diff1
      value: 52.7057
    - type: nauc_map_at_5_max
      value: 31.2519
    - type: nauc_map_at_5_std
      value: -7.580299999999999
    - type: nauc_map_at_5_diff1
      value: 52.3165
    - type: nauc_map_at_10_max
      value: 31.231399999999997
    - type: nauc_map_at_10_std
      value: -7.360800000000001
    - type: nauc_map_at_10_diff1
      value: 52.23
    - type: nauc_map_at_20_max
      value: 31.2307
    - type: nauc_map_at_20_std
      value: -7.2384
    - type: nauc_map_at_20_diff1
      value: 52.2532
    - type: nauc_map_at_100_max
      value: 31.2368
    - type: nauc_map_at_100_std
      value: -7.1598
    - type: nauc_map_at_100_diff1
      value: 52.260600000000004
    - type: nauc_map_at_1000_max
      value: 31.230900000000002
    - type: nauc_map_at_1000_std
      value: -7.1662
    - type: nauc_map_at_1000_diff1
      value: 52.267300000000006
    - type: nauc_recall_at_1_max
      value: 29.945899999999998
    - type: nauc_recall_at_1_std
      value: -7.957
    - type: nauc_recall_at_1_diff1
      value: 55.8451
    - type: nauc_recall_at_3_max
      value: 32.6121
    - type: nauc_recall_at_3_std
      value: -8.363
    - type: nauc_recall_at_3_diff1
      value: 48.9016
    - type: nauc_recall_at_5_max
      value: 33.0025
    - type: nauc_recall_at_5_std
      value: -5.5725
    - type: nauc_recall_at_5_diff1
      value: 46.7352
    - type: nauc_recall_at_10_max
      value: 32.9683
    - type: nauc_recall_at_10_std
      value: -3.2460999999999998
    - type: nauc_recall_at_10_diff1
      value: 45.0443
    - type: nauc_recall_at_20_max
      value: 33.2455
    - type: nauc_recall_at_20_std
      value: -0.0093
    - type: nauc_recall_at_20_diff1
      value: 44.294200000000004
    - type: nauc_recall_at_100_max
      value: 34.4004
    - type: nauc_recall_at_100_std
      value: 8.996500000000001
    - type: nauc_recall_at_100_diff1
      value: 41.0779
    - type: nauc_recall_at_1000_max
      value: 33.096399999999996
    - type: nauc_recall_at_1000_std
      value: 19.266
    - type: nauc_recall_at_1000_diff1
      value: 38.2966
    - type: nauc_precision_at_1_max
      value: 29.945899999999998
    - type: nauc_precision_at_1_std
      value: -7.957
    - type: nauc_precision_at_1_diff1
      value: 55.8451
    - type: nauc_precision_at_3_max
      value: 32.6121
    - type: nauc_precision_at_3_std
      value: -8.363
    - type: nauc_precision_at_3_diff1
      value: 48.9016
    - type: nauc_precision_at_5_max
      value: 33.0025
    - type: nauc_precision_at_5_std
      value: -5.5725
    - type: nauc_precision_at_5_diff1
      value: 46.7352
    - type: nauc_precision_at_10_max
      value: 32.9683
    - type: nauc_precision_at_10_std
      value: -3.2460999999999998
    - type: nauc_precision_at_10_diff1
      value: 45.0443
    - type: nauc_precision_at_20_max
      value: 33.2455
    - type: nauc_precision_at_20_std
      value: -0.0093
    - type: nauc_precision_at_20_diff1
      value: 44.294200000000004
    - type: nauc_precision_at_100_max
      value: 34.4004
    - type: nauc_precision_at_100_std
      value: 8.996500000000001
    - type: nauc_precision_at_100_diff1
      value: 41.0779
    - type: nauc_precision_at_1000_max
      value: 33.096399999999996
    - type: nauc_precision_at_1000_std
      value: 19.266
    - type: nauc_precision_at_1000_diff1
      value: 38.2966
    - type: nauc_mrr_at_1_max
      value: 29.9427
    - type: nauc_mrr_at_1_std
      value: -7.9670000000000005
    - type: nauc_mrr_at_1_diff1
      value: 55.824799999999996
    - type: nauc_mrr_at_3_max
      value: 31.1834
    - type: nauc_mrr_at_3_std
      value: -8.175799999999999
    - type: nauc_mrr_at_3_diff1
      value: 52.6952
    - type: nauc_mrr_at_5_max
      value: 31.2515
    - type: nauc_mrr_at_5_std
      value: -7.5835
    - type: nauc_mrr_at_5_diff1
      value: 52.303599999999996
    - type: nauc_mrr_at_10_max
      value: 31.2284
    - type: nauc_mrr_at_10_std
      value: -7.3647
    - type: nauc_mrr_at_10_diff1
      value: 52.2177
    - type: nauc_mrr_at_20_max
      value: 31.2274
    - type: nauc_mrr_at_20_std
      value: -7.243399999999999
    - type: nauc_mrr_at_20_diff1
      value: 52.2417
    - type: nauc_mrr_at_100_max
      value: 31.2336
    - type: nauc_mrr_at_100_std
      value: -7.1640999999999995
    - type: nauc_mrr_at_100_diff1
      value: 52.2482
    - type: nauc_mrr_at_1000_max
      value: 31.227700000000002
    - type: nauc_mrr_at_1000_std
      value: -7.1705000000000005
    - type: nauc_mrr_at_1000_diff1
      value: 52.254900000000006
    - type: main_score
      value: 53.593999999999994
    task:
      type: Retrieval
  - dataset:
      config: javascript
      name: MTEB CodeSearchNetCCRetrieval (javascript)
      revision: 6e1effa2c03723c5fde48ee912b5ee08d4f211e8
      split: test
      type: CoIR-Retrieval/CodeSearchNet-ccr
    metrics:
    - type: ndcg_at_1
      value: 39.593
    - type: ndcg_at_3
      value: 48.759
    - type: ndcg_at_5
      value: 51.073
    - type: ndcg_at_10
      value: 53.1
    - type: ndcg_at_20
      value: 54.230999999999995
    - type: ndcg_at_100
      value: 56.289
    - type: ndcg_at_1000
      value: 57.67400000000001
    - type: map_at_1
      value: 39.593
    - type: map_at_3
      value: 46.536
    - type: map_at_5
      value: 47.826
    - type: map_at_10
      value: 48.676
    - type: map_at_20
      value: 48.983
    - type: map_at_100
      value: 49.268
    - type: map_at_1000
      value: 49.313
    - type: recall_at_1
      value: 39.593
    - type: recall_at_3
      value: 55.181000000000004
    - type: recall_at_5
      value: 60.772000000000006
    - type: recall_at_10
      value: 66.971
    - type: recall_at_20
      value: 71.468
    - type: recall_at_100
      value: 82.55799999999999
    - type: recall_at_1000
      value: 93.83200000000001
    - type: precision_at_1
      value: 39.593
    - type: precision_at_3
      value: 18.394
    - type: precision_at_5
      value: 12.154
    - type: precision_at_10
      value: 6.697
    - type: precision_at_20
      value: 3.573
    - type: precision_at_100
      value: 0.826
    - type: precision_at_1000
      value: 0.094
    - type: mrr_at_1
      value: 39.5624
    - type: mrr_at_3
      value: 46.5158
    - type: mrr_at_5
      value: 47.8056
    - type: mrr_at_10
      value: 48.654799999999994
    - type: mrr_at_20
      value: 48.9616
    - type: mrr_at_100
      value: 49.2469
    - type: mrr_at_1000
      value: 49.2923
    - type: nauc_ndcg_at_1_max
      value: 26.582099999999997
    - type: nauc_ndcg_at_1_std
      value: -14.751900000000001
    - type: nauc_ndcg_at_1_diff1
      value: 54.9795
    - type: nauc_ndcg_at_3_max
      value: 30.000700000000002
    - type: nauc_ndcg_at_3_std
      value: -13.107299999999999
    - type: nauc_ndcg_at_3_diff1
      value: 51.7972
    - type: nauc_ndcg_at_5_max
      value: 29.4468
    - type: nauc_ndcg_at_5_std
      value: -13.3189
    - type: nauc_ndcg_at_5_diff1
      value: 51.0062
    - type: nauc_ndcg_at_10_max
      value: 28.6629
    - type: nauc_ndcg_at_10_std
      value: -13.900000000000002
    - type: nauc_ndcg_at_10_diff1
      value: 50.4771
    - type: nauc_ndcg_at_20_max
      value: 28.558600000000002
    - type: nauc_ndcg_at_20_std
      value: -13.793
    - type: nauc_ndcg_at_20_diff1
      value: 50.720299999999995
    - type: nauc_ndcg_at_100_max
      value: 28.7124
    - type: nauc_ndcg_at_100_std
      value: -13.133000000000001
    - type: nauc_ndcg_at_100_diff1
      value: 50.7983
    - type: nauc_ndcg_at_1000_max
      value: 28.4906
    - type: nauc_ndcg_at_1000_std
      value: -13.5678
    - type: nauc_ndcg_at_1000_diff1
      value: 51.1172
    - type: nauc_map_at_1_max
      value: 26.582099999999997
    - type: nauc_map_at_1_std
      value: -14.751900000000001
    - type: nauc_map_at_1_diff1
      value: 54.9795
    - type: nauc_map_at_3_max
      value: 29.191899999999997
    - type: nauc_map_at_3_std
      value: -13.565299999999999
    - type: nauc_map_at_3_diff1
      value: 52.5372
    - type: nauc_map_at_5_max
      value: 28.865099999999998
    - type: nauc_map_at_5_std
      value: -13.6911
    - type: nauc_map_at_5_diff1
      value: 52.12520000000001
    - type: nauc_map_at_10_max
      value: 28.5526
    - type: nauc_map_at_10_std
      value: -13.9255
    - type: nauc_map_at_10_diff1
      value: 51.931400000000004
    - type: nauc_map_at_20_max
      value: 28.520200000000003
    - type: nauc_map_at_20_std
      value: -13.8934
    - type: nauc_map_at_20_diff1
      value: 51.991299999999995
    - type: nauc_map_at_100_max
      value: 28.5184
    - type: nauc_map_at_100_std
      value: -13.8399
    - type: nauc_map_at_100_diff1
      value: 52.0024
    - type: nauc_map_at_1000_max
      value: 28.512500000000003
    - type: nauc_map_at_1000_std
      value: -13.851700000000001
    - type: nauc_map_at_1000_diff1
      value: 52.0139
    - type: nauc_recall_at_1_max
      value: 26.582099999999997
    - type: nauc_recall_at_1_std
      value: -14.751900000000001
    - type: nauc_recall_at_1_diff1
      value: 54.9795
    - type: nauc_recall_at_3_max
      value: 32.443
    - type: nauc_recall_at_3_std
      value: -11.6927
    - type: nauc_recall_at_3_diff1
      value: 49.568400000000004
    - type: nauc_recall_at_5_max
      value: 31.2258
    - type: nauc_recall_at_5_std
      value: -12.1296
    - type: nauc_recall_at_5_diff1
      value: 47.3057
    - type: nauc_recall_at_10_max
      value: 28.561999999999998
    - type: nauc_recall_at_10_std
      value: -14.103499999999999
    - type: nauc_recall_at_10_diff1
      value: 44.9228
    - type: nauc_recall_at_20_max
      value: 28.0738
    - type: nauc_recall_at_20_std
      value: -13.632
    - type: nauc_recall_at_20_diff1
      value: 45.6569
    - type: nauc_recall_at_100_max
      value: 29.9618
    - type: nauc_recall_at_100_std
      value: -6.2382
    - type: nauc_recall_at_100_diff1
      value: 44.1378
    - type: nauc_recall_at_1000_max
      value: 23.4062
    - type: nauc_recall_at_1000_std
      value: -11.6326
    - type: nauc_recall_at_1000_diff1
      value: 45.130199999999995
    - type: nauc_precision_at_1_max
      value: 26.582099999999997
    - type: nauc_precision_at_1_std
      value: -14.751900000000001
    - type: nauc_precision_at_1_diff1
      value: 54.9795
    - type: nauc_precision_at_3_max
      value: 32.443
    - type: nauc_precision_at_3_std
      value: -11.6927
    - type: nauc_precision_at_3_diff1
      value: 49.568400000000004
    - type: nauc_precision_at_5_max
      value: 31.2258
    - type: nauc_precision_at_5_std
      value: -12.1296
    - type: nauc_precision_at_5_diff1
      value: 47.3057
    - type: nauc_precision_at_10_max
      value: 28.561999999999998
    - type: nauc_precision_at_10_std
      value: -14.103499999999999
    - type: nauc_precision_at_10_diff1
      value: 44.9228
    - type: nauc_precision_at_20_max
      value: 28.0738
    - type: nauc_precision_at_20_std
      value: -13.632
    - type: nauc_precision_at_20_diff1
      value: 45.6569
    - type: nauc_precision_at_100_max
      value: 29.9618
    - type: nauc_precision_at_100_std
      value: -6.2382
    - type: nauc_precision_at_100_diff1
      value: 44.1378
    - type: nauc_precision_at_1000_max
      value: 23.4062
    - type: nauc_precision_at_1000_std
      value: -11.6326
    - type: nauc_precision_at_1000_diff1
      value: 45.130199999999995
    - type: nauc_mrr_at_1_max
      value: 26.571499999999997
    - type: nauc_mrr_at_1_std
      value: -14.9002
    - type: nauc_mrr_at_1_diff1
      value: 55.071400000000004
    - type: nauc_mrr_at_3_max
      value: 29.1956
    - type: nauc_mrr_at_3_std
      value: -13.6331
    - type: nauc_mrr_at_3_diff1
      value: 52.59439999999999
    - type: nauc_mrr_at_5_max
      value: 28.8688
    - type: nauc_mrr_at_5_std
      value: -13.7599
    - type: nauc_mrr_at_5_diff1
      value: 52.1832
    - type: nauc_mrr_at_10_max
      value: 28.556199999999997
    - type: nauc_mrr_at_10_std
      value: -13.9924
    - type: nauc_mrr_at_10_diff1
      value: 51.9865
    - type: nauc_mrr_at_20_max
      value: 28.523799999999998
    - type: nauc_mrr_at_20_std
      value: -13.960700000000001
    - type: nauc_mrr_at_20_diff1
      value: 52.0466
    - type: nauc_mrr_at_100_max
      value: 28.522
    - type: nauc_mrr_at_100_std
      value: -13.9076
    - type: nauc_mrr_at_100_diff1
      value: 52.058099999999996
    - type: nauc_mrr_at_1000_max
      value: 28.5161
    - type: nauc_mrr_at_1000_std
      value: -13.919500000000001
    - type: nauc_mrr_at_1000_diff1
      value: 52.0697
    - type: main_score
      value: 53.1
    task:
      type: Retrieval
  - dataset:
      config: go
      name: MTEB CodeSearchNetCCRetrieval (go)
      revision: 6e1effa2c03723c5fde48ee912b5ee08d4f211e8
      split: test
      type: CoIR-Retrieval/CodeSearchNet-ccr
    metrics:
    - type: ndcg_at_1
      value: 30.459999999999997
    - type: ndcg_at_3
      value: 37.88
    - type: ndcg_at_5
      value: 40.11
    - type: ndcg_at_10
      value: 42.094
    - type: ndcg_at_20
      value: 43.683
    - type: ndcg_at_100
      value: 45.998
    - type: ndcg_at_1000
      value: 47.723
    - type: map_at_1
      value: 30.459999999999997
    - type: map_at_3
      value: 36.046
    - type: map_at_5
      value: 37.285000000000004
    - type: map_at_10
      value: 38.108
    - type: map_at_20
      value: 38.546
    - type: map_at_100
      value: 38.859
    - type: map_at_1000
      value: 38.917
    - type: recall_at_1
      value: 30.459999999999997
    - type: recall_at_3
      value: 43.191
    - type: recall_at_5
      value: 48.596000000000004
    - type: recall_at_10
      value: 54.716
    - type: recall_at_20
      value: 60.983
    - type: recall_at_100
      value: 73.566
    - type: recall_at_1000
      value: 87.515
    - type: precision_at_1
      value: 30.459999999999997
    - type: precision_at_3
      value: 14.396999999999998
    - type: precision_at_5
      value: 9.719
    - type: precision_at_10
      value: 5.4719999999999995
    - type: precision_at_20
      value: 3.049
    - type: precision_at_100
      value: 0.736
    - type: precision_at_1000
      value: 0.08800000000000001
    - type: mrr_at_1
      value: 30.448199999999996
    - type: mrr_at_3
      value: 36.042
    - type: mrr_at_5
      value: 37.2763
    - type: mrr_at_10
      value: 38.1013
    - type: mrr_at_20
      value: 38.5373
    - type: mrr_at_100
      value: 38.8506
    - type: mrr_at_1000
      value: 38.9093
    - type: nauc_ndcg_at_1_max
      value: 27.284999999999997
    - type: nauc_ndcg_at_1_std
      value: -6.6476999999999995
    - type: nauc_ndcg_at_1_diff1
      value: 50.871500000000005
    - type: nauc_ndcg_at_3_max
      value: 26.6017
    - type: nauc_ndcg_at_3_std
      value: -7.6026
    - type: nauc_ndcg_at_3_diff1
      value: 46.768
    - type: nauc_ndcg_at_5_max
      value: 26.2865
    - type: nauc_ndcg_at_5_std
      value: -7.3601
    - type: nauc_ndcg_at_5_diff1
      value: 45.7969
    - type: nauc_ndcg_at_10_max
      value: 25.746599999999997
    - type: nauc_ndcg_at_10_std
      value: -7.4333
    - type: nauc_ndcg_at_10_diff1
      value: 45.4115
    - type: nauc_ndcg_at_20_max
      value: 25.5118
    - type: nauc_ndcg_at_20_std
      value: -6.9322
    - type: nauc_ndcg_at_20_diff1
      value: 45.0598
    - type: nauc_ndcg_at_100_max
      value: 25.309900000000003
    - type: nauc_ndcg_at_100_std
      value: -6.0600000000000005
    - type: nauc_ndcg_at_100_diff1
      value: 44.8825
    - type: nauc_ndcg_at_1000_max
      value: 25.521700000000003
    - type: nauc_ndcg_at_1000_std
      value: -5.9789
    - type: nauc_ndcg_at_1000_diff1
      value: 45.2513
    - type: nauc_map_at_1_max
      value: 27.284999999999997
    - type: nauc_map_at_1_std
      value: -6.6476999999999995
    - type: nauc_map_at_1_diff1
      value: 50.871500000000005
    - type: nauc_map_at_3_max
      value: 26.7721
    - type: nauc_map_at_3_std
      value: -7.452300000000001
    - type: nauc_map_at_3_diff1
      value: 47.7211
    - type: nauc_map_at_5_max
      value: 26.600600000000004
    - type: nauc_map_at_5_std
      value: -7.3378
    - type: nauc_map_at_5_diff1
      value: 47.1879
    - type: nauc_map_at_10_max
      value: 26.372
    - type: nauc_map_at_10_std
      value: -7.3735
    - type: nauc_map_at_10_diff1
      value: 47.0298
    - type: nauc_map_at_20_max
      value: 26.3071
    - type: nauc_map_at_20_std
      value: -7.2452000000000005
    - type: nauc_map_at_20_diff1
      value: 46.9294
    - type: nauc_map_at_100_max
      value: 26.281100000000002
    - type: nauc_map_at_100_std
      value: -7.1155
    - type: nauc_map_at_100_diff1
      value: 46.9054
    - type: nauc_map_at_1000_max
      value: 26.2903
    - type: nauc_map_at_1000_std
      value: -7.1089
    - type: nauc_map_at_1000_diff1
      value: 46.9182
    - type: nauc_recall_at_1_max
      value: 27.284999999999997
    - type: nauc_recall_at_1_std
      value: -6.6476999999999995
    - type: nauc_recall_at_1_diff1
      value: 50.871500000000005
    - type: nauc_recall_at_3_max
      value: 26.1146
    - type: nauc_recall_at_3_std
      value: -7.9985
    - type: nauc_recall_at_3_diff1
      value: 44.0707
    - type: nauc_recall_at_5_max
      value: 25.3292
    - type: nauc_recall_at_5_std
      value: -7.331799999999999
    - type: nauc_recall_at_5_diff1
      value: 41.6571
    - type: nauc_recall_at_10_max
      value: 23.6012
    - type: nauc_recall_at_10_std
      value: -7.5294
    - type: nauc_recall_at_10_diff1
      value: 40.244099999999996
    - type: nauc_recall_at_20_max
      value: 22.453300000000002
    - type: nauc_recall_at_20_std
      value: -5.3024000000000004
    - type: nauc_recall_at_20_diff1
      value: 38.4242
    - type: nauc_recall_at_100_max
      value: 20.069100000000002
    - type: nauc_recall_at_100_std
      value: 1.4581
    - type: nauc_recall_at_100_diff1
      value: 35.1775
    - type: nauc_recall_at_1000_max
      value: 19.4385
    - type: nauc_recall_at_1000_std
      value: 9.0112
    - type: nauc_recall_at_1000_diff1
      value: 34.138000000000005
    - type: nauc_precision_at_1_max
      value: 27.284999999999997
    - type: nauc_precision_at_1_std
      value: -6.6476999999999995
    - type: nauc_precision_at_1_diff1
      value: 50.871500000000005
    - type: nauc_precision_at_3_max
      value: 26.1146
    - type: nauc_precision_at_3_std
      value: -7.9985
    - type: nauc_precision_at_3_diff1
      value: 44.0707
    - type: nauc_precision_at_5_max
      value: 25.3292
    - type: nauc_precision_at_5_std
      value: -7.331799999999999
    - type: nauc_precision_at_5_diff1
      value: 41.6571
    - type: nauc_precision_at_10_max
      value: 23.6012
    - type: nauc_precision_at_10_std
      value: -7.5294
    - type: nauc_precision_at_10_diff1
      value: 40.244099999999996
    - type: nauc_precision_at_20_max
      value: 22.453300000000002
    - type: nauc_precision_at_20_std
      value: -5.3024000000000004
    - type: nauc_precision_at_20_diff1
      value: 38.4242
    - type: nauc_precision_at_100_max
      value: 20.069100000000002
    - type: nauc_precision_at_100_std
      value: 1.4581
    - type: nauc_precision_at_100_diff1
      value: 35.1775
    - type: nauc_precision_at_1000_max
      value: 19.4385
    - type: nauc_precision_at_1000_std
      value: 9.0112
    - type: nauc_precision_at_1000_diff1
      value: 34.138000000000005
    - type: nauc_mrr_at_1_max
      value: 27.334000000000003
    - type: nauc_mrr_at_1_std
      value: -6.5517
    - type: nauc_mrr_at_1_diff1
      value: 50.9102
    - type: nauc_mrr_at_3_max
      value: 26.807199999999998
    - type: nauc_mrr_at_3_std
      value: -7.436800000000001
    - type: nauc_mrr_at_3_diff1
      value: 47.7425
    - type: nauc_mrr_at_5_max
      value: 26.6194
    - type: nauc_mrr_at_5_std
      value: -7.3031
    - type: nauc_mrr_at_5_diff1
      value: 47.2053
    - type: nauc_mrr_at_10_max
      value: 26.3924
    - type: nauc_mrr_at_10_std
      value: -7.324700000000001
    - type: nauc_mrr_at_10_diff1
      value: 47.051500000000004
    - type: nauc_mrr_at_20_max
      value: 26.3274
    - type: nauc_mrr_at_20_std
      value: -7.209899999999999
    - type: nauc_mrr_at_20_diff1
      value: 46.953
    - type: nauc_mrr_at_100_max
      value: 26.3019
    - type: nauc_mrr_at_100_std
      value: -7.0785
    - type: nauc_mrr_at_100_diff1
      value: 46.9298
    - type: nauc_mrr_at_1000_max
      value: 26.311
    - type: nauc_mrr_at_1000_std
      value: -7.0719
    - type: nauc_mrr_at_1000_diff1
      value: 46.942499999999995
    - type: main_score
      value: 42.094
    task:
      type: Retrieval
  - dataset:
      config: ruby
      name: MTEB CodeSearchNetCCRetrieval (ruby)
      revision: 6e1effa2c03723c5fde48ee912b5ee08d4f211e8
      split: test
      type: CoIR-Retrieval/CodeSearchNet-ccr
    metrics:
    - type: ndcg_at_1
      value: 37.827
    - type: ndcg_at_3
      value: 47.599000000000004
    - type: ndcg_at_5
      value: 49.687
    - type: ndcg_at_10
      value: 51.686
    - type: ndcg_at_20
      value: 53.018
    - type: ndcg_at_100
      value: 54.75600000000001
    - type: ndcg_at_1000
      value: 56.196
    - type: map_at_1
      value: 37.827
    - type: map_at_3
      value: 45.242
    - type: map_at_5
      value: 46.400000000000006
    - type: map_at_10
      value: 47.223
    - type: map_at_20
      value: 47.593
    - type: map_at_100
      value: 47.824
    - type: map_at_1000
      value: 47.878
    - type: recall_at_1
      value: 37.827
    - type: recall_at_3
      value: 54.400999999999996
    - type: recall_at_5
      value: 59.477000000000004
    - type: recall_at_10
      value: 65.66199999999999
    - type: recall_at_20
      value: 70.896
    - type: recall_at_100
      value: 80.41199999999999
    - type: recall_at_1000
      value: 91.753
    - type: precision_at_1
      value: 37.827
    - type: precision_at_3
      value: 18.134
    - type: precision_at_5
      value: 11.895
    - type: precision_at_10
      value: 6.566
    - type: precision_at_20
      value: 3.5450000000000004
    - type: precision_at_100
      value: 0.804
    - type: precision_at_1000
      value: 0.092
    - type: mrr_at_1
      value: 37.8271
    - type: mrr_at_3
      value: 45.2154
    - type: mrr_at_5
      value: 46.3931
    - type: mrr_at_10
      value: 47.2166
    - type: mrr_at_20
      value: 47.5869
    - type: mrr_at_100
      value: 47.8167
    - type: mrr_at_1000
      value: 47.8715
    - type: nauc_ndcg_at_1_max
      value: 34.1998
    - type: nauc_ndcg_at_1_std
      value: -15.7415
    - type: nauc_ndcg_at_1_diff1
      value: 61.8572
    - type: nauc_ndcg_at_3_max
      value: 33.566
    - type: nauc_ndcg_at_3_std
      value: -18.0058
    - type: nauc_ndcg_at_3_diff1
      value: 54.5929
    - type: nauc_ndcg_at_5_max
      value: 34.0447
    - type: nauc_ndcg_at_5_std
      value: -17.3914
    - type: nauc_ndcg_at_5_diff1
      value: 53.980399999999996
    - type: nauc_ndcg_at_10_max
      value: 34.0521
    - type: nauc_ndcg_at_10_std
      value: -17.298099999999998
    - type: nauc_ndcg_at_10_diff1
      value: 53.63830000000001
    - type: nauc_ndcg_at_20_max
      value: 34.076499999999996
    - type: nauc_ndcg_at_20_std
      value: -17.1978
    - type: nauc_ndcg_at_20_diff1
      value: 53.3739
    - type: nauc_ndcg_at_100_max
      value: 33.9961
    - type: nauc_ndcg_at_100_std
      value: -17.0232
    - type: nauc_ndcg_at_100_diff1
      value: 53.8714
    - type: nauc_ndcg_at_1000_max
      value: 34.0269
    - type: nauc_ndcg_at_1000_std
      value: -16.6124
    - type: nauc_ndcg_at_1000_diff1
      value: 54.286199999999994
    - type: nauc_map_at_1_max
      value: 34.1998
    - type: nauc_map_at_1_std
      value: -15.7415
    - type: nauc_map_at_1_diff1
      value: 61.8572
    - type: nauc_map_at_3_max
      value: 33.8395
    - type: nauc_map_at_3_std
      value: -17.529
    - type: nauc_map_at_3_diff1
      value: 56.4065
    - type: nauc_map_at_5_max
      value: 34.1343
    - type: nauc_map_at_5_std
      value: -17.1732
    - type: nauc_map_at_5_diff1
      value: 56.1246
    - type: nauc_map_at_10_max
      value: 34.1717
    - type: nauc_map_at_10_std
      value: -17.1179
    - type: nauc_map_at_10_diff1
      value: 56.041399999999996
    - type: nauc_map_at_20_max
      value: 34.1895
    - type: nauc_map_at_20_std
      value: -17.077
    - type: nauc_map_at_20_diff1
      value: 55.96489999999999
    - type: nauc_map_at_100_max
      value: 34.1922
    - type: nauc_map_at_100_std
      value: -17.0664
    - type: nauc_map_at_100_diff1
      value: 56.0487
    - type: nauc_map_at_1000_max
      value: 34.186
    - type: nauc_map_at_1000_std
      value: -17.0498
    - type: nauc_map_at_1000_diff1
      value: 56.0623
    - type: nauc_recall_at_1_max
      value: 34.1998
    - type: nauc_recall_at_1_std
      value: -15.7415
    - type: nauc_recall_at_1_diff1
      value: 61.8572
    - type: nauc_recall_at_3_max
      value: 32.6911
    - type: nauc_recall_at_3_std
      value: -19.4073
    - type: nauc_recall_at_3_diff1
      value: 49.1188
    - type: nauc_recall_at_5_max
      value: 33.7416
    - type: nauc_recall_at_5_std
      value: -17.965700000000002
    - type: nauc_recall_at_5_diff1
      value: 47.0821
    - type: nauc_recall_at_10_max
      value: 33.5209
    - type: nauc_recall_at_10_std
      value: -17.7965
    - type: nauc_recall_at_10_diff1
      value: 44.8874
    - type: nauc_recall_at_20_max
      value: 33.4757
    - type: nauc_recall_at_20_std
      value: -17.4921
    - type: nauc_recall_at_20_diff1
      value: 42.747
    - type: nauc_recall_at_100_max
      value: 32.2069
    - type: nauc_recall_at_100_std
      value: -15.6244
    - type: nauc_recall_at_100_diff1
      value: 43.0441
    - type: nauc_recall_at_1000_max
      value: 32.428000000000004
    - type: nauc_recall_at_1000_std
      value: -2.6172
    - type: nauc_recall_at_1000_diff1
      value: 42.1384
    - type: nauc_precision_at_1_max
      value: 34.1998
    - type: nauc_precision_at_1_std
      value: -15.7415
    - type: nauc_precision_at_1_diff1
      value: 61.8572
    - type: nauc_precision_at_3_max
      value: 32.6911
    - type: nauc_precision_at_3_std
      value: -19.4073
    - type: nauc_precision_at_3_diff1
      value: 49.1188
    - type: nauc_precision_at_5_max
      value: 33.7416
    - type: nauc_precision_at_5_std
      value: -17.965700000000002
    - type: nauc_precision_at_5_diff1
      value: 47.0821
    - type: nauc_precision_at_10_max
      value: 33.5209
    - type: nauc_precision_at_10_std
      value: -17.7965
    - type: nauc_precision_at_10_diff1
      value: 44.8874
    - type: nauc_precision_at_20_max
      value: 33.4757
    - type: nauc_precision_at_20_std
      value: -17.4921
    - type: nauc_precision_at_20_diff1
      value: 42.747
    - type: nauc_precision_at_100_max
      value: 32.2069
    - type: nauc_precision_at_100_std
      value: -15.6244
    - type: nauc_precision_at_100_diff1
      value: 43.0441
    - type: nauc_precision_at_1000_max
      value: 32.428000000000004
    - type: nauc_precision_at_1000_std
      value: -2.6172
    - type: nauc_precision_at_1000_diff1
      value: 42.1384
    - type: nauc_mrr_at_1_max
      value: 34.5467
    - type: nauc_mrr_at_1_std
      value: -15.676499999999999
    - type: nauc_mrr_at_1_diff1
      value: 61.8572
    - type: nauc_mrr_at_3_max
      value: 34.0355
    - type: nauc_mrr_at_3_std
      value: -17.448900000000002
    - type: nauc_mrr_at_3_diff1
      value: 56.4005
    - type: nauc_mrr_at_5_max
      value: 34.319100000000006
    - type: nauc_mrr_at_5_std
      value: -17.1276
    - type: nauc_mrr_at_5_diff1
      value: 56.1231
    - type: nauc_mrr_at_10_max
      value: 34.3588
    - type: nauc_mrr_at_10_std
      value: -17.0717
    - type: nauc_mrr_at_10_diff1
      value: 56.03979999999999
    - type: nauc_mrr_at_20_max
      value: 34.3778
    - type: nauc_mrr_at_20_std
      value: -17.0305
    - type: nauc_mrr_at_20_diff1
      value: 55.96339999999999
    - type: nauc_mrr_at_100_max
      value: 34.3812
    - type: nauc_mrr_at_100_std
      value: -17.022599999999997
    - type: nauc_mrr_at_100_diff1
      value: 56.0469
    - type: nauc_mrr_at_1000_max
      value: 34.375
    - type: nauc_mrr_at_1000_std
      value: -17.0037
    - type: nauc_mrr_at_1000_diff1
      value: 56.0608
    - type: main_score
      value: 51.686
    task:
      type: Retrieval
  - dataset:
      config: java
      name: MTEB CodeSearchNetCCRetrieval (java)
      revision: 6e1effa2c03723c5fde48ee912b5ee08d4f211e8
      split: test
      type: CoIR-Retrieval/CodeSearchNet-ccr
    metrics:
    - type: ndcg_at_1
      value: 39.744
    - type: ndcg_at_3
      value: 48.465
    - type: ndcg_at_5
      value: 50.615
    - type: ndcg_at_10
      value: 52.544000000000004
    - type: ndcg_at_20
      value: 53.864999999999995
    - type: ndcg_at_100
      value: 55.806
    - type: ndcg_at_1000
      value: 57.082
    - type: map_at_1
      value: 39.744
    - type: map_at_3
      value: 46.346
    - type: map_at_5
      value: 47.538000000000004
    - type: map_at_10
      value: 48.333999999999996
    - type: map_at_20
      value: 48.699999999999996
    - type: map_at_100
      value: 48.97
    - type: map_at_1000
      value: 49.014
    - type: recall_at_1
      value: 39.744
    - type: recall_at_3
      value: 54.586999999999996
    - type: recall_at_5
      value: 59.80799999999999
    - type: recall_at_10
      value: 65.778
    - type: recall_at_20
      value: 70.97200000000001
    - type: recall_at_100
      value: 81.415
    - type: recall_at_1000
      value: 91.702
    - type: precision_at_1
      value: 39.744
    - type: precision_at_3
      value: 18.196
    - type: precision_at_5
      value: 11.962
    - type: precision_at_10
      value: 6.578
    - type: precision_at_20
      value: 3.549
    - type: precision_at_100
      value: 0.814
    - type: precision_at_1000
      value: 0.092
    - type: mrr_at_1
      value: 39.7901
    - type: mrr_at_3
      value: 46.367000000000004
    - type: mrr_at_5
      value: 47.556799999999996
    - type: mrr_at_10
      value: 48.3531
    - type: mrr_at_20
      value: 48.7206
    - type: mrr_at_100
      value: 48.9901
    - type: mrr_at_1000
      value: 49.034
    - type: nauc_ndcg_at_1_max
      value: 31.1431
    - type: nauc_ndcg_at_1_std
      value: -10.407399999999999
    - type: nauc_ndcg_at_1_diff1
      value: 56.6466
    - type: nauc_ndcg_at_3_max
      value: 33.022800000000004
    - type: nauc_ndcg_at_3_std
      value: -9.5046
    - type: nauc_ndcg_at_3_diff1
      value: 52.7916
    - type: nauc_ndcg_at_5_max
      value: 33.1721
    - type: nauc_ndcg_at_5_std
      value: -9.0365
    - type: nauc_ndcg_at_5_diff1
      value: 52.317400000000006
    - type: nauc_ndcg_at_10_max
      value: 33.1837
    - type: nauc_ndcg_at_10_std
      value: -8.4008
    - type: nauc_ndcg_at_10_diff1
      value: 52.007999999999996
    - type: nauc_ndcg_at_20_max
      value: 33.024
    - type: nauc_ndcg_at_20_std
      value: -7.9246
    - type: nauc_ndcg_at_20_diff1
      value: 51.9078
    - type: nauc_ndcg_at_100_max
      value: 32.962599999999995
    - type: nauc_ndcg_at_100_std
      value: -7.4719
    - type: nauc_ndcg_at_100_diff1
      value: 51.94180000000001
    - type: nauc_ndcg_at_1000_max
      value: 33.1905
    - type: nauc_ndcg_at_1000_std
      value: -7.295599999999999
    - type: nauc_ndcg_at_1000_diff1
      value: 52.351099999999995
    - type: nauc_map_at_1_max
      value: 31.1431
    - type: nauc_map_at_1_std
      value: -10.407399999999999
    - type: nauc_map_at_1_diff1
      value: 56.6466
    - type: nauc_map_at_3_max
      value: 32.5713
    - type: nauc_map_at_3_std
      value: -9.734
    - type: nauc_map_at_3_diff1
      value: 53.703599999999994
    - type: nauc_map_at_5_max
      value: 32.6494
    - type: nauc_map_at_5_std
      value: -9.4813
    - type: nauc_map_at_5_diff1
      value: 53.4567
    - type: nauc_map_at_10_max
      value: 32.664100000000005
    - type: nauc_map_at_10_std
      value: -9.225999999999999
    - type: nauc_map_at_10_diff1
      value: 53.3589
    - type: nauc_map_at_20_max
      value: 32.6136
    - type: nauc_map_at_20_std
      value: -9.107899999999999
    - type: nauc_map_at_20_diff1
      value: 53.337
    - type: nauc_map_at_100_max
      value: 32.6036
    - type: nauc_map_at_100_std
      value: -9.0547
    - type: nauc_map_at_100_diff1
      value: 53.35339999999999
    - type: nauc_map_at_1000_max
      value: 32.610299999999995
    - type: nauc_map_at_1000_std
      value: -9.0493
    - type: nauc_map_at_1000_diff1
      value: 53.3656
    - type: nauc_recall_at_1_max
      value: 31.1431
    - type: nauc_recall_at_1_std
      value: -10.407399999999999
    - type: nauc_recall_at_1_diff1
      value: 56.6466
    - type: nauc_recall_at_3_max
      value: 34.3846
    - type: nauc_recall_at_3_std
      value: -8.8071
    - type: nauc_recall_at_3_diff1
      value: 50.047
    - type: nauc_recall_at_5_max
      value: 34.8431
    - type: nauc_recall_at_5_std
      value: -7.550999999999999
    - type: nauc_recall_at_5_diff1
      value: 48.6504
    - type: nauc_recall_at_10_max
      value: 34.9686
    - type: nauc_recall_at_10_std
      value: -5.1544
    - type: nauc_recall_at_10_diff1
      value: 47.0462
    - type: nauc_recall_at_20_max
      value: 34.441300000000005
    - type: nauc_recall_at_20_std
      value: -2.3698
    - type: nauc_recall_at_20_diff1
      value: 45.9903
    - type: nauc_recall_at_100_max
      value: 34.4855
    - type: nauc_recall_at_100_std
      value: 4.2675
    - type: nauc_recall_at_100_diff1
      value: 43.5966
    - type: nauc_recall_at_1000_max
      value: 42.692600000000006
    - type: nauc_recall_at_1000_std
      value: 21.8632
    - type: nauc_recall_at_1000_diff1
      value: 46.5143
    - type: nauc_precision_at_1_max
      value: 31.1431
    - type: nauc_precision_at_1_std
      value: -10.407399999999999
    - type: nauc_precision_at_1_diff1
      value: 56.6466
    - type: nauc_precision_at_3_max
      value: 34.3846
    - type: nauc_precision_at_3_std
      value: -8.8071
    - type: nauc_precision_at_3_diff1
      value: 50.047
    - type: nauc_precision_at_5_max
      value: 34.8431
    - type: nauc_precision_at_5_std
      value: -7.550999999999999
    - type: nauc_precision_at_5_diff1
      value: 48.6504
    - type: nauc_precision_at_10_max
      value: 34.9686
    - type: nauc_precision_at_10_std
      value: -5.1544
    - type: nauc_precision_at_10_diff1
      value: 47.0462
    - type: nauc_precision_at_20_max
      value: 34.441300000000005
    - type: nauc_precision_at_20_std
      value: -2.3698
    - type: nauc_precision_at_20_diff1
      value: 45.9903
    - type: nauc_precision_at_100_max
      value: 34.4855
    - type: nauc_precision_at_100_std
      value: 4.2675
    - type: nauc_precision_at_100_diff1
      value: 43.5966
    - type: nauc_precision_at_1000_max
      value: 42.692600000000006
    - type: nauc_precision_at_1000_std
      value: 21.8632
    - type: nauc_precision_at_1000_diff1
      value: 46.5143
    - type: nauc_mrr_at_1_max
      value: 31.1816
    - type: nauc_mrr_at_1_std
      value: -10.2945
    - type: nauc_mrr_at_1_diff1
      value: 56.5084
    - type: nauc_mrr_at_3_max
      value: 32.609300000000005
    - type: nauc_mrr_at_3_std
      value: -9.6538
    - type: nauc_mrr_at_3_diff1
      value: 53.6187
    - type: nauc_mrr_at_5_max
      value: 32.6863
    - type: nauc_mrr_at_5_std
      value: -9.3972
    - type: nauc_mrr_at_5_diff1
      value: 53.378400000000006
    - type: nauc_mrr_at_10_max
      value: 32.697700000000005
    - type: nauc_mrr_at_10_std
      value: -9.1456
    - type: nauc_mrr_at_10_diff1
      value: 53.2796
    - type: nauc_mrr_at_20_max
      value: 32.6496
    - type: nauc_mrr_at_20_std
      value: -9.0244
    - type: nauc_mrr_at_20_diff1
      value: 53.257600000000004
    - type: nauc_mrr_at_100_max
      value: 32.6402
    - type: nauc_mrr_at_100_std
      value: -8.970799999999999
    - type: nauc_mrr_at_100_diff1
      value: 53.274100000000004
    - type: nauc_mrr_at_1000_max
      value: 32.647
    - type: nauc_mrr_at_1000_std
      value: -8.9653
    - type: nauc_mrr_at_1000_diff1
      value: 53.286100000000005
    - type: main_score
      value: 52.544000000000004
    task:
      type: Retrieval
  - dataset:
      config: php
      name: MTEB CodeSearchNetCCRetrieval (php)
      revision: 6e1effa2c03723c5fde48ee912b5ee08d4f211e8
      split: test
      type: CoIR-Retrieval/CodeSearchNet-ccr
    metrics:
    - type: ndcg_at_1
      value: 29.685
    - type: ndcg_at_3
      value: 37.448
    - type: ndcg_at_5
      value: 39.781
    - type: ndcg_at_10
      value: 41.814
    - type: ndcg_at_20
      value: 43.333
    - type: ndcg_at_100
      value: 45.664
    - type: ndcg_at_1000
      value: 47.536
    - type: map_at_1
      value: 29.685
    - type: map_at_3
      value: 35.545
    - type: map_at_5
      value: 36.839
    - type: map_at_10
      value: 37.682
    - type: map_at_20
      value: 38.099
    - type: map_at_100
      value: 38.415
    - type: map_at_1000
      value: 38.478
    - type: recall_at_1
      value: 29.685
    - type: recall_at_3
      value: 42.95
    - type: recall_at_5
      value: 48.616
    - type: recall_at_10
      value: 54.888000000000005
    - type: recall_at_20
      value: 60.895999999999994
    - type: recall_at_100
      value: 73.548
    - type: recall_at_1000
      value: 88.697
    - type: precision_at_1
      value: 29.685
    - type: precision_at_3
      value: 14.316999999999998
    - type: precision_at_5
      value: 9.722999999999999
    - type: precision_at_10
      value: 5.489
    - type: precision_at_20
      value: 3.045
    - type: precision_at_100
      value: 0.735
    - type: precision_at_1000
      value: 0.089
    - type: mrr_at_1
      value: 29.6489
    - type: mrr_at_3
      value: 35.5299
    - type: mrr_at_5
      value: 36.8133
    - type: mrr_at_10
      value: 37.6632
    - type: mrr_at_20
      value: 38.079299999999996
    - type: mrr_at_100
      value: 38.3951
    - type: mrr_at_1000
      value: 38.4584
    - type: nauc_ndcg_at_1_max
      value: 23.1966
    - type: nauc_ndcg_at_1_std
      value: -9.4926
    - type: nauc_ndcg_at_1_diff1
      value: 50.2664
    - type: nauc_ndcg_at_3_max
      value: 22.9114
    - type: nauc_ndcg_at_3_std
      value: -9.3945
    - type: nauc_ndcg_at_3_diff1
      value: 45.266400000000004
    - type: nauc_ndcg_at_5_max
      value: 22.2736
    - type: nauc_ndcg_at_5_std
      value: -9.1173
    - type: nauc_ndcg_at_5_diff1
      value: 44.1003
    - type: nauc_ndcg_at_10_max
      value: 22.0212
    - type: nauc_ndcg_at_10_std
      value: -8.5559
    - type: nauc_ndcg_at_10_diff1
      value: 43.5542
    - type: nauc_ndcg_at_20_max
      value: 21.5977
    - type: nauc_ndcg_at_20_std
      value: -8.236400000000001
    - type: nauc_ndcg_at_20_diff1
      value: 43.1564
    - type: nauc_ndcg_at_100_max
      value: 21.4543
    - type: nauc_ndcg_at_100_std
      value: -7.5462
    - type: nauc_ndcg_at_100_diff1
      value: 43.1768
    - type: nauc_ndcg_at_1000_max
      value: 21.6202
    - type: nauc_ndcg_at_1000_std
      value: -7.5571
    - type: nauc_ndcg_at_1000_diff1
      value: 43.5388
    - type: nauc_map_at_1_max
      value: 23.1966
    - type: nauc_map_at_1_std
      value: -9.4926
    - type: nauc_map_at_1_diff1
      value: 50.2664
    - type: nauc_map_at_3_max
      value: 23.0018
    - type: nauc_map_at_3_std
      value: -9.4391
    - type: nauc_map_at_3_diff1
      value: 46.428000000000004
    - type: nauc_map_at_5_max
      value: 22.642300000000002
    - type: nauc_map_at_5_std
      value: -9.2849
    - type: nauc_map_at_5_diff1
      value: 45.776
    - type: nauc_map_at_10_max
      value: 22.551099999999998
    - type: nauc_map_at_10_std
      value: -9.045300000000001
    - type: nauc_map_at_10_diff1
      value: 45.5645
    - type: nauc_map_at_20_max
      value: 22.4407
    - type: nauc_map_at_20_std
      value: -8.9542
    - type: nauc_map_at_20_diff1
      value: 45.4588
    - type: nauc_map_at_100_max
      value: 22.4247
    - type: nauc_map_at_100_std
      value: -8.869299999999999
    - type: nauc_map_at_100_diff1
      value: 45.467200000000005
    - type: nauc_map_at_1000_max
      value: 22.429299999999998
    - type: nauc_map_at_1000_std
      value: -8.8653
    - type: nauc_map_at_1000_diff1
      value: 45.479
    - type: nauc_recall_at_1_max
      value: 23.1966
    - type: nauc_recall_at_1_std
      value: -9.4926
    - type: nauc_recall_at_1_diff1
      value: 50.2664
    - type: nauc_recall_at_3_max
      value: 22.6466
    - type: nauc_recall_at_3_std
      value: -9.259599999999999
    - type: nauc_recall_at_3_diff1
      value: 41.9917
    - type: nauc_recall_at_5_max
      value: 21.121100000000002
    - type: nauc_recall_at_5_std
      value: -8.5882
    - type: nauc_recall_at_5_diff1
      value: 39.1445
    - type: nauc_recall_at_10_max
      value: 20.191200000000002
    - type: nauc_recall_at_10_std
      value: -6.824
    - type: nauc_recall_at_10_diff1
      value: 37.107
    - type: nauc_recall_at_20_max
      value: 18.2104
    - type: nauc_recall_at_20_std
      value: -5.3749
    - type: nauc_recall_at_20_diff1
      value: 34.9673
    - type: nauc_recall_at_100_max
      value: 16.0859
    - type: nauc_recall_at_100_std
      value: 0.7539
    - type: nauc_recall_at_100_diff1
      value: 32.603500000000004
    - type: nauc_recall_at_1000_max
      value: 14.1642
    - type: nauc_recall_at_1000_std
      value: 8.5463
    - type: nauc_recall_at_1000_diff1
      value: 29.5927
    - type: nauc_precision_at_1_max
      value: 23.1966
    - type: nauc_precision_at_1_std
      value: -9.4926
    - type: nauc_precision_at_1_diff1
      value: 50.2664
    - type: nauc_precision_at_3_max
      value: 22.6466
    - type: nauc_precision_at_3_std
      value: -9.259599999999999
    - type: nauc_precision_at_3_diff1
      value: 41.9917
    - type: nauc_precision_at_5_max
      value: 21.121100000000002
    - type: nauc_precision_at_5_std
      value: -8.5882
    - type: nauc_precision_at_5_diff1
      value: 39.1445
    - type: nauc_precision_at_10_max
      value: 20.191200000000002
    - type: nauc_precision_at_10_std
      value: -6.824
    - type: nauc_precision_at_10_diff1
      value: 37.107
    - type: nauc_precision_at_20_max
      value: 18.2104
    - type: nauc_precision_at_20_std
      value: -5.3749
    - type: nauc_precision_at_20_diff1
      value: 34.9673
    - type: nauc_precision_at_100_max
      value: 16.0859
    - type: nauc_precision_at_100_std
      value: 0.7539
    - type: nauc_precision_at_100_diff1
      value: 32.603500000000004
    - type: nauc_precision_at_1000_max
      value: 14.1642
    - type: nauc_precision_at_1000_std
      value: 8.5463
    - type: nauc_precision_at_1000_diff1
      value: 29.5927
    - type: nauc_mrr_at_1_max
      value: 23.2502
    - type: nauc_mrr_at_1_std
      value: -9.507
    - type: nauc_mrr_at_1_diff1
      value: 50.3997
    - type: nauc_mrr_at_3_max
      value: 23.009
    - type: nauc_mrr_at_3_std
      value: -9.4541
    - type: nauc_mrr_at_3_diff1
      value: 46.4733
    - type: nauc_mrr_at_5_max
      value: 22.656000000000002
    - type: nauc_mrr_at_5_std
      value: -9.2987
    - type: nauc_mrr_at_5_diff1
      value: 45.839999999999996
    - type: nauc_mrr_at_10_max
      value: 22.5697
    - type: nauc_mrr_at_10_std
      value: -9.0543
    - type: nauc_mrr_at_10_diff1
      value: 45.618700000000004
    - type: nauc_mrr_at_20_max
      value: 22.461000000000002
    - type: nauc_mrr_at_20_std
      value: -8.9628
    - type: nauc_mrr_at_20_diff1
      value: 45.5146
    - type: nauc_mrr_at_100_max
      value: 22.4449
    - type: nauc_mrr_at_100_std
      value: -8.877699999999999
    - type: nauc_mrr_at_100_diff1
      value: 45.5229
    - type: nauc_mrr_at_1000_max
      value: 22.4498
    - type: nauc_mrr_at_1000_std
      value: -8.873899999999999
    - type: nauc_mrr_at_1000_diff1
      value: 45.535199999999996
    - type: main_score
      value: 41.814
    task:
      type: Retrieval
  - dataset:
      config: python
      name: MTEB CodeSearchNetRetrieval (python)
      revision: fdc6a9e39575768c27eb8a2a5f702bf846eb4759
      split: test
      type: code-search-net/code_search_net
    metrics:
    - type: ndcg_at_1
      value: 73.5
    - type: ndcg_at_3
      value: 82.35900000000001
    - type: ndcg_at_5
      value: 83.543
    - type: ndcg_at_10
      value: 84.357
    - type: ndcg_at_20
      value: 84.973
    - type: ndcg_at_100
      value: 85.449
    - type: ndcg_at_1000
      value: 85.591
    - type: map_at_1
      value: 73.5
    - type: map_at_3
      value: 80.2
    - type: map_at_5
      value: 80.85
    - type: map_at_10
      value: 81.189
    - type: map_at_20
      value: 81.364
    - type: map_at_100
      value: 81.434
    - type: map_at_1000
      value: 81.44
    - type: recall_at_1
      value: 73.5
    - type: recall_at_3
      value: 88.6
    - type: recall_at_5
      value: 91.5
    - type: recall_at_10
      value: 94.0
    - type: recall_at_20
      value: 96.39999999999999
    - type: recall_at_100
      value: 98.9
    - type: recall_at_1000
      value: 100.0
    - type: precision_at_1
      value: 73.5
    - type: precision_at_3
      value: 29.532999999999998
    - type: precision_at_5
      value: 18.3
    - type: precision_at_10
      value: 9.4
    - type: precision_at_20
      value: 4.82
    - type: precision_at_100
      value: 0.989
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 73.5
    - type: mrr_at_3
      value: 80.2
    - type: mrr_at_5
      value: 80.85
    - type: mrr_at_10
      value: 81.1894
    - type: mrr_at_20
      value: 81.3638
    - type: mrr_at_100
      value: 81.43430000000001
    - type: mrr_at_1000
      value: 81.44
    - type: nauc_ndcg_at_1_max
      value: 45.553
    - type: nauc_ndcg_at_1_std
      value: -3.8149
    - type: nauc_ndcg_at_1_diff1
      value: 72.4638
    - type: nauc_ndcg_at_3_max
      value: 47.8454
    - type: nauc_ndcg_at_3_std
      value: -3.2174
    - type: nauc_ndcg_at_3_diff1
      value: 69.05059999999999
    - type: nauc_ndcg_at_5_max
      value: 48.105599999999995
    - type: nauc_ndcg_at_5_std
      value: -3.0107
    - type: nauc_ndcg_at_5_diff1
      value: 70.2436
    - type: nauc_ndcg_at_10_max
      value: 48.871900000000004
    - type: nauc_ndcg_at_10_std
      value: -2.7289
    - type: nauc_ndcg_at_10_diff1
      value: 70.87440000000001
    - type: nauc_ndcg_at_20_max
      value: 49.1441
    - type: nauc_ndcg_at_20_std
      value: -2.2193
    - type: nauc_ndcg_at_20_diff1
      value: 70.9602
    - type: nauc_ndcg_at_100_max
      value: 48.2597
    - type: nauc_ndcg_at_100_std
      value: -2.8648
    - type: nauc_ndcg_at_100_diff1
      value: 70.5487
    - type: nauc_ndcg_at_1000_max
      value: 48.0576
    - type: nauc_ndcg_at_1000_std
      value: -3.0315000000000003
    - type: nauc_ndcg_at_1000_diff1
      value: 70.8214
    - type: nauc_map_at_1_max
      value: 45.553
    - type: nauc_map_at_1_std
      value: -3.8149
    - type: nauc_map_at_1_diff1
      value: 72.4638
    - type: nauc_map_at_3_max
      value: 47.143
    - type: nauc_map_at_3_std
      value: -3.4511
    - type: nauc_map_at_3_diff1
      value: 70.2411
    - type: nauc_map_at_5_max
      value: 47.2524
    - type: nauc_map_at_5_std
      value: -3.3834999999999997
    - type: nauc_map_at_5_diff1
      value: 70.8691
    - type: nauc_map_at_10_max
      value: 47.5215
    - type: nauc_map_at_10_std
      value: -3.3042000000000002
    - type: nauc_map_at_10_diff1
      value: 71.1041
    - type: nauc_map_at_20_max
      value: 47.5871
    - type: nauc_map_at_20_std
      value: -3.1888
    - type: nauc_map_at_20_diff1
      value: 71.1157
    - type: nauc_map_at_100_max
      value: 47.4746
    - type: nauc_map_at_100_std
      value: -3.3092
    - type: nauc_map_at_100_diff1
      value: 71.0626
    - type: nauc_map_at_1000_max
      value: 47.4686
    - type: nauc_map_at_1000_std
      value: -3.3099000000000003
    - type: nauc_map_at_1000_diff1
      value: 71.0712
    - type: nauc_recall_at_1_max
      value: 45.553
    - type: nauc_recall_at_1_std
      value: -3.8149
    - type: nauc_recall_at_1_diff1
      value: 72.4638
    - type: nauc_recall_at_3_max
      value: 51.09590000000001
    - type: nauc_recall_at_3_std
      value: -2.1018
    - type: nauc_recall_at_3_diff1
      value: 63.4433
    - type: nauc_recall_at_5_max
      value: 53.195499999999996
    - type: nauc_recall_at_5_std
      value: -0.6421
    - type: nauc_recall_at_5_diff1
      value: 66.7381
    - type: nauc_recall_at_10_max
      value: 60.660599999999995
    - type: nauc_recall_at_10_std
      value: 2.5576000000000003
    - type: nauc_recall_at_10_diff1
      value: 69.8771
    - type: nauc_recall_at_20_max
      value: 72.0082
    - type: nauc_recall_at_20_std
      value: 13.519300000000001
    - type: nauc_recall_at_20_diff1
      value: 70.8774
    - type: nauc_recall_at_100_max
      value: 67.6683
    - type: nauc_recall_at_100_std
      value: 16.4757
    - type: nauc_recall_at_100_diff1
      value: 45.535199999999996
    - type: nauc_recall_at_1000_max
      value: .nan
    - type: nauc_recall_at_1000_std
      value: .nan
    - type: nauc_recall_at_1000_diff1
      value: .nan
    - type: nauc_precision_at_1_max
      value: 45.553
    - type: nauc_precision_at_1_std
      value: -3.8149
    - type: nauc_precision_at_1_diff1
      value: 72.4638
    - type: nauc_precision_at_3_max
      value: 51.09590000000001
    - type: nauc_precision_at_3_std
      value: -2.1018
    - type: nauc_precision_at_3_diff1
      value: 63.4433
    - type: nauc_precision_at_5_max
      value: 53.195499999999996
    - type: nauc_precision_at_5_std
      value: -0.6421
    - type: nauc_precision_at_5_diff1
      value: 66.7381
    - type: nauc_precision_at_10_max
      value: 60.660599999999995
    - type: nauc_precision_at_10_std
      value: 2.5576000000000003
    - type: nauc_precision_at_10_diff1
      value: 69.8771
    - type: nauc_precision_at_20_max
      value: 72.0082
    - type: nauc_precision_at_20_std
      value: 13.519300000000001
    - type: nauc_precision_at_20_diff1
      value: 70.8774
    - type: nauc_precision_at_100_max
      value: 67.6683
    - type: nauc_precision_at_100_std
      value: 16.4757
    - type: nauc_precision_at_100_diff1
      value: 45.535199999999996
    - type: nauc_precision_at_1000_max
      value: .nan
    - type: nauc_precision_at_1000_std
      value: .nan
    - type: nauc_precision_at_1000_diff1
      value: .nan
    - type: nauc_mrr_at_1_max
      value: 45.553
    - type: nauc_mrr_at_1_std
      value: -3.8149
    - type: nauc_mrr_at_1_diff1
      value: 72.4638
    - type: nauc_mrr_at_3_max
      value: 47.143
    - type: nauc_mrr_at_3_std
      value: -3.4511
    - type: nauc_mrr_at_3_diff1
      value: 70.2411
    - type: nauc_mrr_at_5_max
      value: 47.2524
    - type: nauc_mrr_at_5_std
      value: -3.3834999999999997
    - type: nauc_mrr_at_5_diff1
      value: 70.8691
    - type: nauc_mrr_at_10_max
      value: 47.5215
    - type: nauc_mrr_at_10_std
      value: -3.3042000000000002
    - type: nauc_mrr_at_10_diff1
      value: 71.1041
    - type: nauc_mrr_at_20_max
      value: 47.5871
    - type: nauc_mrr_at_20_std
      value: -3.1888
    - type: nauc_mrr_at_20_diff1
      value: 71.1157
    - type: nauc_mrr_at_100_max
      value: 47.4746
    - type: nauc_mrr_at_100_std
      value: -3.3092
    - type: nauc_mrr_at_100_diff1
      value: 71.0626
    - type: nauc_mrr_at_1000_max
      value: 47.4686
    - type: nauc_mrr_at_1000_std
      value: -3.3099000000000003
    - type: nauc_mrr_at_1000_diff1
      value: 71.0712
    - type: main_score
      value: 84.357
    task:
      type: Retrieval
  - dataset:
      config: javascript
      name: MTEB CodeSearchNetRetrieval (javascript)
      revision: fdc6a9e39575768c27eb8a2a5f702bf846eb4759
      split: test
      type: code-search-net/code_search_net
    metrics:
    - type: ndcg_at_1
      value: 59.4
    - type: ndcg_at_3
      value: 68.58800000000001
    - type: ndcg_at_5
      value: 70.0
    - type: ndcg_at_10
      value: 71.384
    - type: ndcg_at_20
      value: 72.505
    - type: ndcg_at_100
      value: 73.532
    - type: ndcg_at_1000
      value: 74.414
    - type: map_at_1
      value: 59.4
    - type: map_at_3
      value: 66.367
    - type: map_at_5
      value: 67.157
    - type: map_at_10
      value: 67.72399999999999
    - type: map_at_20
      value: 68.036
    - type: map_at_100
      value: 68.182
    - type: map_at_1000
      value: 68.208
    - type: recall_at_1
      value: 59.4
    - type: recall_at_3
      value: 75.0
    - type: recall_at_5
      value: 78.4
    - type: recall_at_10
      value: 82.69999999999999
    - type: recall_at_20
      value: 87.1
    - type: recall_at_100
      value: 92.60000000000001
    - type: recall_at_1000
      value: 100.0
    - type: precision_at_1
      value: 59.4
    - type: precision_at_3
      value: 25.0
    - type: precision_at_5
      value: 15.68
    - type: precision_at_10
      value: 8.27
    - type: precision_at_20
      value: 4.3549999999999995
    - type: precision_at_100
      value: 0.9259999999999999
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 59.4
    - type: mrr_at_3
      value: 66.3667
    - type: mrr_at_5
      value: 67.1567
    - type: mrr_at_10
      value: 67.72399999999999
    - type: mrr_at_20
      value: 68.036
    - type: mrr_at_100
      value: 68.1821
    - type: mrr_at_1000
      value: 68.20779999999999
    - type: nauc_ndcg_at_1_max
      value: 55.2077
    - type: nauc_ndcg_at_1_std
      value: 23.8385
    - type: nauc_ndcg_at_1_diff1
      value: 72.8827
    - type: nauc_ndcg_at_3_max
      value: 62.495
    - type: nauc_ndcg_at_3_std
      value: 31.867800000000003
    - type: nauc_ndcg_at_3_diff1
      value: 69.8148
    - type: nauc_ndcg_at_5_max
      value: 63.132999999999996
    - type: nauc_ndcg_at_5_std
      value: 33.3486
    - type: nauc_ndcg_at_5_diff1
      value: 69.8501
    - type: nauc_ndcg_at_10_max
      value: 64.3507
    - type: nauc_ndcg_at_10_std
      value: 36.4767
    - type: nauc_ndcg_at_10_diff1
      value: 69.5995
    - type: nauc_ndcg_at_20_max
      value: 63.930299999999995
    - type: nauc_ndcg_at_20_std
      value: 36.8457
    - type: nauc_ndcg_at_20_diff1
      value: 70.0822
    - type: nauc_ndcg_at_100_max
      value: 63.10249999999999
    - type: nauc_ndcg_at_100_std
      value: 36.4228
    - type: nauc_ndcg_at_100_diff1
      value: 70.0219
    - type: nauc_ndcg_at_1000_max
      value: 62.3826
    - type: nauc_ndcg_at_1000_std
      value: 34.2464
    - type: nauc_ndcg_at_1000_diff1
      value: 70.2371
    - type: nauc_map_at_1_max
      value: 55.2077
    - type: nauc_map_at_1_std
      value: 23.8385
    - type: nauc_map_at_1_diff1
      value: 72.8827
    - type: nauc_map_at_3_max
      value: 60.4208
    - type: nauc_map_at_3_std
      value: 29.6445
    - type: nauc_map_at_3_diff1
      value: 70.58630000000001
    - type: nauc_map_at_5_max
      value: 60.709900000000005
    - type: nauc_map_at_5_std
      value: 30.400899999999996
    - type: nauc_map_at_5_diff1
      value: 70.6255
    - type: nauc_map_at_10_max
      value: 61.152499999999996
    - type: nauc_map_at_10_std
      value: 31.550800000000002
    - type: nauc_map_at_10_diff1
      value: 70.56099999999999
    - type: nauc_map_at_20_max
      value: 61.0075
    - type: nauc_map_at_20_std
      value: 31.585600000000003
    - type: nauc_map_at_20_diff1
      value: 70.6649
    - type: nauc_map_at_100_max
      value: 60.90370000000001
    - type: nauc_map_at_100_std
      value: 31.510700000000003
    - type: nauc_map_at_100_diff1
      value: 70.66839999999999
    - type: nauc_map_at_1000_max
      value: 60.8865
    - type: nauc_map_at_1000_std
      value: 31.4572
    - type: nauc_map_at_1000_diff1
      value: 70.6705
    - type: nauc_recall_at_1_max
      value: 55.2077
    - type: nauc_recall_at_1_std
      value: 23.8385
    - type: nauc_recall_at_1_diff1
      value: 72.8827
    - type: nauc_recall_at_3_max
      value: 69.92819999999999
    - type: nauc_recall_at_3_std
      value: 39.8045
    - type: nauc_recall_at_3_diff1
      value: 67.10040000000001
    - type: nauc_recall_at_5_max
      value: 72.8013
    - type: nauc_recall_at_5_std
      value: 45.1476
    - type: nauc_recall_at_5_diff1
      value: 66.84790000000001
    - type: nauc_recall_at_10_max
      value: 80.1828
    - type: nauc_recall_at_10_std
      value: 61.6781
    - type: nauc_recall_at_10_diff1
      value: 64.9272
    - type: nauc_recall_at_20_max
      value: 82.11840000000001
    - type: nauc_recall_at_20_std
      value: 72.1146
    - type: nauc_recall_at_20_diff1
      value: 67.3756
    - type: nauc_recall_at_100_max
      value: 80.8836
    - type: nauc_recall_at_100_std
      value: 89.47810000000001
    - type: nauc_recall_at_100_diff1
      value: 64.169
    - type: nauc_recall_at_1000_max
      value: .nan
    - type: nauc_recall_at_1000_std
      value: .nan
    - type: nauc_recall_at_1000_diff1
      value: .nan
    - type: nauc_precision_at_1_max
      value: 55.2077
    - type: nauc_precision_at_1_std
      value: 23.8385
    - type: nauc_precision_at_1_diff1
      value: 72.8827
    - type: nauc_precision_at_3_max
      value: 69.92819999999999
    - type: nauc_precision_at_3_std
      value: 39.8045
    - type: nauc_precision_at_3_diff1
      value: 67.10040000000001
    - type: nauc_precision_at_5_max
      value: 72.8013
    - type: nauc_precision_at_5_std
      value: 45.1476
    - type: nauc_precision_at_5_diff1
      value: 66.84790000000001
    - type: nauc_precision_at_10_max
      value: 80.1828
    - type: nauc_precision_at_10_std
      value: 61.6781
    - type: nauc_precision_at_10_diff1
      value: 64.9272
    - type: nauc_precision_at_20_max
      value: 82.11840000000001
    - type: nauc_precision_at_20_std
      value: 72.1146
    - type: nauc_precision_at_20_diff1
      value: 67.3756
    - type: nauc_precision_at_100_max
      value: 80.8836
    - type: nauc_precision_at_100_std
      value: 89.47810000000001
    - type: nauc_precision_at_100_diff1
      value: 64.169
    - type: nauc_precision_at_1000_max
      value: .nan
    - type: nauc_precision_at_1000_std
      value: .nan
    - type: nauc_precision_at_1000_diff1
      value: .nan
    - type: nauc_mrr_at_1_max
      value: 55.2077
    - type: nauc_mrr_at_1_std
      value: 23.8385
    - type: nauc_mrr_at_1_diff1
      value: 72.8827
    - type: nauc_mrr_at_3_max
      value: 60.4208
    - type: nauc_mrr_at_3_std
      value: 29.6445
    - type: nauc_mrr_at_3_diff1
      value: 70.58630000000001
    - type: nauc_mrr_at_5_max
      value: 60.709900000000005
    - type: nauc_mrr_at_5_std
      value: 30.400899999999996
    - type: nauc_mrr_at_5_diff1
      value: 70.6255
    - type: nauc_mrr_at_10_max
      value: 61.152499999999996
    - type: nauc_mrr_at_10_std
      value: 31.550800000000002
    - type: nauc_mrr_at_10_diff1
      value: 70.56099999999999
    - type: nauc_mrr_at_20_max
      value: 61.0075
    - type: nauc_mrr_at_20_std
      value: 31.585600000000003
    - type: nauc_mrr_at_20_diff1
      value: 70.6649
    - type: nauc_mrr_at_100_max
      value: 60.90370000000001
    - type: nauc_mrr_at_100_std
      value: 31.510700000000003
    - type: nauc_mrr_at_100_diff1
      value: 70.66839999999999
    - type: nauc_mrr_at_1000_max
      value: 60.8865
    - type: nauc_mrr_at_1000_std
      value: 31.4572
    - type: nauc_mrr_at_1000_diff1
      value: 70.6705
    - type: main_score
      value: 71.384
    task:
      type: Retrieval
  - dataset:
      config: go
      name: MTEB CodeSearchNetRetrieval (go)
      revision: fdc6a9e39575768c27eb8a2a5f702bf846eb4759
      split: test
      type: code-search-net/code_search_net
    metrics:
    - type: ndcg_at_1
      value: 71.39999999999999
    - type: ndcg_at_3
      value: 82.32000000000001
    - type: ndcg_at_5
      value: 84.22699999999999
    - type: ndcg_at_10
      value: 84.922
    - type: ndcg_at_20
      value: 85.226
    - type: ndcg_at_100
      value: 85.563
    - type: ndcg_at_1000
      value: 85.66
    - type: map_at_1
      value: 71.39999999999999
    - type: map_at_3
      value: 79.783
    - type: map_at_5
      value: 80.848
    - type: map_at_10
      value: 81.145
    - type: map_at_20
      value: 81.229
    - type: map_at_100
      value: 81.284
    - type: map_at_1000
      value: 81.286
    - type: recall_at_1
      value: 71.39999999999999
    - type: recall_at_3
      value: 89.60000000000001
    - type: recall_at_5
      value: 94.19999999999999
    - type: recall_at_10
      value: 96.3
    - type: recall_at_20
      value: 97.5
    - type: recall_at_100
      value: 99.2
    - type: recall_at_1000
      value: 100.0
    - type: precision_at_1
      value: 71.39999999999999
    - type: precision_at_3
      value: 29.866999999999997
    - type: precision_at_5
      value: 18.84
    - type: precision_at_10
      value: 9.629999999999999
    - type: precision_at_20
      value: 4.875
    - type: precision_at_100
      value: 0.992
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 71.39999999999999
    - type: mrr_at_3
      value: 79.7833
    - type: mrr_at_5
      value: 80.8483
    - type: mrr_at_10
      value: 81.14489999999999
    - type: mrr_at_20
      value: 81.22890000000001
    - type: mrr_at_100
      value: 81.2836
    - type: mrr_at_1000
      value: 81.28649999999999
    - type: nauc_ndcg_at_1_max
      value: 46.2744
    - type: nauc_ndcg_at_1_std
      value: -2.9863
    - type: nauc_ndcg_at_1_diff1
      value: 74.0857
    - type: nauc_ndcg_at_3_max
      value: 54.4012
    - type: nauc_ndcg_at_3_std
      value: -3.3299000000000003
    - type: nauc_ndcg_at_3_diff1
      value: 70.891
    - type: nauc_ndcg_at_5_max
      value: 54.3223
    - type: nauc_ndcg_at_5_std
      value: -1.6239
    - type: nauc_ndcg_at_5_diff1
      value: 71.7397
    - type: nauc_ndcg_at_10_max
      value: 53.629099999999994
    - type: nauc_ndcg_at_10_std
      value: -1.8041999999999998
    - type: nauc_ndcg_at_10_diff1
      value: 72.8108
    - type: nauc_ndcg_at_20_max
      value: 52.8247
    - type: nauc_ndcg_at_20_std
      value: -2.6823
    - type: nauc_ndcg_at_20_diff1
      value: 72.7573
    - type: nauc_ndcg_at_100_max
      value: 52.359
    - type: nauc_ndcg_at_100_std
      value: -2.8805
    - type: nauc_ndcg_at_100_diff1
      value: 72.8282
    - type: nauc_ndcg_at_1000_max
      value: 52.1323
    - type: nauc_ndcg_at_1000_std
      value: -2.8353
    - type: nauc_ndcg_at_1000_diff1
      value: 72.6771
    - type: nauc_map_at_1_max
      value: 46.2744
    - type: nauc_map_at_1_std
      value: -2.9863
    - type: nauc_map_at_1_diff1
      value: 74.0857
    - type: nauc_map_at_3_max
      value: 52.0957
    - type: nauc_map_at_3_std
      value: -3.5077999999999996
    - type: nauc_map_at_3_diff1
      value: 71.90530000000001
    - type: nauc_map_at_5_max
      value: 51.9209
    - type: nauc_map_at_5_std
      value: -2.7184
    - type: nauc_map_at_5_diff1
      value: 72.3474
    - type: nauc_map_at_10_max
      value: 51.642900000000004
    - type: nauc_map_at_10_std
      value: -2.8069
    - type: nauc_map_at_10_diff1
      value: 72.74589999999999
    - type: nauc_map_at_20_max
      value: 51.451800000000006
    - type: nauc_map_at_20_std
      value: -2.9922
    - type: nauc_map_at_20_diff1
      value: 72.7222
    - type: nauc_map_at_100_max
      value: 51.3795
    - type: nauc_map_at_100_std
      value: -3.0112
    - type: nauc_map_at_100_diff1
      value: 72.723
    - type: nauc_map_at_1000_max
      value: 51.3724
    - type: nauc_map_at_1000_std
      value: -3.009
    - type: nauc_map_at_1000_diff1
      value: 72.7192
    - type: nauc_recall_at_1_max
      value: 46.2744
    - type: nauc_recall_at_1_std
      value: -2.9863
    - type: nauc_recall_at_1_diff1
      value: 74.0857
    - type: nauc_recall_at_3_max
      value: 65.8657
    - type: nauc_recall_at_3_std
      value: -2.2125
    - type: nauc_recall_at_3_diff1
      value: 65.75649999999999
    - type: nauc_recall_at_5_max
      value: 74.348
    - type: nauc_recall_at_5_std
      value: 8.7503
    - type: nauc_recall_at_5_diff1
      value: 66.9693
    - type: nauc_recall_at_10_max
      value: 77.9494
    - type: nauc_recall_at_10_std
      value: 12.8688
    - type: nauc_recall_at_10_diff1
      value: 75.7287
    - type: nauc_recall_at_20_max
      value: 72.9655
    - type: nauc_recall_at_20_std
      value: 0.8702
    - type: nauc_recall_at_20_diff1
      value: 76.5864
    - type: nauc_recall_at_100_max
      value: 80.4563
    - type: nauc_recall_at_100_std
      value: -9.278699999999999
    - type: nauc_recall_at_100_diff1
      value: 92.793
    - type: nauc_recall_at_1000_max
      value: .nan
    - type: nauc_recall_at_1000_std
      value: .nan
    - type: nauc_recall_at_1000_diff1
      value: .nan
    - type: nauc_precision_at_1_max
      value: 46.2744
    - type: nauc_precision_at_1_std
      value: -2.9863
    - type: nauc_precision_at_1_diff1
      value: 74.0857
    - type: nauc_precision_at_3_max
      value: 65.8657
    - type: nauc_precision_at_3_std
      value: -2.2125
    - type: nauc_precision_at_3_diff1
      value: 65.75649999999999
    - type: nauc_precision_at_5_max
      value: 74.348
    - type: nauc_precision_at_5_std
      value: 8.7503
    - type: nauc_precision_at_5_diff1
      value: 66.9693
    - type: nauc_precision_at_10_max
      value: 77.9494
    - type: nauc_precision_at_10_std
      value: 12.8688
    - type: nauc_precision_at_10_diff1
      value: 75.7287
    - type: nauc_precision_at_20_max
      value: 72.9655
    - type: nauc_precision_at_20_std
      value: 0.8702
    - type: nauc_precision_at_20_diff1
      value: 76.5864
    - type: nauc_precision_at_100_max
      value: 80.4563
    - type: nauc_precision_at_100_std
      value: -9.278699999999999
    - type: nauc_precision_at_100_diff1
      value: 92.793
    - type: nauc_precision_at_1000_max
      value: .nan
    - type: nauc_precision_at_1000_std
      value: .nan
    - type: nauc_precision_at_1000_diff1
      value: .nan
    - type: nauc_mrr_at_1_max
      value: 46.2744
    - type: nauc_mrr_at_1_std
      value: -2.9863
    - type: nauc_mrr_at_1_diff1
      value: 74.0857
    - type: nauc_mrr_at_3_max
      value: 52.0957
    - type: nauc_mrr_at_3_std
      value: -3.5077999999999996
    - type: nauc_mrr_at_3_diff1
      value: 71.90530000000001
    - type: nauc_mrr_at_5_max
      value: 51.9209
    - type: nauc_mrr_at_5_std
      value: -2.7184
    - type: nauc_mrr_at_5_diff1
      value: 72.3474
    - type: nauc_mrr_at_10_max
      value: 51.642900000000004
    - type: nauc_mrr_at_10_std
      value: -2.8069
    - type: nauc_mrr_at_10_diff1
      value: 72.74589999999999
    - type: nauc_mrr_at_20_max
      value: 51.451800000000006
    - type: nauc_mrr_at_20_std
      value: -2.9922
    - type: nauc_mrr_at_20_diff1
      value: 72.7222
    - type: nauc_mrr_at_100_max
      value: 51.3795
    - type: nauc_mrr_at_100_std
      value: -3.0112
    - type: nauc_mrr_at_100_diff1
      value: 72.723
    - type: nauc_mrr_at_1000_max
      value: 51.3724
    - type: nauc_mrr_at_1000_std
      value: -3.009
    - type: nauc_mrr_at_1000_diff1
      value: 72.7192
    - type: main_score
      value: 84.922
    task:
      type: Retrieval
  - dataset:
      config: ruby
      name: MTEB CodeSearchNetRetrieval (ruby)
      revision: fdc6a9e39575768c27eb8a2a5f702bf846eb4759
      split: test
      type: code-search-net/code_search_net
    metrics:
    - type: ndcg_at_1
      value: 61.9
    - type: ndcg_at_3
      value: 71.91
    - type: ndcg_at_5
      value: 74.11
    - type: ndcg_at_10
      value: 75.274
    - type: ndcg_at_20
      value: 75.97
    - type: ndcg_at_100
      value: 77.021
    - type: ndcg_at_1000
      value: 77.511
    - type: map_at_1
      value: 61.9
    - type: map_at_3
      value: 69.55
    - type: map_at_5
      value: 70.78
    - type: map_at_10
      value: 71.26
    - type: map_at_20
      value: 71.45899999999999
    - type: map_at_100
      value: 71.609
    - type: map_at_1000
      value: 71.624
    - type: recall_at_1
      value: 61.9
    - type: recall_at_3
      value: 78.7
    - type: recall_at_5
      value: 84.0
    - type: recall_at_10
      value: 87.6
    - type: recall_at_20
      value: 90.3
    - type: recall_at_100
      value: 95.89999999999999
    - type: recall_at_1000
      value: 100.0
    - type: precision_at_1
      value: 61.9
    - type: precision_at_3
      value: 26.233
    - type: precision_at_5
      value: 16.8
    - type: precision_at_10
      value: 8.76
    - type: precision_at_20
      value: 4.515000000000001
    - type: precision_at_100
      value: 0.959
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 61.9
    - type: mrr_at_3
      value: 69.55
    - type: mrr_at_5
      value: 70.78
    - type: mrr_at_10
      value: 71.2604
    - type: mrr_at_20
      value: 71.4589
    - type: mrr_at_100
      value: 71.609
    - type: mrr_at_1000
      value: 71.6242
    - type: nauc_ndcg_at_1_max
      value: 51.8333
    - type: nauc_ndcg_at_1_std
      value: 8.4163
    - type: nauc_ndcg_at_1_diff1
      value: 72.37700000000001
    - type: nauc_ndcg_at_3_max
      value: 56.0395
    - type: nauc_ndcg_at_3_std
      value: 12.583
    - type: nauc_ndcg_at_3_diff1
      value: 67.5758
    - type: nauc_ndcg_at_5_max
      value: 56.35289999999999
    - type: nauc_ndcg_at_5_std
      value: 13.9102
    - type: nauc_ndcg_at_5_diff1
      value: 68.36179999999999
    - type: nauc_ndcg_at_10_max
      value: 55.954499999999996
    - type: nauc_ndcg_at_10_std
      value: 14.8003
    - type: nauc_ndcg_at_10_diff1
      value: 68.3755
    - type: nauc_ndcg_at_20_max
      value: 56.2808
    - type: nauc_ndcg_at_20_std
      value: 16.0875
    - type: nauc_ndcg_at_20_diff1
      value: 68.3962
    - type: nauc_ndcg_at_100_max
      value: 56.3164
    - type: nauc_ndcg_at_100_std
      value: 15.8916
    - type: nauc_ndcg_at_100_diff1
      value: 69.00699999999999
    - type: nauc_ndcg_at_1000_max
      value: 55.785700000000006
    - type: nauc_ndcg_at_1000_std
      value: 14.3348
    - type: nauc_ndcg_at_1000_diff1
      value: 69.0698
    - type: nauc_map_at_1_max
      value: 51.8333
    - type: nauc_map_at_1_std
      value: 8.4163
    - type: nauc_map_at_1_diff1
      value: 72.37700000000001
    - type: nauc_map_at_3_max
      value: 54.942800000000005
    - type: nauc_map_at_3_std
      value: 11.2973
    - type: nauc_map_at_3_diff1
      value: 68.9311
    - type: nauc_map_at_5_max
      value: 55.0587
    - type: nauc_map_at_5_std
      value: 11.9547
    - type: nauc_map_at_5_diff1
      value: 69.3713
    - type: nauc_map_at_10_max
      value: 54.9098
    - type: nauc_map_at_10_std
      value: 12.2453
    - type: nauc_map_at_10_diff1
      value: 69.3958
    - type: nauc_map_at_20_max
      value: 54.9689
    - type: nauc_map_at_20_std
      value: 12.524799999999999
    - type: nauc_map_at_20_diff1
      value: 69.4109
    - type: nauc_map_at_100_max
      value: 54.9906
    - type: nauc_map_at_100_std
      value: 12.500300000000001
    - type: nauc_map_at_100_diff1
      value: 69.50319999999999
    - type: nauc_map_at_1000_max
      value: 54.97840000000001
    - type: nauc_map_at_1000_std
      value: 12.4639
    - type: nauc_map_at_1000_diff1
      value: 69.50460000000001
    - type: nauc_recall_at_1_max
      value: 51.8333
    - type: nauc_recall_at_1_std
      value: 8.4163
    - type: nauc_recall_at_1_diff1
      value: 72.37700000000001
    - type: nauc_recall_at_3_max
      value: 60.100699999999996
    - type: nauc_recall_at_3_std
      value: 17.4623
    - type: nauc_recall_at_3_diff1
      value: 62.495599999999996
    - type: nauc_recall_at_5_max
      value: 62.3622
    - type: nauc_recall_at_5_std
      value: 23.282700000000002
    - type: nauc_recall_at_5_diff1
      value: 63.8786
    - type: nauc_recall_at_10_max
      value: 61.567899999999995
    - type: nauc_recall_at_10_std
      value: 30.543300000000002
    - type: nauc_recall_at_10_diff1
      value: 62.765800000000006
    - type: nauc_recall_at_20_max
      value: 65.8648
    - type: nauc_recall_at_20_std
      value: 45.2891
    - type: nauc_recall_at_20_diff1
      value: 61.5048
    - type: nauc_recall_at_100_max
      value: 77.73790000000001
    - type: nauc_recall_at_100_std
      value: 78.3004
    - type: nauc_recall_at_100_diff1
      value: 66.54820000000001
    - type: nauc_recall_at_1000_max
      value: .nan
    - type: nauc_recall_at_1000_std
      value: .nan
    - type: nauc_recall_at_1000_diff1
      value: .nan
    - type: nauc_precision_at_1_max
      value: 51.8333
    - type: nauc_precision_at_1_std
      value: 8.4163
    - type: nauc_precision_at_1_diff1
      value: 72.37700000000001
    - type: nauc_precision_at_3_max
      value: 60.100699999999996
    - type: nauc_precision_at_3_std
      value: 17.4623
    - type: nauc_precision_at_3_diff1
      value: 62.495599999999996
    - type: nauc_precision_at_5_max
      value: 62.3622
    - type: nauc_precision_at_5_std
      value: 23.282700000000002
    - type: nauc_precision_at_5_diff1
      value: 63.8786
    - type: nauc_precision_at_10_max
      value: 61.567899999999995
    - type: nauc_precision_at_10_std
      value: 30.543300000000002
    - type: nauc_precision_at_10_diff1
      value: 62.765800000000006
    - type: nauc_precision_at_20_max
      value: 65.8648
    - type: nauc_precision_at_20_std
      value: 45.2891
    - type: nauc_precision_at_20_diff1
      value: 61.5048
    - type: nauc_precision_at_100_max
      value: 77.73790000000001
    - type: nauc_precision_at_100_std
      value: 78.3004
    - type: nauc_precision_at_100_diff1
      value: 66.54820000000001
    - type: nauc_precision_at_1000_max
      value: .nan
    - type: nauc_precision_at_1000_std
      value: .nan
    - type: nauc_precision_at_1000_diff1
      value: .nan
    - type: nauc_mrr_at_1_max
      value: 51.8333
    - type: nauc_mrr_at_1_std
      value: 8.4163
    - type: nauc_mrr_at_1_diff1
      value: 72.37700000000001
    - type: nauc_mrr_at_3_max
      value: 54.942800000000005
    - type: nauc_mrr_at_3_std
      value: 11.2973
    - type: nauc_mrr_at_3_diff1
      value: 68.9311
    - type: nauc_mrr_at_5_max
      value: 55.0587
    - type: nauc_mrr_at_5_std
      value: 11.9547
    - type: nauc_mrr_at_5_diff1
      value: 69.3713
    - type: nauc_mrr_at_10_max
      value: 54.9098
    - type: nauc_mrr_at_10_std
      value: 12.2453
    - type: nauc_mrr_at_10_diff1
      value: 69.3958
    - type: nauc_mrr_at_20_max
      value: 54.9689
    - type: nauc_mrr_at_20_std
      value: 12.524799999999999
    - type: nauc_mrr_at_20_diff1
      value: 69.4109
    - type: nauc_mrr_at_100_max
      value: 54.9906
    - type: nauc_mrr_at_100_std
      value: 12.500300000000001
    - type: nauc_mrr_at_100_diff1
      value: 69.50319999999999
    - type: nauc_mrr_at_1000_max
      value: 54.97840000000001
    - type: nauc_mrr_at_1000_std
      value: 12.4639
    - type: nauc_mrr_at_1000_diff1
      value: 69.50460000000001
    - type: main_score
      value: 75.274
    task:
      type: Retrieval
  - dataset:
      config: java
      name: MTEB CodeSearchNetRetrieval (java)
      revision: fdc6a9e39575768c27eb8a2a5f702bf846eb4759
      split: test
      type: code-search-net/code_search_net
    metrics:
    - type: ndcg_at_1
      value: 52.6
    - type: ndcg_at_3
      value: 64.044
    - type: ndcg_at_5
      value: 67.202
    - type: ndcg_at_10
      value: 69.447
    - type: ndcg_at_20
      value: 70.488
    - type: ndcg_at_100
      value: 71.481
    - type: ndcg_at_1000
      value: 71.995
    - type: map_at_1
      value: 52.6
    - type: map_at_3
      value: 61.317
    - type: map_at_5
      value: 63.062
    - type: map_at_10
      value: 64.01400000000001
    - type: map_at_20
      value: 64.302
    - type: map_at_100
      value: 64.443
    - type: map_at_1000
      value: 64.459
    - type: recall_at_1
      value: 52.6
    - type: recall_at_3
      value: 71.89999999999999
    - type: recall_at_5
      value: 79.60000000000001
    - type: recall_at_10
      value: 86.4
    - type: recall_at_20
      value: 90.5
    - type: recall_at_100
      value: 95.8
    - type: recall_at_1000
      value: 100.0
    - type: precision_at_1
      value: 52.6
    - type: precision_at_3
      value: 23.967
    - type: precision_at_5
      value: 15.920000000000002
    - type: precision_at_10
      value: 8.64
    - type: precision_at_20
      value: 4.5249999999999995
    - type: precision_at_100
      value: 0.958
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 52.6
    - type: mrr_at_3
      value: 61.316700000000004
    - type: mrr_at_5
      value: 63.0617
    - type: mrr_at_10
      value: 64.01400000000001
    - type: mrr_at_20
      value: 64.3022
    - type: mrr_at_100
      value: 64.443
    - type: mrr_at_1000
      value: 64.4595
    - type: nauc_ndcg_at_1_max
      value: 38.4317
    - type: nauc_ndcg_at_1_std
      value: -18.9677
    - type: nauc_ndcg_at_1_diff1
      value: 62.74570000000001
    - type: nauc_ndcg_at_3_max
      value: 43.612
    - type: nauc_ndcg_at_3_std
      value: -14.6587
    - type: nauc_ndcg_at_3_diff1
      value: 56.92230000000001
    - type: nauc_ndcg_at_5_max
      value: 44.840999999999994
    - type: nauc_ndcg_at_5_std
      value: -12.328600000000002
    - type: nauc_ndcg_at_5_diff1
      value: 56.998000000000005
    - type: nauc_ndcg_at_10_max
      value: 45.5768
    - type: nauc_ndcg_at_10_std
      value: -10.871
    - type: nauc_ndcg_at_10_diff1
      value: 57.36130000000001
    - type: nauc_ndcg_at_20_max
      value: 45.1125
    - type: nauc_ndcg_at_20_std
      value: -10.575
    - type: nauc_ndcg_at_20_diff1
      value: 57.2132
    - type: nauc_ndcg_at_100_max
      value: 45.4087
    - type: nauc_ndcg_at_100_std
      value: -10.356300000000001
    - type: nauc_ndcg_at_100_diff1
      value: 57.607
    - type: nauc_ndcg_at_1000_max
      value: 44.2686
    - type: nauc_ndcg_at_1000_std
      value: -12.2661
    - type: nauc_ndcg_at_1000_diff1
      value: 58.0082
    - type: nauc_map_at_1_max
      value: 38.4317
    - type: nauc_map_at_1_std
      value: -18.9677
    - type: nauc_map_at_1_diff1
      value: 62.74570000000001
    - type: nauc_map_at_3_max
      value: 42.278
    - type: nauc_map_at_3_std
      value: -15.937499999999998
    - type: nauc_map_at_3_diff1
      value: 58.4671
    - type: nauc_map_at_5_max
      value: 42.8414
    - type: nauc_map_at_5_std
      value: -14.7742
    - type: nauc_map_at_5_diff1
      value: 58.582100000000004
    - type: nauc_map_at_10_max
      value: 43.0236
    - type: nauc_map_at_10_std
      value: -14.3595
    - type: nauc_map_at_10_diff1
      value: 58.765100000000004
    - type: nauc_map_at_20_max
      value: 42.8918
    - type: nauc_map_at_20_std
      value: -14.335500000000001
    - type: nauc_map_at_20_diff1
      value: 58.746500000000005
    - type: nauc_map_at_100_max
      value: 42.9383
    - type: nauc_map_at_100_std
      value: -14.296600000000002
    - type: nauc_map_at_100_diff1
      value: 58.796099999999996
    - type: nauc_map_at_1000_max
      value: 42.9079
    - type: nauc_map_at_1000_std
      value: -14.3452
    - type: nauc_map_at_1000_diff1
      value: 58.8048
    - type: nauc_recall_at_1_max
      value: 38.4317
    - type: nauc_recall_at_1_std
      value: -18.9677
    - type: nauc_recall_at_1_diff1
      value: 62.74570000000001
    - type: nauc_recall_at_3_max
      value: 48.255199999999995
    - type: nauc_recall_at_3_std
      value: -10.116999999999999
    - type: nauc_recall_at_3_diff1
      value: 51.5211
    - type: nauc_recall_at_5_max
      value: 53.7581
    - type: nauc_recall_at_5_std
      value: -1.1828
    - type: nauc_recall_at_5_diff1
      value: 50.139199999999995
    - type: nauc_recall_at_10_max
      value: 62.2138
    - type: nauc_recall_at_10_std
      value: 12.5761
    - type: nauc_recall_at_10_diff1
      value: 49.091499999999996
    - type: nauc_recall_at_20_max
      value: 64.05619999999999
    - type: nauc_recall_at_20_std
      value: 24.6892
    - type: nauc_recall_at_20_diff1
      value: 44.4292
    - type: nauc_recall_at_100_max
      value: 94.1543
    - type: nauc_recall_at_100_std
      value: 72.2889
    - type: nauc_recall_at_100_diff1
      value: 39.8115
    - type: nauc_recall_at_1000_max
      value: .nan
    - type: nauc_recall_at_1000_std
      value: .nan
    - type: nauc_recall_at_1000_diff1
      value: .nan
    - type: nauc_precision_at_1_max
      value: 38.4317
    - type: nauc_precision_at_1_std
      value: -18.9677
    - type: nauc_precision_at_1_diff1
      value: 62.74570000000001
    - type: nauc_precision_at_3_max
      value: 48.255199999999995
    - type: nauc_precision_at_3_std
      value: -10.116999999999999
    - type: nauc_precision_at_3_diff1
      value: 51.5211
    - type: nauc_precision_at_5_max
      value: 53.7581
    - type: nauc_precision_at_5_std
      value: -1.1828
    - type: nauc_precision_at_5_diff1
      value: 50.139199999999995
    - type: nauc_precision_at_10_max
      value: 62.2138
    - type: nauc_precision_at_10_std
      value: 12.5761
    - type: nauc_precision_at_10_diff1
      value: 49.091499999999996
    - type: nauc_precision_at_20_max
      value: 64.05619999999999
    - type: nauc_precision_at_20_std
      value: 24.6892
    - type: nauc_precision_at_20_diff1
      value: 44.4292
    - type: nauc_precision_at_100_max
      value: 94.1543
    - type: nauc_precision_at_100_std
      value: 72.2889
    - type: nauc_precision_at_100_diff1
      value: 39.8115
    - type: nauc_precision_at_1000_max
      value: .nan
    - type: nauc_precision_at_1000_std
      value: .nan
    - type: nauc_precision_at_1000_diff1
      value: .nan
    - type: nauc_mrr_at_1_max
      value: 38.4317
    - type: nauc_mrr_at_1_std
      value: -18.9677
    - type: nauc_mrr_at_1_diff1
      value: 62.74570000000001
    - type: nauc_mrr_at_3_max
      value: 42.278
    - type: nauc_mrr_at_3_std
      value: -15.937499999999998
    - type: nauc_mrr_at_3_diff1
      value: 58.4671
    - type: nauc_mrr_at_5_max
      value: 42.8414
    - type: nauc_mrr_at_5_std
      value: -14.7742
    - type: nauc_mrr_at_5_diff1
      value: 58.582100000000004
    - type: nauc_mrr_at_10_max
      value: 43.0236
    - type: nauc_mrr_at_10_std
      value: -14.3595
    - type: nauc_mrr_at_10_diff1
      value: 58.765100000000004
    - type: nauc_mrr_at_20_max
      value: 42.8918
    - type: nauc_mrr_at_20_std
      value: -14.335500000000001
    - type: nauc_mrr_at_20_diff1
      value: 58.746500000000005
    - type: nauc_mrr_at_100_max
      value: 42.9383
    - type: nauc_mrr_at_100_std
      value: -14.296600000000002
    - type: nauc_mrr_at_100_diff1
      value: 58.796099999999996
    - type: nauc_mrr_at_1000_max
      value: 42.9079
    - type: nauc_mrr_at_1000_std
      value: -14.3452
    - type: nauc_mrr_at_1000_diff1
      value: 58.8048
    - type: main_score
      value: 69.447
    task:
      type: Retrieval
  - dataset:
      config: php
      name: MTEB CodeSearchNetRetrieval (php)
      revision: fdc6a9e39575768c27eb8a2a5f702bf846eb4759
      split: test
      type: code-search-net/code_search_net
    metrics:
    - type: ndcg_at_1
      value: 57.699999999999996
    - type: ndcg_at_3
      value: 69.071
    - type: ndcg_at_5
      value: 71.331
    - type: ndcg_at_10
      value: 73.455
    - type: ndcg_at_20
      value: 74.298
    - type: ndcg_at_100
      value: 74.842
    - type: ndcg_at_1000
      value: 75.411
    - type: map_at_1
      value: 57.699999999999996
    - type: map_at_3
      value: 66.233
    - type: map_at_5
      value: 67.508
    - type: map_at_10
      value: 68.398
    - type: map_at_20
      value: 68.634
    - type: map_at_100
      value: 68.718
    - type: map_at_1000
      value: 68.735
    - type: recall_at_1
      value: 57.699999999999996
    - type: recall_at_3
      value: 77.3
    - type: recall_at_5
      value: 82.69999999999999
    - type: recall_at_10
      value: 89.2
    - type: recall_at_20
      value: 92.5
    - type: recall_at_100
      value: 95.3
    - type: recall_at_1000
      value: 100.0
    - type: precision_at_1
      value: 57.699999999999996
    - type: precision_at_3
      value: 25.767
    - type: precision_at_5
      value: 16.54
    - type: precision_at_10
      value: 8.92
    - type: precision_at_20
      value: 4.625
    - type: precision_at_100
      value: 0.9530000000000001
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 57.699999999999996
    - type: mrr_at_3
      value: 66.2333
    - type: mrr_at_5
      value: 67.5083
    - type: mrr_at_10
      value: 68.398
    - type: mrr_at_20
      value: 68.6345
    - type: mrr_at_100
      value: 68.71770000000001
    - type: mrr_at_1000
      value: 68.7351
    - type: nauc_ndcg_at_1_max
      value: 47.0017
    - type: nauc_ndcg_at_1_std
      value: 7.702000000000001
    - type: nauc_ndcg_at_1_diff1
      value: 65.5265
    - type: nauc_ndcg_at_3_max
      value: 53.1223
    - type: nauc_ndcg_at_3_std
      value: 14.5277
    - type: nauc_ndcg_at_3_diff1
      value: 60.5267
    - type: nauc_ndcg_at_5_max
      value: 55.99570000000001
    - type: nauc_ndcg_at_5_std
      value: 17.467
    - type: nauc_ndcg_at_5_diff1
      value: 63.1188
    - type: nauc_ndcg_at_10_max
      value: 55.7826
    - type: nauc_ndcg_at_10_std
      value: 19.1279
    - type: nauc_ndcg_at_10_diff1
      value: 63.463
    - type: nauc_ndcg_at_20_max
      value: 55.2338
    - type: nauc_ndcg_at_20_std
      value: 19.5684
    - type: nauc_ndcg_at_20_diff1
      value: 63.7312
    - type: nauc_ndcg_at_100_max
      value: 54.898199999999996
    - type: nauc_ndcg_at_100_std
      value: 19.1172
    - type: nauc_ndcg_at_100_diff1
      value: 63.7935
    - type: nauc_ndcg_at_1000_max
      value: 53.9486
    - type: nauc_ndcg_at_1000_std
      value: 17.0841
    - type: nauc_ndcg_at_1000_diff1
      value: 63.5189
    - type: nauc_map_at_1_max
      value: 47.0017
    - type: nauc_map_at_1_std
      value: 7.702000000000001
    - type: nauc_map_at_1_diff1
      value: 65.5265
    - type: nauc_map_at_3_max
      value: 51.3811
    - type: nauc_map_at_3_std
      value: 12.6201
    - type: nauc_map_at_3_diff1
      value: 61.781299999999995
    - type: nauc_map_at_5_max
      value: 52.788599999999995
    - type: nauc_map_at_5_std
      value: 13.9926
    - type: nauc_map_at_5_diff1
      value: 63.155300000000004
    - type: nauc_map_at_10_max
      value: 52.630900000000004
    - type: nauc_map_at_10_std
      value: 14.5419
    - type: nauc_map_at_10_diff1
      value: 63.299499999999995
    - type: nauc_map_at_20_max
      value: 52.4779
    - type: nauc_map_at_20_std
      value: 14.615300000000001
    - type: nauc_map_at_20_diff1
      value: 63.360099999999996
    - type: nauc_map_at_100_max
      value: 52.434999999999995
    - type: nauc_map_at_100_std
      value: 14.5613
    - type: nauc_map_at_100_diff1
      value: 63.362700000000004
    - type: nauc_map_at_1000_max
      value: 52.412000000000006
    - type: nauc_map_at_1000_std
      value: 14.5121
    - type: nauc_map_at_1000_diff1
      value: 63.361000000000004
    - type: nauc_recall_at_1_max
      value: 47.0017
    - type: nauc_recall_at_1_std
      value: 7.702000000000001
    - type: nauc_recall_at_1_diff1
      value: 65.5265
    - type: nauc_recall_at_3_max
      value: 59.7842
    - type: nauc_recall_at_3_std
      value: 21.8077
    - type: nauc_recall_at_3_diff1
      value: 55.81850000000001
    - type: nauc_recall_at_5_max
      value: 71.5097
    - type: nauc_recall_at_5_std
      value: 34.341899999999995
    - type: nauc_recall_at_5_diff1
      value: 63.604000000000006
    - type: nauc_recall_at_10_max
      value: 78.1568
    - type: nauc_recall_at_10_std
      value: 53.016600000000004
    - type: nauc_recall_at_10_diff1
      value: 65.779
    - type: nauc_recall_at_20_max
      value: 81.5145
    - type: nauc_recall_at_20_std
      value: 72.038
    - type: nauc_recall_at_20_diff1
      value: 69.7603
    - type: nauc_recall_at_100_max
      value: 89.0587
    - type: nauc_recall_at_100_std
      value: 91.89070000000001
    - type: nauc_recall_at_100_diff1
      value: 75.1088
    - type: nauc_recall_at_1000_max
      value: .nan
    - type: nauc_recall_at_1000_std
      value: .nan
    - type: nauc_recall_at_1000_diff1
      value: .nan
    - type: nauc_precision_at_1_max
      value: 47.0017
    - type: nauc_precision_at_1_std
      value: 7.702000000000001
    - type: nauc_precision_at_1_diff1
      value: 65.5265
    - type: nauc_precision_at_3_max
      value: 59.7842
    - type: nauc_precision_at_3_std
      value: 21.8077
    - type: nauc_precision_at_3_diff1
      value: 55.81850000000001
    - type: nauc_precision_at_5_max
      value: 71.5097
    - type: nauc_precision_at_5_std
      value: 34.341899999999995
    - type: nauc_precision_at_5_diff1
      value: 63.604000000000006
    - type: nauc_precision_at_10_max
      value: 78.1568
    - type: nauc_precision_at_10_std
      value: 53.016600000000004
    - type: nauc_precision_at_10_diff1
      value: 65.779
    - type: nauc_precision_at_20_max
      value: 81.5145
    - type: nauc_precision_at_20_std
      value: 72.038
    - type: nauc_precision_at_20_diff1
      value: 69.7603
    - type: nauc_precision_at_100_max
      value: 89.0587
    - type: nauc_precision_at_100_std
      value: 91.89070000000001
    - type: nauc_precision_at_100_diff1
      value: 75.1088
    - type: nauc_precision_at_1000_max
      value: .nan
    - type: nauc_precision_at_1000_std
      value: .nan
    - type: nauc_precision_at_1000_diff1
      value: .nan
    - type: nauc_mrr_at_1_max
      value: 47.0017
    - type: nauc_mrr_at_1_std
      value: 7.702000000000001
    - type: nauc_mrr_at_1_diff1
      value: 65.5265
    - type: nauc_mrr_at_3_max
      value: 51.3811
    - type: nauc_mrr_at_3_std
      value: 12.6201
    - type: nauc_mrr_at_3_diff1
      value: 61.781299999999995
    - type: nauc_mrr_at_5_max
      value: 52.788599999999995
    - type: nauc_mrr_at_5_std
      value: 13.9926
    - type: nauc_mrr_at_5_diff1
      value: 63.155300000000004
    - type: nauc_mrr_at_10_max
      value: 52.630900000000004
    - type: nauc_mrr_at_10_std
      value: 14.5419
    - type: nauc_mrr_at_10_diff1
      value: 63.299499999999995
    - type: nauc_mrr_at_20_max
      value: 52.4779
    - type: nauc_mrr_at_20_std
      value: 14.615300000000001
    - type: nauc_mrr_at_20_diff1
      value: 63.360099999999996
    - type: nauc_mrr_at_100_max
      value: 52.434999999999995
    - type: nauc_mrr_at_100_std
      value: 14.5613
    - type: nauc_mrr_at_100_diff1
      value: 63.362700000000004
    - type: nauc_mrr_at_1000_max
      value: 52.412000000000006
    - type: nauc_mrr_at_1000_std
      value: 14.5121
    - type: nauc_mrr_at_1000_diff1
      value: 63.361000000000004
    - type: main_score
      value: 73.455
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CodeTransOceanContest (default)
      revision: 20da4eb20a4b17300c0986ee148c90867a7f2a4d
      split: test
      type: CoIR-Retrieval/codetrans-contest
    metrics:
    - type: ndcg_at_1
      value: 46.154
    - type: ndcg_at_3
      value: 52.019999999999996
    - type: ndcg_at_5
      value: 53.929
    - type: ndcg_at_10
      value: 57.475
    - type: ndcg_at_20
      value: 59.861
    - type: ndcg_at_100
      value: 61.577000000000005
    - type: ndcg_at_1000
      value: 62.755
    - type: map_at_1
      value: 46.154
    - type: map_at_3
      value: 50.602999999999994
    - type: map_at_5
      value: 51.68899999999999
    - type: map_at_10
      value: 53.174
    - type: map_at_20
      value: 53.818
    - type: map_at_100
      value: 54.041
    - type: map_at_1000
      value: 54.081
    - type: recall_at_1
      value: 46.154
    - type: recall_at_3
      value: 56.108999999999995
    - type: recall_at_5
      value: 60.633
    - type: recall_at_10
      value: 71.493
    - type: recall_at_20
      value: 80.99499999999999
    - type: recall_at_100
      value: 90.498
    - type: recall_at_1000
      value: 100.0
    - type: precision_at_1
      value: 46.154
    - type: precision_at_3
      value: 18.703
    - type: precision_at_5
      value: 12.127
    - type: precision_at_10
      value: 7.149
    - type: precision_at_20
      value: 4.05
    - type: precision_at_100
      value: 0.905
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 46.153800000000004
    - type: mrr_at_3
      value: 50.6033
    - type: mrr_at_5
      value: 51.6893
    - type: mrr_at_10
      value: 53.173899999999996
    - type: mrr_at_20
      value: 53.8181
    - type: mrr_at_100
      value: 54.0405
    - type: mrr_at_1000
      value: 54.081199999999995
    - type: nauc_ndcg_at_1_max
      value: 59.032
    - type: nauc_ndcg_at_1_std
      value: 8.2815
    - type: nauc_ndcg_at_1_diff1
      value: 80.5428
    - type: nauc_ndcg_at_3_max
      value: 55.47410000000001
    - type: nauc_ndcg_at_3_std
      value: 4.4284
    - type: nauc_ndcg_at_3_diff1
      value: 77.2405
    - type: nauc_ndcg_at_5_max
      value: 54.6337
    - type: nauc_ndcg_at_5_std
      value: 5.3048
    - type: nauc_ndcg_at_5_diff1
      value: 76.5969
    - type: nauc_ndcg_at_10_max
      value: 51.8584
    - type: nauc_ndcg_at_10_std
      value: 3.5628
    - type: nauc_ndcg_at_10_diff1
      value: 74.6966
    - type: nauc_ndcg_at_20_max
      value: 54.3478
    - type: nauc_ndcg_at_20_std
      value: 4.3697
    - type: nauc_ndcg_at_20_diff1
      value: 75.6032
    - type: nauc_ndcg_at_100_max
      value: 55.488400000000006
    - type: nauc_ndcg_at_100_std
      value: 6.101
    - type: nauc_ndcg_at_100_diff1
      value: 76.0249
    - type: nauc_ndcg_at_1000_max
      value: 55.1091
    - type: nauc_ndcg_at_1000_std
      value: 5.5951
    - type: nauc_ndcg_at_1000_diff1
      value: 76.3907
    - type: nauc_map_at_1_max
      value: 59.032
    - type: nauc_map_at_1_std
      value: 8.2815
    - type: nauc_map_at_1_diff1
      value: 80.5428
    - type: nauc_map_at_3_max
      value: 56.261700000000005
    - type: nauc_map_at_3_std
      value: 5.3123
    - type: nauc_map_at_3_diff1
      value: 77.823
    - type: nauc_map_at_5_max
      value: 55.7926
    - type: nauc_map_at_5_std
      value: 5.8055
    - type: nauc_map_at_5_diff1
      value: 77.4779
    - type: nauc_map_at_10_max
      value: 54.77459999999999
    - type: nauc_map_at_10_std
      value: 5.1733
    - type: nauc_map_at_10_diff1
      value: 76.79249999999999
    - type: nauc_map_at_20_max
      value: 55.4426
    - type: nauc_map_at_20_std
      value: 5.4346
    - type: nauc_map_at_20_diff1
      value: 77.0378
    - type: nauc_map_at_100_max
      value: 55.6049
    - type: nauc_map_at_100_std
      value: 5.7131
    - type: nauc_map_at_100_diff1
      value: 77.0756
    - type: nauc_map_at_1000_max
      value: 55.5915
    - type: nauc_map_at_1000_std
      value: 5.7007
    - type: nauc_map_at_1000_diff1
      value: 77.0939
    - type: nauc_recall_at_1_max
      value: 59.032
    - type: nauc_recall_at_1_std
      value: 8.2815
    - type: nauc_recall_at_1_diff1
      value: 80.5428
    - type: nauc_recall_at_3_max
      value: 53.1398
    - type: nauc_recall_at_3_std
      value: 1.7934999999999999
    - type: nauc_recall_at_3_diff1
      value: 75.5862
    - type: nauc_recall_at_5_max
      value: 50.9304
    - type: nauc_recall_at_5_std
      value: 3.8924
    - type: nauc_recall_at_5_diff1
      value: 73.8369
    - type: nauc_recall_at_10_max
      value: 38.9905
    - type: nauc_recall_at_10_std
      value: -3.4564999999999997
    - type: nauc_recall_at_10_diff1
      value: 65.5567
    - type: nauc_recall_at_20_max
      value: 50.0429
    - type: nauc_recall_at_20_std
      value: -1.4551
    - type: nauc_recall_at_20_diff1
      value: 67.9871
    - type: nauc_recall_at_100_max
      value: 63.44030000000001
    - type: nauc_recall_at_100_std
      value: 17.8876
    - type: nauc_recall_at_100_diff1
      value: 68.9388
    - type: nauc_recall_at_1000_max
      value: .nan
    - type: nauc_recall_at_1000_std
      value: .nan
    - type: nauc_recall_at_1000_diff1
      value: .nan
    - type: nauc_precision_at_1_max
      value: 59.032
    - type: nauc_precision_at_1_std
      value: 8.2815
    - type: nauc_precision_at_1_diff1
      value: 80.5428
    - type: nauc_precision_at_3_max
      value: 53.1398
    - type: nauc_precision_at_3_std
      value: 1.7934999999999999
    - type: nauc_precision_at_3_diff1
      value: 75.5862
    - type: nauc_precision_at_5_max
      value: 50.9304
    - type: nauc_precision_at_5_std
      value: 3.8924
    - type: nauc_precision_at_5_diff1
      value: 73.8369
    - type: nauc_precision_at_10_max
      value: 38.9905
    - type: nauc_precision_at_10_std
      value: -3.4564999999999997
    - type: nauc_precision_at_10_diff1
      value: 65.5567
    - type: nauc_precision_at_20_max
      value: 50.0429
    - type: nauc_precision_at_20_std
      value: -1.4551
    - type: nauc_precision_at_20_diff1
      value: 67.9871
    - type: nauc_precision_at_100_max
      value: 63.44030000000001
    - type: nauc_precision_at_100_std
      value: 17.8876
    - type: nauc_precision_at_100_diff1
      value: 68.9388
    - type: nauc_precision_at_1000_max
      value: 100.0
    - type: nauc_precision_at_1000_std
      value: 100.0
    - type: nauc_precision_at_1000_diff1
      value: 100.0
    - type: nauc_mrr_at_1_max
      value: 59.032
    - type: nauc_mrr_at_1_std
      value: 8.2815
    - type: nauc_mrr_at_1_diff1
      value: 80.5428
    - type: nauc_mrr_at_3_max
      value: 56.261700000000005
    - type: nauc_mrr_at_3_std
      value: 5.3123
    - type: nauc_mrr_at_3_diff1
      value: 77.823
    - type: nauc_mrr_at_5_max
      value: 55.7926
    - type: nauc_mrr_at_5_std
      value: 5.8055
    - type: nauc_mrr_at_5_diff1
      value: 77.4779
    - type: nauc_mrr_at_10_max
      value: 54.77459999999999
    - type: nauc_mrr_at_10_std
      value: 5.1733
    - type: nauc_mrr_at_10_diff1
      value: 76.79249999999999
    - type: nauc_mrr_at_20_max
      value: 55.4426
    - type: nauc_mrr_at_20_std
      value: 5.4346
    - type: nauc_mrr_at_20_diff1
      value: 77.0378
    - type: nauc_mrr_at_100_max
      value: 55.6049
    - type: nauc_mrr_at_100_std
      value: 5.7131
    - type: nauc_mrr_at_100_diff1
      value: 77.0756
    - type: nauc_mrr_at_1000_max
      value: 55.5915
    - type: nauc_mrr_at_1000_std
      value: 5.7007
    - type: nauc_mrr_at_1000_diff1
      value: 77.0939
    - type: main_score
      value: 57.475
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CodeTransOceanDL (default)
      revision: 281562cb8a1265ab5c0824bfa6ddcd9b0a15618f
      split: test
      type: CoIR-Retrieval/codetrans-dl
    metrics:
    - type: ndcg_at_1
      value: 8.889
    - type: ndcg_at_3
      value: 10.700999999999999
    - type: ndcg_at_5
      value: 16.082
    - type: ndcg_at_10
      value: 26.888
    - type: ndcg_at_20
      value: 35.608000000000004
    - type: ndcg_at_100
      value: 36.459
    - type: ndcg_at_1000
      value: 36.775999999999996
    - type: map_at_1
      value: 8.889
    - type: map_at_3
      value: 10.184999999999999
    - type: map_at_5
      value: 13.241
    - type: map_at_10
      value: 17.502000000000002
    - type: map_at_20
      value: 19.978
    - type: map_at_100
      value: 20.108
    - type: map_at_1000
      value: 20.125
    - type: recall_at_1
      value: 8.889
    - type: recall_at_3
      value: 12.222
    - type: recall_at_5
      value: 25.0
    - type: recall_at_10
      value: 59.443999999999996
    - type: recall_at_20
      value: 93.333
    - type: recall_at_100
      value: 97.77799999999999
    - type: recall_at_1000
      value: 100.0
    - type: precision_at_1
      value: 8.889
    - type: precision_at_3
      value: 4.074
    - type: precision_at_5
      value: 5.0
    - type: precision_at_10
      value: 5.944
    - type: precision_at_20
      value: 4.667000000000001
    - type: precision_at_100
      value: 0.9780000000000001
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 3.8889
    - type: mrr_at_3
      value: 8.9815
    - type: mrr_at_5
      value: 10.2593
    - type: mrr_at_10
      value: 15.263399999999999
    - type: mrr_at_20
      value: 17.711
    - type: mrr_at_100
      value: 17.8421
    - type: mrr_at_1000
      value: 17.8596
    - type: nauc_ndcg_at_1_max
      value: -40.8791
    - type: nauc_ndcg_at_1_std
      value: -22.7629
    - type: nauc_ndcg_at_1_diff1
      value: -23.105
    - type: nauc_ndcg_at_3_max
      value: -43.187599999999996
    - type: nauc_ndcg_at_3_std
      value: -26.9994
    - type: nauc_ndcg_at_3_diff1
      value: -15.4181
    - type: nauc_ndcg_at_5_max
      value: -37.2549
    - type: nauc_ndcg_at_5_std
      value: -24.4115
    - type: nauc_ndcg_at_5_diff1
      value: -5.7322999999999995
    - type: nauc_ndcg_at_10_max
      value: -36.3471
    - type: nauc_ndcg_at_10_std
      value: -22.8065
    - type: nauc_ndcg_at_10_diff1
      value: -5.3767000000000005
    - type: nauc_ndcg_at_20_max
      value: -35.829100000000004
    - type: nauc_ndcg_at_20_std
      value: -20.787300000000002
    - type: nauc_ndcg_at_20_diff1
      value: -9.6038
    - type: nauc_ndcg_at_100_max
      value: -36.5805
    - type: nauc_ndcg_at_100_std
      value: -20.1283
    - type: nauc_ndcg_at_100_diff1
      value: -8.9448
    - type: nauc_ndcg_at_1000_max
      value: -38.1158
    - type: nauc_ndcg_at_1000_std
      value: -22.2744
    - type: nauc_ndcg_at_1000_diff1
      value: -9.8704
    - type: nauc_map_at_1_max
      value: -40.8791
    - type: nauc_map_at_1_std
      value: -22.7629
    - type: nauc_map_at_1_diff1
      value: -23.105
    - type: nauc_map_at_3_max
      value: -42.559200000000004
    - type: nauc_map_at_3_std
      value: -25.8594
    - type: nauc_map_at_3_diff1
      value: -17.2362
    - type: nauc_map_at_5_max
      value: -38.595800000000004
    - type: nauc_map_at_5_std
      value: -24.1339
    - type: nauc_map_at_5_diff1
      value: -10.4452
    - type: nauc_map_at_10_max
      value: -38.2389
    - type: nauc_map_at_10_std
      value: -23.453599999999998
    - type: nauc_map_at_10_diff1
      value: -10.2748
    - type: nauc_map_at_20_max
      value: -38.8856
    - type: nauc_map_at_20_std
      value: -23.095499999999998
    - type: nauc_map_at_20_diff1
      value: -11.695500000000001
    - type: nauc_map_at_100_max
      value: -38.9696
    - type: nauc_map_at_100_std
      value: -23.0057
    - type: nauc_map_at_100_diff1
      value: -11.635900000000001
    - type: nauc_map_at_1000_max
      value: -39.035399999999996
    - type: nauc_map_at_1000_std
      value: -23.1075
    - type: nauc_map_at_1000_diff1
      value: -11.6855
    - type: nauc_recall_at_1_max
      value: -40.8791
    - type: nauc_recall_at_1_std
      value: -22.7629
    - type: nauc_recall_at_1_diff1
      value: -23.105
    - type: nauc_recall_at_3_max
      value: -44.8047
    - type: nauc_recall_at_3_std
      value: -29.9296
    - type: nauc_recall_at_3_diff1
      value: -10.8169
    - type: nauc_recall_at_5_max
      value: -34.5699
    - type: nauc_recall_at_5_std
      value: -24.9544
    - type: nauc_recall_at_5_diff1
      value: 3.4269000000000003
    - type: nauc_recall_at_10_max
      value: -32.149699999999996
    - type: nauc_recall_at_10_std
      value: -21.0142
    - type: nauc_recall_at_10_diff1
      value: 4.358
    - type: nauc_recall_at_20_max
      value: 0.7547
    - type: nauc_recall_at_20_std
      value: 7.1739999999999995
    - type: nauc_recall_at_20_diff1
      value: -3.2252
    - type: nauc_recall_at_100_max
      value: 41.4332
    - type: nauc_recall_at_100_std
      value: 86.1111
    - type: nauc_recall_at_100_diff1
      value: 35.7143
    - type: nauc_recall_at_1000_max
      value: .nan
    - type: nauc_recall_at_1000_std
      value: .nan
    - type: nauc_recall_at_1000_diff1
      value: .nan
    - type: nauc_precision_at_1_max
      value: -40.8791
    - type: nauc_precision_at_1_std
      value: -22.7629
    - type: nauc_precision_at_1_diff1
      value: -23.105
    - type: nauc_precision_at_3_max
      value: -44.8047
    - type: nauc_precision_at_3_std
      value: -29.9296
    - type: nauc_precision_at_3_diff1
      value: -10.8169
    - type: nauc_precision_at_5_max
      value: -34.5699
    - type: nauc_precision_at_5_std
      value: -24.9544
    - type: nauc_precision_at_5_diff1
      value: 3.4269000000000003
    - type: nauc_precision_at_10_max
      value: -32.149699999999996
    - type: nauc_precision_at_10_std
      value: -21.0142
    - type: nauc_precision_at_10_diff1
      value: 4.358
    - type: nauc_precision_at_20_max
      value: 0.7547
    - type: nauc_precision_at_20_std
      value: 7.1739999999999995
    - type: nauc_precision_at_20_diff1
      value: -3.2252
    - type: nauc_precision_at_100_max
      value: 41.4332
    - type: nauc_precision_at_100_std
      value: 86.1111
    - type: nauc_precision_at_100_diff1
      value: 35.7143
    - type: nauc_precision_at_1000_max
      value: 100.0
    - type: nauc_precision_at_1000_std
      value: 100.0
    - type: nauc_precision_at_1000_diff1
      value: 100.0
    - type: nauc_mrr_at_1_max
      value: -42.7345
    - type: nauc_mrr_at_1_std
      value: -35.9194
    - type: nauc_mrr_at_1_diff1
      value: -3.8369
    - type: nauc_mrr_at_3_max
      value: -35.497099999999996
    - type: nauc_mrr_at_3_std
      value: -28.1283
    - type: nauc_mrr_at_3_diff1
      value: 22.5336
    - type: nauc_mrr_at_5_max
      value: -34.9895
    - type: nauc_mrr_at_5_std
      value: -26.9499
    - type: nauc_mrr_at_5_diff1
      value: 16.9652
    - type: nauc_mrr_at_10_max
      value: -36.7778
    - type: nauc_mrr_at_10_std
      value: -28.069
    - type: nauc_mrr_at_10_diff1
      value: 18.806700000000003
    - type: nauc_mrr_at_20_max
      value: -36.2726
    - type: nauc_mrr_at_20_std
      value: -26.359500000000004
    - type: nauc_mrr_at_20_diff1
      value: 18.1655
    - type: nauc_mrr_at_100_max
      value: -36.361
    - type: nauc_mrr_at_100_std
      value: -26.280900000000003
    - type: nauc_mrr_at_100_diff1
      value: 18.5228
    - type: nauc_mrr_at_1000_max
      value: -36.4424
    - type: nauc_mrr_at_1000_std
      value: -26.415699999999998
    - type: nauc_mrr_at_1000_diff1
      value: 18.496499999999997
    - type: main_score
      value: 26.888
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB CosQA (default)
      revision: bc5efb7e9d437246ce393ed19d772e08e4a79535
      split: test
      type: CoIR-Retrieval/cosqa
    metrics:
    - type: ndcg_at_1
      value: 15.4
    - type: ndcg_at_3
      value: 23.59
    - type: ndcg_at_5
      value: 29.779
    - type: ndcg_at_10
      value: 35.449999999999996
    - type: ndcg_at_20
      value: 38.309
    - type: ndcg_at_100
      value: 41.980000000000004
    - type: ndcg_at_1000
      value: 42.917
    - type: map_at_1
      value: 15.4
    - type: map_at_3
      value: 21.4
    - type: map_at_5
      value: 24.84
    - type: map_at_10
      value: 27.245
    - type: map_at_20
      value: 28.043000000000003
    - type: map_at_100
      value: 28.592000000000002
    - type: map_at_1000
      value: 28.63
    - type: recall_at_1
      value: 15.4
    - type: recall_at_3
      value: 30.0
    - type: recall_at_5
      value: 45.0
    - type: recall_at_10
      value: 62.2
    - type: recall_at_20
      value: 73.4
    - type: recall_at_100
      value: 92.60000000000001
    - type: recall_at_1000
      value: 99.8
    - type: precision_at_1
      value: 15.4
    - type: precision_at_3
      value: 10.0
    - type: precision_at_5
      value: 9.0
    - type: precision_at_10
      value: 6.22
    - type: precision_at_20
      value: 3.6700000000000004
    - type: precision_at_100
      value: 0.9259999999999999
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 13.600000000000001
    - type: mrr_at_3
      value: 19.666700000000002
    - type: mrr_at_5
      value: 22.0867
    - type: mrr_at_10
      value: 25.020799999999998
    - type: mrr_at_20
      value: 25.8896
    - type: mrr_at_100
      value: 26.434400000000004
    - type: mrr_at_1000
      value: 26.4729
    - type: nauc_ndcg_at_1_max
      value: 7.9282
    - type: nauc_ndcg_at_1_std
      value: -14.053299999999998
    - type: nauc_ndcg_at_1_diff1
      value: 36.687799999999996
    - type: nauc_ndcg_at_3_max
      value: 11.969899999999999
    - type: nauc_ndcg_at_3_std
      value: -13.7404
    - type: nauc_ndcg_at_3_diff1
      value: 22.2386
    - type: nauc_ndcg_at_5_max
      value: 13.4812
    - type: nauc_ndcg_at_5_std
      value: -13.2079
    - type: nauc_ndcg_at_5_diff1
      value: 15.8384
    - type: nauc_ndcg_at_10_max
      value: 12.061399999999999
    - type: nauc_ndcg_at_10_std
      value: -15.1337
    - type: nauc_ndcg_at_10_diff1
      value: 18.804399999999998
    - type: nauc_ndcg_at_20_max
      value: 14.027000000000001
    - type: nauc_ndcg_at_20_std
      value: -13.123899999999999
    - type: nauc_ndcg_at_20_diff1
      value: 18.546499999999998
    - type: nauc_ndcg_at_100_max
      value: 15.4228
    - type: nauc_ndcg_at_100_std
      value: -9.7982
    - type: nauc_ndcg_at_100_diff1
      value: 20.637900000000002
    - type: nauc_ndcg_at_1000_max
      value: 13.3878
    - type: nauc_ndcg_at_1000_std
      value: -12.3766
    - type: nauc_ndcg_at_1000_diff1
      value: 21.2979
    - type: nauc_map_at_1_max
      value: 7.9282
    - type: nauc_map_at_1_std
      value: -14.053299999999998
    - type: nauc_map_at_1_diff1
      value: 36.687799999999996
    - type: nauc_map_at_3_max
      value: 11.2376
    - type: nauc_map_at_3_std
      value: -13.882800000000001
    - type: nauc_map_at_3_diff1
      value: 25.4638
    - type: nauc_map_at_5_max
      value: 12.0973
    - type: nauc_map_at_5_std
      value: -13.581399999999999
    - type: nauc_map_at_5_diff1
      value: 21.6642
    - type: nauc_map_at_10_max
      value: 11.4818
    - type: nauc_map_at_10_std
      value: -14.3841
    - type: nauc_map_at_10_diff1
      value: 23.0484
    - type: nauc_map_at_20_max
      value: 11.9802
    - type: nauc_map_at_20_std
      value: -13.8687
    - type: nauc_map_at_20_diff1
      value: 23.0349
    - type: nauc_map_at_100_max
      value: 12.112
    - type: nauc_map_at_100_std
      value: -13.423099999999998
    - type: nauc_map_at_100_diff1
      value: 23.385
    - type: nauc_map_at_1000_max
      value: 12.034
    - type: nauc_map_at_1000_std
      value: -13.5156
    - type: nauc_map_at_1000_diff1
      value: 23.4084
    - type: nauc_recall_at_1_max
      value: 7.9282
    - type: nauc_recall_at_1_std
      value: -14.053299999999998
    - type: nauc_recall_at_1_diff1
      value: 36.687799999999996
    - type: nauc_recall_at_3_max
      value: 13.6773
    - type: nauc_recall_at_3_std
      value: -13.376299999999999
    - type: nauc_recall_at_3_diff1
      value: 14.4918
    - type: nauc_recall_at_5_max
      value: 16.8852
    - type: nauc_recall_at_5_std
      value: -12.237499999999999
    - type: nauc_recall_at_5_diff1
      value: 1.4449
    - type: nauc_recall_at_10_max
      value: 13.234499999999999
    - type: nauc_recall_at_10_std
      value: -17.8241
    - type: nauc_recall_at_10_diff1
      value: 7.6404
    - type: nauc_recall_at_20_max
      value: 22.708000000000002
    - type: nauc_recall_at_20_std
      value: -9.111600000000001
    - type: nauc_recall_at_20_diff1
      value: 3.4109
    - type: nauc_recall_at_100_max
      value: 66.1165
    - type: nauc_recall_at_100_std
      value: 55.2477
    - type: nauc_recall_at_100_diff1
      value: 5.7612
    - type: nauc_recall_at_1000_max
      value: 100.0
    - type: nauc_recall_at_1000_std
      value: 86.9281
    - type: nauc_recall_at_1000_diff1
      value: 72.2222
    - type: nauc_precision_at_1_max
      value: 7.9282
    - type: nauc_precision_at_1_std
      value: -14.053299999999998
    - type: nauc_precision_at_1_diff1
      value: 36.687799999999996
    - type: nauc_precision_at_3_max
      value: 13.6773
    - type: nauc_precision_at_3_std
      value: -13.376299999999999
    - type: nauc_precision_at_3_diff1
      value: 14.4918
    - type: nauc_precision_at_5_max
      value: 16.8852
    - type: nauc_precision_at_5_std
      value: -12.237499999999999
    - type: nauc_precision_at_5_diff1
      value: 1.4449
    - type: nauc_precision_at_10_max
      value: 13.234499999999999
    - type: nauc_precision_at_10_std
      value: -17.8241
    - type: nauc_precision_at_10_diff1
      value: 7.6404
    - type: nauc_precision_at_20_max
      value: 22.708000000000002
    - type: nauc_precision_at_20_std
      value: -9.111600000000001
    - type: nauc_precision_at_20_diff1
      value: 3.4109
    - type: nauc_precision_at_100_max
      value: 66.1165
    - type: nauc_precision_at_100_std
      value: 55.2477
    - type: nauc_precision_at_100_diff1
      value: 5.7612
    - type: nauc_precision_at_1000_max
      value: 100.0
    - type: nauc_precision_at_1000_std
      value: 86.9281
    - type: nauc_precision_at_1000_diff1
      value: 72.2222
    - type: nauc_mrr_at_1_max
      value: 13.238199999999999
    - type: nauc_mrr_at_1_std
      value: -21.1942
    - type: nauc_mrr_at_1_diff1
      value: 47.1481
    - type: nauc_mrr_at_3_max
      value: 13.370999999999999
    - type: nauc_mrr_at_3_std
      value: -18.0171
    - type: nauc_mrr_at_3_diff1
      value: 31.3232
    - type: nauc_mrr_at_5_max
      value: 12.646099999999999
    - type: nauc_mrr_at_5_std
      value: -18.5601
    - type: nauc_mrr_at_5_diff1
      value: 28.8561
    - type: nauc_mrr_at_10_max
      value: 13.1101
    - type: nauc_mrr_at_10_std
      value: -18.915000000000003
    - type: nauc_mrr_at_10_diff1
      value: 28.9512
    - type: nauc_mrr_at_20_max
      value: 13.0191
    - type: nauc_mrr_at_20_std
      value: -18.501
    - type: nauc_mrr_at_20_diff1
      value: 29.102299999999996
    - type: nauc_mrr_at_100_max
      value: 13.475699999999998
    - type: nauc_mrr_at_100_std
      value: -17.9907
    - type: nauc_mrr_at_100_diff1
      value: 29.549999999999997
    - type: nauc_mrr_at_1000_max
      value: 13.3963
    - type: nauc_mrr_at_1000_std
      value: -18.093999999999998
    - type: nauc_mrr_at_1000_diff1
      value: 29.583
    - type: main_score
      value: 35.449999999999996
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB DBPedia (default)
      revision: c0f706b76e590d620bd6618b3ca8efdd34e2d659
      split: test
      type: mteb/dbpedia
    metrics:
    - type: ndcg_at_1
      value: 51.37500000000001
    - type: ndcg_at_3
      value: 41.275
    - type: ndcg_at_5
      value: 38.297
    - type: ndcg_at_10
      value: 35.96
    - type: ndcg_at_20
      value: 35.117
    - type: ndcg_at_100
      value: 39.878
    - type: ndcg_at_1000
      value: 47.931000000000004
    - type: map_at_1
      value: 8.651
    - type: map_at_3
      value: 13.51
    - type: map_at_5
      value: 15.468000000000002
    - type: map_at_10
      value: 17.628
    - type: map_at_20
      value: 19.786
    - type: map_at_100
      value: 23.354
    - type: map_at_1000
      value: 24.826
    - type: recall_at_1
      value: 8.651
    - type: recall_at_3
      value: 14.847
    - type: recall_at_5
      value: 18.04
    - type: recall_at_10
      value: 22.416
    - type: recall_at_20
      value: 28.136
    - type: recall_at_100
      value: 46.381
    - type: recall_at_1000
      value: 71.557
    - type: precision_at_1
      value: 64.5
    - type: precision_at_3
      value: 44.417
    - type: precision_at_5
      value: 36.6
    - type: precision_at_10
      value: 27.450000000000003
    - type: precision_at_20
      value: 19.811999999999998
    - type: precision_at_100
      value: 8.405
    - type: precision_at_1000
      value: 1.923
    - type: mrr_at_1
      value: 64.5
    - type: mrr_at_3
      value: 70.25
    - type: mrr_at_5
      value: 71.275
    - type: mrr_at_10
      value: 71.9889
    - type: mrr_at_20
      value: 72.207
    - type: mrr_at_100
      value: 72.33239999999999
    - type: mrr_at_1000
      value: 72.3461
    - type: nauc_ndcg_at_1_max
      value: 31.932100000000002
    - type: nauc_ndcg_at_1_std
      value: 10.2841
    - type: nauc_ndcg_at_1_diff1
      value: 36.07
    - type: nauc_ndcg_at_3_max
      value: 29.2531
    - type: nauc_ndcg_at_3_std
      value: 11.178799999999999
    - type: nauc_ndcg_at_3_diff1
      value: 25.764799999999997
    - type: nauc_ndcg_at_5_max
      value: 27.1826
    - type: nauc_ndcg_at_5_std
      value: 12.5
    - type: nauc_ndcg_at_5_diff1
      value: 24.9511
    - type: nauc_ndcg_at_10_max
      value: 24.1388
    - type: nauc_ndcg_at_10_std
      value: 11.350200000000001
    - type: nauc_ndcg_at_10_diff1
      value: 23.7319
    - type: nauc_ndcg_at_20_max
      value: 19.1396
    - type: nauc_ndcg_at_20_std
      value: 9.464699999999999
    - type: nauc_ndcg_at_20_diff1
      value: 20.9192
    - type: nauc_ndcg_at_100_max
      value: 20.1158
    - type: nauc_ndcg_at_100_std
      value: 13.2815
    - type: nauc_ndcg_at_100_diff1
      value: 21.221400000000003
    - type: nauc_ndcg_at_1000_max
      value: 26.648899999999998
    - type: nauc_ndcg_at_1000_std
      value: 22.5347
    - type: nauc_ndcg_at_1000_diff1
      value: 19.6168
    - type: nauc_map_at_1_max
      value: -4.3177
    - type: nauc_map_at_1_std
      value: -24.5562
    - type: nauc_map_at_1_diff1
      value: 29.4423
    - type: nauc_map_at_3_max
      value: -3.3966000000000003
    - type: nauc_map_at_3_std
      value: -21.9222
    - type: nauc_map_at_3_diff1
      value: 21.2481
    - type: nauc_map_at_5_max
      value: -1.1166
    - type: nauc_map_at_5_std
      value: -17.1077
    - type: nauc_map_at_5_diff1
      value: 19.9608
    - type: nauc_map_at_10_max
      value: 2.8669000000000002
    - type: nauc_map_at_10_std
      value: -11.6119
    - type: nauc_map_at_10_diff1
      value: 19.6247
    - type: nauc_map_at_20_max
      value: 6.4855
    - type: nauc_map_at_20_std
      value: -4.1277
    - type: nauc_map_at_20_diff1
      value: 18.1824
    - type: nauc_map_at_100_max
      value: 12.971499999999999
    - type: nauc_map_at_100_std
      value: 7.603400000000001
    - type: nauc_map_at_100_diff1
      value: 17.5644
    - type: nauc_map_at_1000_max
      value: 15.277299999999999
    - type: nauc_map_at_1000_std
      value: 10.5578
    - type: nauc_map_at_1000_diff1
      value: 17.1155
    - type: nauc_recall_at_1_max
      value: -4.3177
    - type: nauc_recall_at_1_std
      value: -24.5562
    - type: nauc_recall_at_1_diff1
      value: 29.4423
    - type: nauc_recall_at_3_max
      value: -6.2376000000000005
    - type: nauc_recall_at_3_std
      value: -23.4233
    - type: nauc_recall_at_3_diff1
      value: 17.329800000000002
    - type: nauc_recall_at_5_max
      value: -3.4825000000000004
    - type: nauc_recall_at_5_std
      value: -17.4895
    - type: nauc_recall_at_5_diff1
      value: 16.2379
    - type: nauc_recall_at_10_max
      value: 0.9988
    - type: nauc_recall_at_10_std
      value: -11.1992
    - type: nauc_recall_at_10_diff1
      value: 16.225
    - type: nauc_recall_at_20_max
      value: 4.693300000000001
    - type: nauc_recall_at_20_std
      value: -1.8259999999999998
    - type: nauc_recall_at_20_diff1
      value: 12.612400000000001
    - type: nauc_recall_at_100_max
      value: 13.420599999999999
    - type: nauc_recall_at_100_std
      value: 14.4476
    - type: nauc_recall_at_100_diff1
      value: 14.5736
    - type: nauc_recall_at_1000_max
      value: 18.4052
    - type: nauc_recall_at_1000_std
      value: 32.6262
    - type: nauc_recall_at_1000_diff1
      value: 6.2448
    - type: nauc_precision_at_1_max
      value: 44.2395
    - type: nauc_precision_at_1_std
      value: 16.9766
    - type: nauc_precision_at_1_diff1
      value: 42.981
    - type: nauc_precision_at_3_max
      value: 37.5078
    - type: nauc_precision_at_3_std
      value: 24.46
    - type: nauc_precision_at_3_diff1
      value: 16.700799999999997
    - type: nauc_precision_at_5_max
      value: 39.9766
    - type: nauc_precision_at_5_std
      value: 35.1485
    - type: nauc_precision_at_5_diff1
      value: 13.0716
    - type: nauc_precision_at_10_max
      value: 39.642500000000005
    - type: nauc_precision_at_10_std
      value: 41.8067
    - type: nauc_precision_at_10_diff1
      value: 8.864700000000001
    - type: nauc_precision_at_20_max
      value: 36.7342
    - type: nauc_precision_at_20_std
      value: 47.144200000000005
    - type: nauc_precision_at_20_diff1
      value: 3.6226000000000003
    - type: nauc_precision_at_100_max
      value: 35.3062
    - type: nauc_precision_at_100_std
      value: 47.2687
    - type: nauc_precision_at_100_diff1
      value: 0.0039
    - type: nauc_precision_at_1000_max
      value: 27.387099999999997
    - type: nauc_precision_at_1000_std
      value: 24.4162
    - type: nauc_precision_at_1000_diff1
      value: -13.5
    - type: nauc_mrr_at_1_max
      value: 44.2395
    - type: nauc_mrr_at_1_std
      value: 16.9766
    - type: nauc_mrr_at_1_diff1
      value: 42.981
    - type: nauc_mrr_at_3_max
      value: 45.9027
    - type: nauc_mrr_at_3_std
      value: 16.3998
    - type: nauc_mrr_at_3_diff1
      value: 42.7201
    - type: nauc_mrr_at_5_max
      value: 46.7905
    - type: nauc_mrr_at_5_std
      value: 17.921599999999998
    - type: nauc_mrr_at_5_diff1
      value: 42.4334
    - type: nauc_mrr_at_10_max
      value: 46.775
    - type: nauc_mrr_at_10_std
      value: 18.282899999999998
    - type: nauc_mrr_at_10_diff1
      value: 42.4501
    - type: nauc_mrr_at_20_max
      value: 46.671600000000005
    - type: nauc_mrr_at_20_std
      value: 18.064700000000002
    - type: nauc_mrr_at_20_diff1
      value: 42.4331
    - type: nauc_mrr_at_100_max
      value: 46.7118
    - type: nauc_mrr_at_100_std
      value: 18.2135
    - type: nauc_mrr_at_100_diff1
      value: 42.4809
    - type: nauc_mrr_at_1000_max
      value: 46.6966
    - type: nauc_mrr_at_1000_std
      value: 18.185200000000002
    - type: nauc_mrr_at_1000_diff1
      value: 42.4844
    - type: main_score
      value: 35.96
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB EmotionClassification (default)
      revision: 4f58c6b202a23cf9a4da393831edf4f9183cad37
      split: test
      type: mteb/emotion
    metrics:
    - type: accuracy
      value: 38.795
    - type: f1
      value: 35.2399
    - type: f1_weighted
      value: 40.7945
    - type: main_score
      value: 38.795
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB FEVER (default)
      revision: bea83ef9e8fb933d90a2f1d5515737465d613e12
      split: test
      type: mteb/fever
    metrics:
    - type: ndcg_at_1
      value: 79.08800000000001
    - type: ndcg_at_3
      value: 83.943
    - type: ndcg_at_5
      value: 84.878
    - type: ndcg_at_10
      value: 85.528
    - type: ndcg_at_20
      value: 85.842
    - type: ndcg_at_100
      value: 86.134
    - type: ndcg_at_1000
      value: 86.367
    - type: map_at_1
      value: 73.211
    - type: map_at_3
      value: 80.5
    - type: map_at_5
      value: 81.134
    - type: map_at_10
      value: 81.463
    - type: map_at_20
      value: 81.566
    - type: map_at_100
      value: 81.622
    - type: map_at_1000
      value: 81.634
    - type: recall_at_1
      value: 73.211
    - type: recall_at_3
      value: 88.32799999999999
    - type: recall_at_5
      value: 90.821
    - type: recall_at_10
      value: 92.797
    - type: recall_at_20
      value: 93.932
    - type: recall_at_100
      value: 95.26299999999999
    - type: recall_at_1000
      value: 96.738
    - type: precision_at_1
      value: 79.08800000000001
    - type: precision_at_3
      value: 31.963
    - type: precision_at_5
      value: 19.769000000000002
    - type: precision_at_10
      value: 10.132
    - type: precision_at_20
      value: 5.149
    - type: precision_at_100
      value: 1.055
    - type: precision_at_1000
      value: 0.109
    - type: mrr_at_1
      value: 79.0879
    - type: mrr_at_3
      value: 86.1536
    - type: mrr_at_5
      value: 86.7004
    - type: mrr_at_10
      value: 86.9425
    - type: mrr_at_20
      value: 87.00099999999999
    - type: mrr_at_100
      value: 87.01719999999999
    - type: mrr_at_1000
      value: 87.01769999999999
    - type: nauc_ndcg_at_1_max
      value: 28.2184
    - type: nauc_ndcg_at_1_std
      value: -20.374200000000002
    - type: nauc_ndcg_at_1_diff1
      value: 64.4185
    - type: nauc_ndcg_at_3_max
      value: 22.014
    - type: nauc_ndcg_at_3_std
      value: -15.221699999999998
    - type: nauc_ndcg_at_3_diff1
      value: 47.511700000000005
    - type: nauc_ndcg_at_5_max
      value: 21.381700000000002
    - type: nauc_ndcg_at_5_std
      value: -14.3711
    - type: nauc_ndcg_at_5_diff1
      value: 46.6271
    - type: nauc_ndcg_at_10_max
      value: 20.4251
    - type: nauc_ndcg_at_10_std
      value: -13.3096
    - type: nauc_ndcg_at_10_diff1
      value: 46.1205
    - type: nauc_ndcg_at_20_max
      value: 20.686
    - type: nauc_ndcg_at_20_std
      value: -12.6058
    - type: nauc_ndcg_at_20_diff1
      value: 46.14
    - type: nauc_ndcg_at_100_max
      value: 20.657700000000002
    - type: nauc_ndcg_at_100_std
      value: -12.5531
    - type: nauc_ndcg_at_100_diff1
      value: 46.3788
    - type: nauc_ndcg_at_1000_max
      value: 21.0177
    - type: nauc_ndcg_at_1000_std
      value: -12.8318
    - type: nauc_ndcg_at_1000_diff1
      value: 46.8648
    - type: nauc_map_at_1_max
      value: 21.4975
    - type: nauc_map_at_1_std
      value: -14.5207
    - type: nauc_map_at_1_diff1
      value: 51.53959999999999
    - type: nauc_map_at_3_max
      value: 20.322699999999998
    - type: nauc_map_at_3_std
      value: -13.8986
    - type: nauc_map_at_3_diff1
      value: 46.3932
    - type: nauc_map_at_5_max
      value: 20.3296
    - type: nauc_map_at_5_std
      value: -13.5416
    - type: nauc_map_at_5_diff1
      value: 46.1518
    - type: nauc_map_at_10_max
      value: 20.0385
    - type: nauc_map_at_10_std
      value: -13.239999999999998
    - type: nauc_map_at_10_diff1
      value: 46.061800000000005
    - type: nauc_map_at_20_max
      value: 20.113300000000002
    - type: nauc_map_at_20_std
      value: -13.0931
    - type: nauc_map_at_20_diff1
      value: 46.091
    - type: nauc_map_at_100_max
      value: 20.1262
    - type: nauc_map_at_100_std
      value: -13.0646
    - type: nauc_map_at_100_diff1
      value: 46.1321
    - type: nauc_map_at_1000_max
      value: 20.1391
    - type: nauc_map_at_1000_std
      value: -13.069600000000001
    - type: nauc_map_at_1000_diff1
      value: 46.1501
    - type: nauc_recall_at_1_max
      value: 21.4975
    - type: nauc_recall_at_1_std
      value: -14.5207
    - type: nauc_recall_at_1_diff1
      value: 51.53959999999999
    - type: nauc_recall_at_3_max
      value: 15.379399999999999
    - type: nauc_recall_at_3_std
      value: -9.9735
    - type: nauc_recall_at_3_diff1
      value: 30.6769
    - type: nauc_recall_at_5_max
      value: 13.104099999999999
    - type: nauc_recall_at_5_std
      value: -6.2273000000000005
    - type: nauc_recall_at_5_diff1
      value: 24.4602
    - type: nauc_recall_at_10_max
      value: 6.4093
    - type: nauc_recall_at_10_std
      value: 0.9238
    - type: nauc_recall_at_10_diff1
      value: 16.2715
    - type: nauc_recall_at_20_max
      value: 5.5285
    - type: nauc_recall_at_20_std
      value: 9.1474
    - type: nauc_recall_at_20_diff1
      value: 10.8034
    - type: nauc_recall_at_100_max
      value: -0.116
    - type: nauc_recall_at_100_std
      value: 14.4612
    - type: nauc_recall_at_100_diff1
      value: 4.6372
    - type: nauc_recall_at_1000_max
      value: -1.595
    - type: nauc_recall_at_1000_std
      value: 18.1495
    - type: nauc_recall_at_1000_diff1
      value: -0.022000000000000002
    - type: nauc_precision_at_1_max
      value: 28.2184
    - type: nauc_precision_at_1_std
      value: -20.374200000000002
    - type: nauc_precision_at_1_diff1
      value: 64.4185
    - type: nauc_precision_at_3_max
      value: 24.238799999999998
    - type: nauc_precision_at_3_std
      value: -19.7064
    - type: nauc_precision_at_3_diff1
      value: 37.7498
    - type: nauc_precision_at_5_max
      value: 20.8308
    - type: nauc_precision_at_5_std
      value: -13.6486
    - type: nauc_precision_at_5_diff1
      value: 23.3404
    - type: nauc_precision_at_10_max
      value: 9.4386
    - type: nauc_precision_at_10_std
      value: -4.8239
    - type: nauc_precision_at_10_diff1
      value: 6.8594
    - type: nauc_precision_at_20_max
      value: 9.0063
    - type: nauc_precision_at_20_std
      value: 4.0311
    - type: nauc_precision_at_20_diff1
      value: -2.9298
    - type: nauc_precision_at_100_max
      value: 5.1057
    - type: nauc_precision_at_100_std
      value: 7.3903
    - type: nauc_precision_at_100_diff1
      value: -8.7148
    - type: nauc_precision_at_1000_max
      value: 6.3359
    - type: nauc_precision_at_1000_std
      value: 3.9797
    - type: nauc_precision_at_1000_diff1
      value: -8.3131
    - type: nauc_mrr_at_1_max
      value: 28.2184
    - type: nauc_mrr_at_1_std
      value: -20.374200000000002
    - type: nauc_mrr_at_1_diff1
      value: 64.4185
    - type: nauc_mrr_at_3_max
      value: 29.7481
    - type: nauc_mrr_at_3_std
      value: -21.9924
    - type: nauc_mrr_at_3_diff1
      value: 62.5737
    - type: nauc_mrr_at_5_max
      value: 29.8062
    - type: nauc_mrr_at_5_std
      value: -22.078
    - type: nauc_mrr_at_5_diff1
      value: 62.9
    - type: nauc_mrr_at_10_max
      value: 29.641000000000002
    - type: nauc_mrr_at_10_std
      value: -21.6827
    - type: nauc_mrr_at_10_diff1
      value: 62.944599999999994
    - type: nauc_mrr_at_20_max
      value: 29.6535
    - type: nauc_mrr_at_20_std
      value: -21.520400000000002
    - type: nauc_mrr_at_20_diff1
      value: 62.9583
    - type: nauc_mrr_at_100_max
      value: 29.622799999999998
    - type: nauc_mrr_at_100_std
      value: -21.5393
    - type: nauc_mrr_at_100_diff1
      value: 62.9658
    - type: nauc_mrr_at_1000_max
      value: 29.619400000000002
    - type: nauc_mrr_at_1000_std
      value: -21.5417
    - type: nauc_mrr_at_1000_diff1
      value: 62.96469999999999
    - type: main_score
      value: 85.528
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB FiQA2018 (default)
      revision: 27a168819829fe9bcd655c2df245fb19452e8e06
      split: test
      type: mteb/fiqa
    metrics:
    - type: ndcg_at_1
      value: 35.494
    - type: ndcg_at_3
      value: 32.305
    - type: ndcg_at_5
      value: 34.332
    - type: ndcg_at_10
      value: 36.851
    - type: ndcg_at_20
      value: 39.31
    - type: ndcg_at_100
      value: 43.462
    - type: ndcg_at_1000
      value: 46.766000000000005
    - type: map_at_1
      value: 18.311
    - type: map_at_3
      value: 24.778
    - type: map_at_5
      value: 27.453
    - type: map_at_10
      value: 29.198
    - type: map_at_20
      value: 30.118000000000002
    - type: map_at_100
      value: 30.930000000000003
    - type: map_at_1000
      value: 31.115
    - type: recall_at_1
      value: 18.311
    - type: recall_at_3
      value: 28.823999999999998
    - type: recall_at_5
      value: 36.178
    - type: recall_at_10
      value: 43.842
    - type: recall_at_20
      value: 51.370000000000005
    - type: recall_at_100
      value: 68.593
    - type: recall_at_1000
      value: 88.55
    - type: precision_at_1
      value: 35.494
    - type: precision_at_3
      value: 21.142
    - type: precision_at_5
      value: 16.326999999999998
    - type: precision_at_10
      value: 10.309
    - type: precision_at_20
      value: 6.211
    - type: precision_at_100
      value: 1.7069999999999999
    - type: precision_at_1000
      value: 0.22899999999999998
    - type: mrr_at_1
      value: 35.4938
    - type: mrr_at_3
      value: 41.6667
    - type: mrr_at_5
      value: 43.4182
    - type: mrr_at_10
      value: 44.4732
    - type: mrr_at_20
      value: 44.969
    - type: mrr_at_100
      value: 45.318599999999996
    - type: mrr_at_1000
      value: 45.3674
    - type: nauc_ndcg_at_1_max
      value: 33.946799999999996
    - type: nauc_ndcg_at_1_std
      value: -5.282
    - type: nauc_ndcg_at_1_diff1
      value: 47.413
    - type: nauc_ndcg_at_3_max
      value: 30.9073
    - type: nauc_ndcg_at_3_std
      value: -2.2498
    - type: nauc_ndcg_at_3_diff1
      value: 38.548500000000004
    - type: nauc_ndcg_at_5_max
      value: 30.2537
    - type: nauc_ndcg_at_5_std
      value: -0.9919000000000001
    - type: nauc_ndcg_at_5_diff1
      value: 37.988499999999995
    - type: nauc_ndcg_at_10_max
      value: 30.5224
    - type: nauc_ndcg_at_10_std
      value: 0.0762
    - type: nauc_ndcg_at_10_diff1
      value: 38.2531
    - type: nauc_ndcg_at_20_max
      value: 32.173
    - type: nauc_ndcg_at_20_std
      value: 3.3266999999999998
    - type: nauc_ndcg_at_20_diff1
      value: 37.5071
    - type: nauc_ndcg_at_100_max
      value: 33.551700000000004
    - type: nauc_ndcg_at_100_std
      value: 5.8902
    - type: nauc_ndcg_at_100_diff1
      value: 37.3363
    - type: nauc_ndcg_at_1000_max
      value: 34.1671
    - type: nauc_ndcg_at_1000_std
      value: 5.4682
    - type: nauc_ndcg_at_1000_diff1
      value: 37.5779
    - type: nauc_map_at_1_max
      value: 20.0425
    - type: nauc_map_at_1_std
      value: -7.41
    - type: nauc_map_at_1_diff1
      value: 40.725699999999996
    - type: nauc_map_at_3_max
      value: 25.380799999999997
    - type: nauc_map_at_3_std
      value: -4.5524000000000004
    - type: nauc_map_at_3_diff1
      value: 38.960699999999996
    - type: nauc_map_at_5_max
      value: 27.208900000000003
    - type: nauc_map_at_5_std
      value: -3.034
    - type: nauc_map_at_5_diff1
      value: 38.475500000000004
    - type: nauc_map_at_10_max
      value: 28.6066
    - type: nauc_map_at_10_std
      value: -2.1042
    - type: nauc_map_at_10_diff1
      value: 38.4411
    - type: nauc_map_at_20_max
      value: 29.3931
    - type: nauc_map_at_20_std
      value: -0.8289
    - type: nauc_map_at_20_diff1
      value: 38.137
    - type: nauc_map_at_100_max
      value: 29.8041
    - type: nauc_map_at_100_std
      value: -0.1992
    - type: nauc_map_at_100_diff1
      value: 38.0546
    - type: nauc_map_at_1000_max
      value: 29.886400000000002
    - type: nauc_map_at_1000_std
      value: -0.1638
    - type: nauc_map_at_1000_diff1
      value: 38.0646
    - type: nauc_recall_at_1_max
      value: 20.0425
    - type: nauc_recall_at_1_std
      value: -7.41
    - type: nauc_recall_at_1_diff1
      value: 40.725699999999996
    - type: nauc_recall_at_3_max
      value: 20.8038
    - type: nauc_recall_at_3_std
      value: -4.1075
    - type: nauc_recall_at_3_diff1
      value: 33.0009
    - type: nauc_recall_at_5_max
      value: 23.1816
    - type: nauc_recall_at_5_std
      value: 0.2681
    - type: nauc_recall_at_5_diff1
      value: 30.1663
    - type: nauc_recall_at_10_max
      value: 23.754
    - type: nauc_recall_at_10_std
      value: 2.4185000000000003
    - type: nauc_recall_at_10_diff1
      value: 28.475499999999997
    - type: nauc_recall_at_20_max
      value: 27.711599999999997
    - type: nauc_recall_at_20_std
      value: 12.509700000000002
    - type: nauc_recall_at_20_diff1
      value: 25.172299999999996
    - type: nauc_recall_at_100_max
      value: 29.3806
    - type: nauc_recall_at_100_std
      value: 25.1963
    - type: nauc_recall_at_100_diff1
      value: 21.849
    - type: nauc_recall_at_1000_max
      value: 34.1492
    - type: nauc_recall_at_1000_std
      value: 40.4872
    - type: nauc_recall_at_1000_diff1
      value: 17.0167
    - type: nauc_precision_at_1_max
      value: 33.946799999999996
    - type: nauc_precision_at_1_std
      value: -5.282
    - type: nauc_precision_at_1_diff1
      value: 47.413
    - type: nauc_precision_at_3_max
      value: 36.6837
    - type: nauc_precision_at_3_std
      value: 3.7282
    - type: nauc_precision_at_3_diff1
      value: 31.0152
    - type: nauc_precision_at_5_max
      value: 37.6087
    - type: nauc_precision_at_5_std
      value: 7.3439000000000005
    - type: nauc_precision_at_5_diff1
      value: 27.2321
    - type: nauc_precision_at_10_max
      value: 38.2792
    - type: nauc_precision_at_10_std
      value: 11.3814
    - type: nauc_precision_at_10_diff1
      value: 22.6494
    - type: nauc_precision_at_20_max
      value: 38.455
    - type: nauc_precision_at_20_std
      value: 17.4053
    - type: nauc_precision_at_20_diff1
      value: 16.8265
    - type: nauc_precision_at_100_max
      value: 36.203
    - type: nauc_precision_at_100_std
      value: 22.2758
    - type: nauc_precision_at_100_diff1
      value: 8.3908
    - type: nauc_precision_at_1000_max
      value: 29.599700000000002
    - type: nauc_precision_at_1000_std
      value: 17.186899999999998
    - type: nauc_precision_at_1000_diff1
      value: 0.0332
    - type: nauc_mrr_at_1_max
      value: 33.946799999999996
    - type: nauc_mrr_at_1_std
      value: -5.282
    - type: nauc_mrr_at_1_diff1
      value: 47.413
    - type: nauc_mrr_at_3_max
      value: 34.0785
    - type: nauc_mrr_at_3_std
      value: -2.1323000000000003
    - type: nauc_mrr_at_3_diff1
      value: 43.8661
    - type: nauc_mrr_at_5_max
      value: 34.244
    - type: nauc_mrr_at_5_std
      value: -1.5425
    - type: nauc_mrr_at_5_diff1
      value: 43.7631
    - type: nauc_mrr_at_10_max
      value: 34.265299999999996
    - type: nauc_mrr_at_10_std
      value: -1.1494
    - type: nauc_mrr_at_10_diff1
      value: 43.639
    - type: nauc_mrr_at_20_max
      value: 34.5648
    - type: nauc_mrr_at_20_std
      value: -0.6076
    - type: nauc_mrr_at_20_diff1
      value: 43.431
    - type: nauc_mrr_at_100_max
      value: 34.571400000000004
    - type: nauc_mrr_at_100_std
      value: -0.5074000000000001
    - type: nauc_mrr_at_100_diff1
      value: 43.4003
    - type: nauc_mrr_at_1000_max
      value: 34.5576
    - type: nauc_mrr_at_1000_std
      value: -0.534
    - type: nauc_mrr_at_1000_diff1
      value: 43.4086
    - type: main_score
      value: 36.851
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB HotpotQA (default)
      revision: ab518f4d6fcca38d87c25209f94beba119d02014
      split: test
      type: mteb/hotpotqa
    metrics:
    - type: ndcg_at_1
      value: 73.531
    - type: ndcg_at_3
      value: 58.24700000000001
    - type: ndcg_at_5
      value: 60.905
    - type: ndcg_at_10
      value: 62.918
    - type: ndcg_at_20
      value: 64.297
    - type: ndcg_at_100
      value: 66.056
    - type: ndcg_at_1000
      value: 67.554
    - type: map_at_1
      value: 36.766
    - type: map_at_3
      value: 50.427
    - type: map_at_5
      value: 52.449999999999996
    - type: map_at_10
      value: 53.639
    - type: map_at_20
      value: 54.17999999999999
    - type: map_at_100
      value: 54.532000000000004
    - type: map_at_1000
      value: 54.608000000000004
    - type: recall_at_1
      value: 36.766
    - type: recall_at_3
      value: 54.835
    - type: recall_at_5
      value: 60.080999999999996
    - type: recall_at_10
      value: 65.098
    - type: recall_at_20
      value: 69.541
    - type: recall_at_100
      value: 77.306
    - type: recall_at_1000
      value: 87.252
    - type: precision_at_1
      value: 73.531
    - type: precision_at_3
      value: 36.556
    - type: precision_at_5
      value: 24.032
    - type: precision_at_10
      value: 13.020000000000001
    - type: precision_at_20
      value: 6.954000000000001
    - type: precision_at_100
      value: 1.546
    - type: precision_at_1000
      value: 0.17500000000000002
    - type: mrr_at_1
      value: 73.5314
    - type: mrr_at_3
      value: 78.9489
    - type: mrr_at_5
      value: 79.7288
    - type: mrr_at_10
      value: 80.1036
    - type: mrr_at_20
      value: 80.2602
    - type: mrr_at_100
      value: 80.3412
    - type: mrr_at_1000
      value: 80.3512
    - type: nauc_ndcg_at_1_max
      value: 49.4087
    - type: nauc_ndcg_at_1_std
      value: -8.233
    - type: nauc_ndcg_at_1_diff1
      value: 69.19380000000001
    - type: nauc_ndcg_at_3_max
      value: 29.407899999999998
    - type: nauc_ndcg_at_3_std
      value: -2.1144
    - type: nauc_ndcg_at_3_diff1
      value: 27.245599999999996
    - type: nauc_ndcg_at_5_max
      value: 27.483
    - type: nauc_ndcg_at_5_std
      value: -0.7036
    - type: nauc_ndcg_at_5_diff1
      value: 24.2534
    - type: nauc_ndcg_at_10_max
      value: 26.766499999999997
    - type: nauc_ndcg_at_10_std
      value: 0.5583
    - type: nauc_ndcg_at_10_diff1
      value: 22.822300000000002
    - type: nauc_ndcg_at_20_max
      value: 26.339800000000004
    - type: nauc_ndcg_at_20_std
      value: 1.3486
    - type: nauc_ndcg_at_20_diff1
      value: 22.3499
    - type: nauc_ndcg_at_100_max
      value: 26.436799999999998
    - type: nauc_ndcg_at_100_std
      value: 2.5304
    - type: nauc_ndcg_at_100_diff1
      value: 22.372700000000002
    - type: nauc_ndcg_at_1000_max
      value: 26.9472
    - type: nauc_ndcg_at_1000_std
      value: 2.3277
    - type: nauc_ndcg_at_1000_diff1
      value: 23.3345
    - type: nauc_map_at_1_max
      value: 49.4087
    - type: nauc_map_at_1_std
      value: -8.233
    - type: nauc_map_at_1_diff1
      value: 69.19380000000001
    - type: nauc_map_at_3_max
      value: 25.2676
    - type: nauc_map_at_3_std
      value: -1.8659999999999999
    - type: nauc_map_at_3_diff1
      value: 21.0961
    - type: nauc_map_at_5_max
      value: 24.0651
    - type: nauc_map_at_5_std
      value: -0.8111
    - type: nauc_map_at_5_diff1
      value: 19.237099999999998
    - type: nauc_map_at_10_max
      value: 23.785
    - type: nauc_map_at_10_std
      value: -0.1037
    - type: nauc_map_at_10_diff1
      value: 18.5973
    - type: nauc_map_at_20_max
      value: 23.6813
    - type: nauc_map_at_20_std
      value: 0.1708
    - type: nauc_map_at_20_diff1
      value: 18.499299999999998
    - type: nauc_map_at_100_max
      value: 23.7276
    - type: nauc_map_at_100_std
      value: 0.3879
    - type: nauc_map_at_100_diff1
      value: 18.5423
    - type: nauc_map_at_1000_max
      value: 23.7501
    - type: nauc_map_at_1000_std
      value: 0.3886
    - type: nauc_map_at_1000_diff1
      value: 18.578500000000002
    - type: nauc_recall_at_1_max
      value: 49.4087
    - type: nauc_recall_at_1_std
      value: -8.233
    - type: nauc_recall_at_1_diff1
      value: 69.19380000000001
    - type: nauc_recall_at_3_max
      value: 21.7043
    - type: nauc_recall_at_3_std
      value: 0.24320000000000003
    - type: nauc_recall_at_3_diff1
      value: 12.102599999999999
    - type: nauc_recall_at_5_max
      value: 16.923
    - type: nauc_recall_at_5_std
      value: 2.9763
    - type: nauc_recall_at_5_diff1
      value: 5.5262
    - type: nauc_recall_at_10_max
      value: 13.8286
    - type: nauc_recall_at_10_std
      value: 6.1254
    - type: nauc_recall_at_10_diff1
      value: 0.6326
    - type: nauc_recall_at_20_max
      value: 11.307300000000001
    - type: nauc_recall_at_20_std
      value: 8.9861
    - type: nauc_recall_at_20_diff1
      value: -2.5909
    - type: nauc_recall_at_100_max
      value: 8.2009
    - type: nauc_recall_at_100_std
      value: 16.051199999999998
    - type: nauc_recall_at_100_diff1
      value: -7.757699999999999
    - type: nauc_recall_at_1000_max
      value: 5.4062
    - type: nauc_recall_at_1000_std
      value: 20.6122
    - type: nauc_recall_at_1000_diff1
      value: -11.931700000000001
    - type: nauc_precision_at_1_max
      value: 49.4087
    - type: nauc_precision_at_1_std
      value: -8.233
    - type: nauc_precision_at_1_diff1
      value: 69.19380000000001
    - type: nauc_precision_at_3_max
      value: 21.7043
    - type: nauc_precision_at_3_std
      value: 0.24320000000000003
    - type: nauc_precision_at_3_diff1
      value: 12.102599999999999
    - type: nauc_precision_at_5_max
      value: 16.923
    - type: nauc_precision_at_5_std
      value: 2.9763
    - type: nauc_precision_at_5_diff1
      value: 5.5262
    - type: nauc_precision_at_10_max
      value: 13.8286
    - type: nauc_precision_at_10_std
      value: 6.1254
    - type: nauc_precision_at_10_diff1
      value: 0.6326
    - type: nauc_precision_at_20_max
      value: 11.307300000000001
    - type: nauc_precision_at_20_std
      value: 8.9861
    - type: nauc_precision_at_20_diff1
      value: -2.5909
    - type: nauc_precision_at_100_max
      value: 8.2009
    - type: nauc_precision_at_100_std
      value: 16.051199999999998
    - type: nauc_precision_at_100_diff1
      value: -7.757699999999999
    - type: nauc_precision_at_1000_max
      value: 5.4062
    - type: nauc_precision_at_1000_std
      value: 20.6122
    - type: nauc_precision_at_1000_diff1
      value: -11.931700000000001
    - type: nauc_mrr_at_1_max
      value: 49.4087
    - type: nauc_mrr_at_1_std
      value: -8.233
    - type: nauc_mrr_at_1_diff1
      value: 69.19380000000001
    - type: nauc_mrr_at_3_max
      value: 51.004099999999994
    - type: nauc_mrr_at_3_std
      value: -6.4677
    - type: nauc_mrr_at_3_diff1
      value: 66.1969
    - type: nauc_mrr_at_5_max
      value: 50.880199999999995
    - type: nauc_mrr_at_5_std
      value: -6.3541
    - type: nauc_mrr_at_5_diff1
      value: 66.0764
    - type: nauc_mrr_at_10_max
      value: 50.924899999999994
    - type: nauc_mrr_at_10_std
      value: -6.2945
    - type: nauc_mrr_at_10_diff1
      value: 66.2079
    - type: nauc_mrr_at_20_max
      value: 50.907199999999996
    - type: nauc_mrr_at_20_std
      value: -6.253
    - type: nauc_mrr_at_20_diff1
      value: 66.28450000000001
    - type: nauc_mrr_at_100_max
      value: 50.8991
    - type: nauc_mrr_at_100_std
      value: -6.2459
    - type: nauc_mrr_at_100_diff1
      value: 66.3257
    - type: nauc_mrr_at_1000_max
      value: 50.8934
    - type: nauc_mrr_at_1000_std
      value: -6.2602
    - type: nauc_mrr_at_1000_diff1
      value: 66.328
    - type: main_score
      value: 62.918
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB ImdbClassification (default)
      revision: 3d86128a09e091d6018b6d26cad27f2739fc2db7
      split: test
      type: mteb/imdb
    metrics:
    - type: accuracy
      value: 62.2348
    - type: f1
      value: 62.0977
    - type: f1_weighted
      value: 62.0977
    - type: ap
      value: 57.750800000000005
    - type: ap_weighted
      value: 57.750800000000005
    - type: main_score
      value: 62.2348
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB MSMARCO (default)
      revision: c5a29a104738b98a9e76336939199e264163d4a0
      split: dev
      type: mteb/msmarco
    metrics:
    - type: ndcg_at_1
      value: 15.085999999999999
    - type: ndcg_at_3
      value: 23.567
    - type: ndcg_at_5
      value: 27.066000000000003
    - type: ndcg_at_10
      value: 30.711
    - type: ndcg_at_20
      value: 33.251999999999995
    - type: ndcg_at_100
      value: 37.221
    - type: ndcg_at_1000
      value: 39.133
    - type: map_at_1
      value: 14.654
    - type: map_at_3
      value: 21.234
    - type: map_at_5
      value: 23.189999999999998
    - type: map_at_10
      value: 24.72
    - type: map_at_20
      value: 25.433
    - type: map_at_100
      value: 25.994
    - type: map_at_1000
      value: 26.067
    - type: recall_at_1
      value: 14.654
    - type: recall_at_3
      value: 29.862
    - type: recall_at_5
      value: 38.274
    - type: recall_at_10
      value: 49.341
    - type: recall_at_20
      value: 59.206
    - type: recall_at_100
      value: 80.22399999999999
    - type: recall_at_1000
      value: 95.037
    - type: precision_at_1
      value: 15.085999999999999
    - type: precision_at_3
      value: 10.277
    - type: precision_at_5
      value: 7.922999999999999
    - type: precision_at_10
      value: 5.132
    - type: precision_at_20
      value: 3.0949999999999998
    - type: precision_at_100
      value: 0.845
    - type: precision_at_1000
      value: 0.101
    - type: mrr_at_1
      value: 15.085999999999999
    - type: mrr_at_3
      value: 21.7311
    - type: mrr_at_5
      value: 23.6738
    - type: mrr_at_10
      value: 25.184099999999997
    - type: mrr_at_20
      value: 25.878899999999998
    - type: mrr_at_100
      value: 26.4216
    - type: mrr_at_1000
      value: 26.4886
    - type: nauc_ndcg_at_1_max
      value: 3.3686000000000003
    - type: nauc_ndcg_at_1_std
      value: -14.960799999999999
    - type: nauc_ndcg_at_1_diff1
      value: 30.0257
    - type: nauc_ndcg_at_3_max
      value: 4.3222
    - type: nauc_ndcg_at_3_std
      value: -15.8473
    - type: nauc_ndcg_at_3_diff1
      value: 26.935399999999998
    - type: nauc_ndcg_at_5_max
      value: 4.8392
    - type: nauc_ndcg_at_5_std
      value: -15.7197
    - type: nauc_ndcg_at_5_diff1
      value: 26.1067
    - type: nauc_ndcg_at_10_max
      value: 4.8289
    - type: nauc_ndcg_at_10_std
      value: -14.713300000000002
    - type: nauc_ndcg_at_10_diff1
      value: 25.3576
    - type: nauc_ndcg_at_20_max
      value: 5.2264
    - type: nauc_ndcg_at_20_std
      value: -13.5723
    - type: nauc_ndcg_at_20_diff1
      value: 25.7189
    - type: nauc_ndcg_at_100_max
      value: 6.2197000000000005
    - type: nauc_ndcg_at_100_std
      value: -10.5613
    - type: nauc_ndcg_at_100_diff1
      value: 25.407200000000003
    - type: nauc_ndcg_at_1000_max
      value: 6.336899999999999
    - type: nauc_ndcg_at_1000_std
      value: -11.2538
    - type: nauc_ndcg_at_1000_diff1
      value: 25.8353
    - type: nauc_map_at_1_max
      value: 3.4762
    - type: nauc_map_at_1_std
      value: -14.829899999999999
    - type: nauc_map_at_1_diff1
      value: 30.220200000000002
    - type: nauc_map_at_3_max
      value: 4.1498
    - type: nauc_map_at_3_std
      value: -15.659699999999999
    - type: nauc_map_at_3_diff1
      value: 27.6738
    - type: nauc_map_at_5_max
      value: 4.457599999999999
    - type: nauc_map_at_5_std
      value: -15.593599999999999
    - type: nauc_map_at_5_diff1
      value: 27.147399999999998
    - type: nauc_map_at_10_max
      value: 4.4191
    - type: nauc_map_at_10_std
      value: -15.199599999999998
    - type: nauc_map_at_10_diff1
      value: 26.8024
    - type: nauc_map_at_20_max
      value: 4.559699999999999
    - type: nauc_map_at_20_std
      value: -14.8687
    - type: nauc_map_at_20_diff1
      value: 26.929799999999997
    - type: nauc_map_at_100_max
      value: 4.709300000000001
    - type: nauc_map_at_100_std
      value: -14.430599999999998
    - type: nauc_map_at_100_diff1
      value: 26.895200000000003
    - type: nauc_map_at_1000_max
      value: 4.7146
    - type: nauc_map_at_1000_std
      value: -14.4381
    - type: nauc_map_at_1000_diff1
      value: 26.9071
    - type: nauc_recall_at_1_max
      value: 3.4762
    - type: nauc_recall_at_1_std
      value: -14.829899999999999
    - type: nauc_recall_at_1_diff1
      value: 30.220200000000002
    - type: nauc_recall_at_3_max
      value: 4.8518
    - type: nauc_recall_at_3_std
      value: -16.215
    - type: nauc_recall_at_3_diff1
      value: 25.1628
    - type: nauc_recall_at_5_max
      value: 5.8279
    - type: nauc_recall_at_5_std
      value: -15.9303
    - type: nauc_recall_at_5_diff1
      value: 23.544999999999998
    - type: nauc_recall_at_10_max
      value: 5.7948
    - type: nauc_recall_at_10_std
      value: -13.1624
    - type: nauc_recall_at_10_diff1
      value: 21.5447
    - type: nauc_recall_at_20_max
      value: 7.0539000000000005
    - type: nauc_recall_at_20_std
      value: -8.9408
    - type: nauc_recall_at_20_diff1
      value: 22.4027
    - type: nauc_recall_at_100_max
      value: 15.1651
    - type: nauc_recall_at_100_std
      value: 16.419
    - type: nauc_recall_at_100_diff1
      value: 17.897299999999998
    - type: nauc_recall_at_1000_max
      value: 41.646300000000004
    - type: nauc_recall_at_1000_std
      value: 54.791000000000004
    - type: nauc_recall_at_1000_diff1
      value: 16.4922
    - type: nauc_precision_at_1_max
      value: 3.3686000000000003
    - type: nauc_precision_at_1_std
      value: -14.960799999999999
    - type: nauc_precision_at_1_diff1
      value: 30.0257
    - type: nauc_precision_at_3_max
      value: 4.8638
    - type: nauc_precision_at_3_std
      value: -16.3
    - type: nauc_precision_at_3_diff1
      value: 25.1213
    - type: nauc_precision_at_5_max
      value: 5.8399
    - type: nauc_precision_at_5_std
      value: -16.1007
    - type: nauc_precision_at_5_diff1
      value: 23.4288
    - type: nauc_precision_at_10_max
      value: 6.042
    - type: nauc_precision_at_10_std
      value: -13.0782
    - type: nauc_precision_at_10_diff1
      value: 20.8509
    - type: nauc_precision_at_20_max
      value: 7.9528
    - type: nauc_precision_at_20_std
      value: -8.2321
    - type: nauc_precision_at_20_diff1
      value: 21.0746
    - type: nauc_precision_at_100_max
      value: 16.026699999999998
    - type: nauc_precision_at_100_std
      value: 15.112200000000001
    - type: nauc_precision_at_100_diff1
      value: 13.2433
    - type: nauc_precision_at_1000_max
      value: 24.8965
    - type: nauc_precision_at_1000_std
      value: 24.741
    - type: nauc_precision_at_1000_diff1
      value: 2.8078
    - type: nauc_mrr_at_1_max
      value: 3.3686000000000003
    - type: nauc_mrr_at_1_std
      value: -14.960799999999999
    - type: nauc_mrr_at_1_diff1
      value: 30.0257
    - type: nauc_mrr_at_3_max
      value: 3.9521
    - type: nauc_mrr_at_3_std
      value: -15.6591
    - type: nauc_mrr_at_3_diff1
      value: 27.511799999999997
    - type: nauc_mrr_at_5_max
      value: 4.3118
    - type: nauc_mrr_at_5_std
      value: -15.5244
    - type: nauc_mrr_at_5_diff1
      value: 27.024199999999997
    - type: nauc_mrr_at_10_max
      value: 4.3529
    - type: nauc_mrr_at_10_std
      value: -15.065100000000001
    - type: nauc_mrr_at_10_diff1
      value: 26.7106
    - type: nauc_mrr_at_20_max
      value: 4.4593
    - type: nauc_mrr_at_20_std
      value: -14.7683
    - type: nauc_mrr_at_20_diff1
      value: 26.815099999999997
    - type: nauc_mrr_at_100_max
      value: 4.5908999999999995
    - type: nauc_mrr_at_100_std
      value: -14.361099999999999
    - type: nauc_mrr_at_100_diff1
      value: 26.7866
    - type: nauc_mrr_at_1000_max
      value: 4.5903
    - type: nauc_mrr_at_1000_std
      value: -14.3764
    - type: nauc_mrr_at_1000_diff1
      value: 26.801000000000002
    - type: main_score
      value: 30.711
    task:
      type: Retrieval
  - dataset:
      config: en
      name: MTEB MTOPDomainClassification (en)
      revision: d80d48c1eb48d3562165c59d59d0034df9fff0bf
      split: test
      type: mteb/mtop_domain
    metrics:
    - type: accuracy
      value: 89.4505
    - type: f1
      value: 89.00200000000001
    - type: f1_weighted
      value: 89.442
    - type: main_score
      value: 89.4505
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB MTOPIntentClassification (en)
      revision: ae001d0e6b1228650b7bd1c2c65fb50ad11a8aba
      split: test
      type: mteb/mtop_intent
    metrics:
    - type: accuracy
      value: 56.846799999999995
    - type: f1
      value: 39.2152
    - type: f1_weighted
      value: 58.797999999999995
    - type: main_score
      value: 56.846799999999995
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB MassiveIntentClassification (en)
      revision: 4672e20407010da34463acc759c162ca9734bca6
      split: test
      type: mteb/amazon_massive_intent
    metrics:
    - type: accuracy
      value: 64.768
    - type: f1
      value: 61.9285
    - type: f1_weighted
      value: 63.67
    - type: main_score
      value: 64.768
    task:
      type: Classification
  - dataset:
      config: en
      name: MTEB MassiveScenarioClassification (en)
      revision: fad2c6e8459f9e1c45d9315f4953d921437d70f8
      split: test
      type: mteb/amazon_massive_scenario
    metrics:
    - type: accuracy
      value: 71.3416
    - type: f1
      value: 69.9576
    - type: f1_weighted
      value: 71.19680000000001
    - type: main_score
      value: 71.3416
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB MedrxivClusteringP2P (default)
      revision: e7a26af6f3ae46b30dde8737f02c07b1505bcc73
      split: test
      type: mteb/medrxiv-clustering-p2p
    metrics:
    - type: v_measure
      value: 32.5684
    - type: v_measure_std
      value: 1.6362999999999999
    - type: main_score
      value: 32.5684
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB MedrxivClusteringS2S (default)
      revision: 35191c8c0dca72d8ff3efcd72aa802307d469663
      split: test
      type: mteb/medrxiv-clustering-s2s
    metrics:
    - type: v_measure
      value: 31.551299999999998
    - type: v_measure_std
      value: 1.7208999999999999
    - type: main_score
      value: 31.551299999999998
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB MindSmallReranking (default)
      revision: 59042f120c80e8afa9cdbb224f67076cec0fc9a7
      split: test
      type: mteb/mind_small
    metrics:
    - type: map
      value: 30.883
    - type: mrr
      value: 31.923299999999998
    - type: nAUC_map_max
      value: -20.072000000000003
    - type: nAUC_map_std
      value: -4.8503
    - type: nAUC_map_diff1
      value: 14.178099999999999
    - type: nAUC_mrr_max
      value: -14.7901
    - type: nAUC_mrr_std
      value: -2.8666
    - type: nAUC_mrr_diff1
      value: 13.2767
    - type: main_score
      value: 30.883
    task:
      type: Reranking
  - dataset:
      config: default
      name: MTEB NFCorpus (default)
      revision: ec0fa4fe99da2ff19ca1214b7966684033a58814
      split: test
      type: mteb/nfcorpus
    metrics:
    - type: ndcg_at_1
      value: 41.486000000000004
    - type: ndcg_at_3
      value: 39.324
    - type: ndcg_at_5
      value: 36.949
    - type: ndcg_at_10
      value: 33.737
    - type: ndcg_at_20
      value: 31.320999999999998
    - type: ndcg_at_100
      value: 30.886000000000003
    - type: ndcg_at_1000
      value: 40.018
    - type: map_at_1
      value: 5.452
    - type: map_at_3
      value: 9.45
    - type: map_at_5
      value: 10.92
    - type: map_at_10
      value: 12.758
    - type: map_at_20
      value: 14.036999999999999
    - type: map_at_100
      value: 15.93
    - type: map_at_1000
      value: 17.422
    - type: recall_at_1
      value: 5.452
    - type: recall_at_3
      value: 10.732999999999999
    - type: recall_at_5
      value: 13.553
    - type: recall_at_10
      value: 17.119999999999997
    - type: recall_at_20
      value: 20.459
    - type: recall_at_100
      value: 30.719
    - type: recall_at_1000
      value: 62.766
    - type: precision_at_1
      value: 43.344
    - type: precision_at_3
      value: 37.152
    - type: precision_at_5
      value: 31.703
    - type: precision_at_10
      value: 24.799
    - type: precision_at_20
      value: 18.142
    - type: precision_at_100
      value: 7.8950000000000005
    - type: precision_at_1000
      value: 2.091
    - type: mrr_at_1
      value: 43.3437
    - type: mrr_at_3
      value: 51.135200000000005
    - type: mrr_at_5
      value: 52.15689999999999
    - type: mrr_at_10
      value: 52.9277
    - type: mrr_at_20
      value: 53.2931
    - type: mrr_at_100
      value: 53.467200000000005
    - type: mrr_at_1000
      value: 53.5122
    - type: nauc_ndcg_at_1_max
      value: 33.6844
    - type: nauc_ndcg_at_1_std
      value: 17.6117
    - type: nauc_ndcg_at_1_diff1
      value: 37.641999999999996
    - type: nauc_ndcg_at_3_max
      value: 36.6302
    - type: nauc_ndcg_at_3_std
      value: 25.738
    - type: nauc_ndcg_at_3_diff1
      value: 29.8566
    - type: nauc_ndcg_at_5_max
      value: 39.043099999999995
    - type: nauc_ndcg_at_5_std
      value: 28.904999999999998
    - type: nauc_ndcg_at_5_diff1
      value: 26.129400000000004
    - type: nauc_ndcg_at_10_max
      value: 38.935199999999995
    - type: nauc_ndcg_at_10_std
      value: 30.338700000000003
    - type: nauc_ndcg_at_10_diff1
      value: 23.594
    - type: nauc_ndcg_at_20_max
      value: 38.2138
    - type: nauc_ndcg_at_20_std
      value: 31.8994
    - type: nauc_ndcg_at_20_diff1
      value: 21.583
    - type: nauc_ndcg_at_100_max
      value: 39.869
    - type: nauc_ndcg_at_100_std
      value: 33.591300000000004
    - type: nauc_ndcg_at_100_diff1
      value: 23.0398
    - type: nauc_ndcg_at_1000_max
      value: 44.9572
    - type: nauc_ndcg_at_1000_std
      value: 38.222
    - type: nauc_ndcg_at_1000_diff1
      value: 23.7314
    - type: nauc_map_at_1_max
      value: 8.0309
    - type: nauc_map_at_1_std
      value: -12.6861
    - type: nauc_map_at_1_diff1
      value: 45.5924
    - type: nauc_map_at_3_max
      value: 11.8264
    - type: nauc_map_at_3_std
      value: -7.3325000000000005
    - type: nauc_map_at_3_diff1
      value: 35.5714
    - type: nauc_map_at_5_max
      value: 15.7483
    - type: nauc_map_at_5_std
      value: -2.9122
    - type: nauc_map_at_5_diff1
      value: 32.2211
    - type: nauc_map_at_10_max
      value: 19.9795
    - type: nauc_map_at_10_std
      value: 2.6611
    - type: nauc_map_at_10_diff1
      value: 29.047099999999997
    - type: nauc_map_at_20_max
      value: 23.1754
    - type: nauc_map_at_20_std
      value: 8.0668
    - type: nauc_map_at_20_diff1
      value: 27.7477
    - type: nauc_map_at_100_max
      value: 26.4818
    - type: nauc_map_at_100_std
      value: 15.723
    - type: nauc_map_at_100_diff1
      value: 26.5443
    - type: nauc_map_at_1000_max
      value: 27.929100000000002
    - type: nauc_map_at_1000_std
      value: 19.81
    - type: nauc_map_at_1000_diff1
      value: 25.0603
    - type: nauc_recall_at_1_max
      value: 8.0309
    - type: nauc_recall_at_1_std
      value: -12.6861
    - type: nauc_recall_at_1_diff1
      value: 45.5924
    - type: nauc_recall_at_3_max
      value: 10.9894
    - type: nauc_recall_at_3_std
      value: -7.4279
    - type: nauc_recall_at_3_diff1
      value: 29.917899999999996
    - type: nauc_recall_at_5_max
      value: 15.7163
    - type: nauc_recall_at_5_std
      value: -0.8366
    - type: nauc_recall_at_5_diff1
      value: 22.8634
    - type: nauc_recall_at_10_max
      value: 19.5902
    - type: nauc_recall_at_10_std
      value: 5.3492
    - type: nauc_recall_at_10_diff1
      value: 19.4157
    - type: nauc_recall_at_20_max
      value: 23.1894
    - type: nauc_recall_at_20_std
      value: 12.8919
    - type: nauc_recall_at_20_diff1
      value: 17.8387
    - type: nauc_recall_at_100_max
      value: 30.150399999999998
    - type: nauc_recall_at_100_std
      value: 27.5036
    - type: nauc_recall_at_100_diff1
      value: 15.4935
    - type: nauc_recall_at_1000_max
      value: 32.404500000000006
    - type: nauc_recall_at_1000_std
      value: 30.7325
    - type: nauc_recall_at_1000_diff1
      value: 13.9299
    - type: nauc_precision_at_1_max
      value: 34.747699999999995
    - type: nauc_precision_at_1_std
      value: 17.5475
    - type: nauc_precision_at_1_diff1
      value: 36.0582
    - type: nauc_precision_at_3_max
      value: 39.8251
    - type: nauc_precision_at_3_std
      value: 34.3835
    - type: nauc_precision_at_3_diff1
      value: 19.651699999999998
    - type: nauc_precision_at_5_max
      value: 42.796800000000005
    - type: nauc_precision_at_5_std
      value: 40.083999999999996
    - type: nauc_precision_at_5_diff1
      value: 12.4069
    - type: nauc_precision_at_10_max
      value: 41.562599999999996
    - type: nauc_precision_at_10_std
      value: 44.7888
    - type: nauc_precision_at_10_diff1
      value: 5.587000000000001
    - type: nauc_precision_at_20_max
      value: 37.000499999999995
    - type: nauc_precision_at_20_std
      value: 50.4486
    - type: nauc_precision_at_20_diff1
      value: -0.1011
    - type: nauc_precision_at_100_max
      value: 24.7635
    - type: nauc_precision_at_100_std
      value: 51.001200000000004
    - type: nauc_precision_at_100_diff1
      value: -7.7414
    - type: nauc_precision_at_1000_max
      value: 10.837900000000001
    - type: nauc_precision_at_1000_std
      value: 37.2421
    - type: nauc_precision_at_1000_diff1
      value: -14.086599999999999
    - type: nauc_mrr_at_1_max
      value: 34.747699999999995
    - type: nauc_mrr_at_1_std
      value: 17.5475
    - type: nauc_mrr_at_1_diff1
      value: 36.0582
    - type: nauc_mrr_at_3_max
      value: 40.8392
    - type: nauc_mrr_at_3_std
      value: 24.9403
    - type: nauc_mrr_at_3_diff1
      value: 33.9575
    - type: nauc_mrr_at_5_max
      value: 42.2108
    - type: nauc_mrr_at_5_std
      value: 26.374799999999997
    - type: nauc_mrr_at_5_diff1
      value: 33.8034
    - type: nauc_mrr_at_10_max
      value: 42.180800000000005
    - type: nauc_mrr_at_10_std
      value: 26.6843
    - type: nauc_mrr_at_10_diff1
      value: 33.151
    - type: nauc_mrr_at_20_max
      value: 42.4685
    - type: nauc_mrr_at_20_std
      value: 27.1065
    - type: nauc_mrr_at_20_diff1
      value: 33.0052
    - type: nauc_mrr_at_100_max
      value: 42.417
    - type: nauc_mrr_at_100_std
      value: 27.069300000000002
    - type: nauc_mrr_at_100_diff1
      value: 33.1211
    - type: nauc_mrr_at_1000_max
      value: 42.3902
    - type: nauc_mrr_at_1000_std
      value: 27.019
    - type: nauc_mrr_at_1000_diff1
      value: 33.1177
    - type: main_score
      value: 33.737
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB NQ (default)
      revision: b774495ed302d8c44a3a7ea25c90dbce03968f31
      split: test
      type: mteb/nq
    metrics:
    - type: ndcg_at_1
      value: 32.793
    - type: ndcg_at_3
      value: 42.782
    - type: ndcg_at_5
      value: 47.554
    - type: ndcg_at_10
      value: 51.63100000000001
    - type: ndcg_at_20
      value: 54.005
    - type: ndcg_at_100
      value: 56.287
    - type: ndcg_at_1000
      value: 56.949000000000005
    - type: map_at_1
      value: 29.022
    - type: map_at_3
      value: 39.045
    - type: map_at_5
      value: 41.86
    - type: map_at_10
      value: 43.730000000000004
    - type: map_at_20
      value: 44.478
    - type: map_at_100
      value: 44.849
    - type: map_at_1000
      value: 44.877
    - type: recall_at_1
      value: 29.022
    - type: recall_at_3
      value: 50.40599999999999
    - type: recall_at_5
      value: 61.45
    - type: recall_at_10
      value: 73.32499999999999
    - type: recall_at_20
      value: 82.06099999999999
    - type: recall_at_100
      value: 93.455
    - type: recall_at_1000
      value: 98.414
    - type: precision_at_1
      value: 32.793
    - type: precision_at_3
      value: 19.583000000000002
    - type: precision_at_5
      value: 14.484
    - type: precision_at_10
      value: 8.737
    - type: precision_at_20
      value: 4.928
    - type: precision_at_100
      value: 1.134
    - type: precision_at_1000
      value: 0.12
    - type: mrr_at_1
      value: 32.821600000000004
    - type: mrr_at_3
      value: 42.275
    - type: mrr_at_5
      value: 44.7895
    - type: mrr_at_10
      value: 46.2574
    - type: mrr_at_20
      value: 46.8249
    - type: mrr_at_100
      value: 47.0971
    - type: mrr_at_1000
      value: 47.1157
    - type: nauc_ndcg_at_1_max
      value: 23.167299999999997
    - type: nauc_ndcg_at_1_std
      value: -4.5794
    - type: nauc_ndcg_at_1_diff1
      value: 31.1021
    - type: nauc_ndcg_at_3_max
      value: 27.1071
    - type: nauc_ndcg_at_3_std
      value: -4.8229
    - type: nauc_ndcg_at_3_diff1
      value: 26.442
    - type: nauc_ndcg_at_5_max
      value: 29.579
    - type: nauc_ndcg_at_5_std
      value: -3.9125
    - type: nauc_ndcg_at_5_diff1
      value: 26.1946
    - type: nauc_ndcg_at_10_max
      value: 30.6847
    - type: nauc_ndcg_at_10_std
      value: -2.3781
    - type: nauc_ndcg_at_10_diff1
      value: 25.9597
    - type: nauc_ndcg_at_20_max
      value: 31.4414
    - type: nauc_ndcg_at_20_std
      value: -0.6708000000000001
    - type: nauc_ndcg_at_20_diff1
      value: 25.886300000000002
    - type: nauc_ndcg_at_100_max
      value: 30.5333
    - type: nauc_ndcg_at_100_std
      value: -0.605
    - type: nauc_ndcg_at_100_diff1
      value: 26.3173
    - type: nauc_ndcg_at_1000_max
      value: 29.6714
    - type: nauc_ndcg_at_1000_std
      value: -1.4797
    - type: nauc_ndcg_at_1000_diff1
      value: 26.4662
    - type: nauc_map_at_1_max
      value: 22.0826
    - type: nauc_map_at_1_std
      value: -7.1051
    - type: nauc_map_at_1_diff1
      value: 31.398
    - type: nauc_map_at_3_max
      value: 26.0631
    - type: nauc_map_at_3_std
      value: -5.564100000000001
    - type: nauc_map_at_3_diff1
      value: 27.4542
    - type: nauc_map_at_5_max
      value: 27.4859
    - type: nauc_map_at_5_std
      value: -5.1595
    - type: nauc_map_at_5_diff1
      value: 27.4557
    - type: nauc_map_at_10_max
      value: 27.9754
    - type: nauc_map_at_10_std
      value: -4.4186000000000005
    - type: nauc_map_at_10_diff1
      value: 27.3476
    - type: nauc_map_at_20_max
      value: 28.168
    - type: nauc_map_at_20_std
      value: -3.8931
    - type: nauc_map_at_20_diff1
      value: 27.333800000000004
    - type: nauc_map_at_100_max
      value: 28.020899999999997
    - type: nauc_map_at_100_std
      value: -3.8826
    - type: nauc_map_at_100_diff1
      value: 27.411099999999998
    - type: nauc_map_at_1000_max
      value: 27.9917
    - type: nauc_map_at_1000_std
      value: -3.9068
    - type: nauc_map_at_1000_diff1
      value: 27.4158
    - type: nauc_recall_at_1_max
      value: 22.0826
    - type: nauc_recall_at_1_std
      value: -7.1051
    - type: nauc_recall_at_1_diff1
      value: 31.398
    - type: nauc_recall_at_3_max
      value: 29.145500000000002
    - type: nauc_recall_at_3_std
      value: -4.3699
    - type: nauc_recall_at_3_diff1
      value: 22.868
    - type: nauc_recall_at_5_max
      value: 35.4075
    - type: nauc_recall_at_5_std
      value: -2.0428
    - type: nauc_recall_at_5_diff1
      value: 21.4863
    - type: nauc_recall_at_10_max
      value: 41.0673
    - type: nauc_recall_at_10_std
      value: 3.6994
    - type: nauc_recall_at_10_diff1
      value: 19.2556
    - type: nauc_recall_at_20_max
      value: 50.6702
    - type: nauc_recall_at_20_std
      value: 16.162399999999998
    - type: nauc_recall_at_20_diff1
      value: 16.9676
    - type: nauc_recall_at_100_max
      value: 64.5925
    - type: nauc_recall_at_100_std
      value: 42.2234
    - type: nauc_recall_at_100_diff1
      value: 12.741
    - type: nauc_recall_at_1000_max
      value: 66.29310000000001
    - type: nauc_recall_at_1000_std
      value: 61.5236
    - type: nauc_recall_at_1000_diff1
      value: -6.1148
    - type: nauc_precision_at_1_max
      value: 23.167299999999997
    - type: nauc_precision_at_1_std
      value: -4.5794
    - type: nauc_precision_at_1_diff1
      value: 31.1021
    - type: nauc_precision_at_3_max
      value: 28.3464
    - type: nauc_precision_at_3_std
      value: -0.0571
    - type: nauc_precision_at_3_diff1
      value: 18.987399999999997
    - type: nauc_precision_at_5_max
      value: 30.9637
    - type: nauc_precision_at_5_std
      value: 2.3625
    - type: nauc_precision_at_5_diff1
      value: 15.912299999999998
    - type: nauc_precision_at_10_max
      value: 28.3203
    - type: nauc_precision_at_10_std
      value: 8.2947
    - type: nauc_precision_at_10_diff1
      value: 10.066899999999999
    - type: nauc_precision_at_20_max
      value: 26.2198
    - type: nauc_precision_at_20_std
      value: 15.4182
    - type: nauc_precision_at_20_diff1
      value: 5.0011
    - type: nauc_precision_at_100_max
      value: 12.721599999999999
    - type: nauc_precision_at_100_std
      value: 18.2616
    - type: nauc_precision_at_100_diff1
      value: -1.5249000000000001
    - type: nauc_precision_at_1000_max
      value: 1.514
    - type: nauc_precision_at_1000_std
      value: 12.6332
    - type: nauc_precision_at_1000_diff1
      value: -4.8346
    - type: nauc_mrr_at_1_max
      value: 23.3079
    - type: nauc_mrr_at_1_std
      value: -4.6507
    - type: nauc_mrr_at_1_diff1
      value: 31.014999999999997
    - type: nauc_mrr_at_3_max
      value: 26.371299999999998
    - type: nauc_mrr_at_3_std
      value: -3.6183
    - type: nauc_mrr_at_3_diff1
      value: 27.5342
    - type: nauc_mrr_at_5_max
      value: 27.4604
    - type: nauc_mrr_at_5_std
      value: -2.9482
    - type: nauc_mrr_at_5_diff1
      value: 27.308100000000003
    - type: nauc_mrr_at_10_max
      value: 27.6781
    - type: nauc_mrr_at_10_std
      value: -2.5515
    - type: nauc_mrr_at_10_diff1
      value: 27.338
    - type: nauc_mrr_at_20_max
      value: 27.760099999999998
    - type: nauc_mrr_at_20_std
      value: -2.2787
    - type: nauc_mrr_at_20_diff1
      value: 27.372200000000003
    - type: nauc_mrr_at_100_max
      value: 27.6611
    - type: nauc_mrr_at_100_std
      value: -2.3218
    - type: nauc_mrr_at_100_diff1
      value: 27.444000000000003
    - type: nauc_mrr_at_1000_max
      value: 27.6393
    - type: nauc_mrr_at_1000_std
      value: -2.3404000000000003
    - type: nauc_mrr_at_1000_diff1
      value: 27.4444
    - type: main_score
      value: 51.63100000000001
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB QuoraRetrieval (default)
      revision: e4e08e0b7dbe3c8700f0daef558ff32256715259
      split: test
      type: mteb/quora
    metrics:
    - type: ndcg_at_1
      value: 79.36999999999999
    - type: ndcg_at_3
      value: 83.545
    - type: ndcg_at_5
      value: 85.32
    - type: ndcg_at_10
      value: 86.696
    - type: ndcg_at_20
      value: 87.46199999999999
    - type: ndcg_at_100
      value: 88.103
    - type: ndcg_at_1000
      value: 88.252
    - type: map_at_1
      value: 68.961
    - type: map_at_3
      value: 79.616
    - type: map_at_5
      value: 81.54
    - type: map_at_10
      value: 82.65400000000001
    - type: map_at_20
      value: 83.098
    - type: map_at_100
      value: 83.33
    - type: map_at_1000
      value: 83.34899999999999
    - type: recall_at_1
      value: 68.961
    - type: recall_at_3
      value: 85.501
    - type: recall_at_5
      value: 90.379
    - type: recall_at_10
      value: 94.407
    - type: recall_at_20
      value: 96.86399999999999
    - type: recall_at_100
      value: 99.226
    - type: recall_at_1000
      value: 99.958
    - type: precision_at_1
      value: 79.36999999999999
    - type: precision_at_3
      value: 36.35
    - type: precision_at_5
      value: 24.048
    - type: precision_at_10
      value: 13.145000000000001
    - type: precision_at_20
      value: 7.007
    - type: precision_at_100
      value: 1.517
    - type: precision_at_1000
      value: 0.156
    - type: mrr_at_1
      value: 79.3
    - type: mrr_at_3
      value: 84.82169999999999
    - type: mrr_at_5
      value: 85.6047
    - type: mrr_at_10
      value: 85.94500000000001
    - type: mrr_at_20
      value: 86.0381
    - type: mrr_at_100
      value: 86.0694
    - type: mrr_at_1000
      value: 86.0712
    - type: nauc_ndcg_at_1_max
      value: 37.962
    - type: nauc_ndcg_at_1_std
      value: -32.129999999999995
    - type: nauc_ndcg_at_1_diff1
      value: 76.2543
    - type: nauc_ndcg_at_3_max
      value: 36.5568
    - type: nauc_ndcg_at_3_std
      value: -36.9639
    - type: nauc_ndcg_at_3_diff1
      value: 74.33229999999999
    - type: nauc_ndcg_at_5_max
      value: 36.6236
    - type: nauc_ndcg_at_5_std
      value: -38.3823
    - type: nauc_ndcg_at_5_diff1
      value: 74.8725
    - type: nauc_ndcg_at_10_max
      value: 37.2726
    - type: nauc_ndcg_at_10_std
      value: -37.6889
    - type: nauc_ndcg_at_10_diff1
      value: 75.437
    - type: nauc_ndcg_at_20_max
      value: 37.3643
    - type: nauc_ndcg_at_20_std
      value: -36.4545
    - type: nauc_ndcg_at_20_diff1
      value: 75.3032
    - type: nauc_ndcg_at_100_max
      value: 37.701
    - type: nauc_ndcg_at_100_std
      value: -34.6794
    - type: nauc_ndcg_at_100_diff1
      value: 75.1545
    - type: nauc_ndcg_at_1000_max
      value: 37.7386
    - type: nauc_ndcg_at_1000_std
      value: -34.659099999999995
    - type: nauc_ndcg_at_1000_diff1
      value: 75.1303
    - type: nauc_map_at_1_max
      value: 28.3786
    - type: nauc_map_at_1_std
      value: -34.4402
    - type: nauc_map_at_1_diff1
      value: 78.58579999999999
    - type: nauc_map_at_3_max
      value: 34.1617
    - type: nauc_map_at_3_std
      value: -39.0191
    - type: nauc_map_at_3_diff1
      value: 75.551
    - type: nauc_map_at_5_max
      value: 35.2348
    - type: nauc_map_at_5_std
      value: -39.352399999999996
    - type: nauc_map_at_5_diff1
      value: 75.45530000000001
    - type: nauc_map_at_10_max
      value: 36.0009
    - type: nauc_map_at_10_std
      value: -38.389
    - type: nauc_map_at_10_diff1
      value: 75.523
    - type: nauc_map_at_20_max
      value: 36.167300000000004
    - type: nauc_map_at_20_std
      value: -37.5191
    - type: nauc_map_at_20_diff1
      value: 75.3798
    - type: nauc_map_at_100_max
      value: 36.2928
    - type: nauc_map_at_100_std
      value: -36.8001
    - type: nauc_map_at_100_diff1
      value: 75.2957
    - type: nauc_map_at_1000_max
      value: 36.3027
    - type: nauc_map_at_1000_std
      value: -36.7641
    - type: nauc_map_at_1000_diff1
      value: 75.29090000000001
    - type: nauc_recall_at_1_max
      value: 28.3786
    - type: nauc_recall_at_1_std
      value: -34.4402
    - type: nauc_recall_at_1_diff1
      value: 78.58579999999999
    - type: nauc_recall_at_3_max
      value: 32.1082
    - type: nauc_recall_at_3_std
      value: -43.2936
    - type: nauc_recall_at_3_diff1
      value: 71.4939
    - type: nauc_recall_at_5_max
      value: 32.590599999999995
    - type: nauc_recall_at_5_std
      value: -48.7416
    - type: nauc_recall_at_5_diff1
      value: 70.7945
    - type: nauc_recall_at_10_max
      value: 34.755
    - type: nauc_recall_at_10_std
      value: -49.398599999999995
    - type: nauc_recall_at_10_diff1
      value: 71.87219999999999
    - type: nauc_recall_at_20_max
      value: 33.879999999999995
    - type: nauc_recall_at_20_std
      value: -45.1325
    - type: nauc_recall_at_20_diff1
      value: 71.3805
    - type: nauc_recall_at_100_max
      value: 37.4684
    - type: nauc_recall_at_100_std
      value: -13.0134
    - type: nauc_recall_at_100_diff1
      value: 69.963
    - type: nauc_recall_at_1000_max
      value: 31.6199
    - type: nauc_recall_at_1000_std
      value: 59.0228
    - type: nauc_recall_at_1000_diff1
      value: 60.9687
    - type: nauc_precision_at_1_max
      value: 37.962
    - type: nauc_precision_at_1_std
      value: -32.129999999999995
    - type: nauc_precision_at_1_diff1
      value: 76.2543
    - type: nauc_precision_at_3_max
      value: 11.419799999999999
    - type: nauc_precision_at_3_std
      value: 2.5604999999999998
    - type: nauc_precision_at_3_diff1
      value: -11.505799999999999
    - type: nauc_precision_at_5_max
      value: 4.454700000000001
    - type: nauc_precision_at_5_std
      value: 11.6986
    - type: nauc_precision_at_5_diff1
      value: -26.2868
    - type: nauc_precision_at_10_max
      value: -0.4261
    - type: nauc_precision_at_10_std
      value: 20.7877
    - type: nauc_precision_at_10_diff1
      value: -34.5624
    - type: nauc_precision_at_20_max
      value: -3.7817000000000003
    - type: nauc_precision_at_20_std
      value: 27.056599999999996
    - type: nauc_precision_at_20_diff1
      value: -39.0052
    - type: nauc_precision_at_100_max
      value: -6.4321
    - type: nauc_precision_at_100_std
      value: 33.1245
    - type: nauc_precision_at_100_diff1
      value: -41.9135
    - type: nauc_precision_at_1000_max
      value: -7.100199999999999
    - type: nauc_precision_at_1000_std
      value: 34.0081
    - type: nauc_precision_at_1000_diff1
      value: -42.556
    - type: nauc_mrr_at_1_max
      value: 37.754
    - type: nauc_mrr_at_1_std
      value: -32.2644
    - type: nauc_mrr_at_1_diff1
      value: 76.4182
    - type: nauc_mrr_at_3_max
      value: 38.7583
    - type: nauc_mrr_at_3_std
      value: -33.631699999999995
    - type: nauc_mrr_at_3_diff1
      value: 75.30369999999999
    - type: nauc_mrr_at_5_max
      value: 38.675399999999996
    - type: nauc_mrr_at_5_std
      value: -33.873
    - type: nauc_mrr_at_5_diff1
      value: 75.58890000000001
    - type: nauc_mrr_at_10_max
      value: 38.7962
    - type: nauc_mrr_at_10_std
      value: -33.5451
    - type: nauc_mrr_at_10_diff1
      value: 75.7153
    - type: nauc_mrr_at_20_max
      value: 38.7213
    - type: nauc_mrr_at_20_std
      value: -33.433600000000006
    - type: nauc_mrr_at_20_diff1
      value: 75.6934
    - type: nauc_mrr_at_100_max
      value: 38.6943
    - type: nauc_mrr_at_100_std
      value: -33.4013
    - type: nauc_mrr_at_100_diff1
      value: 75.6932
    - type: nauc_mrr_at_1000_max
      value: 38.6928
    - type: nauc_mrr_at_1000_std
      value: -33.4051
    - type: nauc_mrr_at_1000_diff1
      value: 75.69369999999999
    - type: main_score
      value: 86.696
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB RedditClustering (default)
      revision: 24640382cdbf8abc73003fb0fa6d111a705499eb
      split: test
      type: mteb/reddit-clustering
    metrics:
    - type: v_measure
      value: 50.019999999999996
    - type: v_measure_std
      value: 4.5914
    - type: main_score
      value: 50.019999999999996
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB RedditClusteringP2P (default)
      revision: 385e3cb46b4cfa89021f56c4380204149d0efe33
      split: test
      type: mteb/reddit-clustering-p2p
    metrics:
    - type: v_measure
      value: 53.9756
    - type: v_measure_std
      value: 11.6573
    - type: main_score
      value: 53.9756
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB SCIDOCS (default)
      revision: f8c2fcf00f625baaa80f62ec5bd9e1fff3b8ae88
      split: test
      type: mteb/scidocs
    metrics:
    - type: ndcg_at_1
      value: 24.6
    - type: ndcg_at_3
      value: 20.896
    - type: ndcg_at_5
      value: 18.497
    - type: ndcg_at_10
      value: 22.542
    - type: ndcg_at_20
      value: 25.812
    - type: ndcg_at_100
      value: 32.326
    - type: ndcg_at_1000
      value: 38.279999999999994
    - type: map_at_1
      value: 4.988
    - type: map_at_3
      value: 9.439
    - type: map_at_5
      value: 11.459999999999999
    - type: map_at_10
      value: 13.553
    - type: map_at_20
      value: 14.767
    - type: map_at_100
      value: 16.136
    - type: map_at_1000
      value: 16.512
    - type: recall_at_1
      value: 4.988
    - type: recall_at_3
      value: 12.046999999999999
    - type: recall_at_5
      value: 16.777
    - type: recall_at_10
      value: 24.212
    - type: recall_at_20
      value: 31.885
    - type: recall_at_100
      value: 53.105000000000004
    - type: recall_at_1000
      value: 82.02199999999999
    - type: precision_at_1
      value: 24.6
    - type: precision_at_3
      value: 19.8
    - type: precision_at_5
      value: 16.54
    - type: precision_at_10
      value: 11.940000000000001
    - type: precision_at_20
      value: 7.865
    - type: precision_at_100
      value: 2.616
    - type: precision_at_1000
      value: 0.404
    - type: mrr_at_1
      value: 24.6
    - type: mrr_at_3
      value: 33.1167
    - type: mrr_at_5
      value: 35.1717
    - type: mrr_at_10
      value: 36.7925
    - type: mrr_at_20
      value: 37.5284
    - type: mrr_at_100
      value: 37.9725
    - type: mrr_at_1000
      value: 38.0112
    - type: nauc_ndcg_at_1_max
      value: 17.8923
    - type: nauc_ndcg_at_1_std
      value: 9.1225
    - type: nauc_ndcg_at_1_diff1
      value: 22.665399999999998
    - type: nauc_ndcg_at_3_max
      value: 23.6866
    - type: nauc_ndcg_at_3_std
      value: 15.3093
    - type: nauc_ndcg_at_3_diff1
      value: 17.589299999999998
    - type: nauc_ndcg_at_5_max
      value: 25.3398
    - type: nauc_ndcg_at_5_std
      value: 18.002299999999998
    - type: nauc_ndcg_at_5_diff1
      value: 16.8155
    - type: nauc_ndcg_at_10_max
      value: 28.057399999999998
    - type: nauc_ndcg_at_10_std
      value: 22.7388
    - type: nauc_ndcg_at_10_diff1
      value: 16.0553
    - type: nauc_ndcg_at_20_max
      value: 28.9134
    - type: nauc_ndcg_at_20_std
      value: 25.389
    - type: nauc_ndcg_at_20_diff1
      value: 15.7728
    - type: nauc_ndcg_at_100_max
      value: 29.9553
    - type: nauc_ndcg_at_100_std
      value: 29.8607
    - type: nauc_ndcg_at_100_diff1
      value: 15.526100000000001
    - type: nauc_ndcg_at_1000_max
      value: 29.088399999999996
    - type: nauc_ndcg_at_1000_std
      value: 29.2896
    - type: nauc_ndcg_at_1000_diff1
      value: 15.2143
    - type: nauc_map_at_1_max
      value: 17.9628
    - type: nauc_map_at_1_std
      value: 8.9923
    - type: nauc_map_at_1_diff1
      value: 22.7227
    - type: nauc_map_at_3_max
      value: 24.012700000000002
    - type: nauc_map_at_3_std
      value: 15.1908
    - type: nauc_map_at_3_diff1
      value: 17.7637
    - type: nauc_map_at_5_max
      value: 25.0497
    - type: nauc_map_at_5_std
      value: 17.366300000000003
    - type: nauc_map_at_5_diff1
      value: 16.1512
    - type: nauc_map_at_10_max
      value: 26.777299999999997
    - type: nauc_map_at_10_std
      value: 21.0365
    - type: nauc_map_at_10_diff1
      value: 15.0999
    - type: nauc_map_at_20_max
      value: 27.6561
    - type: nauc_map_at_20_std
      value: 23.031399999999998
    - type: nauc_map_at_20_diff1
      value: 14.935300000000002
    - type: nauc_map_at_100_max
      value: 28.015800000000002
    - type: nauc_map_at_100_std
      value: 24.840899999999998
    - type: nauc_map_at_100_diff1
      value: 14.9355
    - type: nauc_map_at_1000_max
      value: 27.9646
    - type: nauc_map_at_1000_std
      value: 24.9601
    - type: nauc_map_at_1000_diff1
      value: 14.886
    - type: nauc_recall_at_1_max
      value: 17.9628
    - type: nauc_recall_at_1_std
      value: 8.9923
    - type: nauc_recall_at_1_diff1
      value: 22.7227
    - type: nauc_recall_at_3_max
      value: 25.008399999999998
    - type: nauc_recall_at_3_std
      value: 17.1697
    - type: nauc_recall_at_3_diff1
      value: 15.1082
    - type: nauc_recall_at_5_max
      value: 26.4345
    - type: nauc_recall_at_5_std
      value: 20.7923
    - type: nauc_recall_at_5_diff1
      value: 13.58
    - type: nauc_recall_at_10_max
      value: 29.5057
    - type: nauc_recall_at_10_std
      value: 27.8646
    - type: nauc_recall_at_10_diff1
      value: 11.8098
    - type: nauc_recall_at_20_max
      value: 29.3419
    - type: nauc_recall_at_20_std
      value: 31.6086
    - type: nauc_recall_at_20_diff1
      value: 10.6491
    - type: nauc_recall_at_100_max
      value: 28.8421
    - type: nauc_recall_at_100_std
      value: 40.2696
    - type: nauc_recall_at_100_diff1
      value: 8.1461
    - type: nauc_recall_at_1000_max
      value: 22.8234
    - type: nauc_recall_at_1000_std
      value: 41.6117
    - type: nauc_recall_at_1000_diff1
      value: 1.8689999999999998
    - type: nauc_precision_at_1_max
      value: 17.8923
    - type: nauc_precision_at_1_std
      value: 9.1225
    - type: nauc_precision_at_1_diff1
      value: 22.665399999999998
    - type: nauc_precision_at_3_max
      value: 25.1067
    - type: nauc_precision_at_3_std
      value: 17.4066
    - type: nauc_precision_at_3_diff1
      value: 15.0583
    - type: nauc_precision_at_5_max
      value: 26.6005
    - type: nauc_precision_at_5_std
      value: 20.9158
    - type: nauc_precision_at_5_diff1
      value: 13.591700000000001
    - type: nauc_precision_at_10_max
      value: 29.8091
    - type: nauc_precision_at_10_std
      value: 28.0069
    - type: nauc_precision_at_10_diff1
      value: 11.675699999999999
    - type: nauc_precision_at_20_max
      value: 29.5651
    - type: nauc_precision_at_20_std
      value: 31.439899999999998
    - type: nauc_precision_at_20_diff1
      value: 10.4784
    - type: nauc_precision_at_100_max
      value: 28.853299999999997
    - type: nauc_precision_at_100_std
      value: 39.3115
    - type: nauc_precision_at_100_diff1
      value: 7.6562
    - type: nauc_precision_at_1000_max
      value: 23.025599999999997
    - type: nauc_precision_at_1000_std
      value: 38.554300000000005
    - type: nauc_precision_at_1000_diff1
      value: 1.3502999999999998
    - type: nauc_mrr_at_1_max
      value: 17.8923
    - type: nauc_mrr_at_1_std
      value: 9.1225
    - type: nauc_mrr_at_1_diff1
      value: 22.665399999999998
    - type: nauc_mrr_at_3_max
      value: 21.2588
    - type: nauc_mrr_at_3_std
      value: 12.7528
    - type: nauc_mrr_at_3_diff1
      value: 19.808999999999997
    - type: nauc_mrr_at_5_max
      value: 22.572200000000002
    - type: nauc_mrr_at_5_std
      value: 14.210500000000001
    - type: nauc_mrr_at_5_diff1
      value: 20.502000000000002
    - type: nauc_mrr_at_10_max
      value: 23.372799999999998
    - type: nauc_mrr_at_10_std
      value: 15.1215
    - type: nauc_mrr_at_10_diff1
      value: 20.8449
    - type: nauc_mrr_at_20_max
      value: 23.017599999999998
    - type: nauc_mrr_at_20_std
      value: 15.0391
    - type: nauc_mrr_at_20_diff1
      value: 20.8233
    - type: nauc_mrr_at_100_max
      value: 22.8993
    - type: nauc_mrr_at_100_std
      value: 14.8474
    - type: nauc_mrr_at_100_diff1
      value: 20.8759
    - type: nauc_mrr_at_1000_max
      value: 22.8744
    - type: nauc_mrr_at_1000_std
      value: 14.8178
    - type: nauc_mrr_at_1000_diff1
      value: 20.8635
    - type: main_score
      value: 22.542
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB SICK-R (default)
      revision: 20a6d6f312dd54037fe07a32d58e5e168867909d
      split: test
      type: mteb/sickr-sts
    metrics:
    - type: pearson
      value: 77.4874
    - type: spearman
      value: 68.79809999999999
    - type: cosine_pearson
      value: 77.4874
    - type: cosine_spearman
      value: 68.79809999999999
    - type: manhattan_pearson
      value: 73.3583
    - type: manhattan_spearman
      value: 68.6911
    - type: euclidean_pearson
      value: 73.82039999999999
    - type: euclidean_spearman
      value: 68.79809999999999
    - type: main_score
      value: 68.79809999999999
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS12 (default)
      revision: a0d554a64d88156834ff5ae9920b964011b16384
      split: test
      type: mteb/sts12-sts
    metrics:
    - type: pearson
      value: 67.8391
    - type: spearman
      value: 64.77380000000001
    - type: cosine_pearson
      value: 67.8391
    - type: cosine_spearman
      value: 64.77380000000001
    - type: manhattan_pearson
      value: 64.7258
    - type: manhattan_spearman
      value: 64.1558
    - type: euclidean_pearson
      value: 65.68469999999999
    - type: euclidean_spearman
      value: 64.7722
    - type: main_score
      value: 64.77380000000001
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS13 (default)
      revision: 7e90230a92c190f1bf69ae9002b8cea547a64cca
      split: test
      type: mteb/sts13-sts
    metrics:
    - type: pearson
      value: 78.8177
    - type: spearman
      value: 79.3253
    - type: cosine_pearson
      value: 78.8177
    - type: cosine_spearman
      value: 79.3253
    - type: manhattan_pearson
      value: 78.6048
    - type: manhattan_spearman
      value: 79.1874
    - type: euclidean_pearson
      value: 78.71010000000001
    - type: euclidean_spearman
      value: 79.3253
    - type: main_score
      value: 79.3253
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS14 (default)
      revision: 6031580fec1f6af667f0bd2da0a551cf4f0b2375
      split: test
      type: mteb/sts14-sts
    metrics:
    - type: pearson
      value: 75.6791
    - type: spearman
      value: 70.1701
    - type: cosine_pearson
      value: 75.6791
    - type: cosine_spearman
      value: 70.1701
    - type: manhattan_pearson
      value: 73.85239999999999
    - type: manhattan_spearman
      value: 69.9223
    - type: euclidean_pearson
      value: 74.143
    - type: euclidean_spearman
      value: 70.1701
    - type: main_score
      value: 70.1701
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS15 (default)
      revision: ae752c7c21bf194d8b67fd573edf7ae58183cbe3
      split: test
      type: mteb/sts15-sts
    metrics:
    - type: pearson
      value: 80.4413
    - type: spearman
      value: 82.0343
    - type: cosine_pearson
      value: 80.4413
    - type: cosine_spearman
      value: 82.0343
    - type: manhattan_pearson
      value: 81.3627
    - type: manhattan_spearman
      value: 81.8838
    - type: euclidean_pearson
      value: 81.47569999999999
    - type: euclidean_spearman
      value: 82.0343
    - type: main_score
      value: 82.0343
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STS16 (default)
      revision: 4d8694f8f0e0100860b497b999b3dbed754a0513
      split: test
      type: mteb/sts16-sts
    metrics:
    - type: pearson
      value: 77.172
    - type: spearman
      value: 78.9633
    - type: cosine_pearson
      value: 77.172
    - type: cosine_spearman
      value: 78.9633
    - type: manhattan_pearson
      value: 78.35849999999999
    - type: manhattan_spearman
      value: 78.7975
    - type: euclidean_pearson
      value: 78.5236
    - type: euclidean_spearman
      value: 78.9633
    - type: main_score
      value: 78.9633
    task:
      type: STS
  - dataset:
      config: en-en
      name: MTEB STS17 (en-en)
      revision: faeb762787bd10488a50c8b5be4a3b82e411949c
      split: test
      type: mteb/sts17-crosslingual-sts
    metrics:
    - type: pearson
      value: 83.5117
    - type: spearman
      value: 84.64970000000001
    - type: cosine_pearson
      value: 83.5117
    - type: cosine_spearman
      value: 84.64970000000001
    - type: manhattan_pearson
      value: 84.5137
    - type: manhattan_spearman
      value: 84.7848
    - type: euclidean_pearson
      value: 84.531
    - type: euclidean_spearman
      value: 84.64970000000001
    - type: main_score
      value: 84.64970000000001
    task:
      type: STS
  - dataset:
      config: es-en
      name: MTEB STS17 (es-en)
      revision: faeb762787bd10488a50c8b5be4a3b82e411949c
      split: test
      type: mteb/sts17-crosslingual-sts
    metrics:
    - type: pearson
      value: 29.0052
    - type: spearman
      value: 30.640299999999996
    - type: cosine_pearson
      value: 29.0052
    - type: cosine_spearman
      value: 30.640299999999996
    - type: manhattan_pearson
      value: 25.988099999999996
    - type: manhattan_spearman
      value: 26.935399999999998
    - type: euclidean_pearson
      value: 28.5366
    - type: euclidean_spearman
      value: 30.640299999999996
    - type: main_score
      value: 30.640299999999996
    task:
      type: STS
  - dataset:
      config: nl-en
      name: MTEB STS17 (nl-en)
      revision: faeb762787bd10488a50c8b5be4a3b82e411949c
      split: test
      type: mteb/sts17-crosslingual-sts
    metrics:
    - type: pearson
      value: 42.0755
    - type: spearman
      value: 39.763999999999996
    - type: cosine_pearson
      value: 42.0755
    - type: cosine_spearman
      value: 39.763999999999996
    - type: manhattan_pearson
      value: 40.872
    - type: manhattan_spearman
      value: 38.4749
    - type: euclidean_pearson
      value: 42.051500000000004
    - type: euclidean_spearman
      value: 39.7565
    - type: main_score
      value: 39.763999999999996
    task:
      type: STS
  - dataset:
      config: en-de
      name: MTEB STS17 (en-de)
      revision: faeb762787bd10488a50c8b5be4a3b82e411949c
      split: test
      type: mteb/sts17-crosslingual-sts
    metrics:
    - type: pearson
      value: 44.2318
    - type: spearman
      value: 46.5518
    - type: cosine_pearson
      value: 44.2318
    - type: cosine_spearman
      value: 46.5518
    - type: manhattan_pearson
      value: 43.396699999999996
    - type: manhattan_spearman
      value: 46.1132
    - type: euclidean_pearson
      value: 43.993500000000004
    - type: euclidean_spearman
      value: 46.5518
    - type: main_score
      value: 46.5518
    task:
      type: STS
  - dataset:
      config: fr-en
      name: MTEB STS17 (fr-en)
      revision: faeb762787bd10488a50c8b5be4a3b82e411949c
      split: test
      type: mteb/sts17-crosslingual-sts
    metrics:
    - type: pearson
      value: 36.716100000000004
    - type: spearman
      value: 34.6968
    - type: cosine_pearson
      value: 36.716100000000004
    - type: cosine_spearman
      value: 34.6968
    - type: manhattan_pearson
      value: 35.1918
    - type: manhattan_spearman
      value: 33.3692
    - type: euclidean_pearson
      value: 36.3921
    - type: euclidean_spearman
      value: 34.6968
    - type: main_score
      value: 34.6968
    task:
      type: STS
  - dataset:
      config: en-ar
      name: MTEB STS17 (en-ar)
      revision: faeb762787bd10488a50c8b5be4a3b82e411949c
      split: test
      type: mteb/sts17-crosslingual-sts
    metrics:
    - type: pearson
      value: 21.2825
    - type: spearman
      value: 17.6922
    - type: cosine_pearson
      value: 21.2825
    - type: cosine_spearman
      value: 17.6922
    - type: manhattan_pearson
      value: 19.491
    - type: manhattan_spearman
      value: 15.989700000000001
    - type: euclidean_pearson
      value: 21.583
    - type: euclidean_spearman
      value: 17.6922
    - type: main_score
      value: 17.6922
    task:
      type: STS
  - dataset:
      config: it-en
      name: MTEB STS17 (it-en)
      revision: faeb762787bd10488a50c8b5be4a3b82e411949c
      split: test
      type: mteb/sts17-crosslingual-sts
    metrics:
    - type: pearson
      value: 32.1584
    - type: spearman
      value: 27.9254
    - type: cosine_pearson
      value: 32.1584
    - type: cosine_spearman
      value: 27.9254
    - type: manhattan_pearson
      value: 34.2047
    - type: manhattan_spearman
      value: 31.1955
    - type: euclidean_pearson
      value: 32.4369
    - type: euclidean_spearman
      value: 27.9254
    - type: main_score
      value: 27.9254
    task:
      type: STS
  - dataset:
      config: en-tr
      name: MTEB STS17 (en-tr)
      revision: faeb762787bd10488a50c8b5be4a3b82e411949c
      split: test
      type: mteb/sts17-crosslingual-sts
    metrics:
    - type: pearson
      value: 21.0842
    - type: spearman
      value: 18.5115
    - type: cosine_pearson
      value: 21.0842
    - type: cosine_spearman
      value: 18.5115
    - type: manhattan_pearson
      value: 23.5904
    - type: manhattan_spearman
      value: 21.032400000000003
    - type: euclidean_pearson
      value: 21.2805
    - type: euclidean_spearman
      value: 18.5115
    - type: main_score
      value: 18.5115
    task:
      type: STS
  - dataset:
      config: en
      name: MTEB STS22 (en)
      revision: de9d86b3b84231dc21f76c7b7af1f28e2f57f6e3
      split: test
      type: mteb/sts22-crosslingual-sts
    metrics:
    - type: pearson
      value: 66.9563
    - type: spearman
      value: 67.4747
    - type: cosine_pearson
      value: 66.9563
    - type: cosine_spearman
      value: 67.4747
    - type: manhattan_pearson
      value: 68.32629999999999
    - type: manhattan_spearman
      value: 66.8163
    - type: euclidean_pearson
      value: 68.731
    - type: euclidean_spearman
      value: 67.4747
    - type: main_score
      value: 67.4747
    task:
      type: STS
  - dataset:
      config: de-en
      name: MTEB STS22 (de-en)
      revision: de9d86b3b84231dc21f76c7b7af1f28e2f57f6e3
      split: test
      type: mteb/sts22-crosslingual-sts
    metrics:
    - type: pearson
      value: 56.3095
    - type: spearman
      value: 54.1005
    - type: cosine_pearson
      value: 56.3095
    - type: cosine_spearman
      value: 54.1005
    - type: manhattan_pearson
      value: 59.4023
    - type: manhattan_spearman
      value: 52.6259
    - type: euclidean_pearson
      value: 58.6527
    - type: euclidean_spearman
      value: 54.1005
    - type: main_score
      value: 54.1005
    task:
      type: STS
  - dataset:
      config: es-en
      name: MTEB STS22 (es-en)
      revision: de9d86b3b84231dc21f76c7b7af1f28e2f57f6e3
      split: test
      type: mteb/sts22-crosslingual-sts
    metrics:
    - type: pearson
      value: 62.0575
    - type: spearman
      value: 66.9527
    - type: cosine_pearson
      value: 62.0575
    - type: cosine_spearman
      value: 66.9527
    - type: manhattan_pearson
      value: 62.648700000000005
    - type: manhattan_spearman
      value: 65.6446
    - type: euclidean_pearson
      value: 63.546800000000005
    - type: euclidean_spearman
      value: 66.9527
    - type: main_score
      value: 66.9527
    task:
      type: STS
  - dataset:
      config: pl-en
      name: MTEB STS22 (pl-en)
      revision: de9d86b3b84231dc21f76c7b7af1f28e2f57f6e3
      split: test
      type: mteb/sts22-crosslingual-sts
    metrics:
    - type: pearson
      value: 68.42439999999999
    - type: spearman
      value: 69.0444
    - type: cosine_pearson
      value: 68.42439999999999
    - type: cosine_spearman
      value: 69.0444
    - type: manhattan_pearson
      value: 65.1492
    - type: manhattan_spearman
      value: 65.2364
    - type: euclidean_pearson
      value: 68.4923
    - type: euclidean_spearman
      value: 69.0444
    - type: main_score
      value: 69.0444
    task:
      type: STS
  - dataset:
      config: zh-en
      name: MTEB STS22 (zh-en)
      revision: de9d86b3b84231dc21f76c7b7af1f28e2f57f6e3
      split: test
      type: mteb/sts22-crosslingual-sts
    metrics:
    - type: pearson
      value: 34.164699999999996
    - type: spearman
      value: 36.1776
    - type: cosine_pearson
      value: 34.164699999999996
    - type: cosine_spearman
      value: 36.1776
    - type: manhattan_pearson
      value: 33.0685
    - type: manhattan_spearman
      value: 34.4054
    - type: euclidean_pearson
      value: 34.1002
    - type: euclidean_spearman
      value: 36.1776
    - type: main_score
      value: 36.1776
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB STSBenchmark (default)
      revision: b0fddb56ed78048fa8b90373c8a3cfc37b684831
      split: test
      type: mteb/stsbenchmark-sts
    metrics:
    - type: pearson
      value: 78.0802
    - type: spearman
      value: 78.0444
    - type: cosine_pearson
      value: 78.0802
    - type: cosine_spearman
      value: 78.0444
    - type: manhattan_pearson
      value: 78.0703
    - type: manhattan_spearman
      value: 77.681
    - type: euclidean_pearson
      value: 78.4998
    - type: euclidean_spearman
      value: 78.0444
    - type: main_score
      value: 78.0444
    task:
      type: STS
  - dataset:
      config: default
      name: MTEB SciDocsRR (default)
      revision: d3c5e1fc0b855ab6097bf1cda04dd73947d7caab
      split: test
      type: mteb/scidocs-reranking
    metrics:
    - type: map
      value: 86.4489
    - type: mrr
      value: 96.0178
    - type: nAUC_map_max
      value: 49.2333
    - type: nAUC_map_std
      value: 63.6541
    - type: nAUC_map_diff1
      value: 0.40959999999999996
    - type: nAUC_mrr_max
      value: 83.6216
    - type: nAUC_mrr_std
      value: 76.7559
    - type: nAUC_mrr_diff1
      value: 42.9429
    - type: main_score
      value: 86.4489
    task:
      type: Reranking
  - dataset:
      config: default
      name: MTEB SciFact (default)
      revision: 0228b52cf27578f30900b9e5271d331663a030d7
      split: test
      type: mteb/scifact
    metrics:
    - type: ndcg_at_1
      value: 59.333000000000006
    - type: ndcg_at_3
      value: 65.793
    - type: ndcg_at_5
      value: 69.429
    - type: ndcg_at_10
      value: 71.27
    - type: ndcg_at_20
      value: 72.929
    - type: ndcg_at_100
      value: 73.88900000000001
    - type: ndcg_at_1000
      value: 74.41
    - type: map_at_1
      value: 56.577999999999996
    - type: map_at_3
      value: 63.416
    - type: map_at_5
      value: 65.77
    - type: map_at_10
      value: 66.725
    - type: map_at_20
      value: 67.24799999999999
    - type: map_at_100
      value: 67.379
    - type: map_at_1000
      value: 67.4
    - type: recall_at_1
      value: 56.577999999999996
    - type: recall_at_3
      value: 70.072
    - type: recall_at_5
      value: 79.011
    - type: recall_at_10
      value: 84.2
    - type: recall_at_20
      value: 90.5
    - type: recall_at_100
      value: 95.667
    - type: recall_at_1000
      value: 99.667
    - type: precision_at_1
      value: 59.333000000000006
    - type: precision_at_3
      value: 25.556
    - type: precision_at_5
      value: 17.666999999999998
    - type: precision_at_10
      value: 9.6
    - type: precision_at_20
      value: 5.167
    - type: precision_at_100
      value: 1.087
    - type: precision_at_1000
      value: 0.11299999999999999
    - type: mrr_at_1
      value: 59.3333
    - type: mrr_at_3
      value: 64.9444
    - type: mrr_at_5
      value: 66.9278
    - type: mrr_at_10
      value: 67.5327
    - type: mrr_at_20
      value: 67.9354
    - type: mrr_at_100
      value: 68.0616
    - type: mrr_at_1000
      value: 68.08239999999999
    - type: nauc_ndcg_at_1_max
      value: 62.536199999999994
    - type: nauc_ndcg_at_1_std
      value: 4.3275
    - type: nauc_ndcg_at_1_diff1
      value: 78.2294
    - type: nauc_ndcg_at_3_max
      value: 63.0626
    - type: nauc_ndcg_at_3_std
      value: 6.0584
    - type: nauc_ndcg_at_3_diff1
      value: 74.4931
    - type: nauc_ndcg_at_5_max
      value: 64.73989999999999
    - type: nauc_ndcg_at_5_std
      value: 5.6514
    - type: nauc_ndcg_at_5_diff1
      value: 73.5498
    - type: nauc_ndcg_at_10_max
      value: 65.43090000000001
    - type: nauc_ndcg_at_10_std
      value: 9.1274
    - type: nauc_ndcg_at_10_diff1
      value: 72.4814
    - type: nauc_ndcg_at_20_max
      value: 65.7156
    - type: nauc_ndcg_at_20_std
      value: 9.9385
    - type: nauc_ndcg_at_20_diff1
      value: 73.0996
    - type: nauc_ndcg_at_100_max
      value: 65.5687
    - type: nauc_ndcg_at_100_std
      value: 8.818299999999999
    - type: nauc_ndcg_at_100_diff1
      value: 73.6361
    - type: nauc_ndcg_at_1000_max
      value: 65.1956
    - type: nauc_ndcg_at_1000_std
      value: 8.4772
    - type: nauc_ndcg_at_1000_diff1
      value: 74.0393
    - type: nauc_map_at_1_max
      value: 58.2314
    - type: nauc_map_at_1_std
      value: -2.7946
    - type: nauc_map_at_1_diff1
      value: 78.24940000000001
    - type: nauc_map_at_3_max
      value: 61.364200000000004
    - type: nauc_map_at_3_std
      value: 2.7072
    - type: nauc_map_at_3_diff1
      value: 75.4798
    - type: nauc_map_at_5_max
      value: 63.1297
    - type: nauc_map_at_5_std
      value: 3.9505
    - type: nauc_map_at_5_diff1
      value: 74.9693
    - type: nauc_map_at_10_max
      value: 63.6643
    - type: nauc_map_at_10_std
      value: 5.8328999999999995
    - type: nauc_map_at_10_diff1
      value: 74.5464
    - type: nauc_map_at_20_max
      value: 63.8666
    - type: nauc_map_at_20_std
      value: 6.1967
    - type: nauc_map_at_20_diff1
      value: 74.7224
    - type: nauc_map_at_100_max
      value: 63.8254
    - type: nauc_map_at_100_std
      value: 6.0627
    - type: nauc_map_at_100_diff1
      value: 74.791
    - type: nauc_map_at_1000_max
      value: 63.811499999999995
    - type: nauc_map_at_1000_std
      value: 6.0484
    - type: nauc_map_at_1000_diff1
      value: 74.807
    - type: nauc_recall_at_1_max
      value: 58.2314
    - type: nauc_recall_at_1_std
      value: -2.7946
    - type: nauc_recall_at_1_diff1
      value: 78.24940000000001
    - type: nauc_recall_at_3_max
      value: 61.132299999999994
    - type: nauc_recall_at_3_std
      value: 6.1988
    - type: nauc_recall_at_3_diff1
      value: 70.7273
    - type: nauc_recall_at_5_max
      value: 66.542
    - type: nauc_recall_at_5_std
      value: 5.7653
    - type: nauc_recall_at_5_diff1
      value: 66.4586
    - type: nauc_recall_at_10_max
      value: 69.3605
    - type: nauc_recall_at_10_std
      value: 19.6237
    - type: nauc_recall_at_10_diff1
      value: 60.2814
    - type: nauc_recall_at_20_max
      value: 72.6154
    - type: nauc_recall_at_20_std
      value: 31.3504
    - type: nauc_recall_at_20_diff1
      value: 58.8899
    - type: nauc_recall_at_100_max
      value: 78.6002
    - type: nauc_recall_at_100_std
      value: 26.484999999999996
    - type: nauc_recall_at_100_diff1
      value: 56.4605
    - type: nauc_recall_at_1000_max
      value: 55.415499999999994
    - type: nauc_recall_at_1000_std
      value: 72.2222
    - type: nauc_recall_at_1000_diff1
      value: 35.8077
    - type: nauc_precision_at_1_max
      value: 62.536199999999994
    - type: nauc_precision_at_1_std
      value: 4.3275
    - type: nauc_precision_at_1_diff1
      value: 78.2294
    - type: nauc_precision_at_3_max
      value: 53.5524
    - type: nauc_precision_at_3_std
      value: 23.5724
    - type: nauc_precision_at_3_diff1
      value: 47.5389
    - type: nauc_precision_at_5_max
      value: 49.1594
    - type: nauc_precision_at_5_std
      value: 32.3563
    - type: nauc_precision_at_5_diff1
      value: 28.2105
    - type: nauc_precision_at_10_max
      value: 41.955799999999996
    - type: nauc_precision_at_10_std
      value: 44.039699999999996
    - type: nauc_precision_at_10_diff1
      value: 12.0187
    - type: nauc_precision_at_20_max
      value: 34.2442
    - type: nauc_precision_at_20_std
      value: 50.204899999999995
    - type: nauc_precision_at_20_diff1
      value: -0.1954
    - type: nauc_precision_at_100_max
      value: 26.8264
    - type: nauc_precision_at_100_std
      value: 51.4247
    - type: nauc_precision_at_100_diff1
      value: -11.9827
    - type: nauc_precision_at_1000_max
      value: 17.467
    - type: nauc_precision_at_1000_std
      value: 56.435100000000006
    - type: nauc_precision_at_1000_diff1
      value: -24.2103
    - type: nauc_mrr_at_1_max
      value: 62.536199999999994
    - type: nauc_mrr_at_1_std
      value: 4.3275
    - type: nauc_mrr_at_1_diff1
      value: 78.2294
    - type: nauc_mrr_at_3_max
      value: 64.5911
    - type: nauc_mrr_at_3_std
      value: 7.8005
    - type: nauc_mrr_at_3_diff1
      value: 75.82140000000001
    - type: nauc_mrr_at_5_max
      value: 65.1643
    - type: nauc_mrr_at_5_std
      value: 7.258100000000001
    - type: nauc_mrr_at_5_diff1
      value: 75.2062
    - type: nauc_mrr_at_10_max
      value: 65.3198
    - type: nauc_mrr_at_10_std
      value: 8.2173
    - type: nauc_mrr_at_10_diff1
      value: 74.9449
    - type: nauc_mrr_at_20_max
      value: 65.2169
    - type: nauc_mrr_at_20_std
      value: 8.115400000000001
    - type: nauc_mrr_at_20_diff1
      value: 75.1765
    - type: nauc_mrr_at_100_max
      value: 65.1744
    - type: nauc_mrr_at_100_std
      value: 7.994700000000001
    - type: nauc_mrr_at_100_diff1
      value: 75.2388
    - type: nauc_mrr_at_1000_max
      value: 65.1615
    - type: nauc_mrr_at_1000_std
      value: 7.9817
    - type: nauc_mrr_at_1000_diff1
      value: 75.2553
    - type: main_score
      value: 71.27
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB SprintDuplicateQuestions (default)
      revision: d66bd1f72af766a5cc4b0ca5e00c162f89e8cc46
      split: test
      type: mteb/sprintduplicatequestions-pairclassification
    metrics:
    - type: similarity_accuracy
      value: 99.7604
    - type: similarity_accuracy_threshold
      value: 84.88210000000001
    - type: similarity_f1
      value: 87.86359999999999
    - type: similarity_f1_threshold
      value: 84.88210000000001
    - type: similarity_precision
      value: 88.1288
    - type: similarity_recall
      value: 87.6
    - type: similarity_ap
      value: 94.07140000000001
    - type: cosine_accuracy
      value: 99.7604
    - type: cosine_accuracy_threshold
      value: 84.88210000000001
    - type: cosine_f1
      value: 87.86359999999999
    - type: cosine_f1_threshold
      value: 84.88210000000001
    - type: cosine_precision
      value: 88.1288
    - type: cosine_recall
      value: 87.6
    - type: cosine_ap
      value: 94.07140000000001
    - type: manhattan_accuracy
      value: 99.7644
    - type: manhattan_accuracy_threshold
      value: 829.5789
    - type: manhattan_f1
      value: 87.92320000000001
    - type: manhattan_f1_threshold
      value: 840.6424
    - type: manhattan_precision
      value: 88.86619999999999
    - type: manhattan_recall
      value: 87.0
    - type: manhattan_ap
      value: 94.17
    - type: euclidean_accuracy
      value: 99.7604
    - type: euclidean_accuracy_threshold
      value: 54.986999999999995
    - type: euclidean_f1
      value: 87.86359999999999
    - type: euclidean_f1_threshold
      value: 54.986999999999995
    - type: euclidean_precision
      value: 88.1288
    - type: euclidean_recall
      value: 87.6
    - type: euclidean_ap
      value: 94.07140000000001
    - type: dot_accuracy
      value: 99.7604
    - type: dot_accuracy_threshold
      value: 84.88210000000001
    - type: dot_f1
      value: 87.86359999999999
    - type: dot_f1_threshold
      value: 84.88210000000001
    - type: dot_precision
      value: 88.1288
    - type: dot_recall
      value: 87.6
    - type: dot_ap
      value: 94.07140000000001
    - type: max_accuracy
      value: 99.7644
    - type: max_f1
      value: 87.92320000000001
    - type: max_precision
      value: 88.86619999999999
    - type: max_recall
      value: 87.6
    - type: max_ap
      value: 94.17
    - type: main_score
      value: 94.17
    task:
      type: PairClassification
  - dataset:
      config: default
      name: MTEB StackExchangeClustering (default)
      revision: 6cbc1f7b2bc0622f2e39d2c77fa502909748c259
      split: test
      type: mteb/stackexchange-clustering
    metrics:
    - type: v_measure
      value: 64.6589
    - type: v_measure_std
      value: 4.734
    - type: main_score
      value: 64.6589
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB StackExchangeClusteringP2P (default)
      revision: 815ca46b2622cec33ccafc3735d572c266efdb44
      split: test
      type: mteb/stackexchange-clustering-p2p
    metrics:
    - type: v_measure
      value: 32.9388
    - type: v_measure_std
      value: 1.6312
    - type: main_score
      value: 32.9388
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB StackOverflowDupQuestions (default)
      revision: e185fbe320c72810689fc5848eb6114e1ef5ec69
      split: test
      type: mteb/stackoverflowdupquestions-reranking
    metrics:
    - type: map
      value: 52.645399999999995
    - type: mrr
      value: 53.5346
    - type: nAUC_map_max
      value: 12.8874
    - type: nAUC_map_std
      value: 9.2781
    - type: nAUC_map_diff1
      value: 39.864
    - type: nAUC_mrr_max
      value: 13.278
    - type: nAUC_mrr_std
      value: 9.501999999999999
    - type: nAUC_mrr_diff1
      value: 39.409499999999994
    - type: main_score
      value: 52.645399999999995
    task:
      type: Reranking
  - dataset:
      config: default
      name: MTEB StackOverflowQA (default)
      revision: db8f169f3894c14a00251061f957b2063eef2bd5
      split: test
      type: CoIR-Retrieval/stackoverflow-qa
    metrics:
    - type: ndcg_at_1
      value: 74.97500000000001
    - type: ndcg_at_3
      value: 81.247
    - type: ndcg_at_5
      value: 82.921
    - type: ndcg_at_10
      value: 83.92699999999999
    - type: ndcg_at_20
      value: 84.57000000000001
    - type: ndcg_at_100
      value: 85.095
    - type: ndcg_at_1000
      value: 85.33800000000001
    - type: map_at_1
      value: 74.97500000000001
    - type: map_at_3
      value: 79.781
    - type: map_at_5
      value: 80.711
    - type: map_at_10
      value: 81.126
    - type: map_at_20
      value: 81.308
    - type: map_at_100
      value: 81.389
    - type: map_at_1000
      value: 81.39699999999999
    - type: recall_at_1
      value: 74.97500000000001
    - type: recall_at_3
      value: 85.456
    - type: recall_at_5
      value: 89.519
    - type: recall_at_10
      value: 92.628
    - type: recall_at_20
      value: 95.135
    - type: recall_at_100
      value: 97.844
    - type: recall_at_1000
      value: 99.799
    - type: precision_at_1
      value: 74.97500000000001
    - type: precision_at_3
      value: 28.485
    - type: precision_at_5
      value: 17.904
    - type: precision_at_10
      value: 9.263
    - type: precision_at_20
      value: 4.757
    - type: precision_at_100
      value: 0.9780000000000001
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 74.9749
    - type: mrr_at_3
      value: 79.781
    - type: mrr_at_5
      value: 80.7113
    - type: mrr_at_10
      value: 81.12610000000001
    - type: mrr_at_20
      value: 81.30760000000001
    - type: mrr_at_100
      value: 81.38889999999999
    - type: mrr_at_1000
      value: 81.3974
    - type: nauc_ndcg_at_1_max
      value: 76.1721
    - type: nauc_ndcg_at_1_std
      value: -5.5159
    - type: nauc_ndcg_at_1_diff1
      value: 84.6697
    - type: nauc_ndcg_at_3_max
      value: 78.27629999999999
    - type: nauc_ndcg_at_3_std
      value: -1.2
    - type: nauc_ndcg_at_3_diff1
      value: 81.1214
    - type: nauc_ndcg_at_5_max
      value: 77.7687
    - type: nauc_ndcg_at_5_std
      value: -1.8698
    - type: nauc_ndcg_at_5_diff1
      value: 80.9252
    - type: nauc_ndcg_at_10_max
      value: 77.8029
    - type: nauc_ndcg_at_10_std
      value: -1.5579
    - type: nauc_ndcg_at_10_diff1
      value: 81.1043
    - type: nauc_ndcg_at_20_max
      value: 77.79310000000001
    - type: nauc_ndcg_at_20_std
      value: -1.7669000000000001
    - type: nauc_ndcg_at_20_diff1
      value: 81.4121
    - type: nauc_ndcg_at_100_max
      value: 77.7522
    - type: nauc_ndcg_at_100_std
      value: -1.4502
    - type: nauc_ndcg_at_100_diff1
      value: 81.684
    - type: nauc_ndcg_at_1000_max
      value: 77.6032
    - type: nauc_ndcg_at_1000_std
      value: -2.0256
    - type: nauc_ndcg_at_1000_diff1
      value: 81.7641
    - type: nauc_map_at_1_max
      value: 76.1721
    - type: nauc_map_at_1_std
      value: -5.5159
    - type: nauc_map_at_1_diff1
      value: 84.6697
    - type: nauc_map_at_3_max
      value: 77.6991
    - type: nauc_map_at_3_std
      value: -2.3189
    - type: nauc_map_at_3_diff1
      value: 82.0708
    - type: nauc_map_at_5_max
      value: 77.4286
    - type: nauc_map_at_5_std
      value: -2.721
    - type: nauc_map_at_5_diff1
      value: 82.0265
    - type: nauc_map_at_10_max
      value: 77.4212
    - type: nauc_map_at_10_std
      value: -2.633
    - type: nauc_map_at_10_diff1
      value: 82.109
    - type: nauc_map_at_20_max
      value: 77.4188
    - type: nauc_map_at_20_std
      value: -2.6752000000000002
    - type: nauc_map_at_20_diff1
      value: 82.19340000000001
    - type: nauc_map_at_100_max
      value: 77.4169
    - type: nauc_map_at_100_std
      value: -2.6487
    - type: nauc_map_at_100_diff1
      value: 82.2353
    - type: nauc_map_at_1000_max
      value: 77.413
    - type: nauc_map_at_1000_std
      value: -2.6639
    - type: nauc_map_at_1000_diff1
      value: 82.238
    - type: nauc_recall_at_1_max
      value: 76.1721
    - type: nauc_recall_at_1_std
      value: -5.5159
    - type: nauc_recall_at_1_diff1
      value: 84.6697
    - type: nauc_recall_at_3_max
      value: 80.4678
    - type: nauc_recall_at_3_std
      value: 3.0113000000000003
    - type: nauc_recall_at_3_diff1
      value: 77.5303
    - type: nauc_recall_at_5_max
      value: 79.2732
    - type: nauc_recall_at_5_std
      value: 2.0842
    - type: nauc_recall_at_5_diff1
      value: 75.5155
    - type: nauc_recall_at_10_max
      value: 80.2527
    - type: nauc_recall_at_10_std
      value: 5.7078
    - type: nauc_recall_at_10_diff1
      value: 74.4861
    - type: nauc_recall_at_20_max
      value: 81.29950000000001
    - type: nauc_recall_at_20_std
      value: 6.5553
    - type: nauc_recall_at_20_diff1
      value: 74.5628
    - type: nauc_recall_at_100_max
      value: 83.8742
    - type: nauc_recall_at_100_std
      value: 28.4213
    - type: nauc_recall_at_100_diff1
      value: 74.4027
    - type: nauc_recall_at_1000_max
      value: 60.9178
    - type: nauc_recall_at_1000_std
      value: -2.6599
    - type: nauc_recall_at_1000_diff1
      value: 47.6074
    - type: nauc_precision_at_1_max
      value: 76.1721
    - type: nauc_precision_at_1_std
      value: -5.5159
    - type: nauc_precision_at_1_diff1
      value: 84.6697
    - type: nauc_precision_at_3_max
      value: 80.4678
    - type: nauc_precision_at_3_std
      value: 3.0113000000000003
    - type: nauc_precision_at_3_diff1
      value: 77.5303
    - type: nauc_precision_at_5_max
      value: 79.2732
    - type: nauc_precision_at_5_std
      value: 2.0842
    - type: nauc_precision_at_5_diff1
      value: 75.5155
    - type: nauc_precision_at_10_max
      value: 80.2527
    - type: nauc_precision_at_10_std
      value: 5.7078
    - type: nauc_precision_at_10_diff1
      value: 74.4861
    - type: nauc_precision_at_20_max
      value: 81.29950000000001
    - type: nauc_precision_at_20_std
      value: 6.5553
    - type: nauc_precision_at_20_diff1
      value: 74.5628
    - type: nauc_precision_at_100_max
      value: 83.8742
    - type: nauc_precision_at_100_std
      value: 28.4213
    - type: nauc_precision_at_100_diff1
      value: 74.4027
    - type: nauc_precision_at_1000_max
      value: 60.9178
    - type: nauc_precision_at_1000_std
      value: -2.6599
    - type: nauc_precision_at_1000_diff1
      value: 47.6074
    - type: nauc_mrr_at_1_max
      value: 76.1721
    - type: nauc_mrr_at_1_std
      value: -5.5159
    - type: nauc_mrr_at_1_diff1
      value: 84.6697
    - type: nauc_mrr_at_3_max
      value: 77.6991
    - type: nauc_mrr_at_3_std
      value: -2.3189
    - type: nauc_mrr_at_3_diff1
      value: 82.0708
    - type: nauc_mrr_at_5_max
      value: 77.4286
    - type: nauc_mrr_at_5_std
      value: -2.721
    - type: nauc_mrr_at_5_diff1
      value: 82.0265
    - type: nauc_mrr_at_10_max
      value: 77.4212
    - type: nauc_mrr_at_10_std
      value: -2.633
    - type: nauc_mrr_at_10_diff1
      value: 82.109
    - type: nauc_mrr_at_20_max
      value: 77.4188
    - type: nauc_mrr_at_20_std
      value: -2.6752000000000002
    - type: nauc_mrr_at_20_diff1
      value: 82.19340000000001
    - type: nauc_mrr_at_100_max
      value: 77.4169
    - type: nauc_mrr_at_100_std
      value: -2.6487
    - type: nauc_mrr_at_100_diff1
      value: 82.2353
    - type: nauc_mrr_at_1000_max
      value: 77.413
    - type: nauc_mrr_at_1000_std
      value: -2.6639
    - type: nauc_mrr_at_1000_diff1
      value: 82.238
    - type: main_score
      value: 83.92699999999999
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB SummEval (default)
      revision: cda12ad7615edc362dbf25a00fdd61d3b1eaf93c
      split: test
      type: mteb/summeval
    metrics:
    - type: pearson
      value: 29.8395
    - type: spearman
      value: 29.383
    - type: cosine_spearman
      value: 29.383
    - type: cosine_pearson
      value: 29.8395
    - type: dot_spearman
      value: 29.383
    - type: dot_pearson
      value: 29.8395
    - type: main_score
      value: 29.383
    task:
      type: Summarization
  - dataset:
      config: default
      name: MTEB SyntheticText2SQL (default)
      revision: 686b87296c3a0191b5d9415a00526c62db9fce09
      split: test
      type: CoIR-Retrieval/synthetic-text2sql
    metrics:
    - type: ndcg_at_1
      value: 4.222
    - type: ndcg_at_3
      value: 38.329
    - type: ndcg_at_5
      value: 42.076
    - type: ndcg_at_10
      value: 44.775
    - type: ndcg_at_20
      value: 46.528999999999996
    - type: ndcg_at_100
      value: 48.554
    - type: ndcg_at_1000
      value: 49.143
    - type: map_at_1
      value: 4.222
    - type: map_at_3
      value: 30.676
    - type: map_at_5
      value: 32.76
    - type: map_at_10
      value: 33.898
    - type: map_at_20
      value: 34.386
    - type: map_at_100
      value: 34.677
    - type: map_at_1000
      value: 34.701
    - type: recall_at_1
      value: 4.222
    - type: recall_at_3
      value: 60.178
    - type: recall_at_5
      value: 69.253
    - type: recall_at_10
      value: 77.474
    - type: recall_at_20
      value: 84.36200000000001
    - type: recall_at_100
      value: 95.12899999999999
    - type: recall_at_1000
      value: 99.675
    - type: precision_at_1
      value: 4.222
    - type: precision_at_3
      value: 20.058999999999997
    - type: precision_at_5
      value: 13.850999999999999
    - type: precision_at_10
      value: 7.747
    - type: precision_at_20
      value: 4.218
    - type: precision_at_100
      value: 0.951
    - type: precision_at_1000
      value: 0.1
    - type: mrr_at_1
      value: 27.3287
    - type: mrr_at_3
      value: 43.8956
    - type: mrr_at_5
      value: 45.656
    - type: mrr_at_10
      value: 46.6697
    - type: mrr_at_20
      value: 47.1331
    - type: mrr_at_100
      value: 47.4153
    - type: mrr_at_1000
      value: 47.4391
    - type: nauc_ndcg_at_1_max
      value: 16.045
    - type: nauc_ndcg_at_1_std
      value: -8.7715
    - type: nauc_ndcg_at_1_diff1
      value: 48.4886
    - type: nauc_ndcg_at_3_max
      value: 30.771500000000003
    - type: nauc_ndcg_at_3_std
      value: -16.2537
    - type: nauc_ndcg_at_3_diff1
      value: -59.0158
    - type: nauc_ndcg_at_5_max
      value: 30.354
    - type: nauc_ndcg_at_5_std
      value: -16.576
    - type: nauc_ndcg_at_5_diff1
      value: -55.0555
    - type: nauc_ndcg_at_10_max
      value: 30.0579
    - type: nauc_ndcg_at_10_std
      value: -16.3765
    - type: nauc_ndcg_at_10_diff1
      value: -52.5829
    - type: nauc_ndcg_at_20_max
      value: 29.8131
    - type: nauc_ndcg_at_20_std
      value: -15.7493
    - type: nauc_ndcg_at_20_diff1
      value: -51.1605
    - type: nauc_ndcg_at_100_max
      value: 29.9313
    - type: nauc_ndcg_at_100_std
      value: -14.9786
    - type: nauc_ndcg_at_100_diff1
      value: -49.6997
    - type: nauc_ndcg_at_1000_max
      value: 29.7154
    - type: nauc_ndcg_at_1000_std
      value: -15.2567
    - type: nauc_ndcg_at_1000_diff1
      value: -49.660399999999996
    - type: nauc_map_at_1_max
      value: 16.045
    - type: nauc_map_at_1_std
      value: -8.7715
    - type: nauc_map_at_1_diff1
      value: 48.4886
    - type: nauc_map_at_3_max
      value: 29.6122
    - type: nauc_map_at_3_std
      value: -15.509500000000001
    - type: nauc_map_at_3_diff1
      value: -52.033300000000004
    - type: nauc_map_at_5_max
      value: 29.3076
    - type: nauc_map_at_5_std
      value: -15.7
    - type: nauc_map_at_5_diff1
      value: -49.1839
    - type: nauc_map_at_10_max
      value: 29.1468
    - type: nauc_map_at_10_std
      value: -15.564400000000001
    - type: nauc_map_at_10_diff1
      value: -47.7791
    - type: nauc_map_at_20_max
      value: 29.0578
    - type: nauc_map_at_20_std
      value: -15.3635
    - type: nauc_map_at_20_diff1
      value: -47.2635
    - type: nauc_map_at_100_max
      value: 29.0523
    - type: nauc_map_at_100_std
      value: -15.2602
    - type: nauc_map_at_100_diff1
      value: -46.9875
    - type: nauc_map_at_1000_max
      value: 29.048299999999998
    - type: nauc_map_at_1000_std
      value: -15.2626
    - type: nauc_map_at_1000_diff1
      value: -46.98
    - type: nauc_recall_at_1_max
      value: 16.045
    - type: nauc_recall_at_1_std
      value: -8.7715
    - type: nauc_recall_at_1_diff1
      value: 48.4886
    - type: nauc_recall_at_3_max
      value: 32.8552
    - type: nauc_recall_at_3_std
      value: -17.6374
    - type: nauc_recall_at_3_diff1
      value: -71.1273
    - type: nauc_recall_at_5_max
      value: 32.378299999999996
    - type: nauc_recall_at_5_std
      value: -18.411
    - type: nauc_recall_at_5_diff1
      value: -65.7517
    - type: nauc_recall_at_10_max
      value: 32.041799999999995
    - type: nauc_recall_at_10_std
      value: -18.4057
    - type: nauc_recall_at_10_diff1
      value: -62.019999999999996
    - type: nauc_recall_at_20_max
      value: 31.663999999999998
    - type: nauc_recall_at_20_std
      value: -16.352800000000002
    - type: nauc_recall_at_20_diff1
      value: -59.1186
    - type: nauc_recall_at_100_max
      value: 37.872499999999995
    - type: nauc_recall_at_100_std
      value: -4.3914
    - type: nauc_recall_at_100_diff1
      value: -51.8363
    - type: nauc_recall_at_1000_max
      value: 59.5105
    - type: nauc_recall_at_1000_std
      value: 23.3375
    - type: nauc_recall_at_1000_diff1
      value: -73.9075
    - type: nauc_precision_at_1_max
      value: 16.045
    - type: nauc_precision_at_1_std
      value: -8.7715
    - type: nauc_precision_at_1_diff1
      value: 48.4886
    - type: nauc_precision_at_3_max
      value: 32.8552
    - type: nauc_precision_at_3_std
      value: -17.6374
    - type: nauc_precision_at_3_diff1
      value: -71.1273
    - type: nauc_precision_at_5_max
      value: 32.378299999999996
    - type: nauc_precision_at_5_std
      value: -18.411
    - type: nauc_precision_at_5_diff1
      value: -65.7517
    - type: nauc_precision_at_10_max
      value: 32.041799999999995
    - type: nauc_precision_at_10_std
      value: -18.4057
    - type: nauc_precision_at_10_diff1
      value: -62.019999999999996
    - type: nauc_precision_at_20_max
      value: 31.663999999999998
    - type: nauc_precision_at_20_std
      value: -16.352800000000002
    - type: nauc_precision_at_20_diff1
      value: -59.1186
    - type: nauc_precision_at_100_max
      value: 37.872499999999995
    - type: nauc_precision_at_100_std
      value: -4.3914
    - type: nauc_precision_at_100_diff1
      value: -51.8363
    - type: nauc_precision_at_1000_max
      value: 59.5105
    - type: nauc_precision_at_1000_std
      value: 23.3375
    - type: nauc_precision_at_1000_diff1
      value: -73.9075
    - type: nauc_mrr_at_1_max
      value: 15.1452
    - type: nauc_mrr_at_1_std
      value: -9.760399999999999
    - type: nauc_mrr_at_1_diff1
      value: -39.2235
    - type: nauc_mrr_at_3_max
      value: 23.6826
    - type: nauc_mrr_at_3_std
      value: -13.300899999999999
    - type: nauc_mrr_at_3_diff1
      value: -55.17809999999999
    - type: nauc_mrr_at_5_max
      value: 23.3754
    - type: nauc_mrr_at_5_std
      value: -13.306299999999998
    - type: nauc_mrr_at_5_diff1
      value: -53.744499999999995
    - type: nauc_mrr_at_10_max
      value: 23.0703
    - type: nauc_mrr_at_10_std
      value: -13.1632
    - type: nauc_mrr_at_10_diff1
      value: -53.2374
    - type: nauc_mrr_at_20_max
      value: 22.9496
    - type: nauc_mrr_at_20_std
      value: -13.031
    - type: nauc_mrr_at_20_diff1
      value: -53.016
    - type: nauc_mrr_at_100_max
      value: 22.9044
    - type: nauc_mrr_at_100_std
      value: -12.9409
    - type: nauc_mrr_at_100_diff1
      value: -52.9092
    - type: nauc_mrr_at_1000_max
      value: 22.897100000000002
    - type: nauc_mrr_at_1000_std
      value: -12.940399999999999
    - type: nauc_mrr_at_1000_diff1
      value: -52.9095
    - type: main_score
      value: 44.775
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB TRECCOVID (default)
      revision: bb9466bac8153a0349341eb1b22e06409e78ef4e
      split: test
      type: mteb/trec-covid
    metrics:
    - type: ndcg_at_1
      value: 70.0
    - type: ndcg_at_3
      value: 68.704
    - type: ndcg_at_5
      value: 67.533
    - type: ndcg_at_10
      value: 63.098
    - type: ndcg_at_20
      value: 60.507999999999996
    - type: ndcg_at_100
      value: 49.847
    - type: ndcg_at_1000
      value: 48.394999999999996
    - type: map_at_1
      value: 0.211
    - type: map_at_3
      value: 0.555
    - type: map_at_5
      value: 0.873
    - type: map_at_10
      value: 1.526
    - type: map_at_20
      value: 2.731
    - type: map_at_100
      value: 8.863
    - type: map_at_1000
      value: 23.162
    - type: recall_at_1
      value: 0.211
    - type: recall_at_3
      value: 0.5930000000000001
    - type: recall_at_5
      value: 0.962
    - type: recall_at_10
      value: 1.748
    - type: recall_at_20
      value: 3.318
    - type: recall_at_100
      value: 12.447999999999999
    - type: recall_at_1000
      value: 46.794999999999995
    - type: precision_at_1
      value: 76.0
    - type: precision_at_3
      value: 72.667
    - type: precision_at_5
      value: 71.6
    - type: precision_at_10
      value: 66.0
    - type: precision_at_20
      value: 63.6
    - type: precision_at_100
      value: 51.339999999999996
    - type: precision_at_1000
      value: 21.68
    - type: mrr_at_1
      value: 76.0
    - type: mrr_at_3
      value: 84.0
    - type: mrr_at_5
      value: 84.39999999999999
    - type: mrr_at_10
      value: 84.85000000000001
    - type: mrr_at_20
      value: 84.85000000000001
    - type: mrr_at_100
      value: 84.85000000000001
    - type: mrr_at_1000
      value: 84.85000000000001
    - type: nauc_ndcg_at_1_max
      value: 48.710300000000004
    - type: nauc_ndcg_at_1_std
      value: 72.6125
    - type: nauc_ndcg_at_1_diff1
      value: -19.9816
    - type: nauc_ndcg_at_3_max
      value: 44.8032
    - type: nauc_ndcg_at_3_std
      value: 64.7227
    - type: nauc_ndcg_at_3_diff1
      value: -25.933899999999998
    - type: nauc_ndcg_at_5_max
      value: 44.7004
    - type: nauc_ndcg_at_5_std
      value: 65.05330000000001
    - type: nauc_ndcg_at_5_diff1
      value: -26.0531
    - type: nauc_ndcg_at_10_max
      value: 49.5716
    - type: nauc_ndcg_at_10_std
      value: 66.18730000000001
    - type: nauc_ndcg_at_10_diff1
      value: -22.3525
    - type: nauc_ndcg_at_20_max
      value: 49.0212
    - type: nauc_ndcg_at_20_std
      value: 71.2387
    - type: nauc_ndcg_at_20_diff1
      value: -21.6522
    - type: nauc_ndcg_at_100_max
      value: 47.3029
    - type: nauc_ndcg_at_100_std
      value: 82.31819999999999
    - type: nauc_ndcg_at_100_diff1
      value: -27.5265
    - type: nauc_ndcg_at_1000_max
      value: 38.8474
    - type: nauc_ndcg_at_1000_std
      value: 77.1578
    - type: nauc_ndcg_at_1000_diff1
      value: -29.350700000000003
    - type: nauc_map_at_1_max
      value: 16.4698
    - type: nauc_map_at_1_std
      value: 9.657300000000001
    - type: nauc_map_at_1_diff1
      value: -4.3484
    - type: nauc_map_at_3_max
      value: 25.183299999999996
    - type: nauc_map_at_3_std
      value: 16.8245
    - type: nauc_map_at_3_diff1
      value: -7.1254
    - type: nauc_map_at_5_max
      value: 24.5899
    - type: nauc_map_at_5_std
      value: 19.8027
    - type: nauc_map_at_5_diff1
      value: -9.8547
    - type: nauc_map_at_10_max
      value: 34.9032
    - type: nauc_map_at_10_std
      value: 26.435599999999997
    - type: nauc_map_at_10_diff1
      value: -8.833499999999999
    - type: nauc_map_at_20_max
      value: 40.551700000000004
    - type: nauc_map_at_20_std
      value: 34.6141
    - type: nauc_map_at_20_diff1
      value: -8.578199999999999
    - type: nauc_map_at_100_max
      value: 51.403299999999994
    - type: nauc_map_at_100_std
      value: 68.4083
    - type: nauc_map_at_100_diff1
      value: -17.7135
    - type: nauc_map_at_1000_max
      value: 48.9955
    - type: nauc_map_at_1000_std
      value: 82.9784
    - type: nauc_map_at_1000_diff1
      value: -26.473000000000003
    - type: nauc_recall_at_1_max
      value: 16.4698
    - type: nauc_recall_at_1_std
      value: 9.657300000000001
    - type: nauc_recall_at_1_diff1
      value: -4.3484
    - type: nauc_recall_at_3_max
      value: 21.4136
    - type: nauc_recall_at_3_std
      value: 11.4801
    - type: nauc_recall_at_3_diff1
      value: -7.1396
    - type: nauc_recall_at_5_max
      value: 18.0314
    - type: nauc_recall_at_5_std
      value: 12.7486
    - type: nauc_recall_at_5_diff1
      value: -9.7349
    - type: nauc_recall_at_10_max
      value: 27.8032
    - type: nauc_recall_at_10_std
      value: 18.7061
    - type: nauc_recall_at_10_diff1
      value: -9.2739
    - type: nauc_recall_at_20_max
      value: 30.878299999999996
    - type: nauc_recall_at_20_std
      value: 26.0295
    - type: nauc_recall_at_20_diff1
      value: -7.8001000000000005
    - type: nauc_recall_at_100_max
      value: 39.4065
    - type: nauc_recall_at_100_std
      value: 56.112399999999994
    - type: nauc_recall_at_100_diff1
      value: -17.8753
    - type: nauc_recall_at_1000_max
      value: 31.571199999999997
    - type: nauc_recall_at_1000_std
      value: 65.3181
    - type: nauc_recall_at_1000_diff1
      value: -26.398899999999998
    - type: nauc_precision_at_1_max
      value: 59.8382
    - type: nauc_precision_at_1_std
      value: 66.9075
    - type: nauc_precision_at_1_diff1
      value: -5.1873000000000005
    - type: nauc_precision_at_3_max
      value: 55.787600000000005
    - type: nauc_precision_at_3_std
      value: 64.1127
    - type: nauc_precision_at_3_diff1
      value: -24.3791
    - type: nauc_precision_at_5_max
      value: 50.0544
    - type: nauc_precision_at_5_std
      value: 61.812599999999996
    - type: nauc_precision_at_5_diff1
      value: -24.5456
    - type: nauc_precision_at_10_max
      value: 57.4695
    - type: nauc_precision_at_10_std
      value: 63.7448
    - type: nauc_precision_at_10_diff1
      value: -22.6982
    - type: nauc_precision_at_20_max
      value: 57.3052
    - type: nauc_precision_at_20_std
      value: 72.00619999999999
    - type: nauc_precision_at_20_diff1
      value: -18.2329
    - type: nauc_precision_at_100_max
      value: 50.0873
    - type: nauc_precision_at_100_std
      value: 84.9689
    - type: nauc_precision_at_100_diff1
      value: -27.625300000000003
    - type: nauc_precision_at_1000_max
      value: 29.3103
    - type: nauc_precision_at_1000_std
      value: 57.898700000000005
    - type: nauc_precision_at_1000_diff1
      value: -28.8765
    - type: nauc_mrr_at_1_max
      value: 59.8382
    - type: nauc_mrr_at_1_std
      value: 66.9075
    - type: nauc_mrr_at_1_diff1
      value: -5.1873000000000005
    - type: nauc_mrr_at_3_max
      value: 58.4682
    - type: nauc_mrr_at_3_std
      value: 64.6751
    - type: nauc_mrr_at_3_diff1
      value: -5.9737
    - type: nauc_mrr_at_5_max
      value: 59.099999999999994
    - type: nauc_mrr_at_5_std
      value: 63.6902
    - type: nauc_mrr_at_5_diff1
      value: -6.482499999999999
    - type: nauc_mrr_at_10_max
      value: 57.9638
    - type: nauc_mrr_at_10_std
      value: 63.716300000000004
    - type: nauc_mrr_at_10_diff1
      value: -5.6598999999999995
    - type: nauc_mrr_at_20_max
      value: 57.9638
    - type: nauc_mrr_at_20_std
      value: 63.716300000000004
    - type: nauc_mrr_at_20_diff1
      value: -5.6598999999999995
    - type: nauc_mrr_at_100_max
      value: 57.9638
    - type: nauc_mrr_at_100_std
      value: 63.716300000000004
    - type: nauc_mrr_at_100_diff1
      value: -5.6598999999999995
    - type: nauc_mrr_at_1000_max
      value: 57.9638
    - type: nauc_mrr_at_1000_std
      value: 63.716300000000004
    - type: nauc_mrr_at_1000_diff1
      value: -5.6598999999999995
    - type: main_score
      value: 63.098
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB Touche2020 (default)
      revision: a34f9a33db75fa0cbb21bb5cfc3dae8dc8bec93f
      split: test
      type: mteb/touche2020
    metrics:
    - type: ndcg_at_1
      value: 23.469
    - type: ndcg_at_3
      value: 25.522
    - type: ndcg_at_5
      value: 24.333
    - type: ndcg_at_10
      value: 24.029
    - type: ndcg_at_20
      value: 24.573
    - type: ndcg_at_100
      value: 34.425
    - type: ndcg_at_1000
      value: 46.907
    - type: map_at_1
      value: 1.976
    - type: map_at_3
      value: 4.589
    - type: map_at_5
      value: 6.555999999999999
    - type: map_at_10
      value: 9.687999999999999
    - type: map_at_20
      value: 11.926
    - type: map_at_100
      value: 15.116999999999999
    - type: map_at_1000
      value: 16.769000000000002
    - type: recall_at_1
      value: 1.976
    - type: recall_at_3
      value: 6.101
    - type: recall_at_5
      value: 9.68
    - type: recall_at_10
      value: 16.633
    - type: recall_at_20
      value: 23.589
    - type: recall_at_100
      value: 45.61
    - type: recall_at_1000
      value: 82.48100000000001
    - type: precision_at_1
      value: 26.531
    - type: precision_at_3
      value: 27.891
    - type: precision_at_5
      value: 25.714
    - type: precision_at_10
      value: 22.448999999999998
    - type: precision_at_20
      value: 16.837
    - type: precision_at_100
      value: 7.122000000000001
    - type: precision_at_1000
      value: 1.5270000000000001
    - type: mrr_at_1
      value: 26.5306
    - type: mrr_at_3
      value: 39.1156
    - type: mrr_at_5
      value: 41.1565
    - type: mrr_at_10
      value: 43.863
    - type: mrr_at_20
      value: 44.5963
    - type: mrr_at_100
      value: 44.766600000000004
    - type: mrr_at_1000
      value: 44.766600000000004
    - type: nauc_ndcg_at_1_max
      value: -31.661099999999998
    - type: nauc_ndcg_at_1_std
      value: 2.8871
    - type: nauc_ndcg_at_1_diff1
      value: 3.4787
    - type: nauc_ndcg_at_3_max
      value: -34.6673
    - type: nauc_ndcg_at_3_std
      value: -3.8882
    - type: nauc_ndcg_at_3_diff1
      value: 0.6512
    - type: nauc_ndcg_at_5_max
      value: -33.815
    - type: nauc_ndcg_at_5_std
      value: 0.20209999999999997
    - type: nauc_ndcg_at_5_diff1
      value: -6.4072000000000005
    - type: nauc_ndcg_at_10_max
      value: -26.9953
    - type: nauc_ndcg_at_10_std
      value: -3.6511
    - type: nauc_ndcg_at_10_diff1
      value: -3.8763
    - type: nauc_ndcg_at_20_max
      value: -30.218600000000002
    - type: nauc_ndcg_at_20_std
      value: -1.4384
    - type: nauc_ndcg_at_20_diff1
      value: -8.5927
    - type: nauc_ndcg_at_100_max
      value: -32.1409
    - type: nauc_ndcg_at_100_std
      value: 20.1662
    - type: nauc_ndcg_at_100_diff1
      value: -12.0591
    - type: nauc_ndcg_at_1000_max
      value: -31.6892
    - type: nauc_ndcg_at_1000_std
      value: 32.1464
    - type: nauc_ndcg_at_1000_diff1
      value: -8.3651
    - type: nauc_map_at_1_max
      value: -41.9612
    - type: nauc_map_at_1_std
      value: -11.0332
    - type: nauc_map_at_1_diff1
      value: -5.2508
    - type: nauc_map_at_3_max
      value: -30.4968
    - type: nauc_map_at_3_std
      value: -11.138
    - type: nauc_map_at_3_diff1
      value: -0.8447
    - type: nauc_map_at_5_max
      value: -24.7543
    - type: nauc_map_at_5_std
      value: -10.302
    - type: nauc_map_at_5_diff1
      value: -10.0762
    - type: nauc_map_at_10_max
      value: -20.420099999999998
    - type: nauc_map_at_10_std
      value: -10.485
    - type: nauc_map_at_10_diff1
      value: -10.3134
    - type: nauc_map_at_20_max
      value: -20.8606
    - type: nauc_map_at_20_std
      value: -6.3984
    - type: nauc_map_at_20_diff1
      value: -10.8605
    - type: nauc_map_at_100_max
      value: -22.6385
    - type: nauc_map_at_100_std
      value: 3.8738
    - type: nauc_map_at_100_diff1
      value: -12.9055
    - type: nauc_map_at_1000_max
      value: -23.0823
    - type: nauc_map_at_1000_std
      value: 8.6942
    - type: nauc_map_at_1000_diff1
      value: -13.1715
    - type: nauc_recall_at_1_max
      value: -41.9612
    - type: nauc_recall_at_1_std
      value: -11.0332
    - type: nauc_recall_at_1_diff1
      value: -5.2508
    - type: nauc_recall_at_3_max
      value: -25.9715
    - type: nauc_recall_at_3_std
      value: -14.9623
    - type: nauc_recall_at_3_diff1
      value: -4.2583
    - type: nauc_recall_at_5_max
      value: -24.5848
    - type: nauc_recall_at_5_std
      value: -14.258299999999998
    - type: nauc_recall_at_5_diff1
      value: -13.1162
    - type: nauc_recall_at_10_max
      value: -22.3834
    - type: nauc_recall_at_10_std
      value: -15.274199999999999
    - type: nauc_recall_at_10_diff1
      value: -10.8836
    - type: nauc_recall_at_20_max
      value: -22.8634
    - type: nauc_recall_at_20_std
      value: -4.8215
    - type: nauc_recall_at_20_diff1
      value: -11.1747
    - type: nauc_recall_at_100_max
      value: -25.9537
    - type: nauc_recall_at_100_std
      value: 29.75
    - type: nauc_recall_at_100_diff1
      value: -15.512799999999999
    - type: nauc_recall_at_1000_max
      value: -18.9449
    - type: nauc_recall_at_1000_std
      value: 69.619
    - type: nauc_recall_at_1000_diff1
      value: -5.629300000000001
    - type: nauc_precision_at_1_max
      value: -33.7627
    - type: nauc_precision_at_1_std
      value: 1.8065000000000002
    - type: nauc_precision_at_1_diff1
      value: 5.3592
    - type: nauc_precision_at_3_max
      value: -30.7992
    - type: nauc_precision_at_3_std
      value: -6.285399999999999
    - type: nauc_precision_at_3_diff1
      value: 1.1098000000000001
    - type: nauc_precision_at_5_max
      value: -27.8949
    - type: nauc_precision_at_5_std
      value: -1.8754
    - type: nauc_precision_at_5_diff1
      value: -8.0528
    - type: nauc_precision_at_10_max
      value: -19.659299999999998
    - type: nauc_precision_at_10_std
      value: -0.9809999999999999
    - type: nauc_precision_at_10_diff1
      value: -2.0972999999999997
    - type: nauc_precision_at_20_max
      value: -25.810899999999997
    - type: nauc_precision_at_20_std
      value: 19.5577
    - type: nauc_precision_at_20_diff1
      value: -8.879199999999999
    - type: nauc_precision_at_100_max
      value: -21.1488
    - type: nauc_precision_at_100_std
      value: 65.00200000000001
    - type: nauc_precision_at_100_diff1
      value: -11.740499999999999
    - type: nauc_precision_at_1000_max
      value: 20.7392
    - type: nauc_precision_at_1000_std
      value: 38.2851
    - type: nauc_precision_at_1000_diff1
      value: 17.4954
    - type: nauc_mrr_at_1_max
      value: -33.7627
    - type: nauc_mrr_at_1_std
      value: 1.8065000000000002
    - type: nauc_mrr_at_1_diff1
      value: 5.3592
    - type: nauc_mrr_at_3_max
      value: -39.837
    - type: nauc_mrr_at_3_std
      value: -5.3861
    - type: nauc_mrr_at_3_diff1
      value: -4.1776
    - type: nauc_mrr_at_5_max
      value: -39.756099999999996
    - type: nauc_mrr_at_5_std
      value: -5.3674
    - type: nauc_mrr_at_5_diff1
      value: -2.4693
    - type: nauc_mrr_at_10_max
      value: -37.7379
    - type: nauc_mrr_at_10_std
      value: -6.2844
    - type: nauc_mrr_at_10_diff1
      value: -0.6525000000000001
    - type: nauc_mrr_at_20_max
      value: -38.4522
    - type: nauc_mrr_at_20_std
      value: -5.0927
    - type: nauc_mrr_at_20_diff1
      value: -0.2814
    - type: nauc_mrr_at_100_max
      value: -38.1599
    - type: nauc_mrr_at_100_std
      value: -5.2147
    - type: nauc_mrr_at_100_diff1
      value: -0.7001000000000001
    - type: nauc_mrr_at_1000_max
      value: -38.1599
    - type: nauc_mrr_at_1000_std
      value: -5.2147
    - type: nauc_mrr_at_1000_diff1
      value: -0.7001000000000001
    - type: main_score
      value: 24.029
    task:
      type: Retrieval
  - dataset:
      config: default
      name: MTEB ToxicConversationsClassification (default)
      revision: edfaf9da55d3dd50d43143d90c1ac476895ae6de
      split: test
      type: mteb/toxic_conversations_50k
    metrics:
    - type: accuracy
      value: 62.9395
    - type: f1
      value: 47.7133
    - type: f1_weighted
      value: 71.0525
    - type: ap
      value: 10.306600000000001
    - type: ap_weighted
      value: 10.306600000000001
    - type: main_score
      value: 62.9395
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB TweetSentimentExtractionClassification (default)
      revision: d604517c81ca91fe16a244d1248fc021f9ecee7a
      split: test
      type: mteb/tweet_sentiment_extraction
    metrics:
    - type: accuracy
      value: 52.8721
    - type: f1
      value: 53.034800000000004
    - type: f1_weighted
      value: 52.4319
    - type: main_score
      value: 52.8721
    task:
      type: Classification
  - dataset:
      config: default
      name: MTEB TwentyNewsgroupsClustering (default)
      revision: 6125ec4e24fa026cec8a478383ee943acfbd5449
      split: test
      type: mteb/twentynewsgroups-clustering
    metrics:
    - type: v_measure
      value: 44.9227
    - type: v_measure_std
      value: 1.1638000000000002
    - type: main_score
      value: 44.9227
    task:
      type: Clustering
  - dataset:
      config: default
      name: MTEB TwitterSemEval2015 (default)
      revision: 70970daeab8776df92f5ea462b6173c0b46fd2d1
      split: test
      type: mteb/twittersemeval2015-pairclassification
    metrics:
    - type: similarity_accuracy
      value: 82.04090000000001
    - type: similarity_accuracy_threshold
      value: 86.6147
    - type: similarity_f1
      value: 57.258399999999995
    - type: similarity_f1_threshold
      value: 82.9233
    - type: similarity_precision
      value: 52.1456
    - type: similarity_recall
      value: 63.4828
    - type: similarity_ap
      value: 60.0317
    - type: cosine_accuracy
      value: 82.04090000000001
    - type: cosine_accuracy_threshold
      value: 86.6147
    - type: cosine_f1
      value: 57.258399999999995
    - type: cosine_f1_threshold
      value: 82.9233
    - type: cosine_precision
      value: 52.1456
    - type: cosine_recall
      value: 63.4828
    - type: cosine_ap
      value: 60.0317
    - type: manhattan_accuracy
      value: 81.9574
    - type: manhattan_accuracy_threshold
      value: 794.4433
    - type: manhattan_f1
      value: 57.1936
    - type: manhattan_f1_threshold
      value: 898.9445
    - type: manhattan_precision
      value: 51.91480000000001
    - type: manhattan_recall
      value: 63.6675
    - type: manhattan_ap
      value: 59.9255
    - type: euclidean_accuracy
      value: 82.04090000000001
    - type: euclidean_accuracy_threshold
      value: 51.7403
    - type: euclidean_f1
      value: 57.258399999999995
    - type: euclidean_f1_threshold
      value: 58.440999999999995
    - type: euclidean_precision
      value: 52.1456
    - type: euclidean_recall
      value: 63.4828
    - type: euclidean_ap
      value: 60.0317
    - type: dot_accuracy
      value: 82.04090000000001
    - type: dot_accuracy_threshold
      value: 86.6147
    - type: dot_f1
      value: 57.258399999999995
    - type: dot_f1_threshold
      value: 82.9233
    - type: dot_precision
      value: 52.1456
    - type: dot_recall
      value: 63.4828
    - type: dot_ap
      value: 60.0317
    - type: max_accuracy
      value: 82.04090000000001
    - type: max_f1
      value: 57.258399999999995
    - type: max_precision
      value: 52.1456
    - type: max_recall
      value: 63.6675
    - type: max_ap
      value: 60.0317
    - type: main_score
      value: 60.0317
    task:
      type: PairClassification
  - dataset:
      config: default
      name: MTEB TwitterURLCorpus (default)
      revision: 8b6510b0b1fa4e4c4f879467980e9be563ec1cdf
      split: test
      type: mteb/twitterurlcorpus-pairclassification
    metrics:
    - type: similarity_accuracy
      value: 87.3035
    - type: similarity_accuracy_threshold
      value: 85.4123
    - type: similarity_f1
      value: 74.5555
    - type: similarity_f1_threshold
      value: 83.7581
    - type: similarity_precision
      value: 72.55369999999999
    - type: similarity_recall
      value: 76.6708
    - type: similarity_ap
      value: 82.42930000000001
    - type: cosine_accuracy
      value: 87.3035
    - type: cosine_accuracy_threshold
      value: 85.4123
    - type: cosine_f1
      value: 74.5555
    - type: cosine_f1_threshold
      value: 83.7581
    - type: cosine_precision
      value: 72.55369999999999
    - type: cosine_recall
      value: 76.6708
    - type: cosine_ap
      value: 82.42930000000001
    - type: manhattan_accuracy
      value: 87.3249
    - type: manhattan_accuracy_threshold
      value: 831.9304999999999
    - type: manhattan_f1
      value: 74.8665
    - type: manhattan_f1_threshold
      value: 893.9980999999999
    - type: manhattan_precision
      value: 70.8502
    - type: manhattan_recall
      value: 79.3656
    - type: manhattan_ap
      value: 82.5792
    - type: euclidean_accuracy
      value: 87.3035
    - type: euclidean_accuracy_threshold
      value: 54.014300000000006
    - type: euclidean_f1
      value: 74.5555
    - type: euclidean_f1_threshold
      value: 56.9946
    - type: euclidean_precision
      value: 72.55369999999999
    - type: euclidean_recall
      value: 76.6708
    - type: euclidean_ap
      value: 82.42920000000001
    - type: dot_accuracy
      value: 87.3035
    - type: dot_accuracy_threshold
      value: 85.4123
    - type: dot_f1
      value: 74.5555
    - type: dot_f1_threshold
      value: 83.7581
    - type: dot_precision
      value: 72.55369999999999
    - type: dot_recall
      value: 76.6708
    - type: dot_ap
      value: 82.42920000000001
    - type: max_accuracy
      value: 87.3249
    - type: max_f1
      value: 74.8665
    - type: max_precision
      value: 72.55369999999999
    - type: max_recall
      value: 79.3656
    - type: max_ap
      value: 82.5792
    - type: main_score
      value: 82.5792
    task:
      type: PairClassification
pipeline_tag: sentence-similarity
---
# Granite-Embedding-30m-English

**Model Summary:**
Granite-Embedding-30m-English is a 30M parameter dense biencoder embedding model from the Granite Embeddings suite that can be used to generate high quality text embeddings. This model produces embedding vectors of size 384 and is trained using a combination of open source relevance-pair datasets with permissive, enterprise-friendly license, and IBM collected and generated datasets. While maintaining competitive scores on academic benchmarks such as BEIR, this model also performs well on many enterprise use cases. This model is developed using retrieval oriented pretraining, contrastive finetuning, knowledge distillation and model merging for improved performance.

- **Developers:** Granite Embedding Team, IBM
- **GitHub Repository:** [ibm-granite/granite-embedding-models](https://github.com/ibm-granite/granite-embedding-models)
- **Website**: [Granite Docs](https://www.ibm.com/granite/docs/)
- **Paper:** Coming Soon
- **Release Date**: December 18th, 2024
- **License:** [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)

**Supported Languages:** 
English.

**Intended use:** 
The model is designed to produce fixed length vector representations for a given text, which can be used for text similarity, retrieval, and search applications.

**Usage with Sentence Transformers:** 
The model is compatible with SentenceTransformer library and is very easy to use:

First, install the sentence transformers library
```shell
pip install sentence_transformers
```

The model can then be used to encode pairs of text and find the similarity between their representations

```python
from sentence_transformers import SentenceTransformer, util

model_path = "ibm-granite/granite-embedding-30m-english"
# Load the Sentence Transformer model
model = SentenceTransformer(model_path)

input_queries = [
    ' Who made the song My achy breaky heart? ',
    'summit define'
    ]

input_passages = [
    "Achy Breaky Heart is a country song written by Don Von Tress. Originally titled Don't Tell My Heart and performed by The Marcy Brothers in 1991. ",
    "Definition of summit for English Language Learners. : 1 the highest point of a mountain : the top of a mountain. : 2 the highest level. : 3 a meeting or series of meetings between the leaders of two or more governments."
    ]

# encode queries and passages
query_embeddings = model.encode(input_queries)
passage_embeddings = model.encode(input_passages)

# calculate cosine similarity
print(util.cos_sim(query_embeddings, passage_embeddings))
```

**Usage with Huggingface Transformers:** 
This is a simple example of how to use the Granite-Embedding-30m-English model with the Transformers library and PyTorch.

First, install the required libraries
```shell
pip install transformers torch
```

The model can then be used to encode pairs of text

```python
import torch
from transformers import AutoModel, AutoTokenizer

model_path = "ibm-granite/granite-embedding-30m-english"

# Load the model and tokenizer
model = AutoModel.from_pretrained(model_path)
tokenizer = AutoTokenizer.from_pretrained(model_path)
model.eval()

input_queries = [
    ' Who made the song My achy breaky heart? ',
    'summit define'
    ]

# tokenize inputs
tokenized_queries = tokenizer(input_queries, padding=True, truncation=True, return_tensors='pt')

# encode queries
with torch.no_grad():
    # Queries
    model_output = model(**tokenized_queries)
    # Perform pooling. granite-embedding-30m-english uses CLS Pooling
    query_embeddings = model_output[0][:, 0]

# normalize the embeddings
query_embeddings = torch.nn.functional.normalize(query_embeddings, dim=1)

```
**Evaluation:**

Granite-Embedding-30M-English is twice as fast as other models with similar embedding dimensions, while maintaining competitive performance. The performance of the Granite-Embedding-30M-English model on MTEB Retrieval (i.e., BEIR) and code retrieval (CoIR) benchmarks is reported below. 

| Model                           | Paramters (M)| Embedding Dimension |  MTEB Retrieval (15) |  CoIR (10) | 
|---------------------------------|:------------:|:-------------------:|:-------------------: |:----------:|
|granite-embedding-30m-english    |30            |384                  |49.1                  |47.0        | 


**Model Architecture:**
Granite-Embedding-30m-English is based on an encoder-only RoBERTa like transformer architecture, trained internally at IBM Research.

| Model                     | granite-embedding-30m-english | granite-embedding-125m-english    | granite-embedding-107m-multilingual | granite-embedding-278m-multilingual |
| :---------                | :-------:| :--------:   | :-----:| :-----:|
| Embedding size            | **384**  | 768          | 384    | 768    |
| Number of layers          | **6**    | 12           | 6      | 12     |
| Number of attention heads | **12**   | 12           | 12     | 12     |
| Intermediate size         | **1536** | 3072         | 1536   | 3072   |
| Activation Function       | **GeLU** | GeLU         | GeLU   | GeLU   |
| Vocabulary Size           | **50265**| 50265        | 250002 | 250002 |
| Max. Sequence Length      | **512**  | 512          | 512    | 512    |
| # Parameters              | **30M**  | 125M         | 107M   | 278M   |


**Training Data:**
Overall, the training data consists of four key sources: (1) unsupervised title-body paired data scraped from the web, (2) publicly available paired with permissive, enterprise-friendly license, (3) IBM-internal paired data targetting specific technical domains, and (4) IBM-generated synthetic data. The data is listed below:

| **Dataset**                                        | **Num. Pairs** | 
|----------------------------------------------------|:---------------:|
| SPECTER citation triplets                          | 684,100         | 
| Stack Exchange Duplicate questions (titles)        | 304,525         | 
| Stack Exchange Duplicate questions (bodies)        | 250,519         | 
| Stack Exchange Duplicate questions (titles+bodies) | 250,460         | 
| Natural Questions (NQ)                             | 100,231         | 
| SQuAD2.0                                           | 87,599          | 
| PAQ (Question, Answer) pairs                       | 64,371,441       | 
| Stack Exchange (Title, Answer) pairs               | 4,067,139        | 
| Stack Exchange (Title, Body) pairs                 | 23,978,013       | 
| Stack Exchange (Title+Body, Answer) pairs          | 187,195         | 
| S2ORC Citation pairs (Titles)                      | 52,603,982       | 
| S2ORC (Title, Abstract)                            | 41,769,185       | 
| S2ORC (Citations, abstracts)                       | 52,603,982       | 
| WikiAnswers Duplicate question pairs               | 77,427,422       | 
| SearchQA                                           | 582,261         | 
| HotpotQA                                           | 85,000          | 
| Fever                                              | 109,810         | 
| Arxiv                                              | 2,358,545        | 
| Wikipedia                                          | 20,745,403       | 
| PubMed                                             | 20,000,000       | 
| Miracl En Pairs                                    | 9,016           | 
| DBPedia Title-Body Pairs                           | 4,635,922        | 
| Synthetic: Query-Wikipedia Passage                 | 1,879,093        | 
| Synthetic: Fact Verification                       | 9,888           | 
| IBM Internal Triples                               | 40,290          | 
| IBM Internal Title-Body Pairs                      | 1,524,586        | 

Notably, we do not use the popular MS-MARCO retrieval dataset in our training corpus due to its non-commercial license, while other open-source models train on this dataset due to its high quality.

**Infrastructure:**
We train Granite Embedding Models using IBM's computing cluster, Cognitive Compute Cluster, which is outfitted with NVIDIA A100 80gb GPUs. This cluster provides a scalable and efficient infrastructure for training our models over multiple GPUs.

**Ethical Considerations and Limitations:** 
The data used to train the base language model was filtered to remove text containing hate, abuse, and profanity. Granite-Embedding-30m-English is trained only for English texts, and has a context length of 512 tokens (longer texts will be truncated to this size).

**Resources**
- ⭐️ Learn about the latest updates with Granite: https://www.ibm.com/granite
- 📄 Get started with tutorials, best practices, and prompt engineering advice: https://www.ibm.com/granite/docs/
- 💡 Learn about the latest Granite learning resources: https://ibm.biz/granite-learning-resources

<!-- ## Citation
```
@misc{granite-embedding-models,
  author = {author 1, author2, ...},
  title = {},
  journal = {},
  volume = {},
  year = {2024},
  url = {https://arxiv.org/abs/0000.00000},
}
``` -->