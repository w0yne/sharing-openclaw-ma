---
theme: apple-basic
title: "OpenClaw 如何重塑 AI 生产力"
info: |
  OpenClaw — Medical Affairs Sharing
layout: intro-image-right
image: ''
colorSchema: light
drawings:
  persist: false
transition: slide-left
mdc: true
---

# OpenClaw

<div style="font-size: 1.6rem; color: #666; margin-top: 1rem; font-weight: 300;">
如何重塑 AI 生产力
</div>

<div style="margin-top: 3rem; font-size: 0.95rem; color: #999;">
Open Source · Self-Hosted · Enterprise-Ready
</div>

<div style="margin-top: 2.5rem; font-size: 0.85rem; color: #888;">
<strong style="color: #555;">Speaker</strong> · Solutions Architect · AWS<br/>
Medical Affairs Team · 2026.04
</div>

---

# 今天聊什么

<div style="display: grid; grid-template-columns: repeat(5, 1fr); gap: 1rem; margin-top: 2.5rem;">

<div style="text-align: center; padding: 1.5rem 0.8rem; border: 1px solid #e5e7eb; border-radius: 12px;">
<div style="font-size: 2rem; font-weight: 700; color: #000;">01</div>
<div style="font-size: 0.9rem; font-weight: 600; margin-top: 0.5rem;">AI Agent 是什么</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">从聊天到干活</div>
</div>

<div style="text-align: center; padding: 1.5rem 0.8rem; border: 1px solid #e5e7eb; border-radius: 12px;">
<div style="font-size: 2rem; font-weight: 700; color: #000;">02</div>
<div style="font-size: 0.9rem; font-weight: 600; margin-top: 0.5rem;">OpenClaw 是什么</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">数字员工的<br/>操作系统</div>
</div>

<div style="text-align: center; padding: 1.5rem 0.8rem; border: 1px solid #e5e7eb; border-radius: 12px;">
<div style="font-size: 2rem; font-weight: 700; color: #000;">03</div>
<div style="font-size: 0.9rem; font-weight: 600; margin-top: 0.5rem;">三种使用场景</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">你的龙虾同事<br/>能做什么</div>
</div>

<div style="text-align: center; padding: 1.5rem 0.8rem; border: 1px solid #e5e7eb; border-radius: 12px;">
<div style="font-size: 2rem; font-weight: 700; color: #000;">04</div>
<div style="font-size: 0.9rem; font-weight: 600; margin-top: 0.5rem;">医学场景深挖</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">临床试验 &<br/>医学文档</div>
</div>

<div style="text-align: center; padding: 1.5rem 0.8rem; border: 1px solid #e5e7eb; border-radius: 12px;">
<div style="font-size: 2rem; font-weight: 700; color: #000;">05</div>
<div style="font-size: 0.9rem; font-weight: 600; margin-top: 0.5rem;">安全与部署</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">数据不出境<br/>生产级架构</div>
</div>

</div>

---
layout: section
---

<div style="font-size: 0.9rem; color: #999; text-transform: uppercase; letter-spacing: 0.15em;">Part One</div>

# AI Agent 是什么

---

# 聊天机器人 vs 数字员工

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 0; margin-top: 2rem;">

<div>
<div style="padding: 1.5rem 2rem; border-bottom: 1px solid #eee;">
<div style="font-size: 0.75rem; color: #999; text-transform: uppercase; letter-spacing: 0.1em;">聊天机器人 ChatBot</div>
<div style="font-size: 1.1rem; margin-top: 0.5rem; font-weight: 500;">你问一句，它答一句</div>
<div style="font-size: 0.85rem; color: #888; margin-top: 0.3rem;">像查字典 📖</div>
</div>
<div style="padding: 1.5rem 2rem; border-bottom: 1px solid #eee;">
<div style="font-size: 0.85rem; color: #888;">不能操作任何系统</div>
</div>
<div style="padding: 1.5rem 2rem; border-bottom: 1px solid #eee;">
<div style="font-size: 0.85rem; color: #888;">每次对话从零开始</div>
</div>
<div style="padding: 1.5rem 2rem;">
<div style="font-size: 0.85rem; color: #888;">只能给建议，不能帮你做</div>
</div>
</div>

