These commands were used for performance testing:

`asreview simulate benchmark:van_de_Schoot_2017 -m xgboost --n_queries min -s xgboost.h5 --seed 1 --n_prior_included 5 --n_instances 10`

`asreview simulate benchmark:van_de_Schoot_2017 -m rf --n_queries min -s nb.h5 --seed 1 --n_prior_included 5 --n_instances 10`

`asreview simulate benchmark:van_de_Schoot_2017 -m nb --n_queries min -s nb.h5 --seed 1 --n_prior_included 5 --n_instances 10`