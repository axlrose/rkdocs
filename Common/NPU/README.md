## RK356X/RK3588 RKNN SDK to V1.2.0

### 主要修改

- 支持RK3588

- 优化内存使用

- 增加更多OP支持

- 提高稳定性

- 修复一些已知的BUG

###  版本号查询

  librknnrt runtime版本：1.2.0（strings librknnrt.so | grep version | grep lib）
  rknpu driver版本：0.6.4（dmesg | grep rknpu）

### 其他说明

rknn-toolkit适用RV1109/RV1126/RK1808/RK3399Pro，rknn-toolkit2适用RK356X/RK3588

rknn-toolkit2与rknn-toolkit API接口基本保持一致，用户不需要太多修改（rknn.config()部分参数有删减）

