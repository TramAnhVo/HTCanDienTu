# Hệ thống cân bàn sử dụng đầu kết nối RS232 với cân bàn điện tử
khi kết nối, trọng lượng hàng hóa sẽ truyền vào hệ thống với các chức năng sau:
+ Chức năng cân thủ công lưu lại trọng lượng và tính toán trọng lượng thực ( Trong trường hợp có trọng lượng bì) và ghi nhận thành 1 phiếu cân.
+ Chức nằng cân tự động, trọng lượng sẽ tự động lưu vào ( lưu 1 lần khi trọng lượng ổn định và trọng lượng trở về 0 thì sẽ không lưu) với chức năng này người dùng chỉ cần để hàng lên cân không cần phải thực hiện thao tác lưu từng phiếu cân như cân thủ công, tiết kiệm thời gian trong lúc cân hàng hóa với số lượng nhiều. Ngoài ra, có thể áp dụng cho nhiều trường hợp khác nữa.
+ Chức năng in phiếu cân ( có form mẫu cho phiếu cân)
+ Chức năng xuất ra file excel
+ Chức năng tạo mã phiếu cân theo nhiều định dạng (yyyyMMdd-00000i/00000i/NX-0000i) và có thể khởi tạo theo nhiều mốc thời gian (theo ngày/ theo tháng/ theo năm)
+ Chức năng kết nối với SQL Server (kết nối chủ động và bảo mật)
+ Chức năng tìm kiếm theo ngày, theo mốc thời gian,... thuận tiện cho người dùng tìm kiếm và có thể in phiếu cân cũ(nếu cần)
+ Chức năng quản lý khách hàng/ hàng hóa/ trọng lượng bì/...
+ Chức năng quản lý thông tin doanh nghiệp(chức năng này thiết lập dùng cho in phiếu cân)
+ Chức năng quản lý người dùng(tạo/xóa/sửa/cấp quyền theo nhóm quyền/Cấp mật khẩu)
+ Chức năng phân quyền cho từng người dùng
+ Chức năng khôi phục lại phiếu cân đã xóa(Chức năng này dùng khi người dùng cần yêu cầu mà chỉ khôi phục được trong vòng 30 ngày)
+ Chức năng xóa tự động sau 30 ngày
+ Chức năng tạo thống số cân và điều chỉnh thông số cân phù hợp với từng cân(Vì mỗi cân sẽ có 1 thông số cân riêng biệt và sẽ truyền vào phần mềm với thông số khác nhau) 
