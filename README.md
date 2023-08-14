# 利用ResNet50测试pytorch Batch Size的工具

## 1. 参考信息

修改`IMAGE_SHAPE`,`NUM_CLASSES`,`DATASET_SIZE`,运行`python getBatchSize`即可知道程序报oom时可选用的最大BatchSize是多少

[参考网站](https://towardsdatascience.com/a-batch-too-large-finding-the-batch-size-that-fits-on-gpus-aef70902a9f1)

## 2.创建对应环境[Windows]

```bash
conda create -n test_batch_size python=3.10
conda activate test_batch_size
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
conda install tqdm
```