# LSA_eval
Evaluation of LSA on different genre datasets
# Abstract
Analogies are a fundamental aspect of human intelligence and cognition, and crucial for our cognitive functions, learning,
memory retention, and access. By utilizing the context of the entire document, Latent Semantic Analysis (LSA) seeks to uncover semantic
links between texts, phrases, or words. In contrast, more recent models like GloVe and word2vec consider the "local window” around the
target word [6]. Additionally, there is evidence that LSA performs better when trained on a more task-specific sub-corpus unlike modern
models that may produce higher accuracy when trained on a larger and more general dataset [8]. This motivates our investigation on
whether a LSA model trained on a fictional dataset will output word representations that are more abstract, and therefore predict analogies
more similarly to humans. We will examine the correlations between the outcomes from the LSA model and human data for analogy
problems provided by Joshua C. Peterson’s research [9]. This will be performed using various distance metrics, including Euclidean and
cosine distances, and genres of training datasets, such as fiction and non-fiction sources. We hypothesize that texts with a higher degree of
abstraction, such as fictional literature, may improve LSA’s ability to relate dissimilar words for analogies. The limitation of LSA compared
to modern models is that it lacks generalizability to other tasks because the datasets need to be hand-picked for comparable performance.
Moreover, this comparative analysis can be extended to word2vec and GloVe, and can be broken down into more specific or granular
categories of genres of texts.
