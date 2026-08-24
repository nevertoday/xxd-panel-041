<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 041 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 041

### 把一个有依据的主题隐喻建进清透等距研究图

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EA846F?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-6FAEB4?style=flat-square)](#)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> 主题隐喻 · 等距秩序 · 淡手稿 · 日系清透色 · 东方留白

统一等距模型保住源图身份，一个几何主题隐喻成为底座、缺口、路径、包围或负形；极淡研究草图只在清透成品周围留下从属的思考痕迹。

## 为什么需要这套 Skill

这套风格依赖每一张源图，不是可替换内容的装饰预设。它遵循这条重构链：

```text
锁定身份与结构轴线 → 保留三个决定性线索 → 在统一等距网格中重构 → 提炼一个有源图依据的隐喻 → 让隐喻决定底座、切面、路径、包围、承托或负形 → 使用源图衍生日系清透色与哑光色面 → 环绕极淡分析手稿 → 让文案对齐轴线与研究辅助线
```

如果换成无关照片后，辨识度、构造、位置、材质、颜色、留白与文案都不发生实质变化，结果就不属于这套 Panel。

## 视觉契约

- 从剪影、比例、轴线、开口、层级、方向、动作或关系中保留至少三个源图专属线索。
- 使用一套统一等距轴线重构有意义的体块、层级、切面与空间关系，不得只是把原物做成通用3D模型。
- 从真实内容、动作、结构或象征中提炼一个主题意象，让它因果性地控制底座、切面、缺口、路径、包围、承托、悬浮或负形。
- 使用源图衍生的高明度、清透、柔和日系色，浅暖基础、哑光表面和轻微可读阴影，不得塑料高光或厚重CG。
- 只加入极淡的源图相关轮廓草图、结构拆解、局部放大、比例线、箭头、几何推演、自然观察和微注释；它们只是从属思考痕迹。
- 允许有源图依据的偏置、悬浮、尺度反差、裁切与东方留白，但始终只保留一个视觉中心。

原始审美约束与拒绝项只存在于[原始提示词](references/041-source.md)；Skill 与运行适配器只处理本次交付变量。 [Skill 工作流](SKILL.md) · [英文运行适配器](references/xxd-panel-041-prompt.en.md)

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091001986519068891) · 2026 年 8 月 22 日<br>
> GPT2 × isometric × 达·芬奇 × 美学提示词<br>注：原推文正文中的 “VOL.401” 为编号笔误；作者已确认该样张归属 XXD Panel 041。

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 041 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 041 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 041 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 041 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091001986519068891">查看原推文与完整提示词 →</a></p>

这些样张用于展示 041 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 原始提示词优先，而不是二次导演

`references/041-source.md` 是本项目唯一的创作与审美权威。Skill 不再额外总结或扩写它，也不会统一规划颜色、色板、美学动机、标题或微文案。原始提示词要求怎样处理颜色、材料、构图、留白与文字，GPT Image 2 就按那套逻辑执行。

模式与尺寸会完整替换原始提示词旧有的 3:4 上下交付容器，但不改写它的转译美学。每张成品只向 GPT Image 2 发送一个已选模式的最终契约，不再把四种模式放进同一个通用模板让模型自行猜测。

## 四种可组合输出模式

模式可以单选或多选：`top-bottom`、`left-right`、`design-only`、`wallpaper-pack`；多选时，每个模式分别生成、分别拥有自己的提示词。

- `top-bottom`：整张画面由上方现实画面与下方设计转译两个主要部分组成。
- `left-right`：整张画面从顶部到底部保持完整左右结构，原图在左、设计在右；文字融入这两个区域，不再生成横跨全宽的第三块底栏。左右宽度可以不对称，由模型自主构图。
- `design-only`：原图只作为不可见的身份、结构、颜色与事实依据；整张成品的每个可见元素都必须属于该 Skill 自己的设计转译语言。
- `wallpaper-pack`：每台设备分别生成完整画布的设计转译壁纸，原图不作为照片区域出现。

上下或左右都不做分界线、中线百分比或像素坐标检测。只有用户明确要求像素级分区或原片逐像素不变时，才使用确定性拼合。

普通成品尺寸同样可以多选：自动适配、跟随原图、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5，或自定义比例／准确像素。没有静默默认尺寸；每个不同比例都会基于同一份原始提示词独立重构。

壁纸套装可选“连贯”或“四张独立”。连贯模式先生成一张定调图，其余设备同时参考原图与定调图重新构图；不会把一张图机械裁成四种尺寸。

## 文字方式

正式生图前只确认三种选择：

