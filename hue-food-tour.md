# Huế Food Tour – Prompt & Kết quả

> Ngày lập: 2026-11-16 · Cập nhật lần 2: thêm cafe (tab Cafe gid=298540028), bỏ cơm buổi sáng, thêm bún bò sáng Tour 1
> Nguồn dữ liệu: Google Sheets "(NO BOOKING) FOODLIST XỨ HUẾ MỘNG MƠ" (tab đầu, gid=0) — đã đọc trực tiếp, gồm cả màu ô để xác định quán HIGHLY RECOMMEND.

---

## PHẦN 1 – PROMPT

```markdown
# ROLE: HUẾ FOOD TOUR PLANNER

Bạn là chuyên gia lập lịch trình food tour tại Huế, am hiểu ẩm thực địa phương, vị trí các quán ăn và cách tối ưu tuyến đường tham quan.

## 1. Dữ liệu đầu vào

Google Sheets chứa danh sách các quán ăn tại Huế:

https://docs.google.com/spreadsheets/d/1ZR_3WfUYhg5v6RWVizEr5lKXJ44G-mZJm-W-fI6SECw/edit?gid=0#gid=0

Hãy truy cập và phân tích dữ liệu trực tiếp từ Google Sheets.

Cấu trúc dữ liệu:
- Cột A: STT.
- Cột B: Danh mục món ăn (có tổng cộng 21 danh mục).
- Các cột tiếp theo chứa thông tin quán ăn tương ứng, bao gồm tên quán, địa chỉ, giá, đánh giá, ghi chú và các thông tin khác.
- Những quán được tô màu xanh là HIGHLY RECOMMEND. Đây là tiêu chí ưu tiên quan trọng khi lựa chọn.

Nếu không đọc được Google Sheets, hãy thông báo rõ và yêu cầu dữ liệu thay vì tự suy đoán hoặc tự tạo tên quán.

## 2. Yêu cầu lập tour

Tạo chính xác 2 food tour tại Huế.

Mỗi tour cần có khoảng 7–10 QUÁN ĂN khác nhau.

Mục tiêu là trải nghiệm được nhiều món đặc sản Huế nhất có thể, không phải cố gắng ghé tất cả các quán trong bảng tính.

### Nguyên tắc lựa chọn quán

1. Ưu tiên quán được đánh dấu HIGHLY RECOMMEND.
2. Mỗi danh mục món ăn chỉ nên chọn một quán đại diện tốt nhất.
3. Không chọn nhiều quán chỉ vì chúng cùng bán một món hoặc một nhóm món.
4. Nếu một quán phục vụ nhiều món thuộc nhiều danh mục khác nhau, hãy ưu tiên quán đó để tăng số món trải nghiệm và giảm số điểm dừng.
5. Chọn quán dựa trên chất lượng, đánh giá, giá cả, ghi chú và vị trí.
6. Không bắt buộc phải sử dụng đủ cả 21 danh mục. Chỉ chọn những danh mục phù hợp với sở thích và có quán đáng ghé.
7. Không lặp lại cùng một quán giữa Tour 1 và Tour 2, trừ khi thực sự không có lựa chọn thay thế tốt.
8. Không tự ý thêm quán không có trong Google Sheets.

### Các món KHÔNG ăn

Tuyệt đối loại bỏ:
- Món chay.
- Bánh canh.
- Bánh tráng cuốn thịt heo.
- Ốp la / bánh mì chảo.
- Bún đậu mắm tôm.

Lưu ý: Nếu một quán bán cả món được phép ăn và món không ăn, vẫn có thể chọn quán đó nếu các món phù hợp đáng thử.

## 3. Tối ưu vị trí và lộ trình

Đây là tiêu chí rất quan trọng.

Không sắp xếp quán theo thứ tự danh mục trong bảng tính. Hãy dựa vào vị trí địa lý thực tế để xây dựng tuyến đường.

- Chia các quán thành các cụm địa lý hợp lý.
- Ưu tiên các quán gần nhau và các địa điểm tham quan gần tuyến đường.
- Hạn chế tối đa việc di chuyển qua lại giữa các khu vực.
- Không chọn quán quá xa chỉ vì muốn đủ số lượng.
- Thứ tự ghé quán phải hợp lý theo thời gian ăn uống và di chuyển.
- Nếu có thể, kết hợp tham quan các địa điểm nổi tiếng ở Huế giữa các điểm ăn uống.
- Hai tour nên đi theo hai hướng hoặc hai khu vực khác nhau để tránh trùng trải nghiệm.

Điểm xuất phát: [ĐIỀN ĐỊA CHỈ HOẶC GOOGLE MAPS LINK]

Nếu chưa xác định được vị trí chính xác của quán, hãy tra cứu Google Maps để kiểm tra. Không tự đoán địa chỉ hoặc tọa độ.

## 4. Định dạng kết quả

### TOUR 1 – [Tên tour theo khu vực]

Mô tả ngắn về khu vực và đặc điểm của tour.

| STT | Quán ăn | Món nên thử | Danh mục | Địa chỉ | Đánh giá / Giá |
|---|---|---|---|---|---|
| 1 | Tên quán | Các món nên gọi | Danh mục | Địa chỉ | Thông tin |
| 2 | ... | ... | ... | ... | ... |

Mỗi quán cần có:
- Link Google Maps chính xác để mở vị trí quán.
- Ghi chú ngắn vì sao chọn quán.
- Đánh dấu rõ nếu là HIGHLY RECOMMEND.

Sau bảng, cung cấp:
- Thứ tự di chuyển tối ưu.
- Link Google Maps chỉ đường toàn tour nếu có thể tạo được.
- Ước tính khoảng cách và thời gian di chuyển giữa các điểm.
- Các địa điểm tham quan có thể kết hợp.

### TOUR 2 – [Tên tour theo khu vực]

Trình bày tương tự Tour 1.

## 5. Phân tích và kiểm tra trước khi đưa ra kết quả

Trước khi hoàn thành, hãy tự kiểm tra:

- Mỗi tour có 7–10 quán khác nhau.
- Không có quán trùng giữa hai tour.
- Không có hai quán được chọn chỉ để ăn cùng một món/danh mục.
- Không chứa bất kỳ món nào trong danh sách không ăn.
- Ưu tiên tối đa các quán HIGHLY RECOMMEND.
- Các quán được sắp xếp theo vị trí địa lý, không đi vòng vô lý.
- Tất cả quán đều tồn tại và địa chỉ có thể xác minh trên Google Maps.
- Mỗi quán có link Google Maps riêng.
- Hai tour có trải nghiệm ẩm thực đa dạng, không chỉ tập trung vào các món bánh Huế.

Nếu không đủ quán chất lượng để đạt 7–10 quán/tour, hãy ưu tiên chất lượng và giải thích lý do, không cố thêm quán kém phù hợp.

## 6. Nguyên tắc quan trọng

Không được:
- Tự bịa tên quán, địa chỉ, đánh giá hoặc giá tiền.
- Chọn nhiều quán cùng bán một nhóm món chỉ để đủ số lượng.
- Chọn quán xa tuyến đường mà không có lý do hợp lý.
- Bỏ qua ghi chú HIGHLY RECOMMEND trong bảng tính.
- Chỉ liệt kê quán mà không tối ưu thứ tự di chuyển.

Hãy phân tích dữ liệu trước, sau đó mới đưa ra hai tour hoàn chỉnh. Chất lượng lựa chọn và tính hợp lý của lộ trình quan trọng hơn số lượng quán.
```

