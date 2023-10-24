Phase 1: Định nghĩa chức năng và giao thức

Chức năng: Quản lý kết nối và thông tin máy chủ

Mô tả: Xác định cách máy khách kết nối và duy trì kết nối với máy chủ trung tâm. Xác định cách máy khách gửi thông tin về các tập tin mà nó đang lưu trữ và nhận thông tin từ máy chủ.
Giao thức: Sử dụng giao thức TCP/IP để thiết lập và duy trì kết nối giữa máy khách và máy chủ. Sử dụng giao thức tùy chỉnh để máy khách thông báo thông tin về tập tin địa phương của nó cho máy chủ.
Chức năng: Tra cứu tập tin và kiểm tra trạng thái sống của máy chủ

Mô tả: Xác định cách máy chủ có thể tra cứu danh sách các tập tin cục bộ của máy khách theo yêu cầu và kiểm tra trạng thái sống của các máy chủ khác.
Giao thức: Sử dụng giao thức tùy chỉnh để máy chủ thực hiện các yêu cầu discover và ping từ máy khách.
Chức năng: Đăng tải và tải về tập tin

Mô tả: Xác định cách máy khách có thể đăng tải tập tin lên máy chủ (lệnh publish) và tải về tập tin từ các máy khách khác (lệnh fetch).
Giao thức: Sử dụng giao thức tùy chỉnh để máy khách và máy chủ thực hiện việc đăng tải và tải về tập tin.
Chức năng: Quản lý đa luồng

Mô tả: Xác định cách máy khách xử lý đa luồng để hỗ trợ nhiều máy khách đang tải về các tập tin khác nhau cùng một lúc.
Giao thức: Không yêu cầu giao thức riêng, nhưng máy khách cần hỗ trợ đa luồng trong mã nguồn của nó để xử lý nhiều yêu cầu đồng thời.
Ghi chú:

Các giao thức tùy chỉnh có thể được định nghĩa bằng cách sử dụng mã nguồn và thư viện TCP/IP như Socket trong Python hoặc Java.
Chức năng mở rộng của hệ thống có thể bao gồm tính năng bảo mật, quản lý phiên, và nhiều tính năng khác để cải thiện hiệu suất và tính năng của ứng dụng.
Khi bạn đã xác định các chức năng và giao thức cho Phase 1, bạn cần viết báo cáo theo định dạng đã đề cập trong yêu cầu. Sau đó, nộp báo cáo này lên hệ thống quản lý môn học.
