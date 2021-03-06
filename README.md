# Real-Time-Abnormal-Event-Detection-in-Crowded-Scenes
This project is based on STACOG descriptor [1] to detect anomalous crowd event in real-time.

The underlying assumption of the method presented here is that the abnormal event differs from normal ones in their space-time motion pattern. So, STACOG features that considered as spatio-temporal representation is extracted from video sequences. We then perform K-medoids clustering using training features. During the test phase, the anomaly score of each frame is determined from distances between frame-based feature STACOG and center of the clusters.

The proposed anomaly detection method was tested on benchmark dataset: UMN dataset, PETS2009. Experiments show that the proposed method achieves comparable results with the state-of-the-art methods in terms of accuracy while requiring a low computational cost than alternative approaches


References
[1]	T. Kobayashi and N. Otsu, “Motion recognition using local auto-correlation of space–time gradients,” Pattern Recognition Letters, vol. 33, no. 9, pp. 1188–1195, 2012.

Citation Details
----------------------
  
Please cite the following paper when using this source code:
A. Nady, A. Atia, A. E. Aboutabl, “Real-Time Abnormal Event Detection in CrowdedScenes”, Journal of Theoretical and Applied Information Technology.96(18):6064-6075, September2018.
https://www.researchgate.net/publication/327972246_REAL-TIME_ABNORMAL_EVENT_DETECTION_IN_CROWDED_SCENES