---

### Prompt điều chỉnh (lần 2)

```markdown
- ko ăn cơm niêu chạn buổi sáng, buổi sáng ko ăn cơm
- ở tour 1 thêm 1 option bún bò huế trước xôi
- đọc thêm https://docs.google.com/spreadsheets/d/1ZR_3WfUYhg5v6RWVizEr5lKXJ44G-mZJm-W-fI6SECw/edit?gid=298540028#gid=298540028
  để chèn vào quán cafe buổi sáng sau bữa ăn sáng, và gần trưa, và chiều tối
```

### Prompt điều chỉnh (lần 3)

```markdown
- tour 1 sẽ đi quán cf này https://maps.app.goo.gl/D7dfRcttFk6GGDsL7, thay vào ko care tuyến đường
  (→ chọn: thay quán cafe buổi sáng)
- Cung An Định thay bằng đồi Thiên An - xong chúng tôi sẽ quay về thành phố ăn uống theo tuyến đường đã chọn ko cần thay đổi
- và thêm vào lăng Khải Định ở tour 1
```

### Prompt điều chỉnh (lần 4)

```markdown
- bỏ mấy ký hiệu tick xanh đi (trong index.html)
- sao lại không còn món chè nữa
```

> Trả lời: trước đó món chè duy nhất là **đậu hũ Thiên Mụ** (sheet xếp đậu hũ vào nhóm Chè), nên khi nhìn bảng không thấy có chè thật sự. Đã thêm **Chè Mợ Tôn Đích** vào Tour 1 và **Ngọc Chè Bưởi** vào Tour 2.

---

## PHẦN 2 – KẾT QUẢ (bản cập nhật lần 3)

### 0. Phân tích dữ liệu & giả định

**Nguồn**
- Tab **Food** (gid=0): đọc trực tiếp từ sheet, có cả màu ô. Quán HIGHLY RECOMMEND (HR) là quán có ô tên tô xanh, gồm cả xanh đậm `#93c47d` và xanh nhạt `#b6d7a8`.
- Tab **Cafe** (gid=298540028): có 37 quán cafe, một số quán bia/bar và trà sữa. Tab này **không tô màu recommend**, nên chọn quán dựa vào 3 thứ: vị trí nằm trên tuyến, ghi chú "vibe/view" của chủ sheet, và món được recommend.
- Tọa độ lấy từ link Google Maps gắn trong sheet. Tên đường/phường đối chiếu qua OpenStreetMap. Khoảng cách tính theo đường xe thực tế (OSRM). Thời gian xe máy/Grab là **ước tính** (~3 phút/km).

**Thay đổi so với bản 1**
1. **Buổi sáng không ăn cơm:**
   - Bỏ **Cơm niêu Chạn** khỏi Tour 2. Tour 2 giờ bắt đầu từ sáng bằng **Xôi Dì Gái**.
   - **Cơm hến bé Đen** (Tour 1) dời sang **12:15**, thành bữa trưa.
   - Từ 6:00 đến 11:59 không còn điểm nào ăn cơm.
2. **Tour 1 thêm bún bò trước xôi:** **Bún cơm nguội Cảnh Vân** (HR, sheet xếp vào danh mục *Bún bò Huế*, là bún, không phải cơm) lúc 06:30, ghi rõ là **tùy chọn**. Phương án thay thế là **Bún bò mệ Kéo**, cách 130 m.
3. **Chèn cafe vào 3 khung giờ mỗi tour:** sau ăn sáng, gần trưa, chiều tối.