<div>
<div style="padding: 1.5rem 2rem; border-bottom: 1px solid #eee; border-left: 3px solid #ef4444;">
<div style="font-size: 0.75rem; color: #ef4444; text-transform: uppercase; letter-spacing: 0.1em;">数字员工 AI Agent</div>
<div style="font-size: 1.1rem; margin-top: 0.5rem; font-weight: 600;">你给目标，它自己规划执行</div>
<div style="font-size: 0.85rem; color: #888; margin-top: 0.3rem;">像一个实习生 🧑‍💼</div>
</div>
<div style="padding: 1.5rem 2rem; border-bottom: 1px solid #eee; border-left: 3px solid #ef4444;">
<div style="font-size: 0.85rem; font-weight: 500;">能查邮件、写文档、操作系统</div>
</div>
<div style="padding: 1.5rem 2rem; border-bottom: 1px solid #eee; border-left: 3px solid #ef4444;">
<div style="font-size: 0.85rem; font-weight: 500;">记住你说过什么、做过什么</div>
</div>
<div style="padding: 1.5rem 2rem; border-left: 3px solid #ef4444;">
<div style="font-size: 0.85rem; font-weight: 500;">能主动干活，交付结果</div>
</div>
</div>

</div>

---

# 数字员工 = 大脑 + 手 + 记忆

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 2rem; margin-top: 2.5rem;">

<div style="padding: 2rem 1.5rem; border: 1px solid #e5e7eb; border-radius: 12px; text-align: center;">
<div style="font-size: 2.5rem; margin-bottom: 1rem;">🧠</div>
<div style="font-weight: 700; font-size: 1.1rem;">大脑</div>
<div style="font-size: 0.8rem; color: #666; margin-top: 0.5rem; font-weight: 500;">大语言模型</div>
<div style="font-size: 0.75rem; color: #999; margin-top: 0.8rem; line-height: 1.6;">
能理解自然语言<br/>
能推理和判断<br/>
能生成内容
</div>
</div>

<div style="padding: 2rem 1.5rem; border: 1px solid #e5e7eb; border-radius: 12px; text-align: center;">
<div style="font-size: 2.5rem; margin-bottom: 1rem;">🤲</div>
<div style="font-weight: 700; font-size: 1.1rem;">手</div>
<div style="font-size: 0.8rem; color: #666; margin-top: 0.5rem; font-weight: 500;">工具调用</div>
<div style="font-size: 0.75rem; color: #999; margin-top: 0.8rem; line-height: 1.6;">
查邮件、看日历<br/>
写文档、做表格<br/>
操作业务系统
</div>
</div>

<div style="padding: 2rem 1.5rem; border: 1px solid #e5e7eb; border-radius: 12px; text-align: center;">
<div style="font-size: 2.5rem; margin-bottom: 1rem;">💾</div>
<div style="font-weight: 700; font-size: 1.1rem;">记忆</div>
<div style="font-size: 0.8rem; color: #666; margin-top: 0.5rem; font-weight: 500;">上下文持久化</div>
<div style="font-size: 0.75rem; color: #999; margin-top: 0.8rem; line-height: 1.6;">
记住你的偏好<br/>
记住历史对话<br/>
越用越懂你
</div>
</div>

</div>

<div style="text-align: center; margin-top: 2.5rem; padding: 0.8rem 2rem; background: #f8fafc; border-radius: 8px; border: 1px solid #e5e7eb;">
<span style="font-size: 1rem; color: #333; font-weight: 500;">数字员工不是更聪明的聊天，是<strong style="color: #ef4444;">能干活</strong>的 AI。</span>
</div>

---
layout: section
---

<div style="font-size: 0.9rem; color: #999; text-transform: uppercase; letter-spacing: 0.15em;">Part Two</div>

# OpenClaw 是什么

---

# 数字员工的操作系统

<div style="font-size: 1.1rem; color: #555; margin: 0.5rem 0 2rem; font-weight: 300;">
如果数字员工是员工，OpenClaw 就是办公室。
</div>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 2.5rem;">

<div>

<div style="padding: 1.2rem 1.5rem; border-bottom: 1px solid #eee; margin-bottom: 0;">
<div style="font-size: 0.75rem; color: #999; text-transform: uppercase; letter-spacing: 0.1em;">类比</div>
<div style="font-size: 0.95rem; margin-top: 0.3rem;">数字员工 = <strong>员工</strong></div>
</div>
<div style="padding: 1.2rem 1.5rem; border-bottom: 1px solid #eee;">
<div style="font-size: 0.95rem;">OpenClaw = <strong>办公室</strong></div>
<div style="font-size: 0.8rem; color: #888; margin-top: 0.3rem;">给它工位、电脑、门禁卡、通讯录</div>
</div>

