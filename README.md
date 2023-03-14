# Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification
This study aims to develop deep learning (DL) classification frameworks for one-dimensional (1D) spectral time series. In this work, we deal with the spectra classification problem from two different perspectives, one is a general two-dimensional (2D) space segmentation problem, and the other is a common 1D time series classification problem. We focused on the two proposed classification models under these two settings, the namely the end-to-end binned Fully Connected Neural Network (FCNN) with the automatically capturing weighting factors model and the convolutional SCT attention model. Under the setting of 1D time series classification, several other end-to-end structures based on FCNN, Convolutional Neural Network (CNN), ResNets, Long Short-Term Memory (LSTM), and Transformer were explored. Finally, we evaluated and compared the performance of these classification models based on the High Energy Density (HED) spectra dataset from multiple perspectives, and further performed the feature importance analysis to explore their interpretability. The results show that all the applied models can achieve 100% classification confidence, but the models applied under the 1D time series classification setting are superior. Among them, Transformer-based methods consume the least training time (0.449 s). Our proposed convolutional Spatial-Channel-Temporal (SCT) attention model uses 1.269 s, but its self-attention mechanism performed across spatial, channel, and temporal dimensions can suppress indistinguishable features better than others, and selectively focus on obvious features with high separability.


For more information see our publication 'Sun, Y., Brockhauser, S. and Hegedűs, P., 2021. Comparing End-to-End Machine Learning Methods for Spectra Classification. Applied Sciences, 11(23), p.11520.'

Open the project in Mybinder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/HEAD)

Open the project in Colab:
<a target="_blank" href="https://colab.research.google.com/github/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**CNN model:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/HEAD?labpath=SpectralFingerprint_L2Beamtime-CNN-20230307-2mpool3.ipynb)
<a target="_blank" href="https://colab.research.google.com/github/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/blob/main/SpectralFingerprint_L2Beamtime-CNN-20230307-2mpool3.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**LSTM model:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/main?labpath=SpectralClassification-FNN1D-20230312.ipynb)
<a target="_blank" href="https://colab.research.google.com/github/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/blob/main/SpectralClassification-FNN1D-20230312.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**Transformer model:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/main?labpath=SpectralClassification-TRANSFORMER-20210815-MultLen.ipynb)
<a target="_blank" href="https://colab.research.google.com/github/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/blob/main/SpectralClassification-TRANSFORMER-20210815-MultLen.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**ConvSCT Attention model:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/main?labpath=SpectralClassification-Convolutional%20SCT%20Attention-20230306.ipynb)
<a target="_blank" href="https://colab.research.google.com/github/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/blob/main/SpectralClassification-Convolutional%20SCT%20Attention-20230306.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**ConvSC Attention model:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/main?labpath=SpectralClassification-Convolutional%20SC%20Attention-20210530.ipynb)
<a target="_blank" href="https://colab.research.google.com/github/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/blob/main/SpectralClassification-Convolutional%20SC%20Attention-20210530.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**FNN_1D model:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/main?labpath=SpectralClassification-FNN1D-20230312.ipynb)
<a target="_blank" href="https://colab.research.google.com/github/sunyue-xfel/Comparing-End-to-End-Machine-Learning-Methods-for-Spectra-Classification/blob/main/SpectralClassification-FNN1D-20230312.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
