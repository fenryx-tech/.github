# Fenryx GitHub 素材資料夾結構規劃

## 概述

本文檔定義 `fenryx-tech/.github` 倉庫中素材的資料夾結構，確保素材有組織、易於管理和擴展。

## 建議的資料夾結構

```
.github/
└── profile/
    └── assets/
        ├── README.md                    # 素材說明文件
        ├── logo/                        # Logo 相關素材
        │   ├── logo-32.png
        │   ├── logo-64.png
        │   ├── logo-128.png
        │   ├── logo-256.png
        │   ├── logo-512.png
        │   └── logo-horizontal.png
        ├── banner/                      # Banner 相關素材
        │   ├── github-banner.png       # GitHub 組織頁面 Banner
        │   ├── linkedin-banner.png     # LinkedIn Banner
        │   └── twitter-header.png      # Twitter Header
        ├── social/                      # 社群媒體素材
        │   ├── linkedin/               # LinkedIn 專用素材
        │   │   └── welcome-post.png
        │   └── instagram/               # Instagram 專用素材（如需要）
        └── blog/                        # 部落格文章素材
            └── (未來可擴展)
```

## 資料夾說明

### `/logo/` - Logo 素材

存放各種尺寸的 Logo PNG 檔案。

| 檔案名稱 | 尺寸 | 用途 | 狀態 |
|---------|------|------|------|
| `logo-32.png` | 32×32px | Favicon、最小尺寸 | ✅ 可用 |
| `logo-64.png` | 64×64px | 小尺寸顯示、Icon | ✅ 可用 |
| `logo-128.png` | 128×128px | 文章標題、中等尺寸顯示 | ✅ 可用 |
| `logo-256.png` | 256×256px | 大尺寸顯示、簡報 | ✅ 可用 |
| `logo-512.png` | 512×512px | 高解析度顯示 | ✅ 可用 |
| `logotype.png` | 1200×240px | 橫向 Logo、Banner | ✅ 可用 |

**引用路徑範例：**
```
https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-128.png
```

### `/banner/` - Banner 素材

存放各種平台的 Banner 圖片。

| 檔案名稱 | 尺寸 | 用途 | 平台 |
|---------|------|------|------|
| `github-banner.png` | 1280×320px | GitHub 組織頁面 | GitHub |
| `linkedin-banner.png` | 1584×396px | LinkedIn 公司頁面 | LinkedIn |
| `twitter-header.png` | 1500×500px | Twitter 個人/公司頁面 | Twitter |

**引用路徑範例：**
```
https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/banner/github-banner.png
```

### `/social/` - 社群媒體素材

存放社群媒體平台專用的素材。

#### `/social/linkedin/`
- `welcome-post.png` - LinkedIn 歡迎貼文圖片

#### `/social/instagram/`
- （未來可擴展）

**引用路徑範例：**
```
https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/social/linkedin/welcome-post.png
```

### `/blog/` - 部落格素材

存放部落格文章專用的圖片素材（未來擴展）。

## 檔案命名規範

### 命名原則

1. **小寫字母**：所有檔案名稱使用小寫字母
2. **連字號分隔**：使用連字號 `-` 而非底線 `_`
3. **描述性名稱**：檔案名稱應清楚描述內容
4. **尺寸標示**：Logo 檔案應包含尺寸資訊（如 `logo-128.png`）

### 命名範例

✅ **正確：**
- `logo-128.png`
- `github-banner.png`
- `linkedin-welcome-post.png`

❌ **錯誤：**
- `Logo_128.PNG`（大寫、底線、大寫副檔名）
- `githubBanner.png`（駝峰式命名）
- `logo.png`（缺少尺寸資訊）

## 素材分類原則

素材按照以下原則進行分類，方便查找和使用：

### 按用途分類

- **Logo**：品牌識別相關
- **Banner**：頁面頂部橫幅
- **Social**：社群媒體平台專用
- **Blog**：部落格文章專用

### 按平台分類

- **GitHub**：GitHub 相關素材
- **LinkedIn**：LinkedIn 相關素材
- **Twitter**：Twitter 相關素材
- **通用**：多平台共用素材

## 引用路徑格式

### 基礎路徑

```
https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/
```

### 完整路徑格式

```
https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/[分類]/[檔案名稱]
```

### 範例

```markdown
<!-- Logo -->
<img src="https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-128.png" alt="Fenryx Logo" width="64" height="64">

<!-- Banner -->
<img src="https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/banner/github-banner.png" alt="Fenryx Banner" width="100%">
```

## 擴展性考量

### 未來可能新增的分類

- `/icons/` - 圖示素材
- `/illustrations/` - 插圖素材
- `/templates/` - 模板檔案
- `/screenshots/` - 產品截圖

### 版本控制

如需要版本控制，可以使用以下結構：

```
assets/
├── v1/
│   └── logo/
└── v2/
    └── logo/
```

或使用檔案命名：

```
logo-v1-128.png
logo-v2-128.png
```

## 維護建議

1. **定期審查**：每季度審查素材使用情況
2. **清理未使用**：移除不再使用的素材
3. **優化檔案大小**：壓縮圖片以減少載入時間
4. **更新文件**：保持文件與實際結構同步

## 相關文件

- [素材使用規範](./ASSETS_USAGE_GUIDE.md) - 如何使用這些素材
- [品牌指南](../BRAND_GUIDELINES.md) - 品牌設計規範
- [GitHub 組織頁面設定](./ORGANIZATION_PROFILE_README.md) - GitHub 設定說明

---

**維護者：** Fenryx 技術團隊  
**最後更新：** 2025-11-26  
**版本：** 1.0
