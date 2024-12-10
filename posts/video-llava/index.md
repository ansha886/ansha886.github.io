# 北大多模态Video-LLaVA模型：秒懂视频笑点的视觉语言大模型

Video-LLaVA模型的核心在于其能够提前将图片和视频的特征绑定到统一的特征空间中，这一策略极大地促进了模型对视觉信息的理解和处理能力。与传统的视觉语言模型相比，Video-LLaVA通过联合图片和视频的训练与指令微调，大幅提高了计算效率和模型性能。
&lt;!--more--&gt;

#### 技术创新

Video-LLaVA引入了LanguageBind编码器，这一机制通过预先对齐图片和视频特征来形成统一的视觉表征。这种方法的优势在于无需预先训练各自的图片和视频编码器，从而简化了模型的训练过程，同时也降低了模型对数据的依赖。

![](https://raw.githubusercontent.com/ansha886/blog-images/master/LLaVA-video.jpg)

---

> 作者:   
> URL: https://ansha886.github.io/posts/video-llava/  

