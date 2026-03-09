# openclaw-xiaohongshu-publish-skill

OpenClaw Skill: 使用浏览器发布小红书笔记

## 目录结构

每个账号一个文件夹 `~/xiaohongshu-<账号名>/`：

```
~/xiaohongshu-meizhuang/
├── account.md      # 账号信息
├── resource.md     # 素材列表
├── resources/      # 素材文件
│   ├── img1.jpg
│   └── video1.mp4
└── history.md      # 发布历史（自动生成）
```

## 文件模板

### account.md

```markdown
# 账号信息

## 账号定位
[如：美妆博主]

## 目标受众
[如：年轻女性]

## 内容风格
[如：温柔亲切]

## 产品/服务
[描述]

## 其他要求
- 禁止：xxx
- 必须：xxx
```

### resource.md

```markdown
# 素材列表

## 素材1
- 类型：图文 / 视频
- 文件：img1.jpg
- 描述：xxx

## 素材2
- 类型：视频
- 文件：video1.mp4
- 描述：xxx
```

## 首次登录

```bash
openclaw browser --browser-profile openclaw open https://www.xiaohongshu.com/
```

## 使用

告诉 AI："发布小红书"，选择账号和素材，确认文案后自动发布。
