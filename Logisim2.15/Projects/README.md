# 项目文件 (Projects)

本文件夹包含 Logisim 电路设计项目文件。

## 📂 项目清单

### Basic-Circuits.circ
- **用途**：基础电路模块设计文件
- **内容**：包含基本的电路组件和设计
- **说明**：作为开发交通灯系统的基础模块库

## 🎯 项目用途

这些文件用于支持华科数字逻辑实验课程，特别是：
- **交通灯控制系统设计**
- 从基础模块逐步进阶到完整系统

## 🚀 如何使用

### 打开项目
1. 启动 Logisim：`Applications\logisim-ita-cn-2.15.exe`
2. 选择 `文件 → 打开`
3. 导航到本文件夹，选择 `.circ` 文件

### 创建新项目
1. 在 Logisim 中新建电路
2. 导入所需的芯片库（见 `Component-Libraries` 文件夹）
3. 设计电路
4. 保存到此文件夹

### 保存格式
- 格式：`.circ`（Logisim 原生格式）
- 编码：UTF-8
- 兼容性：Logisim 2.7.1+

## 📋 设计流程推荐

```
1. 查看基础电路模块
   └─ 打开 Basic-Circuits.circ

2. 导入所需芯片库
   └─ Component-Libraries/TTL-74x-Series/

3. 设计交通灯控制电路
   ├─ 7段数码管驱动电路
   ├─ 比较器与多路选择器
   ├─ BCD计数器
   └─ 完整系统集成

4. 仿真与调试
   └─ 使用 Logisim 的仿真工具验证电路

5. 保存项目
   └─ 保存到此文件夹或指定位置
```

## 🔗 相关文件

- **芯片库**：`../Component-Libraries/`
- **应用程序**：`../Applications/`
- **实验说明**：`../../readme.md`
- **项目主文件**：`../../Final.circ`（最终的交通灯系统）

## 💡 提示

- 定期保存你的工作（Ctrl+S）
- 复杂电路建议分模块设计，然后集成
- 充分利用 Logisim 的仿真工具进行验证

## ⚙️ 文件管理建议

建议为不同阶段的设计创建新文件：
```
Projects/
├── Basic-Circuits.circ           # 基础模块
├── Traffic-Light-v1.circ         # 第一版设计
├── Traffic-Light-v2.circ         # 优化版本
└── Traffic-Light-Final.circ       # 最终版本
```
