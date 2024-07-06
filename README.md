# Chat Group Application

Ứng dụng Chat Group này được xây dựng bằng Express.js và Socket.IO, cho phép người dùng tạo các nhóm chat và trò chuyện thời gian thực.

## Mục lục

- [Giới thiệu](#giới-thiệu)
- [Tính năng](#tính-năng)
- [Cài đặt](#cài-đặt)
- [Sử dụng](#sử-dụng)
- [Công nghệ sử dụng](#công-nghệ-sử-dụng)
- [Đóng góp](#đóng-góp)
- [Giấy phép](#giấy-phép)

## Giới thiệu

Ứng dụng Chat Group cho phép người dùng tham gia vào các phòng chat, gửi và nhận tin nhắn thời gian thực. Đây là một ví dụ cơ bản về cách sử dụng Socket.IO với Express.js để xây dựng các ứng dụng thời gian thực.

## Tính năng

- Tạo và tham gia các phòng chat.
- Nhắn tin thời gian thực.
- Thông báo khi người dùng tham gia hoặc rời khỏi phòng.
- Giao diện người dùng thân thiện và dễ sử dụng.

## Cài đặt

Để cài đặt và chạy ứng dụng này trên máy tính của bạn, hãy làm theo các bước sau:

1. Clone repository này:

    ```sh
    git clone https://github.com/Peterxyjz/ChatGroup.git
    ```

2. Chuyển đến thư mục của dự án:

    ```sh
    cd ChatGroup
    ```

3. Cài đặt các gói phụ thuộc:

    ```sh
    npm install
    ```

4. Chạy ứng dụng:

    ```sh
    npm start
    ```

5. Mở trình duyệt và truy cập vào `http://localhost:3000` để xem ứng dụng.

## Sử dụng

- Truy cập `http://localhost:3000` để vào giao diện chính.
- Nhập tên người dùng và chọn phòng chat để bắt đầu trò chuyện.
- Gửi tin nhắn và xem các tin nhắn thời gian thực từ những người dùng khác trong cùng phòng chat.

## Công nghệ sử dụng

- [Express.js](https://expressjs.com/)
- [Socket.IO](https://socket.io/)
- [Node.js](https://nodejs.org/)

## Đóng góp

Chúng tôi hoan nghênh các đóng góp từ cộng đồng. Nếu bạn có ý tưởng, lỗi phát hiện hoặc cải tiến, hãy tạo một pull request hoặc mở một issue mới.

1. Fork dự án.
2. Tạo nhánh mới: `git checkout -b feature/YourFeature`
3. Commit các thay đổi của bạn: `git commit -m 'Add some feature'`
4. Push lên nhánh: `git push origin feature/YourFeature`
5. Mở một pull request.

## Giấy phép

Dự án này được cấp phép dưới giấy phép MIT - xem tệp [LICENSE](LICENSE) để biết thêm chi tiết.