**Thay đổi lần 3**
1. **Tour 1, cafe sáng:** thay Cà Phê Sửu bằng **Phê La – Huế** (gần 30 Lê Lợi, bờ Nam, đầu cầu Trường Tiền) theo ý bạn. Đi lệch tuyến sang bờ Nam rồi quay về Đại Nội, khoảng 2 km mỗi chiều.
2. **Tour 1, thêm Lăng Khải Định:** thay chỗ KODO/nghỉ trưa (13:30–14:45). Thiên Mụ dời sang 15:20.
3. **Tour 2:** thay Cung An Định bằng **Đồi Thiên An** (08:50–10:15). Sau đó quay về thành phố, các quán ăn giữ nguyên.
4. Lăng Khải Định và Đồi Thiên An cách nhau chỉ **~1,5 km** (cùng khu Thủy Bằng). Nếu muốn, có thể gộp cả hai vào một buổi.

**Thay đổi lần 4 – thêm chè**
- **Tour 1:** thêm **Chè Mợ Tôn Đích** lúc 17:35. Quán được tô xanh, bán chè bột lọc heo quay (đặc sản), nằm ở khu cửa Thượng Tứ, trên đường từ Thiên Mụ về Gia Hội. Các điểm buổi tối lùi khoảng 15–30 phút.
- **Tour 2:** thêm **Ngọc Chè Bưởi – Trương Định** lúc 18:45, cách Cá viên O Huệ 190 m. Bờ Nam không có quán chè nào được tô xanh nên chọn quán gần tuyến nhất. Quán Ủa? lùi sang 21:00.

**Món loại bỏ:** giữ nguyên như bản 1, gồm bánh canh, chay, bánh tráng cuốn thịt heo, ốp la/bánh mì chảo, bún đậu mắm tôm.

**Điểm xuất phát:** prompt vẫn chưa điền, nên lộ trình bắt đầu từ quán đầu tiên.

---

### TOUR 1 – BỜ BẮC: GIA HỘI – KINH THÀNH – TÂY LỘC – LĂNG KHẢI ĐỊNH – THIÊN MỤ

Tour cả ngày, chủ yếu ở bờ Bắc sông Hương. Sáng: bún bò (tùy chọn) và xôi, cafe Phê La, rồi vào Đại Nội. Gần trưa: cà phê nhìn ra Đại Nội, xong ăn cơm hến trưa ở chợ Tây Lộc. Chiều: lăng Khải Định, rồi Thiên Mụ ngắm hoàng hôn. Chiều tối: về cụm Gia Hội, ăn bèo nậm lọc, uống cafe view sông Đông Ba, ăn ốc rồi bún bò.

#### Quán ăn

