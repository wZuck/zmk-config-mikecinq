# mikecinq 无 LOGO 制造文件

来源：files/mikecinq.kicad_pcb（2026-11-04），导出前在临时副本重新铺铜。未添加 L.Y 或任何 LOGO，未修改源 PCB。

- 双层板，板厚 0.8 mm；铜厚 0.035 mm；当前板叠层配置为黑色阻焊、白色丝印。
- ZIP 内为 7 个 Gerber 层、PTH/NPTH 两个 Excellon 文件、Gerber job 文件。
- 全部采用绝对原点，钻孔单位 mm；Gerber 使用 X2 属性。
- NPTH 钻孔文件为空；板内圆孔按当前设计位于 Edge.Cuts，需按板框内铣孔加工。
- 未指定表面处理，下单时另行选择。

## DRC 结果

尚未完全通过：2 处未连接错误，均为 Chassis GND 填充区到 S15、S19 的 3 号焊盘。另有 76 条封装库未配置警告、42 条孤立铜警告。该包是当前设计的导出，不能视为已经通过生产检查。

## 文件校验

已检查 10 个文件非空、Gerber/Excellon 结束标记、job 文件引用及 ZIP 完整性。

源 PCB SHA-256：`a075a428ebcaafc357d0e6a980ba239517c1b3db1bfc418acea49c7b05b45ec5`

ZIP SHA-256：`e044daa082bceaeacc969c98fdf1d5618e52a35da35a9607a756e5ae6a7ededa`
