# Báo cáo cá nhân — Discovery & Problem Framing

> Bản nháp. Các tình huống, quy trình và số liệu ở mục 2–3 là minh họa cần đối chiếu với trải nghiệm thật. Khi hoàn tất, đổi tên file thành `MSSV_HoTen.md` theo MSSV và họ tên viết liền không dấu của bạn.

## 1. Thông tin học viên

- Họ tên: Nguyễn Minh Quân
- MSSV: 2A202603794
- Tên nhóm: B1
- Link repo nhóm: https://github.com/Youngboy1609/K5-L3B-DAY02-B1-DiscoveryProblemFraming

## 2. Scan problem (CP1)

|   # | Lăng kính                         | Job Story                                                                                                         | Ai chịu ảnh hưởng?                | Dấu hiệu minh họa cần xác nhận                                                |
| --: | --------------------------------- | ----------------------------------------------------------------------------------------------------------------- | --------------------------------- | ----------------------------------------------------------------------------- |
|   1 | Lặp lại                           | Khi chuẩn bị nộp bài, tôi muốn biết mình còn thiếu yêu cầu nào, để hoàn tất bài đúng hạn.                         | Người nộp bài                     | Trong 3 bài gần nhất, mỗi bài mở lại đề và hướng dẫn nộp khoảng 2 lần.        |
|   2 | Tốn thời gian                     | Khi nhóm chuẩn bị ghép bài, tôi muốn xác định bản mới nhất của từng phần, để ghép đúng nội dung mọi người đã sửa. | Người ghép bài và các thành viên  | Lần ghép gần nhất mất khoảng 20 phút để tìm và đối chiếu 4 phiên bản.         |
|   3 | Cần đọc, tổng hợp nhiều thông tin | Khi ôn kiểm tra, tôi muốn biết nội dung nào nằm trong phạm vi ôn, để ưu tiên phần cần học trước.                  | Người ôn kiểm tra                 | Mất khoảng 30 phút để đối chiếu slide, ghi chú và thông báo lớp.              |
|   4 | Khó khăn từ người khác            | Khi nhận việc sau buổi họp, tôi muốn biết mình cần bàn giao gì và khi nào, để có thể bắt đầu ngay.                | Thành viên nhận việc              | Sau buổi họp gần nhất, 2 thành viên nhắn lại để hỏi về đầu ra hoặc thời hạn.  |
|   5 | Lặp lại                           | Khi nhóm cần hẹn họp, tôi muốn biết khung giờ mọi người cùng rảnh, để chốt lịch và bắt đầu công việc.             | Người điều phối và các thành viên | Lần hẹn gần nhất cần 6 lượt trao đổi và khoảng 4 giờ từ lúc hỏi đến lúc chốt. |

**Gợi ý từ AI đã giữ hoặc bỏ:** [Ghi ý bạn giữ, ý bạn bỏ và vì sao sau khi đối chiếu với trải nghiệm thật.]

## 3. Top 3 Problem Cards và quy trình nháp (CP2)

### Bảng chọn top 3

