# 主页 README

状态：已完成
分支：无
负责人：Howieu

## 目标
GitHub 主页一眼看出 Howie 做什么、做过什么、去哪看。

## 范围
- 居中页头：名字、一句定位、个人站链接（参考 op7418）；不放头像
- 个人优势四条：数字可信、AI 落地到流程、从需求到上线、数据底子；事实以简历项目为准
- GitHub bio 同步改写
- 产品清单：线上可用的作品，链线上地址（参考 oil-oil "My Products"）
- 开源项目表：项目、一句话、星标徽章（参考 oil-oil "Featured Skills"）
- 联系方式

## 不做
- 自动更新的统计 / 最新发布 / 博客列表（tw93 式 GitHub Action）：目前没有 release 和博客源，等有了再加
- 总星数徽章：数字小，反而减分

## 约束
- AGENTS.md 硬约束

## 验收
- [x] https://github.com/Howieu 显示新 README — 核对方式：gh api repos/Howieu/Howieu/readme
- [x] 所有链接 200 — 核对方式：curl

## 任务
- [x] T1 写 README.md
- [x] T2 建 Howieu/Howieu 公开仓库并推送

## 变更记录
- 2026-11-19 创建（Claude Code）
- 2026-11-19 去掉 memoji 头像和原介绍句，加个人优势，改 bio（Claude Code）
