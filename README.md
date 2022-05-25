# A Survey and an Empirical Evaluation of Multi-view Clustering Approaches
This reporsity is a collection of state-of-the-art (SOTA), novel incomplete and complete multi-view clustering (papers, codes and datasets). Any problems, please contact lhzhou@ynu.edu.cn, dugking@mail.ynu.edu.cn and lu983760699@gmail.com. If you find this repository useful to your research or work, it is really appreciated to star this repository. :heart:

## What's Multi-view data?
Multi-view data means that the same sample is described from different perspectives, and each perspective describes a class of features of the sample, called a view. In other words, the same sample can be represented by multiple heterogeneous features and each feature representation corresponds to a view. For example, a) a web document is represented by its url and words on the page, b) a web image is depicted by its surrounding text separate to the visual information, c) images of a 3D sample taken from different viewpoints, d) video clips are combinations of audio signals and visual frames, e) multilingual documents have one view in each language. 
![an intuitive example of multi-view data](img/data.png)


## What's Multi-view clustering?
Multi-view clustering (MVC) aims to group samples (objects/instances/points) with similar structures or patterns into the same group (cluster) and samples with dissimilar ones into different groups by combining the available feature information of different views and searching for consistent clusters across different views.
![multi-view clustering](img/clustering.png)

<!-- ## What's incomplete Multi-view clsutering?
Multi-view clustering (MVC) aims to group samples (objects/instances/points) with similar structures or patterns into the same group (cluster) and samples with dissimilar ones into different groups by combining the available feature information of different views and searching for consistent clusters across different views. -->

## 
## Papers

# The information fusion strategy


## early-fusion：


<!-- 1.  \[[paper]()|[code]()] -->

