# 41120A018 演算法練習紀錄

這個 repository 是演算法課程與 LeetCode 題目練習紀錄，內容依週次整理，包含程式碼、題目截圖與解題筆記。主要練習排序、鏈結串列、堆積、雙指標、陣列與樹等資料結構與演算法概念。

## 專案內容

```text
41120A018/
├── Alogorithm Wk1/   # 第 1 週：排序與鏈結串列
├── Alogorithm Wk2/   # 第 2 週：鏈結串列與 Heap
├── Alogorithm Wk3/   # 第 3 週：陣列、雙指標、區間平均
└── Alogorithm Wk4/   # 第 4 週：樹與 DFS 題目
```

## 練習題目

| 週次 | 題目 | 主題 |
| --- | --- | --- |
| Wk1 | LeetCode 912 - Sort an Array | 排序 |
| Wk1 | LeetCode 147 - Insertion Sort List | 鏈結串列、插入排序 |
| Wk2 | LeetCode 148 - Sort List | 鏈結串列、排序 |
| Wk2 | LeetCode 215 - Kth Largest Element in an Array | Heap、Priority Queue |
| Wk3 | LeetCode 167 - Two Sum II | 雙指標 |
| Wk3 | LeetCode 2090 - K Radius Subarray Averages | 陣列、前綴和 |
| Wk3 | LeetCode 512 | SQL / 資料查詢練習 |
| Wk4 | LeetCode 113 - Path Sum II | Binary Tree、DFS |
| Wk4 | LeetCode 1302 - Deepest Leaves Sum | Binary Tree、DFS / BFS |

## 使用技術

- C++
- STL
- vector
- priority_queue
- two pointers
- linked list
- binary tree

## 學習重點

- 練習將題目拆成資料結構與演算法步驟。
- 熟悉 C++ STL 容器與常用工具。
- 了解排序、Heap、雙指標、DFS 等常見解題技巧。
- 透過截圖與程式碼保存每週練習成果。

## 範例：Heap 解題概念

以 LeetCode 215 為例，可以使用大小為 `k` 的 min heap：

1. 依序把陣列元素放入 heap。
2. 當 heap 的大小超過 `k`，移除最小值。
3. 最後 heap 頂端就是第 `k` 大的元素。

這個做法可以避免完整排序全部資料，適合練習 priority queue 的使用。

## 如何閱讀

每個週次資料夾中包含：

- 題目截圖 `.png`
- 程式碼或筆記檔案
- 對應 LeetCode 題號

可以從 `Alogorithm Wk1` 開始，依週次查看練習進度。

## 後續可改進方向

- 統一程式碼副檔名，例如全部改為 `.cpp`。
- 在每題補上時間複雜度與空間複雜度。
- 補充解題思路與錯誤紀錄。
- 將題目依資料結構分類，方便複習。
