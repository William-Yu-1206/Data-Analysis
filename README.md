# 資料分析專案實作
+ 資料集取自kaggle


# 無監督機器學習
## 購物車分析：fp-growth [連結](fp-growth.ipynb)
+ 為提升銷售成效，我們將對歷史訂單資料進行購物車分析 (Market Basket Analysis)。此舉目的在於洞察顧客最常一併購買的商品組合，這些洞察將直接應用於三大方面：優化實體或線上的貨架陳列、設計更具吸引力的組合式銷售 (Bundle)，以及為個人化推薦系統提供數據驅動的決策依據。
+ 採用 mlxtend 套件中的 FP-Growth 演算法與關聯規則 (Association Rules)，旨在探勘出具有高度支持度 (Support) 與信賴度 (Confidence) 的商品項目集 (Itemsets)。分析結果將用於制定商品貨架、綑綁銷售及推薦系統的優化策略。

## 集群分析：Kmeans [連結](cluster.ipynb)
+ 本分析旨在透過顧客消費數據及行銷活動參與記錄，對會員進行市場區隔。採用 K-Means 演算法，並利用輪廓係數 (Silhouette Score) 評估分群品質，以挖掘具高潛力的顧客群體，作為未來精準行銷策略的依據