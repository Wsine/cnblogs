# Labview实现脉波调制( PPM )

根据定义为脉冲宽度调制
生成一个正弦信号，得到其幅值输入给一个方波信号的偏移量
由于方波信号的偏移量里面含有正弦信号的信息
因此通过对方波信号的上升沿或下降沿进行信号触发则可以恢复波形

### 实现效果

![1](/images/wsine-blog-image70.png)

![2](/images/wsine-blog-image71.png)

PPM图像输出2

![3](/images/wsine-blog-image72.png)

对比两个PPM图像，方波信号的相位发生了偏移，这部分就是正弦信号的幅值信息。
从结果图中可以看出，信号恢复准确。

### 后端实现

![4](/images/wsine-blog-image73.png)