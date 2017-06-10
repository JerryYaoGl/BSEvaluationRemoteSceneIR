# BSEvaluationRemoteSceneIR

Manuscript:
Comparative Evaluation of Background Subtraction Algorithms in Remote Scene Video Captured by MWIR Sensor<br>
Guangle Yao, Tao Lei, Jiandan Zhong, Ping Jiang, Wenwu Jia<br>

./RemoteSceneIRDataset:       Remote Scene IR Dataset<br>
　　IRVideoSequence:  Frames caputered by MWIR camera<br>
　　GroundTruth:      Pixel-wise GroundTruth of foreground<br>
./BSResults:          Detected foreground masks by BS<br>
./BSResultsM:         Detected foreground masks by BS+MedianFilter<br>
./BSResultsMM:        Detected foreground masks by BS+MedianFilter+MorphologicalOperation

16 BS algorithms are evaluated in Remote Scene IR Dataset:<br>
AdaptiveMedian[1], Bayes[2], Codebook[3,4], Gaussian[5], GMG[6], GMM1[7], GMM2[8], GMM3[9], KDE[10], KNN[9], PBAS[11], PCAWS[12], Sigma-delta[13], SOBS[14], Texture[15], ViBe[16]

The implementations and parameter settings are detailed in the manuscript.

[1] N.J.B. McFarlane et al., Segmentation and tracking of piglets in images<br>
[2] L. Li et al., Foreground object detection from videos containing complex background<br>
[3] K. Kim et al., Background modeling and subtraction by codebook construction<br>
[4] K. Kim et al., Real-time foreground–background segmentation using codebook model<br>
[5] C.R. Wren et al., Pfinder: real-time tracking of the human body<br>
[6] A.B. Godbehere et al., Visual tracking of human visitors under variable-lighting conditions for a responsive audio art installation<br>
[7] C. Stauffer et al, Adaptive background mixture models for real-time tracking<br>
[8] P. KaewTraKulPong et al., An improved adaptive background mixture model for real-time tracking with shadow detection<br>
[9] Z. Zivkovic et al., Efficient adaptive density estimation per image pixel for the task of background subtraction<br>
[10] A. Elgammal et al., Non-parametric model for background subtraction<br>
[11] M. Hofmann et al., Background segmentation with feedback: the pixel-based adaptive segmenter<br>
[12] P. St-Charles et al., Universal background subtraction using word consensus models<br>
[13] A. Manzanera et al., A new motion detection algorithm based on Sigma-Delta background estimation<br>
[14] L. Maddalena et al., A self-organizing approach to background subtraction for visual surveillance applications<br>
[15] M. Heikkila et al., A texture-based method for modeling the background and detecting moving objects<br>
[16] O. Barnich et al., ViBe: a universal background subtraction algorithm for video sequences<br>

