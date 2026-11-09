# Báo cáo cá nhân — 2A202603775_VuBaTungLam

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
| Pitch Problem Card | Đưa ra 3 Card mà bản thân thấy problem nhất | Giúp cả nhóm tập trung đưa ra câu phản biện và giải quyết vấn đề một cách tốt nhất có thể |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Liệu AI có thể giải quyết triệt để vấn đề chốt lịch để hẹn họp không? | Câu trả lời là giải quyết cần phụ thuộc vào cả phía người họp vì AI chỉ là công cụ hỗ trợ chứ không ép người được |
| Nhận phản biện | Câu hỏi tôi nhận được: Liệu excel/googlesheet có đủ để quản lý chi tiêu hàng tháng mà không cần đến AI không | Tôi đã sửa gì: Trong thời đại ngày này thì có sự trợ giúp của AI luôn làm cho mọi việc dễ dàng hơn nên chúng ta nên kết hợp cả 2 giải pháp để đạt được hiệu quả tốt nhất |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | Tìm hiểu về các diễn đàn trên internet để khảo sát về các vấn đề được đặt ra | Kết quả cho thấy cũng có nhiều người gặp phải các vấn đề được nêu ra |
| Quy trình nhóm | Nghiên cứu giải pháp giúp giảm thiểu thời gian và chi phí | Ra được bảng biểu before/after |
| Problem Statement | Hỗ trợ giải quyết với thành viên trong nhóm | Problem Statement v0 |
| Mức can thiệp AI | So sánh các mức sử dụng AI với không sử dụng AI | Đưa ra được ma trận, eval, Problems Statement v1 |
| Quyết định | Hỗ trợ đưa ra quyết định | Ra quyết định với 4 rủi ro + Go/Not Yet/No-Go |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Sử dụng AI để brainstorm và mở rộng danh sách các vấn đề có thể gặp trong học tập, công việc và cuộc sống cá nhân | AI giúp tôi phát hiện nhiều vấn đề, phân loại theo mức độ lặp lại, thời gian tiêu tốn và khả năng ứng dụng công nghệ | Một số vấn đề còn chung chung, chưa thể hiện rõ trải nghiệm thực tế và mức độ ảnh hưởng đối với người dùng | Tôi lựa chọn và sắp xếp lại các vấn đề dựa trên mức độ quen thuộc, tính thực tế và khả năng kiểm chứng. Cuối cùng, tôi chọn 3 vấn đề ưu tiên, trong đó có việc tìm kiếm và chọn lọc tài liệu học tập |
| CP2 Problem Card | Sử dụng AI để xây dựng Job Story, xác định Actor, quy trình hiện tại, Bottleneck, Impact và Success Metrics cho 3 vấn đề đã chọn | AI giúp cấu trúc hóa vấn đề, phân chia quy trình thành từng bước và đề xuất các chỉ số để đánh giá hiệu quả | Thời gian thực hiện và các chỉ số ban đầu chủ yếu là ước tính, chưa có khảo sát thực tế. Đối tượng người dùng và mức độ cần thiết của AI cũng chưa được xác định rõ | Tôi chọn Card 2 để pitch, thu hẹp đối tượng vào sinh viên và người tự học, bổ sung ảnh hưởng đến hiệu quả phối hợp nhóm và xác định các câu hỏi cần kiểm chứng |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe các vấn đề mà những thành viên khác lựa chọn, tôi nhận ra mỗi người có cách nhìn nhận và xác định vấn đề khác nhau dựa trên trải nghiệm cá nhân. Một vấn đề mà tôi có thể xem là bình thường lại có thể gây ra nhiều khó khăn cho người khác. Tôi cũng nhận thấy không phải vấn đề nào cũng cần một giải pháp công nghệ phức tạp. Có những vấn đề có thể được giải quyết bằng cách thay đổi quy trình hoặc sử dụng những công cụ đơn giản. Điều này giúp tôi hiểu rằng khi xác định một problem, cần tập trung vào nhu cầu thực tế của người gặp vấn đề thay vì chỉ quan tâm đến khả năng xây dựng sản phẩm.
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Tôi nhận thấy nhóm có nguy cơ đi theo hướng solution-first khi bắt đầu thảo luận về khả năng ứng dụng AI trước khi xác định rõ vấn đề cần giải quyết. Tuy nhiên, khi phân tích kỹ hơn, tôi nhận ra vấn đề thực sự không chỉ nằm ở việc tìm tài liệu mà còn ở việc đánh giá chất lượng, mức độ phù hợp và sắp xếp thứ tự học.
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Một lần cụ thể là khi xây dựng Card 2, ban đầu tôi tập trung chủ yếu vào việc người học mất thời gian tìm kiếm tài liệu từ nhiều nguồn khác nhau. Sau khi nhận được phản biện từ AI, tôi nhận ra đối tượng người dùng còn quá rộng, số liệu thời gian chưa được kiểm chứng và chưa chứng minh được tại sao cần AI thay vì sử dụng Google hoặc các nền tảng học tập hiện có. Điều này khiến tôi thay đổi cách tiếp cận. Tôi thu hẹp đối tượng mục tiêu vào sinh viên và người tự học, phân tích rõ hơn các bước tìm kiếm, xem trước và đánh giá tài liệu, đồng thời bổ sung phương án không sử dụng AI để so sánh. Tôi cũng nhận ra rằng giá trị của giải pháp không đơn thuần là tìm được nhiều tài liệu mà phải tìm được tài liệu phù hợp với trình độ và mục tiêu của người học.
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Khi tham khảo nghiên cứu về hành vi học tập trực tuyến, tôi chú ý đến việc người học thường sử dụng nhiều nền tảng khác nhau. Điều này giúp tôi nhận ra vấn đề không chỉ nằm ở số lượng tài liệu mà còn ở sự phân tán thông tin giữa các nguồn. Một người học có thể tìm được rất nhiều tài liệu nhưng vẫn khó xác định đâu là nguồn đáng tin cậy và phù hợp với trình độ của mình.
**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất đối với tôi là xác định đúng trọng tâm của vấn đề và diễn đạt sao cho không bị nhầm lẫn giữa problem và solution. Ban đầu, tôi thường nghĩ đến việc xây dựng một công cụ AI giúp tìm kiếm tài liệu và tạo lộ trình học tập. Tuy nhiên, nếu mô tả vấn đề theo hướng đó thì Problem Statement sẽ bị ảnh hưởng bởi giải pháp mà tôi đã nghĩ ra. Sau khi phân tích, tôi nhận thấy cần tập trung vào khó khăn của người học: mất thời gian tìm kiếm, khó đánh giá độ tin cậy và không biết lựa chọn tài liệu nào phù hợp với trình độ và mục tiêu. Ngoài ra, việc xác định đối tượng người dùng, bối cảnh xảy ra vấn đề và tác động cụ thể cũng không đơn giản. Tôi hiểu rằng một Problem Statement tốt cần mô tả được vấn đề thực tế mà người dùng gặp phải, thay vì mô tả sản phẩm mà nhóm muốn xây dựng.
**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu được thực hiện lại, tôi sẽ dành nhiều thời gian hơn cho việc khảo sát và thu thập trải nghiệm thực tế trước khi lựa chọn Problem Card. Thay vì chỉ dựa vào trải nghiệm cá nhân và số liệu tham khảo, tôi sẽ phỏng vấn một số sinh viên hoặc người tự học để xác định tần suất xảy ra vấn đề, thời gian thực tế và những khó khăn lớn nhất của họ. 
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Vấn đề nhóm tôi lựa chọn là người học mất nhiều thời gian tìm kiếm, đánh giá và lựa chọn tài liệu khi bắt đầu học một chủ đề mới. Quy trình hiện tại gồm xác định mục tiêu, tìm kiếm tài liệu, xem trước nội dung, đánh giá độ phù hợp và xây dựng lộ trình học. Nhóm sử dụng các metric như thời gian tìm kiếm tài liệu, tỷ lệ tài liệu phù hợp và mức độ hài lòng để đánh giá hiệu quả giải pháp. Boundary của vấn đề là tập trung vào việc hỗ trợ sinh viên và người tự học lựa chọn tài liệu, không thay thế toàn bộ quá trình giảng dạy hoặc học tập. Về mức can thiệp, nhóm cân nhắc từ giải pháp không sử dụng AI, Rule-based đến AI-assisted và AI Agent. Tôi cho rằng AI phù hợp nhất ở việc phân tích nhu cầu, đánh giá và đề xuất tài liệu theo trình độ và mục tiêu của người học. Cuối cùng, nhóm ưu tiên hướng AI-assisted, trong đó AI đưa ra đề xuất còn người dùng vẫn kiểm tra và quyết định lựa chọn tài liệu.
---

## 7. Tài liệu tham khảo

-
