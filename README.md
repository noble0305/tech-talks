# Tech Talks

技术分享合集。每个主题一个目录，包含网页 PPT 和配套分享稿。

## 目录

| 主题 | 时长 | 简介 |
|------|------|------|
| [Playwright Test Agents](./playwright-test-agents/) | ~20min | 三个 AI Agent 全自动写测试——Planner 探索规划、Generator 生成代码、Healer 自动修复 |

## 目录结构规范

```
tech-talks/
├── README.md                  # 本文件，总索引
├── .gitignore
├── playwright-test-agents/    # 单个分享
│   ├── README.md              # 该主题说明 + 参考资料
│   ├── index.html             # 网页 PPT
│   └── share-script.md        # 配套分享稿
├── another-topic/             # 后续分享
│   ├── README.md
│   ├── index.html
│   └── share-script.md
└── ...
```

## 约定

- 每个分享一个独立目录，目录名用英文短横线连接（如 `playwright-test-agents`）
- 每个目录至少包含 `index.html`（PPT）和 `share-script.md`（分享稿）
- PPT 使用统一的网页模板（全屏翻页、键盘导航、入场动画）
- 分享稿标注预计时长，按页面分段，方便对照

## License

MIT
