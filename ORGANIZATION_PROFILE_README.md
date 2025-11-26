# GitHub 組織 Profile README

此文件是給 GitHub 組織頁面使用的 README。

## 如何使用

1. 在 GitHub 上創建一個名為 `.github` 的 repository（需要是 public）
2. 在該 repository 中創建 `profile/README.md`
3. 將下方內容複製到 `profile/README.md`
4. GitHub 會自動在組織頁面 (https://github.com/fenryx-tech) 顯示此內容

---

## profile/README.md 完整內容

以下是建議的內容（請複製到 `.github` repository 的 `profile/README.md`）：

```markdown
<div align="center">

# FENRYX

**Software Engineering × Offensive Security**

專注於軟體工程與攻擊技術的科技工程品牌

[🌐 Website](https://fenryx.tech) • [📧 Contact](mailto:contact@fenryx.tech)

---

</div>

## 🎯 我們的服務

### 💻 軟體與系統開發
打造高品質的客製化系統，從概念到部署，提供完整的軟體工程解決方案。

- **Cloud-native Architecture** - 彈性擴展、高可用性
- **Microservices Design** - 模組化、易於維護
- **Full-Stack Development** - Frontend、Backend、Infrastructure
- **CI/CD Pipeline** - 自動化測試、建置、部署

### 🔒 滲透測試與攻擊工程
以駭客思維發現系統漏洞，在攻擊者之前找到並修補安全缺陷。

- **Black/White/Grey Box Testing** - 多種測試類型
- **OWASP Top 10 Coverage** - 涵蓋常見漏洞
- **Red Team Exercise** - 全方位攻擊模擬
- **Comprehensive Reporting** - 詳細報告與修復建議

### 🛡️ 系統強化（Hardening）
提升系統安全性，建立多層防禦機制，降低被攻擊風險。

- **Security Configuration** - 最佳安全設定
- **Access Control** - 嚴格權限管理
- **Network Segmentation** - 網路微分段設計
- **Monitoring & Alerting** - 即時監控與警示

### 🏗️ 架構與技術顧問
協助企業做出正確的技術決策，設計可擴展、安全、高效能的系統架構。

- **Architecture Review** - 架構審查與優化
- **Technology Selection** - 技術選型建議
- **Performance Optimization** - 效能調校
- **Cost Optimization** - 雲端成本優化

## 🔧 技術棧

**Frontend**: Next.js, Astro, React, TypeScript
**Backend**: Node.js, Python, Go
**Infrastructure**: Cloudflare, AWS, GCP, Docker, Kubernetes
**Security**: Burp Suite, Metasploit, OWASP ZAP, Custom Tools

## 📚 開源專案

我們致力於回饋開源社群，分享我們的工具與知識。

<!-- 未來可以在這裡列出開源專案 -->

## 🌟 為什麼選擇 Fenryx？

- ✅ **專業團隊** - 豐富的軟體工程與資安經驗
- ✅ **全方位服務** - 從開發到安全，一站式解決方案
- ✅ **品質保證** - 嚴格的程式碼審查與測試流程
- ✅ **持續支援** - 不只是交付，更提供長期維護與優化

## 📫 聯絡我們

- **Website**: [fenryx.tech](https://fenryx.tech)
- **Email**: [contact@fenryx.tech](mailto:contact@fenryx.tech)
- **GitHub**: [@fenryx-tech](https://github.com/fenryx-tech)

---

<div align="center">

**Building Secure & Scalable Systems**

</div>
```

---

## 設置步驟

### 步驟 1: 創建 `.github` Repository

```bash
# 在 GitHub 上手動創建，或使用 gh CLI
gh repo create fenryx-tech/.github --public --description "Fenryx organization profile"
```

### 步驟 2: 創建 Profile README

```bash
# Clone repository
git clone https://github.com/fenryx-tech/.github.git
cd .github

# 創建目錄結構
mkdir -p profile

# 創建 README
cat > profile/README.md << 'EOF'
[將上方的 markdown 內容貼上]
EOF

# Commit and push
git add profile/README.md
git commit -m "feat: add organization profile README"
git push
```

### 步驟 3: 驗證

訪問 https://github.com/fenryx-tech 查看組織頁面，應該會看到 README 內容。

## Banner 設計

已創建並上傳 GitHub banner 圖片：

- **檔案**: `profile/assets/github-banner.png`
- **尺寸**: 1280x320px
- **位置**: https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/github-banner.png
- **SVG 源文件**: `/docs/github/github-banner.svg`

### Banner 設計元素

- ✅ Fenryx Logo（左側，帶發光效果）
- ✅ 品牌名稱 FENRYX（大字體、粗體）
- ✅ Tagline: Software Engineering × Offensive Security
- ✅ 品牌色彩：Fenryx Crimson (#D72638)、Graphite Black (#121212)
- ✅ 微妙的網格背景與幾何裝飾元素
- ✅ fenryx.tech 網址（右下角）

### 使用方式

Banner 已經整合到 profile README 中：

```markdown
<img src="https://raw.githubusercontent.com/fenryx-tech/.github/main/profile/assets/github-banner.png" alt="Fenryx Banner" width="100%"/>
```

## 進階選項

### 添加統計資訊

可以使用 GitHub Stats 顯示組織活動：

```markdown
## 📊 組織統計

![GitHub Organization Stats](https://github-readme-stats.vercel.app/api?username=fenryx-tech&show_icons=true&theme=dark)
```

### 添加技能徽章

```markdown
## 🛠️ 技術棧

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
```

## 參考資源

- [GitHub Organization Profile README 官方文件](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)

## 注意事項

1. `.github` repository 必須是 **public** 才能顯示
2. README 路徑必須是 `profile/README.md`（精確匹配，大小寫敏感）
3. 圖片建議放在 `profile/assets/` 目錄
4. 可以使用 emoji、markdown、HTML 格式化內容
5. 更新後可能需要幾分鐘才會在組織頁面顯示
