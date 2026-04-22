📄 Business Requirements Document (BRD)
Ứng dụng Game Caro
1. Tổng quan
1.1 Mục tiêu

Xây dựng một ứng dụng game Caro (cờ caro / Gomoku) cho phép người dùng giải trí, thi đấu với bạn bè hoặc với máy, đồng thời có thể lưu lại kết quả và xếp hạng người chơi.

1.2 Phạm vi

Ứng dụng sẽ được phát triển trên:

Nền tảng Web (ưu tiên)
Có thể mở rộng sang Mobile (Android/iOS)
2. Stakeholders
Stakeholder	Vai trò
Product Owner	Định hướng sản phẩm
Development Team	Phát triển ứng dụng
QA Team	Kiểm thử
End Users	Người chơi
3. Mô tả sản phẩm

Ứng dụng Caro là một trò chơi:

Hai người chơi (PvP) hoặc chơi với máy (PvE)
Luật: Người chơi nào tạo được 5 quân liên tiếp sẽ thắng
Giao diện đơn giản, dễ sử dụng
4. Business Objectives
Thu hút người dùng giải trí
Tăng thời gian sử dụng ứng dụng
Có thể tích hợp quảng cáo hoặc mô hình freemium trong tương lai
5. Functional Requirements
5.1 Đăng nhập / Đăng ký
Người dùng có thể:
Đăng ký tài khoản
Đăng nhập
Chơi với tư cách khách (Guest)
5.2 Gameplay
5.2.1 Chế độ chơi
Người vs Người (Local hoặc Online)
Người vs Máy (AI)
5.2.2 Luật chơi
Bàn cờ kích thước: 10x10, 15x15 hoặc 20x20
Luân phiên đánh X và O
Người thắng là người có 5 quân liên tiếp (ngang, dọc, chéo)
5.3 Giao diện người dùng
Hiển thị bàn cờ
Highlight nước đi gần nhất
Hiển thị trạng thái trận đấu:
Đang chơi
Thắng / Thua / Hòa
5.4 Lưu trữ & Lịch sử
Lưu lại:
Kết quả trận đấu
Lịch sử chơi
Người dùng có thể xem lại lịch sử
5.5 Bảng xếp hạng (Leaderboard)
Xếp hạng dựa trên:
Số trận thắng
Điểm số
5.6 Chat (Optional)
Người chơi có thể chat khi chơi online
6. Non-Functional Requirements
6.1 Hiệu năng
Thời gian phản hồi < 1 giây
Hỗ trợ nhiều người chơi đồng thời
6.2 Bảo mật
Bảo vệ thông tin tài khoản
Xác thực người dùng
6.3 Khả năng mở rộng
Dễ dàng nâng cấp AI
Có thể mở rộng thêm tính năng multiplayer online
6.4 Khả năng sử dụng
Giao diện thân thiện, dễ chơi
Hỗ trợ nhiều độ tuổi
7. User Stories
Là người chơi, tôi muốn chơi nhanh với máy để giải trí
Là người chơi, tôi muốn chơi với bạn bè online
Là người chơi, tôi muốn xem lại lịch sử trận đấu
Là người chơi, tôi muốn xem bảng xếp hạng
8. Assumptions
Người dùng có kết nối internet (đối với chơi online)
Người dùng có thiết bị hỗ trợ trình duyệt
9. Constraints
Giới hạn thời gian phát triển
Giới hạn tài nguyên server ban đầu
10. Future Enhancements
AI nâng cao (Minimax, Alpha-beta pruning)
Matchmaking online
Tournament mode
Giao diện tùy chỉnh (themes, skins)