<div style="margin-top: 1.5rem;">

<div style="padding: 0.8rem 1rem; background: #f8f9fa; border-radius: 8px; margin-bottom: 0.6rem;">
<span style="font-size: 0.85rem;">🔓 <strong>开源</strong> — 代码完全公开，可审计</span>
</div>
<div style="padding: 0.8rem 1rem; background: #f8f9fa; border-radius: 8px; margin-bottom: 0.6rem;">
<span style="font-size: 0.85rem;">🏠 <strong>自部署</strong> — 跑在自己的基础设施上</span>
</div>
<div style="padding: 0.8rem 1rem; background: #f8f9fa; border-radius: 8px;">
<span style="font-size: 0.85rem;">🔒 <strong>数据不出境</strong> — 合规有保障</span>
</div>

</div>

</div>

<div style="display: flex; align-items: center;">
<div style="width: 100%; padding: 1.5rem; background: #f8fafc; border-radius: 10px; border: 1px solid #e5e7eb;">
<div style="font-size: 0.75rem; color: #999; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 1rem;">核心价值</div>
<div style="font-size: 1.15rem; font-weight: 500; line-height: 1.7; color: #333;">
一个平台<br/>
管理所有数字员工<br/>
连接所有工具<br/>
服务整个团队
</div>
</div>
</div>

</div>

---

# 它是怎么工作的

<div style="display: flex; align-items: center; justify-content: center; margin-top: 3rem;">
<div style="display: flex; align-items: center; gap: 0;">

<div style="text-align: center; width: 140px;">
<div style="width: 68px; height: 68px; background: #f0f9ff; border-radius: 14px; display: flex; align-items: center; justify-content: center; margin: 0 auto; font-size: 1.8rem;">👤</div>
<div style="font-weight: 600; font-size: 0.85rem; margin-top: 0.7rem;">用户</div>
<div style="font-size: 0.7rem; color: #888;">医学团队成员</div>
</div>

<div style="font-size: 1.5rem; color: #ccc; margin: 0 0.3rem;">→</div>

<div style="text-align: center; width: 140px;">
<div style="width: 68px; height: 68px; background: #f0fdf4; border-radius: 14px; display: flex; align-items: center; justify-content: center; margin: 0 auto; font-size: 1.8rem;">💬</div>
<div style="font-weight: 600; font-size: 0.85rem; margin-top: 0.7rem;">消息平台</div>
<div style="font-size: 0.7rem; color: #888;">飞书 / Slack / 微信</div>
</div>

<div style="font-size: 1.5rem; color: #ccc; margin: 0 0.3rem;">→</div>

<div style="text-align: center; width: 140px;">
<div style="width: 68px; height: 68px; background: #111; border-radius: 14px; display: flex; align-items: center; justify-content: center; margin: 0 auto; font-size: 1.8rem;">🦞</div>
<div style="font-weight: 600; font-size: 0.85rem; margin-top: 0.7rem;">OpenClaw</div>
<div style="font-size: 0.7rem; color: #888;">调度 & 编排中心</div>
</div>

<div style="font-size: 1.5rem; color: #ccc; margin: 0 0.3rem;">→</div>

<div style="text-align: center; width: 140px;">
<div style="width: 68px; height: 68px; background: #fef3c7; border-radius: 14px; display: flex; align-items: center; justify-content: center; margin: 0 auto; font-size: 1.8rem;">🧠</div>
<div style="font-weight: 600; font-size: 0.85rem; margin-top: 0.7rem;">AI 大脑</div>
<div style="font-size: 0.7rem; color: #888;">+ 各种工具</div>
</div>

</div>
</div>

<div style="text-align: center; margin-top: 2.5rem; padding: 0.8rem 2rem; background: #f8fafc; border-radius: 8px; border: 1px solid #e5e7eb;">
<span style="font-size: 0.9rem; color: #475569;">用户不需要换工具 — 在<strong>飞书</strong>里就能跟数字员工对话</span>
</div>

---
layout: section
---

<div style="font-size: 0.9rem; color: #999; text-transform: uppercase; letter-spacing: 0.15em;">Part Three</div>

# 三种使用场景

<div style="font-size: 1.2rem; color: #666; margin-top: 1rem; font-weight: 300;">
你的龙虾同事 🦞 能做什么
</div>

