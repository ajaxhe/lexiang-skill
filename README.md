# Lexiang Skill

腾讯乐享知识库 API 技能包，适用于各类 AI Agent（Clawdbot、Claude、Cursor、Codebuddy 等）。

## 功能

- 📚 知识库管理（创建、查询、更新、删除）
- 👥 团队与成员管理
- 📝 在线文档编辑（块接口）
- 🔍 AI 搜索与问答
- 📤 文件上传与下载
- 📋 任务管理

## 使用方式

### 方式一：Clawdbot 安装

```bash
clawdbot skills install github:ajaxhe/lexiang-skill
```

### 方式二：其他 Agent

将 `SKILL.md` 文件内容作为 System Prompt 或 Context 提供给你的 AI Agent 即可。

## 配置凭证

### 环境变量方式

```bash
export LEXIANG_APP_KEY="your_app_key"
export LEXIANG_APP_SECRET="your_app_secret"
export LEXIANG_STAFF_ID="your_staff_id"
```

### 配置文件方式

```json
{
  "LEXIANG_APP_KEY": "your_app_key",
  "LEXIANG_APP_SECRET": "your_app_secret",
  "LEXIANG_STAFF_ID": "your_staff_id"
}
```

## 获取凭证

1. 登录乐享企业管理后台
2. 进入【开发】→【接口凭证管理】
3. 点击**添加凭证**，保存 AppKey 和 AppSecret

## 文档

详细 API 文档请参考 [SKILL.md](./SKILL.md)

## License

MIT
