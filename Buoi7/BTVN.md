# 📝 BÀI TẬP VỀ NHÀ - CRUD QUẢN LÝ MÔN HỌC

## 🎯 Chủ đề

Xây dựng ứng dụng **Quản lý môn học** bằng **HTML, CSS và JavaScript DOM**.

Ứng dụng cho phép người dùng thêm, hiển thị, sửa và xóa môn học.

##  Yêu cầu

Tạo **3 file**:

* `index.html`
* `style.css`
* `index.js`

Sử dụng **External CSS** để liên kết file `style.css` với `index.html`.

Sử dụng **External JavaScript** để liên kết file `index.js` với `index.html`.

##  Giao diện

Giao diện cần có:

* Tiêu đề **Quản lý môn học**.
* Ô input để nhập tên môn học.
* Button **Thêm**.
* Tiêu đề **Danh sách môn học**.
* Danh sách các môn học.
* Mỗi môn học có 2 button:

  * **Sửa**
  * **Xóa**

Có thể sử dụng màu sắc để giao diện rõ ràng và dễ sử dụng.

##  Chức năng CRUD

### C - Create: Thêm môn học

Khi người dùng nhập tên môn học và nhấn **Thêm**:

* Lấy giá trị từ input.
* Kiểm tra input có bị để trống hay không.
* Nếu để trống → thông báo cho người dùng.
* Nếu có dữ liệu → tạo một phần tử `<li>` mới.
* Hiển thị tên môn học lên danh sách.
* Tạo button **Sửa**.
* Tạo button **Xóa**.
* Thêm môn học vào `<ul>`.
* Sau khi thêm thành công, xóa nội dung trong input.

### R - Read: Hiển thị danh sách

Hiển thị toàn bộ các môn học đã được thêm vào danh sách.

Mỗi môn học cần có dạng:

```text
Tên môn học                    Sửa    Xóa
```

Ví dụ:

```text
Kỹ thuật lập trình             Sửa    Xóa
Toán rời rạc                   Sửa    Xóa
Cơ sở dữ liệu                  Sửa    Xóa
```

### U - Update: Sửa môn học

Khi nhấn button **Sửa**:

* Cho phép người dùng nhập tên môn học mới.
* Kiểm tra tên môn học mới không được để trống.
* Cập nhật tên môn học trên giao diện.
* Không tạo thêm một môn học mới.

Ví dụ:

```text
Tên cũ:
Kỹ thuật lập trình

Tên mới:
Lập trình C++
```

Sau khi sửa:

```text
Lập trình C++                  Sửa    Xóa
```

### D - Delete: Xóa môn học

Khi nhấn button **Xóa**:

* Hiển thị thông báo xác nhận.
* Nếu người dùng đồng ý → xóa môn học khỏi danh sách.
* Nếu người dùng không đồng ý → giữ nguyên môn học.

## 💻 Kiến thức JavaScript cần sử dụng

Trong bài làm, áp dụng các kiến thức DOM đã học:

* `document.getElementById()`
* `document.createElement()`
* `textContent`
* `className`
* `value`
* `appendChild()`
* `removeChild()`
* `addEventListener()`

Có thể sử dụng:

```javascript
input.value
```

để lấy dữ liệu từ input.

Có thể sử dụng:

```javascript
document.createElement()
```

để tạo phần tử HTML bằng JavaScript.

Có thể sử dụng:

```javascript
appendChild()
```

để thêm phần tử vào DOM.

Có thể sử dụng:
```javascript
removeChild()
```
để xóa phần tử khỏi DOM.
## 🎨 Yêu cầu CSS
Sử dụng CSS để thiết kế giao diện.

Có thể sử dụng:
* `margin`
* `padding`
* `width`
* `height`
* `background`
* `color`
* `font-size`
* `font-family`
* `border`
* `border-radius`
* `display`
* `gap`
Không bắt buộc sử dụng:
* Framework CSS.
* Bootstrap.
* Tailwind CSS.
##  Yêu cầu kiểm tra dữ liệu
Không cho phép thêm môn học khi input rỗng.
Ví dụ:
```text
Input:
""
Kết quả:
Vui lòng nhập tên môn học
```
Khi sửa cũng không được để tên môn học rỗng.
##  Mục tiêu
Sau khi hoàn thành bài tập, sinh viên có thể:
* Hiểu khái niệm CRUD.
* Biết cách lấy phần tử HTML bằng JavaScript.
* Biết cách tạo phần tử HTML bằng DOM.
* Biết cách thêm phần tử vào DOM.
* Biết cách xóa phần tử khỏi DOM.
* Biết cách thay đổi nội dung phần tử.
* Biết cách xử lý sự kiện `click`.
* Biết cách lấy dữ liệu từ input.
* Biết cách xây dựng một ứng dụng CRUD đơn giản bằng JavaScript.

