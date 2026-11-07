# Changelog / 更新日志

## [3.0] — First release / 首次发布

**English**

Initial open-source release of **PyGamiX V3.0**, the integrated CAD / CAM / simulation workbench for engineering origami accompanying the paper *Design and Fabrication of String-driven Origami Robots* (ICRA 2024).

- **Design (CAD):** crease-pattern import (DXF / parametric KL modules), interactive editing of panels and creases, tendon holes and actuation ends.
- **Fabrication (CAM):** layered DXF export for laser cutting, Split-DXF with hinge features for thick panels, STL export for 3D printing.
- **Physics simulation:** a Taichi physics simulator — in-plane stretching, crease and facet bending, tendon actuation through holes with friction, ground contact, implicit time stepping with energy-based line search.
- **Automated tendon actuation design:** MCTS-style multi-process search for tendon actuation strategies — which holes each tendon passes through and how far it is contracted — with ranked candidates and preset simulation / search settings.
- **Sim-to-real validation:** experiment recordings and simulation curves plotted in one figure for comparison.

**中文**

**PyGamiX V3.0** 首个开源版本——面向工程折纸的一体化 CAD / CAM / 仿真工作台，配套论文 *Design and Fabrication of String-driven Origami Robots*（ICRA 2024）。

- **设计（CAD）：** 折痕图导入（DXF / 参数化 KL 模块）、面板与折痕交互编辑、腱绳孔位与驱动端布置。
- **制造（CAM）：** 激光切割用分层 DXF 导出、带铰链特征的厚板 Split-DXF、3D 打印用 STL 导出。
- **物理仿真：** 基于 Taichi 的物理仿真器——面内拉伸、折痕与面片弯曲、腱绳过孔驱动与摩擦、地面接触、隐式时间积分与基于能量的线搜索。
- **腱绳驱动方案自动设计：** MCTS 风格多进程搜索完整的腱绳驱动方案（每根腱绳穿过哪些孔、收短多少），返回排序候选，支持仿真 / 搜索参数预设。
- **仿真-实物验证：** 实验记录与仿真曲线同图对比。
