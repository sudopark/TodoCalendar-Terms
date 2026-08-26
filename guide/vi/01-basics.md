# 1. Kiến thức cơ bản

[← Mục lục](./README.md)

---

## Màn hình lịch

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/vi/calendar.png" alt="Lịch" width="280">

Mở ứng dụng là thấy ngay lịch của tháng này. Vuốt sang trái hoặc phải để chuyển tháng, chạm vào một ngày để mở danh sách sự kiện của ngày đó ở bên dưới.

- Mỗi ô ngày hiển thị từng sự kiện bằng một vệt màu, và khi một ngày có nhiều sự kiện hơn chỗ hiển thị thì **+N** cho biết còn bao nhiêu.
- Thứ tự danh sách trong ngày: việc cần làm không có thời gian → việc cần làm có thời gian → lịch trình → ngày lễ → sự kiện của lịch bên ngoài.
- Chạm vào phần đầu màn hình để nhảy tới ngày bất kỳ, hoặc dùng **Di chuyển ngày** để chọn trực tiếp.

Mỗi ngày hiện chi tiết đến đâu là do bạn quyết định: lượng thông tin của từng sự kiện, cỡ chữ, màu sắc, tên ngày lễ, cho tới âm lịch. [Cá nhân hóa](./05-personalization.md) gọi tên từng cài đặt một.

---

## Việc cần làm và lịch trình

Ứng dụng có hai loại sự kiện, khác nhau ở chỗ đó có phải là việc bạn đánh dấu cho xong hay không.

| | Việc cần làm | Lịch trình |
|---|---|---|
| Thời gian | Tùy chọn | Bắt buộc |
| Hoàn thành | Có — đánh dấu để hoàn thành | Không |
| Khi không có thời gian | Ở lại trong **Việc cần làm hiện tại** cho đến khi bạn xong | Không thể tạo |

**Việc cần làm không có thời gian** dành cho những thứ bạn phải làm sớm nhưng chưa xếp lịch. Nó nằm ở đầu màn hình lịch và trong tiện ích Việc cần làm hiện tại cho tới khi bạn hoàn thành.

Bạn có thể chuyển đổi qua lại bất cứ lúc nào — **Chuyển thành lịch trình** / **Chuyển thành việc cần làm** trong menu tùy chọn của sự kiện. Chỉ khi chuyển việc cần làm thành lịch trình mới cần điền thời gian.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/vi/event-detail.png" alt="Chi tiết sự kiện" width="280">

Mỗi sự kiện đều có thể mang theo **Vị trí**, **Liên kết** và **Ghi chú**. Vị trí kèm xem trước bản đồ và mở bằng một chạm trong ứng dụng bản đồ bạn thích; liên kết cũng có xem trước riêng.

---

## Thêm sự kiện

Có ba cách thêm sự kiện, tùy vào việc bạn muốn nhập nhiều hay ít:

- **Thêm nhanh** — ô nhập ở cuối danh sách của ngày. Gõ tên rồi nhấn xuống dòng là việc cần làm được tạo.
- **Nhập chi tiết** — chạm **+** để mở trình soạn với thời gian, lặp lại, nhắc nhở, loại sự kiện, vị trí, liên kết và ghi chú.
- **Nhập nhanh AI** — mô tả bằng ngôn ngữ thường ngày và để ứng dụng dựng sự kiện giúp bạn. Xem [Nhập nhanh AI](./02-ai-input.md).

Việc cần làm chỉ cần một cái tên. Lịch trình cần tên và thời gian.

---

## Sự kiện lặp lại

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/vi/repeat-options.png" alt="Tùy chọn lặp lại" width="240">

Thay vì bắt bạn ghép một quy tắc từ các danh sách thả xuống, ứng dụng đọc ngày bạn đã chọn và đưa ra sẵn những lựa chọn hợp với ngày đó. Chọn một Thứ Năm thì danh sách đưa ra **Mỗi Thứ Năm** và **Thứ Năm thứ ba của mỗi tháng**.

**Chu kỳ thường dùng**

- Mỗi ngày
- Mỗi tuần · Mỗi 2 tuần · Mỗi 3 tuần · Mỗi 4 tuần — vào cùng thứ trong tuần với sự kiện
- Mỗi tháng — vào cùng ngày mỗi tháng
- Mỗi năm
- Mỗi năm (âm lịch) — cho sinh nhật và ngày kỷ niệm tính theo âm lịch

**Theo vị trí trong tháng**

- Mỗi ngày trong tuần — từ Thứ Hai đến Thứ Sáu. Xuất hiện khi sự kiện bắt đầu vào ngày thường
- Tất cả các ngày của tuần cuối mỗi tháng
- **Thứ Năm** đầu tiên / thứ hai / thứ ba / thứ tư / cuối cùng của mỗi tháng — chỗ ghi thứ được điền từ ngày bạn chọn, nên sự kiện rơi vào Thứ Sáu sẽ thành **Thứ Sáu cuối cùng của mỗi tháng**

**Kết thúc lặp lại**

Chọn kiểu lặp lại xong, bạn quyết định luôn khi nào nó dừng: **Không bao giờ** để lặp mãi, **Vào ngày** để ấn định ngày kết thúc, hoặc **Sau** một số **lần** nhất định.

