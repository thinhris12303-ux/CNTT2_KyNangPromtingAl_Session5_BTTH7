# Kế hoạch Tổ chức Sự kiện: AI Innovation Day

- **Quy mô:** 150 sinh viên (cố định)
- **Thời gian:** 1 ngày (08:00 – 17:00)
- **Ngân sách tối đa:** 15.000.000 VNĐ
- **Nhân sự tổ chức:** 10 người (`NS-01` đến `NS-10`)
- **Mục tiêu:** Giúp sinh viên hiểu và trải nghiệm ứng dụng AI trong học tập và công việc

---

## 1. Bộ Prompt hoàn chỉnh (Chain-of-Thought + Prompt Chaining + Context Management)

### Prompt 1 — Phân tích tính khả thi & Rủi ro (Chain-of-Thought)
```text
Vai trò: Chuyên gia quản trị dự án sự kiện đại học.
Dữ liệu gốc: Sự kiện "AI Innovation Day", 150 sinh viên, 1 ngày, ngân sách tối đa 15.000.000 đồng, 10 nhân sự BTC. Mục tiêu: giúp sinh viên hiểu và trải nghiệm ứng dụng AI trong học tập và công việc.
Yêu cầu: Hãy suy nghĩ từng bước một trước khi kết luận:
1. Kiểm tra tính khả thi về mặt bằng cho 150 sinh viên (+ BTC và khách mời).
2. Tính chi phí bình quân/sinh viên và xác định các hạng mục bắt buộc phải tối ưu để không vượt 15.000.000 đồng.
3. Đánh giá tỷ lệ nhân sự (10 người / 150 khách) và chỉ ra điểm nghẽn vận hành lớn nhất.
4. Liệt kê 3 rủi ro trọng yếu kèm giải pháp phòng ngừa cụ thể.
```

### Prompt 2 — Lập lịch trình 1 ngày & Dự toán ngân sách (Prompt Chaining)
```text
Dựa trên [KẾT QUẢ PROMPT 1], hãy xây dựng đồng thời 2 bảng liên kết chặt với nhau:
1. Lịch trình 1 ngày (08:00 – 17:00) gồm các phiên chia sẻ và thực hành AI, đảm bảo mọi hoạt động có trải nghiệm thực tế cho 150 sinh viên.
2. Bảng dự toán ngân sách chi tiết (Đơn vị tính, Số lượng, Đơn giá, Thành tiền, Tỷ lệ %).
Ràng buộc: Bắt buộc tính đủ suất Teabreak cho cả 150 SV + 10 BTC + khách mời; dành tối thiểu 5% (750.000 đồng) cho quỹ dự phòng; tổng cộng bằng chính xác 15.000.000 đồng.
```

### Prompt 3 — Phân công 10 nhân sự & Kế hoạch truyền thông (Prompt Chaining)
```text
Sử dụng [LỊCH TRÌNH & DỰ TOÁN TỪ PROMPT 2], hãy thiết kế:
1. Bảng phân công cho đúng 10 nhân sự (mã NS-01 đến NS-10), ghi rõ nhiệm vụ trước sự kiện và nhiệm vụ theo từng khung giờ trong ngày, đảm bảo phủ kín các điểm nghẽn đã nêu ở Prompt 1.
2. Kế hoạch truyền thông 14 ngày trước sự kiện (T-14 đến T-0) để đạt tối thiểu 180–190 đơn đăng ký, bảo đảm 150 sinh viên tham dự thực tế mà không phát sinh thêm chi phí quảng cáo.
```

### Prompt 4 — Tạo bản tóm tắt chuyển ngữ cảnh (Context Management)
```text
Hãy tổng hợp toàn bộ kế hoạch từ Prompt 1 đến Prompt 3 thành một "Bản tóm tắt ngữ cảnh dự án" ngắn gọn (dưới 250 từ) để tôi sao chép sang một hội thoại mới.
Bắt buộc giữ nguyên: 4 ràng buộc cứng (150 SV, 1 ngày, 15.000.000 đ, 10 nhân sự), các con số dự toán đã chốt, cấu trúc lịch trình chính và các điểm cần rà soát tiếp.
```

