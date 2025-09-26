# RMS(Rental-Management-System)

手機租借管理系統 - 實務應用開發  
目前已經有架設Line bot在處理手機租借的服務  
但剛好需要做一個Side Project來檢視自己會的技能  
以及學習更多技能(Docker、部屬、單元測試)  
所以就順勢做了一個可以實現商業行為的系統，而不是單純的技能練習  

### 🎯 專案目標

- 展示完整的 CRUD 能力與實務架構設計
- 實作 Vue + [ASP.NET](http://asp.net/) Core 的全端架構
- 包含部署、自動化、驗證、權限、資料管理等能力

### 🔧 技術選擇目錄

| 領域 | 技術 |
| --- | --- |
| 前端 | Vue 3 + Pinia + Vue Router + Tailwind CSS |
| 後端 | [ASP.NET](http://asp.net/) Core Web API + Entity Framework |
| 資料庫 | SQL Server（或 SQLite for Local 測試） |
| 驗證 | JWT or Cookie-based Auth |
| 部署 | Docker + Azure / Render |
| DevOps | GitHub Actions（CI/CD） |
| 配置管理 | `appsettings.json` + `appsettings.Development.json`（多環境設定） |

---

## 📂 專案目錄初步規劃（階段 1）

```bash
📦 rental-management-system/
├── backend/                  # ASP.NET Core 專案
│   ├── Controllers/
│   ├── Models/
│   ├── Services/
│   ├── Data/                # EF 資料上下文與遷移
│   ├── DTOs/
│   └── Program.cs / Startup.cs
├── frontend/                 # Vue 3 + Pinia 專案
│   ├── src/
│   │   ├── views/
│   │   ├── components/
│   │   ├── store/
│   │   └── router/
├── docker/
│   ├── nginx/
│   └── docker-compose.yml
├── docs/                     # 文件與筆記
│   ├── README.md
│   └── api-spec.md

```
