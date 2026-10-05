#Các loại `type` của ``<input>``
| `type`           | Công dụng                     | Ví dụ                           |
| ---------------- | ----------------------------- | ------------------------------- |
| `text`           | Nhập văn bản                  | `<input type="text">`           |
| `password`       | Nhập mật khẩu, ký tự bị che   | `<input type="password">`       |
| `email`          | Nhập email                    | `<input type="email">`          |
| `number`         | Nhập số                       | `<input type="number">`         |
| `tel`            | Nhập số điện thoại            | `<input type="tel">`            |
| `url`            | Nhập URL                      | `<input type="url">`            |
| `search`         | Ô tìm kiếm                    | `<input type="search">`         |
| `date`           | Chọn ngày                     | `<input type="date">`           |
| `time`           | Chọn giờ                      | `<input type="time">`           |
| `datetime-local` | Chọn ngày + giờ               | `<input type="datetime-local">` |
| `checkbox`       | Chọn nhiều lựa chọn           | `<input type="checkbox">`       |
| `radio`          | Chọn một trong nhiều lựa chọn | `<input type="radio">`          |
| `file`           | Chọn file                     | `<input type="file">`           |
| `submit`         | Nút gửi form                  | `<input type="submit">`         |
| `reset`          | Xóa/reset form                | `<input type="reset">`          |
| `button`         | Nút thông thường              | `<input type="button">`         |
| `hidden`         | Dữ liệu ẩn                    | `<input type="hidden">`         |
| `color`          | Chọn màu                      | `<input type="color">`          |
| `range`          | Thanh kéo                     | `<input type="range">`          |
3. radio
Dùng khi chỉ chọn một:

<input type="radio" name="gender" value="male"> Nam
<input type="radio" name="gender" value="female"> Nữ

Ở đây hai radio phải có cùng name:
name="gender"
Nếu chọn Nam:
gender=male
# <fieldset> tự tạo một khung viền:

┌──── Phần A — Kiến thức HTML (4 điểm) ─────┐  
│                                            │
│  Nội dung                                  │
│                                            │
└────────────────────────────────────────────┘

# <legend> chính là phần chữ đè lên đường viền:

<legend>Phần A — Kiến thức HTML (4 điểm)</legend>

4. &lt; và &gt; nghĩa là gì?
| Viết trong HTML | Hiển thị |
| --------------- | -------- |
| `&lt;`          | `<`      |
| `&gt;`          | `>`      |
| `&amp;`         | `&`      |
| `&quot;`        | `"`      |
#<textarea placeholder="Nhập câu trả lời của em..."></textarea>
--> nhập câu trả lời dạng nhiều dòng  <--