### Prompt 5 — Kiểm tra tính thống nhất & Hiệu chỉnh (Chạy ở hội thoại mới)
```text
Ngữ cảnh dự án: [DÁN BẢN TÓM TẮT NGỮ CẢNH TỪ PROMPT 4] và [TOÀN BỘ KẾ HOẠCH].
Hãy đóng vai Kiểm toán viên vận hành, suy nghĩ từng bước một (Chain-of-Thought) để rà soát chéo 4 tiêu chí:
1. Tổng ngân sách có vượt 15.000.000 đồng hoặc bỏ sót chi phí ẩn nào không?
2. Có khung giờ nào bị thiếu nhân sự trực hoặc một người phải làm 2 việc cùng lúc không?
3. Số lượng suất ăn, giải thưởng, ấn phẩm có khớp 150 SV + 10 BTC không?
4. Đề xuất các điểm hiệu chỉnh cụ thể nếu phát hiện mâu thuẫn.
```

---

## 2. Bản phân tích tính khả thi (Chain-of-Thought)

1. **Bước 1 — Sức chứa và mặt bằng:** Với 150 sinh viên cộng 10 nhân sự BTC và 5 khách mời (tổng 165 người), hội trường chuẩn 200 chỗ của trường đáp ứng tốt và miễn phí mặt bằng. Nếu phải thuê địa điểm ngoài, ngân sách 15.000.000 đồng sẽ không đủ.
2. **Bước 2 — Định mức chi phí bình quân:** Chia 15.000.000 đồng cho 150 sinh viên cho mức bình quân **100.000 đồng/sinh viên**. Sau khi trích 5% quỹ dự phòng (750.000 đồng), phần thực chi 14.250.000 đồng đủ trang trải âm thanh/ánh sáng, 3 diễn giả, in ấn, giải thưởng và Teabreak 30.000 đồng/suất.
3. **Bước 3 — Tải công việc của 10 nhân sự:** Tỷ lệ điều phối **1 BTC : 15 sinh viên** nằm trong ngưỡng an toàn. Điểm nghẽn lớn nhất nằm ở phiên thực hành AI buổi chiều khi 150 sinh viên cùng kết nối mạng và thao tác; cần bố trí riêng 2 nhân sự kỹ thuật trực tiếp hỗ trợ.
4. **Bước 4 — Đánh giá rủi ro và phương án phòng ngừa:**
   - *Rủi ro vắng mặt (no-show):* Mở form 190 suất đăng ký để bù hao hụt 15–20%.
   - *Rủi ro nghẽn Wi-Fi khi thực hành:* Trang bị bộ phát Wi-Fi dự phòng/4G và tài khoản AI mẫu.
   - *Rủi ro thiếu suất Teabreak:* Tính đủ 165 suất (150 SV + 10 BTC + 5 khách mời).

---

## 3. Lịch trình sự kiện theo khung giờ (08:00 – 17:00)

| Khung giờ | Hoạt động chính | Nội dung trọng tâm | Nhân sự trực | Hạng mục liên kết |
| :--- | :--- | :--- | :--- | :--- |
| 08:00 – 08:45 | Đón khách & Check-in | Quét QR điểm danh, phát thẻ tên, ổn định 150 SV | NS-01, NS-03, NS-04, NS-09 | Ấn phẩm check-in, Backdrop |
| 08:45 – 09:00 | Khai mạc chương trình | Giới thiệu mục tiêu ngày hội và 3 diễn giả khách mời | NS-01, NS-05, NS-06 | Âm thanh, ánh sáng hội trường |
| 09:00 – 10:15 | Keynote: AI trong học tập & nghề nghiệp | Dùng AI tổng hợp tài liệu, nghiên cứu và tự học | NS-05, NS-06, NS-07 | Quà tặng Diễn giả 1 |
| 10:15 – 10:40 | Teabreak & Networking | Nghỉ giải lao, giao lưu cùng diễn giả tại sảnh | NS-03, NS-04, NS-08 | 165 suất Teabreak |
| 10:40 – 12:00 | Tọa đàm: Kỹ năng làm việc cùng AI | AI viết code, phân tích dữ liệu và đạo đức AI | NS-02, NS-05, NS-07 | Quà tặng Diễn giả 2 & 3 |
| 12:00 – 13:30 | Nghỉ trưa tự túc | BTC kiểm tra đường truyền Wi-Fi và học liệu chiều | NS-06, NS-07, NS-10 | Vật tư vận hành |
| 13:30 – 15:15 | Workshop: Thực hành Prompt & Workflow | 150 SV thực hành giải quyết bài toán theo nhóm | NS-02, NS-06, NS-07, NS-08 | Học liệu số, Wi-Fi dự phòng |
| 15:15 – 16:30 | Mini-Challenge & Thuyết trình nhanh | 5 đội xuất sắc trình bày sản phẩm (5 phút/đội) | NS-01, NS-05, NS-09, NS-10 | Giải thưởng Nhất, Nhì, Ba |
| 16:30 – 17:00 | Trao giải, Khảo sát & Bế mạc | Trao thưởng, quét QR đánh giá và chụp ảnh lưu niệm | Toàn bộ 10 nhân sự | Quỹ dự phòng (nếu phát sinh) |