---

# 场景一：1:1 贴身助手

<div style="font-size: 0.95rem; color: #666; margin: 0.5rem 0 1.5rem;">每个人都有一个随叫随到的数字员工。</div>

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 1rem;">

<div style="padding: 1.3rem; border: 1px solid #e5e7eb; border-radius: 10px; text-align: center;">
<div style="font-size: 1.5rem; margin-bottom: 0.5rem;">📅</div>
<div style="font-weight: 600; font-size: 0.85rem;">日程提醒</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">自动整理今天的<br/>日程和待办</div>
</div>

<div style="padding: 1.3rem; border: 1px solid #e5e7eb; border-radius: 10px; text-align: center;">
<div style="font-size: 1.5rem; margin-bottom: 0.5rem;">📰</div>
<div style="font-weight: 600; font-size: 0.85rem;">资讯摘要</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">行业动态、竞品<br/>信息一键整理</div>
</div>

<div style="padding: 1.3rem; border: 1px solid #e5e7eb; border-radius: 10px; text-align: center;">
<div style="font-size: 1.5rem; margin-bottom: 0.5rem;">🌐</div>
<div style="font-weight: 600; font-size: 0.85rem;">翻译 & 检索</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">多语言翻译<br/>快速信息查找</div>
</div>

<div style="padding: 1.3rem; border: 1px solid #e5e7eb; border-radius: 10px; text-align: center;">
<div style="font-size: 1.5rem; margin-bottom: 0.5rem;">✉️</div>
<div style="font-weight: 600; font-size: 0.85rem;">邮件管理</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">未读邮件摘要<br/>帮你拟回复</div>
</div>

</div>

<div style="margin-top: 1.5rem; padding: 1rem 1.5rem; border-left: 3px solid #0284c7; background: #f0f9ff; border-radius: 0 8px 8px 0;">
<div style="font-size: 0.75rem; color: #0284c7; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 0.3rem;">医学场景</div>
<div style="font-size: 0.85rem; color: #333;">MSL 出差前，让数字员工帮忙整理目标 KOL 的最新发表和学术动态。<br/>早上打开飞书，日程、未回邮件、今日重点已经整理好了。</div>
</div>

---

# 场景二：管理者助手

<div style="font-size: 0.95rem; color: #666; margin: 0.5rem 0 1.5rem;">多个数字员工协同工作，帮管理者盯进度、做汇报。</div>

<div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 1.5rem; margin-top: 1rem;">

<div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px;">
<div style="font-size: 1.3rem; margin-bottom: 0.5rem;">📊</div>
<div style="font-weight: 600; font-size: 0.9rem;">项目追踪</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.5rem; line-height: 1.6;">
自动盯项目进度<br/>
异常即时提醒<br/>
周报自动生成
</div>
</div>

<div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px;">
<div style="font-size: 1.3rem; margin-bottom: 0.5rem;">📝</div>
<div style="font-weight: 600; font-size: 0.9rem;">会议纪要</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.5rem; line-height: 1.6;">
自动整理纪要<br/>
提取待办事项<br/>
跟进落实情况
</div>
</div>

<div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px;">
<div style="font-size: 1.3rem; margin-bottom: 0.5rem;">☀️</div>
<div style="font-weight: 600; font-size: 0.9rem;">晨间简报</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.5rem; line-height: 1.6;">
每天早上一份<br/>
关键指标汇总<br/>
需要决策的事项
</div>
</div>

</div>

<div style="margin-top: 1.5rem; padding: 1rem 1.5rem; border-left: 3px solid #0284c7; background: #f0f9ff; border-radius: 0 8px 8px 0;">
<div style="font-size: 0.75rem; color: #0284c7; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 0.3rem;">医学场景</div>
<div style="font-size: 0.85rem; color: #333;">医学总监让数字员工追踪多个临床试验的 milestone，有延迟自动预警。</div>
</div>

---

# 场景三：团队智能基础设施

<div style="font-size: 0.95rem; color: #666; margin: 0.5rem 0 1.5rem;">整个团队共用一个数字员工 — 在群里 @龙虾 就能求助。</div>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; margin-top: 1rem;">

<div>

<div style="padding: 1rem 1.2rem; border: 1px solid #e5e7eb; border-radius: 8px; margin-bottom: 0.8rem;">
<div style="font-weight: 600; font-size: 0.9rem;">🔍 知识问答</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.3rem;">新员工问数字员工就能查 SOP、流程、历史决策</div>
</div>

