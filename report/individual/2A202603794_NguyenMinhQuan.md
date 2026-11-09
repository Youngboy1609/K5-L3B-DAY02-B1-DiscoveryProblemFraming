# Báo cáo cá nhân — 2A202603794_NguyenMinhQuan

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Minh Quân
- MSSV: 2A202603794
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: B1
- Link repo nhóm: https://github.com/Youngboy1609/K5-L3B-DAY02-B1-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

|   # | Lăng kính                         | Job Story                                                                                                         | Ai chịu ảnh hưởng?                | Dấu hiệu thật                                                                 |
| --: | --------------------------------- | ----------------------------------------------------------------------------------------------------------------- | --------------------------------- | ----------------------------------------------------------------------------- |
|   1 | Lặp lại                           | Khi chuẩn bị nộp bài, tôi muốn biết mình còn thiếu yêu cầu nào, để hoàn tất bài đúng hạn.                         | Người nộp bài                     | Trong 3 bài gần nhất, mỗi bài mở lại đề và hướng dẫn nộp khoảng 2 lần.        |
|   2 | Tốn thời gian                     | Khi nhóm chuẩn bị ghép bài, tôi muốn xác định bản mới nhất của từng phần, để ghép đúng nội dung mọi người đã sửa. | Người ghép bài và các thành viên  | Lần ghép gần nhất mất khoảng 20 phút để tìm và đối chiếu 4 phiên bản.         |
|   3 | Cần đọc, tổng hợp nhiều thông tin | Khi ôn kiểm tra, tôi muốn biết nội dung nào nằm trong phạm vi ôn, để ưu tiên phần cần học trước.                  | Người ôn kiểm tra                 | Mất khoảng 30 phút để đối chiếu slide, ghi chú và thông báo lớp.              |
|   4 | Khó khăn từ người khác            | Khi nhận việc sau buổi họp, tôi muốn biết mình cần bàn giao gì và khi nào, để có thể bắt đầu ngay.                | Thành viên nhận việc              | Sau buổi họp gần nhất, 2 thành viên nhắn lại để hỏi về đầu ra hoặc thời hạn.  |
|   5 | Lặp lại                           | Khi nhóm cần hẹn họp, tôi muốn biết khung giờ mọi người cùng rảnh, để chốt lịch và bắt đầu công việc.             | Người điều phối và các thành viên | Lần hẹn gần nhất cần 6 lượt trao đổi và khoảng 4 giờ từ lúc hỏi đến lúc chốt. |

## 3. Top 3 Problem Cards

### Bảng chọn top 3

