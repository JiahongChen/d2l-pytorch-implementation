# Mutiple GPUs with Pytorch

As PyTorch and MxNet has much difference in the Hybridization and parallelization, I did not refer to the original course/book.

Instead, this repo provide a brief guide to setting up the multi-GPU environment and sample code to utilize multiple GPUs.

* For Hybridization, as PyToch does not support symbolic computing, I will skip this part.
* For Multi-GPU setup, you can refer to [another repo](https://github.com/JiahongChen/Set-up-deep-learning-frameworks-with-GPU-on-Google-Cloud-Platform) of mine, which gives detailed setup guide on Google Cloud Platform.
* For Brief guide for running codes on multiple GPUs, you can find in this [repo](https://github.com/JiahongChen/multiGPU) of mine.
  * The main idea to make your code run on multiple GPUs is to warp your model using ```torch.nn.DataParallel```: ```model = nn.DataParallel(model)```
  * A sample code that replicates [Maximum Classifier Discrepancy for Domain Adaptation](https://github.com/mil-tokyo/MCD_DA) is provided in this folder, which is run on [VISDA](https://github.com/VisionLearningGroup/taskcv-2017-public) dataset.