<div style="padding: 1rem 1.2rem; border: 1px solid #e5e7eb; border-radius: 8px; margin-bottom: 0.8rem;">
<div style="font-weight: 600; font-size: 0.9rem;">📋 流程自动化</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.3rem;">审批提醒、文档归档、定期报告自动生成</div>
</div>

<div style="padding: 1rem 1.2rem; border: 1px solid #e5e7eb; border-radius: 8px;">
<div style="font-weight: 600; font-size: 0.9rem;">🤝 跨团队协作</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.3rem;">不同部门的数字员工之间可以互相沟通协调</div>
</div>

</div>

<div style="display: flex; align-items: center;">
<div style="width: 100%; padding: 1.5rem; background: #f8fafc; border-radius: 10px; border: 1px solid #e5e7eb;">
<div style="font-size: 0.75rem; color: #999; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 1rem;">三级进化</div>
<div style="font-size: 0.95rem; line-height: 2; color: #333;">
<strong>Level 1</strong> — 个人助手<br/>
<strong>Level 2</strong> — 管理者助手<br/>
<strong style="color: #ef4444;">Level 3</strong> — 团队基础设施<br/>
</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.8rem;">从个人效率提升 → 团队协作升级 → 组织智能化</div>
</div>
</div>

</div>

---
layout: section
---

<div style="font-size: 0.9rem; color: #999; text-transform: uppercase; letter-spacing: 0.15em;">Part Four</div>

# 医学场景深挖

---

# 场景 A：临床试验文档处理

<div style="font-size: 0.95rem; color: #666; margin: 0.5rem 0 1.5rem;">海量文档是医学团队的日常 — 数字员工帮你处理繁重的文书工作。</div>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 2rem;">

<div>
<div style="font-size: 0.75rem; color: #ef4444; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 0.8rem;">痛点</div>

<div style="padding: 0.8rem 1rem; border-left: 3px solid #ef4444; margin-bottom: 0.6rem;">
<div style="font-size: 0.85rem; color: #333;">Protocol、ICF、IB 版本频繁更新</div>
</div>
<div style="padding: 0.8rem 1rem; border-left: 3px solid #ef4444; margin-bottom: 0.6rem;">
<div style="font-size: 0.85rem; color: #333;">SAE 报告需要快速处理和归档</div>
</div>
<div style="padding: 0.8rem 1rem; border-left: 3px solid #ef4444;">
<div style="font-size: 0.85rem; color: #333;">跨文档一致性检查耗时巨大</div>
</div>
</div>

<div>
<div style="font-size: 0.75rem; color: #16a34a; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 0.8rem;">数字员工能做</div>

<div style="padding: 0.8rem 1rem; border-left: 3px solid #16a34a; margin-bottom: 0.6rem;">
<div style="font-size: 0.85rem; color: #333; font-weight: 500;">文档摘要与版本对比</div>
</div>
<div style="padding: 0.8rem 1rem; border-left: 3px solid #16a34a; margin-bottom: 0.6rem;">
<div style="font-size: 0.85rem; color: #333; font-weight: 500;">合规性初步检查</div>
</div>
<div style="padding: 0.8rem 1rem; border-left: 3px solid #16a34a;">
<div style="font-size: 0.85rem; color: #333; font-weight: 500;">关键时间节点追踪与提醒</div>
</div>
</div>

</div>

<div style="text-align: center; margin-top: 2rem; padding: 0.8rem 2rem; background: #fff7ed; border-radius: 8px; border: 1px solid #fed7aa;">
<span style="font-size: 0.95rem; color: #9a3412; font-weight: 500;">数字员工不替你做医学判断，但能帮你处理 <strong>80%</strong> 的文书工作</span>
</div>

---

# 场景 B：医学文档撰写 & Review

<div style="font-size: 0.95rem; color: #666; margin: 0.5rem 0 2rem;">让数字员工成为你的写作搭档 — Co-pilot，不是 Auto-pilot。</div>

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1.5rem;">

<div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px;">
<div style="font-size: 1.3rem; margin-bottom: 0.5rem;">✍️</div>
<div style="font-weight: 600; font-size: 0.9rem;">初稿辅助</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.5rem; line-height: 1.6;">
CSR 初稿框架搭建<br/>
基于模板快速生成<br/>
引用文献自动关联
</div>
</div>

