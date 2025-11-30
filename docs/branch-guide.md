\# 分支管理指南



\## 分支类型说明



\### 主分支 (main)

\- 用途：稳定版本，用于发布

\- 要求：只能通过Pull Request合并



\### 开发分支 (develop)  

\- 用途：日常开发集成

\- 要求：功能开发完成后的合并目标



\### 功能分支 (feature/\*)

\- 用途：新功能开发

\- 命名：feature/功能描述

\- 示例：feature/add-styling



\## 工作流程



\### 1. 开始新功能

```bash

git checkout develop

git checkout -b feature/新功能名称

