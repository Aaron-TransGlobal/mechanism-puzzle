# Changelog

版號採 [Semantic Versioning](https://semver.org/lang/zh-TW/)：`vX.Y.Z`＝重大改版・新功能・修補。

## [0.1.2] - 2026-09-29

### Fixed
- 抽屜打開後點鑰匙沒有反應：移除抽屜的點擊時，連帶把放在抽屜裡的鑰匙也移除了
- 點暗格齒輪的正中央拿不到：點擊射線會穿過齒輪的軸孔

### Changed
- 抽屜彈出後，鏡頭自動移到看得進抽屜的高角度；點抽屜任何位置都能取出鑰匙
- 鑰匙、曲柄、齒輪加上較大的隱形點擊範圍，手機上比較好點中

## [0.1.1] - 2026-09-29

### Changed
- Repo 移到 GitHub `Aaron-TransGlobal/mechanism-puzzle`（個人帳號，不在 org 裡）
- 部署改用 Vercel 的 GitHub 整合：推到 `main` 自動部署正式環境，其他分支產生預覽網址

## [0.1.0] - 2026-09-28

### Added
- v0 原型「五重機關盒」（`prototype/v0-five-locks.html`）：單檔 Three.js，五道機關（寄木滑板、連環轉盤、齒輪齒條、密碼滾筒、鑰匙鎖）、道具欄、分層提示、程序合成音效
- 規劃書 v0.1（`docs/planning.md`）：解謎公式解構、關卡依賴圖與描述格式、元件庫分層與契約、可擴充性、可變化性、題材評估框架、開發路線
- 部署設定：個人 Vercel 靜態站，根路徑導向原型
