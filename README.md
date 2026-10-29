# EHNS 主控板硬件工程

KiCad 工程入口：`EH主控板.kicad_pro`。仓库包括原理图、PCB、本地元件库、元件数据库及原有生产输出。

`database/hqproject.db` 由 Git LFS 管理。克隆前请安装 Git LFS，然后执行：

```sh
git lfs install
git clone https://github.com/HW9711/EHNS_-.git
```

原工程的 `fp-lib-table` 保留了指向 `F:/库/Library.pretty` 的本机库条目；PCB 中还有一个 3D 模型引用 `${KICAD7_3RD_PARTY}`。在其他电脑上需要按实际环境配置这些外部路径。

`nextpcb/` 和 `output/` 是原目录已有的导出文件，是否与当前设计完全一致需要另行核对。