<div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px;">
<div style="font-size: 1.3rem; margin-bottom: 0.5rem;">🔎</div>
<div style="font-weight: 600; font-size: 0.9rem;">交叉审阅</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.5rem; line-height: 1.6;">
数据一致性检查<br/>
术语标准化校验<br/>
格式规范检查
</div>
</div>

<div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px;">
<div style="font-size: 1.3rem; margin-bottom: 0.5rem;">📄</div>
<div style="font-weight: 600; font-size: 0.9rem;">递交准备</div>
<div style="font-size: 0.78rem; color: #888; margin-top: 0.5rem; line-height: 1.6;">
监管要求核对<br/>
文档清单检查<br/>
递交前预审
</div>
</div>

</div>

<div style="text-align: center; margin-top: 2rem; padding: 0.8rem 2rem; background: #f8fafc; border-radius: 8px; border: 1px solid #e5e7eb;">
<span style="font-size: 0.95rem; color: #333; font-weight: 500;">数字员工是 <strong>Co-pilot</strong>，不是 Auto-pilot — 最终判断<strong style="color: #ef4444;">永远是人做</strong></span>
</div>

---
layout: section
---

<div style="font-size: 0.9rem; color: #999; text-transform: uppercase; letter-spacing: 0.15em;">Part Five</div>

# 安全性 + 部署架构

---

# 数据安全：不出境，可审计

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 2rem; margin-top: 2rem;">

<div>

<div style="padding: 1.2rem 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px; margin-bottom: 1rem;">
<div style="display: flex; align-items: center; gap: 0.6rem;">
<div style="width: 32px; height: 32px; background: #f0f9ff; border-radius: 8px; display: flex; align-items: center; justify-content: center; font-size: 1rem;">🏠</div>
<div>
<div style="font-weight: 600; font-size: 0.85rem;">自有 AWS 账号部署</div>
<div style="font-size: 0.72rem; color: #888;">数据不离开你的基础设施</div>
</div>
</div>
</div>

<div style="padding: 1.2rem 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px; margin-bottom: 1rem;">
<div style="display: flex; align-items: center; gap: 0.6rem;">
<div style="width: 32px; height: 32px; background: #f0fdf4; border-radius: 8px; display: flex; align-items: center; justify-content: center; font-size: 1rem;">🛡️</div>
<div>
<div style="font-weight: 600; font-size: 0.85rem;">Amazon Bedrock</div>
<div style="font-size: 0.72rem; color: #888;">数据不用于模型训练</div>
</div>
</div>
</div>

<div style="padding: 1.2rem 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px; margin-bottom: 1rem;">
<div style="display: flex; align-items: center; gap: 0.6rem;">
<div style="width: 32px; height: 32px; background: #fef3c7; border-radius: 8px; display: flex; align-items: center; justify-content: center; font-size: 1rem;">🔐</div>
<div>
<div style="font-weight: 600; font-size: 0.85rem;">端到端加密</div>
<div style="font-size: 0.72rem; color: #888;">传输与存储全程加密</div>
</div>
</div>
</div>

<div style="padding: 1.2rem 1.5rem; border: 1px solid #e5e7eb; border-radius: 10px;">
<div style="display: flex; align-items: center; gap: 0.6rem;">
<div style="width: 32px; height: 32px; background: #ede9fe; border-radius: 8px; display: flex; align-items: center; justify-content: center; font-size: 1rem;">👁️</div>
<div>
<div style="font-weight: 600; font-size: 0.85rem;">开源 = 可审计</div>
<div style="font-size: 0.72rem; color: #888;">每一行代码都可以审查</div>
</div>
</div>
</div>

</div>

<div style="display: flex; align-items: center;">
<div style="width: 100%; padding: 1.5rem; background: #f8fafc; border-radius: 10px; border: 1px solid #e5e7eb;">
<div style="font-size: 0.75rem; color: #999; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 1rem;">合规要点</div>
<div style="font-size: 0.9rem; line-height: 1.8; color: #333;">
✅ 数据存储在中国区 AWS<br/>
✅ 不经过任何第三方<br/>
✅ 权限隔离，按角色管控<br/>
✅ 审计日志完整可追溯<br/>
✅ 满足药企合规要求
</div>
</div>
</div>

</div>

---

# AWS 部署架构（极简版）

<div style="display: flex; align-items: center; justify-content: center; margin-top: 2.5rem;">
<div style="display: flex; align-items: stretch; gap: 0;">

