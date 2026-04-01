Dùng AI : ChatGPT

Lệnh ( Prompt ) : Hãy làm giúp tôi CSS đơn giản cho trang web có các phần QuocGia, navigation, NoiDung; giao diện giống Apple với thanh trên nền xám , menu ngang có khoảng cách, nội dung căn giữa gồm tiêu đề lớn, mô tả màu xám nhạt, hai  nút bo tròn (Learn more màu xanh nước biển, Buy màu xám nhạt ), ảnh nằm dưới, code ngắn gọn dễ hiểu, không thay đổi HTML.
Kết quả của AI ChatGPT :
/* Reset cơ bản */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
}

/* Thanh chọn quốc gia */
.quocgia {
  background: #f5f5f7;
  text-align: center;
  padding: 8px;
  font-size: 14px;
  color: #333;
}

/* Navigation */
.nav {
  background: #f5f5f7;
  display: flex;
  justify-content: center;
  gap: 30px;
  padding: 12px 0;
  font-size: 14px;
}

.nav a {
  text-decoration: none;
  color: #333;
}

.nav a:hover {
  color: black;
}

/* Nội dung chính */
.noidung {
  text-align: center;
  padding: 60px 20px;
}

/* Tiêu đề lớn */
.noidung h1 {
  font-size: 48px;
  font-weight: 600;
  margin-bottom: 10px;
}

/* Mô tả */
.noidung p {
  font-size: 20px;
  color: #6e6e73;
  margin-bottom: 25px;
}

/* Nhóm nút */
.buttons {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-bottom: 40px;
}

/* Nút chung */
.buttons a {
  padding: 10px 20px;
  border-radius: 20px;
  font-size: 14px;
  text-decoration: none;
}

/* Nút Learn more (xanh) */
.learn {
  background: #0071e3;
  color: white;
}

/* Nút Buy (xám nhạt) */
.buy {
  background: #e8e8ed;
  color: black;
}

/* Ảnh */
.noidung img {
  max-width: 100%;
  height: auto;
}
