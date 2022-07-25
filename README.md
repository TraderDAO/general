# general

TraderDAO general collections

## 分支管理

1. 在 dev 開發, release 分支為 master
2. 根據 issue 開發, 解 issue 進版 `v0.0.1 -> v0.0.2`
3. 文檔寫 wiki , 先全中文
4. commit message 依照規範: 
    - `Updated blah blah` 沒有對應的 issue, 通常是小修小改
    - `Related #xxx` 未完成但是有關於特定 issue 
    - `Resolved #xxx` 完成, 等待驗收測試的 issue 
    - `Closed #xxx` 經過驗收測試後關閉的 issue 
    - `Fixed #xxx` 驗收測試後出現的bug, reopen issue, 並以 `hotfix-<issue number>` 分支進行