---

## 4. Bảng dự toán ngân sách (Tổng: 15.000.000 VNĐ)

| Hạng mục chi phí | ĐVT | SL | Đơn giá | Thành tiền | Tỷ lệ % | Ghi chú liên kết |
| :--- | :--- | ---: | ---: | ---: | ---: | :--- |
| Hỗ trợ kỹ thuật âm thanh, ánh sáng, Wi-Fi | Gói | 1 | 1.500.000 đ | 1.500.000 đ | 10,0% | Hội trường trường miễn phí mặt bằng |
| Quà tặng & tri ân Diễn giả khách mời | Người | 3 | 1.000.000 đ | 3.000.000 đ | 20,0% | Phiên Keynote sáng & Tọa đàm |
| Teabreak & nước uống giữa giờ | Suất | 165 | 30.000 đ | 4.950.000 đ | 33,0% | 150 SV + 10 BTC + 5 khách mời |
| Backdrop, Standee, Thẻ BTC & In ấn | Gói | 1 | 2.250.000 đ | 2.250.000 đ | 15,0% | Phục vụ check-in & nhận diện |
| Giải thưởng Mini-Challenge AI | Gói | 1 | 1.950.000 đ | 1.950.000 đ | 13,0% | Nhất 1.000k, Nhì 600k, Ba 350k |
| Vật tư vận hành, văn phòng phẩm, dây đeo | Gói | 1 | 600.000 đ | 600.000 đ | 4,0% | Bút, giấy note, pin micro, băng keo |
| Quỹ dự phòng rủi ro | Gói | 1 | 750.000 đ | 750.000 đ | 5,0% | Chỉ chi khi có sự cố phát sinh |
| **Tổng cộng dự toán** | | | | **15.000.000 đ** | **100,0%** | **Đạt đúng trần ngân sách 15 triệu** |

---

## 5. Bảng phân công 10 nhân sự (`NS-01` đến `NS-10`)

| Mã NS | Vai trò phụ trách | Nhiệm vụ trước sự kiện (T-14 đến T-1) | Nhiệm vụ trong ngày diễn ra |
| :--- | :--- | :--- | :--- |
| NS-01 | Trưởng ban tổ chức | Duyệt kế hoạch tổng thể, xin cấp phép hội trường, điều phối chung | Giám sát tiến độ, xử lý sự cố cấp cao, điều hành bế mạc |
| NS-02 | Phó BTC / Nội dung | Xây dựng kịch bản chương trình, đề bài Mini-Challenge và học liệu số | Điều phối nội dung tọa đàm, hướng dẫn thể lệ Workshop chiều |
| NS-03 | Thư ký & Thủ quỹ | Quản lý danh sách 190 đơn đăng ký, tạm ứng & giữ quỹ 15.000.000 đ | Quản lý bàn Check-in, phát thẻ, đối soát hóa đơn thực chi |
| NS-04 | Hậu cần & Teabreak | Đặt 165 suất Teabreak, mua vật tư văn phòng phẩm, in ấn Backdrop | Tiếp nhận Teabreak lúc 09:45, bố trí sảnh và thu dọn sau giờ nghỉ |
| NS-05 | Đối ngoại & Diễn giả | Mời và chốt slide 3 diễn giả, chuẩn bị 3 phần quà tri ân | Đón tiếp, hướng dẫn diễn giả, nhắc giờ (timekeeper) trên sân khấu |
| NS-06 | Kỹ thuật AV & Sân khấu | Kiểm tra hệ thống âm thanh, máy chiếu, micro hội trường trước 1 ngày | Vận hành âm thanh, slide, ghi hình toàn bộ các phiên chính |
| NS-07 | Kỹ thuật Mạng & AI Lab | Chuẩn bị bộ phát Wi-Fi dự phòng, tài khoản AI mẫu cho 150 SV | Hỗ trợ kết nối và xử lý lỗi công cụ cho các nhóm trong phiên chiều |
| NS-08 | Điều phối Hội trường | Lên sơ đồ chỗ ngồi 150 SV và phân khu làm việc nhóm | Hướng dẫn ổn định chỗ ngồi, hỗ trợ chia nhóm và phát học liệu |
| NS-09 | Truyền thông & Thiết kế | Thiết kế bộ nhận diện, chạy chuỗi bài đăng T-14 đến T-0 | Chụp ảnh sự kiện, cập nhật tin nhanh lên kênh truyền thông CLB |
| NS-10 | MC & Khảo sát | Viết kịch bản dẫn chương trình, tạo form QR đánh giá sau sự kiện | Dẫn dắt toàn bộ chương trình, điều phối phần Q&A và quét QR bế mạc |

