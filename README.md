# 🏦 Credit Scoring: Data Balancing & Explainable AI (XAI)
**Đề tài:** Nghiên cứu ứng dụng kỹ thuật Cân bằng dữ liệu và AI giải thích được (XAI) trong Xếp hạng tín dụng.

## 📌 1. Giới thiệu (Overview)
Dự án này nhằm mục đích xây dựng mô hình máy học dự đoán khả năng vỡ nợ của khách hàng (Credit Default Prediction) dựa trên bộ dữ liệu **Home Credit Default Risk**.
Thách thức chính mà nhóm tập trung giải quyết:
1.  **Dữ liệu mất cân bằng (Imbalanced Data):** Tỷ lệ vỡ nợ thực tế rất thấp (~8%), khiến mô hình dễ bị thiên lệch.
2.  **Tính minh bạch (Interpretability):** Sử dụng **SHAP** để giải thích lý do tại sao hồ sơ bị từ chối/chấp thuận.

**Phạm vi dữ liệu:** Chỉ sử dụng bảng `application_train.csv` (Thông tin nộp đơn tĩnh).

---

## 👥 2. Thành viên & Phân công (Team & Roles)

| STT | Thành viên | Vai trò (Role) |  
|:---:|:---|:---|
| 1 | **[Đặng Quang Hưng]** | **Team Leader** |
| 2 | **[Nguyễn Trần Bảo Tâm]**|**Member**|
| 3 | **[Trần Đình Duy]** |**Member**|
| 4 | **[Nguyễn Hữu Thành]** |**Member**|
| 5 | **[Nguyễn Quang Thái]** |**Member**|

---

## 📂 3. Cấu trúc Dự án (Project Structure)
```bash
├── data/                   # Link dataset, raw/processed data
├── notebooks/              # Dode
│   ├── EDA.ipynb
│   └── ...
├── src/                    # Source code
├── images/                 # Biểu đồ cho báo cáo
├── requirements.txt        # Các thư viện cần thiết
└── README.md               # File hướng dẫn này
