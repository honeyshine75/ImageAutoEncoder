# ImageAutoEncoder

Just a image autoEncoder

说明：

    1. 训练一共采用了10w张左右图片
    2. 会有部分色彩失真
    3. 训练过程图片resize=[224,224]
    4. 采用更大分辨率训练可能会提高还原质量

注意： 

    1. 此网络无法实现无损压缩
    2. 还原后的图片尺寸为int(size/8)*8
    3. 欢迎各位提交更好的权重
    
input/output效果如下

    <img src="input_image/1.jpg" alt="input_1" width="300" /><img src="output_image/out_1.jpg" alt="input_1" width="300" />
    <img src="input_image/2.jpg" alt="input_2" width="300" /><img src="output_image/out_2.jpg" alt="input_2" width="300" />
    <img src="input_image/3.jpg" alt="input_3" width="300" /><img src="output_image/out_3.jpg" alt="input_3" width="300" />
    <img src="input_image/4.jpg" alt="input_4" width="300" /><img src="output_image/out_4.jpg" alt="input_4" width="300" />
    <img src="input_image/5.jpg" alt="input_5" width="300" /><img src="output_image/out_5.jpg" alt="input_5" width="300" />