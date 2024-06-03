# JMeter

Jmeter là một phần mềm cái mà có thể sử dụng để chạy thử nghiệm hiệu suất, thử nghiệm tại và thử nghiệm chức năng của ứng dụng web. JMeter cũng có thể mô phỏng tải nặng trên máy chủ bằng cách tạo hàng tấn người dùng ảo đồng thời lên máy chủ web.

JMeter là một ứng dụng mã nguồn mở. Điều này có nghĩa là bạn có thể tải xuống mã nguồn của JMeter để phân tích và sửa đổi nó nếu bạn muốn.

Stefano Mazzocchi của Quỹ phần mềm Apache thiết kế nó đầu tiên. Bây giờ anh ấy là một kỹ sư phần mềm tại Google. Ngày nay, JMeter đã trở thành một trong những công cụ thử nghiệm phổ biến nhất trên thế giới, bên cạnh Selenium và Load Runner.
Ưu điểm:
Mã nguồn mở: Jmeter là một phần mềm mã nguồn mở. Điều này có nghĩa là nó có thể được tải xuống miễn phí. Nó cũng là một ứng dụng Java thuần túy 100%. Nhà phát triển có thể sử dụng mã nguồn của nó, có thể sửa đổi và tùy chỉnh nó theo yêu cầu của họ. Họ cũng có thể đóng góp code của họ để làm nên một JMeter tốt hơn.

Dễ sử dụng: Người dùng có thể cài đặt và sử dụng JMeter một cách dễ dàng. Chỉ cần tải về từ internet, cài đặt và chạy. Như một ứng dụng Java thuần túy, nó sẵn sàng để sử dụng với các cài đặt mặc định. Nó không yêu cầu bạn phải có bất kỳ kỹ năng cụ thể nào hoặc kiến thức tên miền để sử dụng nó.

Nền tảng độc lập: JMeter được phát triển bằng Java, đây là ngôn ngữ lập trình phổ biến nhất trên thế giới. Do đó, nó có thể chạy trong mọi hệ điều hành có thể là Window, Linux hoặc Mac.

Báo cáo mạnh mẽ: JMeter có thể tạo báo cáo hiệu quả. Kết quả kiểm tra có thể được xem lại bằng cách sử dụng Graph, Chart, and Tree View. Jmeter hỗ trợ các định dạng khác nhau của báo cáo như text, XML, HTML and JSON.

Thử nghiệm cuối cùng: Với Jmeter, người dùng có thể thực hiện bất kỳ loại kiểm thử nào mà bạn muốn. Load Test, Stress Test, Functional Test, Distributed Test, tất cả trong một công cụ

Tính linh hoạt: Bạn có thể tùy chỉnh JMeter theo yêu cầu của bạn và áp dụng thử nghiệm tự động cho JMeter. Bạn có thể tiết kiệm công sức của việc thực hiện các trường hợp kiểm tra thủ công.

Hỗ trợ đa giao thức: JMeter hỗ trợ một vài giao thức như HTTP, FTP, SOAP, JDBC, JMS và LDAP. Nó cũng có thể được sử dụng để kiểm thử hiệu suất của cơ sở dữ liệu của bạn.

JMeter là công cụ tuyệt vời, nhưng nó vẫn có một số nhược điểm.

Nhược điểm:
Tiêu thụ bộ nhớ: JMeter có thể mô phỏng tải nặng và trực quan hóa báo cáo thử nghiệm. Điều này có thể tiêu tốn rất nhiều bộ nhớ và có thể dẫn ra khỏi bộ nhớ dưới tải nặng.

Chỉ áp dụng cho ứng dụng web: JMeter là công cụ tốt để thử nghiệm ứng dụng web nhưng nó không phải là công cụ phù hợp để thử nghiệm ứng dụng máy tính để bàn.

Thiếu hỗ trợ cho JavaScript: JMeter không phải là một trình duyệt, vì vậy nó không thể chạy JavaScript trong ứng dụng web. Nó có hỗ trợ hạn chế để xử lý JavaScript hoặc Ajax, điều này có thể ảnh hưởng đến độ chính xác của mô phỏng.

# Tạo các Thread Group với 10 user   
![Thread Group](https://github.com/nhvu2311/JMeterr/blob/main/Screenshot%202024-06-03%20155806.png)

 # Tạo HTTP Request với tên server hoặc IP là canvasphenikaa-uni.edu.vn
![HTTP Request](https://github.com/nhvu2311/JMeterr/blob/main/Screenshot%202024-06-03%20160738.png)

Sau khi khởi chạy sẽ cho ra kết quả với các dạng hiển thị sau:

# Kết quả dạng cây
![Tree](https://github.com/nhvu2311/JMeterr/blob/main/Screenshot%202024-06-03%20160747.png)

# Kết quả dạng bảng

![Table](https://github.com/nhvu2311/JMeterr/blob/main/Screenshot%202024-06-03%20160753.png)

# Kết quả dạng biểu đồ 

![Graph](https://github.com/nhvu2311/JMeterr/blob/main/Screenshot%202024-06-03%20160758.png)

# Báo cáo tổng quát 
![Summary Report](https://github.com/nhvu2311/JMeterr/blob/main/Screenshot%202024-06-03%20160808.png)

Sau khi gửi yêu cầu và đo lưởng thời lượng phản hồi từ máy chủ. Đã cho ra kết quả như sau:
	- Thời gian phản hổi trung bình là 1624 mili giây, thời gian phản hồi tối thiểu là 0 và tối đa 19249 mili giây. Độ lệch chuẩn là 3276.61 mili giây. Hiệu năng của trang web có sự thay đổi rõ rệt

Số lượng yêu cầu thành công và thất bại : 
	- Với 10 yêu cầu gửi đi thì không có sự thất bại. Điều này cho thấy trang web hoạt động ổn định và duy trì được khả năng xử lý các yêu cầu.
