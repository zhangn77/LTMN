# Divide and Conquer: A Real-Time Semi-Supervised Deep Tone Mapping Network

**Abstract**
Tone mapping operators (TMOs) can compress the range of high dynamic range (HDR) images so that they can be displayed normally on the low dynamic range (LDR) devices. Recent TMOs based on deep neural networks can produce impressive results, but there are still some shortcomings. On the one hand, their supervised learning procedure requires a high-quality paired dataset which is hard to be accessed. On the other hand, they are too slow and heavy to run at practical applications. This paper proposes a real-time deep semi-supervised learning TMO to solve the above problems. The proposed method learns in a semi-supervised way by combining the adversarial loss, cycle consistency loss, and the pixel-wise loss. The first two can simulate the image distributions in the real word from the unpaired LDR data and the latter can learn the guidance of paired LDR labels. In this way, the proposed method only requires HDR sources, unpaired high-quality LDR images, and a few well tone-mapped HDR-LDR pairs as training data. Furthermore, the proposed method divides tone mapping into luminance mapping and saturation adjustment and then conquers them in a parallel approach. By this``divide and conquer" strategy, we can reconstruct each component more precisely. Based on semi-supervised learning and divide and conquer strategy, we propose a lightweight tone mapping network that is efficient in tone mapping task (up to 5000x parameters-saving and 27x time-saving compared to the learning-based TMOs). Both quantitative and visual results demonstrate that the proposed method achieves comparable results to state-of-the-art TMOs.


## DataSet

[Training Data](https://drive.google.com/file/d/1aHdLkexzdqXTmMU2sokTUaDAZjhwqVxw/view?usp=sharing)


[Testing Data](https://drive.google.com/file/d/193T7IzEDj4iXJyAvyCsRO_dhJPdF12Pz/view?usp=sharing)

## Code
The code and pre-trained weights are going to be released as soon as possible.
