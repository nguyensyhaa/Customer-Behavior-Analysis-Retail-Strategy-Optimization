# Customer Behavior Analysis & Retail Strategy Optimization 🛒

## 📌 Tổng quan (Overview)
Dự án tập trung phân tích dữ liệu giao dịch bán lẻ để thấu hiểu hành vi khách hàng, từ đó đề xuất các chiến lược tối ưu hóa doanh thu và giữ chân khách hàng. Sử dụng các kỹ thuật phân tích nâng cao như RFM và thuật toán Apriori để tìm ra quy luật mua sắm.

## 📂 Dữ liệu (Dataset)
* **Nguồn:** Kaggle Retail Dataset.
* **Quy mô:** Hơn 293,000 dòng dữ liệu giao dịch.
* **Đặc điểm:** Bao gồm thông tin khách hàng, chi tiết đơn hàng, sản phẩm và thời gian giao dịch.

## 🛠 Công nghệ sử dụng (Tech Stack)
* **Ngôn ngữ:** Python (Pandas, NumPy, Matplotlib, Seaborn, Mlxtend).
* **Cơ sở dữ liệu:** SQL (Truy vấn & Trích xuất dữ liệu).
* **Trực quan hóa:** Power BI (Interactive Dashboard).

## 🔍 Phương pháp thực hiện (Methodology)
1. **Data Cleaning:** Xử lý dữ liệu thô, loại bỏ giá trị Null, tách bảng để chuẩn hóa dữ liệu.
2. **RFM Analysis:** Phân khúc khách hàng dựa trên 3 chỉ số: Recency (Mới mua), Frequency (Tần suất), Monetary (Giá trị).
3. **Market Basket Analysis (Apriori):** Tìm kiếm các sản phẩm thường được mua cùng nhau để tối ưu chiến lược Cross-sell/Up-sell.
4. **Visualization:** Xây dựng Dashboard theo dõi các chỉ số KPI như NPS, Retention Rate.

## 📊 Kết quả & Insights (Key Findings)
* **Khách hàng tiềm năng:** Nhóm khách hàng độ tuổi **19-40** có sức mua lớn nhất.
* **Chiến lược sản phẩm:** Phát hiện "Alkaline Water" là sản phẩm mang lại doanh thu cao nhất nhưng lại có rating thấp -> Đề xuất cải thiện chất lượng sản phẩm này ngay lập tức.
* **Mô hình gợi ý:** Xác định thành công các combo sản phẩm có độ kết hợp cao (Lift > 1) để chạy khuyến mãi.

