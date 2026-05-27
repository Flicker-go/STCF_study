# 完整重建流程
* 包括 General、 Digitization、 BkgDigiMixing、 Reconstruction、 Classic Global PID 和 SummaryWriter六个部分。
  - 每个部分里面会包含两种调用：
  1. createSvc：调用服务，相当于调用算法的依赖项
  2. createAlg：调用算法
 

