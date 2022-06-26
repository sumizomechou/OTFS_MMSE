# OTFS_MMSE
功能：以不同调制编码方式模拟OTFS传输的BER  
发射通道数：1  
调制方式：BPSK，QPSK，8PSK  
编码方式：卷积码  
编码速率：1/2，2/3  
均衡方式：MMSE  
信道估计方式：IPNLMS （已被注释，效果不佳）  
_ (1).mat: 一条Bellhop仿真的时变水声信道（行为时延维度，列为时间维度）
  
Function: Simulate the BER of the OTFS transmission with different modulation and coding methods  
Number of transmit channels: 1  
Modulation method: BPSK, QPSK, 8PSK  
Encoding method: convolutional code  
Encoding rate: 1/2, 2/3  
Equalization method: MMSE  
Channel estimation method: IPNLMS (annotated, not very good)  
_ (1).mat: A time-varying UWA channel simulated by Bellhop (rows are delay dimension, columns are time dimension).  
