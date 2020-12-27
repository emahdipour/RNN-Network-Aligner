# RNN-Network-Aligner

The discovery of protein-protein interaction networks alignment is of great importance in
bioinformatics due to their utilization in identifying the cellular pathways, ﬁnding new medicines, and
disease recognition. Most current issues require particular assumptions, such as the application of local
mapping, seed and extend strategy, or side information. In this study, we propose an efﬁcient alignment
issue that does not have the above limitations. In this regard, we describe the network alignment method
in the form of a classiﬁcation problem for the very ﬁrst time and introduce a deep network that ﬁnds the
alignment of nodes present in the two networks. We call this method RENA, which means network alignment
using Recurrent Neural Network or RNN. The proposed solution consists of three steps; in the ﬁrst phase,
we obtain the sequence and topological similarities from the networks’ structure. For the second phase,
the dataset needed for the transformation of the problem into a classiﬁcation problem is created from
obtained features. In the third phase, we predict the nodes’ alignment between two networks using deep
learning. The RENA architecture is implemented using Keras deep learning API in python. For examination
of the efﬁciency of our proposed method, we selected seven biological species from protein-protein
interaction (PPI) datasets of the Biogrid website. The proposed RENA method is compared with three
classiﬁcation approaches of Support Vector Machine, K-Nearest Neighbors, and Linear Discriminant
Analysis. The experimental results demonstrate the efﬁciency of the proposed RENA method and 100%
accuracy in PPI networks alignment prediction.

This project implemented by Elham Mahdipour, Ph.D. graduate of Artificial Intelligence at Yazd University, Yazd, Iran. She is faculty member of Khavaran Institute of Higer Education, Mahshhad, Iran.

The supervisor is Dr. Mohammad Ghasemzadeh, associate Prof. of Computer Engineering department at Yazd University.

Please feel free and contact to me: e.mahdipour@prof.khi.ac.ir/ elham.mahdipour@gmail.com

All right reserved by the authors.
