# CambridgeSpark AI L7 - Hackathon October 2021

This repository is for the hackathon held on 20th and 21st of October 2021. 


1) Base line:
    All features, 'None' as a value, no overrides

    LR score train:  0.8990602419946635
    LR score valid:  0.82602918308811

    DTC score train:  0.9197129777640092
    DTC score valid:  0.8166051160298665

    RF score train:  0.9196520288122647
    RF score valid:  0.8424296911537992

    knn score train:  0.8721130623224342
    knn score valid:  0.7904165154306139
2) 




For the ensemble:
https://scikit-learn.org/stable/modules/ensemble.html#voting-classifier


best parameters for knn: n_neighbors = 3, weights = 'uniform', metric ='euclidean'
