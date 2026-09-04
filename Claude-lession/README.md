# Claude-lession

Bài giảng AI/ML tiếng Việt cho người mới, mỗi bài là **một file HTML tương tác độc lập** (mở thẳng bằng trình duyệt, không cần cài gì).

Quy ước đặt tên: `YYYY-MM-DD-<chu-de>-<ma-ngau-nhien>.html` — mã ngẫu nhiên 8 ký tự hex để các bài không đè lên nhau.

## Danh sách bài

| Ngày | Bài | Chủ đề | Mã |
|---|---|---|---|
| 2026-09-03 | [Linear Regression: Tìm Đường Thẳng Khớp Nhất](./2026-09-03-linear-regression-2f2c44d6.html) | Supervised Learning — Ordinary Least Squares, Normal Equation vs Gradient Descent, learning rate quá lớn (phân kỳ), dừng huấn luyện quá sớm (chưa hội tụ), MSE, R², ảnh hưởng của outlier | `2f2c44d6` |
| 2026-09-02 | [PCA: Nén Dữ Liệu Mà Không Mất Thông Tin](./2026-09-02-pca-dimensionality-reduction-89cd5b1b.html) | Dimensionality Reduction — Principal Component Analysis, eigenvalue/eigenvector, chuẩn hoá trước PCA, chọn đúng thứ tự trục PC1/PC2, % phương sai giữ lại, sai số tái tạo | `89cd5b1b` |
| 2026-09-01 | [Confusion Matrix & Precision/Recall/F1/ROC-AUC](./2026-09-01-confusion-matrix-metrics-102456cc.html) | Model Evaluation — Accuracy Paradox trên dữ liệu mất cân bằng, Confusion Matrix (TP/FP/TN/FN), Precision vs Recall vs F1, ROC curve & AUC, chọn threshold theo chi phí FN/FP | `102456cc` |
| 2026-08-31 | [Support Vector Machine](./2026-08-31-svm-support-vector-machine-28b46348.html) | Maximum-Margin Classifier — hyperplane, support vector, hard vs soft margin, slack variable, tham số C, overfit theo outlier | `28b46348` |
| 2026-08-30 | [Naive Bayes: Bộ Lọc Spam](./2026-08-30-naive-bayes-spam-filter-201288cf.html) | Probabilistic Classifier — Định lý Bayes, giả định độc lập, Laplace smoothing, zero-frequency problem, numerical underflow, imbalanced prior | `201288cf` |
| 2026-08-29 | [K-Nearest Neighbors](./2026-08-29-knn-k-nearest-neighbors-1600b4a3.html) | Supervised Learning — lazy/instance-based learning, chọn k (overfit vs underfit), tầm quan trọng của chuẩn hoá dữ liệu | `1600b4a3` |
| 2026-08-27 | [Logistic Regression](./2026-08-27-logistic-regression-33a99007.html) | Supervised Classification — sigmoid, threshold tuning (precision/recall), L2 regularization | `33a99007` |
| 2026-08-26 | [Random Forest & Ensemble Learning](./2026-08-26-random-forest-ensemble-35f36b72.html) | Ensemble Learning — Bagging vs Boosting vs Stacking, bootstrap, vote đa số | `35f36b72` |
| 2026-08-25 | [Cây Quyết Định (Decision Tree)](./2026-08-25-decision-tree-3d45ae7c.html) | Supervised Learning — Gini/Entropy, độ sâu cây, overfitting/underfitting, pruning | `3d45ae7c` |
| 2026-08-25 | [CNN: Tích Chập & Pooling](./2026-08-25-cnn-convolution-4bbe45f2.html) | Computer Vision — convolution, kernel/filter, ReLU, max pooling, data augmentation | `4bbe45f2` |
| 2026-08-23 | [K-Means Clustering](./2026-08-23-kmeans-clustering-1dba440e.html) | Unsupervised Learning — phân cụm, E-step/M-step, elbow method, chuẩn hoá dữ liệu | `1dba440e` |
| 2026-08-22 | [Overfitting vs Underfitting](./2026-08-22-overfitting-underfitting-c4cf9012.html) | Model Evaluation — bias-variance tradeoff, underfit/overfit, regularization (Ridge/L2) | `c4cf9012` |
| 2026-08-20 | [Perceptron từng nhịp](./2026-08-20-perceptron-cd2c084e.html) | Neural Networks — perceptron, hàm ngưỡng, quy tắc cập nhật, giới hạn tuyến tính (XOR) | `cd2c084e` |
| 2026-08-19 | [Gradient Descent: Đi Tìm Đáy Thung Lũng](./gradient-descent-20260819-4ecf3f.html) | Optimization — Batch/SGD/Mini-batch/Momentum gradient descent | `4ecf3f` |

## Cấu trúc mỗi bài

1. Định nghĩa ngắn gọn + công thức tối giản
2. Bài toán thực tế kèm dữ liệu thật
3. **3–4 trạng thái** của model, mỗi trạng thái có biểu đồ + code + đánh giá ✅ / ⚠️ / ❌
4. Bảng so sánh `[Trạng thái | Input | Xử lý | Output | Đánh giá]`
5. Demo tương tác: nhập input → xem từng bước tính → output
6. Dữ liệu tốt vs dữ liệu xấu
7. Bài tập nhỏ + quiz tự chấm

Hỗ trợ dark mode và màn hình điện thoại.
