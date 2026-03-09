# openclaw-xiaohongshu-publish-skill

OpenClaw Skill: 使用浏览器发布小红书笔记（图文/视频）

## 使用前提

1. 创建账号信息 `~/xiaohongshu-account.md`
2. 创建素材信息 `~/xiaohongshu-resource.md`
3. 首次用 OpenClaw 浏览器登录小红书一次

## 首次登录

```bash
openclaw browser --browser-profile openclaw open https://www.xiaohongshu.com/
```

## 文件模板

### ~/xiaohongshu-account.md

```markdown
# 小红书账号信息

## 账号定位
[如：美妆博主]

## 目标受众
[如：年轻女性]

## 内容风格
[如：温柔亲切]

## 产品/服务（可选）
[描述]

## 其他要求
- 禁止出现的词汇：xxx
- 必须包含的关键词：xxx
```

### ~/xiaohongshu-resource.md

```markdown
# 小红书素材

## 素材1
- 类型：图文 / 视频
- 路径：~/images/xxx.jpg
- 描述：xxx

## 素材2
- 类型：图文 / 视频
- 路径：~/videos/xxx.mp4
- 描述：xxx
```

## 使用方式

告诉 AI："帮我发布小红书"，AI 会读取素材列表，让你选择要发布哪条，确认后自动发布。

## 自动生成文件

- `~/xiaohongshu-history.md` - 发布历史
