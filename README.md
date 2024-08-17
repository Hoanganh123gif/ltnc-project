Giới thiệu game

video giói thiệu game:

Jack adventure là game thuộc thể loại giải trí. Trong game bạn sẽ được vào vai jack để phưu lưu và tránh những con quái vật.

0. Cách tải game

1. Tính năng game 

2. Bắt đầu game

3. Hướng dẫn chơi game 

a. Về nhân vật 

b. Cơ chế chơi 

c.Quái vật 

d. Tính điểm 

4. Về source code game
5. Về tài nguyên trong game

0. Cách tải game

a. Cách 1: Không bao gồm code 

Tải game tại link github:

Sau đó giải nén vào game vào thư mục bất kì và vào folder debug vào JackAdventure.exe để khới động game.

b. Cách 2:Bao gồm code và có thể biên dịch

B1: Tải link source code tại:

B2: Tải visual studio. Ở đây mình dùng visual studio 2022

B3: Vào visual stuidio chạy vào thư mục source để chạy code game 

1. Tính năng game 

Có âm thanh sinh động khi vào game. 

Màn hình menu có tính năng bật tắt âm thanh khi vào game.

Cơ chế bảng xếp hạng điểm của game được cập nhật sau mỗi lần chơi. 

Nhân vật chính có các hành động và âm thanh sinh động.

Background game ấn tượng.

2. Bắt đầu game
   
   Khi khởi động game màn hình sẽ có như hình dưới 
   ![image](https://github.com/user-attachments/assets/34d0eead-933d-4669-9308-eea89f6e1e02)
   
   
   Chọn biểu tượng ![image](https://github.com/user-attachments/assets/9605327b-feb2-422a-a6ed-e81bc39b315d) để vào game hoặc chọn ![image](https://github.com/user-attachments/assets/d7d8a3cb-5e8c-4633-8995-44d18c6bf178) để xem bảng xếp hạng ba điểm cao nhất.
3. Hướng dẫn chơi game

   Sau khi nhấn biểu tượng trên, người chơi sẽ vào chơi game. Điều bạn chú ý là điểm số của game ![image](https://github.com/user-attachments/assets/5a27866c-1c16-4f71-bac0-0d4e9a0d1ddd) được hiện lên màn hình.

   a. Về nhân vật

    Các phím điều khiển
    Jump: Space.

    Left: A.

    Right: D.

   B. Cơ chế chơi
    
   Mỗi khi gặp quái vật bạn  chỉ cần nhấn nút space để nhảy lên để tránh né những con quái vật ![image](https://github.com/user-attachments/assets/1a5535df-f4df-4c75-b264-4266a691c18f) hoặc nhấn nút A hoặc D để di chuyển nhanh hơn tránh để con boss sau lưng bắt kịp bạn.
   
   Bạn cũng có thể nhấn tổ hợp nút space kết hợp với tổ hợp phím A Hoặc D để nhảy sang trái hoặc sang phải.

4. Về source code game

   Source code game được sắp xếp và nằm trong source
   
   Tổng quát về file source:

   gamme manager: File này định nghĩa một lớp ResourceManager trong C++ dùng để quản lý các tài nguyên (textures, fonts, sounds, music) trong trò chơi. Mỗi loại tài nguyên được lưu trữ trong một std::map, cho phép truy cập, thêm, xóa, và lấy tài nguyên dễ dàng.

   game object: File này bao gồm các mã định nghĩa một lớp Animation trong C++ để quản lý và điều khiển hoạt ảnh (animation) của các đối tượng trong trò chơi sử dụng thư viện SFML. Lớp này xử lý việc chia một tấm hình (sprite sheet) thành nhiều khung hình và chuyển đổi qua lại giữa các khung hình để tạo hiệu ứng hoạt ảnh.

   game state manager: File nay bao gồm các mã để cài đặt các nút setting trong game bao gồm: điểm số, end và một số các cài đặt khác.

5. Tài nguyên trong game

   Forder chứa các tài nguyên trong game: Data.
   
   Bao gồm các hình animation và âm thanh của game.
   
     