Việc cần làm lặp lại hoạt động khác với lịch trình lặp lại:

- Một lần lặp chưa hoàn thành vẫn hiện trên lịch hôm nay ngay cả khi đã qua giờ — nó không tự nhảy sang lần kế tiếp.
- Hoàn thành nó sẽ đưa lần đó vào danh sách việc đã hoàn thành và tạo ra lần kế tiếp.
- **Bỏ qua việc cần làm này** đưa bạn sang lần kế tiếp mà không đánh dấu hoàn thành.
- Khi kiểu lặp lại có điều kiện kết thúc và không còn lần nào tiếp theo, chuỗi lặp lại sẽ kết thúc.

Khi bạn chỉnh sửa hoặc xóa một lần của sự kiện lặp lại, bạn sẽ chọn phạm vi: **Chỉ lần này**, **Từ lần này trở đi**, hoặc **Tất cả sự kiện**.

Với sự kiện nằm trên lịch bên ngoài đã kết nối, tùy chọn âm lịch không xuất hiện — lịch bên ngoài không có chỗ để lưu quy tắc lặp lại theo âm lịch.

---

## Loại sự kiện và màu sắc

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/vi/event-type-list.png" alt="Loại sự kiện" width="280">

Loại sự kiện là cách phân nhóm của riêng bạn, và nó quyết định màu mà sự kiện hiện trên lịch. Hãy tạo bao nhiêu tùy thích, mỗi loại một màu riêng.

- Tắt một loại đi là mọi sự kiện thuộc loại đó biến khỏi lịch — rất tiện khi muốn tạm im một lịch công việc dày đặc mà không cần ngắt kết nối.
- Khi xóa một loại, bạn được chọn giữ lại hay xóa luôn các sự kiện gắn với nó.
- Đặt **Loại sự kiện mặc định** để sự kiện mới rơi đúng chỗ mà không phải chọn lại mỗi lần.

Ngày lễ và các lịch bên ngoài đã kết nối đều có loại riêng, nên bạn cũng có thể ẩn chúng độc lập.

---

## Nhắc nhở sự kiện

Bạn có thể đặt bao nhiêu nhắc nhở cho mỗi sự kiện tùy nhu cầu.

- **Sự kiện có thời gian** — vào thời điểm diễn ra sự kiện, hoặc trước 1 / 5 / 10 / 15 / 30 phút, 1 / 2 giờ, 1 / 2 / 7 ngày.
- **Sự kiện cả ngày** — lúc 9 giờ sáng hoặc giữa trưa hôm đó, hoặc lúc 9 giờ sáng của 1 / 2 / 7 ngày trước.
- **Tùy chỉnh** — chọn bất kỳ mốc nào bạn muốn.

Giá trị mặc định cho sự kiện có thời gian và sự kiện cả ngày được đặt riêng trong Cài đặt, nên sự kiện mới đã có sẵn nhắc nhở. Nhắc nhở cần quyền thông báo; nếu quyền đang tắt, ứng dụng sẽ chỉ đường sang Cài đặt của iOS.

---

## Sự kiện quan trọng nhất

Hãy ghim thứ duy nhất bạn không được phép bỏ lỡ. Sự kiện quan trọng nhất luôn nằm ở đầu màn hình lịch dù bạn đang xem ngày nào, và nó có tiện ích riêng.

Việc cần làm và lịch trình không lặp lại đều đặt làm sự kiện quan trọng nhất được. Lịch trình lặp lại thì không.

---

## Việc chưa hoàn thành

Những việc cần làm đã qua giờ mà chưa được hoàn thành sẽ được gom vào mục **Việc chưa hoàn thành** ở đầu màn hình lịch, để việc bị bỏ lỡ không nằm chìm ở một ngày đã qua.

Việc cần làm không có thời gian và việc của tương lai không bị tính là chưa hoàn thành — đơn giản là chúng chưa tới hạn. Nếu không muốn thấy mục này, bạn có thể ẩn hẳn nó trong Cài đặt.

---

## Việc đã hoàn thành

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/vi/done-todos.png" alt="Việc đã hoàn thành" width="280">

Mọi thứ bạn đánh dấu xong đều được giữ lại, nhóm theo thời điểm bạn hoàn thành — hôm nay, hôm qua, tháng này, rồi tới theo tháng và theo năm.

- Hoàn tác một lần hoàn thành để đưa việc cần làm quay lại.
- Dọn hàng loạt cũng được: xóa **Tất cả việc cần làm đã hoàn thành**, hoặc chỉ những mục **Cũ hơn 1 tháng / 3 tháng / 6 tháng / 1 năm**.

---

## Chia sẻ

Chia sẻ **một ngày, một tuần hoặc một tháng** dưới dạng văn bản hoặc thẻ hình ảnh.

Trước khi chia sẻ, bạn có thể lọc những loại sự kiện muốn đưa vào và chọn có hiển thị tên loại hay không, nhờ vậy gửi được lịch tuần của mình mà không phơi bày mọi thứ trong đó.

---

[← Mục lục](./README.md) · [Tiếp theo: Nhập nhanh AI →](./02-ai-input.md)
