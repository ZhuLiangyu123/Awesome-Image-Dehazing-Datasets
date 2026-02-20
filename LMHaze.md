LMHaze数据集对应论文：LMHaze: Intensity-aware Image Dehazing with a Large-scale Multi-intensity Real Haze Dataset（ACM MM 2024）

LMHaze数据集下载链接：[https://github.com/wangzrk/LMHaze?tab=readme-ov-file](https://bgithub.xyz/wangzrk/LMHaze)

LMHaze数据集是由北京理工大学和澳大利亚国立大学联合发布，是第一个包含非均匀雾霾场景的去雾数据集，包含55对真实的有雾霾和对应的无雾霾户外图像。雾霾图像是在使用专业雾霾机器产生的真实雾霾条件下拍摄的，该机器能够高保真地模拟真实的雾霾条件。2020年，CVPR下NTIRE（New Trends in Image Restoration and Enhancement）研讨会举办第三届图像去雾在线挑战，NH-HAZE数据集被用于去雾挑战中。

LMHaze数据集是一个大规模、高质量的真实世界去雾数据集，包含5040对高分辨率的有雾和对应的无雾图像，涵盖多种室内外环境和不同的雾浓度。其中，训练集包含3925对图像，测试集包含1115对图像。
数据集大小超过现有最大真实世界去雾数据集的25倍，图像分辨率高达5472×3648。数据集创建过程中，通过专业的雾生成器和静态场景采集，确保了图像对齐和雾浓度的多样性。此外，数据集还提供了多类型的手工标注，包括目标检测、语义分割和图像描述，旨在评估去雾方法在下游任务中的性能，解决现有数据集在雾浓度分布和场景多样性方面的不足。


想了解更多关于​NH-HAZE数据集的详细信息，请看原始论文！（文中还描述了很多采集图像的细节，如采用什么型号的雾霾产生机器、采用什么型号的相机拍摄照片等）
