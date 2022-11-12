# CIFAR10

## 1.Introduction

人工智能安全的课程作业，用cifar10为数据集训练分类  
这个数据集是只有10个类别的  
采用`pytorch`提供的预训练好的`ResNet18` 

**单个GP运行main.py**；  
  
**多GPU运行`main1.py`获取resnet18， 运行`main-resnet34.py`获取resnet34;**  
  
    
___


## 2.Preparation

保证文件结构如下：
> AI-security-homework
>> data  
>>> cifar-10-python.tar.gz  
>>> cifar-10-batches-py  

>> main1.py  
>> main2.py  
>> main-resnet34.py
**请注意，如果`data`下面没有数据集的话，请把`trainset = torchvision.datasets.CIFAR10(root='./data/', train=True,download=False, transform=transform_train)`和`testset = torchvision.datasets.CIFAR10(root='./data/', train=False, download=False, transform=transform_test)`里面的`download`改成`True`**  
  
  ___
## 3.hyper parameter
batch_size, epoch, lr, weigth_decy, lr_period, lr_decay
## 4.Issue
欢迎交流

