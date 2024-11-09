## Joint-Design-OFDM-LFM-MIMO-Radar
Reproduction of the paper "Joint Design of OFDM-LFM Waveforms and Receive Filter for MIMO Radar in Spatial Heterogeneous Clutter."


## 理论基础 / Theoretical Foundation


![](https://github.com/wangsh386/Joint-Design-OFDM-LFM-MIMO-Radar/blob/main/images/core.png)

**公式说明**：
- **$\mathbf{s}$**：发射波形向量
- **$\mathbf{w}$**：接收滤波器向量
- **$\boldsymbol{\Phi}_t(\mathbf{w})$**：与信号相关的矩阵
- **$\boldsymbol{\Phi}_c(\mathbf{w})$**：与杂波相关的矩阵
- **$\sigma^2$**：噪声功率
- **$e_0$**：能量限制
- **$\mathcal{N}$**：天线集合
  
  

## 使用说明 / Usage
本项目包含以下主要 MATLAB Live Scripts，用于优化和可视化MIMO雷达波形设计：

1. **MIMOfuxianBTW.mlx**  
   这是主要的优化代码，整合了多个函数。运行此脚本后，优化结果将保存在工作区中。然后，您可以使用 **Spectra.mlx** 进行结果的可视化。

2. **MIMOfuxianTW.mlx**  
   该脚本固定初始的B，只优化T和W。适用于需要固定某些参数进行优化的情况。

3. **Spectra.mlx**  
   用于可视化优化后的结果。确保在运行 `MIMOfuxianBTW.mlx` 或 `MIMOfuxianTW.mlx` 之后，相关结果已保存在工作区中，然后运行此脚本以生成可视化图表。



## 实验结果 / Experimental Results
我们已基本完成对论文中实验结果的复现。复现结果与论文中的结果高度一致，验证了复现代码的正确性和有效性。

![](https://github.com/wangsh386/Joint-Design-OFDM-LFM-MIMO-Radar/blob/main/images/compare.png)
![](https://github.com/wangsh386/Joint-Design-OFDM-LFM-MIMO-Radar/blob/main/images/compare_2.png)



## 相关文献 / References
- M. Ding, Y. Li, J. Wei and E. Zhu, "Joint Design of OFDM-LFM Waveforms and Receive Filter for MIMO Radar in Spatial Heterogeneous Clutter," in *IEEE Geoscience and Remote Sensing Letters*, vol. 21, pp. 1-5, 2024, Art no. 3500105, doi: [10.1109/LGRS.2023.3331716](https://doi.org/10.1109/LGRS.2023.3331716).


## 关键词 / Keywords
Clutter; Optimization methods; MIMO radar; Transmitting antennas; OFDM; Receiving antennas; Radar antennas; Heterogeneous clutter; Iterative sequence optimization (ISO); Orthogonal frequency division multiplexing (OFDM)-LFM; Waveform design



## 许可证 / License
本项目基于MIT许可证。


