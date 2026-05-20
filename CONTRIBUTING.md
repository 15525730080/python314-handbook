# 贡献指南 / Contributing Guidelines

感谢你对这个项目的关注和贡献！

Thank you for your interest in contributing to this project!

## 如何贡献 / How to Contribute

### 1. 报告问题 / Report Issues

如果你发现了 bug 或者有改进建议，请提交 Issue：

- 清晰描述问题或建议
- 提供相关的截图或代码示例
- 说明你的环境信息（浏览器、操作系统等）

### 2. 提交代码 / Submit Code

#### 准备工作 / Preparation

```bash
# Fork 项目
# Clone 你的 fork
git clone https://github.com/YOUR_USERNAME/python314-handbook.git
cd python314-handbook

# 创建新分支
git checkout -b feature/your-feature-name
```

#### 开发工作流 / Development Workflow

1. **编辑内容**
   - 编辑 `index.html` 或相关文件
   - 确保符合项目风格

2. **本地测试**
   ```bash
   # 启动本地服务器
   python -m http.server 8000
   # 访问 http://localhost:8000
   ```

3. **提交更改**
   ```bash
   git add .
   git commit -m "feat: 添加新内容" # 使用有意义的提交信息
   git push origin feature/your-feature-name
   ```

4. **提交 Pull Request**
   - 在 GitHub 创建 PR
   - 清晰描述你的改动
   - 关联相关的 Issue（如果有）

### 3. 改进文档 / Improve Documentation

- 修正错别字或语法错误
- 补充缺失的代码示例
- 改进代码注释
- 翻译内容为其他语言

## 代码风格 / Code Style

### HTML/CSS/JavaScript

- 使用 2 空格缩进
- 保持代码简洁易读
- 添加必要的注释

### 提交信息 / Commit Messages

```
type(scope): subject

body

footer
```

类型（type）：
- `feat`: 新功能
- `fix`: 修复 bug
- `docs`: 文档更改
- `style`: 代码格式（不影响功能）
- `refactor`: 代码重构
- `perf`: 性能优化
- `test`: 添加测试
- `chore`: 其他改动

示例：
```
feat(content): 添加第一章语言基础内容
docs: 更新 README
fix: 修复搜索功能 bug
```

## 开发指南 / Development Guide

### 项目结构

```
python314-handbook/
├── index.html           # 主页面
├── _config.yml         # Jekyll 配置
├── README.md           # 项目说明
├── CONTRIBUTING.md     # 本文件
├── Gemfile            # Ruby 依赖
├── .github/
│   └── workflows/     # GitHub Actions
└── docs/              # 其他文档
```

### 构建过程

项目使用 Jekyll 生成静态网站，通过 GitHub Actions 自动部署到 GitHub Pages。

## 行为准则 / Code of Conduct

- 尊重他人
- 不传播歧视性或辱骂性内容
- 建设性的批评
- 关注项目目标

## 联系方式 / Contact

有任何问题？请：
- 提交 Issue
- 发送邮件到 contact@python314.com
- 在 GitHub Discussions 中讨论

感谢你的贡献！🙏

---

**Last Updated**: 2026-05-20
