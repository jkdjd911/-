
2020：
  1.raft：baseline

2021：
  2.gma：global motion feature
  3.flow1D：4d 水平，垂直特征，减少计算量		
  4.separable flow*：可分析成本块			

2022：
  5.gmflow：transformer							
  6.Flowformer*：有点没完全懂					
  7.SKFlow：大小核（可分离）卷积核					
  8.KPA：额外滤波特征（局部）
  9.pola*：gmflow改						
  10.MS-raft+：尺度由粗到细堆叠raft
  11.CRAFT*：transformer生成4D成本块	
  12.AGFLow*：对fm和fc做图特征增强

2023:
  13.GAFlow:高斯滤波
  14.VideoFlow：多帧时序模型，正反向光流
  15.AccFlow：没懂（没源码）			
  16.Transflow:flowformer加强版（没源码）
  17.DCVNet：新模型（没源码）
  18.MFCFlow:4帧同练（没源码）
  19.EMD-Flow：上下文指导初始光流
  20.MatchFlow*：图像匹配先验知识		
  21：SamFlow*：FlowFormer辅助		
  22.LLA-Flow：局部滤波
  23.StreamFLow*：类transformer			

2024：
  24.CCMR*：MS-raft+改进			
  25.MeFlow*：Flow1D改进			
  26.rapidFlow*：NeXt1D卷积，提速
  27.ACPAFlow*：类比transformer			
  28.MemFlow：效果非常好
  29.RPKNet：PKConv，提速
  30.SplatFlow:没懂（没源码）
  40.Sea-raft：预训练概率回归，新loss，新编码器，解码器
