1. Giới thiệu đề tài

- Trong thời đại hiện đại, ngành tài chính đóng vai trò quan trọng trong việc hỗ trợ
và phát triển nền kinh tế của một quốc gia. Việt Nam không phải là ngoại lệ, với một hệ
thống tài chính đang phát triển mạnh mẽ và đa dạng. Trong bối cảnh này, việc nắm bắt
thông tin và hiểu rõ về hoạt động của các doanh nghiệp thông qua việc trực quan hóa dữ
liệu là rất quan trọng.
Mục tiêu của dự án này là phân tích và trực quan hóa dữ liệu liên quan đến các
cổ phiếu của các doanh nghiệp tại Việt Nam. Bằng cách sử dụng các công cụ trực quan
hóa dữ liệu, chúng tôi hy vọng có thể đem lại cái nhìn sâu sắc và tổng quan về hiệu suất,
biến động và xu hướng của các cổ phiếu. Điều này không chỉ hỗ trợ nhà đầu tư trong
việc ra quyết định mua bán cổ phiếu mà còn cung cấp thông tin hữu ích cho các nhà
nghiên cứu, nhà quản lý quỹ và các chuyên gia tài chính để hiểu rõ hơn về thị trường tài
chính ở Việt Nam.
Trực quan hóa dữ liệu không chỉ giúp chúng ta hiểu rõ hơn về các con số và dữ
liệu, mà còn làm cho thông tin trở nên trực quan và dễ tiếp cận hơn. Bằng cách này,
chúng ta có thể nắm bắt các xu hướng, phát hiện ra các mẫu và đưa ra những quyết định
thông minh dựa trên dữ liệu. Chính vì vậy, dự án này không chỉ tập trung vào việc thu
thập và phân tích dữ liệu, mà còn đặc biệt chú trọng vào việc truyền đạt thông điệp và
hiểu biết từ dữ liệu thông qua các biểu đồ, đồ thị và hình ảnh mô phỏng.
1.1. Công cụ và tài liệu hỗ trợ thực hiện đồ án
Bài toán: Sử dụng công cụ trực quan hóa dữ liệu để phân tích hiệu suất cổ phiếu
của một số doanh nghiệp tại Việt Nam.
Ngữ cảnh: Hiệu suất cổ phiếu là một trong những chỉ số quan trọng đối với thị
trường tài chính, ảnh hưởng đến sự quan tâm của nhà đầu tư và tình hình kinh tế xã hội.
Việc phân tích và dự đoán hiệu suất cổ phiếu có vai trò quan trọng trong việc đưa ra
quyết định đầu tư, giao dịch và quản lý danh mục đầu tư.
Dữ liệu đồ án: Bộ dữ liệu được sử dụng được lấy từ các nguồn đáng tin cậy, bao
gồm dữ liệu thị trường chứng khoán và các chỉ số tài chính của một số các doanh nghiệp
tại Việt Nam...
Công cụ sử dụng: Public Tableau, Jupyter Notebook.
Mục tiêu: Dự án này nhằm mục đích phân tích và trực quan hóa dữ liệu liên quan
đến cổ phiếu của một số doanh nghiệp tại Việt Nam.

2

1.2. Quy trình thực hiện
Đầu tiên, chúng tôi đã thu thập dữ liệu từ các nguồn đáng tin cậy như các trang
web tài chính và cơ sở dữ liệu về thị trường chứng khoán. Dữ liệu bao gồm các chỉ số
quan trọng như giá cổ phiếu, khối lượng giao dịch, biến động giá, và các chỉ số tài chính
khác liên quan đến hoạt động kinh doanh của các doanh nghiệp.
Tiếp theo, nhóm đã thực hiện bước tiền xử lý dữ liệu để làm sạch và chuẩn hóa
dữ liệu, đảm bảo tính nhất quán và đáng tin cậy của nó. Sau đó, chúng tôi đã sử dụng
một loạt các công cụ và kỹ thuật trực quan hóa dữ liệu như biểu đồ đường, biểu đồ cột,
đồ thị nến, và biểu đồ phân tích kỹ thuật để hiển thị thông tin một cách trực quan và dễ
hiểu.
Kết quả của dự án cung cấp cái nhìn sâu sắc về hiệu suất, biến động và xu hướng
của một số cổ phiếu doanh nghiệp tại Việt Nam trong một khoảng thời gian nhất định.
Thông qua các biểu đồ và đồ thị, nhóm đã phân tích các mẫu và xu hướng trong dữ liệu,
nhấn mạnh vào những điểm quan trọng và cung cấp thông tin hữu ích cho nhà đầu tư,
nhà quản lý quỹ và nhà nghiên cứu trong lĩnh vực tài chính. Dự án này mang lại lợi ích
trong việc hỗ trợ ra quyết định đầu tư, đánh giá rủi ro và hiểu biết sâu hơn về thị trường
tài chính của Việt Nam.
2. Phương pháp thực hiện
Dashboard: FinalProject | Tableau Public
2.1. Thông tin về tập dữ liệu
Tên cột Mô tả
Ticker Mã chứng khoán của doanh nghiệp.
DTYYYYMMDD Ngày giao dịch (theo định dạng YYYYMMDD).
OpenFixed Giá mở cửa (cố định) trong ngày giao dịch.
HighFixed Giá cao nhất (cố định) trong ngày giao dịch.
LowFixed Giá thấp nhất (cố định) trong ngày giao dịch.
CloseFixed Giá đóng cửa (cố định) trong ngày giao dịch.
Volume Khối lượng giao dịch trong ngày (số lượng cổ phiếu được giao dịch).

3

Dữ liệu được nhóm crawl từ Kaggle. Dữ liệu về cổ phiếu của 32 doanh nghiệp lớn ở
Việt Nam từ năm 2017 đến năm 2023. Dữ liệu bao gồm: 7 biến và hơn 75000 quan sát.
