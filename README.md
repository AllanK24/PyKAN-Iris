# Kolmogorov Arnold Networks trained on Iris Dataset
From the [GitHub repository](https://github.com/KindXiaoming/pykan), Kolmogorov-Arnold Networks (KANs) are emerging as compelling alternatives to Multi-Layer Perceptrons (MLPs). While MLPs are grounded in the universal approximation theorem, KANs are supported by the Kolmogorov-Arnold representation theorem. The key difference between the two lies in their structure: KANs apply activation functions to edges, whereas MLPs apply them to nodes. This structural variation enables KANs to outperform MLPs in terms of both accuracy and interpretability. 

This is the implementation of KAN on Iris dataset.
The Iris dataset consists of 150 examples. Train and test sets were split as the following:
- Training set: 90%
- Test set: 10%
<br><br>

### Conclustion
- Train set accuracy: 96.3%
- Test set accuracy: 93.3%

*Note*: Adjusting hyperparameters didn't really change anything. Hyperparameter adjustment might affect algorithm's performance when dealing with bigger datasets
<br><br>

## References
- [arxiv paper](https://arxiv.org/abs/2404.19756)
- [documentation](https://kindxiaoming.github.io/pykan/)


<!-- Google Search Console HTML Tag -->
<meta name="google-site-verification" content="IbBsnxp7SEco6wVBgeN6y_bHu-u9rJCtEjNyzW7cEpE" />