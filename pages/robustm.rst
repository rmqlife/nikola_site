.. title: Robust Cloth Manipulation Using Random Forest-Based Controller Parametrization
.. slug: robustm
.. date: 2017-09-15 10:00:00 UTC-03:00
.. tags: Robotics, Computer Vision, Machine Learning
.. author: Biao Jia
.. link:
.. description: 
.. category: 


Authors
=======
    * `Biao Jia <http://cs.unc.edu/~dm>`_, University of North Carolina at Chapel Hill
    * Zherong Pan, University of North Carolina at Chapel Hill
    * Zhe Hu, City University of Hong Kong
    * `Jia Pan <http://www.cityu.edu.hk/mbe/jiapan/>`_,  City University of Hong Kong
    * `Dinesh Manocha <http://cs.unc.edu/~dm>`_, University of North Carolina at Chapel Hill
    

Abstract
========

	* We present a novel approach for robust manipulation of high-DOF deformable objects such as cloth. Our approach uses  a random forest-based controller that maps the observed visual features to an optimal control action. We present a method to automatically determine the topological structure of the random forest, based on a classification generated using training data. This enables us to integrate the overall process of training data classification and controller optimization into an imitation learning (IL) framework. This framework enables learning of robust control policy for cloth manipulation with guarantees on convergence. We have evaluated our approach on different multi-task cloth manipulation benchmarks. 

	* In practice, our approach works well with different deformable features learned based on the specific task or deep learning. Moreover, our controller outperforms a simple or piecewise linear controller in terms of robustness to noise. In addition, our approach is easy to implement and does not require much parameter tuning.






