# Asana 自动化流程归档

本仓库用于存档 iHouse 公司内部与 Asana 工作流相关的自动化流程（Make场景 + 规则配置 + 脚本 + 文档）。

## 项目结构
- `scenarios/`：Make 场景蓝图文件（可导入 JSON）
- `docs/`：使用文档、流程说明
- `scripts/`：JS/Python 脚本（如用于生成日期区段）
- `regex/`：正则表达式筛选规则说明
- `changelog.md`：更新记录

## 自动化目标
- 每日区段任务自动生成
- 出入金数据同步至 Google Sheets
- 日报归档与员工追踪流程整合

## 说明
- 本仓库用于归档与交流，不包含敏感数据
- Make 中使用 OpenAI 模块的配置暂未公开
