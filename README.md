## 使用GitHub Action 构建一加ACE2内核（KernelSU,SukiSU,KernelSU NEXT）
注意：
- 可选原版KernelSU,，MKSU，SukiSU,Kernelsu NEXT(同样支持Wild Ksu)
- SukiSU不接受关于KPM的反馈，因为本身就有BUG
- 除了SukiSU外，勾选SUSFS都需要安装模块，否则无法调整设置
- action思路以及部分代码 来自[https://github.com/Numbersf] 大佬
### 致谢
- Numbersf[https://github.com/Numbersf]
- Bai[黄金猫猫头]
## 注意：当上游更新仓库时，SUSFS可能没有同步上游，所以有时候会导致SUSFS不可用，请等待上游仓库更新，或者使用旧版
