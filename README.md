# Stair Gallery Site (v3.1)

离线单文件图库 + 构建器，已打包好可直接推送到 GitHub 仓库并用 GitHub Pages 发布。

## 目录
- `index.html` — 图库（支持手机自适配、筛选、无限滚动、收藏导入导出、多语言、EXIF 排序）  
- `builder.html` — 离线构建器（拖拽图片、读取 EXIF、CSV 批量元数据、导出单文件、重命名脚本）  
- `seo.html` — SEO 索引页（带筛选 URL 参数入口）  
- `manifest.json`, `sw.js` — PWA 基础文件  
- `404.html` — 兜底路由（兼容带查询参数的访问）  
- `.nojekyll` — 禁止 Jekyll 处理

## 一键部署（GitHub Pages）
1. 新建仓库（或进入现有仓库）并切到默认分支（如 `main`）。
2. 把以上文件全部推送到仓库根目录。
3. 打开 **Settings → Pages**：
   - Source 选择 **Deploy from a branch**
   - Branch 选择 **main /root**，保存。
4. 访问：
   - 图库首页：`https://<用户名>.github.io/<仓库名>/`
   - 构建器：`https://<用户名>.github.io/<仓库名>/builder.html`
   - SEO 索引：`https://<用户名>.github.io/<仓库名>/seo.html`