# Machine Learning Design Patterns
- Choose the number of hash buckets by balancing the need to handle out-of-vocabulary inputs reasonably and the need to have the model accurately
- Choose the number of hash buckets by balancing the need to handle out-of-vocabulary inputs reasonably and the need to have the model accurately reflect the categorical input. With 10 hash buckets, ~35 airports get commingled. A good rule of thumb is to choose the number of hash buckets such that each bucket gets about five entries. In this case, that would mean that 70 hash buckets is a good compromise.