---

## 6. Kế hoạch truyền thông trước sự kiện (T-14 đến T-0)

- **Giai đoạn 1 (T-14 đến T-10) — Khởi động & Teaser:** Tung thông điệp *"Trải nghiệm AI thực chiến cho học tập và việc làm"*, công bố thời gian, địa điểm và quyền lợi tham gia miễn phí trên Fanpage CLB và nhóm sinh viên.
- **Giai đoạn 2 (T-9 đến T-5) — Mở đơn & Công bố Diễn giả:** Mở form giới hạn 190 suất (tính sẵn tỷ lệ hao hụt); đăng bài giới thiệu 3 diễn giả cùng chủ đề Keynote/Workshop để thu hút đăng ký tự nhiên (0 đồng quảng cáo).
- **Giai đoạn 3 (T-4 đến T-2) — Đẩy mạnh Mini-Challenge:** Hé lộ cơ cấu giải thưởng 1.950.000 đồng và gửi thông báo qua đại diện các lớp/khoa để lấp đầy chỉ tiêu còn lại.
- **Giai đoạn 4 (T-1 đến T-0) — Chốt danh sách & Nhắc lịch:** Đóng form, gửi email xác nhận kèm mã QR check-in và hướng dẫn sinh viên chuẩn bị laptop/tài khoản AI trước khi đến hội trường.

---

## 7. Bản tóm tắt ngữ cảnh dự án (Context Management Snapshot)

```text
[CONTEXT_SNAPSHOT · AI INNOVATION DAY]
- Quy mô & thời lượng: Cố định 150 sinh viên, tổ chức trong 1 ngày (08:00–17:00) tại hội trường trường (miễn phí thuê).
- Nhân sự: Cố định 10 thành viên BTC (NS-01 đến NS-10), đã phân công theo từng khung giờ.
- Ngân sách trần: 15.000.000 VNĐ. Đã phân bổ 100%: Teabreak 165 suất (4.950.000 đ), Quà 3 diễn giả (3.000.000 đ), Backdrop/In ấn (2.250.000 đ), Giải thưởng (1.950.000 đ), Kỹ thuật AV/Wi-Fi (1.500.000 đ), Vật tư (600.000 đ), Dự phòng 5% (750.000 đ).
- Truyền thông: 4 chặng (T-14 đến T-0), mục tiêu 190 đơn đăng ký để đảm bảo 150 người tham dự thực tế.
- Trạng thái hiện tại: Đã hoàn tất lập kế hoạch tổng thể; sẵn sàng bước kiểm toán chéo và hiệu chỉnh rủi ro vận hành.
```

---

## 8. Báo cáo kiểm tra tính thống nhất và hiệu chỉnh kế hoạch

1. **Độ lệch suất ăn giữa khách mời và BTC:**
   - *Vấn đề:* Dự toán ban đầu chỉ tính 150 suất Teabreak cho sinh viên, bỏ sót 10 nhân sự BTC và khách mời.
   - *Đã hiệu chỉnh:* Nâng số lượng lên **165 suất** (`4.950.000 đ`) và cân đối lại giải thưởng/ấn phẩm để giữ nguyên trần `15.000.000 đ`.
2. **Thiếu nhân sự hỗ trợ kỹ thuật phiên chiều:**
   - *Vấn đề:* Phiên Workshop 13:30–15:15 có 150 sinh viên cùng truy cập công cụ AI dễ gây nghẽn mạng nếu chỉ có 1 kỹ thuật viên.
   - *Đã hiệu chỉnh:* Bổ sung `NS-07` chuyên trách mạng/AI Lab và huy động thêm `NS-02`, `NS-08` hỗ trợ trực tiếp các nhóm trong khung giờ chiều.
3. **Rủi ro hụt quy mô 150 sinh viên thực tế:**
   - *Vấn đề:* Sự kiện miễn phí thường có tỷ lệ vắng mặt 15–20% nếu chỉ mở đúng 150 suất đăng ký.
   - *Đã hiệu chỉnh:* Thiết lập ngưỡng mở form **190 đơn** kèm bước gửi QR xác nhận ở T-1 nhằm giữ đúng quy mô 150 sinh viên có mặt.
4. **Kiểm tra khớp số học cuối cùng:** Tổng 7 hạng mục dự toán bằng chính xác **15.000.000 đ (100,0%)**, toàn bộ 9 khung giờ đều có nhân sự phụ trách từ danh sách `NS-01` đến `NS-10`.
