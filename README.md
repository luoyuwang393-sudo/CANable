# CANable

CANable 硬件设计工程，使用 Altium Designer，包含原理图、PCB 布局布线、封装库以及项目输出资料。

## 文件说明

| 文件 | 用途 |
| --- | --- |
| `CANable.PrjPcb` | Altium Designer 工程入口 |
| `CANable.SchDoc` | 原理图 |
| `CANable-250818.PcbDoc` | PCB 布局布线 |
| `CANable.PcbLib` | PCB 封装库 |
| `CANable.PrjPcbStructure` | 工程层级描述 |
| `CANable-250818.zip` | 原始工程压缩附件 |
| `Project Outputs for CANable.zip` | 项目输出目录的压缩包，解压后保留原目录名 |

## 项目输出资料

`Project Outputs for CANable.zip` 包含：

- `CANable-BOM-250820.xlsx`：BOM 表。
- `Pick Place for CANable-250818.csv`：元器件贴片坐标。
- `Design Rule Check - CANable-250818.drc`、对应 HTML 文件：设计规则检查报告。
- `Status Report.Txt`：状态报告。

## 打开方式

1. 下载或克隆本仓库。
2. 将 `Project Outputs for CANable.zip` 解压到工程根目录，恢复 `Project Outputs for CANable` 文件夹。
3. 使用 Altium Designer 打开 `CANable.PrjPcb`，查看原理图、PCB 和封装库。

## 设计工作

独立完成器件选型、原理图设计、封装制作、PCB 布局布线、BOM 整理及调试。