### Late fusion：
1. Partition level multiview subspace clustering \[[paper](https://doi.org/10.1016/j.neunet.2019.10.010)|[code](https://github.com/sckangz/PMSC)]

2. A co-training approach for multi-view spectral clustering \[[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.221.6302&rep=rep1&type=pdf)|[code]] 



# The clustering routine

# one-step routine
1. Partition level multiview subspace clustering \[[paper](https://doi.org/10.1016/j.neunet.2019.10.010)|[code](https://github.com/sckangz/PMSC)]

### two-step routine

# The weighting strategy

1. Self-weighted Multiview Clustering with Multiple Graphs \[[paper](https://www.ijcai.org/proceedings/2017/0357.pdf)|[code](https://github.com/kylejingli/SwMC-IJCAI17)]

2. Multiview spectral embedding \[[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5415552)|[code](https://github.com/rciszek/mse)] 

3. Multi-view content-context information bottleneck for image clustering \[[paper](https://doi.org/10.1016/j.eswa.2021.115374)|[code]] 

4. Parameter-free auto-weighted multiple graph learning: a framework for multiview clustering and  semi-supervised classification \[[paper](https://www.ijcai.org/Proceedings/16/Papers/269.pdf)|[code](https://github.com/kylejingli/AMGL-IJCAI16)]

5. 基于两级权重的多视角聚类 \[[paper](http://qikan.cqvip.com/Qikan/Article/ReadIndex?id=7106866589&info=XP1LB9m8HlJHlvrlgLmLWaqtt3uIZQDhpLMW8JGCuj9lpe6ARTZy9Q%3d%3d)|[code]]

6. Confidence level auto-weighting robust multi-view subspace clustering \[[paper](https://doi.org/10.1016/j.neucom.2021.12.029)|[code]]

7. Weighted multi-view clustering with feature selection  \[[paper](https://doi.org/10.1016/j.patcog.2015.12.007)|[code]]

8. Two-level weighted collaborative k-means for multi-view clustering \[[paper](https://doi.org/10.1016/j.knosys.2018.03.009)|[code](https://github.com/dugzzuli/code-of-TW-Co-kmeans)]

9. Weighted multi-view co-clustering (WMVCC) for sparse data \[[paper](https://doi.org/10.1007/s10489-021-02405-3)|[code]]

10. A cluster-weighted kernel K-means method for multi-view clustering\[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/5922)|[code]] 

11. Multi-graph fusion for multi-view spectral clustering. Knowledge-Based Systems\[[paper](https://doi.org/10.1016/j.knosys.2019.105102)|[code]]

12. 一种双重加权的多视角聚类方法\[[paper](https://cjc.ict.ac.cn/online/onlinepaper/08177-胡世哲-202094103146.pdf)|[code]]

13. View-Wise Versus Cluster-Wise Weight: Which Is Better for Multi-View Clustering?\[[paper]|[code]]

<!-- 1.  \[[paper]()|[code]] -->
# Spectral clustering-based approaches

1. Multi-view clustering via canonical correlation analysis\[[paper](https://doi.org/10.1145/1553374.1553391)|[code]]

2. Multi-view kernel spectral clustering\[[paper](https://doi.org/10.1016/j.inffus.2017.12.002)|[code]]

3. Correlational spectral clustering\[[paper](https://doi.org/10.1109/CVPR.2008.4587353)|[code]]

## Co-regularization and co-training spectral clustering

1. Co-regularized multi-view spectral clustering\[[paper](https://proceedings.neurips.cc/paper/2011/hash/31839b036f63806cba3f47b93af8ccb5-Abstract.html)|[code](https://github.com/lkrmbhlz/CRMVSC)]

2. A co-training approach for multi-view spectral clustering\[[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.221.6302&rep=rep1&type=pdf)|[code]]

3. Combining labeled and unlabeled data with co-training\[[paper](https://doi.org/10.1145/279943.279962)|[code]] 

## Constrained spectral clustering

1. Heterogeneous image feature integration via multi-modal spectral clustering\[[paper](https://doi.org/10.1109/CVPR.2011.5995740)|[code]]

2. Robust multi-view spectral clustering via low-rank and sparse decomposition \[[paper](http://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/view/8135)|[code]]

3. Multiview clustering via adaptively weighted procrustes\[[paper](https://doi.org/10.1145/3219819.3220049)|[code]]

4. One-step multi-view spectral clustering\[[paper](https://doi.org/10.1109/TKDE.2018.2873378)|[code]]

5. Multi-graph fusion for multi-view spectral clustering\[[paper](https://doi.org/10.1016/j.knosys.2019.105102)|[code]]

6. multi-view spectral clustering with adaptive graph learning and tensor  schatten p-norm\[[paper](https://doi.org/10.1016/j.neucom.2021.09.052)|[code]]

7. nonnegative embedding and spectral embedding (NESE) \[[paper]|[code]]

8. Constrained nonnegative embedding and spectral embedding (CNESE)\[[paper]|[code]]

9. Low-rank tensor constrained co-regularized multi-view spectral clustering\[[paper](https://doi.org/10.1016/j.neunet.2020.08.019)|[code]]

## Fast spectral clustering 

1. Large-scale multi-view spectral clustering via bipartite graph\[[paper](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9641)|[code]()]

2. Refining a k-nearest neighbor graph for a computationally efficient spectral  clustering\[[paper](https://doi.org/10.1016/j.patcog.2021.107869)|[code]]

3. Multi-view clustering based on generalized low rank approximation \[[paper](https://doi.org/10.1016/j.neucom.2020.08.049)|[code]]

4. Multi-view spectral clustering by simultaneous consensus graph learning and discretization\[[paper](https://doi.org/10.1016/j.knosys.2021.107632)|[code]]
<!-- 1.  \[[paper]()|[code]] -->

# NMF-based approaches 

1. Multi-view clustering via joint nonnegative matrix factorization\[[paper](https://doi.org/10.1137/1.9781611972832.28)|[code]]

2. Multi-view clustering via concept factorization with local manifold regularization\[[paper](https://doi.org/10.1109/ICDM.2016.0167)|[code]]

3. Multi-view clustering via multi-manifold regularized non-negative matrix factorization\[[paper](https://doi.org/10.1016/j.neunet.2017.02.003)|[code]]

4. Semi-supervised multi-view clustering with graph-regularized partially shared non-negative matrix  factorization\[[paper](https://doi.org/10.1016/j.knosys.2019.105185)|[code]] 

5. Semi-supervised multi-view clustering based on constrained nonnegative matrix factorization\[[paper](https://doi.org/10.1016/j.knosys.2019.06.006)|[code]]

6. Semi-supervised multi-view clustering based on orthonormality-constrained nonnegative matrix factorization\[[paper](https://doi.org/10.1016/j.ins.2020.05.073)|[code]]

7. Multi-view clustering by non-negative matrix factorization with co-orthogonal constraints\[[paper](https://doi.org/10.1016/j.knosys.2020.105582)|[code]] 

8. Dual regularized multi-view non-negative matrix factorization for clustering\[[paper](https://doi.org/10.1016/j.neucom.2017.10.023)|[code]]

9. A network-based sparse and multi-manifold regularized multiple non-negative matrix factorization for multi-view clustering\[[paper](https://doi.org/10.1016/j.eswa.2021.114783)|[code]]

10. Multi-view clustering with the cooperation of visible and hidden views\[[paper](https://doi.org/10.1109/TKDE.2020.2983366)|[code]]

## Fast NMF 

1. Binary Multi-View Clustering\[[paper](https://doi.org/10.1109/TPAMI.2018.2847335)|[code]]

2. Fast Multi-View Clustering via Nonnegative and Orthogonal Factorization\[[paper](https://doi.org/10.1109/TIP.2020.3045631)|[code]] 

## Deep NMF  

1. Multi-View Clustering via Deep Matrix Factorization\[[paper](http://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14647)|[code]]

2. Multi-view clustering via deep concept factorization\[[paper](https://doi.org/10.1016/j.knosys.2021.106807)|[code]]

3. Deep Multi-View Concept Learning\[[paper](https://doi.org/10.24963/ijcai.2018/402)|[code]] 

4. Deep graph regularized non-negative matrix factorization for multi-view clustering\[[paper](https://doi.org/10.1016/j.neucom.2019.12.054)|[code]]

5. Multi-view clustering via deep matrix factorization and partition alignment\[[paper](https://doi.org/10.1145/3474085.3475548)|[code]]

6. Deep multiple non-negative matrix factorization for multi-view clustering\[[paper](https://doi.org/10.3233/IDA-195075)|[code]]

# Multiple kernel learning

1. Learning non-linear combinations of kernels\[[paper](https://proceedings.neurips.cc/paper/2009/hash/e7f8a7fb0b77bcb3b283af5be021448f-Abstract.html)|[code]]

2. Multi-View Clustering with Multiple Kernels\[[paper]|[code]]

3. (Ren & Li et al. 2020 LLMKL) (Ren & Lei et al. 2021 SLMKC)\[[paper]|[code]]

4. (Huang & Kang & Tsang 2019 MVCMK)\[[paper]|[code]] 

5. (Chen&Xiao et al. 2020 JLMVC)\[[paper]|[code]]

6. Kernelized Multi-view Subspace Clustering via Auto-weighted Graph Learning\[[paper](https://doi.org/10.1007/s10489-021-02365-8)|[code]]  
<!-- 1.  \[[paper]()|[code]] -->

# Graph learning

1. Refining a k-nearest neighbor graph for a computationally efficient spectral  clustering\[[paper](https://doi.org/10.1016/j.patcog.2021.107869)|[code]]

2. (Tang & Liu et al. 2018)

3. (Kang &Pan et al. 2019)

4. (Zhan, Zhang, et al. 2018 MVGL)

5. Multi- view projected clustering with graph learning\[[paper](https://doi.org/10.1016/j.neunet.2020.03.020)|[code]]

6. (Wang, Nie, et al. 2020  SwMPC)

7. Learning robust affinity graph representation for multi-view clustering\[[paper](https://doi.org/10.1016/j.ins.2020.06.068)|[code]]

8. GMC: Graph-based multi-view clustering\[[paper](https://doi.org/10.1109/TKDE.2019.2903810)|[code]]

9. Multiview consensus graph clustering\[[paper](https://doi.org/10.1109/TIP.2018.2877335)|[code]]

10. A study of graph-based system for multi-view clustering. Knowledge-Based Systems\[[paper]|[code]]

11. Multi-view Clustering with Latent Low-rank Proxy Graph Learning\[[paper](https://doi.org/10.1007/s12559-021-09889-8)|[code]]

12. Learning latent low-rank and sparse embedding for robust image feature extractio\[[paper](https://doi.org/10.1109/TIP.2019.2938859)|[code]]

13. Robust multi-view graph clustering in latent energy-preserving embedding space\[[paper](https://doi.org/10.1016/j.ins.2021.05.025)|[code]]

14. Robust multi-view data clustering with multi-view capped-norm k-means\[[paper](https://doi.org/10.1016/j.neucom.2018.05.072)|[code]]

# Embedding learning

1. Robust multi-view graph clustering in latent energy-preserving embedding space\[[paper](https://doi.org/10.1016/j.ins.2021.05.025)|[code]]

2. COMIC: Multi-view clustering without parameter selection\[[paper](http://proceedings.mlr.press/v97/peng19a.html)|[code]]

3. Multi-view clustering in latent embedding space\[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/5756)|[code]]

4. Relaxed multi-view clustering in latent embedding space\[[paper](https://doi.org/10.1016/j.inffus.2020.10.013)|[code]]

5. Auto-weighted multi-view clustering via spectral embedding\[[paper](https://doi.org/10.1016/j.neucom.2020.02.071)|[code]]

6. Robust graph-based multi-view clustering in latent embedding space\[[paper](https://doi.org/10.1007/s13042-021-01421-6)|[code]]

7. Efficient correntropy-based multi-view clustering with anchor graph embedding\[[paper](https://doi.org/10.1016/j.neunet.2021.11.027)|[code]]

8. Self-supervised discriminative feature learning for multi-view clustering\[[paper](https://arxiv.org/abs/2103.15069)|[code]]

9. Deep Multiple Auto-Encoder-Based Multi-view Clustering\[[paper](https://doi.org/10.1007/s41019-021-00159-z)|[code]]

10. Joint deep multi-view learning for image clustering\[[paper](https://doi.org/10.1109/TKDE.2020.2973981)|[code]]

11. Deep embedded multi-view clustering with collaborative training\[[paper](https://doi.org/10.1016/j.ins.2020.12.073)|[code]]

12. Trio-based collaborative multi-view graph clustering with multiple constraints\[[paper](https://doi.org/10.1016/j.ipm.2020.102466)|[code]] 

14. Multi-view graph embedding clustering network: Joint self-supervision and block diagonal representation\[[paper](https://doi.org/10.1016/j.neunet.2021.10.006)|[code]] 

15. Multi-view fuzzy clustering of deep random walk and sparse low-rank embedding\[[paper](https://doi.org/10.1016/j.ins.2021.11.075)|[code]]

16. Differentiable Bi-Sparse Multi-View Co-Clustering\[[paper](https://doi.org/10.1109/TSP.2021.3101979)|[code]]

# Alignment learning

1. Multi-view Clustering via Late Fusion Alignment Maximization\[[paper](https://doi.org/10.24963/ijcai.2019/524)|[code]]

2. End-to-end adversarial-attention network for multi-modal clustering\[[paper](https://openaccess.thecvf.com/content\_CVPR\_2020/html/Zhou\_End-to-End\_Adversarial-Attention\_Network\_for\_Multi-Modal\_Clustering\_CVPR\_2020\_paper.html)|[code]]

3. Reconsidering representation alignment for multi-view clustering\[[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Trosten\_Reconsidering\_Representation\_Alignment\_for\_Multi-View\_Clustering\_CVPR\_2021\_paper.html)|[code]]

4. Multiview Subspace Clustering With Multilevel Representations and Adversarial Regularization\[[paper]|[code]]

5. Partially view-aligned clustering\[[paper](https://proceedings.neurips.cc/paper/2020/hash/1e591403ff232de0f0f139ac51d99295-Abstract.html)|[code]]

# Subspace learning

1. Consistent and diverse multi-View subspace clustering with structure constraint\[[paper](https://doi.org/10.1016/j.patcog.2021.108196)|[code]]

2. Consistent and specific multi-view subspace clustering\[[paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16212)|[code]] 

3. Flexible Multi-View Representation Learning for Subspace Clustering\[[paper](https://doi.org/10.24963/ijcai.2019/404)|[code]]

4. Learning a joint affinity graph for multiview subspace clustering\[[paper](https://doi.org/10.1109/TMM.2018.2889560)|[code]] 

5. Exclusivity-consistency regularized multi-view subspace clustering\[[paper](https://doi.org/10.1109/CVPR.2017.8)|[code]] 

6. Multi-view subspace clustering with intactness-aware similarity\[[paper](https://doi.org/10.1016/j.patcog.2018.09.009)|[code]]

7. Diversity-induced multi-view subspace clustering\[[paper](https://doi.org/10.1109/CVPR.2015.7298657)|[code]]

8. Split multiplicative multi-view subspace clustering\[[paper](https://doi.org/10.1109/TIP.2019.2913096)|[code]]

9. Learning a consensus affinity matrix for multi-view clustering via subspaces merging on Grassmann manifold\[[paper](https://doi.org/10.1016/j.ins.2020.07.059)|[code]] 

10. Clustering on multi-layer graphs via subspace analysis on Grassmann manifolds\[[paper](https://doi.org/10.1109/TSP.2013.2295553)|[code]]

11. Deep multi-view subspace clustering with unified and discriminative learning\[[paper](https://doi.org/10.1109/TMM.2020.3025666)|[code]] 

12. Attentive multi-view deep subspace clustering net\[[paper](https://doi.org/10.1016/j.neucom.2021.01.011)|[code]]

13. Dual shared-specific multiview subspace clustering\[[paper](https://doi.org/10.1109/TCYB.2019.2918495)|[code]]

14. Multi-view subspace clustering with consistent and view-specific latent factors and coefficient matrices\[[paper](https://doi.org/10.1109/IJCNN52387.2021.9534421)|[code]] 

15. Robust low-rank kernel multi-view subspace clustering based on the schatten p-norm and correntropy\[[paper](https://doi.org/10.1016/j.ins.2018.10.049)|[code]]

16. Multiple kernel low-rank representation-based robust multi-view subspace clustering\[[paper](https://doi.org/10.1016/j.ins.2020.10.059)|[code]]

17. One-step kernel multi-view subspace clustering\[[paper](https://doi.org/10.1016/j.knosys.2019.105126)|[code]]

18. Deep low-rank subspace ensemble for multi-view clustering\[[paper](https://doi.org/10.1016/j.ins.2019.01.018)|[code]]

19. Multi-view subspace clustering with adaptive locally consistent graph regularization\[[paper](https://doi.org/10.1007/s00521-021-06166-5)|[code]]

20. Multi-view subspace clustering networks with local and global graph information\[[paper](https://doi.org/10.1016/j.neucom.2021.03.115)|[code]] 

21. Deep Multimodal Subspace Clustering Networks\[[paper](https://doi.org/10.1109/JSTSP.2018.2875385)|[code]] -

22. Multi-view Deep Subspace Clustering Networks\[[paper](http://arxiv.org/abs/1908.01978)|[code]] 

23. Multiview subspace clustering via tensorial t-product representation\[[paper](https://doi.org/10.1109/TNNLS.2018.2851444)|[code]]

24. Latent complete row space recovery for multi-view subspace clustering\[[paper](https://doi.org/10.1109/TIP.2020.3010631)|[code]]

25. Fast Parameter-Free Multi-View Subspace Clustering With Consensus Anchor Guidance\[[paper](https://doi.org/10.1109/TIP.2021.3131941)|[code]]

26. Multi-view subspace clustering via partition fusion. Information Sciences\[[paper]|[code]] 

27. Semi-Supervised Structured Subspace Learning for Multi-View Clustering\[[paper](https://doi.org/10.1109/TIP.2021.3128325)|[code]] 

28. 双加权多视角子空间聚类算法\[[paper]|[code]] 

# Self-paced learning 

1. Self-paced learning for latent variable models\[[paper](https://proceedings.neurips.cc/paper/2010/hash/e57c6b956a6521b28495f2886ca0977a-Abstract.html)|[code]] 

2. Multi-view self-paced learning for clustering\[[paper](http://ijcai.org/Abstract/15/558)|[code]] 

3. Self-paced and auto-weighted multi-view clustering\[[paper](https://doi.org/10.1016/j.neucom.2019.11.104)|[code]]

4. Dual self-paced multi-view clustering\[[paper](https://doi.org/10.1016/j.neunet.2021.02.022)|[code]] 

# Co-Clustering-based approaches

1. A generalized maximum entropy approach to bregman co-clustering and matrix approximation\[[paper](http://dl.acm.org/citation.cfm?id=1314563)|[code]] 

2. Multi-view information-theoretic co-clustering for co-occurrence data\[[paper](https://doi.org/10.1609/aaai.v33i01.3301379)|[code]] 

3. Dynamic auto-weighted multi-view co-clustering\[[paper](https://doi.org/10.1016/j.patcog.2019.107101)|[code]] 

4. Auto-weighted multi-view co-clustering with bipartite graphs\[[paper](https://doi.org/10.1016/j.ins.2019.09.079)|[code]]

5. Auto-weighted multi-view co-clustering via fast matrix factorization\[[paper](https://doi.org/10.1016/j.patcog.2020.107207)|[code]]

6. Differentiable Bi-Sparse Multi-View Co-Clustering\[[paper](https://doi.org/10.1109/TSP.2021.3101979)|[code]] 

7. Weighted multi-view co-clustering (WMVCC) for sparse data\[[paper](https://doi.org/10.1007/s10489-021-02405-3)|[code]] 


# Multi-task-based approaches

1. Multi-task multi-view clustering for non-negative data\[[paper](http://ijcai.org/Abstract/15/569)|[code]] 

2. A Multi-task Multi-view based Multi-objective Clustering Algorithm\[[paper](https://doi.org/10.1109/ICPR48806.2021.9412053)|[code]]

3. Multi-task multi-view clustering\[[paper](https://doi.org/10.1109/TKDE.2016.2603983)|[code]]

4. Co-clustering documents and words using bipartite spectral graph partitioning\[[paper](https://doi.org/10.1145/502512.502550)|[code]] 

5. Self-paced multi-task multi-view capped-norm clustering\[[paper](https://doi.org/10.1007/978-3-030-04212-7\_18)|[code]]

6.  Learning task-driving affinity matrix for accurate multi-view clustering through tensor subspace learning\[[paper](https://doi.org/10.1016/j.ins.2021.02.054)|[code]]


# Incomplete Multi-view clustering 

1. Doubly aligned incomplete multi-view clustering\[[paper](http://arxiv.org/abs/1903.02785)|[code]]

## Imputation-based IMVC Incomplete Multi-view clustering 

1. Incomplete multiview spectral clustering with adaptive graph learning\[[paper](https://doi.org/10.1109/TCYB.2018.2884715)|[code]]

2. Late fusion incomplete multi-view clustering\[[paper](https://doi.org/10.1109/TPAMI.2018.2879108)|[code]]

3. Consensus graph learning for incomplete multi-view clustering\[[paper](https://doi.org/10.1007/978-3-030-16148-4\_41)|[code]] 

4. Multi-view kernel completion\[[paper](http://arxiv.org/abs/1602.02518)|[code]] 

5. Unified embedding alignment with missing views inferring for incomplete multi-view clustering\[[paper](https://doi.org/10.1609/aaai.v33i01.33015393)|[code]]

6. One-Stage Incomplete Multi-view Clustering via Late Fusion\[[paper](https://doi.org/10.1145/3474085.3475204)|[code]]

7. Spectral perturbation meets incomplete multi-view data\[[paper](https://doi.org/10.24963/ijcai.2019/510)|[code]]

8. Efficient and effective regularized incomplete multi-view clustering\[[paper](https://doi.org/10.1109/TPAMI.2020.2974828)|[code]]

9. Adaptive partial graph learning and fusion for incomplete multi‐view clustering\[[paper](https://doi.org/10.1002/int.22655)|[code]] 

10. Unified tensor framework for incomplete multi-view clustering and missing-view inferring\[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/17231)|[code]]

11. Incomplete multi-view clustering with cosine similarity\[[paper](https://doi.org/10.1016/j.patcog.2021.108371)|[code]]

## Transformation-based IMVC

1. Partial multi-view clustering via consistent GAN\[[paper](https://doi.org/10.1109/ICDM.2018.00174)|[code]] 

2. One-step multi-view subspace clustering with incomplete views\[[paper](https://doi.org/10.1016/j.neucom.2021.01.080)|[code]]

3. Consensus guided incomplete multi-view spectral clustering\[[paper](https://doi.org/10.1016/j.neunet.2020.10.014)|[code]] 

4. Incomplete multi-view subspace clustering with adaptive instance-sample mapping and deep feature fusion\[[paper](https://doi.org/10.1007/s10489-020-02138-9)|[code]]

5. Dual Alignment Self-Supervised Incomplete Multi-View Subspace Clustering Network\[[paper](https://doi.org/10.1109/LSP.2021.3120311)|[code]]

6. Structural Deep Incomplete Multi-view Clustering Network\[[paper](https://doi.org/10.1145/3459637.3482192)|[code]]

## The unified IMVC

1. Complete/incomplete multi‐view subspace clustering via soft block‐diagonal‐induced regulariser\[[paper](https://doi.org/10.1049/cvi2.12077)|[code]] 

2. A novel consensus learning approach to incomplete multi-view clustering\[[paper](https://doi.org/10.1016/j.patcog.2021.107890)|[code]]

3. Adaptive graph completion based incomplete multi-view clustering\[[paper](https://doi.org/10.1109/TMM.2020.3013408)|[code]] 

4. Incomplete multi-view clustering via contrastive prediction\[[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Lin\_COMPLETER\_Incomplete\_Multi-View\_Clustering\_via\_Contrastive\_Prediction\_CVPR\_2021\_paper.html)|[code]] 

## Uncertain multi-view clustering

1. Outlier-robust multi-view clustering for uncertain data\[[paper](https://doi.org/10.1016/j.knosys.2020.106567)|[code]] 

2. Multi-view spectral clustering for uncertain objects\[[paper](https://doi.org/10.1016/j.ins.2020.08.080)|[code]] 

## Incremental multi-view clustering

1. (Miao, Zhang, Hu, & W ang, 2020)

2. Incremental multi-view spectral clustering\[[paper](https://doi.org/10.1016/j.knosys.2019.02.036)|[code]]

3. Incremental multi-view spectral clustering with sparse and connected graph learning\[[paper](https://doi.org/10.1016/j.neunet.2021.08.031)|[code]]

4. Multi-graph fusion for multi-view spectral clustering\[[paper](http://arxiv.org/abs/1909.06940)|[code]] 

5. Incremental learning through deep adaptation\[[paper](https://doi.org/10.1109/TPAMI.2018.2884462)|[code]]

# Code
<!-- 1.  \[[paper]()|[code]] -->
- ## utils.py

  1. ### **load_graph_data**: load graph datasets

  2. ### **load_data**: load non-graph datasets

  3. ### **normalize_adj**: normalize the adjacency matrix

  4. ### **diffusion_adj**: calculate the graph diffusion

  5. ### **construct_graph**: construct the knn graph for non-graph datasets

  6. ### **numpy_to_torch**: convert numpy to torch

  7. ### **torch_to_numpy**: convert torch to numpy

- ## clustering.py

  1. ### **setup_seed**: fix the random seed

  2. ### **evaluation**: evaluate the performance of clustering

  3. ### **k_means**: K-means algorithm

- ## visualization.py

  1. ### **t_sne**: t-SNE algorithm

  2. ### **similarity_plot**: visualize cosine similarity matrix of the embedding or feature







# Datasets Details

## 	1.Text Datasets

| Dataset                   | #views | #classes | #instances | F-Type(#View1)     | F-Type(#View2)        | F-Type(#View3)    | F-Type(#View4)  | F-Type(#View5)  | F-Type(#View6)                                      |
| ------------------------- | ------ | -------- | ---------- | ------------------ | --------------------- | ----------------- | --------------- | --------------- | --------------------------------------------------- |
| 3Sources                  | 3      | 6        | 169        | BBC(3560)          | Reuters(3631)         | Guardian(3068)    |                 |                 | http://mlg.ucd.ie/datasets/3sources.html            |
| BBC                       | 4      | 5        | 685        | seg1(4659)         | seg2(4633)            | seg3(4665)        | seq4(4684)      |                 | http://mlg.ucd.ie/datasets/segment.html.            |
| BBCSport [87]             | 3      | 5        | 544/282    | seq1(3183/2582)    | seg2(3203/2544)       | / seq3 (2465)     |                 |                 | http://mlg.ucd.ie/datasets/segment.html             |
| Newsgroup(text) [71] [77] | 3      | 5        | 500        | -2000              | -2000                 | -2000             |                 |                 | H:\Multi_view_Clustering\data\20NewsGroups.mat      |
| Reuters(KMSC-AGL) [87]    | 5      | 6        | 600/1200   | English(9749/2000) | French(9109/2000)     | German(7774/2000) | / Italian(2000) | / Spanish(2000) | https://lig-membres.imag.fr/grimal/data.html        |
| Reuters-21578             | 5      | 6        | 1500       | English(21531)     | French(24892)         | German(34251)     | Italian(15506)  | Spanish(11547)  | H:\Multi_view_Clustering\data                       |
| Citeseer s(text) [87]     | 2      | 6        | 3312       | citations(4732)    | word vector(3703)     |                   |                 |                 | https://lig-membres.imag.fr/grimal/data.html        |
| Cornell                   | 2      | 5        | 195        | Citation (195)     | Content (1703)        |                   |                 |                 | https://lig-membres.imag.fr/grimal/data.html        |
| Texas                     | 2      | 5        | 187        | Citation (187)     | Content (1398)        |                   |                 |                 | https://lig-membres.imag.fr/grimal/data.html        |
| Washington                | 2      | 5        | 230        | Citation (230)     | Content (2000)        |                   |                 |                 | https://lig-membres.imag.fr/grimal/data.html        |
| Wisconsin                 | 2      | 5        | 265        | Citation (265)     | Content (1703)        |                   |                 |                 | https://lig-membres.imag.fr/grimal/data.html        |
| Wikipedia[58]             | 2      | 10       | 693        |                    |                       |                   |                 |                 | http://www.svcl.ucsd.edu/projects/crossmodal/       |
| Derm [125]                | 2      | 6        | 366        | Clinical (11)      | Histopathological(22) |                   |                 |                 | https://archive.ics.uci.edu/ml/datasets/dermatology |

## 	2.Image Datasets

| Dataset                                  | #views | #classes | #instances     | F-Type(#View1)     | F-Type(#View2)      | F-Type(#View3) | F-Type(#View4) | F-Type(#View5) | F-Type(#View6) | url                                                          |
| ---------------------------------------- | ------ | -------- | -------------- | ------------------ | ------------------- | -------------- | -------------- | -------------- | -------------- | ------------------------------------------------------------ |
| Yale [87]                                | 3      | 15       | 165            | Intensity (4096)   | LBP(33040           | Gabor (6750)   |                |                |                | http://vision.ucsd.edu/content/yale-face-database            |
| Yale-B(KMSC-AGL)                         | 3      | 10       | 650            | Intensity(2500)    | LBP(3304)           | Gabor(6750)    |                |                |                | http://vision.ucsd.edu/content/extended-yale-face-database-b-b |
| Extended-Yale[172]                       | 2      | 28       | 1774           | LBP(900)           | COV(45)             |                |                |                |                | [**http://vision.ucsd.edu/leekc/ExtYaleDatabase/ExtYaleB/html**](http://vision.ucsd.edu/leekc/ExtYaleDatabase/ExtYaleB/html) |
| VIS/NIR(KMSC-AGL)                        | 2      | 22       | 1056           | VL(10000)          | NIRI(10000)         |                |                |                |                |                                                              |
| ORL [87]                                 | 3      | 40       | 400            | Intensity(4096)    | LBP(3304)           | Gabor(6750)    |                |                |                | E:\ConsistentGraphLearning_geneGraph\data                    |
| (MVC-DMF-PA)                             | 4      | 40       | 400            | GIST(512)          | LBP (59)            | HOG(864)       | Centrist(254)  |                |                |                                                              |
| Notting-Hill(KMSC-AGL)                   | 3      | 5        | 550            | Intensity(2000)    | LBP(3304)           | Gabor(6750)    |                |                |                |                                                              |
| YouTube  Faces(BMVC)                     | 3      | 66       | 152549         | CH(768)            | GIST(1024)          | HOG( 1152)     |                |                |                | [**http://www.cs.tau.ac.il/~wolf/ytfaces/**](http://www.cs.tau.ac.il/~wolf/ytfaces/) |
| UCI [173]                                | 3      | 10       | 2000           | FAC (216)          | FOU (76)            | KAR(64)        |                |                |                | H:\Multi_view_Clustering\data                                |
| UCI [173]                                | 3      | 10       | 2000           | FAC (216)          | FOU (76)            | KAR(64)        |                |                |                | H:\Multi_view_Clustering\data                                |
| Digits(LCRSR)                            | 3      | 10       | 2000           | FAC(216)           | FOU(76)             | KAR (64)       |                |                |                | [**https://archive.ics.uci.edu/ml/datasets/Multiple+Features**](https://archive.ics.uci.edu/ml/datasets/Multiple+Features) |
| HW2sources                               | 2      | 10       | 2000           | FOU (76)           | PIX (240)           |                |                |                |                |                                                              |
| Handwritten  (FMVBKM)                    | 6      | 10       | 2000           | FOU(76)            | FAC(216)            | KAR(64)        | PIX(240)       | ZER(47)        | MOR(6)         | [**https://archive.ics.uci.edu/ml/datasets/Multiple+Features**](https://archive.ics.uci.edu/ml/datasets/Multiple+Features) |
| MNIST-USPS  [92]                         | 2      | 10       | 5000           | MNIST(28´28)       | USPS(16´16)         |                |                |                |                | https://github.com/SubmissionsIn/DEMVC/tree/master/data      |
| MNIST-10000[172]                         | 2      | 10       | 10000          | VGG16 FC1(4096)    | Resnet50(2048)      |                |                |                |                | [**http://yann.lecun.com/exdb/mnist/**](http://yann.lecun.com/exdb/mnist/) |
| MNIST-10000(FMVBKM)                      | 3      | 10       | 10000          | ISO(30)            | LDA(9)              | NPE(30)        |                |                |                | E:\ConsistentGraphLearning_geneGraph\data                    |
| Noisy  MNIST-Rotated MNIST [92]          | 2      | 10       | 70000          | Noisy MNIST(28´28) | Rotated             |                |                |                |                | [**https://github.com/SubmissionsIn/DEMVC/tree/master/data**](https://github.com/SubmissionsIn/DEMVC/tree/master/data) |
| NUS-WIDE-Obj  (BMVC) (KMSC-AGL)          | 5      | 31       | 30000          | CH(65)             | CM(226)             | CORR(145)      | ED(74)         | WT(129)        |                | https://pan.baidu.com/s/1zPA56kNu8ItkFqpzY7IzsA#list/path=%2F |
| NUSWIDE(FMVBKM)                          | 6      | 7        | 2400           | CH(64)             | CC(144)             | EDH(73)        | WAV(128)       | BCM(255)       | SIFT(500)      | H:\Multi_view_Clustering\data                                |
| MSRC [134]                               | 5      | 7        | 210            | CM(48)             | LBP(256)            | HOG(100)       | SIFT(200)      | GIST(512)      |                | [**https://www.microsoft.com/en-us/research/project/imageunderstanding/**](https://www.microsoft.com/en-us/research/project/imageunderstanding/) |
| MSRCv1  [87]                             | 5      | 7        | 210            | CM(24)             | HOG(576)            | GIST(512)      | LBP(256)       | GENT(254)      |                | [**https://www.researchgate.net/publication/335857675**](https://www.researchgate.net/publication/335857675) |
| COIL-20  (Ren, Li et al. 2021)           | 3      | 20       | 1440           | Intensity(1024)    | LBP (3304)          | Gabor (6750)   |                |                |                | [**http://www.cs.columbia.edu/CAVE/software/softlib/coil-20.php**](http://www.cs.columbia.edu/CAVE/software/softlib/coil-20.php) |
| Caltech101-7/20/102  (FMVBKM)[92] (BMVC) | 6      | 7/20/102 | 1474/2386/9144 | Gabor(48)          | WM(40)              | Centrist (254) | HOG(1984)      | GIST(512)      | LBP(928)       | [**http://www.vision.caltech.edu/Image   Datasets/Caltech101/**](http://www.vision.caltech.edu/Image Datasets/Caltech101/) |
| MSRA-MM2.0  (DMvNMF)                     | 4      | 25       | 5000           | HSV-CH(64)         | CORRH(144)          | EDH(75)        | WT(128)        |                |                |                                                              |
| Scene(AMCSE)                             | 4      | 8        | 2688           | GIST(512)          | CM(432)             | HOG(256)       | LBP(48)        |                |                |                                                              |
| scene-15  (Ren, Li et al. 2021)          | 3      | 15       | 4485           | GIST(1800)         | PHOG(1180)          | LBP(1240)      |                |                |                | H:\Multi_view_Clustering\data                                |
| Out-Scene  [172]                         | 4      | 8        | 2688           | GIST(512)          | LBP(48)             | HOG(256)       | CM(432)        |                |                | [**https://scholar.googleusercontent.com/scholar?q=cache:Dxo2Hbfln2sJ:scholar.google.com/hl=enas-sdt=0,5**](https://scholar.googleusercontent.com/scholar?q=cache:Dxo2Hbfln2sJ:scholar.google.com/hl=enas-sdt=0,5) |
| Indoor  [134]                            | 6      | 5        | 621            | SURF(200)          | SIFT(200)           | GIST(512)      | HOG(680)       | WT(32)         |                | [**http://web.mit.edu/torralba/www/indoor.html**](http://web.mit.edu/torralba/www/indoor.html) |
| 100leaves  (DMNMF)                       | 3      | 100      | 1600           | TH(64)             | FSM(64)             | SD(64)         |                |                |                | H:\Multi_view_Clustering\data\100leaves                      |
| Animal  with attributes (AWA) (FMVBKM)   | 6      | 50       | 4000/30475     | CH(2688)           | LSS(2000)           | PHOG(252)      | SIFT(2000)     | RGSIFT(2000)   | -2000          |                                                              |
| (FPMVS-CAG)                              |        |          |                |                    |                     |                |                |                |                |                                                              |
| Forest  [125]                            | 2      | 4        | 524            | RS(9)              | GWSV(18)            |                |                |                |                | https://archive.ics.uci.edu/ml/datasets/Forest+type+mapping  |
| Fashion-10K  [92]                        | 2      | 10       | 70000          | Test set(28´28)    | sampled set (28´28) |                |                |                |                | https://github.com/SubmissionsIn/DEMVC/tree/master/data      |
| Event [134]                              | 6      | 8        | 1579           | SURF(500)          | SIFT(500)           | GIST(512)      | HOG(680)       | WT(32)         | LBP(256)       | vision.stanford.edu/lijiali/event  dataset/                  |
| ALOI (GMC)                               | 4      | 100      | 110250         | RGB-CH(77)         | HSV-CH(13)          | CS(64)         | Haralick (64)  |                |                | https://aloi.science.uva.nl/                                 |
| ImageNet  (DMCL)                         | 3      | 50       | 12000          | HSV-CH(64)         | GIST(512)           | SIFT(1000)     |                |                |                | https://image-net.org/download.php                           |
| Corel  [134]                             | 3      | 50       | 5000           | CH (9)             | EDH(18)             | WT (9)         |                |                |                | [**http://www.cais.ntu.edu.sg/˜chhoi/SVMBMAL/**](http://www.cais.ntu.edu.sg/˜chhoi/SVMBMAL/) |
| Cifar-10(BMVC)                           | 3      | 10       | 60000          | CH(768)            | GIST (1024)         | HOG(1152)      |                |                |                | .  https://www.cs.toronto.edu/~kriz/cifar.html               |
| SUN1k  [134]                             | 3      | 10       | 1000           | SIFT(6300)         | HOG(6300)           | TH(10752)      |                |                |                | [**http://vision.princeton.edu/projects/2010/SUN/**](http://vision.princeton.edu/projects/2010/SUN/) |
| Sun397(BMVC)                             | 3      | 397      | 108754         | CH(768)            | GIST (1024)         | HOG(1152)      |                |                |                | [**https://vision.princeton.edu/projects/2010/SUN/**](https://vision.princeton.edu/projects/2010/SUN/) |

## 	3.Rest of data

| Dataset                         | #views                    | #classes                            | #instances          | F-Type(#View1)                              | F-Type(#View2)                     | F-Type(#View3)               | F-Type(#View4) | F-Type(#View5) | F-Type(#View6) | url                                                          |
| ------------------------------- | ------------------------- | ----------------------------------- | ------------------- | ------------------------------------------- | ---------------------------------- | ---------------------------- | -------------- | -------------- | -------------- | ------------------------------------------------------------ |
| Prok [125]                      | 3                         | 4                                   | 551                 | Textual TF-IDF re-weighted word frequencies | Genomic- the proteome  composition | Genomic- the gene repertoire |                |                |                | https://github.com/mbrbic/MultiViewLRSSC/tree/master/datasets |
| Wikipedia [58] [125]            | 2                         | 10                                  | 693/2866            | image                                       | article                            |                              |                |                |                | http://www.svcl.ucsd.edu/projects/crossmodal/                |
| BDGP [92]                       | 5                         |                                     | 2500                | Visual(1750)                                | Textual(79)                        |                              |                |                |                |                                                              |
| NNSpt [134]                     | 2                         | 2                                   | 840                 | image(1024)                                 | TF-IDF(296)                        |                              |                |                |                | http://vision.princeton.edu/projects/2010/SUN/               |
| SentencesNYU  v2 (RGB-D)(CoMVC) | 2                         | 13                                  | 1449                | image (2048)                                | text (300)                         |                              |                |                |                | https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html     |
| VOC (EAMC)                      | 2                         | 20                                  | 5,649               | Image: Gist (512)                           | Text (399)                         |                              |                |                |                | https://deepai.org/dataset/pascal-voc                        |
| NUS-WIDE-C5(NWC)  (EAMC)        | 2                         | 5                                   | 4000                | visual codeword vector(500)                 | annotation vector(1000)            |                              |                |                |                | E:\ConsistentGraphLearning_geneGraph\data                    |
| MIR Flickr  1M (CAGL)           | 4                         | 10                                  | 2000                | HOG(300)                                    | LBP(50)                            | HSV CORRH (114)              | TF-IDF(60)     |                |                | https://press.liacs.nl/mirflickr/mirdownload.html            |
| DTHC [125]                      | 3 cameras                 | Dispersing from  the center quickly | 3 video sequences   | 151 frames/video                            | resolution 135 ×  240              |                              |                |                |                | http://www.escience.cn/people/huyongli/Dongzhimen.html       |
| Lab [125]                       | 4 cameras                 | 4 people                            | 16 video sequences  | 3915 frames/video                           | resolution 144 ×180                |                              |                |                |                | https://cvlab.epflfl.ch/data/data-pom-index-php/             |
| CMU  Mobo(CAGL)                 | 4 videos                  | 24 objects                          | 96 video sequences  | about 300 frames/video                      | resolution 40´40                   |                              |                |                |                | https://www.ri.cmu.edu/publications/the-cmu-motion-of-body-mobo-database/ |
| Honda/UCSD(CAGL)                | at least 2 videos/ person | 20 objects                          | 59 video sequences  | 12 to 645 frames/video                      | resolution 20´20                   |                              |                |                |                | http://vision.ucsd.edu/~iskwak/HondaUCSDVideoDatabase/HondaUCSD.html |
| YouTubeFace_sel (FPMVS-CAG)     | 5                         | 31                                  | 101499              | 64                                          | 512                                | 64                           | 647            | 838            |                | http://www.cs.tau.ac.il/~wolf/ytfaces/                       |
| CCV(CoMVC)                      | 3                         | 20                                  | 6773 YouTube videos | SIFT(5000)                                  | STIP(5000)                         | MFCC(4000)                   |                |                |                | [https://www.ee.columbia.edu/ln/dvmm/https://press.liacs.nl/mirflickr/mirdownload.htmlCCV/](https://www.ee.columbia.edu/ln/dvmm/https:/press.liacs.nl/mirflickr/mirdownload.htmlCCV/) |



<!-- ```
Multi-graph fusion for multi-view spectral clustering. Knowledge-Based Systems
```

```
论文：https://doi.org/10.1016/j.knosys.2019.105102
```

```
一种双重加权的多视角聚类方法
```

```
论文：
```

[Microsoft Word - 8---2019-8-31-08177-胡世哲_new_.doc (ict.ac.cn)](https://cjc.ict.ac.cn/online/onlinepaper/08177-胡世哲-202094103146.pdf)

```
View-Wise Versus Cluster-Wise Weight: Which Is Better for Multi-View Clustering?
```

```
论文：无
```

# Spectral clustering-based approaches

```
Multi-view clustering via canonical correlation analysis
```

```
论文：https://doi.org/10.1145/1553374.1553391
```

```
Multi-view kernel spectral clustering
```

```
论文：https://doi.org/10.1016/j.inffus.2017.12.002
```

```
Correlational spectral clustering
```

```
论文：https://doi.org/10.1109/CVPR.2008.4587353
```

### Co-regularization and co-training spectral clustering

```
Co-regularized multi-view spectral clustering
```

```
论文：https://proceedings.neurips.cc/paper/2011/hash/31839b036f63806cba3f47b93af8ccb5-Abstract.html
```

```
A co-training approach for multi-view spectral clustering
```

   论文：[A Co-training Approach for Multi-view Spectral Clustering (psu.edu)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.221.6302&rep=rep1&type=pdf)

```
Combining labeled and unlabeled data with co-training
```

```
论文：https://doi.org/10.1145/279943.279962
```

### Constrained spectral clustering

```
Heterogeneous image feature integration via multi-modal spectral clustering
```

```
论文：https://doi.org/10.1109/CVPR.2011.5995740
```

```
Robust multi-view spectral clustering via low-rank and sparse decomposition
```

```
论文：http://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/view/8135
```

```
Multiview clustering via adaptively weighted procrustes
```

```
论文：https://doi.org/10.1145/3219819.3220049
```

```
One-step multi-view spectral clustering
```

```
论文：https://doi.org/10.1109/TKDE.2018.2873378
```

```
Multi-graph fusion for multi-view spectral clustering
```

```
论文：https://doi.org/10.1016/j.knosys.2019.105102
```

```
multi-view spectral clustering with adaptive graph learning and tensor  schatten p-norm
```

```
论文：https://doi.org/10.1016/j.neucom.2021.09.052
```

```
nonnegative embedding and spectral embedding (NESE)
```

```
论文：
```

```
Constrained nonnegative embedding and spectral embedding (CNESE)
```

```
论文：无
```

```
Low-rank tensor constrained co-regularized multi-view spectral clustering
```

```
论文：https://doi.org/10.1016/j.neunet.2020.08.019
```

### Fast spectral clustering

```
Large-scale multi-view spectral clustering via bipartite graph
```

```
论文：http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9641
```

```
Refining a k-nearest neighbor graph for a computationally efficient spectral  clustering
```

```
论文：https://doi.org/10.1016/j.patcog.2021.107869
```

```
Multi-view clustering based on generalized low rank approximation
```

```
论文：https://doi.org/10.1016/j.neucom.2020.08.049
```

```
Multi-view spectral clustering by simultaneous consensus graph learning and discretization
```

```
论文：https://doi.org/10.1016/j.knosys.2021.107632
```

# NMF-based approaches

```
Multi-view clustering via joint nonnegative matrix factorization
```

```
论文：https://doi.org/10.1137/1.9781611972832.28
```

```
Multi-view clustering via concept factorization with local manifold regularization
```

```
论文：https://doi.org/10.1109/ICDM.2016.0167
```

```
Multi-view clustering via multi-manifold regularized non-negative matrix factorization
```

```
论文：https://doi.org/10.1016/j.neunet.2017.02.003
```

```
Semi-supervised multi-view clustering with graph-regularized partially shared non-negative matrix  factorization
```

```
论文：https://doi.org/10.1016/j.knosys.2019.105185
```

```
Semi-supervised multi-view clustering based on constrained nonnegative matrix factorization
```

```
论文：https://doi.org/10.1016/j.knosys.2019.06.006
```

```
Semi-supervised multi-view clustering based on orthonormality-constrained nonnegative matrix factorization
```

```
论文：https://doi.org/10.1016/j.ins.2020.05.073
```

```
Multi-view clustering by non-negative matrix factorization with co-orthogonal constraints
```

```
论文：https://doi.org/10.1016/j.knosys.2020.105582
```

```
Dual regularized multi-view non-negative matrix factorization for clustering
```

```
论文：https://doi.org/10.1016/j.neucom.2017.10.023
```

```
A network-based sparse and multi-manifold regularized multiple non-negative matrix factorization for multi-view clustering
```

```
论文：https://doi.org/10.1016/j.eswa.2021.114783
```

```
Multi-view clustering with the cooperation of visible and hidden views
```

```
论文：https://doi.org/10.1109/TKDE.2020.2983366
```

### Fast NMF

```
Binary Multi-View Clustering
```

```
论文：https://doi.org/10.1109/TPAMI.2018.2847335
```

```
Fast Multi-View Clustering via Nonnegative and Orthogonal Factorization
```

```
论文：https://doi.org/10.1109/TIP.2020.3045631
```

### Deep NMF

```
Multi-View Clustering via Deep Matrix Factorization
```

```
论文：http://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14647
```

```
Multi-view clustering via deep concept factorization
```

```
论文：https://doi.org/10.1016/j.knosys.2021.106807
```

```
. Deep Multi-View Concept Learning
```

```
论文：https://doi.org/10.24963/ijcai.2018/402
```

```
Deep graph regularized non-negative matrix factorization for multi-view clustering
```

```
论文：https://doi.org/10.1016/j.neucom.2019.12.054
```

```
Multi-view clustering via deep matrix factorization and partition alignment
```

```
论文：https://doi.org/10.1145/3474085.3475548
```

```
Deep multiple non-negative matrix factorization for multi-view clustering
```

```
论文：https://doi.org/10.3233/IDA-195075
```

# Multiple kernel learning

```
Learning non-linear combinations of kernels
```

```
论文：https://proceedings.neurips.cc/paper/2009/hash/e7f8a7fb0b77bcb3b283af5be021448f-Abstract.html
```

```
Multi-View Clustering with Multiple Kernels
```

```
论文：
```

```
(Ren & Li et al. 2020 LLMKL) (Ren & Lei et al. 2021 SLMKC)
```

```
(Huang & Kang & Tsang 2019 MVCMK)
```

```
(Chen&Xiao et al. 2020 JLMVC)
```

```
Kernelized Multi-view Subspace Clustering via Auto-weighted Graph Learning
```

```
论文：https://doi.org/10.1007/s10489-021-02365-8
```

### Graph learning

```
Refining a k-nearest neighbor graph for a computationally efficient spectral  clustering
```

```
论文：https://doi.org/10.1016/j.patcog.2021.107869
```

```
(Tang & Liu et al. 2018)
```

```
(Kang &Pan et al. 2019)
```

```
(Zhan, Zhang, et al. 2018 MVGL)
```

```
Multi- view projected clustering with graph learning
```

```
论文：https://doi.org/10.1016/j.neunet.2020.03.020
```

```
(Wang, Nie, et al. 2020  SwMPC)
```

```
Learning robust affinity graph representation for multi-view clustering
```

```
论文：https://doi.org/10.1016/j.ins.2020.06.068
```

```
GMC: Graph-based multi-view clustering
```

```
论文：https://doi.org/10.1109/TKDE.2019.2903810
```

```
Multiview consensus graph clustering
```

```
论文：https://doi.org/10.1109/TIP.2018.2877335
```

```
A study of graph-based system for multi-view clustering. Knowledge-Based Systems,
```

```
论文：无
```

```
Multi-view Clustering with Latent Low-rank Proxy Graph Learning
```

```
论文：https://doi.org/10.1007/s12559-021-09889-8
```

```
Learning latent low-rank and sparse embedding for robust image feature extractio
```

```
论文：https://doi.org/10.1109/TIP.2019.2938859
```

```
Robust multi-view graph clustering in latent energy-preserving embedding space
```

```
论文：https://doi.org/10.1016/j.ins.2021.05.025
```

```
Robust multi-view data clustering with multi-view capped-norm k-means
```

```
论文：https://doi.org/10.1016/j.neucom.2018.05.072
```

### Embedding learning

```
Robust multi-view graph clustering in latent energy-preserving embedding space
```

```
论文：https://doi.org/10.1016/j.ins.2021.05.025
```

```
COMIC: Multi-view clustering without parameter selection
```

```
论文:http://proceedings.mlr.press/v97/peng19a.html
```

```
Multi-view clustering in latent embedding space
```

```
论文：https://ojs.aaai.org/index.php/AAAI/article/view/5756
```

```
Relaxed multi-view clustering in latent embedding space
```

```
论文：https://doi.org/10.1016/j.inffus.2020.10.013
```

```
Auto-weighted multi-view clustering via spectral embedding
```

```
论文：https://doi.org/10.1016/j.neucom.2020.02.071
```

```
Robust graph-based multi-view clustering in latent embedding space
```

```
论文：https://doi.org/10.1007/s13042-021-01421-6
```

```
Efficient correntropy-based multi-view clustering with anchor graph embedding
```

```
论文：https://doi.org/10.1016/j.neunet.2021.11.027
```

```
Self-supervised discriminative feature learning for multi-view clustering
```

```
论文：https://arxiv.org/abs/2103.15069
```

```
Deep Multiple Auto-Encoder-Based Multi-view Clustering
```

```
论文：https://doi.org/10.1007/s41019-021-00159-z
```

```
Joint deep multi-view learning for image clustering
```

```
论文：https://doi.org/10.1109/TKDE.2020.2973981
```

```
Deep embedded multi-view clustering with collaborative training
```

```
论文：https://doi.org/10.1016/j.ins.2020.12.073
```

```
Trio-based collaborative multi-view graph clustering with multiple constraints
```

```
论文：https://doi.org/10.1016/j.ipm.2020.102466
```

```
Multi-view graph embedding clustering network: Joint self-supervision and block diagonal representation
```

```
论文：https://doi.org/10.1016/j.neunet.2021.10.006
```

```
Multi-view fuzzy clustering of deep random walk and sparse low-rank embedding
```

```
论文：https://doi.org/10.1016/j.ins.2021.11.075
```

```
Differentiable Bi-Sparse Multi-View Co-Clustering
```

```
论文：https://doi.org/10.1109/TSP.2021.3101979
```

### Alignment learning

```
Multi-view Clustering via Late Fusion Alignment Maximization
```

```
论文：https://doi.org/10.24963/ijcai.2019/524
```

```
End-to-end adversarial-attention network for multi-modal clustering
```

```
论文：https://openaccess.thecvf.com/content
```

\_CVPR\_2020/html/Zhou\_End-to-End\_Adversarial-Attention\_Network\_for\_Multi-Modal\_Clustering\_CVPR\_2020\_paper.html

```
Reconsidering representation alignment for multi-view clustering
```

```
论文：https://openaccess.thecvf.com/content/CVPR2021/html/Trosten
```

\_Reconsidering\_Representation\_Alignment\_for\_Multi-View\_Clustering\_CVPR\_2021\_paper.html

```
Multiview Subspace Clustering With Multilevel Representations and Adversarial Regularization
```

```
论文：无
```

```
Partially view-aligned clustering
```

```
论文：https://proceedings.neurips.cc/paper/2020/hash/1e591403ff232de0f0f139ac51d99295-Abstract.html
```

# Subspace learning

```
Consistent and diverse multi-View subspace clustering with structure constraint
```

```
论文：https://doi.org/10.1016/j.patcog.2021.108196
```

```
Consistent and specific multi-view subspace clustering
```

```
论文：https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16212
```

```
Flexible Multi-View Representation Learning for Subspace Clustering
```

```
论文：https://doi.org/10.24963/ijcai.2019/404
```

```
Learning a joint affinity graph for multiview subspace clustering
```

```
论文：https://doi.org/10.1109/TMM.2018.2889560
```

```
Exclusivity-consistency regularized multi-view subspace clustering
```

```
论文：https://doi.org/10.1109/CVPR.2017.8
```

```
Multi-view subspace clustering with intactness-aware similarity
```

```
论文：https://doi.org/10.1016/j.patcog.2018.09.009
```

```
Diversity-induced multi-view subspace clustering
```

```
论文：https://doi.org/10.1109/CVPR.2015.7298657
```

```
Split multiplicative multi-view subspace clustering
```

```
论文：https://doi.org/10.1109/TIP.2019.2913096
```

```
Learning a consensus affinity matrix for multi-view clustering via subspaces merging on Grassmann manifold
```

```
论文：https://doi.org/10.1016/j.ins.2020.07.059
```

```
Clustering on multi-layer graphs via subspace analysis on Grassmann manifolds
```

```
论文：https://doi.org/10.1109/TSP.2013.2295553
```

```
Deep multi-view subspace clustering with unified and discriminative learning
```

```
论文：https://doi.org/10.1109/TMM.2020.3025666
```

```
Attentive multi-view deep subspace clustering net
```

```
论文：https://doi.org/10.1016/j.neucom.2021.01.011
```

```
Dual shared-specific multiview subspace clustering
```

```
论文：https://doi.org/10.1109/TCYB.2019.2918495
```

```
Multi-view subspace clustering with consistent and view-specific latent factors and coefficient matrices
```

```
论文：https://doi.org/10.1109/IJCNN52387.2021.9534421
```

```
Robust low-rank kernel multi-view subspace clustering based on the schatten p-norm and correntropy
```

```
论文：https://doi.org/10.1016/j.ins.2018.10.049
```

```
Multiple kernel low-rank representation-based robust multi-view subspace clustering
```

```
论文：https://doi.org/10.1016/j.ins.2020.10.059
```

```
One-step kernel multi-view subspace clustering
```

```
论文：https://doi.org/10.1016/j.knosys.2019.105126
```

```
Deep low-rank subspace ensemble for multi-view clustering
```

```
论文：https://doi.org/10.1016/j.ins.2019.01.018
```

```
Multi-view subspace clustering with adaptive locally consistent graph regularization
```

```
论文：https://doi.org/10.1007/s00521-021-06166-5
```

```
Multi-view subspace clustering networks with local and global graph information
```

```
论文：https://doi.org/10.1016/j.neucom.2021.03.115
```

```
Deep Multimodal Subspace Clustering Networks
```

```
论文：https://doi.org/10.1109/JSTSP.2018.2875385
```

```
Multi-view Deep Subspace Clustering Networks
```

```
论文：http://arxiv.org/abs/1908.01978
```

```
Multiview subspace clustering via tensorial t-product representation
```

```
论文：https://doi.org/10.1109/TNNLS.2018.2851444
```

```
Latent complete row space recovery for multi-view subspace clustering
```

```
论文：https://doi.org/10.1109/TIP.2020.3010631
```

```
Fast Parameter-Free Multi-View Subspace Clustering With Consensus Anchor Guidance
```

```
论文：https://doi.org/10.1109/TIP.2021.3131941
```

```
Multi-view subspace clustering via partition fusion. Information Sciences
```

```
论文：无
```

```
Semi-Supervised Structured Subspace Learning for Multi-View Clustering
```

```
论文：https://doi.org/10.1109/TIP.2021.3128325
```

```
双加权多视角子空间聚类算法
```

```
论文：无
```

# Self-paced learning

```
Self-paced learning for latent variable models
```

```
论文：https://proceedings.neurips.cc/paper/2010/hash/e57c6b956a6521b28495f2886ca0977a-Abstract.html
```

```
Multi-view self-paced learning for clustering
```

```
论文：http://ijcai.org/Abstract/15/558
```

```
Self-paced and auto-weighted multi-view clustering
```

```
论文：https://doi.org/10.1016/j.neucom.2019.11.104
```

```
Dual self-paced multi-view clustering
```

```
论文：https://doi.org/10.1016/j.neunet.2021.02.022
```

# Co-Clustering-based approaches

```
A generalized maximum entropy approach to bregman co-clustering and matrix approximation
```

```
论文：http://dl.acm.org/citation.cfm?id=1314563
```

```
Multi-view information-theoretic co-clustering for co-occurrence data
```

```
论文：https://doi.org/10.1609/aaai.v33i01.3301379
```

```
Dynamic auto-weighted multi-view co-clustering
```

```
论文：https://doi.org/10.1016/j.patcog.2019.107101
```

```
Auto-weighted multi-view co-clustering with bipartite graphs
```

```
论文：https://doi.org/10.1016/j.ins.2019.09.079
```

```
Auto-weighted multi-view co-clustering via fast matrix factorization
```

```
论文：https://doi.org/10.1016/j.patcog.2020.107207
```

```
Differentiable Bi-Sparse Multi-View Co-Clustering
```

```
论文：https://doi.org/10.1109/TSP.2021.3101979
```

```
Weighted multi-view co-clustering (WMVCC) for sparse data
```

```
论文：https://doi.org/10.1007/s10489-021-02405-3
```

# Multi-task-based approaches

```
Multi-task multi-view clustering for non-negative data
```

```
论文：http://ijcai.org/Abstract/15/569
```

```
A Multi-task Multi-view based Multi-objective Clustering Algorithm
```

```
论文：https://doi.org/10.1109/ICPR48806.2021.9412053
```

```
Multi-task multi-view clustering
```

```
论文：https://doi.org/10.1109/TKDE.2016.2603983
```

```
Co-clustering documents and words using bipartite spectral graph partitioning
```

```
论文：https://doi.org/10.1145/502512.502550
```

```
Self-paced multi-task multi-view capped-norm clustering
```

```
论文：https://doi.org/10.1007/978-3-030-04212-7
```

\_18

```
Learning task-driving affinity matrix for accurate multi-view clustering through tensor subspace learning
```

```
论文：https://doi.org/10.1016/j.ins.2021.02.054
```

# Incomplete Multi-view clustering

```
Doubly aligned incomplete multi-view clustering
```

```
论文：http://arxiv.org/abs/1903.02785
```

### Imputation-based IMVC

```
Incomplete multiview spectral clustering with adaptive graph learning
```

```
论文：https://doi.org/10.1109/TCYB.2018.2884715
```

```
Late fusion incomplete multi-view clustering
```

```
论文：https://doi.org/10.1109/TPAMI.2018.2879108
```

```
Consensus graph learning for incomplete multi-view clustering
```

```
论文：https://doi.org/10.1007/978-3-030-16148-4
```

\_41

```
Multi-view kernel completion
```

```
论文：http://arxiv.org/abs/1602.02518
```

```
Unified embedding alignment with missing views inferring for incomplete multi-view clustering
```

```
论文：https://doi.org/10.1609/aaai.v33i01.33015393
```

```
One-Stage Incomplete Multi-view Clustering via Late Fusion
```

```
论文：https://doi.org/10.1145/3474085.3475204
```

```
Spectral perturbation meets incomplete multi-view data
```

```
论文：https://doi.org/10.24963/ijcai.2019/510
```

```
Efficient and effective regularized incomplete multi-view clustering
```

```
论文：https://doi.org/10.1109/TPAMI.2020.2974828
```

```
Adaptive partial graph learning and fusion for incomplete multi‐view clustering
```

```
论文：https://doi.org/10.1002/int.22655
```

```
Unified tensor framework for incomplete multi-view clustering and missing-view inferring
```

```
论文：https://ojs.aaai.org/index.php/AAAI/article/view/17231
```

```
Incomplete multi-view clustering with cosine similarity
```

```
论文：https://doi.org/10.1016/j.patcog.2021.108371
```

### Transformation-based IMVC

```
Partial multi-view clustering via consistent GAN
```

```
论文：https://doi.org/10.1109/ICDM.2018.00174
```

```
One-step multi-view subspace clustering with incomplete views
```

```
论文：https://doi.org/10.1016/j.neucom.2021.01.080
```

```
Consensus guided incomplete multi-view spectral clustering
```

```
论文：https://doi.org/10.1016/j.neunet.2020.10.014
```

```
Incomplete multi-view subspace clustering with adaptive instance-sample mapping and deep feature fusion
```

```
论文：https://doi.org/10.1007/s10489-020-02138-9
```

```
Dual Alignment Self-Supervised Incomplete Multi-View Subspace Clustering Network
```

```
论文：https://doi.org/10.1109/LSP.2021.3120311
```

```
Structural Deep Incomplete Multi-view Clustering Network.
```

```
论文：https://doi.org/10.1145/3459637.3482192
```

### The unified IMVC

```
Complete/incomplete multi‐view subspace clustering via soft block‐diagonal‐induced regulariser
```

```
论文：https://doi.org/10.1049/cvi2.12077
```

```
A novel consensus learning approach to incomplete multi-view clustering
```

```
论文：https://doi.org/10.1016/j.patcog.2021.107890
```

```
Adaptive graph completion based incomplete multi-view clustering
```

```
论文：https://doi.org/10.1109/TMM.2020.3013408
```

```
Incomplete multi-view clustering via contrastive prediction
```

```
论文：https://openaccess.thecvf.com/content/CVPR2021/html/Lin
```

\_COMPLETER\_Incomplete\_Multi-View\_Clustering\_via\_Contrastive\_Prediction\_CVPR\_2021\_paper.html

### Uncertain multi-view clustering

```
Outlier-robust multi-view clustering for uncertain data
```

```
论文：https://doi.org/10.1016/j.knosys.2020.106567
```

```
Multi-view spectral clustering for uncertain objects
```

```
论文：https://doi.org/10.1016/j.ins.2020.08.080
```

### Incremental multi-view clustering

```
(Miao, Zhang, Hu, & W ang, 2020)
```

```
Incremental multi-view spectral clustering
```

```
论文：https://doi.org/10.1016/j.knosys.2019.02.036
```

```
Incremental multi-view spectral clustering with sparse and connected graph learning
```

```
论文：https://doi.org/10.1016/j.neunet.2021.08.031
```

```
Multi-graph fusion for multi-view spectral clustering
```

```
论文：http://arxiv.org/abs/1909.06940
```

```
Incremental learning through deep adaptation
```

```
论文：https://doi.org/10.1109/TPAMI.2018.2884462
```
 -->
