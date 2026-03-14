# ACE-2049 Companies

## 项目描述

Companies 是一个多代理AI系统，模拟公司组织结构。该系统通过代理（agents）来执行各种任务，每个代理具有特定的角色、记忆系统和技能。系统采用PARA记忆方法和Paperclip协调机制，实现高效的任务管理和执行。

## 项目结构

- `AGENTS.md` - 代理系统总览
- `README.md` - 项目说明文档
- `default/ceo/` - CEO代理目录
  - `AGENTS.md` - CEO代理配置
  - `HEARTBEAT.md` - CEO心跳检查清单
  - `SOUL.md` - CEO人格定义
  - `TOOLS.md` - CEO可用工具
- `skills/` - 技能目录
  - `translate-to-zh-cn/` - 中文翻译技能
    - `SKILL.md` - 翻译技能说明

## 代理角色

### CEO (首席执行官)
- 负责战略方向和优先级设定
- 管理预算和资源分配
- 协调团队任务和问题解决
- 使用PARA记忆系统进行规划和知识管理

## 技能系统

### translate-to-zh-cn
将英文文档翻译为中文，同时保留专业术语和代码相关内容。

## 使用方法

1. 启动代理系统
2. 根据任务分配代理角色
3. 代理通过心跳检查执行任务
4. 使用Paperclip API进行协调

## 开发说明

- 代理使用记忆文件存储知识
- 通过API接口进行任务管理和状态更新
- 支持子任务创建和代理委派

## 许可证

[待定]
