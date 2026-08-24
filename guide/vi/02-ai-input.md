# 2. Nhập nhanh AI

[← Mục lục](./README.md)

---

Hãy mô tả điều bạn muốn bằng ngôn ngữ thường ngày và ứng dụng sẽ dựng nó giúp bạn — "ăn trưa với Sara thứ Sáu lúc 12 giờ", "dời lịch nha sĩ sang thứ Ba tuần sau", "đánh dấu đã giặt đồ xong". Không biểu mẫu, không phải xoay bánh xe chọn ngày.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ai-input.png" alt="Nhập nhanh AI" width="280">

Nhập nhanh AI cần một tài khoản đã đăng nhập. Mọi thứ khác trong ứng dụng đều dùng được mà không cần tài khoản.

---

## AI làm được gì

- Tạo việc cần làm và lịch trình, với thời gian, kiểu lặp lại và loại sự kiện được suy ra từ điều bạn nói
- Thay đổi một sự kiện có sẵn — dời nó, đổi tên, đổi giờ
- Hoàn thành một việc cần làm, hoặc hoàn tác hoàn thành
- Xóa một sự kiện
- Xử lý nhiều thứ trong một yêu cầu ("thêm buổi tập thứ Hai, thứ Tư và thứ Sáu lúc 7 giờ sáng")

---

## Các cách gửi yêu cầu

### Trong ứng dụng

Chạm nút AI trên màn hình lịch. Bảng nhập mở ra với hai chế độ mà bạn có thể chuyển qua lại bất cứ lúc nào:

- **Giọng nói** — nói và xem nội dung nhận dạng hiện lên theo thời gian thực. Cần quyền micro và nhận dạng giọng nói; nếu một trong hai bị từ chối, ứng dụng sẽ mời bạn mở Cài đặt của iOS hoặc chuyển sang **Nhập bằng bàn phím**.
- **Bàn phím** — gõ trực tiếp. Hữu ích khi bạn đang ở nơi không tiện nói.

### Từ hình ảnh

**Đọc từ hình ảnh** biến một tấm ảnh thành sự kiện. Hãy **Chụp ảnh** hoặc **Chọn từ thư viện**; ứng dụng đọc chữ trên đó — thời khóa biểu, áp phích sự kiện, ảnh chụp màn hình một tin nhắn — rồi cho bạn xem những gì nó tìm được để bạn sửa chỗ nào sai trước khi gửi.

Bạn có thể kèm theo **Chỉ dẫn thêm (tùy chọn)** để hướng kết quả, kiểu như "thêm những mục này dưới dạng việc cần làm". Nếu trong ảnh không có chữ nào đọc được, ứng dụng sẽ nói cho bạn biết thay vì gửi đi một yêu cầu rỗng.

### Siri

Hãy nói **"Thêm bằng AI trong To-do Calendar"** — hoặc "Thêm lịch trình trong To-do Calendar" / "Thêm việc cần làm trong To-do Calendar". Siri hỏi bạn muốn thêm gì, và yêu cầu chạy **ở chế độ nền mà không cần mở ứng dụng**. Siri đáp "Đã nhận. Tôi sẽ báo cho bạn khi xong", rồi bạn nhận được thông báo khi có kết quả.

### Nút Hành động

Gán nút Hành động cho phím tắt **Thêm bằng AI**. Bấm một lần, nói điều cần nói, xong — ứng dụng thậm chí không cần hiện ra.

### Tiện ích và Trung tâm điều khiển

- **Tiện ích Thêm bằng AI** — một tiện ích trên Màn hình chính hoặc Màn hình khóa, chạm một lần là mở màn hình nhập AI.
- **Trung tâm điều khiển** (iOS 18 trở lên) — thêm chính điều khiển đó vào Trung tâm điều khiển để có lối vào chỉ bằng một cú vuốt xuống.

### Bảng chia sẻ

Chia sẻ **văn bản hoặc hình ảnh từ bất kỳ ứng dụng nào khác** thẳng tới AI của To-do Calendar. Đang đọc tin nhắn có thông tin về một buổi hẹn, hay đang xem một tấm áp phích trong Ảnh — chỉ cần chạm chia sẻ, chọn To-do Calendar, thêm chỉ dẫn nếu muốn, rồi gửi.

Yêu cầu từ bảng chia sẻ cũng chạy ở chế độ nền. Bạn sẽ nhận được xác nhận là đã gửi, còn kết quả thì xem trong ứng dụng.

---

## Một yêu cầu được xử lý ra sao

1. **Gửi** — yêu cầu của bạn lên đường. Nếu nó đến từ Siri, nút Hành động hay bảng chia sẻ, bạn không cần giữ ứng dụng mở.
2. **Đang xử lý** — ứng dụng hiển thị tiến trình. Bạn có thể **Dừng** một yêu cầu đang chạy, nhưng dừng lại sẽ hủy phần việc đang làm dở và không thể tiếp tục.
3. **Cần xác nhận** — nếu yêu cầu sẽ thay đổi điều gì đó đáng kể, ứng dụng xin bạn phê duyệt trước và cho xem chính xác nó sắp làm gì. Có một đồng hồ đếm ngược; nếu hết giờ thì bạn chỉ cần yêu cầu lại.
4. **Hoàn thành** — kết quả xuất hiện ngay trên lịch của bạn, kèm tóm tắt những gì đã thay đổi.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ai-result.png" alt="Kết quả AI" width="280">

Mỗi lần chỉ có một yêu cầu được chạy. Nếu bạn gửi thêm một yêu cầu trong khi yêu cầu trước còn đang chờ bạn phê duyệt, ứng dụng sẽ nhắc bạn xử lý cái trước đã.

---

## Tín dụng

Các yêu cầu AI dùng **hạn mức hằng ngày, được đặt lại mỗi ngày**. Phần còn lại hiển thị ở đầu màn hình nhập AI, nên bạn luôn biết mình còn bao nhiêu trước khi gửi.

Nếu hạn mức cạn, nhập nhanh AI tạm nghỉ cho tới lần đặt lại kế tiếp. Mọi thứ khác trong ứng dụng vẫn chạy bình thường.

---

## Những quyền ứng dụng có thể xin

| Quyền | Dùng cho |
|---|---|
| Micro + Nhận dạng giọng nói | Nhập bằng giọng nói |
| Camera | Chụp ảnh cho **Đọc từ hình ảnh** |
| Thư viện ảnh | Chọn một ảnh có sẵn |
| Thông báo | Báo cho bạn kết quả của yêu cầu chạy nền |

Mỗi quyền chỉ được hỏi khi bạn dùng tính năng cần nó lần đầu, và không có quyền thì ứng dụng vẫn chạy — nhập bằng giọng nói lùi về bàn phím, nhập từ hình ảnh lùi về gõ tay.

---

[← Mục lục](./README.md) · [Tiếp theo: Tiện ích và Màn hình khóa →](./03-widgets.md)
