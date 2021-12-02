# DevelopmentofSiliconforAI

Abstract—This paper provides a review of design approaches
towards artificial intelligence (AI) System-on-Chip. AI algorithms
have progressed over the past decades from perceptron-based
neural network (NN) and neuro-fuzzy (NF) system to today’s
deep neural network (DNN) and neuromorphic computing.
Recent DNN hardware accelerators focus on energy-efficient
integration of digital circuits to realize real-time DNN operation
while neuromorphic processors deploy new memory technologies
with analog computation for low power consumption. However,
different design approaches can be applied to such processor
implementation with their pros and cons. This paper reviews
from the early processor designs for NN and NF in both
mixed-mode and digital implementations to the recent DNN SoC
designs that we have proposed for a decade. The former content
deals with NN and NF processors used as a functional building
block of a machine vision SoC, while the latter concentrates
on integration of the whole DNN function. We also provide a
discussion on the approaches, and provide perspective on future
research directions.

Index Terms—Mixed-mode SoC, neural network processor,
neuro-fuzzy processor, deep learning SoC.

Manuscript received February 2, 2020; revised April 30, 2020; accepted
May 17, 2020. Date of publication June 1, 2020; date of current version
December 1, 2020. This work was supported in part by the National
Research Foundation of Korea (NRF) grant funded by the Korean Government
(MSIT) under Grant 2019R1C1C1009857 and in part by the Samsung
Electronics. This article was recommended by Associate Editor C. H. Chang.
(Corresponding author: Kyuho Jason Lee.)
Kyuho Jason Lee is with the School of Electrical and Computer Engineering,
Ulsan National Institute of Science and Technology, Ulsan 44919, South Korea
(e-mail: kyuho.jsn.lee@unist.ac.kr).
Jinmook Lee, Sungpill Choi, and Hoi-Jun Yoo are with the School of
Electrical Engineering, KAIST, Daejeon 34141, South Korea.
Color versions of one or more of the figures in this article are available
online at https://ieeexplore.ieee.org.
Digital Object Identifier 10.1109/TCSI.2020.2996625
