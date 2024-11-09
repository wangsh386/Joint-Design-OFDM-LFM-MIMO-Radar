# Joint-Design-OFDM-LFM-MIMO-Radar
Reproduction of the paper "Joint Design of OFDM-LFM Waveforms and Receive Filter for MIMO Radar in Spatial Heterogeneous Clutter."


## 理论基础 / Theoretical Foundation

考虑到能量限制，基于最大化输出信号杂波噪声比（SCNR）的发射波形和接收滤波器的联合设计可以表示为：

$$
\begin{align*}
&\max _{{\mathbf {s,w}}} \quad {\frac {{{{\mathbf {s}}}^{H}}{{ \boldsymbol {\Phi }}_{t}}\left ({{\mathbf {w}} }\right){\mathbf {s}}}}{{{{\mathbf {s}}^{H}}{{ \boldsymbol {\Phi }}_{c}}\left ({{\mathbf {w}} }\right){\mathbf {s}} + {\sigma ^{2}}{{\mathbf {w}}^{H}}{\mathbf {w}}}}} \\
&\text {s.t.} \quad {{{\left \|{ {{{\mathbf {s}}_{n}}} }\right \|}^{2}} = {e_{0}},\quad n \in \mathcal {N}} \\
&\hphantom {\text {s.t.} } \quad {{{\left \|{ {\mathbf {w}} }\right \|}^{2}} = 1} \tag{8}
\end{align*}
$$

**公式说明**：
- **$\mathbf{s}$**：发射波形向量
- **$\mathbf{w}$**：接收滤波器向量
- **$\boldsymbol{\Phi}_t(\mathbf{w})$**：与信号相关的矩阵
- **$\boldsymbol{\Phi}_c(\mathbf{w})$**：与杂波相关的矩阵
- **$\sigma^2$**：噪声功率
- **$e_0$**：能量限制
- **$\mathcal{N}$**：天线集合
  
  

## 使用说明 / Usage




## 实验结果 / Experimental Results
我们已基本完成对论文中实验结果的复现。复现结果与论文中的结果高度一致，验证了复现代码的正确性和有效性。

![](https://github.com/wangsh386/Joint-Design-OFDM-LFM-MIMO-Radar/blob/main/images/compare.png)
![](https://github.com/wangsh386/Joint-Design-OFDM-LFM-MIMO-Radar/blob/main/images/compare_2.png)



## 相关文献 / References
- M. Ding, Y. Li, J. Wei and E. Zhu, "Joint Design of OFDM-LFM Waveforms and Receive Filter for MIMO Radar in Spatial Heterogeneous Clutter," in *IEEE Geoscience and Remote Sensing Letters*, vol. 21, pp. 1-5, 2024, Art no. 3500105, doi: [10.1109/LGRS.2023.3331716](https://doi.org/10.1109/LGRS.2023.3331716).
- 

## 关键词 / Keywords
Clutter; Optimization methods; MIMO radar; Transmitting antennas; OFDM; Receiving antennas; Radar antennas; Heterogeneous clutter; Iterative sequence optimization (ISO); Orthogonal frequency division multiplexing (OFDM)-LFM; Waveform design



## 许可证 / License
本项目基于MIT许可证。有关详细信息，请参阅 [LICENSE](LICENSE)。

---

## License
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the "Software"), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in  
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN  
THE SOFTWARE.
