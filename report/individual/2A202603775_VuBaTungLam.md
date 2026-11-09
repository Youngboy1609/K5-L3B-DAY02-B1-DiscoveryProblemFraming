# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Bá Tùng Lâm
- MSSV: 2A202603775
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: B1
- Link repo nhóm: https://github.com/Youngboy1609/K5-L3B-DAY02-B1-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Vào mỗi buổi sáng, tôi cần phải nộp báo cáo daily standup lên trên trang phoenix, nếu nộp trong thời gian từ 0h-10h sẽ được XP | BTC, Mentor, Bản thân | Mỗi ngày một lần, viết khoảng 10 phút |
| 2 | Tốn thời gian | Khi học một chủ đề mới, tôi muốn tìm được tài liệu đúng với kiến thức cần yêu cầu để tối ưu thời gian đọc tài liệu | Người tự học | Tìm sai tài liệu dẫn đến thời gian không phù hợp |
| 3 | Lặp lại | Khi chi tiêu hàng tháng, tôi muốn biết tiền đang được sử dụng vào các khoản nào, để kiếm soát ngân sách cá nhân | Người đi làm | Báo cáo tổng hợp chi tiêu mỗi tuần một lần |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi muốn mua một sản phẩm công nghệ, tôi muốn so sánh thông tin từ nhiều nguồn, để lựa chọn sản phẩm phù hợp với ngân sách và nhu cầu | Người tiêu dùng | Số nguồn tham khảo, thời gian nghiên cứu |
| 5 | Pain từ người khác | Khi nhận một nhiệm vụ từ nhiều email hoặc tin nhắn, tôi muốn xác định rõ yêu cầu, deadline và người phụ trách, để tránh hiểu sai công việc | Nhân viên | Số lần phải xác nhận lại, số lỗi do hiểu sai |
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Chi tiêu hàng tháng | Xảy ra thường xuyên, ảnh hưởng trực tiếp đến ngân sách cá nhân | Tần suất ghi chép, mức độ thiếu chính xác, nguyên nhân chi tiêu vượt kế hoạch |
| 2 | Mất thời gian tìm kiếm và chọn lọc tài liệu khi học chủ đề mới | Có tính lặp lại, ảnh hưởng đến tốc độ tự học và khả năng tiếp thu | Khó khăn lớn nhất nằm ở tìm tài liệu, đánh giá chất lượng hay hiểu nội dung |
| 3 | Mất nhiều thời gian nghiên cứu và so sánh trước khi mua sản phẩm công nghệ | Có nhiều nguồn thông tin, thông số và đánh giá trái chiều | Thời gian nghiên cứu, tiêu chí quyết định mua và mức độ ảnh hưởng của thông tin sai lệch |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi chi tiêu trong tháng, tôi muốn theo dõi và phân loại các khoản tiền đã sử dụng, để biết tiền đang được chi vào đâu và kiểm soát ngân sách hiệu quả |
| Actor | Cá nhân có thu nhập hoặc sinh hoạt phí cố định |
| Thời điểm / bối cảnh | Hàng ngày khi phát sinh giao dịch và cuối tháng khi tổng kết tài chính |
| Quy trình hiện tại (3–7 bước) | 1. Phát sinh giao dịch. 2. Ghi nhớ hoặc lưu hóa đơn. 3. Ghi chép vào ứng dụng hoặc Excel. 4. Phân loại khoản chi. 5. Tổng hợp cuối tháng. 6. So sánh với ngân sách dự kiến |
| Bottleneck (bước nào, mất bao nhiêu phút) | Dễ quên ghi chép các khoản nhỏ; mất thời gian phân loại giao dịch; khó tổng hợp khi dữ liệu nằm ở nhiều nguồn. Cần đo số phút thực tế mỗi ngày và cuối tháng |
| Impact (nếu không giải thì sao) | Không biết chính xác tiền đã sử dụng vào đâu, khó phát hiện khoản chi bất thường và có nguy cơ vượt ngân sách |
| Success metric (baseline → target) | Baseline: đo thời gian ghi chép và tổng hợp hiện tại. Target đề xuất: giảm 50% thời gian tổng hợp; ít nhất 90% giao dịch được ghi nhận và phân loại đúng |
| Phương án không dùng AI | Sử dụng Google Sheets hoặc Excel với danh mục chi tiêu, công thức SUMIF và biểu đồ thống kê |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ phân loại giao dịch từ nội dung chi tiêu, nhận diện xu hướng và đưa ra cảnh báo khi một nhóm chi tiêu tăng bất thường |
| Cảm nhận nhanh | Rule / Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI - 20 Phút