| Hạng | Vấn đề từ CP1                           | Vì sao chọn                                                     | Điều còn chưa chắc                                    |
| ---: | --------------------------------------- | --------------------------------------------------------------- | ----------------------------------------------------- |
|    1 | Tìm bản mới nhất khi ghép bài nhóm (#2) | Vai trò rõ, bước đối chiếu phiên bản có thể tách ra và bấm giờ. | File nằm rải rác hay bản cuối chưa được xác nhận?     |
|    2 | Xác định phạm vi ôn kiểm tra (#3)       | Đo được thời gian đối chiếu và kiểm tra phần bị bỏ sót.         | Thông báo của giảng viên có đủ rõ không?              |
|    3 | Tìm giờ họp chung (#5)                  | Có thể đo thời gian từ các mốc tin nhắn.                        | Phần chậm nhất là chờ phản hồi hay tìm giờ giao nhau? |

### Problem Card 1 — Tìm bản mới nhất khi ghép bài nhóm

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

### Problem Card 2 — Xác định phạm vi ôn kiểm tra

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

### Problem Card 3 — Tìm giờ họp chung

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

| Điểm yếu AI chỉ ra                                         | Đồng ý?                 | Đã sửa gì trong bản nháp                                                       |
| ---------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------ |
| Card 1 có thể nhầm file sửa gần nhất với bản đã duyệt.     | [Ghi nhận định của bạn] | Làm rõ bước xác nhận bản cuối với người phụ trách và bổ sung chỉ số ghép nhầm. |
| Card 2 có thể lập danh sách nhanh hơn nhưng bỏ sót chủ đề. | [Ghi nhận định của bạn] | Bổ sung điều kiện bao phủ các mục nêu rõ trong thông báo.                      |
| Card 3 dễ nhầm thời gian chờ với thời gian thao tác.       | [Ghi nhận định của bạn] | Tách hai loại thời gian và thống nhất mốc đo với sơ đồ.                        |

## 4. Tôi đã tham gia phần nào (CP3–CP7)

| Hoạt động                  | Tôi đã làm gì?            | Kết quả / ảnh hưởng tới bài nhóm  |
| -------------------------- | ------------------------- | --------------------------------- |
| Pitch Problem Card         | [Card đã pitch và lý do]  | [Kết quả]                         |
| Phản biện bài của bạn khác | [Câu hỏi tôi thực sự đặt] | [Nhóm đã làm rõ hoặc thay đổi gì] |
| Nhận phản biện             | [Câu hỏi tôi nhận được]   | [Điều tôi đã sửa]                 |
| Gom cluster / cây OST      | [Đóng góp]                | [Kết quả]                         |
| Chọn candidate problem     | [Đóng góp]                | [Kết quả]                         |
| Kiểm chứng / research      | [Đóng góp]                | [Bằng chứng hoặc nguồn]           |
| Quy trình nhóm             | [Đóng góp]                | [Kết quả]                         |
| Problem Statement          | [Đóng góp]                | [Kết quả]                         |
| Mức can thiệp AI           | [Đóng góp]                | [Kết quả]                         |
| Quyết định                 | [Đóng góp]                | [Kết quả]                         |

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                                       | AI hữu ích ở đâu?                                                                           | AI sai hoặc hời hợt ở đâu?                            | Tôi sửa gì bằng nhận định của mình?                          |
| ------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------ |
| CP1                            | Nhờ AI gợi ý tình huống, viết Job Story và minh họa số liệu. | Tạo bảng theo đúng cấu trúc đề.                                                             | Tình huống và số liệu do AI gợi ý chưa được xác nhận. | [Ghi các dòng giữ, bỏ hoặc thay và cách bạn kiểm số liệu.]   |
| CP2                            | Nhờ AI dựng và phản biện 3 Problem Card.                     | Chỉ ra sự khác nhau giữa bản mới và bản đã duyệt, giữa thời gian chờ và thời gian thao tác. | Quy trình và số phút từng bước dựa trên giả định.     | [Ghi bước, số phút hoặc tiêu chí bạn sửa sau khi đối chiếu.] |
| CP4 Research                   | [Điền nếu có dùng]                                           |                                                                                             |                                                       |                                                              |
| CP5 Quy trình                  | [Điền nếu có dùng]                                           |                                                                                             |                                                       |                                                              |
| CP5–CP6 Problem Statement      | [Điền nếu có dùng]                                           |                                                                                             |                                                       |                                                              |
| CP6 Mức can thiệp / quyết định | [Điền nếu có dùng]                                           |                                                                                             |                                                       |                                                              |

## 6. Reflection (CP7)

_Tự trả lời bằng trải nghiệm thật. Tổng câu 6.1–6.6 ít nhất 200 từ. Câu 6.7 viết riêng 5–8 câu._

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**  
[Viết câu trả lời của bạn.]

**6.2. Nhóm có lúc nào nghĩ giải pháp trước khi hiểu vấn đề không? Nhóm nhận ra và xử lý thế nào?**  
[Viết câu trả lời của bạn.]

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**  
[Viết câu trả lời của bạn.]

**6.4. Điều gì trong kết quả kiểm chứng làm tôi bất ngờ?**  
[Viết câu trả lời của bạn.]

**6.5. Điều khó nhất khi viết Problem Statement là gì?**  
[Viết câu trả lời của bạn.]

**6.6. Nếu làm lại, tôi sẽ đổi gì và phản biện mạnh hơn ở đâu?**  
[Viết câu trả lời của bạn.]

**6.7. Hiểu bài**  
[Tự giải thích vấn đề nhóm chọn, quy trình và bước nghẽn, chỉ số thành công, giới hạn, mức can thiệp AI và quyết định của nhóm.]

## 7. Tài liệu tham khảo

- [Worksheet của lab](../../docs/01-worksheet.md)
- [Bài làm mẫu của lab](../../docs/02-deliverable-example.md)
- [Thêm nguồn thực tế đã dùng, nếu có.]
