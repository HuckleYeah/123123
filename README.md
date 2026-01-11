# 读书笔记：Git 与代码版本管理学习实践

## 一、书籍与学习资料信息

### （一）主要阅读/学习资料
1. 《Git 完整教程：初学者分步指南》
   - 来源：https://www.cnblogs.com/dc-s/p/18857953
   - 内容概述：系统介绍 Git 的基本概念、常用命令、分支管理以及与远程仓库的协作方式，适合初学者循序渐进学习。

2. Git 简易命令行入门教程
   - 来源：https://blog.csdn.net/NAMELZX/article/details/118891788
   - 内容概述：以实例形式介绍 Git 常见命令及基本使用流程，便于快速上手。

3. 【Git】Git 教程（三）—— SSH 方式链接 Git 与 GitHub（图文详解）
   - 来源：CSDN 博客
   - 内容概述：重点介绍 Git 与 GitHub 通过 SSH 方式建立安全连接的原理与操作步骤。

4. DeepSeek 大模型辅助学习
   - 用途：用于理解 Git 分支差异、命令含义以及排查配置过程中出现的问题。

---

## 二、阅读与学习内容概述

通过本次读书与资料学习，系统了解了 Git 作为分布式版本控制系统的基本思想，包括：
- Git 的版本管理原理
- 本地仓库与远程仓库的关系
- 提交（commit）、分支（branch）、推送（push）等核心概念
- Git 在多人协作与代码迭代中的实际应用价值

同时，结合实践操作，加深了对 Git 命令行操作流程的理解。

---

## 三、实践流程记录

### （一）Git 安装与环境配置
1. 从 Git 官网下载并安装 Git。
2. 在 Git Bash 中配置用户信息：
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "email@example.com"
