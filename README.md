# ML-on-MCU
Final project of ETH Machine Learning on Microcontrollers course.

The project is in collaboration with [@Liux1n](https://github.com/Liux1n). We together proposed several networks for human fall detection based on [KFall](https://sites.google.com/view/kfalldataset) dataset and implemented them on STM32 and MAX78000 platforms.

## Structure
The repository is structured as follows:
1. [Fall_Detection](https://github.com/Liux1n/Fall_Detection) contrains code for model training.
2. [FallDetection-STM32-CUBEAI](https://github.com/liyinrong/FallDetection-STM32-CUBEAI) contains STM32 implementation with CUBEAI runtime.
3. [FallDetection-STM32-TFLite](https://github.com/liyinrong/FallDetection-STM32-TFLite) contains STM32 implementation with TensorFlow Lite runtime.
4. [FallDetection-MAX78000](https://github.com/liyinrong/FallDetection-MAX78000) contains MAX78000 implementation.

## Reference
1. Yu, X., Jang, J., & Xiong, S. (2021). A Large-Scale Open Motion Dataset (KFall) and Benchmark Algorithms for Detecting Pre-impact Fall of the Elderly Using Wearable Inertial Sensors. Frontiers in Aging Neuroscience, 13. https://doi.org/10.3389/FNAGI.2021.692865
2. Koo, B., Yu, X., Lee, S., Yang, S., Kim, D., Xiong, S., & Kim, Y. (2023). TinyFallNet: A Lightweight Pre-Impact Fall Detection Model. Sensors 2023, Vol. 23, Page 8459, 23(20), 8459. https://doi.org/10.3390/S23208459
3. Yu, X., Qiu, H., & Xiong, S. (2020). A Novel Hybrid Deep Neural Network to Predict Pre-impact Fall for Older People Based on Wearable Inertial Sensors. Frontiers in Bioengineering and Biotechnology, 8. https://doi.org/10.3389/FBIOE.2020.00063
