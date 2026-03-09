# openclaw-xiaohongshu-publish-skill

OpenClaw Skill: 使用浏览器发布小红书笔记（图文/视频）

## 使用前提

1. 创建账号信息文件 `~/xiaohongshu-account.md`（见下方模板）
2. 用 OpenClaw 浏览器打开小红书，手动登录一次

## 首次登录

打开 OpenClaw 浏览器并登录小红书：

```
browser action=open profile=openclaw targetUrl=https://www.xiaohongshu.com/
```

登录后关闭浏览器即可，之后发布时无需再次登录。

## 账号信息模板

创建 `~/xiaohongshu-account.md`：

```markdown
# 小红书账号信息

## 账号定位
[如：美妆博主]

## 目标受众
[如：年轻女性]

## 内容风格
[如：温柔亲切]

## 产品/服务（可选）
[要推广的产品或服务描述]

## 其他要求
- 禁止出现的词汇：xxx
- 必须包含的关键词：xxx
```

## 使用方式

告诉 AI："帮我发布小红书"，然后按提示提供：
- 图文还是视频？
- 素材文件路径
- 素材描述

AI 会自动生成文案，确认后帮你发布。

## 文件说明

- `~/xiaohongshu-account.md` - 账号信息（用户创建）
- `~/xiaohongshu-history.md` - 发布历史（自动生成）
