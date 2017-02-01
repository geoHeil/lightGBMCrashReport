# lightGBM is crashing
for the settings 

```
assignments['bagging_fraction'] = 1.0
assignments['learning_rate'] = 0.6
assignments['max_bin'] = 200
assignments['max_depth'] = 30
assignments['min_child_weight'] = 200
assignments['n_estimators'] = 6000
assignments['num_leaves'] = 2000000
assignments['subsample'] = 1.0
assignments['scale_pos_weight'] = 2000
assignments['boosting_type'] = 'gbdt'
assignments['reg_alpha'] = 0
assignments['reg_lambda'] = 2
assignments['is_unbalance'] = True
assignments['min_split_gain'] = 0
assignments['min_child_samples'] = 10
assignments['colsample_bytree'] = 0.8
assignments['subsample_freq'] = 3
assignments['subsample_for_bin'] = 50000
```

the lightGBM binary (current master branch version) is crashing without any notice.