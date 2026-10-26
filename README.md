<div align="center">

# 🔍 Nguyễn Văn Đoàn Bảo Huy

### Data Analyst Portfolio · SQL · Python · Power BI · Excel

*“Khi ta loại bỏ những điều không thể, thứ còn lại dù vô lý đến đâu, đó chính là sự thật.”*

**[🌐 Xem Portfolio Website](https://huy054.github.io/huy-portfolio/)** · **[💻 GitHub](https://github.com/Huy054)** · **[💼 LinkedIn](https://www.linkedin.com/in/huy-4671283b4/)**

</div>

---

## 👨‍💻 Giới thiệu

Mình là sinh viên **Công nghệ thông tin**, đang định hướng trở thành **Data Analyst Intern / Fresher**. Mình quan tâm đến việc biến dữ liệu thô thành thông tin đáng tin cậy, trình bày kết quả dễ hiểu và đề xuất hướng ra quyết định dựa trên bằng chứng.

Portfolio này tổng hợp ba dự án thực hành theo ba hướng riêng biệt: **phân tích doanh thu bằng SQL**, **phân tích khả năng sinh lời bằng Python và Power BI**, và **phân khúc khách hàng bằng Machine Learning**. Mỗi dự án đều có mã nguồn, kết quả phân tích và tài liệu giải thích bằng tiếng Việt.

## 🛠️ Kỹ năng và công cụ

| Nhóm kỹ năng | Công cụ và nội dung |
|---|---|
| **SQL & Database** | SQL Server, MySQL, JOIN, CTE, Window Functions, VIEW, kiểm tra chất lượng dữ liệu |
| **Python & Data Analysis** | Pandas, NumPy, Matplotlib, làm sạch dữ liệu, EDA, thống kê mô tả |
| **Business Intelligence** | Power BI, Power Query, DAX, KPI, Dashboard, Data Storytelling |
| **Excel** | PivotTables, xử lý và tổng hợp dữ liệu, Power Query |
| **Machine Learning** | scikit-learn, K-Means, StandardScaler, Elbow, Silhouette Score |

## 📂 Dự án tiêu biểu

### 🍕 1. Pizza Place Sales Analysis — SQL Server & Power BI

![Pizza Place — Sales Overview](https://raw.githubusercontent.com/Huy054/Pizza-Place-Sales-Analysis/main/images/sales_overview.png)

Phân tích hoạt động bán pizza trong **năm 2015** qua dữ liệu đơn hàng, sản phẩm và doanh thu. Dự án sử dụng **T-SQL và SQL VIEW** để kiểm tra, chuẩn hóa dữ liệu giá khi nhập CSV, sau đó trực quan hóa bằng **Power BI** với hai trang *Sales Overview* và *Product Performance*.

**Kết quả nổi bật:** **21.350 đơn hàng** · **49.574 pizza bán ra** · **817.860,05 USD doanh thu** · **38,31 USD/đơn**. Phân tích thêm khung giờ cao điểm, top sản phẩm, kích cỡ và phân nhóm ABC theo **doanh thu**.

**Công nghệ:** `SQL Server` · `T-SQL` · `CTE` · `Window Functions` · `SQL VIEW` · `Power BI` · `DAX`

[**Xem mã nguồn và dashboard Pizza Place**](https://github.com/Huy054/Pizza-Place-Sales-Analysis)

### 🛒 2. Superstore Data Analysis — Python & Power BI

![Superstore — Business Performance](https://raw.githubusercontent.com/Huy054/superstore-data-analysis/main/images/business_performance.png)

Kiểm tra và làm sạch dữ liệu bán lẻ bằng **Python/Pandas**, giữ độ chính xác của `Sales` và `Profit`, rồi xây dựng hai trang Power BI: *Business Performance* và *Profitability Deep Dive*. Trọng tâm là **hiệu quả kinh doanh, biên lợi nhuận, giảm giá và các nhóm sản phẩm thua lỗ**.

**Kết quả nổi bật:** **9.994 dòng bán hàng** · **5.009 đơn hàng** · **2.297.200,86 USD doanh thu** · **286.397,02 USD lợi nhuận** · **12,47% biên lợi nhuận**. Có **1.871 dòng bán hàng bị lỗ**; nhóm giảm giá trên 40% có biên lợi nhuận tổng hợp **−77,40%** trong bộ dữ liệu mẫu.

**Công nghệ:** `Python` · `Pandas` · `Data Cleaning` · `Power BI` · `Power Query` · `DAX`

[**Xem mã nguồn và dashboard Superstore**](https://github.com/Huy054/superstore-data-analysis)

### 👥 3. Customer Behavior Analysis — Python & K-Means

![Customer Behavior — K-Means Clustering](https://raw.githubusercontent.com/Huy054/customer-behavior-analysis/main/images/customer_clusters.png)

Phân tích dữ liệu mẫu **200 khách hàng**, chuẩn hóa **thu nhập hàng năm** và **điểm chi tiêu**, sau đó sử dụng **K-Means** để khám phá các phân khúc khách hàng. Số cụm được đánh giá bằng **Elbow và Silhouette Score**, kèm thống kê hồ sơ từng cụm và kiểm tra độ nhất quán qua nhiều `random_state`.

**Kết quả nổi bật:** chọn **k = 5** (Silhouette Score **0,5547**, cao nhất trong khoảng `k = 2–10` đã thử); nhóm thu nhập và điểm chi tiêu trung bình có **81 khách hàng (40,5%)**. Các đề xuất marketing được trình bày như **giả thuyết cần kiểm thử**, không khẳng định doanh thu thực tế từ điểm chi tiêu.

**Công nghệ:** `Python` · `Pandas` · `scikit-learn` · `StandardScaler` · `K-Means` · `Silhouette` · `Matplotlib`

[**Xem notebook, dữ liệu và kết quả Customer Behavior**](https://github.com/Huy054/customer-behavior-analysis)

> **Lưu ý về dữ liệu:** Cả ba dự án sử dụng bộ dữ liệu mẫu phục vụ học tập và thực hành. Các chỉ số không đại diện cho báo cáo tài chính hay hoạt động thực tế của một doanh nghiệp. Với Customer Behavior, **Spending Score không phải doanh thu thực chi**.

## 🎓 Chứng chỉ chuyên môn

Các chứng chỉ có tài liệu PDF đang lưu trong [`certificates/`](certificates/) của Portfolio:

| Chứng chỉ | Đơn vị | Tài liệu |
|---|---|---|
| Career Essentials in Data Analysis | Microsoft & LinkedIn | [Xem PDF](certificates/CertificateOfCompletion_Career%20Essentials%20in%20Data%20Analysis%20by%20Microsoft%20and%20LinkedIn.pdf) |
| Learning Data Analytics Part 2: Extending and Applying Core Knowledge | LinkedIn Learning | [Xem PDF](certificates/CertificateOfCompletion_Learning%20Data%20Analytics%20Part%202%20Extending%20and%20Applying%20Core%20Knowledge.pdf) |
| Data Visualization for Data Analysts and Analytics | LinkedIn Learning | [Xem PDF](certificates/CertificateOfCompletion_Data%20Visualization%20for%20Data%20Analysts%20and%20Analytics%20%281%29.pdf) |
| SQL for Data Analysis | LinkedIn Learning | [Xem PDF](certificates/CertificateOfCompletion_SQL%20for%20Data%20Analysis.pdf) |
| Learning Power BI Desktop | LinkedIn Learning | [Xem PDF](certificates/CertificateOfCompletion_Learning%20Power%20BI%20Desktop.pdf) |
| Getting Started with Microsoft Excel | Coursera | [Xem PDF](certificates/LDDEQSWEGV5Z.pdf) |
| Data Analytics for Business Professionals | LinkedIn Learning | [Xem PDF](certificates/CertificateOfCompletion_Data%20Analytics%20for%20Business%20Professionals.pdf) |

## 🌐 Giới thiệu website Portfolio

Website **HUY.DATA** được xây dựng bằng **HTML, CSS** và giao diện responsive, triển khai qua **GitHub Pages**. Nội dung website tập trung vào ba dự án, các kỹ năng, chứng chỉ và thông tin liên hệ.

```text
huy-portfolio/
├── index.html        # Giao diện website
├── style.css         # Kiểu dáng và responsive
├── README.md         # Giới thiệu Portfolio và dự án
└── certificates/     # Chứng chỉ PDF
```

## 📫 Liên hệ

- **Email:** [huynguyen54140@gmail.com](mailto:huynguyen54140@gmail.com)
- **LinkedIn:** [Huy Nguyễn](https://www.linkedin.com/in/huy-4671283b4/)
- **GitHub:** [Huy054](https://github.com/Huy054)
- **Portfolio:** [huy054.github.io/huy-portfolio](https://huy054.github.io/huy-portfolio/)

<div align="center">

*Keep exploring the truth — biến dữ liệu thành những quyết định có cơ sở.*

</div>
