# notes-for-turbo-coding-and-decoding
The note briefly explains how turbo coding and decoding works.
# Turbo coding

<img src="./assets/image-20241016174607227.png" alt="image-20241016174607227" style="zoom:67%;" />

编码器形式如上，由两个并行的卷积码编码器构成，第一个编码器输出 ($\mathbf{v}^{(0)}$,$\mathbf{v}^{(1)}$) ，第二个编码器输出 ($\mathbf{v}^{(0)}$,$\mathbf{v}^{(2)}$) !!!! $\mathbf{v}^{(0)}=\mathbf{u}$ 是 信息序列,  $\mathbf{v}^{(1)}$ 和 $\mathbf{v}^{(2)}$ 叫 parity vector，$\pi$ 是交织器 interleaver，负责把输入信息打乱。
