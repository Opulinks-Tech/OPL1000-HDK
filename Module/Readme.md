## 模块方案:

**OPL1000 模块組合表**
| **HDK 版本**    | **V1**         | **V11**      | **V13**       | **V13**    | **V14**    |
| -------------- | -------------- | ------------ | --------------|------------|------------|
| **兼容性**      | **ESP32**      | **ESP8266**  | **ESP8266**   |  **ESP32** | **ESP8266**| 
| **性能版**      | **[D3FV](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/History/D3FV_v1.zip)** | **[D366FV_V11.F](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/History/D366FV_V11_F.zip)** | **[D366FV_V13.F](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/D366FV_V13.rar)** |  **[D332FV_V13.S](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/D332FV_V13.S.rar)**   | **[D366FV_V14](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/D366FV_V14.rar)** |
| **最佳功耗与成本版** | **[D3F](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/History/D3F_v1.zip)   [D3FP](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/History/D3FP_v1.zip) (无天线版本)** | **[D366F_V11.F](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/History/D366F_V11_F.zip)** | **[D366F_V13.F](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/D366F_V13.rar)**  |  N/A  | **[D366F_V14](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/D366F_V14.rar)** |  
  
  
**OPL1200 模块組合表**  
| HDK 版本  |    V1    |  
| --------  | ----- |  
|  **链结** |  **[OPL1200A2](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/OPL1200A2.rar)** | 
  
**OPL1200 球泡灯通用模组**  
| 釋出日期  | 2020/06/30 | 
| --------  | ----- |  
|  **链结** |  **[Light_OPL1200](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/light_OPL1200.rar)** | 


## 最新模块說明
1. D366F_V14为最新版本  
2. D366F_V14版本因增加Brown out &Diodes电路，请依产品需求,再选择使用V_14相关(Brown out &Diodes)线路    
  
* D366F_V14: 
  1. OPL1000 模块参考设计 (模块带外置FLASH 以及天线) <br>
  2. 最低BOM cost  
  3. ESP-12F管脚兼容设计  
  
* D366FV_V14:  
  1. OPL1000 模块参考设计 (模块带外置FLASH 以及天线, 并带外置的 LDO) <br>
  2. 使用外置LDO
  3. ESP-12F管脚兼容设计      

* OPL1200A2:  
  1. OPL1200 模块参考设计 (基于OPL1000上，内嵌flash)  
  
* Light_OPL1200 
  1. OPL1200球泡灯4层板通用模组
  
---
## 旧版本模块說明

* D366F_V13_F: 

OPL1000 模块参考设计 (模块带外置FLASH 以及天线) <br>

1. 最低BOM cost
2. ESP-12F管脚兼容设计

* D366FV_V13_F: 

OPL1000 模块参考设计 (模块带外置FLASH 以及天线, 并带外置的 LDO) <br>

1. 使用外置LDO
2. ESP-12F管脚兼容设计  

* D332FV_V13.S:  

OPL1000 模块参考设计 (模块带外置FLASH 以及天线, 并带外置的 LDO) <br>

1. 使用外置LDO  

---
**注意:**   
OPL1000提供F與S版本HDK.

　　　以上所列模块的F版本即为不包含上拉/下拉电阻及去耦电容的版本；　　

　　　除此之外，S版本为内置上拉/下拉电阻及去耦电容的 。
  
    （請參考下方上拉/下拉电阻及去耦电容）

**上拉/下拉电阻及去耦电容**

F版: 底板需增加上拉/下拉电阻及去耦电容

![avatar](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/History/F_PullUp.png)



S版: 模块内建上拉/下拉电阻及去耦电容

![avatar](https://github.com/Opulinks-Tech/OPL1000-HDK/blob/master/Module/History/S_PullUp.png)

## 旧版本
D3F: OPL1000 模块参考设计 (模块带外置FLASH 以及天线)

D3FP: OPL1000 模块参考设计 (模塊帶外置FLASH, 無天線)

D3FV: OPL1000 模块参考设计 (模块带外置FLASH 以及天线, 并带外置的 LDO)

## 目录结构
Driver_Tool: USB-to-UART 驱动工具

History: 历史版本存放区
