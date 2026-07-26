# 📝 BÀI TẬP VỀ NHÀ - CSS CƠ BẢN

## Chủ đề

Thiết kế **Personal Card** bằng HTML và CSS.

---

## Yêu cầu

Tạo **2 file**:

- `index.html`
- `style.css`

Liên kết CSS bằng **External CSS**.

---

## Giao diện mẫu

Thiết kế một **Personal Card** có các thành phần sau:

- Ảnh đại diện hình tròn.
- Họ và tên (viết in hoa).
- Nghề nghiệp.
- Thông tin cá nhân:
  - Địa chỉ.
  - Trường học.
  - Sở thích.
- 3 kỹ năng hiển thị dạng thẻ (Tag).
- 2 nút:
  - **Follow**
  - **Message**

---

## Hướng dẫn thực hiện

### 1. Reset CSS

Áp dụng Reset CSS cho toàn bộ trang:

- `margin: 0`
- `padding: 0`
- `box-sizing: border-box`

---

### 2. Thiết kế phần Body

- Đặt màu nền xám nhạt.
- Sử dụng font chữ `Arial`.
- Căn giữa nội dung theo chiều ngang.
- Không sử dụng Flexbox hoặc Grid để căn giữa.

---

### 3. Thiết kế Card

Card cần có:

- Chiều rộng khoảng **350px**.
- Nền màu trắng.
- Viền màu xám.
- Bo góc lớn (`border-radius`).
- Khoảng đệm (`padding`) hợp lý.
- Khoảng cách với mép trang bằng `margin`.

---

### 4. Ảnh đại diện

- Kích thước **150px × 150px**.
- Bo tròn thành hình tròn (`border-radius: 50%`).
- Có viền màu xanh.
- Cách phần tên một khoảng bằng `margin-bottom`.

---

### 5. Họ và tên

Yêu cầu:

- Màu xanh đậm.
- Chữ in hoa (`text-transform`).
- Chữ đậm.
- Kích thước khoảng `2rem`.

---

### 6. Nghề nghiệp

- Màu xám.
- Chữ nghiêng (`font-style: italic`).
- Kích thước khoảng `1.1rem`.

---

### 7. Thông tin cá nhân

Bao gồm:

- Địa chỉ
- Trường học
- Sở thích

Mỗi dòng:

- Có khoảng đệm (`padding`).
- Có đường kẻ dưới (`border-bottom`).
- Căn giữa nội dung.

---

### 8. Kỹ năng

Hiển thị 3 kỹ năng dưới dạng các thẻ (Tag).

Mỗi thẻ cần:

- Viền màu xanh.
- Chữ màu xanh.
- Bo góc lớn.
- Khoảng cách giữa các thẻ.
- Sử dụng `display: inline-block`.

Ví dụ:

- HTML
- CSS
- JavaScript

---

### 9. Hai nút chức năng

Tạo hai nút:

- Follow
- Message

Yêu cầu:

- Kích thước giống nhau.
- Có bo góc.
- Chữ in đậm.
- Không gạch chân.
- Sử dụng `display: inline-block`.

Nút **Follow**

- Nền màu xanh.
- Chữ màu trắng.

Nút **Message**

- Nền màu trắng.
- Viền màu xanh.
- Chữ màu xanh.

---

## Kiến thức cần áp dụng

Trong bài làm cần sử dụng các thuộc tính CSS sau:

- Reset CSS (`margin`, `padding`, `box-sizing`)
- `background-color`
- `color`
- `font-family`
- `font-size`
- `font-weight`
- `font-style`
- `text-align`
- `text-transform`
- `width`
- `height`
- `border`
- `border-radius`
- `padding`
- `margin`
- `display: block`
- `display: inline-block`

Sử dụng các đơn vị:

- `px`
- `%`
- `em`
- `rem`

---

## Lưu ý

- Giao diện cân đối và dễ nhìn.
- Các khoảng cách (`margin`, `padding`) hợp lý.
- Không sử dụng **Flexbox**, **Grid** hoặc các thư viện CSS như Bootstrap, Tailwind,...
- Khuyến khích phối màu đẹp và trình bày sạch sẽ.
- Đặt tên class rõ ràng (ví dụ: `.card`, `.avatar`, `.info`, `.skill`, `.btn`).