1. **模型根据原始提示词生成文字**：用户只指定语言或地区，文字内容、数量、气质与排版由 GPT Image 2 按原始提示词生成；所有文字都从当前图片的内容、气质或隐喻中自然生长，任何事实或资料式信息都必须有用户输入、图片可见内容或已核实信息作为依据。
2. **使用我的准确文字**：逐字传给图像模型，不改写、不翻译、不补标题；排版仍遵循原始提示词。
3. **不要文字**：严格禁止文字与伪文字。

外层 Skill 不再预编标题、微文案或文案包。文字语言与操作语言分开确认，不根据人物、场景或文件名猜测国家与受众。

## 完整画布优先与位图边界

图像模型负责整张成品的审美重构，双联也默认一次直出完整画布。`scripts/compose_panel.py` 只保留为条件明确的兜底、无创尺寸校准和只读审计工具，不再预先规划每次任务，也不评价审美是否成功。

全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务；已配置图像通道只返回脱敏状态，不公开供应商、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图不能替代最终作品。

## 能力自适应问询与快捷参数

同一个 Skill 会根据宿主真正提供的交互能力选择界面，不会把文本符号伪装成可点击控件：

- **Claude Code 提供 `AskUserQuestion + multiSelect: true` 时**：模式和尺寸使用真正的 checkbox；文字方式与壁纸关系使用单选。常用尺寸会按方形、竖版、横版分组展示，并累计多组选项；自定义尺寸进入自由输入。
- **Codex 只提供 `request_user_input` 时**：它只用于文字方式、壁纸关系等互斥单选，不拿来伪装模式或尺寸多选。模式与尺寸改用清楚的组合输入。
- **没有交互工具时**：使用两轮文字问询。第一轮选择一个或多个模式；第二轮填写尺寸与文字方式。Skill 不显示假的 `- [ ]`，也不会为了获得表单要求用户切换 Plan mode。

默认第二轮只展示“智能推荐／跟随原图／常用比例／自定义”四个入口；只有选择常用比例时，才展开完整比例库：方形 `1:1`，竖版 `3:4、4:5、2:3、9:16、5:7`，横版 `4:3、5:4、3:2、16:9、21:9、7:5`。所有比例都可组合，也可直接输入准确像素。

全部设置都可以直接作为参数传入：

```text
/xxd-panel-041 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

支持 `--mode`、可重复或逗号分隔的 `--size`、`--text prompt|exact|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size` 和 `--out`。参数齐全时跳过全部问询；参数不完整时只询问缺失项。

## 生图模型优先级

GPT Image 2 是默认首选，并继续执行本项目现有的高保真垫图、生成前确认整张画幅、双联一次生成完整画布、脚本仅作条件式兜底等逻辑。

当当前工具或已配置兼容通道确实可用，并能满足原图保真、整张成品比例、目标语言文字和连贯壁纸多图参考等要求时，也支持 Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）或其他兼容位图模型。备用模型只替换生成通道，不得改变模式、画幅、文案、语言、壁纸关系和完整画布优先策略。

如果没有合适的生图通道，Skill 会请用户启用生图工具或提供 API Key。用户主动提供的凭据可以用于当前任务，但不得在回复或日志中回显、展示或泄露；未经用户明确要求，不会长期保存凭据或修改供应商、账户、计费及全局路由配置。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-041.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-041" ~/.codex/skills/xxd-panel-041
```

Claude Code 用户可把同一文件夹链接到 `~/.claude/skills/xxd-panel-041`. 安装后请重启 Agent 会话。

```text
$xxd-panel-041
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

完整规格: [Skill 工作流](SKILL.md) · [原始风格档案](references/041-source.md) · [英文运行适配器](references/xxd-panel-041-prompt.en.md) · [中文运行适配器](references/xxd-panel-041-prompt.zh-CN.md)

## 关于 XXD

XXD 是小小东品牌名的缩写，本项目由小小东创建并维护： [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 支持与会员

### 深度咨询 · 299 元／小时

一对一深入咨询 Skills 的使用与工作流，通过微信联系小小东预约。 [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### 小小东 Skills 用户交流群 · 99 元

一次付费加入 Skills 用户交流群，用于工作流分享和用户间讨论；不包含按小时计费的一对一咨询。

### 知识星球＋成员提示词库 · 699 元／年

知识星球和成员提示词库是一份会员费用：从任一入口开通后，通过微信联系小小东获取另一边的权益。

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>理性成品与思考痕迹，共处一片安静空间。</strong></div>

---

<div align="center">

## ☕ 支持这个开源项目

算力赞助请使用小小东自己的微信或支付宝赞赏码；赞助完全自愿，不改变开源项目的访问权限。


<table><tr>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="XXD WeChat reward" width="180"></a><br><strong>WeChat</strong></td>
<td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="XXD Alipay reward" width="180"></a><br><strong>Alipay</strong></td>
</tr></table>

</div>
</div>
