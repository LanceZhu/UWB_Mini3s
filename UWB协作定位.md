# UWB协作定位
- - 上位机相关

  - 软件：QT

  - 工程：

    - 目录：DecaRangeRTLS_PC_3p6

    - 路径：DecaRangeRTLS_PC_3p6  TREKdisplay.pro

      > TREKdisplay.pro.user为个人环境配置，初次使用可删除

- 下位机相关

  - 软件：Keil MDK-ARM

  - 工程：

    - 目录：Mini3s_f103_V1.8.1_dma_plus_vcp

    - 路径：Mini3s_f103_V1.8.1_dma_plus_vcp USER   SPI.uvprojx

    - 主函数：

      instance_run()

      decawave芯片

      基于TREK1000双边测距协议

    - Glossary

      - SPI(Serial Periphreal Interface)通用串行接口
      - irq(interupt request)中断请求
      - blink tag-anchor
      - spectrum 光谱

- 算法相关

