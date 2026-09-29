# My Kitchen

一个 Mobile First 的个人菜谱、酒单、菜单计划与每日记录 Web App。

## 本地预览

```bash
python -m http.server 4173 --directory dist
```

## Vercel

项目根目录包含 `vercel.json`，导入 GitHub 仓库后可直接部署，无需构建命令。

## 数据

- 结构化数据保存在 `localStorage`。
- 用户照片保存在 IndexedDB。
- “我的 → 设置 / 数据管理 → 导出全部数据”会把结构化数据和照片一起导出为 JSON。