[1 Phát sinh giao dịch, lưu lại thông tin chi tiêu: 3'] → [2 Nhập giao dịch vào Excel/app: 3'] → [3 Phân loại khoản chi: 8'] ← BOTTLENECK → [4 Tổng hợp chi tiêu trong ngày: 3'] 
→ [5 Đối chiếu với ngân sách: 3']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu học một chủ đề mới, tôi muốn tìm được tài liệu phù hợp với trình độ và mục tiêu của mình, để có thể xây dựng lộ trình học tập hiệu quả và tránh lãng phí thời gian |
| Actor | Sinh viên, người tự học, người mới chuyển sang lĩnh vực khác |
| Thời điểm / bối cảnh | Khi bắt đầu một khóa học, học công nghệ mới hoặc chuẩn bị tiếp cận một lĩnh vực chuyên môn |
| Quy trình hiện tại (3–7 bước) | 1. Xác định chủ đề cần học. 2. Tìm kiếm trên Google, YouTube, GitHub hoặc các nền tảng học tập. 3. Đọc mô tả và đánh giá tài liệu. 4. So sánh các nguồn. 5. Chọn tài liệu. 6. Bắt đầu học và điều chỉnh nếu không phù hợp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Có quá nhiều tài liệu, khó xác định nguồn đáng tin cậy, không biết thứ tự kiến thức cần học và dễ gặp nội dung vượt quá trình độ hiện tại |
| Impact (nếu không giải thì sao) | Tốn thời gian chuẩn bị, học lan man, mất động lực và có thể phải học lại từ đầu khi chọn sai tài liệu |
| Success metric (baseline → target) | Baseline: đo thời gian từ lúc xác định chủ đề đến khi chọn được tài liệu phù hợp. Target đề xuất: giảm 40% thời gian tìm kiếm và lựa chọn tài liệu |
| Phương án không dùng AI | Sử dụng roadmap có sẵn, danh sách tài liệu được cộng đồng đánh giá và checklist kiến thức cần học |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ phân tích trình độ, mục tiêu học tập và đề xuất tài liệu, thứ tự kiến thức phù hợp với người học |
| Cảm nhận nhanh | Workflow / Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 95 phút

[1 Xác định chủ đề, mục tiêu và trình độ hiện tại: 10'] 
→ [2 Tìm kiếm tài liệu trên Google, YouTube,...: 30'] → [3 Đọc mô tả và xem trước nội dung tài liệu: 15']
→ [4 So sánh độ phù hợp và độ tin cậy: 20'] ← BOTTLENECK → [5 Chọn tài liệu và xây dựng lộ trình học: 20'] 
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi có nhu cầu mua một sản phẩm công nghệ mới, tôi muốn thu thập và so sánh thông tin từ nhiều nguồn đáng tin cậy, để lựa chọn sản phẩm đáp ứng nhu cầu và ngân sách mà không phải mất quá nhiều thời gian nghiên cứu |
| Actor | Người tiêu dùng có nhu cầu mua sản phẩm công nghệ |
| Thời điểm / bối cảnh | Khi chuẩn bị mua điện thoại, laptop, linh kiện máy tính hoặc thiết bị điện tử |
| Quy trình hiện tại (3–7 bước) | 1. Xác định nhu cầu và ngân sách. 2. Tìm kiếm sản phẩm. 3. Đọc thông số kỹ thuật. 4. Xem video đánh giá và trải nghiệm người dùng. 5. So sánh các sản phẩm. 6. Kiểm tra giá bán và chính sách bảo hành. 7. Quyết định mua |
| Bottleneck (bước nào, mất bao nhiêu phút) | Thông tin nằm ở nhiều website và video; thông số kỹ thuật khó đối chiếu; đánh giá người dùng có thể thiên lệch; giá bán thay đổi giữa các cửa hàng |
| Impact (nếu không giải thì sao) | Mất nhiều thời gian nghiên cứu, có nguy cơ lựa chọn sản phẩm không phù hợp hoặc bỏ qua lựa chọn có giá trị tốt hơn |
| Success metric (baseline → target) | 	Baseline: đo thời gian nghiên cứu trước mỗi quyết định mua. Target đề xuất: giảm 30% thời gian nghiên cứu nhưng vẫn đáp ứng đầy đủ các tiêu chí lựa chọn |
| Phương án không dùng AI | Sử dụng bảng Excel để so sánh thông số, giá bán, ưu nhược điểm và chính sách bảo hành |
| Giả thuyết về AI (nếu có) | AI có thể tổng hợp đánh giá từ nhiều nguồn, đối chiếu thông số và phân tích ưu nhược điểm dựa trên nhu cầu cụ thể của người mua |
| Cảm nhận nhanh | Workflow / Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 150 phút

[1 Xác định nhu cầu và ngân sách: 10'] → [2 Tìm kiếm các sản phẩm phù hợp: 30'] 
→ [3 Đọc và so sánh thông số kỹ thuật: 20']
→ [4 Xem video review, đánh giá từ người dùng: 60'] ← BOTTLENECK 
→ [5 So sánh giá bán, bảo hành và nơi mua: 15'] 
→ [6 Tổng hợp ưu/nhược điểm và đưa ra quyết định: 15']
```

### Card muốn pitch nhất

- Card số: 2
- Vì sao: là vấn đề phổ biến đối với sinh viên, người tự học và những người muốn chuyển sang một lĩnh vực mới
- Câu hỏi muốn nhóm phản biện: Có thực sự cần AI để giải quyết vấn đề này không, hay chỉ cần một hệ thống lọc và đề xuất tài liệu dựa trên các quy tắc có sẵn?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Đối tượng người dùng còn quá rộng, bao gồm nhiều nhóm có nhu cầu học tập khác nhau | Đồng ý | Thu hẹp đối tượng mục tiêu vào sinh viên, người tự học công nghệ và người mới bắt đầu học một lĩnh vực mới |
| Chưa có số liệu cụ thể chứng minh mức độ nghiêm trọng của vấn đề. | Đồng ý một phần | Bổ sung thời gian ước tính 70–105 phút cho mỗi chủ đề và xác định các chỉ số cần khảo sát để kiểm chứng baseline thực tế | 

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
