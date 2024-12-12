---
language:
- en
license: apache-2.0  
library_name: transformers
tags:
- language
- granite
- embeddings
model-index:
- name: ibm-granite/granite-embedding-30m-english
  results:
  - dataset:
      type: mteb/arguana
      name: MTEB ArguaAna
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.31792
    - type: map_at_10
      value: 0.47599
    - type: map_at_100
      value: 0.48425
    - type: map_at_1000
      value: 0.48427
    - type: map_at_3
      value: 0.42757
    - type: map_at_5
      value: 0.45634
    - type: mrr_at_1
      value: 0.32788
    - type: mrr_at_10
      value: 0.47974
    - type: mrr_at_100
      value: 0.48801
    - type: mrr_at_1000
      value: 0.48802
    - type: mrr_at_3
      value: 0.43065
    - type: mrr_at_5
      value: 0.45999
    - type: ndcg_at_1
      value: 0.31792
    - type: ndcg_at_10
      value: 0.56356
    - type: ndcg_at_100
      value: 0.59789
    - type: ndcg_at_1000
      value: 0.59857
    - type: ndcg_at_3
      value: 0.46453
    - type: ndcg_at_5
      value: 0.51623
    - type: precision_at_1
      value: 0.31792
    - type: precision_at_10
      value: 0.08428
    - type: precision_at_100
      value: 0.00991
    - type: precision_at_1000
      value: 0.001
    - type: precision_at_3
      value: 0.19061
    - type: precision_at_5
      value: 0.1394
    - type: recall_at_1
      value: 0.31792
    - type: recall_at_10
      value: 0.84282
    - type: recall_at_100
      value: 0.99075
    - type: recall_at_1000
      value: 0.99644
    - type: recall_at_3
      value: 0.57183
    - type: recall_at_5
      value: 0.69701
  - dataset:
      type: mteb/climate-fever
      name: MTEB ClimateFEVER
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.13189
    - type: map_at_10
      value: 0.21789
    - type: map_at_100
      value: 0.2358
    - type: map_at_1000
      value: 0.23772
    - type: map_at_3
      value: 0.18513
    - type: map_at_5
      value: 0.20212
    - type: mrr_at_1
      value: 0.29837
    - type: mrr_at_10
      value: 0.41376
    - type: mrr_at_100
      value: 0.42282
    - type: mrr_at_1000
      value: 0.42319
    - type: mrr_at_3
      value: 0.38284
    - type: mrr_at_5
      value: 0.40301
    - type: ndcg_at_1
      value: 0.29837
    - type: ndcg_at_10
      value: 0.30263
    - type: ndcg_at_100
      value: 0.37228
    - type: ndcg_at_1000
      value: 0.40677
    - type: ndcg_at_3
      value: 0.25392
    - type: ndcg_at_5
      value: 0.27153
    - type: precision_at_1
      value: 0.29837
    - type: precision_at_10
      value: 0.09179
    - type: precision_at_100
      value: 0.01659
    - type: precision_at_1000
      value: 0.0023
    - type: precision_at_3
      value: 0.18545
    - type: precision_at_5
      value: 0.14241
    - type: recall_at_1
      value: 0.13189
    - type: recall_at_10
      value: 0.35355
    - type: recall_at_100
      value: 0.59255
    - type: recall_at_1000
      value: 0.78637
    - type: recall_at_3
      value: 0.23255
    - type: recall_at_5
      value: 0.28446
  - dataset:
      type: mteb/cqadupstack-android
      name: MTEB CQADupstackAndroidRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.35797
    - type: map_at_10
      value: 0.47793
    - type: map_at_100
      value: 0.49422
    - type: map_at_1000
      value: 0.49546
    - type: map_at_3
      value: 0.44137
    - type: map_at_5
      value: 0.46063
    - type: mrr_at_1
      value: 0.44206
    - type: mrr_at_10
      value: 0.53808
    - type: mrr_at_100
      value: 0.5454
    - type: mrr_at_1000
      value: 0.54578
    - type: mrr_at_3
      value: 0.51431
    - type: mrr_at_5
      value: 0.5284
    - type: ndcg_at_1
      value: 0.44206
    - type: ndcg_at_10
      value: 0.54106
    - type: ndcg_at_100
      value: 0.59335
    - type: ndcg_at_1000
      value: 0.61015
    - type: ndcg_at_3
      value: 0.49365
    - type: ndcg_at_5
      value: 0.51429
    - type: precision_at_1
      value: 0.44206
    - type: precision_at_10
      value: 0.10443
    - type: precision_at_100
      value: 0.01631
    - type: precision_at_1000
      value: 0.00214
    - type: precision_at_3
      value: 0.23653
    - type: precision_at_5
      value: 0.1691
    - type: recall_at_1
      value: 0.35797
    - type: recall_at_10
      value: 0.65182
    - type: recall_at_100
      value: 0.86654
    - type: recall_at_1000
      value: 0.97131
    - type: recall_at_3
      value: 0.51224
    - type: recall_at_5
      value: 0.57219
  - dataset:
      type: mteb/cqadupstack-english
      name: MTEB CQADupstackEnglishRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.32748
    - type: map_at_10
      value: 0.44138
    - type: map_at_100
      value: 0.45565
    - type: map_at_1000
      value: 0.45698
    - type: map_at_3
      value: 0.40916
    - type: map_at_5
      value: 0.42621
    - type: mrr_at_1
      value: 0.41274
    - type: mrr_at_10
      value: 0.5046
    - type: mrr_at_100
      value: 0.5107
    - type: mrr_at_1000
      value: 0.51109
    - type: mrr_at_3
      value: 0.48238
    - type: mrr_at_5
      value: 0.49563
    - type: ndcg_at_1
      value: 0.41274
    - type: ndcg_at_10
      value: 0.50251
    - type: ndcg_at_100
      value: 0.54725
    - type: ndcg_at_1000
      value: 0.56635
    - type: ndcg_at_3
      value: 0.46023
    - type: ndcg_at_5
      value: 0.47883
    - type: precision_at_1
      value: 0.41274
    - type: precision_at_10
      value: 0.09828
    - type: precision_at_100
      value: 0.01573
    - type: precision_at_1000
      value: 0.00202
    - type: precision_at_3
      value: 0.22718
    - type: precision_at_5
      value: 0.16064
    - type: recall_at_1
      value: 0.32748
    - type: recall_at_10
      value: 0.60322
    - type: recall_at_100
      value: 0.79669
    - type: recall_at_1000
      value: 0.9173
    - type: recall_at_3
      value: 0.47523
    - type: recall_at_5
      value: 0.52957
  - dataset:
      type: mteb/cqadupstack-gaming
      name: MTEB CQADupstackGamingRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.41126
    - type: map_at_10
      value: 0.53661
    - type: map_at_100
      value: 0.54588
    - type: map_at_1000
      value: 0.54638
    - type: map_at_3
      value: 0.50389
    - type: map_at_5
      value: 0.52286
    - type: mrr_at_1
      value: 0.47147
    - type: mrr_at_10
      value: 0.5685
    - type: mrr_at_100
      value: 0.57458
    - type: mrr_at_1000
      value: 0.57487
    - type: mrr_at_3
      value: 0.54431
    - type: mrr_at_5
      value: 0.55957
    - type: ndcg_at_1
      value: 0.47147
    - type: ndcg_at_10
      value: 0.59318
    - type: ndcg_at_100
      value: 0.62972
    - type: ndcg_at_1000
      value: 0.64033
    - type: ndcg_at_3
      value: 0.53969
    - type: ndcg_at_5
      value: 0.56743
    - type: precision_at_1
      value: 0.47147
    - type: precision_at_10
      value: 0.09549
    - type: precision_at_100
      value: 0.01224
    - type: precision_at_1000
      value: 0.00135
    - type: precision_at_3
      value: 0.24159
    - type: precision_at_5
      value: 0.16577
    - type: recall_at_1
      value: 0.41126
    - type: recall_at_10
      value: 0.72691
    - type: recall_at_100
      value: 0.88692
    - type: recall_at_1000
      value: 0.96232
    - type: recall_at_3
      value: 0.58374
    - type: recall_at_5
      value: 0.65226
  - dataset:
      type: mteb/cqadupstack-gis
      name: MTEB CQADupstackGisRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.28464
    - type: map_at_10
      value: 0.3828
    - type: map_at_100
      value: 0.39277
    - type: map_at_1000
      value: 0.39355
    - type: map_at_3
      value: 0.35704
    - type: map_at_5
      value: 0.37116
    - type: mrr_at_1
      value: 0.30734
    - type: mrr_at_10
      value: 0.40422
    - type: mrr_at_100
      value: 0.41297
    - type: mrr_at_1000
      value: 0.41355
    - type: mrr_at_3
      value: 0.38136
    - type: mrr_at_5
      value: 0.39362
    - type: ndcg_at_1
      value: 0.30734
    - type: ndcg_at_10
      value: 0.43564
    - type: ndcg_at_100
      value: 0.48419
    - type: ndcg_at_1000
      value: 0.50404
    - type: ndcg_at_3
      value: 0.38672
    - type: ndcg_at_5
      value: 0.40954
    - type: precision_at_1
      value: 0.30734
    - type: precision_at_10
      value: 0.06633
    - type: precision_at_100
      value: 0.00956
    - type: precision_at_1000
      value: 0.00116
    - type: precision_at_3
      value: 0.16497
    - type: precision_at_5
      value: 0.11254
    - type: recall_at_1
      value: 0.28464
    - type: recall_at_10
      value: 0.57621
    - type: recall_at_100
      value: 0.7966
    - type: recall_at_1000
      value: 0.94633
    - type: recall_at_3
      value: 0.44588
    - type: recall_at_5
      value: 0.50031
  - dataset:
      type: mteb/cqadupstack-mathematica
      name: MTEB CQADupstackMathematicaRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.18119
    - type: map_at_10
      value: 0.27055
    - type: map_at_100
      value: 0.28461
    - type: map_at_1000
      value: 0.28577
    - type: map_at_3
      value: 0.24341
    - type: map_at_5
      value: 0.25861
    - type: mrr_at_1
      value: 0.22886
    - type: mrr_at_10
      value: 0.32234
    - type: mrr_at_100
      value: 0.3328
    - type: mrr_at_1000
      value: 0.3334
    - type: mrr_at_3
      value: 0.29664
    - type: mrr_at_5
      value: 0.31107
    - type: ndcg_at_1
      value: 0.22886
    - type: ndcg_at_10
      value: 0.32749
    - type: ndcg_at_100
      value: 0.39095
    - type: ndcg_at_1000
      value: 0.41656
    - type: ndcg_at_3
      value: 0.27864
    - type: ndcg_at_5
      value: 0.30177
    - type: precision_at_1
      value: 0.22886
    - type: precision_at_10
      value: 0.06169
    - type: precision_at_100
      value: 0.0107
    - type: precision_at_1000
      value: 0.00143
    - type: precision_at_3
      value: 0.13682
    - type: precision_at_5
      value: 0.0995
    - type: recall_at_1
      value: 0.18119
    - type: recall_at_10
      value: 0.44983
    - type: recall_at_100
      value: 0.72396
    - type: recall_at_1000
      value: 0.90223
    - type: recall_at_3
      value: 0.31633
    - type: recall_at_5
      value: 0.37532
  - dataset:
      type: mteb/cqadupstack-physics
      name: MTEB CQADupstackPhysicsRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.30517
    - type: map_at_10
      value: 0.42031
    - type: map_at_100
      value: 0.43415
    - type: map_at_1000
      value: 0.43525
    - type: map_at_3
      value: 0.38443
    - type: map_at_5
      value: 0.40685
    - type: mrr_at_1
      value: 0.38114
    - type: mrr_at_10
      value: 0.47783
    - type: mrr_at_100
      value: 0.48647
    - type: mrr_at_1000
      value: 0.48688
    - type: mrr_at_3
      value: 0.45172
    - type: mrr_at_5
      value: 0.46817
    - type: ndcg_at_1
      value: 0.38114
    - type: ndcg_at_10
      value: 0.4834
    - type: ndcg_at_100
      value: 0.53861
    - type: ndcg_at_1000
      value: 0.55701
    - type: ndcg_at_3
      value: 0.42986
    - type: ndcg_at_5
      value: 0.45893
    - type: precision_at_1
      value: 0.38114
    - type: precision_at_10
      value: 0.08893
    - type: precision_at_100
      value: 0.01375
    - type: precision_at_1000
      value: 0.00172
    - type: precision_at_3
      value: 0.20821
    - type: precision_at_5
      value: 0.15034
    - type: recall_at_1
      value: 0.30517
    - type: recall_at_10
      value: 0.61332
    - type: recall_at_100
      value: 0.84051
    - type: recall_at_1000
      value: 0.95826
    - type: recall_at_3
      value: 0.46015
    - type: recall_at_5
      value: 0.53801
  - dataset:
      type: mteb/cqadupstack-programmers
      name: MTEB CQADupstackProgrammersRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.27396
    - type: map_at_10
      value: 0.38043
    - type: map_at_100
      value: 0.39341
    - type: map_at_1000
      value: 0.39454
    - type: map_at_3
      value: 0.34783
    - type: map_at_5
      value: 0.3663
    - type: mrr_at_1
      value: 0.34247
    - type: mrr_at_10
      value: 0.43681
    - type: mrr_at_100
      value: 0.4451
    - type: mrr_at_1000
      value: 0.44569
    - type: mrr_at_3
      value: 0.41172
    - type: mrr_at_5
      value: 0.42702
    - type: ndcg_at_1
      value: 0.34247
    - type: ndcg_at_10
      value: 0.44065
    - type: ndcg_at_100
      value: 0.49434
    - type: ndcg_at_1000
      value: 0.51682
    - type: ndcg_at_3
      value: 0.38976
    - type: ndcg_at_5
      value: 0.41332
    - type: precision_at_1
      value: 0.34247
    - type: precision_at_10
      value: 0.08059
    - type: precision_at_100
      value: 0.01258
    - type: precision_at_1000
      value: 0.00162
    - type: precision_at_3
      value: 0.1876
    - type: precision_at_5
      value: 0.13333
    - type: recall_at_1
      value: 0.27396
    - type: recall_at_10
      value: 0.56481
    - type: recall_at_100
      value: 0.79012
    - type: recall_at_1000
      value: 0.94182
    - type: recall_at_3
      value: 0.41785
    - type: recall_at_5
      value: 0.48303
  - dataset:
      type: mteb/cqadupstack-stats
      name: MTEB CQADupstackStatsRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.25728
    - type: map_at_10
      value: 0.33903
    - type: map_at_100
      value: 0.34853
    - type: map_at_1000
      value: 0.34944
    - type: map_at_3
      value: 0.31268
    - type: map_at_5
      value: 0.32596
    - type: mrr_at_1
      value: 0.29141
    - type: mrr_at_10
      value: 0.36739
    - type: mrr_at_100
      value: 0.37545
    - type: mrr_at_1000
      value: 0.37608
    - type: mrr_at_3
      value: 0.34407
    - type: mrr_at_5
      value: 0.3568
    - type: ndcg_at_1
      value: 0.29141
    - type: ndcg_at_10
      value: 0.38596
    - type: ndcg_at_100
      value: 0.43375
    - type: ndcg_at_1000
      value: 0.45562
    - type: ndcg_at_3
      value: 0.33861
    - type: ndcg_at_5
      value: 0.35887
    - type: precision_at_1
      value: 0.29141
    - type: precision_at_10
      value: 0.06334
    - type: precision_at_100
      value: 0.00952
    - type: precision_at_1000
      value: 0.00121
    - type: precision_at_3
      value: 0.14826
    - type: precision_at_5
      value: 0.10429
    - type: recall_at_1
      value: 0.25728
    - type: recall_at_10
      value: 0.50121
    - type: recall_at_100
      value: 0.72382
    - type: recall_at_1000
      value: 0.88306
    - type: recall_at_3
      value: 0.36638
    - type: recall_at_5
      value: 0.41689
  - dataset:
      type: mteb/cqadupstack-tex
      name: MTEB CQADupstackTexRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.19911
    - type: map_at_10
      value: 0.2856
    - type: map_at_100
      value: 0.29785
    - type: map_at_1000
      value: 0.29911
    - type: map_at_3
      value: 0.25875
    - type: map_at_5
      value: 0.2741
    - type: mrr_at_1
      value: 0.24054
    - type: mrr_at_10
      value: 0.32483
    - type: mrr_at_100
      value: 0.33464
    - type: mrr_at_1000
      value: 0.33534
    - type: mrr_at_3
      value: 0.30162
    - type: mrr_at_5
      value: 0.31506
    - type: ndcg_at_1
      value: 0.24054
    - type: ndcg_at_10
      value: 0.33723
    - type: ndcg_at_100
      value: 0.39362
    - type: ndcg_at_1000
      value: 0.42065
    - type: ndcg_at_3
      value: 0.29116
    - type: ndcg_at_5
      value: 0.31299
    - type: precision_at_1
      value: 0.24054
    - type: precision_at_10
      value: 0.06194
    - type: precision_at_100
      value: 0.01058
    - type: precision_at_1000
      value: 0.00148
    - type: precision_at_3
      value: 0.13914
    - type: precision_at_5
      value: 0.10076
    - type: recall_at_1
      value: 0.19911
    - type: recall_at_10
      value: 0.45183
    - type: recall_at_100
      value: 0.7025
    - type: recall_at_1000
      value: 0.89222
    - type: recall_at_3
      value: 0.32195
    - type: recall_at_5
      value: 0.37852
  - dataset:
      type: mteb/cqadupstack-unix
      name: MTEB CQADupstackUnixRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.29819
    - type: map_at_10
      value: 0.40073
    - type: map_at_100
      value: 0.41289
    - type: map_at_1000
      value: 0.41375
    - type: map_at_3
      value: 0.36572
    - type: map_at_5
      value: 0.38386
    - type: mrr_at_1
      value: 0.35168
    - type: mrr_at_10
      value: 0.44381
    - type: mrr_at_100
      value: 0.45191
    - type: mrr_at_1000
      value: 0.45234
    - type: mrr_at_3
      value: 0.41402
    - type: mrr_at_5
      value: 0.43039
    - type: ndcg_at_1
      value: 0.35168
    - type: ndcg_at_10
      value: 0.46071
    - type: ndcg_at_100
      value: 0.51351
    - type: ndcg_at_1000
      value: 0.5317
    - type: ndcg_at_3
      value: 0.39972
    - type: ndcg_at_5
      value: 0.42586
    - type: precision_at_1
      value: 0.35168
    - type: precision_at_10
      value: 0.07985
    - type: precision_at_100
      value: 0.01185
    - type: precision_at_1000
      value: 0.00144
    - type: precision_at_3
      value: 0.18221
    - type: precision_at_5
      value: 0.12892
    - type: recall_at_1
      value: 0.29819
    - type: recall_at_10
      value: 0.60075
    - type: recall_at_100
      value: 0.82771
    - type: recall_at_1000
      value: 0.95219
    - type: recall_at_3
      value: 0.43245
    - type: recall_at_5
      value: 0.49931
  - dataset:
      type: mteb/cqadupstack-webmasters
      name: MTEB CQADupstackWebmastersRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.28409
    - type: map_at_10
      value: 0.37621
    - type: map_at_100
      value: 0.39233
    - type: map_at_1000
      value: 0.39471
    - type: map_at_3
      value: 0.34337
    - type: map_at_5
      value: 0.35985
    - type: mrr_at_1
      value: 0.33794
    - type: mrr_at_10
      value: 0.42349
    - type: mrr_at_100
      value: 0.43196
    - type: mrr_at_1000
      value: 0.43237
    - type: mrr_at_3
      value: 0.39526
    - type: mrr_at_5
      value: 0.41087
    - type: ndcg_at_1
      value: 0.33794
    - type: ndcg_at_10
      value: 0.43832
    - type: ndcg_at_100
      value: 0.49514
    - type: ndcg_at_1000
      value: 0.51742
    - type: ndcg_at_3
      value: 0.38442
    - type: ndcg_at_5
      value: 0.40737
    - type: precision_at_1
      value: 0.33794
    - type: precision_at_10
      value: 0.08597
    - type: precision_at_100
      value: 0.01652
    - type: precision_at_1000
      value: 0.00251
    - type: precision_at_3
      value: 0.17787
    - type: precision_at_5
      value: 0.13241
    - type: recall_at_1
      value: 0.28409
    - type: recall_at_10
      value: 0.55388
    - type: recall_at_100
      value: 0.81517
    - type: recall_at_1000
      value: 0.95038
    - type: recall_at_3
      value: 0.40133
    - type: recall_at_5
      value: 0.45913
  - dataset:
      type: mteb/cqadupstack-wordpress
      name: MTEB CQADupstackWordpressRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.24067
    - type: map_at_10
      value: 0.32184
    - type: map_at_100
      value: 0.33357
    - type: map_at_1000
      value: 0.33458
    - type: map_at_3
      value: 0.29492
    - type: map_at_5
      value: 0.3111
    - type: mrr_at_1
      value: 0.26248
    - type: mrr_at_10
      value: 0.34149
    - type: mrr_at_100
      value: 0.35189
    - type: mrr_at_1000
      value: 0.35251
    - type: mrr_at_3
      value: 0.31639
    - type: mrr_at_5
      value: 0.33182
    - type: ndcg_at_1
      value: 0.26248
    - type: ndcg_at_10
      value: 0.36889
    - type: ndcg_at_100
      value: 0.42426
    - type: ndcg_at_1000
      value: 0.44745
    - type: ndcg_at_3
      value: 0.31799
    - type: ndcg_at_5
      value: 0.34563
    - type: precision_at_1
      value: 0.26248
    - type: precision_at_10
      value: 0.05712
    - type: precision_at_100
      value: 0.00915
    - type: precision_at_1000
      value: 0.00123
    - type: precision_at_3
      value: 0.13309
    - type: precision_at_5
      value: 0.09649
    - type: recall_at_1
      value: 0.24067
    - type: recall_at_10
      value: 0.49344
    - type: recall_at_100
      value: 0.7412
    - type: recall_at_1000
      value: 0.91276
    - type: recall_at_3
      value: 0.36272
    - type: recall_at_5
      value: 0.4277
  - dataset:
      type: mteb/dbpedia
      name: MTEB DBPedia
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.08651
    - type: map_at_10
      value: 0.17628
    - type: map_at_100
      value: 0.23354
    - type: map_at_1000
      value: 0.24827
    - type: map_at_3
      value: 0.1351
    - type: map_at_5
      value: 0.15468
    - type: mrr_at_1
      value: 0.645
    - type: mrr_at_10
      value: 0.71989
    - type: mrr_at_100
      value: 0.72332
    - type: mrr_at_1000
      value: 0.72346
    - type: mrr_at_3
      value: 0.7025
    - type: mrr_at_5
      value: 0.71275
    - type: ndcg_at_1
      value: 0.51375
    - type: ndcg_at_10
      value: 0.3596
    - type: ndcg_at_100
      value: 0.39878
    - type: ndcg_at_1000
      value: 0.47931
    - type: ndcg_at_3
      value: 0.41275
    - type: ndcg_at_5
      value: 0.38297
    - type: precision_at_1
      value: 0.645
    - type: precision_at_10
      value: 0.2745
    - type: precision_at_100
      value: 0.08405
    - type: precision_at_1000
      value: 0.01923
    - type: precision_at_3
      value: 0.44417
    - type: precision_at_5
      value: 0.366
    - type: recall_at_1
      value: 0.08651
    - type: recall_at_10
      value: 0.22416
    - type: recall_at_100
      value: 0.46381
    - type: recall_at_1000
      value: 0.71557
    - type: recall_at_3
      value: 0.14847
    - type: recall_at_5
      value: 0.1804
  - dataset:
      type: mteb/fever
      name: MTEB FEVER
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.73211
    - type: map_at_10
      value: 0.81463
    - type: map_at_100
      value: 0.81622
    - type: map_at_1000
      value: 0.81634
    - type: map_at_3
      value: 0.805
    - type: map_at_5
      value: 0.81134
    - type: mrr_at_1
      value: 0.79088
    - type: mrr_at_10
      value: 0.86943
    - type: mrr_at_100
      value: 0.87017
    - type: mrr_at_1000
      value: 0.87018
    - type: mrr_at_3
      value: 0.86154
    - type: mrr_at_5
      value: 0.867
    - type: ndcg_at_1
      value: 0.79088
    - type: ndcg_at_10
      value: 0.85528
    - type: ndcg_at_100
      value: 0.86134
    - type: ndcg_at_1000
      value: 0.86367
    - type: ndcg_at_3
      value: 0.83943
    - type: ndcg_at_5
      value: 0.84878
    - type: precision_at_1
      value: 0.79088
    - type: precision_at_10
      value: 0.10132
    - type: precision_at_100
      value: 0.01055
    - type: precision_at_1000
      value: 0.00109
    - type: precision_at_3
      value: 0.31963
    - type: precision_at_5
      value: 0.19769
    - type: recall_at_1
      value: 0.73211
    - type: recall_at_10
      value: 0.92797
    - type: recall_at_100
      value: 0.95263
    - type: recall_at_1000
      value: 0.96738
    - type: recall_at_3
      value: 0.88328
    - type: recall_at_5
      value: 0.90821
  - dataset:
      type: mteb/fiqa
      name: MTEB FiQA2018
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.18311
    - type: map_at_10
      value: 0.29201
    - type: map_at_100
      value: 0.3093
    - type: map_at_1000
      value: 0.31116
    - type: map_at_3
      value: 0.24778
    - type: map_at_5
      value: 0.27453
    - type: mrr_at_1
      value: 0.35494
    - type: mrr_at_10
      value: 0.44489
    - type: mrr_at_100
      value: 0.4532
    - type: mrr_at_1000
      value: 0.45369
    - type: mrr_at_3
      value: 0.41667
    - type: mrr_at_5
      value: 0.43418
    - type: ndcg_at_1
      value: 0.35494
    - type: ndcg_at_10
      value: 0.36868
    - type: ndcg_at_100
      value: 0.43463
    - type: ndcg_at_1000
      value: 0.46766
    - type: ndcg_at_3
      value: 0.32305
    - type: ndcg_at_5
      value: 0.34332
    - type: precision_at_1
      value: 0.35494
    - type: precision_at_10
      value: 0.10324
    - type: precision_at_100
      value: 0.01707
    - type: precision_at_1000
      value: 0.00229
    - type: precision_at_3
      value: 0.21142
    - type: precision_at_5
      value: 0.16327
    - type: recall_at_1
      value: 0.18311
    - type: recall_at_10
      value: 0.43881
    - type: recall_at_100
      value: 0.68593
    - type: recall_at_1000
      value: 0.8855
    - type: recall_at_3
      value: 0.28824
    - type: recall_at_5
      value: 0.36178
  - dataset:
      type: mteb/hotpotqa
      name: MTEB HotpotQA
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.36766
    - type: map_at_10
      value: 0.53639
    - type: map_at_100
      value: 0.54532
    - type: map_at_1000
      value: 0.54608
    - type: map_at_3
      value: 0.50427
    - type: map_at_5
      value: 0.5245
    - type: mrr_at_1
      value: 0.73531
    - type: mrr_at_10
      value: 0.80104
    - type: mrr_at_100
      value: 0.80341
    - type: mrr_at_1000
      value: 0.80351
    - type: mrr_at_3
      value: 0.78949
    - type: mrr_at_5
      value: 0.79729
    - type: ndcg_at_1
      value: 0.73531
    - type: ndcg_at_10
      value: 0.62918
    - type: ndcg_at_100
      value: 0.66056
    - type: ndcg_at_1000
      value: 0.67554
    - type: ndcg_at_3
      value: 0.58247
    - type: ndcg_at_5
      value: 0.60905
    - type: precision_at_1
      value: 0.73531
    - type: precision_at_10
      value: 0.1302
    - type: precision_at_100
      value: 0.01546
    - type: precision_at_1000
      value: 0.00175
    - type: precision_at_3
      value: 0.36556
    - type: precision_at_5
      value: 0.24032
    - type: recall_at_1
      value: 0.36766
    - type: recall_at_10
      value: 0.65098
    - type: recall_at_100
      value: 0.77306
    - type: recall_at_1000
      value: 0.87252
    - type: recall_at_3
      value: 0.54835
    - type: recall_at_5
      value: 0.60081
  - dataset:
      type: mteb/msmarco
      name: MTEB MSMARCO
      config: default
      split: dev
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.14654
    - type: map_at_10
      value: 0.2472
    - type: map_at_100
      value: 0.25994
    - type: map_at_1000
      value: 0.26067
    - type: map_at_3
      value: 0.21234
    - type: map_at_5
      value: 0.2319
    - type: mrr_at_1
      value: 0.15086
    - type: mrr_at_10
      value: 0.25184
    - type: mrr_at_100
      value: 0.26422
    - type: mrr_at_1000
      value: 0.26489
    - type: mrr_at_3
      value: 0.21731
    - type: mrr_at_5
      value: 0.23674
    - type: ndcg_at_1
      value: 0.15086
    - type: ndcg_at_10
      value: 0.30711
    - type: ndcg_at_100
      value: 0.37221
    - type: ndcg_at_1000
      value: 0.39133
    - type: ndcg_at_3
      value: 0.23567
    - type: ndcg_at_5
      value: 0.27066
    - type: precision_at_1
      value: 0.15086
    - type: precision_at_10
      value: 0.05132
    - type: precision_at_100
      value: 0.00845
    - type: precision_at_1000
      value: 0.00101
    - type: precision_at_3
      value: 0.10277
    - type: precision_at_5
      value: 0.07923
    - type: recall_at_1
      value: 0.14654
    - type: recall_at_10
      value: 0.49341
    - type: recall_at_100
      value: 0.80224
    - type: recall_at_1000
      value: 0.95037
    - type: recall_at_3
      value: 0.29862
    - type: recall_at_5
      value: 0.38274
  - dataset:
      type: mteb/nfcorpus
      name: MTEB NFCorpus
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.05452
    - type: map_at_10
      value: 0.12758
    - type: map_at_100
      value: 0.1593
    - type: map_at_1000
      value: 0.17422
    - type: map_at_3
      value: 0.0945
    - type: map_at_5
      value: 0.1092
    - type: mrr_at_1
      value: 0.43963
    - type: mrr_at_10
      value: 0.53237
    - type: mrr_at_100
      value: 0.53777
    - type: mrr_at_1000
      value: 0.53822
    - type: mrr_at_3
      value: 0.51445
    - type: mrr_at_5
      value: 0.52466
    - type: ndcg_at_1
      value: 0.41486
    - type: ndcg_at_10
      value: 0.33737
    - type: ndcg_at_100
      value: 0.30886
    - type: ndcg_at_1000
      value: 0.40018
    - type: ndcg_at_3
      value: 0.39324
    - type: ndcg_at_5
      value: 0.36949
    - type: precision_at_1
      value: 0.43344
    - type: precision_at_10
      value: 0.24799
    - type: precision_at_100
      value: 0.07895
    - type: precision_at_1000
      value: 0.02091
    - type: precision_at_3
      value: 0.37152
    - type: precision_at_5
      value: 0.31703
    - type: recall_at_1
      value: 0.05452
    - type: recall_at_10
      value: 0.1712
    - type: recall_at_100
      value: 0.30719
    - type: recall_at_1000
      value: 0.62766
    - type: recall_at_3
      value: 0.10733
    - type: recall_at_5
      value: 0.13553
  - dataset:
      type: mteb/nq
      name: MTEB NQ
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.29022
    - type: map_at_10
      value: 0.4373
    - type: map_at_100
      value: 0.44849
    - type: map_at_1000
      value: 0.44877
    - type: map_at_3
      value: 0.39045
    - type: map_at_5
      value: 0.4186
    - type: mrr_at_1
      value: 0.32793
    - type: mrr_at_10
      value: 0.46243
    - type: mrr_at_100
      value: 0.47083
    - type: mrr_at_1000
      value: 0.47101
    - type: mrr_at_3
      value: 0.42261
    - type: mrr_at_5
      value: 0.44775
    - type: ndcg_at_1
      value: 0.32793
    - type: ndcg_at_10
      value: 0.51631
    - type: ndcg_at_100
      value: 0.56287
    - type: ndcg_at_1000
      value: 0.56949
    - type: ndcg_at_3
      value: 0.42782
    - type: ndcg_at_5
      value: 0.47554
    - type: precision_at_1
      value: 0.32793
    - type: precision_at_10
      value: 0.08737
    - type: precision_at_100
      value: 0.01134
    - type: precision_at_1000
      value: 0.0012
    - type: precision_at_3
      value: 0.19583
    - type: precision_at_5
      value: 0.14484
    - type: recall_at_1
      value: 0.29022
    - type: recall_at_10
      value: 0.73325
    - type: recall_at_100
      value: 0.93455
    - type: recall_at_1000
      value: 0.98414
    - type: recall_at_3
      value: 0.50406
    - type: recall_at_5
      value: 0.6145
  - dataset:
      type: mteb/quora
      name: MTEB QuoraRetrieval
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.68941
    - type: map_at_10
      value: 0.82641
    - type: map_at_100
      value: 0.83317
    - type: map_at_1000
      value: 0.83337
    - type: map_at_3
      value: 0.79604
    - type: map_at_5
      value: 0.81525
    - type: mrr_at_1
      value: 0.7935
    - type: mrr_at_10
      value: 0.85969
    - type: mrr_at_100
      value: 0.86094
    - type: mrr_at_1000
      value: 0.86095
    - type: mrr_at_3
      value: 0.84852
    - type: mrr_at_5
      value: 0.85627
    - type: ndcg_at_1
      value: 0.7936
    - type: ndcg_at_10
      value: 0.86687
    - type: ndcg_at_100
      value: 0.88094
    - type: ndcg_at_1000
      value: 0.88243
    - type: ndcg_at_3
      value: 0.83538
    - type: ndcg_at_5
      value: 0.85308
    - type: precision_at_1
      value: 0.7936
    - type: precision_at_10
      value: 0.13145
    - type: precision_at_100
      value: 0.01517
    - type: precision_at_1000
      value: 0.00156
    - type: precision_at_3
      value: 0.36353
    - type: precision_at_5
      value: 0.24044
    - type: recall_at_1
      value: 0.68941
    - type: recall_at_10
      value: 0.94407
    - type: recall_at_100
      value: 0.99226
    - type: recall_at_1000
      value: 0.99958
    - type: recall_at_3
      value: 0.85502
    - type: recall_at_5
      value: 0.90372
  - dataset:
      type: mteb/scidocs
      name: MTEB SCIDOCS
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.04988
    - type: map_at_10
      value: 0.13553
    - type: map_at_100
      value: 0.16136
    - type: map_at_1000
      value: 0.16512
    - type: map_at_3
      value: 0.09439
    - type: map_at_5
      value: 0.1146
    - type: mrr_at_1
      value: 0.246
    - type: mrr_at_10
      value: 0.36792
    - type: mrr_at_100
      value: 0.37973
    - type: mrr_at_1000
      value: 0.38011
    - type: mrr_at_3
      value: 0.33117
    - type: mrr_at_5
      value: 0.35172
    - type: ndcg_at_1
      value: 0.246
    - type: ndcg_at_10
      value: 0.22542
    - type: ndcg_at_100
      value: 0.32326
    - type: ndcg_at_1000
      value: 0.3828
    - type: ndcg_at_3
      value: 0.20896
    - type: ndcg_at_5
      value: 0.18497
    - type: precision_at_1
      value: 0.246
    - type: precision_at_10
      value: 0.1194
    - type: precision_at_100
      value: 0.02616
    - type: precision_at_1000
      value: 0.00404
    - type: precision_at_3
      value: 0.198
    - type: precision_at_5
      value: 0.1654
    - type: recall_at_1
      value: 0.04988
    - type: recall_at_10
      value: 0.24212
    - type: recall_at_100
      value: 0.53105
    - type: recall_at_1000
      value: 0.82022
    - type: recall_at_3
      value: 0.12047
    - type: recall_at_5
      value: 0.16777
  - dataset:
      type: mteb/scifact
      name: MTEB SciFact
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.56578
    - type: map_at_10
      value: 0.66725
    - type: map_at_100
      value: 0.67379
    - type: map_at_1000
      value: 0.674
    - type: map_at_3
      value: 0.63416
    - type: map_at_5
      value: 0.6577
    - type: mrr_at_1
      value: 0.59333
    - type: mrr_at_10
      value: 0.67533
    - type: mrr_at_100
      value: 0.68062
    - type: mrr_at_1000
      value: 0.68082
    - type: mrr_at_3
      value: 0.64944
    - type: mrr_at_5
      value: 0.66928
    - type: ndcg_at_1
      value: 0.59333
    - type: ndcg_at_10
      value: 0.7127
    - type: ndcg_at_100
      value: 0.73889
    - type: ndcg_at_1000
      value: 0.7441
    - type: ndcg_at_3
      value: 0.65793
    - type: ndcg_at_5
      value: 0.69429
    - type: precision_at_1
      value: 0.59333
    - type: precision_at_10
      value: 0.096
    - type: precision_at_100
      value: 0.01087
    - type: precision_at_1000
      value: 0.00113
    - type: precision_at_3
      value: 0.25556
    - type: precision_at_5
      value: 0.17667
    - type: recall_at_1
      value: 0.56578
    - type: recall_at_10
      value: 0.842
    - type: recall_at_100
      value: 0.95667
    - type: recall_at_1000
      value: 0.99667
    - type: recall_at_3
      value: 0.70072
    - type: recall_at_5
      value: 0.79011
  - dataset:
      type: mteb/touche2020
      name: MTEB Touche2020
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.01976
    - type: map_at_10
      value: 0.09688
    - type: map_at_100
      value: 0.15117
    - type: map_at_1000
      value: 0.16769
    - type: map_at_3
      value: 0.04589
    - type: map_at_5
      value: 0.06556
    - type: mrr_at_1
      value: 0.26531
    - type: mrr_at_10
      value: 0.43863
    - type: mrr_at_100
      value: 0.44767
    - type: mrr_at_1000
      value: 0.44767
    - type: mrr_at_3
      value: 0.39116
    - type: mrr_at_5
      value: 0.41156
    - type: ndcg_at_1
      value: 0.23469
    - type: ndcg_at_10
      value: 0.24029
    - type: ndcg_at_100
      value: 0.34425
    - type: ndcg_at_1000
      value: 0.46907
    - type: ndcg_at_3
      value: 0.25522
    - type: ndcg_at_5
      value: 0.24333
    - type: precision_at_1
      value: 0.26531
    - type: precision_at_10
      value: 0.22449
    - type: precision_at_100
      value: 0.07122
    - type: precision_at_1000
      value: 0.01527
    - type: precision_at_3
      value: 0.27891
    - type: precision_at_5
      value: 0.25714
    - type: recall_at_1
      value: 0.01976
    - type: recall_at_10
      value: 0.16633
    - type: recall_at_100
      value: 0.4561
    - type: recall_at_1000
      value: 0.82481
    - type: recall_at_3
      value: 0.06101
    - type: recall_at_5
      value: 0.0968
  - dataset:
      type: mteb/trec-covid
      name: MTEB TRECCOVID
      config: default
      split: test
    task:
      type: Retrieval
    metrics:
    - type: map_at_1
      value: 0.00211
    - type: map_at_10
      value: 0.01526
    - type: map_at_100
      value: 0.08863
    - type: map_at_1000
      value: 0.23162
    - type: map_at_3
      value: 0.00555
    - type: map_at_5
      value: 0.00873
    - type: mrr_at_1
      value: 0.76
    - type: mrr_at_10
      value: 0.8485
    - type: mrr_at_100
      value: 0.8485
    - type: mrr_at_1000
      value: 0.8485
    - type: mrr_at_3
      value: 0.84
    - type: mrr_at_5
      value: 0.844
    - type: ndcg_at_1
      value: 0.7
    - type: ndcg_at_10
      value: 0.63098
    - type: ndcg_at_100
      value: 0.49847
    - type: ndcg_at_1000
      value: 0.48395
    - type: ndcg_at_3
      value: 0.68704
    - type: ndcg_at_5
      value: 0.67533
    - type: precision_at_1
      value: 0.76
    - type: precision_at_10
      value: 0.66
    - type: precision_at_100
      value: 0.5134
    - type: precision_at_1000
      value: 0.2168
    - type: precision_at_3
      value: 0.72667
    - type: precision_at_5
      value: 0.716
    - type: recall_at_1
      value: 0.00211
    - type: recall_at_10
      value: 0.01748
    - type: recall_at_100
      value: 0.12448
    - type: recall_at_1000
      value: 0.46795
    - type: recall_at_3
      value: 0.00593
    - type: recall_at_5
      value: 0.00962
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