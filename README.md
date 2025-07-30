# Cassini
Cassini Ovals for Robust Mitosis Detection in Cellular Imaging

Reza Yazdi, Hassan Khotanlou

RIV Lab., Department of Computer Engineering, Bu-Ali Sina University, Hamedan, Iran

ABSTRACT

Background and Objective: Accurate detection of mitosis is crucial in automated cell analysis, yet many existing methods depend heavily on deep learning models or complex detection techniques, which can be computationally intensive and error-prone, particularly when segmentation is incomplete. This study presents a novel unsupervised method for mitosis detection, leveraging the geometric properties of the Cassini oval to reduce computational costs and enhance robustness.

Methods: Our approach integrates a newly developed deep learning model, MaxSigNet, for initial cell segmentation. We subsequently employ the Cassini oval in its single-ring mode to detect mother cells in the initial frame and switch to double-ring mode in subsequent frames to identify daughter cells and confirm mitosis events. The success of this method hinges on the presence of equal non-zero foci values in the mother cell and distinct non-zero foci values in the daughter cells, which indicate accurate mitosis detection.

Results: The method was evaluated across six datasets from four different cell lines, achieving perfect F1, Recall, and Precision scores on four datasets, with scores of 96% and 85% on the remaining two. Comparative analysis demonstrated that our method outperformed similar approaches in F1 and Recall metrics. Additionally, the method showed substantial robustness to incomplete segmentation, with only a 20% average drop in F1 scores when tested with older segmentation methods like K-means, Felzenszwalb, and Watershed.

Conclusions: The proposed method offers a significant advancement in mitosis detection by leveraging the Cassini oval’s properties, providing a reliable and efficient solution for automated cell analysis systems. This approach promises to enhance the accuracy and efficiency of cellular behavior studies, with potential applications in various biomedical research fields.