| Rank | Problem                                 | Vì sao chọn                                                     | Điều còn chưa chắc                                    |
| ---: | --------------------------------------- | --------------------------------------------------------------- | ----------------------------------------------------- |
|    1 | Tìm bản mới nhất khi ghép bài nhóm (#2) | Vai trò rõ, bước đối chiếu phiên bản có thể tách ra và bấm giờ. | File nằm rải rác hay bản cuối chưa được xác nhận?     |
|    2 | Xác định phạm vi ôn kiểm tra (#3)       | Đo được thời gian đối chiếu và kiểm tra phần bị bỏ sót.         | Thông báo của giảng viên có đủ rõ không?              |
|    3 | Tìm giờ họp chung (#5)                  | Có thể đo thời gian từ các mốc tin nhắn.                        | Phần chậm nhất là chờ phản hồi hay tìm giờ giao nhau? |

### Problem Card #1 — Tìm bản mới nhất khi ghép bài nhóm

| Trường                  | Nội dung                                                                                                                                                           |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Job Story               | Khi nhóm chuẩn bị ghép bài, tôi muốn xác định bản mới nhất đã được duyệt của từng phần, để đưa đúng nội dung vào bản nộp chung.                                    |
| Actor                   | Thành viên được giao ghép bài và chuẩn bị bản nộp chung.                                                                                                           |
| Thời điểm / bối cảnh    | Trước hạn nộp, khi có nhiều bản chỉnh sửa trong tin nhắn hoặc thư mục chung.                                                                                       |
| Quy trình hiện tại      | Xem các phần cần ghép → tìm file đã gửi → đối chiếu phiên bản → xác nhận bản cuối.                                                                                 |
| Bottleneck              | Bước 3, đối chiếu tên file, thời điểm gửi và nội dung của 4 phiên bản, khoảng 10 phút/lần theo giả định.                                                           |
| Impact                  | Khoảng 20 phút/lần để xác định đủ bản cuối. Nếu ghép nhầm, người ghép phải thay lại nội dung.                                                                      |
| Success metric          | Từ 20 xuống tối đa 8 phút/lần. Bấm giờ từ lúc mở danh sách phần cần ghép đến lúc xác nhận đủ bản cuối. Kiểm tra số phần ghép nhầm với người phụ trách, mục tiêu 0. |
| Phương án không dùng AI | Dùng một link chính cho mỗi phần. Người phụ trách cập nhật tại link đó và đánh dấu “Đã chốt”.                                                                      |
| Giả thuyết về AI        | Nếu vẫn phải đối chiếu nhiều bản cũ, AI có thể liệt kê các đoạn khác nhau để người phụ trách kiểm tra.                                                             |
| Cảm nhận nhanh          | Rule — thử một link chính và trạng thái “Đã chốt”.                                                                                                                 |

```text
HIỆN TẠI — 20 phút/lần
[1. Xem danh sách phần cần ghép: 2 phút]
→ [2. Tìm file trong tin nhắn và thư mục: 5 phút]
→ [3. Đối chiếu các phiên bản: 10 phút] ← BƯỚC NGHẼN
→ [4. Xác nhận bản cuối với người phụ trách: 3 phút]
```

### Problem Card #2 — Xác định phạm vi ôn kiểm tra

| Trường                  | Nội dung                                                                                                                                                        |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi chuẩn bị ôn kiểm tra, tôi muốn xác định các chủ đề nằm trong phạm vi kiểm tra, để phân bổ thời gian ôn đúng phần.                                           |
| Actor                   | Sinh viên đang lập danh sách chủ đề cần ôn.                                                                                                                     |
| Thời điểm / bối cảnh    | Trước buổi ôn, khi thông tin nằm trong slide, ghi chú và thông báo lớp.                                                                                         |
| Quy trình hiện tại      | Mở ba nguồn → ghi các chủ đề có thể cần ôn → đối chiếu với thông báo chính thức → chốt danh sách và đánh dấu phần chưa rõ.                                      |
| Bottleneck              | Bước 3, đối chiếu chủ đề với thông báo chính thức, khoảng 15 phút/lần theo giả định.                                                                            |
| Impact                  | Khoảng 30 phút để lập danh sách trước khi ôn. Hiểu nhầm phạm vi có thể khiến sinh viên ôn thừa hoặc bỏ sót chủ đề.                                              |
| Success metric          | Từ 30 xuống tối đa 15 phút/lần, đo từ lúc mở tài liệu đến lúc chốt danh sách. Danh sách bao phủ đủ mục được nêu rõ trong thông báo và đánh dấu mục cần hỏi lại. |
| Phương án không dùng AI | Dùng thông báo chính thức làm checklist và gắn số trang slide hoặc ghi chú tương ứng.                                                                           |
| Giả thuyết về AI        | Nếu đối chiếu thủ công vẫn mất thời gian, AI có thể gợi ý các mục tương ứng để sinh viên kiểm tra với nguồn chính thức.                                         |
| Cảm nhận nhanh          | No AI — thử checklist trước.                                                                                                                                    |

```text
HIỆN TẠI — 30 phút/lần
[1. Mở slide, ghi chú và thông báo lớp: 4 phút]
→ [2. Ghi các chủ đề có thể cần ôn: 7 phút]
→ [3. Đối chiếu với thông báo chính thức: 15 phút] ← BƯỚC NGHẼN
→ [4. Chốt danh sách và đánh dấu phần chưa rõ: 4 phút]
```

### Problem Card #3 — Tìm giờ họp chung

| Trường                  | Nội dung                                                                                                                                   |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Job Story               | Khi nhóm cần hẹn họp, tôi muốn biết khung giờ mọi thành viên có thể tham gia, để chốt lịch và bắt đầu công việc.                           |
| Actor                   | Thành viên phụ trách hẹn lịch họp.                                                                                                         |
| Thời điểm / bối cảnh    | Khi nhóm cần họp và các thành viên có lịch học hoặc lịch cá nhân khác nhau.                                                                |
| Quy trình hiện tại      | Chuẩn bị và gửi khung giờ → chờ đủ phản hồi → đối chiếu để tìm giờ chung → xác nhận và gửi lịch.                                           |
| Bottleneck              | Bước 2, chờ đủ phản hồi, khoảng 210 phút theo giả định. Có thể đo từ mốc gửi đề xuất đến mốc nhận phản hồi cuối.                           |
| Impact                  | Khoảng 240 phút từ lúc bắt đầu chuẩn bị đến lúc gửi lịch, gồm 210 phút chờ và 30 phút thao tác của người điều phối.                        |
| Success metric          | Từ 240 xuống tối đa 120 phút/lần. Bấm giờ từ lúc bắt đầu chuẩn bị đề xuất đến lúc gửi lịch. Tất cả thành viên cần có mặt xác nhận giờ họp. |
| Phương án không dùng AI | Gửi bảng chọn giờ có vài phương án cụ thể, đặt hạn phản hồi và dùng bảng để xem phương án đủ người.                                        |
| Giả thuyết về AI        | AI có thể gom phản hồi dạng văn bản. Hiệu quả dự kiến thấp nếu phần lớn độ trễ đến từ việc chờ người trả lời.                              |
| Cảm nhận nhanh          | Rule — thử danh sách khung giờ và hạn phản hồi.                                                                                            |

```text
HIỆN TẠI — 240 phút từ lúc bắt đầu chuẩn bị đến lúc gửi lịch
[1. Chuẩn bị và gửi các khung giờ: 5 phút]
→ [2. Chờ đủ phản hồi: 210 phút] ← BƯỚC NGHẼN, THỜI GIAN CHỜ
→ [3. Đối chiếu để tìm giờ chung: 20 phút]
→ [4. Xác nhận và gửi lịch: 5 phút]
```

### Card muốn pitch nhất

- **Card 1 — Tìm bản mới nhất khi ghép bài nhóm.**
- **Lý do:** Có thể kiểm chứng bằng một lần ghép bài cụ thể và thử quy ước một link chính cho mỗi phần.
- **Câu hỏi muốn nhóm phản biện:** Trong lần ghép gần nhất, nhóm mất nhiều thời gian hơn để tìm file hay để xác nhận bản nào đã được duyệt? Dấu vết nào giúp phân biệt hai việc đó?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                         | Đồng ý? | Đã sửa gì trong bản nháp                                                       |
| ---------------------------------------------------------- | ------- | ------------------------------------------------------------------------------ |
| Card 1 có thể nhầm file sửa gần nhất với bản đã duyệt.     | Đồng ý  | Làm rõ bước xác nhận bản cuối với người phụ trách và bổ sung chỉ số ghép nhầm. |
| Card 2 có thể lập danh sách nhanh hơn nhưng bỏ sót chủ đề. | Đồng ý  | Bổ sung điều kiện bao phủ các mục nêu rõ trong thông báo.                      |
| Card 3 dễ nhầm thời gian chờ với thời gian thao tác.       | Đồng ý  | Tách hai loại thời gian và thống nhất mốc đo với sơ đồ.                        |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                        | Phần tôi phụ trách hoặc hỗ trợ                                                                                                                             | Kết quả / ảnh hưởng tới bài nhóm                                                                                                                                                                       |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Pitch Problem Card (CP3)         | Tôi trình bày ngắn gọn các Problem Card đã chuẩn bị, tập trung vào người gặp vấn đề, cách họ đang làm, bước nghẽn và cách đo mức độ ảnh hưởng.             | Phần trình bày giúp nhóm có cùng thông tin để so sánh các vấn đề trước khi chọn ứng viên.                                                                                                              |
| Phản biện bài của bạn khác (CP3) | **Câu hỏi gợi ý:** Trong lần gần nhất gặp vấn đề này, bạn mất nhiều thời gian nhất ở bước nào? Bạn dựa vào đâu để ước lượng thời gian ở bước đó?           | Câu hỏi giúp làm rõ bước nghẽn và căn cứ của số liệu trước khi nhóm chấm điểm.                                                                                                                         |
| Nhận phản biện (CP3)             | **Câu hỏi gợi ý:** Bạn dựa vào đâu để biết đây là bản đã chốt để ghép bài?                                                                                 | Tôi làm rõ rằng người phụ trách cần xác nhận bản đã chốt và bổ sung tiêu chí kiểm tra số phần bị ghép nhầm.                                                                                            |
| Gom cluster / cây OST (CP3)      | Tôi hỗ trợ gom các ứng viên theo khó khăn chung và sắp xếp các nhánh của cây OST.                                                                          | Đầu ra được phân công gồm bảng cluster và cây OST.                                                                                                                                                     |
| Chọn candidate problem (CP3)     | Tôi hỗ trợ đối chiếu các ứng viên theo tiêu chí và lập bảng chấm điểm.                                                                                     | Ứng viên xác định phạm vi ôn kiểm tra đang được dùng để chuẩn bị kiểm chứng. Nhóm chưa ghi lựa chọn cuối ở mục 2.4.                                                                                    |
| Kiểm chứng / research (CP4)      | Tôi phụ trách chính phần kiểm chứng. Kế hoạch là ưu tiên các giả định về việc xác định phạm vi ôn kiểm tra và hỏi sinh viên ngoài nhóm về lần ôn gần nhất. | Báo cáo nhóm có 5 giả định, ưu tiên kiểm tra việc dùng nhiều nguồn, thời gian đối chiếu và mức độ lặp lại hoặc hậu quả. Kế hoạch là phỏng vấn 2–3 sinh viên ngoài nhóm. Kết quả thực tế chưa được ghi. |
| Quy trình nhóm (CP5)             | Phần vẽ quy trình trước/sau do Lâm phụ trách, Nghĩa hỗ trợ.                                                                                                | Đầu ra được phân công là hai sơ đồ và bảng so sánh trước/sau.                                                                                                                                          |
| Problem Statement (CP5–CP6)      | Tôi phụ trách chính bản v0. Sang CP6, tôi hỗ trợ cập nhật bản v1 để gắn mức can thiệp và người kiểm tra với bước nghẽn.                                    | Bản v0 sẽ dùng dữ liệu kiểm chứng để xác định bước nghẽn và cách đo thành công. Báo cáo nhóm chưa có nội dung v0 và v1 để đối chiếu.                                                                   |
| Mức can thiệp AI (CP6)           | Tôi hỗ trợ đặt bài toán vào ma trận độ mơ hồ × độ phức tạp, so sánh No AI, Rule, Workflow và Agent, rồi rà soát tiêu chí đánh giá đầu ra.                  | Báo cáo nhóm chưa ghi mức can thiệp được chọn.                                                                                                                                                         |
| Quyết định (CP6)                 | Phần đánh giá bốn rủi ro và kết luận do Nghĩa phụ trách, Lâm hỗ trợ.                                                                                       | Báo cáo nhóm chưa ghi kết luận cuối.                                                                                                                                                                   |
| Tổng kết cá nhân (CP7)           | Tôi tổng hợp phần việc của mình trong báo cáo cá nhân.                                                                                                     | Mục 4 ghi lại phần việc tôi phụ trách chính và phần việc tôi hỗ trợ.                                                                                                                                   |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Tôi dùng AI để gợi ý tình huống, diễn đạt Job Story và minh họa cách ghi dấu hiệu đo được. | Các gợi ý giúp tôi mô tả rõ bối cảnh, nhu cầu và kết quả mong muốn. | AI đưa ra thời lượng minh họa khi chưa có quan sát thực tế. | Tôi đánh dấu các con số là minh họa. Khi xác nhận một tình huống, tôi cần dựa vào lần xảy ra cụ thể và số liệu có căn cứ. |
| CP2 Problem Card | Tôi nhờ AI đối chiếu bản nháp với hướng dẫn, phác thảo quy trình và đặt câu hỏi phản biện cho ba card. | Phản biện giúp làm rõ hai điểm: bản mới nhất có thể chưa được duyệt và thời gian chờ phản hồi khác với thời gian thao tác. | Số phút ở từng bước là ước lượng của bản nháp, chưa đủ để kết luận bước nào thực sự nghẽn. | Tôi đồng ý đưa bước xác nhận bản đã duyệt vào Card 1 và thêm tiêu chí kiểm tra số phần ghép nhầm. Ở Card 3, tôi tách thời gian chờ khỏi thời gian thao tác để đo riêng từng phần. |
| CP3 – Ghi lại phần tham gia | Khi chỉnh báo cáo cá nhân, tôi nhờ AI diễn đạt lại phần trình bày và gợi ý cách viết hai câu hỏi phản biện. | Phần trình bày gọn hơn, còn câu hỏi tập trung vào bước nghẽn và căn cứ của số liệu. | Câu hỏi gợi ý chưa được đối chiếu với lời trao đổi trong buổi pitch. | Tôi chọn mô tả phần pitch ở mức khái quát và giữ nhãn “gợi ý” cho hai câu hỏi. |
| CP4 Research | Tôi nhờ AI đọc lại repo và đối chiếu bảng research với hướng dẫn CP4. | AI chỉ ra rằng kế hoạch phỏng vấn đã có, còn bảng research cần nêu giải pháp hiện có xử lý bước nào và còn khoảng trống gì. | Rà soát repo chỉ cho biết bảng đang trống. Chưa xác minh được công cụ hoặc nguồn bên ngoài từ lần rà soát này. | Tôi tách minh chứng phỏng vấn khỏi bảng research. Mỗi giải pháp đưa vào bảng cần có link nhóm đã mở, bước được hỗ trợ và khoảng trống cụ thể. |
| CP5 Quy trình | Tôi nhờ AI so sánh quy trình nháp của card về phạm vi ôn kiểm tra với yêu cầu sơ đồ trước/sau của nhóm. | AI chỉ ra hai bước nên đo riêng: tìm và mở tài liệu, rồi đối chiếu chủ đề với thông báo chính thức. Sơ đồ tương lai cần chỉ rõ ai kiểm tra kết quả và cách quay về quy trình thủ công. | Quy trình ở CP2 chỉ là giả thuyết. Mốc 30 phút trong card chưa đủ căn cứ để làm số liệu hiện tại của nhóm. | Tôi giữ mốc 30 phút ở phần minh họa CP2. Sơ đồ nhóm sẽ dùng các bước và thời gian lấy từ lần ôn thực tế đã được kiểm chứng. |
| CP5–CP6 Problem Statement | Tôi nhờ AI rà soát các mục v0 và v1 trong báo cáo nhóm để nhận diện dữ kiện còn thiếu. | AI chỉ ra v0 cần làm rõ cách đo từ lúc mở tài liệu đến khi chốt danh sách ôn. Nếu v1 đề xuất AI hỗ trợ đối chiếu, cần ghi ai xác nhận danh sách và xử lý thế nào khi các nguồn mâu thuẫn. | Hai bản trong repo còn là mẫu trống, nên lần rà soát này chỉ xác định được các điểm cần kiểm tra trước khi viết. | Tôi giữ thông báo chính thức làm căn cứ đối chiếu. Mục tiêu về thời gian cần đi kèm tiêu chí bao phủ các chủ đề được nêu rõ trong thông báo. |
| CP6 Mức can thiệp / quyết định | Tôi nhờ AI rà soát các điều kiện cần có trước khi chọn mức can thiệp cho vấn đề xác định phạm vi ôn. | AI gợi ý dùng checklist theo thông báo chính thức làm phương án đối chứng. Nếu cân nhắc AI, có thể kiểm tra việc bỏ sót chủ đề, thêm mục ngoài phạm vi và cách đánh dấu nguồn mâu thuẫn. | Những tiêu chí này là gợi ý rà soát. Repo chưa có kết quả thử nghiệm để xác nhận mức nào hiệu quả. | Tôi giữ checklist trong danh sách phương án cần so sánh. Nhóm sẽ chọn mức can thiệp và chốt Go / Not Yet / No-Go dựa trên dữ liệu kiểm chứng và đánh giá bốn rủi ro. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nhìn lại các vấn đề mà nhóm đưa ra để so sánh, tôi thấy một vấn đề dễ hiểu hơn khi nói rõ ai gặp và họ bị kẹt ở bước nào. Nếu chỉ nói một việc “mất thời gian” thì các vấn đề nghe khá giống nhau. Có một lần cụ thể để kể và có cách đo thì nhóm dễ thảo luận hơn.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Trong bản nháp của tôi có vài ý về dùng AI khá sớm. Khi xem lại ví dụ tìm bản cuối để ghép bài, tôi thấy có thể thử quy ước một link cho mỗi phần và để người phụ trách đánh dấu bản đã chốt. Điều đó giúp tôi quay lại câu hỏi ban đầu là nhóm đang mất thời gian tìm file hay xác nhận bản cuối.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có một điểm tôi đổi cách viết sau khi rà lại card ghép bài. Lúc đầu tôi chú ý đến bản được sửa gần nhất. Sau đó tôi thấy bản mới nhất vẫn có thể đang sửa dở. Tôi thêm bước hỏi người phụ trách xem bản nào đã chốt và thêm tiêu chí kiểm tra xem có phần nào bị ghép nhầm.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Báo cáo nhóm hiện có kế hoạch phỏng vấn. Tôi chú ý nhất đến khả năng có bạn chỉ cần đọc một thông báo rõ là biết phải ôn gì. Nếu gặp trường hợp như vậy, tôi muốn hỏi thêm điều gì khác với những lần phải mở nhiều nguồn. Câu trả lời sẽ giúp nhóm biết nên giới hạn vấn đề vào bối cảnh nào.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất với tôi là chọn cách đo cho rõ. Ví dụ, tôi cần tách thời gian tìm tài liệu khỏi thời gian đọc và đối chiếu nội dung. Nếu gộp hai phần lại thì khó biết nên cải thiện bước nào. Tôi cũng muốn kiểm tra xem danh sách ôn có đủ chủ đề, vì làm nhanh hơn mà bỏ sót thì vẫn chưa đạt.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi sẽ ghi thời gian từng bước ngay từ một lần làm thật. Khi góp ý cho một vấn đề, tôi sẽ hỏi lần gần nhất nó xảy ra là khi nào, người đó đã làm gì và mất bao lâu. Có câu trả lời cụ thể thì tôi sẽ dễ nhận ra nhóm đang dựa vào quan sát hay đang đoán.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

Ứng viên nhóm đang chuẩn bị kiểm chứng là việc sinh viên phải đối chiếu nhiều nguồn để xác định phạm vi ôn kiểm tra. Quy trình dự kiến gồm mở tài liệu, ghi các chủ đề và so lại với thông báo chính thức, trong đó bước đối chiếu là chỗ có thể mất nhiều thời gian nhất. Tôi sẽ đo từ lúc mở nguồn đầu tiên đến lúc chốt danh sách, rồi kiểm tra xem có bỏ sót chủ đề được nêu trong thông báo hay không. Nếu dùng AI để gợi ý, sinh viên vẫn phải xác nhận danh sách theo thông báo và hỏi lại khi thông tin mâu thuẫn. Tôi muốn so sánh trước với cách làm đơn giản là dùng thông báo chính thức làm checklist. Theo tôi, ở thời điểm này hướng phù hợp là Not Yet, vì nhóm còn cần dữ liệu phỏng vấn để xác nhận bước nghẽn và xem cách làm đơn giản đã đủ chưa.

---

## 7. Tài liệu tham khảo

-
