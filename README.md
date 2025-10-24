# my-first-gomoku 🎮

github新手小白的第一个仓库，借助了Claude Code的帮助，想以此好好了解github怎么使用。

## 项目简介

这是一个强大的五子棋AI对战游戏，采用纯HTML+CSS+JavaScript开发，可以直接部署到GitHub Pages供在线体验！

## 功能特点

### 🤖 强大的AI算法
- **VCF (连续冲四)**: AI能够识别并执行连续冲四的必胜策略
- **VCT (连续威胁)**: AI能够通过连续威胁逐步建立优势
- **Minimax搜索**: 配合Alpha-Beta剪枝的经典博弈树搜索算法
- 多层次决策：优先检测必胜/必防 → VCF搜索 → VCT搜索 → Minimax评估

### ⏱️ 计时系统
- AI和玩家各有5秒思考时间限制
- 实时显示剩余时间，少于2秒时红色警告闪烁
- 玩家超时自动随机落子，保证游戏流畅进行
- AI超时自动选择当前最佳着法

### 🎯 游戏特性
- AI执白先手，自动在天元（棋盘中心）落子
- 玩家下第一个黑子时开始正式计时
- 支持悔棋功能（撤销最近两步）
- 精美的渐变UI设计，响应式布局
- 胜负判定和游戏结束动画

## 在线体验

### 部署到GitHub Pages

1. **启用GitHub Pages**
   - 进入仓库的 `Settings` → `Pages`
   - 在 `Source` 下选择分支（例如 `claude/gomoku-ai-implementation-011CUS9escYLc6khJqMxUWdg` 或 `main`）
   - 选择根目录 `/root`
   - 点击 `Save`

2. **访问游戏**
   - 等待几分钟让GitHub Pages构建完成
   - 访问 `https://sure-will.github.io/my-first-gomoku/`
   - 开始与AI对战！

### 本地体验

直接用浏览器打开 `index.html` 文件即可开始游戏！

## 游戏说明

- **AI (白子)**: 先手，默认在天元落子
- **玩家 (黑子)**: 后手，点击棋盘空位落子
- **胜利条件**: 横、竖、斜任意方向连成五子即获胜
- **时间限制**: 每步5秒，超时自动落子
- **悔棋**: 点击"悔棋"按钮可撤销最近两步（玩家+AI）

## 技术栈

- 纯HTML5 Canvas绘图
- CSS3动画和渐变效果
- 原生JavaScript实现AI算法
- 无需任何外部依赖库

## 开发者

由 Claude Code 辅助开发 🤖

---

**提示**: 这个AI很强哦，祝你好运！💪
