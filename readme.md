# [Delay Estimation] Frequency Sliding Generalized Cross-Correlation: A Subband Delay Estimation Method [with MATLAB Code]

Introduction to Time-Delay Estimation (TDE) refers to the process of finding the time difference of arrival (TDOA) between signals received at sensor arrays. Traditionally, TDE plays a significant role in many position-aware systems, including radar, sonar, wireless systems, sensor calibration, and seismology. In acoustic signal processing, time-domain estimation is essential for source localization and tracking [1], [2]. Applications that rely heavily on TDE include automatic camera panning [3], speaker localization [4], or speech enhancement systems.
Generalized Cross-Correlation (GCC), initially proposed by Knapp and Carter in their seminal paper in 1976, remains the most popular technique for Time-Delay Estimation (TDE) to this day. By employing GCC, the time delay between two signals is estimated such that the cross-correlation between the filtered versions of these signals is maximized. In this context, GCC can consider different weighting functions (filters) characterized by specific behaviors [7], [8], [9]. Roth's smooth coherent transformation, Eckart or Hannan-Thomson (Maximum Likelihood) are examples of such weighting schemes [6], [10]. The Generalized Cross-Correlation with Phase Transformation (GCC-PHAT) has been repeatedly proven to be a suitable alternative for TDE in real reverberation scenarios [11], [12]. However, it has also been demonstrated that its performance can only be considered optimal under uncorrelated noise conditions and high Signal-to-Noise Ratio (SNR) [13]. Current research focuses specifically on PHAT weighting, hence the terms GCC and GCC-PHAT will be used vaguely in this article. Since the first proposal of GCC, numerous methods have been developed to improve the robustness of TDE techniques, primarily through leveraging spatial diversity provided by more than two microphones [14], [15], [16], blind channel estimation [17], [18], modified GCC weighting [19] or incorporating some prior information [20]. [21] Section 20. Further improvements for handling reverberation and correlated noise fields have also been proposed [22], addressing some limitations of GCC. Moreover, other methods utilizing temporal diversity through Bayesian filtering have shown great potential [23], [24].
Compared to the aforementioned method, this paper proposes a novel subband approach TDE with two sensors, which is an improvement not directly categorized under the aforementioned processing. Specifically, the method is based on exploring the mutual power spectral phase through a sliding window approach to obtain a set of subband GCC encoding different frequency bands' contributions estimated TDOA. The obtained subband GCC matrix is shown to be rank-one in the case of no noise single-path signals for full band signals. Leveraging this fact to obtain robust GCC in adverse situations, a low-rank approximation of the subband GCC matrix is proposed, which ultimately leads to better estimation accuracy, reduced pseudo peaks level, and lower anomaly estimation probability.
The article includes illustrations.
Conclusion presents an improved GCC time domain estimation technique based on subband analysis using mutual power spectral phase. Attributes generated from the so-called frequency sliding GCC (FS-GCC) allow for the recovery of denoised correlated signals through a low-rank approximation of the FS-GCC matrix. The use of SVD and weighted SVD to obtain strong GCC and accurate time delay estimates has been validated, and compared to other well-known methods, the proposed technique can have a related impact on TDE and source localization performance.

## Images

![(Delay Estimation)Frequency Sliding Generalized Cross-Correlation: A Subband Delay Estimation Method [with MATLAB Code]](01.jpg)
![(Delay Estimation)Frequency Sliding Generalized Cross-Correlation: A Subband Delay Estimation Method [with MATLAB Code]](02.jpg)
![(Delay Estimation)Frequency Sliding Generalized Cross-Correlation: A Subband Delay Estimation Method [with MATLAB Code]](03.jpg)
![(Delay Estimation)Frequency Sliding Generalized Cross-Correlation: A Subband Delay Estimation Method [with MATLAB Code]](04.jpg)
![(Delay Estimation)Frequency Sliding Generalized Cross-Correlation: A Subband Delay Estimation Method [with MATLAB Code]](05.jpg)
![(Delay Estimation)Frequency Sliding Generalized Cross-Correlation: A Subband Delay Estimation Method [with MATLAB Code]](06.jpg)
![(Delay Estimation)Frequency Sliding Generalized Cross-Correlation: A Subband Delay Estimation Method [with MATLAB Code]](07.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
