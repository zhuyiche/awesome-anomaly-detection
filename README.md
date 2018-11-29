# Awesome Anomaly Detection[![Awesome]
A list of Papers on anomaly detection.



## Machine Learning Method
- [Isolation Forest](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf) - ICDM 2008.
- [Extended Isolation Forest](http://matias-ck.com/files/papers/Extended_Isolation_Forest.pdf) 
> This paper is really hard to follow yet some idea are good.
- [LOF: Identifying Density-Based Local Outliers](http://www.dbs.ifi.lmu.de/Publikationen/Papers/LOF.pdf) -SIGMOD 2000.
> A locally density based method.


## Deep Learning Method
### Likelihood Generative Methods
- [Variational Autoencoder based Anomaly Detection using Reconstruction Probability](http://dm.snu.ac.kr/static/docs/TR/SNUDM-TR-2015-03.pdf)  
> Most Auto-encoder methods use either reconstruction error or negative log-likelihood, this is novel. This has been used by Unsupervised Anomaly Detection via Variational Auto-Encoder for Seasonal KPIs in Web Applications in Application section.
- [Learning sparse representation with variational auto-encoder for anomaly detection](https://ieeexplore.ieee.org/document/8386760/)

- [Anomaly Detection with Robust Deep Autoencoders](http://dl.acm.org/authorize?N33358) - KDD 2017.

- [Deep Anomaly Detection with Outlier Exposure](https://github.com/hendrycks/outlier-exposure) 
> Rejected by ICLR2019. But i personally think this is a good paper.

### GAN based
- [Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery](https://arxiv.org/pdf/1703.05921.pdf) -IPMI 2017.
- [Efficient-GAN-Based Anomaly Detection](https://github.com/houssamzenati/Efficient-GAN-Anomaly-Detection) ICLR Workshop 2018.

### RNN

- [Long short term memory networks for anmomaly detection in time series](https://www.elen.ucl.ac.be/Proceedings/esann/esannpdf/es2015-56.pdf)

- [LSTM-based Encoder-Decoder for Multi-sensor Anomaly Detection](https://arxiv.org/pdf/1607.00148.pdf) - ICML 2016 Workshop. 
> Multivariate Guassian distribution based.

- [A Multimodel Anomaly Detector for Robot-Assisted Feeding Using an LSTM-based Variational Autoencoder](https://arxiv.org/pdf/1711.00614.pdf) - IEEE Robotics and Automation Letters 2018. 

### Hypersphereical Learning

- [Anomaly Detection in Dynamic Networks using Multi-view Time-Series Hypersphere Learning](https://dl.acm.org/citation.cfm?id=3132964) -CIKM 2017.

- [Deep into Hypersphere: Robust and Unsupervised Anomaly Discovery in Dynamic Networks](https://www.ijcai.org/proceedings/2018/0378.pdf) IJCAI 2018. 
> Inherit the idea of Anomaly Detection in Dynamic Networks using Multi-view Time-Series Hypersphere Learning, using an extra layer to separate anomaly instances among normal instance.

- [Deep One-Class Classification](http://proceedings.mlr.press/v80/ruff18a/ruff18a.pdf) - ICML 2018 Oral.
> A well written paper, sold a excellent story, but this paper **didn't** cited Anomaly Detection in Dynamic Networks using Multi-view Time-Series Hypersphere Learning, which inherited the same idea but published earlier than Deep One-Class Classification. I doubt the level of nnovelty in this paper though it was presented as oral paper in ICML 2018. Additionally, i have read carefully to the codes that were made public by author, **the implementation on the loss function of SVDD are different from what they claimed in paper**.

## One-Class Classification

- [One-Class SVMs for Document Classification](http://www.jmlr.org/papers/volume2/manevitz01a/manevitz01a.pdf) - JMLR 2001. 
- [Support Vector Data Description](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.100.1425&rep=rep1&type=pdf) 

- [High-dimensional and large-scale anomaly detection using a linear one-class SVM with deep learning](https://www.sciencedirect.com/science/article/abs/pii/S0031320316300267) - Pattern Recognition 2018.

## Hybrid

- [DEEP AUTOENCODING GAUSSIAN MIXTURE MODEL FOR UNSUPERVISED ANOMALY DETECTION](https://www.cs.ucsb.edu/~bzong/doc/iclr18-dagmm.pdf) - ICLR 2018.
> Incorporate mixture gaussian by energy function.

## PCA

- [robust deep and inductive anomaly detection](https://arxiv.org/abs/1704.06743) - ECML PKDD 2017

## Correlation

- [Detecting Multiple Periods and Periodic Paerns in Event Time Sequences](http://chaozhang.org/papers/cikm17a.pdf) - CIKM 2017.

## Ranking

- [ranking causal anomalies via temporal and dynamical analysis on vanishing correlations](https://www.kdd.org/kdd2016/papers/files/rfp0445-chengAemb.pdf) - KDD 2016.

## Survey

- [Anomaly Detection : A Survey](http://cucis.ece.northwestern.edu/projects/DMS/publications/AnomalyDetection.pdf)

- [A Survey of Recent Trends in One Class Classification](https://link.springer.com/chapter/10.1007/978-3-642-17080-5_21) 
> I read this survey only because this is the sole survey in One Class Classification.

## FeedBack
- [Incorporating Feedback into Tree-based Anomaly Detection](https://github.com/ai/size-limit) - KDD 2017 Workshop on Interactive Data Exploration and Analytics. 
Modifications are made on the basis of Isolation Forest.
- [Feedback-Guided Anomaly Discovery via Online Optimization](http://web.engr.oregonstate.edu/~afern/papers/kdd18-siddiqui.pdf) - KDD 2018.
> An improved version of "Incorporating Feedback into Tree-based Anomaly Detection"


## Anomaly Detection Application

### KPI
- [Unsupervised Anomaly Detection via Variational Auto-Encoder for Seasonal KPIs in Web Applications](https://arxiv.org/pdf/1802.03903) - WWW 2018.
### Log

- [DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning](https://acmccs.github.io/papers/p1285-duA.pdf) - CCS 2017. 
> This is the first paper apply deep learning method to detect anomaly in log data. However, there are some obvious flaws in the experiment(i.e. The number of log templates are small, yet the top 10 predicted templates are used as true predications. Additionally, the author refuesed to share more details about there model.)

- [Mining Invariants from Logs for System Problem Detection](https://www.usenix.org/legacy/event/atc10/tech/slides/lou.pdf) -USENIX 2010