<div style="text-align: center; width: 200px; padding: 1.5rem; background: #f0f9ff; border-radius: 12px 0 0 12px; border: 1px solid #e5e7eb;">
<div style="font-size: 0.7rem; color: #0284c7; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 0.8rem;">用户层</div>
<div style="font-size: 2rem; margin-bottom: 0.5rem;">💬</div>
<div style="font-size: 0.85rem; font-weight: 600;">飞书 / Slack</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">用户在熟悉的<br/>平台上对话</div>
</div>

<div style="display: flex; align-items: center; font-size: 1.5rem; color: #ccc; padding: 0 0.5rem;">→</div>

<div style="text-align: center; width: 200px; padding: 1.5rem; background: #111; border-radius: 0; border: 1px solid #333; color: #fff;">
<div style="font-size: 0.7rem; color: #999; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 0.8rem;">应用层</div>
<div style="font-size: 2rem; margin-bottom: 0.5rem;">🦞</div>
<div style="font-size: 0.85rem; font-weight: 600;">OpenClaw on ECS</div>
<div style="font-size: 0.7rem; color: #999; margin-top: 0.3rem;">容器化部署<br/>弹性伸缩</div>
</div>

<div style="display: flex; align-items: center; font-size: 1.5rem; color: #ccc; padding: 0 0.5rem;">→</div>

<div style="text-align: center; width: 200px; padding: 1.5rem; background: #fef3c7; border-radius: 0 12px 12px 0; border: 1px solid #e5e7eb;">
<div style="font-size: 0.7rem; color: #d97706; text-transform: uppercase; letter-spacing: 0.1em; margin-bottom: 0.8rem;">AI 层</div>
<div style="font-size: 2rem; margin-bottom: 0.5rem;">🧠</div>
<div style="font-size: 0.85rem; font-weight: 600;">Amazon Bedrock</div>
<div style="font-size: 0.7rem; color: #888; margin-top: 0.3rem;">Claude / 多模型<br/>数据不出境</div>
</div>

</div>
</div>

<div style="text-align: center; margin-top: 2.5rem; padding: 0.8rem 2rem; background: #f8fafc; border-radius: 8px; border: 1px solid #e5e7eb;">
<span style="font-size: 0.95rem; color: #333; font-weight: 500;">Production-ready — 不是玩具，是可以<strong style="color: #ef4444;">上生产环境</strong>的</span>
</div>

---

# 关键要点

<div style="display: flex; align-items: center; justify-content: center; height: 60%;">
<div style="max-width: 700px;">

<div style="font-size: 1.6rem; font-weight: 300; line-height: 1.6; color: #333; text-align: center;">
AI 不再只是聊天工具<br/>
它可以成为你的<strong style="color: #000;">数字员工</strong><br/>
在你熟悉的平台上<br/>
<strong style="color: #ef4444;">真正帮你干活</strong>
</div>

<div style="display: flex; justify-content: center; gap: 3rem; margin-top: 3rem;">
<div style="text-align: center;">
<div style="font-size: 1.8rem; font-weight: 700; color: #000;">开源</div>
<div style="font-size: 0.8rem; color: #999;">透明可审计</div>
</div>
<div style="text-align: center;">
<div style="font-size: 1.8rem; font-weight: 700; color: #000;">安全</div>
<div style="font-size: 0.8rem; color: #999;">数据不出境</div>
</div>
<div style="text-align: center;">
<div style="font-size: 1.8rem; font-weight: 700; color: #000;">实用</div>
<div style="font-size: 0.8rem; color: #999;">生产级部署</div>
</div>
</div>

</div>
</div>

---

<div style="display: flex; align-items: center; justify-content: center; height: 80%;">
<div style="text-align: center; max-width: 700px;">

<div style="font-size: 3rem; margin-bottom: 1.5rem;">🦞</div>

<div style="font-size: 1.8rem; font-weight: 300; color: #333; line-height: 1.6;">
接下来<br/>
让我们实际看看它能做什么
</div>

<div style="margin-top: 2rem; padding: 1rem 2rem; background: #111; border-radius: 10px; display: inline-block;">
<span style="font-size: 1.2rem; color: #fff; font-weight: 600;">Clash of Claws · 虾路相逢</span>
</div>

<div style="margin-top: 2rem; font-size: 0.85rem; color: #999;">
Speaker · Solutions Architect · AWS<br/>
Thank you 🙏
</div>

</div>
</div>
