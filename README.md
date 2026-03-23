# Deep learning for improving cell segmentation and classification in histology images

第一步处理数据集
下载PanNuke数据集，查看Pannuke文档，根据prepare_pannuke脚本处理数据集，并按照文档的文件结构放置数据
将configs/dataset/pannuke 中的 dataset_config.yaml, weight_config.yaml放入处理好的数据集

第二步下载预训练ViT-256模型
下载后存放至 models/pretrained/

第三步配置训练config
根据 logpaper/pannuke/cellvithv/vit256/best setting中的 根据hpc服务器上的路径进行更改


