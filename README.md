# CSM-ModSets-TagDB-UI

基于 [CSM（可通信状态机）](https://nevstop-lab.github.io/CSM-Wiki/) 框架的 TagDB 仪表盘与显示容器 UI 模块组，用于在 LabVIEW 前面板中展示和管理 TagDB 标签数据。

This repository contains CSM-based UI modules for displaying and managing TagDB tag data on LabVIEW front panels.

---

## 模块列表

| 模块                                                                                                          | 所属模块组                       | 功能说明                                     |
| ------------------------------------------------------------------------------------------------------------- | -------------------------------- | -------------------------------------------- |
| [TagDashboard](./TagDashboard/TagDashboard.md)                                                                | CSM-TagDashboard.lvlib           | 网格仪表盘，展示 TagDB 标签数据的实时快照    |
| [TagDisplayContainer](./TagDisplayContainer/TagDisplayContainer.md)                                           | CSM-TagDBDisplayContainer.lvlib  | 多视图容器，支持预定义页面切换和动态视图插入 |

---

## 许可

本项目采用 Apache License 2.0 发布。

---

- _完整 CSM 语法参考：<https://github.com/NEVSTOP-LAB/Communicable-State-Machine/blob/main/.doc/Syntax.md>_
- _CSM Wiki：<https://nevstop-lab.github.io/CSM-Wiki/>_