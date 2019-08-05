Awesome Ensemble Learning
=========================

.. image:: https://img.shields.io/github/stars/yzhao062/awesome-ensemble-learning.svg
   :target: https://github.com/yzhao062/awesome-ensemble-learning/stargazers
   :alt: GitHub stars


.. image:: https://img.shields.io/github/forks/yzhao062/awesome-ensemble-learning.svg?color=blue
   :target: https://github.com/yzhao062/awesome-ensemble-learning/network
   :alt: GitHub forks


.. image:: https://img.shields.io/github/license/yzhao062/awesome-ensemble-learning.svg?color=blue
   :target: https://github.com/yzhao062/awesome-ensemble-learning/blob/master/LICENSE
   :alt: License


.. image:: https://awesome.re/badge-flat2.svg
   :target: https://awesome.re/badge-flat2.svg
   :alt: Awesome


----


`Ensemble Learning <https://en.wikipedia.org/wiki/Ensemble_learning>`_
(also known as *Ensembling*) is an exciting yet challenging field.
Ensembling leverages multiple base models to achieve better predictive
performance, which is often better than any of the constituent models alone [#Opitz1999Popular]_.
It has been proven critical in many practical applications and data science
competitions [#Bell2007Lessons]_, e.g., Kggle.

This repository collects:


#. Books & Academic Papers
#. Online Courses and Videos
#. Open-source and Commercial Libraries/Toolboxes and Datasets
#. Key Conferences & Journals


**More items will be added to the repository**.
Please feel free to suggest other key resources by opening an issue report,
submitting a pull request, or dropping me an email @ (zhaoy@cmu.edu).
Enjoy reading!

----

Table of Contents
-----------------


* `1. Books & Tutorials <#1-books--tutorials>`_

  * `1.1. Books <#11-books>`_
  * `1.2. Tutorials <#12-tutorials>`_

* `2. Courses/Seminars/Videos <#2-coursesseminarsvideos>`_
* `3. Toolboxes & Datasets <#3-toolboxes--datasets>`_

  * `3.1. Toolboxes <#31-toolboxes>`_
  * `3.2. Datasets <#32-datasets>`_

* `4. Papers <#4-papers>`_

  * `4.1. Overview & Survey Papers <#41-overview--survey-papers>`_
  * `4.2. Key Algorithms <#42-key-algorithms>`_
  * `4.3. Boosting <#43-boosting>`_
  * `4.4. Clustering Ensemble <#44-clustering-ensemble>`_
  * `4.5. Outlier Ensemble <#45-outlier-ensemble>`_

* `5. Key Conferences/Workshops/Journals <#5-key-conferencesworkshopsjournals>`_

  * `5.1. Conferences & Workshops <#51-conferences--workshops>`_
  * `5.2. Journals <#52-journals>`_


----

1. Books & Tutorials
--------------------

1.1. Books
^^^^^^^^^^

`Ensemble Methods: Foundations and Algorithms <https://www.crcpress.com/Ensemble-Methods-Foundations-and-Algorithms/Zhou/p/book/9781439830031>`_
by Zhi-Hua Zhou [#Zhou2012Ensemble]_: Classical text book covering most of the ensemble learning techniques.
A **must-read** for people in the field. `[Full Book] <http://www2.islab.ntua.gr/attachments/article/86/Ensemble%20methods%20-%20Zhou.pdf>`_

`Ensemble Machine Learning: Methods and Applications <https://link.springer.com/book/10.1007%2F978-1-4419-9326-7>`_
edited by Oleg Okun [#Zhang2012Ensemble]_: Responding to a shortage of literature dedicated to the topic, this volume offers comprehensive coverage of state-of-the-art ensemble learning techniques,
including various contributions from researchers in leading industrial research labs.

`Applications of Supervised and Unsupervised Ensemble Methods <https://www.springer.com/gp/book/9783642039980>`_
edited by Oleg Okun [#Okun2009Applications]_: This book contains the extended papers presented at the 2nd Workshop on Supervised and Unsupervised Ensemble Methods and their Applications (SUEMA),
in conjunction with ECAI’2008.

`Data Mining and Knowledge Discovery Handbook <https://link.springer.com/chapter/10.1007/0-387-25465-X_45>`_ Chapter 45 (Ensemble Methods for Classifiers):
by Lior Rokach [#Rokach2005Ensemble]_:  This chapter provides an overview of ensemble methods in classification tasks. We present all important types of ensemble method including boosting and bagging.
Combining methods and modeling issues such as ensemble diversity and ensemble size are discussed.

`Outlier Ensembles: An Introduction <https://www.springer.com/gp/book/9783319547640>`_
by Charu Aggarwal and Saket Sathe [#Aggarwal2017Outlier]_: Great intro book for ensemble learning in outlier analysis.


1.2. Tutorials
^^^^^^^^^^^^^^

=============================================================================== ============================================  =====  ============================  ==========================================================================================================================================================================
Tutorial Title                                                                  Venue                                         Year   Ref                           Materials
=============================================================================== ============================================  =====  ============================  ==========================================================================================================================================================================
On the Power of Ensemble: Supervised and Unsupervised Methods Reconciled        SDM                                           2010   [#Gao2010On]_                 `[HTML] <https://cse.buffalo.edu/~jing/sdm10ensemble.htm>`_
=============================================================================== ============================================  =====  ============================  ==========================================================================================================================================================================

----

2. Courses/Seminars/Videos
--------------------------


**Coursera - How to Win a Data Science Competition: Learn from Top Kagglers**\ :

* `Ensembling (92 mins) <https://www.coursera.org/lecture/competitive-data-science/introduction-into-ensemble-methods-MJKCi>`_


**Coursera - Machine Learning: Classification by University of Washington partly covers the topic**\ :

* `Ensemble classifiers <https://www.coursera.org/lecture/ml-classification/ensemble-classifiers-IAous>`_
* `Ensembles, Bagging, Boosting <https://www.coursera.org/lecture/predictive-analytics/ensembles-bagging-boosting-ph2UL>`_


**Machine Learning and Data Mining** by `Prof. Alexander Ihler <https://www.ics.uci.edu/~ihler/>`_:
`Section on ensembling (4 videos) <https://www.youtube.com/watch?v=Yvn3--rIdZg&list=PLaXDtXvwY-oDvedS3f4HW0b4KxqpJ_imw&index=27>`_.

----


3. Toolboxes & Datasets
---------------------

3.1. Toolboxes
^^^^^^^^^^^^^^

[**Python**] `combo <https://github.com/yzhao062/combo>`_\ : combo is a comprehensive Python toolbox for combining machine learning (ML) models and scores for various tasks, including classification, clustering, and anomaly detection. It supports the combination of ML models from core libraries such as scikit-learn and xgboost.

[**Python**] `pycobra <https://github.com/bhargavvader/pycobra>`_\ :  python library implementing ensemble methods for regression, classification and visualisation tools including Voronoi tesselations.

[**Python**] `DESlib <https://github.com/scikit-learn-contrib/DESlib>`_\ :  A Python library for dynamic classifier and ensemble selection.


3.2. Datasets
^^^^^^^^^^^^^

As a subfield of machine learning, ensemble learning is usually tested against
general machine learning benchmark datasets. Some helpful links can be found below:

* `List of datasets for machine-learning research - Wikipedia <https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research>`_
* `UCI Machine Learning Repository <http://archive.ics.uci.edu/ml/index.php>`_
* `PMLB: a large benchmark suite for machine learning evaluation and comparison <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5725843/>`_ [#Olson2017PMLB]_: `Dataset Repository <https://github.com/EpistasisLab/penn-ml-benchmarks>`_


----


4. Papers
---------

4.1. Overview & Survey Papers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Ensemble methods in machine learning                                                               MCS                           2000   [#Dietterich2000Ensemble]_     `[PDF] <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.34.4718&rep=rep1&type=pdf>`_
Popular ensemble methods: An empirical study                                                       JAIR                          1999   [#Opitz1999Popular]_           `[PDF] <https://www.d.umn.edu/~rmaclin/publications/opitz-jair99.pdf>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.2. Key Algorithms
^^^^^^^^^^^^^^^^^^^

====================  =================================================================================================  =================================  =====  ===========================  ==============================================================================================================================================================================================
Abbreviation          Paper Title                                                                                        Venue                              Year   Ref                          Materials
====================  =================================================================================================  =================================  =====  ===========================  ==============================================================================================================================================================================================
Bagging               Bagging predictors                                                                                 Machine Learning                   1996   [#Breiman1996Bagging]_       `[PDF] <https://link.springer.com/content/pdf/10.1007/BF00058655.pdf>`_
Boosting              A decision-theoretic generalization of on-line learning and an application to boosting             JCSS                               1997   [#Freund1997A]_              `[PDF] <https://pdfs.semanticscholar.org/5fb5/f7b545a5320f2a50b30af599a9d9a92a8216.pdf>`_
N/A                   Bagging, Boosting, and C4.5                                                                        AAAI/IAAI                          1996   [#Quinlan1996Bagging]_       `[PDF] <http://www.cs.ecu.edu/~dingq/CSCI6905/readings/BaggingBoosting.pdf>`_
Stacking              Stacked generalization                                                                             Neural Networks                    1992   [#Wolpert1992Stacked]_       `[PDF] <https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.133.8090&rep=rep1&type=pdf>`_
Stacking              Stacked regressions                                                                                Machine Learning                   1996   [#Breiman1996Stacked]_       `[PDF] <https://link.springer.com/content/pdf/10.1007/BF00117832.pdf>`_
====================  =================================================================================================  =================================  =====  ===========================  ==============================================================================================================================================================================================


4.3. Boosting
^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ==============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                             Materials
=================================================================================================  ============================  =====  ==============================  ==========================================================================================================================================================================
Xgboost: A scalable tree boosting system                                                           KDD                           2016   [#Chen2016Xgboost]_             `[PDF] <https://dl.acm.org/ft_gateway.cfm?ftid=1775849&id=2939785>`_
Lightgbm: A highly efficient gradient boosting decision tree                                       NIPS                          2017   [#Ke2017Lightgbm]_              `[PDF] <https://papers.nips.cc/paper/6907-lightgbm-a-highly-efficient-gradient-boosting-decision-tree.pdf>`_
CatBoost: unbiased boosting with categorical features                                              NIPS                          2018   [#Prokhorenkova2018CatBoost]_   `[PDF] <https://papers.nips.cc/paper/7898-catboost-unbiased-boosting-with-categorical-features.pdf>`_
=================================================================================================  ============================  =====  ==============================  ==========================================================================================================================================================================


4.4. Clustering Ensemble
^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Cluster Ensembles – A Knowledge Reuse Framework for Combining Multiple Partitions                  JMLR                          2002   [#Strehl2002Cluster]_         `[PDF] <http://strehl.com/download/strehl-jmlr02.pdf>`_
Clusterer Ensemble                                                                                 KBS                           2006   [#Zhou2006Clusterer]_         `[PDF] <https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/kbs06.pdf>`_
A survey of clustering ensemble algorithms                                                         IJPRAI                        2011   [#VegaPons2011A]_             `[PDF] <https://pdfs.semanticscholar.org/0d1b/7d01fb2634b6160a96bbdd73f918ed3859cb.pdf>`_
Clustering ensemble method                                                                         Cybernetics                   2019   [#Alqurashi2019Clustering]_   `[PDF] <https://www.researchgate.net/publication/322520921_Clustering_ensemble_method>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


4.5. Outlier Ensemble
^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Outlier ensembles: position paper                                                                  SIGKDD Explorations           2013   [#Aggarwal2013Outlier]_       `[PDF] <https://pdfs.semanticscholar.org/841e/ce7c3812bbf799c99c84c064bbcf77916ba9.pdf>`_
Ensembles for unsupervised outlier detection: challenges and research questions a position paper   SIGKDD Explorations           2014   [#Zimek2014Ensembles]_        `[PDF] <http://www.kdd.org/exploration_files/V15-01-02-Zimek.pdf>`_
Isolation forest                                                                                   ICDM                          2008   [#Liu2008Isolation]_          `[PDF] <https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf>`_
Outlier detection with autoencoder ensembles                                                       SDM                           2017   [#Chen2017Outlier]_           `[PDF] <http://saketsathe.net/downloads/autoencode.pdf>`_
An Unsupervised Boosting Strategy for Outlier Detection Ensembles                                  PAKDD                         2018   [#Campos2018An]_              `[HTML] <https://link.springer.com/chapter/10.1007/978-3-319-93034-3_45>`_
LSCP: Locally selective combination in parallel outlier ensembles                                  SDM                           2019   [#Zhao2019LSCP]_              `[PDF] <https://epubs.siam.org/doi/pdf/10.1137/1.9781611975673.66>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


----

5. Key Conferences/Workshops/Journals
-------------------------------------

5.1. Conferences & Workshops
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Key data mining conference **deadlines**, **historical acceptance rates**, and more
can be found `data-mining-conferences <https://github.com/yzhao062/data-mining-conferences>`_.


`ACM International Conference on Knowledge Discovery and Data Mining (SIGKDD) <http://www.kdd.org/conferences>`_

`ACM International Conference on Management of Data (SIGMOD) <https://sigmod.org/>`_

`The Web Conference (WWW) <https://www2018.thewebconf.org/>`_

`IEEE International Conference on Data Mining (ICDM) <http://icdm2018.org/>`_

`SIAM International Conference on Data Mining (SDM) <https://www.siam.org/Conferences/CM/Main/sdm19>`_

`IEEE International Conference on Data Engineering (ICDE) <https://icde2018.org/>`_

`ACM InternationalConference on Information and Knowledge Management (CIKM) <http://www.cikmconference.org/>`_

`ACM International Conference on Web Search and Data Mining (WSDM) <http://www.wsdm-conference.org/2018/>`_

`The European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD) <http://www.ecmlpkdd2018.org/>`_

`The Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD) <http://pakdd2019.medmeeting.org>`_

5.2. Journals
^^^^^^^^^^^^^

`ACM Transactions on Knowledge Discovery from Data (TKDD) <https://tkdd.acm.org/>`_

`IEEE Transactions on Knowledge and Data Engineering (TKDE) <https://www.computer.org/web/tkde>`_

`ACM SIGKDD Explorations Newsletter <http://www.kdd.org/explorations>`_

`Data Mining and Knowledge Discovery <https://link.springer.com/journal/10618>`_

`Knowledge and Information Systems (KAIS) <https://link.springer.com/journal/10115>`_


----


References
----------


.. [#Aggarwal2013Outlier] Aggarwal, C.C., 2013. Outlier ensembles: position paper. *ACM SIGKDD Explorations Newsletter*\ , 14(2), pp.49-58.

.. [#Aggarwal2017Outlier] Aggarwal, C.C. and Sathe, S., 2017. Outlier ensembles: An introduction. Springer.

.. [#Alqurashi2019Clustering] Alqurashi, T. and Wang, W., 2019. Clustering ensemble method. *International Journal of Machine Learning and Cybernetics*, 10(6), pp.1227-1246.

.. [#Bell2007Lessons] Bell, R.M. and Koren, Y., 2007. Lessons from the Netflix prize challenge. *SIGKDD Explorations*, 9(2), pp.75-79.

.. [#Breiman1996Bagging] Breiman, L., 1996. Bagging predictors. *Machine learning*, 24(2), pp.123-140.

.. [#Breiman1996Stacked] Breiman, L., 1996. Stacked regressions. *Machine learning*, 24(1), pp.49-64.

.. [#Campos2018An] Campos, G.O., Zimek, A. and Meira, W., 2018, June. An Unsupervised Boosting Strategy for Outlier Detection Ensembles. In *Pacific-Asia Conference on Knowledge Discovery and Data Mining (pp. 564-576)*. Springer, Cham.

.. [#Chen2016Xgboost] Chen, T. and Guestrin, C., 2016, August. Xgboost: A scalable tree boosting system. In *Proceedings of the 22nd acm sigkdd international conference on knowledge discovery and data mining* (pp. 785-794). ACM.

.. [#Chen2017Outlier] Chen, J., Sathe, S., Aggarwal, C. and Turaga, D., 2017, June. Outlier detection with autoencoder ensembles. *SIAM International Conference on Data Mining*, pp. 90-98. Society for Industrial and Applied Mathematics.

.. [#Dietterich2000Ensemble] Dietterich, T.G., 2000, June. Ensemble methods in machine learning. In *International workshop on multiple classifier systems* (pp. 1-15). Springer, Berlin, Heidelberg.

.. [#Freund1997A] Freund, Y. and Schapire, R.E., 1997. A decision-theoretic generalization of on-line learning and an application to boosting. *Journal of computer and system sciences*, 55(1), pp.119-139.

.. [#Gao2010On] Gao, J., Fan, W. and Han, J., 2010. On the power of ensemble: Supervised and unsupervised methods reconciled. In *Tutorial on SIAM Data Mining Conference (SDM)*, Columbus, OH.

.. [#Ke2017Lightgbm] Ke, G., Meng, Q., Finley, T., Wang, T., Chen, W., Ma, W., Ye, Q. and Liu, T.Y., 2017. Lightgbm: A highly efficient gradient boosting decision tree. In *Advances in Neural Information Processing Systems* (pp. 3146-3154).

.. [#Liu2008Isolation] Liu, F.T., Ting, K.M. and Zhou, Z.H., 2008, December. Isolation forest. In *International Conference on Data Mining*\ , pp. 413-422. IEEE.

.. [#Okun2009Applications] Okun, O. ed., 2009. Applications of supervised and unsupervised ensemble methods (Vol. 245). Springer.

.. [#Olson2017PMLB] Olson, R.S., La Cava, W., Orzechowski, P., Urbanowicz, R.J. and Moore, J.H., 2017. PMLB: a large benchmark suite for machine learning evaluation and comparison. BioData mining, 10(1), p.36.

.. [#Opitz1999Popular] Opitz, D. and Maclin, R., 1999. Popular ensemble methods: An empirical study. *Journal of artificial intelligence research*, 11, pp.169-198.

.. [#Quinlan1996Bagging] Quinlan, J.R., 1996, August. Bagging, boosting, and C4.5. In *AAAI/IAAI*, Vol. 1 (pp. 725-730).

.. [#Prokhorenkova2018CatBoost] Prokhorenkova, L., Gusev, G., Vorobev, A., Dorogush, A.V. and Gulin, A., 2018. CatBoost: unbiased boosting with categorical features. In *Advances in Neural Information Processing Systems* (pp. 6638-6648).

.. [#Rokach2005Ensemble] Rokach L. (2005) Ensemble Methods for Classifiers. In: Maimon O., Rokach L. (eds) *Data Mining and Knowledge Discovery Handbook*. Springer, Boston, MA

.. [#Strehl2002Cluster] Strehl, A. and Ghosh, J., 2002. Cluster ensembles---a knowledge reuse framework for combining multiple partitions. *Journal of machine learning research*, 3(Dec), pp.583-617.

.. [#VegaPons2011A] Vega-Pons, S. and Ruiz-Shulcloper, J., 2011. A survey of clustering ensemble algorithms. *International Journal of Pattern Recognition and Artificial Intelligence*, 25(03), pp.337-372.

.. [#Wolpert1992Stacked] Wolpert, D.H., 1992. Stacked generalization. *Neural networks*, 5(2), pp.241-259.

.. [#Zhao2019LSCP] Zhao, Y., Nasrullah, Z., Hryniewicki, M.K. and Li, Z., 2019, May. LSCP: Locally selective combination in parallel outlier ensembles. In *Proceedings of the 2019 SIAM International Conference on Data Mining (SDM)*, pp. 585-593. Society for Industrial and Applied Mathematics.

.. [#Zhang2012Ensemble] Zhang, C. and Ma, Y. eds., 2012. Ensemble machine learning: methods and applications. Springer Science & Business Media.

.. [#Zhou2006Clusterer] Zhou, Z.H. and Tang, W., 2006. Clusterer ensemble. *Knowledge-Based Systems*, 19(1), pp.77-83.

.. [#Zhou2012Ensemble] Zhou, Z.H., 2012. Ensemble methods: foundations and algorithms. Chapman and Hall/CRC.

.. [#Zimek2014Ensembles] Zimek, A., Campello, R.J. and Sander, J., 2014. Ensembles for unsupervised outlier detection: challenges and research questions a position paper. *ACM Sigkdd Explorations Newsletter*\ , 15(1), pp.11-22.
