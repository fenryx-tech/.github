# Fenryx GitHub 相關文件與素材

## 概述

本目錄包含所有與 GitHub 組織頁面、公開素材相關的文件和資源。

## 目錄結構

```
docs/github/
├── README.md                          # 本文件
├── ASSETS_STRUCTURE.md                # 素材資料夾結構規劃
├── ASSETS_USAGE_GUIDE.md              # 素材使用規範
├── ORGANIZATION_PROFILE_README.md     # GitHub 組織頁面設定指南
├── profile-README.md                  # Profile README 內容範本
├── github-banner.png                  # GitHub Banner 圖片
├── github-banner.svg                  # GitHub Banner SVG 源文件
└── profile/                           # .github 倉庫內容
    └── assets/                        # 公開素材庫
        ├── README.md                  # 素材庫說明
        ├── logo/                      # Logo 素材
        │   └── logo-128.png
        ├── banner/                    # Banner 素材
        └── social/                    # 社群媒體素材
            └── linkedin/
```

## 文件說明

### 設定與使用指南

- **[ASSETS_USAGE_GUIDE.md](./ASSETS_USAGE_GUIDE.md)**  
  說明如何在 GitHub 相關內容中使用品牌素材，包含引用路徑、使用範例等。

- **[ASSETS_STRUCTURE.md](./ASSETS_STRUCTURE.md)**  
  詳細說明素材資料夾的結構規劃、命名規範、分類原則等。

- **[ORGANIZATION_PROFILE_README.md](./ORGANIZATION_PROFILE_README.md)**  
  GitHub 組織頁面 Profile README 的設定指南。

### 內容範本

- **[profile-README.md](./profile-README.md)**  
  GitHub 組織頁面 Profile README 的內容範本，可直接複製使用。

### 素材資源

- **profile/assets/**  
  所有可在 GitHub 上公開使用的品牌素材，按照用途分類存放。

## 快速開始

### 1. 設定 GitHub 組織頁面

1. 在 GitHub 上創建 `.github` 倉庫（必須是 public）
2. 將 `profile-README.md` 的內容複製到 `.github/profile/README.md`
3. 將 `github-banner.png` 上傳到 `.github/profile/assets/banner/`

### 2. 使用品牌素材

1. 參考 [ASSETS_USAGE_GUIDE.md](./ASSETS_USAGE_GUIDE.md) 了解如何使用素材
2. 使用 GitHub raw URL 引用素材
3. 遵守品牌使用規範

## 素材引用範例

### Logo

```markdown
<img src="https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/logo/logo-128.png" alt="Fenryx Logo" width="64" height="64">
```

### Banner

```markdown
<img src="https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/banner/github-banner.png" alt="Fenryx Banner" width="100%">
```

## 相關文件

- [品牌指南](../BRAND_GUIDELINES.md) - 完整的品牌設計規範
- [簡報模板](../assets/presentation/README.md) - 簡報素材使用說明
- [社群媒體素材](../assets/social/) - Instagram、LinkedIn 等平台素材

## 注意事項

1. **公開性**：`.github` 倉庫必須是 **public** 才能讓外部存取素材
2. **檔案命名**：遵循命名規範（小寫、連字號分隔）
3. **使用規範**：請遵守品牌使用規範，不得修改 Logo 設計或顏色

---

**維護者：** Fenryx 技術團隊  
**最後更新：** 2025-11-26
