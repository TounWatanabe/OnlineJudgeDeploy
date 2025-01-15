[English](https://github.com/TounWatanabe/OnlineJudgeDeploy/blob/2.0/README.md) | Tiếng Việt

## Cài đặt

1. Cài [Docker](https://www.docker.com/)

2. Lấy mã nguồn:

    ```bash
    git clone -b 2.0 https://github.com/TounWatanabe/OnlineJudgeDeploy.git && cd OnlineJudgeDeploy
    ```

3. Start service

    ```bash
    docker-compose up -d
    ```

Tùy theo tốc độ mạng, quá trình thiết lập có thể được hoàn tất tự động trong khoảng 5 đến 30 phút mà không cần can thiệp thủ công.

Đợi quá trình thực thi lệnh hoàn tất rồi chạy `docker ps -a`. Khi bạn thấy trạng thái của tất cả các vùng chứa không có `unhealthy` hoặc `Exited (x) xxx`, điều đó có nghĩa là OnlineJudge đã khởi động thành công.

Truy cập cổng HTTP 80 hoặc cổng HTTPS 443 của máy chủ thông qua trình duyệt và bạn có thể bắt đầu sử dụng nó. Đường dẫn quản lý nền là `/admin`, tên người dùng quản trị viên cấp cao được tự động thêm trong quá trình cài đặt là `root` và mật khẩu là `rootroot`. **Nếu bạn đăng nhập thành công, vui lòng đổi mật khẩu tài khoản ngay lập tức.**.

Tài liệu gốc (Tiếng Anh + Tiếng Trung): http://opensource.qduoj.com/