| STT | Quán ăn | Món nên thử | Danh mục | Địa chỉ (đã xác minh) | Đánh giá / Giá (theo sheet) |
|---|---|---|---|---|---|
| 0 | ✅ **HR** – [Bún cơm nguội Cảnh Vân](https://www.google.com/maps/place/B%C3%BAn+c%C6%A1m+ngu%E1%BB%99i+C%E1%BA%A3nh+V%C3%A2n/@16.4750927,107.5874459,17z/data=!3m1!4b1!4m6!3m5!1s0x3141a18dff2a7db3:0x759b81988b0b353d!8m2!3d16.4750876!4d107.5900262!16s%2Fg%2F11fmslzcmw) – **TÙY CHỌN** | Bún bò Huế | 1. Bún bò Huế | Khu Gia Hội, P. Phú Xuân | Từ 20k/tô, bán buổi sáng. *Thay thế:* [Bún bò mệ Kéo](https://www.google.com/maps/place/B%C3%BAn+b%C3%B2+m%E1%BB%87+K%C3%A9o/@16.463742,107.5637965,15z/data=!4m11!1m3!2m2!1zYsO6biBiw7IgaHXhur8!6e5!3m6!1s0x3141a1ca41e5bf03:0x7f35035e0fe667af!8m2!3d16.4750485!4d107.5886999!15sCg5iw7puIGLDsiBodeG6v1oQIg5iw7puIGLDsiBodeG6v5IBCnJlc3RhdXJhbnTgAQA!16s%2Fg%2F11t0p8_2w7) (đường Bạch Đằng, cách 130 m, từ 30k/tô). "Siêu nổi, siêu đông… 8h–8h30 là hết", tự phục vụ |
| 1 | ✅ **HR** – [Xôi Ngô Đức Kế](https://www.google.com/maps/place/X%C3%B4i+Ng%C3%B4+%C4%90%E1%BB%A9c+K%E1%BA%BF/@16.4610076,107.5696342,14z/data=!4m10!1m2!2m1!1zeMO0aSBodeG6vw!3m6!1s0x3141a1e0eb1b56d7:0x21896596ee61b782!8m2!3d16.4768718!4d107.5834445!15sCgp4w7RpIGh14bq_WgwiCnjDtGkgaHXhur-SAQZiaXN0cm_gAQA!16s%2Fg%2F11p6wn5g24) | Xôi mặn, mì chấm | 10. Xôi | Khu Ngô Đức Kế – Mai Thúc Loan, Thành Nội, P. Phú Xuân | Từ 15k/phần. **Nên đến trước 8h30** vì xôi hết nhanh |
| 2 | ✅ **HR** – Cơm hến bé Đen – chợ Tây Lộc ([Maps: Chợ Tây Lộc](https://www.google.com/maps/search/?api=1&query=Ch%E1%BB%A3+T%C3%A2y+L%E1%BB%99c+Hu%E1%BA%BF)) | Cơm hến (**bữa trưa**) | 5. Cơm/bún/mì hến | Trong chợ Tây Lộc, đường Hoàng Diệu, P. Phú Xuân | 12k/tô, bán cả ngày |
| 3 | ✅ **HR** – [Quán Mì Thiện Mỹ](https://www.google.com/maps/place/Qu%C3%A1n+M%C3%AC+Thi%E1%BB%87n+M%E1%BB%B9/@16.4615313,107.4933576,13z/data=!4m10!1m2!2m1!1zdGhp4buHbiBt4bu5IGLDoW5oIG3DrA!3m6!1s0x3141a7c5c79af549:0x5c76866395a83da8!8m2!3d16.4615313!4d107.5695753!15sChZ0aGnhu4duIG3hu7kgYsOhbmggbcOsWhgiFnRoaeG7h24gbeG7uSBiw6FuaCBtw6ySAQZiaXN0cm_gAQA!16s%2Fg%2F11h7szvkdg) | Bánh mì heo quay (mua mang theo) | 2. Bánh mì | Đường Lê Duẩn (khu Phú Thạnh), P. Phú Xuân | Từ 7k/ổ |
| 4 | ✅ **HR** – Đậu hũ – Chùa Thiên Mụ ([Maps: Chùa Thiên Mụ](https://www.google.com/maps/search/?api=1&query=Ch%C3%B9a+Thi%C3%AAn+M%E1%BB%A5+Hu%E1%BA%BF)) | Đậu hũ | 15. Chè | Dãy hàng trước chùa, đường Nguyễn Phúc Nguyên, P. Kim Long | 5k–10k/ly. Vừa ăn vừa ngắm hoàng hôn |
| 4b | ✅ **HR** – [Chè Mợ Tôn Đích](https://www.google.com/maps/place/Ch%C3%A8+M%E1%BB%A3+T%C3%B4n+%C4%90%C3%ADch/@16.4690466,107.5850157,17z/data=!4m6!3m5!1s0x3141a13065375f0f:0x1c449355353d15b2!8m2!3d16.4690466!4d107.5850157!16s%2Fg%2F11c4tb28kd) | Chè bột lọc heo quay | 15. Chè | Khu cửa Thượng Tứ, Đông Ba, P. Phú Xuân | 17k/ly. Nằm trên đường từ Thiên Mụ về Gia Hội |
| 5 | ✅ **HR** – [Bánh Bèo Nậm Lọc Huế Xưa](https://www.google.com/maps/place/Qu%C3%A1n+B%C3%A1nh+B%C3%A8o+N%E1%BA%ADm+L%E1%BB%8Dc+Hu%E1%BA%BF+X%C6%B0a/@16.4819779,107.5706217,15z/data=!4m10!1m2!2m1!1zYsOhbmggYsOobyBu4bqtbSBs4buNYw!3m6!1s0x3141a0d884d0af8f:0xaee706b9b3cdd8f6!8m2!3d16.4819779!4d107.5896761!15sChZiw6FuaCBiw6hvIG7huq1tIGzhu41jWhgiFmLDoW5oIGLDqG8gbuG6rW0gbOG7jWOSAQpyZXN0YXVyYW504AEA!16s%2Fg%2F11hbg8pxg1) | Bánh bèo, nậm, bánh lọc | 8. Bánh Huế | Đường Nguyễn Bỉnh Khiêm, Gia Hội, P. Phú Xuân | Sheet không ghi giá. Chủ sheet chọn quán này thay vì Bà Đỏ ở đối diện |
| 6 | ✅ **HR** – [Ốc Hẻm Huế](https://www.google.com/maps/place/%E1%BB%90c+H%E1%BA%BBm+Hu%E1%BA%BF/@16.4791391,107.5797537,16z/data=!4m10!1m2!2m1!1z4buRYyA!3m6!1s0x3141a1441d8fb92f:0x9292b0aea10208a9!8m2!3d16.4791391!4d107.5892809!15sCgThu5FjWgYiBOG7kWOSAQZiaXN0cm_gAQA!16s%2Fg%2F11t_hxv8x0) | Các món ốc | 9. Ốc | Gia Hội, P. Phú Xuân | Sheet không ghi giá. "Ngon và đông khách" |
| 7 | ✅ **HR** – [Bún bò O Ty](https://www.google.com/maps/place/B%C3%BAn+b%C3%B2+O+T%C3%BD/@16.4789827,107.58683,17z/data=!3m1!4b1!4m6!3m5!1s0x3141a12703a7aebf:0x9fe679eb0c34270a!8m2!3d16.4789776!4d107.5894103!16s%2Fg%2F11c6pqt0yg) | Bún bò Huế (bữa tối) | 1. Bún bò Huế | Đường Nguyễn Du, Phú Cát, P. Phú Xuân | Từ 30k/tô, bán tối/khuya |

> Nếu ăn bún bò buổi sáng (điểm 0) thì có thể bỏ **O Ty** buổi tối, hoặc giữ cả hai để so sánh bún bò sáng và bún bò tối.

#### Quán cafe (tab Cafe)

| Khung giờ | Quán | Vibe / Món nên thử (theo sheet) | Địa chỉ | Vì sao chọn |
|---|---|---|---|---|
| ☕ Sau ăn sáng | [Phê La – Huế](https://www.google.com/maps/place/Ph%C3%AA+La+-+Hu%C3%AA%CC%81/@16.4671334,107.5905512,17z/data=!4m6!3m5!1s0x3141a11ad897d571:0x75b479b362cb2a74!8m2!3d16.4671334!4d107.5905512!16s%2Fg%2F11yskxfdbd) | Quán bạn chọn (không có trong sheet) | Gần 30 Lê Lợi, Vĩnh Ninh, P. Thuận Hóa (bờ Nam, đầu cầu Trường Tiền) | Theo yêu cầu, không tối ưu tuyến |
| ☕ Gần trưa | [Lầu Tứ Phương Vô Sự](https://www.google.com/maps/place/L%E1%BA%A7u+T%E1%BB%A9+Ph%C6%B0%C6%A1ng+V%C3%B4+S%E1%BB%B1/@16.4719061,107.5732967,17z/data=!3m1!4b1!4m6!3m5!1s0x3141a12d67ad0327:0xd40c3feed2e228f2!8m2!3d16.471901!4d107.575877!16s%2Fg%2F120l36s9) | Cổ kính, Huế · view ra **cổng Hòa Bình** | Đặng Thái Thân, P. Phú Xuân | Cách Đại Nội 1,4 km, chợ Tây Lộc 700 m. Dự phòng: [Đề-Pô Cafe](https://www.google.com/maps/place/%C4%90%E1%BB%81-P%C3%B4+Cafe/@16.4648067,107.5921979,17z/data=!4m6!3m5!1s0x3141a1d1698c78b3:0x8acf0e53b4467931!8m2!3d16.4731576!4d107.5886234!16s%2Fg%2F11tjjpm_vh) (tầng 2 chợ Đông Ba) |
| 📍 Tham quan (thay KODO) | [Lăng Khải Định](https://www.google.com/maps/search/?api=1&query=L%C4%83ng+Kh%E1%BA%A3i+%C4%90%E1%BB%8Bnh+Hu%E1%BA%BF) | – | Thủy Bằng, P. Thủy Xuân (phía Nam thành phố) | Theo yêu cầu |
| ☕ Chiều tối | [HUE CAFE ROASTERY](https://www.google.com/maps/place/HUE+CAFE+ROASTERY/@16.4769342,107.5836365,17z/data=!3m1!4b1!4m6!3m5!1s0x3141a19558ae5ce7:0x4d02f07327065053!8m2!3d16.4769291!4d107.5862168!16s%2Fg%2F11tmt_dh6x) | View sông Đông Ba và chùa trên đường Bạch Đằng | 131 Huỳnh Thúc Kháng, Phú Hòa, P. Phú Xuân | Gần chợ Đông Ba, giữa Huế Xưa (1,6 km) và Ốc Hẻm (1,2 km). Dự phòng: [Mê – Cafe Bến Xưa](https://www.google.com/maps/place/M%C3%AA+-+Cafe+B%E1%BA%BFn+X%C6%B0a/@16.4770875,107.5923485,17z/data=!3m1!4b1!4m6!3m5!1s0x3141a1007ab31489:0x3626544adbe4f10b!8m2!3d16.4770824!4d107.5949288!16s%2Fg%2F11lmk7zc3f) (view bến sông) |

#### Lịch trình & di chuyển

| Giờ | Điểm | Khoảng cách từ điểm trước (đường xe) | Thời gian ước tính |
|---|---|---|---|
| 06:30 | 0. Bún cơm nguội Cảnh Vân *(tùy chọn)* | – | – |
| 07:15 | 1. Xôi Ngô Đức Kế | 1,35 km | ~5 phút |
| 07:45–08:30 | ☕ Phê La – Huế | 2,0 km (qua cầu Trường Tiền) | ~6 phút |
| 08:45–11:00 | 🏯 Đại Nội (Ngọ Môn) | 1,8 km | ~6 phút |
| 11:15–12:00 | ☕ Lầu Tứ Phương Vô Sự | 1,4 km | ~5 phút |
| 12:15 | 2. Cơm hến bé Đen – chợ Tây Lộc (**trưa**) | 1,3 km | ~5 phút |
| 13:00 | 3. Quán Mì Thiện Mỹ (mua mang theo) | 2,3 km | ~8 phút |
| 13:30–14:45 | 📍 Lăng Khải Định | 8,9 km | ~25 phút |
| 15:20–17:15 | 4. Chùa Thiên Mụ + đậu hũ, hoàng hôn | 11,7 km | ~30 phút |
| 17:35 | 4b. Chè Mợ Tôn Đích | 5,5 km | ~15 phút |
| 18:15 | 5. Bánh bèo nậm lọc Huế Xưa | 1,8 km | ~6 phút |
| 19:00–19:40 | ☕ HUE CAFE ROASTERY | 1,6 km | ~5 phút |
| 19:50 | 6. Ốc Hẻm Huế | 1,2 km | ~4 phút |
| 20:45 | 7. Bún bò O Ty | 0,03 km | đi bộ 1 phút |

**Tổng quãng đường: ~39 km** (tăng vì đi Lăng Khải Định và lệch sang Phê La).

🗺️ **Link chỉ đường.** Google Maps giới hạn số điểm dừng trong một link, nên tách làm 2 chặng:
- **Sáng → trưa** (Cảnh Vân → Xôi → Phê La → Đại Nội → Lầu Tứ Phương Vô Sự → Tây Lộc → Thiện Mỹ):
  https://www.google.com/maps/dir/16.4750876,107.5900262/16.4768718,107.5834445/16.4671334,107.5905512/16.4678107,107.5790879/16.471901,107.575877/16.4733387,107.5672745/16.4615313,107.5695753
- **Chiều → tối** (Thiện Mỹ → Lăng Khải Định → Thiên Mụ → Chè Mợ Tôn Đích → Huế Xưa → HUE CAFE ROASTERY → Ốc Hẻm → O Ty):
  https://www.google.com/maps/dir/16.4615313,107.5695753/16.3990174,107.5903393/16.4537195,107.5445808/16.4690466,107.5850157/16.4819779,107.5896761/16.4769291,107.5862168/16.4791391,107.5892809/16.4789776,107.5894103

**Tham quan kết hợp:** Đại Nội, chợ Tây Lộc (đồ 2hand), tường thành Lê Duẩn, Lăng Khải Định, chùa Thiên Mụ, phố cổ Gia Hội về đêm.

**Lưu ý**
- Sheet ghi Huế Xưa bán "trưa, xế". Nếu tới 18:15 mà quán đã đóng, có 2 cách:
  - ăn Huế Xưa ngay sau Xôi Ngô Đức Kế (cách ~1 km), rồi mới qua Phê La;
  - hoặc bỏ Huế Xưa, ngồi HUE CAFE ROASTERY sớm hơn.
- Sheet cafe không ghi giờ mở cửa. Nên kiểm tra trên Maps trước, nhất là Phê La nếu ngồi sớm. Lăng Khải Định cũng nên kiểm tra giờ mở cửa.

---

### TOUR 2 – BỜ NAM: AN CỰU – ĐỒI THIÊN AN – VỸ DẠ – PHỐ TÂY

Tour cả ngày ở bờ Nam sông Hương. Sáng: xôi, cà phê retro ven sông, đồi Thiên An, rồi quay về thành phố. Gần trưa: cafe sát quán bún mắm Donald Trung, ăn trưa luôn ở đó. Chiều: bánh ép, vịt lộn. Chiều tối: cafe ngắm sông Hương và cầu Trường Tiền, sau đó ăn cá viên, bún thịt nướng, kết thúc bằng bia ở Phố Tây.

#### Quán ăn

| STT | Quán ăn | Món nên thử | Danh mục | Địa chỉ (đã xác minh) | Đánh giá / Giá (theo sheet) |
|---|---|---|---|---|---|
| 1 | ✅ **HR** – [Xôi Dì Gái](https://www.google.com/maps/place/X%C3%B4i+D%C3%AC+G%C3%A1i/@16.4610076,107.5696342,14z/data=!4m11!1m3!2m2!1zeMO0aSBodeG6vw!6e5!3m6!1s0x3141a132d7dbeebf:0xad71d0cea12775e5!8m2!3d16.4586672!4d107.5985064!15sCgp4w7RpIGh14bq_WgwiCnjDtGkgaHXhur-SARRicmVha2Zhc3RfcmVzdGF1cmFudOABAA!16s%2Fg%2F11vbtt3glx) | **Xôi lộn xộn** | 10. Xôi | Khu Phan Đình Phùng, P. Thuận Hóa | Từ 15k. "Vibe chill chill thong dong". Khác kiểu với xôi Ngô Đức Kế ở Tour 1 |
| 2 | ✅ **HR** – [Donald Trung Huế – 28 Hoàng Văn Thụ](https://www.google.com/maps/place/TI%E1%BB%86M+%C4%82N+DONALD+TRUNG/@16.4605348,107.5752165,15z/data=!4m10!1m2!2m1!1zYsOhbmggdHLDoW5nIGN14buRbiB0aOG7i3QgaGVv!3m6!1s0x3141a11398950edf:0x15a6cd9cf4d5615d!8m2!3d16.4613952!4d107.604454!15sCh5iw6FuaCB0csOhbmcgY3Xhu5FuIHRo4buLdCBoZW9aICIeYsOhbmggdHLDoW5nIGN14buRbiB0aOG7i3QgaGVvkgEKcmVzdGF1cmFudOABAA!16s%2Fg%2F11fy4c9fjl) | **Bún mắm nêm heo quay** (không gọi bánh tráng cuốn) – **trưa** | 4. Bún mắm heo quay | 28 Hoàng Văn Thụ, P. Vỹ Dạ | Từ 50k/phần bún. "Đỉnh kao ẩm thực… mắm nêm đỉnh chóp ✨" |
| 3 | ✅ **HR** – [Tiệm bánh ép 1992](https://www.google.com/maps/place/Ti%E1%BB%87m+b%C3%A1nh+%C3%A9p+1992/@16.4585147,107.5709957,14z/data=!4m10!1m2!2m1!1zYsOhbmggw6lwIGh14bq_!3m6!1s0x3141a1581796c887:0xae0403180c0559f8!8m2!3d16.4585147!4d107.6091045!15sCg9iw6FuaCDDqXAgaHXhur9aESIPYsOhbmggw6lwIGh14bq_kgEKcmVzdGF1cmFudOABAA!16s%2Fg%2F11twhypz4f) | Bánh ép | 7. Bánh ép Huế | Khu An Đông, P. An Cựu | Sheet không ghi giá. "Ngon, đẫm thịt, bột hơi dai" |
| 4 | ✅ **HR** – [Vịt lộn um bầu AT&F](https://www.google.com/maps/place/V%E1%BB%8Bt+l%E1%BB%99n+um+b%E1%BA%A7u+AT%26F/@16.4570094,107.5732764,15z/data=!4m10!1m2!2m1!1zduG7i3QgbOG7mW4gdW0gYuG6p3U!3m6!1s0x3141a19f1f05906f:0x59c8479837d45cae!8m2!3d16.4568109!4d107.5939576!15sChR24buLdCBs4buZbiB1bSBi4bqndVoWIhR24buLdCBs4buZbiB1bSBi4bqndZIBBmJpc3Ryb-ABAA!16s%2Fg%2F11jz69_hbn) | Trứng lộn um bầu, mì xào trứng lộn, cút chiên xù | 13. Vịt lộn um bầu | Đường Nguyễn Khuyến, P. Thuận Hóa | Sheet không ghi giá. Chủ sheet "hay ăn AT&F nhất" |
| 5 | ✅ **HR** – [Cá Viên O Huệ](https://www.google.com/maps/place/C%C3%A1+Vi%C3%AAn+O+Hu%E1%BB%87/@16.4649388,107.5875715,21z/data=!4m6!3m5!1s0x3141a10057c25067:0xbc9269b154c19551!8m2!3d16.4649746!4d107.5874454!16s%2Fg%2F11lnl9ckbp) | Cá viên chiên, xiên que | 16. Ăn vặt | Đường Bà Huyện Thanh Quan, Vĩnh Ninh, P. Thuận Hóa | 10k/xiên, mua 10 tặng 1. Sau 22h O chuyển xe sang đường Hoàng Hoa Thám |
| 5b | [Ngọc Chè Bưởi – Trương Định](https://www.google.com/maps/place/NG%E1%BB%8CC+CH%C3%88+B%C6%AF%E1%BB%9EI+-+TR%C6%AF%C6%A0NG+%C4%90%E1%BB%8ANH/@16.4650454,107.5887145,17z/data=!4m6!3m5!1s0x3141a1733b44edc7:0x9905b4101091f08c!8m2!3d16.4650454!4d107.5887145!16s%2Fg%2F11ryqvmzzq) (không tô xanh) | Chè bưởi | 15. Chè | Khu 30 Trương Định, Vĩnh Ninh, P. Thuận Hóa | Sheet ghi "từ 20k/ly thì phải?". Chủ sheet thấy hơi ngọt, nên gọi ít ngọt. Chọn vì cách Cá viên chỉ 190 m |
| 6 | ✅ **HR** – [Thìn bún thịt nướng](https://www.google.com/maps/place/Th%C3%ACn+b%C3%BAn+th%E1%BB%8Bt+n%C6%B0%E1%BB%9Bng/@16.4682335,107.5958332,17z/data=!3m1!4b1!4m6!3m5!1s0x3141a1a4cb51b0e3:0x5a65f7d9047ace0f!8m2!3d16.4682284!4d107.6006988!16s%2Fg%2F11sxxf6mk5) | Bún thịt nướng | 12. Cháo, bún | Đường Văn Cao, P. Vỹ Dạ | Sheet không ghi giá. Bán xế, tối/khuya |
| 7 | ✅ **HR** – [Quán bia Ủa?](https://www.google.com/maps/place/Qu%C3%A1n+bia+%E1%BB%A6a%3F/@16.4682894,107.595072,18.9z/data=!4m6!3m5!1s0x3141a191d647371d:0x9d53b7e32ddcb634!8m2!3d16.4691608!4d107.5957886!16s%2Fg%2F11p74r22kp) | Bia + đồ nhắm | 14. Nhậu | Đường Võ Thị Sáu (Phố Tây), P. Thuận Hóa | Sheet không ghi giá |

#### Quán cafe (tab Cafe)

| Khung giờ | Quán | Vibe / Món nên thử (theo sheet) | Địa chỉ | Vì sao chọn |
|---|---|---|---|---|
| ☕ Sau ăn sáng | [Xưởng 1976 Cafe](https://www.google.com/maps/place/C%C3%A0+ph%C3%AA+1976+cs1/@16.456396,107.5991804,17z/data=!3m1!4b1!4m6!3m5!1s0x3141a18cc492e485:0xdfeb13920d226a18!8m2!3d16.4563909!4d107.6017607!16s%2Fg%2F11r9zclrcq) | Retro, cozy, **view sông + chợ An Cựu** · Thái xanh/thái đỏ trân châu | 12 Hải Triều, An Đông, P. An Cựu | Cách Xôi Dì Gái 600 m. Quán retro mở gần 10 năm |
| ☕ Gần trưa | [de b&b house](https://www.google.com/maps/place/de+b%26b+house/@16.4607698,107.6030685,17z/data=!3m1!4b1!4m6!3m5!1s0x3141a187710579d7:0x8b2b421db38d760!8m2!3d16.4607647!4d107.6056488!16s%2Fg%2F11vsvjk_yp) | Xanh, industrial · **Trà ô long sữa, ô long kem sữa, tiramisu** | 13 Lê Minh, An Đông, P. An Cựu | Cách Donald Trung chỉ **240 m**: uống cafe xong đi bộ qua ăn trưa. Có 3 bé mèo. **Đóng cửa ~17h**, nên xếp vào buổi trưa là hợp |
| ☕ Chiều tối | [Không Gian Sách và Văn Hoá Huế](https://www.google.com/maps/place/KH%C3%94NG+GIAN+S%C3%81CH+V%C3%80+V%C4%82N+HO%C3%81+HU%E1%BA%BE/@16.4662488,107.5863741,17z/data=!3m1!4b1!4m6!3m5!1s0x3141a1001fc18775:0x437c7439ab9e2f14!8m2!3d16.4662437!4d107.5889544!16s%2Fg%2F11ww0l8s06) | Cổ kính, Huế · ngồi ngoài trời **view sông Hương + cầu Trường Tiền** | 23–25 Lê Lợi, Vĩnh Ninh, P. Thuận Hóa | Ngắm hoàng hôn trên sông Hương. Cách Cá viên O Huệ 290 m |

#### Lịch trình & di chuyển

| Giờ | Điểm | Khoảng cách từ điểm trước (đường xe) | Thời gian ước tính |
|---|---|---|---|
| 07:00 | 1. Xôi Dì Gái | – | – |
| 07:45–08:45 | ☕ Xưởng 1976 Cafe | 0,6 km | ~3 phút |
| 08:50–10:15 | 🌲 [Đồi Thiên An](https://www.google.com/maps/search/?api=1&query=%C4%90%E1%BB%93i+Thi%C3%AAn+An+Hu%E1%BA%BF) | 7,3 km | ~20 phút |
| 10:45–11:45 | ☕ de b&b house (quay về thành phố) | 9,0 km | ~25 phút |
| 12:00 | 2. Donald Trung – bún mắm heo quay (**trưa**) | 0,24 km | đi bộ 3 phút |
| 14:30 | 3. Tiệm bánh ép 1992 | 0,75 km | ~3 phút |
| 16:00 | 4. Vịt lộn um bầu AT&F | 2,2 km | ~7 phút |
| 17:00–18:00 | ☕ Không Gian Sách và Văn Hoá Huế (hoàng hôn) | 1,4 km | ~5 phút |
| 18:15 | 5. Cá Viên O Huệ → dạo cầu Trường Tiền | 0,29 km | đi bộ 4 phút |
| 18:45 | 5b. Ngọc Chè Bưởi | 0,19 km | đi bộ 3 phút |
| 19:45 | 6. Thìn bún thịt nướng | 1,8 km | ~6 phút |
| 21:00 | 7. Quán bia Ủa? | 0,7 km | ~3 phút |

**Tổng quãng đường: ~25 km** (tăng vì đi Đồi Thiên An).

🗺️ **Link chỉ đường** (tách 2 chặng):
- **Sáng → chiều** (Xôi Dì Gái → Xưởng 1976 → Đồi Thiên An → de b&b → Donald Trung → Bánh ép 1992):
  https://www.google.com/maps/dir/16.4586672,107.5985064/16.4563909,107.6017607/16.4105291,107.5823373/16.4607647,107.6056488/16.4613952,107.604454/16.4585147,107.6091045
- **Chiều → tối** (Bánh ép 1992 → AT&F → Không Gian Sách → Cá viên → Chè bưởi → Thìn → Quán bia Ủa?):
  https://www.google.com/maps/dir/16.4585147,107.6091045/16.4568109,107.5939576/16.4662437,107.5889544/16.4649746,107.5874454/16.4650454,107.5887145/16.4682284,107.6006988/16.4691608,107.5957886

**Tham quan kết hợp:** Đồi Thiên An (gần đó có hồ Thủy Tiên), chợ An Cựu, bờ sông Lê Lợi, cầu Trường Tiền lên đèn, phố đi bộ Phố Tây, Vỹ Dạ.

**Lưu ý**
- Sheet cafe không ghi giờ mở cửa của Xưởng 1976 và Không Gian Sách. Nên kiểm tra trên Maps trước khi đi.
- Địa chỉ Xưởng 1976 lấy theo sheet (12 Hải Triều). OSM định vị điểm đánh dấu gần số 20 Hải Triều, nên cứ đi theo link Maps.
- Nếu vẫn muốn ăn **Cơm niêu Chạn**, có thể thêm vào làm bữa tối. Quán nằm ở Võ Thị Sáu, ngay cạnh Quán bia Ủa?.

---

### Kiểm tra trước khi chốt (bản 2)

| Tiêu chí | Kết quả |
|---|---|
| Mỗi tour 7–10 quán ăn | ✅ Tour 1 có 7 quán + 1 bún bò tùy chọn. Tour 2 có 7 quán. Mỗi tour có thêm 3 quán cafe (Tour 1 thêm 1 cafe tùy chọn) |
| Buổi sáng không ăn cơm | ✅ Đã bỏ Cơm niêu Chạn. Cơm hến dời sang 12:15. Sáng chỉ có bún bò và xôi |
| Bún bò trước xôi (Tour 1) | ✅ Cảnh Vân lúc 06:30 (tùy chọn), thay thế bằng mệ Kéo |
| Cafe sáng / gần trưa / chiều tối | ✅ Tour 1: Phê La, Lầu Tứ Phương Vô Sự, HUE CAFE ROASTERY. Tour 2: Xưởng 1976, de b&b house, Không Gian Sách |
| Không trùng quán giữa 2 tour | ✅ Cả quán ăn lẫn quán cafe |
| Không trùng danh mục | ⚠️ Có 2 ngoại lệ có chủ đích:<br>• **Bún bò** xuất hiện 2 lần trong Tour 1 (sáng là tùy chọn theo yêu cầu, tối là O Ty).<br>• **Xôi** có ở cả 2 tour, khác kiểu: xôi mặn/mì chấm và xôi lộn xộn.<br>Các danh mục còn lại không trùng |
| Không có món cấm | ✅ |
| Ưu tiên HR | ✅ Tất cả quán ăn đều tô xanh. Tab cafe không đánh dấu recommend |
| Lộ trình theo địa lý | ✅ Tour 1 nằm trọn bờ Bắc, Tour 2 nằm trọn bờ Nam. Quán cafe đều nằm sát tuyến: chặng cafe xa nhất là 1,8 km |
| Link Maps riêng từng điểm | ✅ Cơm hến bé Đen và đậu hũ Thiên Mụ không có link riêng trong sheet, nên dùng link chợ Tây Lộc và chùa Thiên Mụ |

---

## Thay đổi lần 5 (Tour 1 – đổi 2 quán cafe)

> tour1: Afternoon Coffee chỉ bán buổi chiều, Giao Cf vừa xa thành phố vừa xấu, đổi quán khác

- Gần trưa: Afternoon Coffee → **Lầu Tứ Phương Vô Sự** (cùng đường Đặng Thái Thân, view cổng Hòa Bình). Dự phòng: Đề-Pô Cafe.
- Chiều tối: Giao Cafe → **HUE CAFE ROASTERY** (131 Huỳnh Thúc Kháng, gần chợ Đông Ba, view sông). Dự phòng: Mê – Cafe Bến Xưa.
- Link chỉ đường Tour 1 đã cập nhật tọa độ mới.
