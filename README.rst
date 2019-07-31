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

`Outlier Ensembles: An Introduction <https://www.springer.com/gp/book/9783319547640>`_
by Charu Aggarwal and Saket Sathe [#Aggarwal2017Outlier]_: Great intro book for ensemble learning in outlier analysis.

`Ensemble Machine Learning: Methods and Applications <https://link.springer.com/book/10.1007%2F978-1-4419-9326-7>`_
edited by Oleg Okun [#Zhang2012Ensemble]_: Responding to a shortage of literature dedicated to the topic, this volume offers comprehensive coverage of state-of-the-art ensemble learning techniques,
including various contributions from researchers in leading industrial research labs.

`Applications of Supervised and Unsupervised Ensemble Methods <https://www.springer.com/gp/book/9783642039980>`_
edited by Oleg Okun [#Okun2009Applications]_: This book contains the extended papers presented at the 2nd Workshop on Supervised and Unsupervised Ensemble Methods and their Applications (SUEMA) held on 21-22 July, 2008 in Patras, Greece,
in conjunction with the 18th European Conference on Artificial Intelligence (ECAI’2008).


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


**Coursera Machine Learning by University of Washington Ng also partly covers the topic**\ :


* `Ensemble classifiers <https://www.coursera.org/lecture/ml-classification/ensemble-classifiers-IAous>`_
* `Ensembles, Bagging, Boosting <https://www.coursera.org/lecture/predictive-analytics/ensembles-bagging-boosting-ph2UL>`_


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

To complete.

----


4. Papers
---------

4.1. Overview & Survey Papers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Ensemble methods in machine learning                                                               MCS                           2000   [Dietterich2000Ensemble]_     `[PDF] <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.34.4718&rep=rep1&type=pdf>`_
Popular ensemble methods: An empirical study                                                       JAIR                          1999   [Opitz1999Popular]_           `[PDF] <https://www.jair.org/index.php/jair/article/download/10239/24370/>`_
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================

4.2. Key Algorithms
^^^^^^^^^^^^^^^^^^^

====================  =================================================================================================  =================================  =====  ===========================  ==============================================================================================================================================================================================
Abbreviation          Paper Title                                                                                        Venue                              Year   Ref                          Materials
====================  =================================================================================================  =================================  =====  ===========================  ==============================================================================================================================================================================================
IForest               Isolation forest                                                                                   ICDM                               2008   [#Liu2008Isolation]_         `[PDF] <https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf>`_
AutoEncoder Ensemble  Outlier detection with autoencoder ensembles                                                       SDM                                2017   [#Chen2017Outlier]_          `[PDF] <http://saketsathe.net/downloads/autoencode.pdf>`_
====================  =================================================================================================  =================================  =====  ===========================  ==============================================================================================================================================================================================


4.3. Outlier Ensembles
^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                           Materials
=================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Outlier ensembles: position paper                                                                  SIGKDD Explorations           2013   [#Aggarwal2013Outlier]_       `[PDF] <https://pdfs.semanticscholar.org/841e/ce7c3812bbf799c99c84c064bbcf77916ba9.pdf>`_
Ensembles for unsupervised outlier detection: challenges and research questions a position paper   SIGKDD Explorations           2014   [#Zimek2014Ensembles]_        `[PDF] <http://www.kdd.org/exploration_files/V15-01-02-Zimek.pdf>`_
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


.. [#Aggarwal2017Outlier] Aggarwal, C.C. and Sathe, S., 2017. Outlier ensembles: An introduction. Springer.

.. [#Bell2007Lessons] Bell, R.M. and Koren, Y., 2007. Lessons from the Netflix prize challenge. *SIGKDD Explorations*, 9(2), pp.75-79.

.. [#Dietterich2000Ensemble] Dietterich, T.G., 2000, June. Ensemble methods in machine learning. In *International workshop on multiple classifier systems* (pp. 1-15). Springer, Berlin, Heidelberg.

.. [#Gao2010On] Gao, J., Fan, W. and Han, J., 2010. On the power of ensemble: Supervised and unsupervised methods reconciled. In *Tutorial on SIAM Data Mining Conference (SDM)*, Columbus, OH.

.. [#Okun2009Applications] Okun, O. ed., 2009. Applications of supervised and unsupervised ensemble methods (Vol. 245). Springer.

.. [#Opitz1999Popular] Opitz, D. and Maclin, R., 1999. Popular ensemble methods: An empirical study. *Journal of artificial intelligence research*, 11, pp.169-198.

.. [#Zhang2012Ensemble] Zhang, C. and Ma, Y. eds., 2012. Ensemble machine learning: methods and applications. Springer Science & Business Media.

.. [#Zhou2012Ensemble] Zhou, Z.H., 2012. Ensemble methods: foundations and algorithms. Chapman and Hall/CRC.