# CausalLearner

Causal Learner: An open-source package of causal feature selection and causal (Bayesian network) structure learning (Matlab version)

Causal Learner is an easy-to-use open source toolbox for causal(Bayesian network) structure learning and causal feature selection (Markov blanket/parent and children, MB/PC) learning, which makes research efforts on causal structure learning and MB learning much easier. Causal Learner integrates a function for generating simulated Bayesian network data, a set of state-of-the-art global causal structure learning algorithms, a set of state-of-the-art local causal structure learning algorithms, a set of state-of-the-art MB learning algorithms, and abundant functions for algorithm evaluation. The data generation part of Causal Learner is written in R language, and the rest of Causal Learner is written in MATLAB.

********** Names of the 31 Bayesian networks are as follows **********

(1) Discrete Bayesian Networks

Small Networks (<20 nodes) asia, cancer, earthquake, sachs, survey

Medium Networks (20–50 nodes) alarm, barley, child, insurance, mildew, water

Large Networks (50–100 nodes) hailfinder, hepar2, win95pts

Very Large Networks (100–1000 nodes) andes, diabetes, link, pathfinder, pigs, munin1, munin2, munin3, munin4';

Massive Networks (>1000 nodes) munin

(2) Continues Bayesian Networks (Gaussian)

Medium Networks (20–50 nodes) ecoli70, magic-niab

Large Networks (50–100 nodes) magic-irri

Very Large Networks (101–1000 nodes) arth150

(3) Continues Bayesian Networks (Conditional Linear Gaussian)

Small Networks (<20 nodes) sangiovese

Medium Networks (20–50 nodes) mehra-original, mehra-complete

********** Names of the 26 algorithms are as follows **********

(1) global causal structure learning: GSBN, GES, PC, MMHC, PCstable, F2SL_c, F2SL_s

(2) local causal structure learning: PCD_by_PCD, MB_by_MB, CMB, LCS_FS

(3) Markov blanket learning: GS, IAMB, interIAMB, IAMBnPC, interIAMBnPC, FastIAMB, FBED, MMMB, HITONMB, PCMB, IPCMB, MBOR, STMB, BAMB, EEMB, MBFS

********** Names of the 13 Metrics evaluating algorithms are as follows **********

(1) global causal structure learning:

----- In accuracy: Ar_F1, Ar_precision, Ar_recall, SHD, Miss, Extra, Reverse

----- In efficiency: running time

(2) local causal structure learning:

----- In accuracy: Ar_F1, Ar_precision, Ar_recall, SHD, Miss, Extra, Reverse, Undirected

----- In efficiency: running time, number of conditional independence tests

(3) Markov blanket learning:

----- In accuracy: Adj_F1, Adj_precision, Adj_recall

----- In efficiency: running time, number of conditional independence tests


References for citation:

-Kui Yu, Xianjie Guo, Lin Liu, Jiuyong Li, Hao Wang, Zhaolong Ling, and Xindong Wu. Causality-based Feature Selection: Methods and Evaluations. ACM Computing Surveys (CSUR) 53, no. 5 (2020): 1-36.
-Kui Yu, Lin Liu, and Jiuyong Li. A unified View of Causal and Non-causal Feature Selection. ACM Transactions on Knowledge Discovery from Data, in press (2020).
