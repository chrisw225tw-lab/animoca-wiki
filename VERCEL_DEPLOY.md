# Vercel 部署說明

## 認證資訊
- Token 位置：`~/.openclaw/.env` (VERCEL_TOKEN)
- 專案名稱：animoca-wiki
- 組織：chris-wongs-projects-d77df329

## 部署指令
```bash
cd /home/chris/.openclaw/workspace-work/animoca-wiki
source ~/.openclaw/.env
vercel deploy --token $VERCEL_TOKEN --prod
```

## 網站網址
- 生產環境：https://animoca-wiki.vercel.app
- 預覽環境：https://animoca-wiki-*.vercel.app

## 技術堆疊
- MkDocs + Material 主題
- 自動安裝 plugins: awesome-pages, redirects, minify

## 更新紀錄
- 2026-02-10: 首次部署成功
