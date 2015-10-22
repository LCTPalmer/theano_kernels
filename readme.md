##Theano implementations of common kernel functions
Takes advantage of faster element-wise (esp. dot-product) calculations on GPU.<br><br>
Currently implements:<br>
RBF<br>
Chi^2<br>
Polynomial<br><br>
Requires:<br>
numpy<br>
Theano<br>
###Benchmarking vs sklearn.metrics.pairwise implementations
Experiments carried out on Intel Xeon W3520 CPU and GeForce 560 Ti GPU <br><br><br>
![rbf_benchmark](benchmark_images/theano_rbf_vs_sklearn.png)<br><br>
![chi2_benchmark](benchmark_images/theano_chi2_vs_sklearn.png)