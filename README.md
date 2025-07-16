# 資料分析專案實作
+ 資料集取自kaggle

## fp-growth.ipynb
+ 為提升銷售成效，我們將對歷史訂單資料進行購物車分析 (Market Basket Analysis)。此舉目的在於洞察顧客最常一併購買的商品組合，這些洞察將直接應用於三大方面：優化實體或線上的貨架陳列、設計更具吸引力的組合式銷售 (Bundle)，以及為個人化推薦系統提供數據驅動的決策依據。
+ 採用 mlxtend 套件中的 FP-Growth 演算法與關聯規則 (Association Rules)，旨在探勘出具有高度支持度 (Support) 與信賴度 (Confidence) 的商品項目集 (Itemsets)。分析結果將用於制定商品貨架、綑綁銷售及推薦系統的優化策略。
