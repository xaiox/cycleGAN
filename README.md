# cycleGAN

学习了
https://github.com/aladdinpersson/Machine-Learning-Collection

###项目说明：
训练时接受三个参数分别是 数据集(在data/train/中)、数据集、训练前是否导入模型（写上load_model）

例如

`
python train.py horses zebras load_model

python train.py photo fake_photo
`
除此之外，在config.py中有更多的参数调整

训练结束后会自动将/data/val中相同名称的数据集放入模型，并将结果放入results文件夹

而saved文件夹存放训练过程中产生的图片
