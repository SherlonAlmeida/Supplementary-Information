**Feature Extraction:**
*   **FEATURE1** = FOS
*   **FEATURE2** = GLCM
*   **FEATURE3** = NGTDM
*   **FEATURE4** = LPQ **(Feature f1 in paper)**
*   **FEATURE5** = FOS + GLCM **(Feature f2 in paper)**
*   **FEATURE6** = FOS + NGTDM
*   **FEATURE7** = FOS + LPQ
*   **FEATURE8** = GLCM + NGTDM
*   **FEATURE9** = GLCM + LPQ
*   **FEATURE10** = NGTDM + LPQ
*   **FEATURE11** = FOS + GLCM + NGTDM
*   **FEATURE12** = FOS + GLCM + LPQ
*   **FEATURE13** = FOS + NGTDM + LPQ
*   **FEATURE14** = GLCM + NGTDM + LPQ

**Data Description (Dataset HC-FMRP):**
*   190 COVID images
*   310 INTERSTITIAL-NOT-COVID images **(Not used)**
*   381 NORMAL images

**Data Description (Dataset Kaggle)**
*   250 COVID images
*   250 NORMAL images
*   250 viral_pneumonia images **(Not used)**
*   250 lung_infection images **(Not used)**

**CSV Format**

|Index|Image|Feature1|Feature2|Feature3|...|FeatureN|Category|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|0|1.jpg|list [...]|list [...]|list [...]|...|list [...]|Class|

**Data dimensionality:**
|Feature1|Feature2|Feature3|Feature4|Feature5|Feature6|Feature7|Feature8|Feature9|Feature10|Feature11|Feature12|Feature13|Feature14|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|16|28|5|255|44|21|271|33|283|260|49|299|276|288|