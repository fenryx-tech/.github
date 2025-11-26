# Fenryx 公司素材使用規範

## 概述

本文檔說明如何在 GitHub 相關內容中使用 Fenryx 的品牌素材，包括 Logo、Banner 等可公開使用的圖片資源。

## 素材存放位置

所有可公開使用的素材存放在 `fenryx-tech/.github` 倉庫中：

**倉庫路徑：** https://github.com/fenryx-tech/.github  
**素材目錄：** `profile/assets/`  
**引用基礎路徑：** `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/`

### 資料夾結構

素材按照用途分類存放，詳細結構請參考：[素材資料夾結構規劃](./ASSETS_STRUCTURE.md)

```
profile/assets/
├── logo/          # Logo 相關素材
├── banner/        # Banner 相關素材
├── social/        # 社群媒體素材
└── blog/          # 部落格素材（未來擴展）
```

## 可用素材清單

### Logo

| 檔案名稱 | 尺寸 | 用途 | 引用路徑 |
|---------|------|------|---------|
| `logo/logo-32.png` | 32×32px | Favicon、最小尺寸 | `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-32.png` |
| `logo/logo-64.png` | 64×64px | 小尺寸顯示、Icon | `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-64.png` |
| `logo/logo-128.png` | 128×128px | 文章標題、中等尺寸顯示 | `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-128.png` |
| `logo/logo-256.png` | 256×256px | 大尺寸顯示、簡報 | `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-256.png` |
| `logo/logo-512.png` | 512×512px | 高解析度顯示 | `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-512.png` |
| `logo/logotype.png` | 1200×240px | 橫向 Logo、Banner | `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logotype.png` |

### Banner

| 檔案名稱 | 尺寸 | 用途 | 引用路徑 |
|---------|------|------|---------|
| `banner/github-banner.png` | 1280×320px | GitHub 組織頁面 Banner | `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/banner/github-banner.png` |
| `banner/linkedin-banner.png` | 1584×396px | LinkedIn 公司頁面 Banner | `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/banner/linkedin-banner.png` |
| `banner/twitter-header.png` | 1500×500px | Twitter 個人/公司頁面 Header | `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/banner/twitter-header.png` |

## 使用方式

### Markdown 文件中的使用

#### Logo 圖片

```markdown
<div align="center">

<img src="https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-128.png" alt="Fenryx Logo" width="64" height="64">

# 文章標題

</div>
```

#### Banner 圖片

```markdown
<img src="https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/banner/github-banner.png" alt="Fenryx Banner" width="100%"/>
```

### GitHub Issue 中的使用

GitHub Issue 支援 Markdown 和 HTML，可以直接使用上述引用方式。

**注意事項：**
- GitHub Issue 不支援 SVG，請使用 PNG 格式
- 圖片路徑必須使用完整的 `raw.githubusercontent.com` URL
- 確保 `.github` 倉庫為 **public** 才能讓外部存取

### GitHub README 中的使用

在組織或專案的 README 中使用：

```markdown
<div align="center">

<img src="https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-128.png" alt="Fenryx Logo" width="64" height="64">

**Fenryx 銳狼科技**

</div>
```

## 使用規範

### 尺寸建議

- **文章標題 Logo：** 64×64px 或 128×128px
- **頁面 Banner：** 使用 `width="100%"` 讓圖片自動適應寬度
- **小圖示：** 32×32px 或 64×64px
- **Favicon：** 32×32px

### 顏色規範

所有素材使用 Fenryx 品牌色彩：

- **主色：** Fenryx Crimson `#D72638`
- **背景：** Graphite Black `#121212`
- **次要背景：** Carbon Grey `#2A2A2A`

詳細色彩規範請參考：[品牌指南](../BRAND_GUIDELINES.md)

### 使用限制

1. **禁止修改：** 不得修改 Logo 的顏色、比例或設計
2. **最小尺寸：** Logo 不得小於 32×32px
3. **背景使用：** 
   - 深色背景：使用紅色 Logo
   - 淺色背景：使用黑色 Logo
   - 紅色背景：使用白色 Logo
4. **安全空間：** Logo 周圍保留至少 1x Logo 高度的空白區域


## 驗證素材可用性

可以透過以下方式驗證素材是否可正常存取：

1. **直接訪問 URL：**
   ```
   https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/[分類]/[filename].png
   ```
   
   範例：
   - Logo: `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-128.png`
   - Banner: `https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/banner/github-banner.png`

2. **在 GitHub Issue 或 README 中測試：**
   - 使用 Markdown 引用圖片
   - 確認圖片正常顯示

## 常見問題

### Q: 圖片無法顯示怎麼辦？

**A:** 檢查以下項目：
1. 檔案路徑是否正確（大小寫敏感）
2. URL 是否完整（包含正確的分類資料夾路徑）
3. 網路連線是否正常
4. 如果問題持續，請聯繫我們：contact@fenryx.tech

### Q: 可以使用 SVG 格式嗎？

**A:** GitHub Issue 和部分 Markdown 渲染器不支援 SVG，建議使用 PNG 格式以確保相容性。

### Q: 如何取得其他尺寸的 Logo？

**A:** 目前提供多種尺寸（32px、64px、128px、256px、512px），請選擇最接近需求的尺寸。如需其他尺寸，請聯繫我們：contact@fenryx.tech

### Q: 可以在外部網站使用這些素材嗎？

**A:** 可以，但請遵守品牌使用規範，不得修改 Logo 設計或顏色。

## 相關文件

- [素材資料夾結構規劃](./ASSETS_STRUCTURE.md) - 詳細的資料夾結構說明
- [品牌指南](../BRAND_GUIDELINES.md) - 完整的品牌使用規範
- [GitHub 組織頁面設定](./ORGANIZATION_PROFILE_README.md) - GitHub 組織頁面配置
- [簡報模板](../assets/presentation/README.md) - 簡報素材使用說明

---

**維護者：** Fenryx 技術團隊  
**最後更新：** 2025-11-26  
**聯絡方式：** contact@fenryx.tech
