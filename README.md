# Lexiang Skill for Clawdbot

腾讯乐享知识库 API 技能包，用于 [Clawdbot](https://github.com/anthropics/clawdbot) AI Agent。

## 功能

- 📚 知识库管理（创建、查询、更新、删除）
- 👥 团队与成员管理
- 📝 在线文档编辑（块接口）
- 🔍 AI 搜索与问答
- 📤 文件上传与下载
- 📋 任务管理

## 安装

```bash
clawdbot skills install github:anthropics/lexiang-skill
```

## 配置

在 `~/.clawdbot/clawdbot.json` 中添加：

```json
{
  "skills": {
    "entries": {
      "lexiang": {
        "env": {
          "LEXIANG_APP_KEY": "your_app_key",
          "LEXIANG_APP_SECRET": "your_app_secret",
          "LEXIANG_STAFF_ID": "your_staff_id"
        }
      }
    }
  }
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
