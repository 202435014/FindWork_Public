--- 
title: "FindWork_Public - 应届生求职网自动化工具" 
summary: "基于 Playwright 的应届生求职网 (yingjiesheng.com) 职位自动化申请工具，助力毕业生高效求职。" 
cover_url: "" 
demo_url: "" 
repo_url: "" 
is_featured: true 
tags: ["Python", "Playwright", "Automation"] 
--- 
 
# 项目详情 
 
**FindWork_Public** 是一个专为应届毕业生设计的网页自动化投递工具。该项目通过模拟真实用户操作，自动在“应届生求职网”上搜索目标职位并完成批量投递流程，显著降低了求职过程中的重复劳动。
 
## 核心功能 
 
- **交互式搜索**：支持在终端直接输入目标职位关键词，实时触发网页搜索。
- **批量一键申请**：自动定位页面中所有的“立即申请”按钮，并根据用户设定的次数进行循环投递。
- **自动翻页处理**：当当前页面的职位申请完毕后，程序能够自动识别并跳转至下一页继续执行。
- **多场景兼容**：智能处理“新窗口打开”与“页内弹窗”两种不同的申请反馈模式，确保自动化流程不中断。
- **Playwright 驱动**：利用高性能的浏览器自动化库，提供比传统爬虫更稳定的交互体验。

## 快速开始

1. 确保已安装 Python 环境。
2. 安装 Playwright 及其浏览器驱动：`pip install playwright` 且 `playwright install`。
3. 运行 `core/mian.py` 启动程序。

感谢关注本项目，祝你早日收获心仪的 Offer！
