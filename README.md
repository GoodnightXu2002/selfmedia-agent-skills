# ZCode Skills 合集

个人自建的 ZCode / Agent skill 合集,沉淀自媒体账号运营与思维工具的工作流。

## 包含的 Skill

| Skill | 用途 | 触发场景示例 |
|---|---|---|
| [account-doctor](account-doctor/) | 账号诊断医生:用真实数据给抖音/小红书账号做体检、软限流自检、三层归因 | "为什么没流量""是不是被限流""帮我看看号" |
| [ai-director](ai-director/) | AI 编导师傅:融合四位在营创作者方法论,诊断/改写/评分短视频内容 | "这条文案行不行""帮我改标题""怎么选题" |
| [benchmark-radar](benchmark-radar/) | 对标雷达:搜索、筛选和蒸馏对标账号,沉淀低粉高赞样本库(含实测抖音抓取配方) | "找对标""拆解同行""这个赛道谁做得好" |
| [content-planner](content-planner/) | 选题规划器:把账号定位翻译成可执行的系列结构与选题库 | "帮我出20个选题""设计3个系列""内容排期" |
| [wisdom-distiller](wisdom-distiller/) | 智慧蒸馏器:把历史人物蒸馏成可复用的思维模型卡,用古人框架分析现代问题 | "王阳明会怎么处理我的困境" |

> 相关仓库:对话式账号定位分析 skill 单独发布在 [account-niche-finder](https://github.com/GoodnightXu2002/account-niche-finder)。

## 安装

把对应文件夹复制到你的 agent skills 目录即可:

```bash
git clone https://github.com/GoodnightXu2002/skills.git
# ZCode / 通用 agents 目录
cp -r skills/account-doctor ~/.agents/skills/
# 或 ZCode 个人目录
cp -r skills/account-doctor ~/.zcode/skills/
```

5 个 skill 为成套设计(定位 → 对标 → 编导 → 选题 → 诊断),互相之间有协作引用,建议整包安装。
