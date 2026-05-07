# Dashboard phân tích doanh thu bán vé thể thao



##### Dasboard được xây dựng theo mô hình Star Schema với bảng fact (FactTickets) và các bảng dimension (DimStadiums, DimMatches, DimOrders, DimUsers, TeamSlicer).



**Trang 1 — Báo cáo Doanh Thu Theo Sân**

**Phân tích hiệu suất bán vé theo từng sân vận động và khu vực địa lý, bao gồm:**



* 4 KPI Cards: Tổng Doanh Thu, Tổng số Đơn hàng, Tổng số Vé bán, Số Khách hàng Duy nhất
* Bảng chi tiết (Table): Tên sân, địa điểm, doanh thu
* Biểu đồ Donut \& Pie: Tỷ trọng doanh thu theo tên sân và khu vực
* Bar Chart \& Column Chart: So sánh doanh thu giữa các sân và khu vực
* Slicer (Location): Lọc dữ liệu theo khu vực địa lý



**Trang 2 — Báo cáo Doanh Thu và Số Vé Theo Đội Tuyển**

**Phân tích hành vi mua vé theo đội tuyển, giải đấu và người dùng, bao gồm:**



* Bảng chi tiết: Trận đấu (home/away team), giải đấu, doanh thu, số vé theo năm
* Column Chart: Doanh thu theo từng đội tuyển (có bộ lọc động TeamSlicer)
* Clustered Bar Chart: So sánh số vé bán theo cặp trận đấu và theo khách hàng cá nhân
* Clustered Column Chart: Phân phối số vé trên mỗi đơn hàng \& doanh thu theo năm
* Stacked Area Chart: Xu hướng giá vé trung bình theo giải đấu qua các năm
* Line Chart: Mô hình đặt vé theo giờ trong ngày theo năm

