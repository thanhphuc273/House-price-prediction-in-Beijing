# House-price-prediction-in-Beijing

## Mô tả

Dự án này tập trung vào việc dự đoán giá nhà tại Bắc Kinh bằng cách sử dụng hai mô hình máy học: Random Forest Regression và Decision Tree Regression. Dữ liệu sử dụng trong dự án được thu thập từ [https://www.kaggle.com/datasets/ruiqurm/lianjia].


## Yêu Cầu

- Python 3.x
- Jupyter Notebook hoặc Google Colab

## Cài Đặt

    ```bash
    git clone https://github.com/thanhphuc273/House-price-prediction-in-Beijing/tree/master.git
    cd House-price-prediction-in-Beijing
    ```
## Dữ Liệu

Giá nhà ở Bắc Kinh từ năm 2011 đến năm 2017, lấy từ Lianjia.com
Nó bao gồm URL, ID, Lng, Lat, CommunityID, TradeTime, DOM (ngày trên thị trường), Người theo dõi, Tổng giá, Giá, Quảng trường, Phòng khách, số phòng khách, Nhà bếp và Phòng tắm, Loại tòa nhà, Thời gian xây dựng. điều kiện cải tạo, cấu trúc tòa nhà, Tỷ lệ thang (lưa tỷ lệ giữa số lượng cư dân trên cùng một tầng và số thang máy thang. Nó mô tả trung bình một cư dân có bao nhiêu thang thang), thang máy, Quyền sở hữu trong năm năm (Nó liên quan đến chính sách mua nhà bị hạn chế của Trung Quốc), Tàu điện ngầm, Quận, Giá trung bình của Cộng đồng.
Hầu hết dữ liệu được giao dịch trong năm 2011-2017, một số trong số chúng được giao dịch vào tháng 1 năm 2018, và một số thậm chí còn sớm hơn (2010,2009)

## Chạy Mô Hình

Mở Jupyter Notebook hoặc Google Colab và mở tệp `Python_MachineLearning.ipynb`. Thực hiện các ô code theo thứ tự để huấn luyện và đánh giá mô hình.

```bash
jupyter notebook Python_MachineLearning.ipynb
