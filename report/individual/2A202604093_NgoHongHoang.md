# Báo cáo cá nhân — 2A202604093_NgoHongHoang

## 1. Thông tin học viên

- Họ tên: Ngô Hồng Hoàng
- MSSV: 2A202604093
- Email trường: Không công khai
- Tên nhóm: The Return of the Kings
- Link repo nhóm: https://github.com/HoangHongNgo/K5-L3B-DAY02-TheReturnOfTheKings-DiscoveryProblemFraming

> **Phạm vi bằng chứng:** Sáu vấn đề trong CP1 đều là ý tưởng tôi tự nêu để nhóm cân nhắc. Với #2–6, bằng chứng hiện có đến từ nguồn công khai, **chưa phải kết quả quan sát cá nhân hoặc phỏng vấn của tôi**. Các số liệu dưới đây mô tả đúng quần thể và thời điểm của từng nguồn, không phải baseline của nhóm. Số phút trong CP2 là **giả định để lập quy trình nháp**, cần đo với người thật trước khi quyết định.

---

## 2. Scan problem (CP1)

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật, nguồn và giới hạn |
|---:|---|---|---|---|
| 1 | Lặp lại; cần đọc, tổng hợp | Khi bắt đầu một câu hỏi nghiên cứu, tôi muốn lọc và đối chiếu các bài báo liên quan hoặc gần liên quan, để xác định bài cần đọc sâu và không bỏ sót công trình quan trọng. | Nhà khoa học, nghiên cứu sinh | **Vấn đề tôi nêu, chưa tự đo thời gian.** PubMed có hơn **40 triệu** trích dẫn/tóm tắt trong lĩnh vực y sinh; đó là quy mô kho tài liệu, không phải số bài một người phải đọc [1]. Một thử nghiệm sàng lọc báo cáo trung vị **17–19 giây/trích dẫn** cho tiêu đề/tóm tắt, không phải thời gian đọc toàn văn [2]. |
| 2 | Pain từ người khác; tốn thời gian | Khi nhận tin nhắn, cuộc gọi hoặc bài đăng có dấu hiệu mạo danh, người dùng muốn kiểm tra nguồn và yêu cầu thanh toán, để không chuyển tiền hay tiết lộ thông tin nhầm. | Người dùng mạng, đặc biệt người dễ bị lừa đảo | **Candidate từ dữ liệu công khai.** FTC ghi nhận hơn **1 triệu** báo cáo lừa đảo mạo danh và **3,5 tỷ USD** tổn thất được báo cáo tại Mỹ năm 2025 [3]. Đây là số báo cáo ở Mỹ, không phải tỷ lệ trong nhóm hoặc Việt Nam. |
| 3 | Cần đọc, tổng hợp; pain từ người khác | Khi định chia sẻ một tin đang lan truyền, người tạo nội dung muốn kiểm tra claim và nguồn gốc, để không phát tán thông tin sai. | Người tạo nội dung, người đọc | **Candidate từ khảo sát.** UNESCO khảo sát **500** người tạo nội dung ở **45** quốc gia/vùng lãnh thổ; **62%** cho biết không kiểm tra tính chính xác trước khi chia sẻ [4]. Mẫu này không đại diện cho mọi người dùng mạng. |
| 4 | Pain từ người khác; cấp thiết | Khi có cảnh báo nắng nóng cực đoan, người chăm sóc muốn hiểu ai có nguy cơ và cần làm gì trong ngày, để giảm phơi nhiễm cho người dễ tổn thương. | Người cao tuổi, người bệnh nền, người chăm sóc | **Candidate sức khỏe, chưa phỏng vấn.** WHO ước tính **61.672** ca tử vong vượt mức liên quan đến nắng nóng ở châu Âu mùa hè 2022 [5]. Đây là ước tính khu vực và năm cụ thể, không đo tác động của thông báo. |
| 5 | Pain từ người khác; cấp thiết | Khi trường phải nghỉ vì lũ, bão hoặc nắng nóng, học sinh và giáo viên muốn biết kế hoạch học bù đáng tin cậy, để không mất tiến độ học. | Học sinh, giáo viên, phụ huynh | **Candidate từ báo cáo.** UNICEF ước tính ít nhất **171 triệu** học sinh bị gián đoạn học do biến cố khí hậu trong năm 2025 [6]. Chưa biết một trường cụ thể đang phối hợp thông báo ra sao. |
| 6 | Pain từ người khác; cấp thiết | Khi được kê nhiều thuốc hoặc đổi liều, bệnh nhân muốn đối chiếu hướng dẫn dùng thuốc và chỗ chưa rõ với nhân viên y tế, để tránh dùng sai. | Bệnh nhân, người chăm sóc, nhân viên y tế | **Candidate y tế, chưa phỏng vấn.** WHO nêu khoảng **5%** bệnh nhân trên toàn cầu gặp tổn hại liên quan thuốc có thể phòng tránh [7]. Không suy ra vấn đề chủ yếu là bệnh nhân đọc sai hướng dẫn; cần xác minh nguyên nhân tại bối cảnh cụ thể. |

**AI hỗ trợ tra cứu và thảo luận:** Tôi tự nêu sáu candidate. AI giúp tìm các nguồn FTC, UNESCO, WHO và UNICEF để đối chiếu số liệu, rồi cùng tôi thảo luận actor, tình huống và cách đo. Tôi giữ Job Story ở dạng vấn đề thay vì biến thành ý tưởng “xây chatbot”, và tránh nhận định quá rộng như “mọi người đều bị quá tải thông tin”.

**Khoảng trống CP1:** Với #2–6, bằng chứng hiện mới là **nghiên cứu thứ cấp**. Trước khi dùng làm bằng chứng cá nhân, cần hỏi về một sự kiện đã xảy ra, ai thực hiện bước nào, mất bao lâu, gặp mấy lần; không hỏi “bạn có muốn dùng ứng dụng này không?”.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Lọc và đối chiếu bài báo liên quan | Bắt đầu từ pain tôi nêu; có thể pilot với một câu hỏi nghiên cứu và nhóm nghiên cứu sinh | Chưa có baseline cá nhân, tần suất hay số bài bị bỏ sót |
| 2 | Kiểm tra tin nhắn/bài đăng mạo danh | Nhiều báo cáo tổn thất; actor và điểm quyết định trước khi chuyển tiền rõ | Dữ liệu FTC là ở Mỹ; cần kiểm chứng tại Việt Nam, nhất là hành vi kiểm tra thực tế |
| 3 | Kiểm chứng claim trước khi chia sẻ | Có tín hiệu hành vi từ khảo sát UNESCO; có thể thử với người tạo nội dung hoặc nhóm sinh viên | 62% không đại diện cho mọi người; chưa biết bước nghẽn là tìm nguồn, đọc nguồn hay thiếu động lực |

### Problem Card #1 — Lọc và đối chiếu bài báo

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu một câu hỏi nghiên cứu, tôi muốn lọc và đối chiếu các bài báo liên quan hoặc gần liên quan, để xác định bài cần đọc sâu và không bỏ sót công trình quan trọng. |
| Actor | Nghiên cứu sinh/nhà nghiên cứu đang khảo sát một chủ đề hẹp. |
| Thời điểm / bối cảnh | Bắt đầu đề tài, chuẩn bị related work hoặc chọn baseline. |
| Quy trình hiện tại (5 bước) | Đặt câu hỏi và tiêu chí → tìm trên cơ sở dữ liệu → lọc tiêu đề/tóm tắt → đọc bài đủ liên quan, trích xuất phương pháp/kết quả → đối chiếu, tìm tiếp nếu thiếu. |
| Bottleneck | **Giả thuyết:** bước 4, đọc và trích xuất thông tin để so sánh, khoảng **30 phút/bài** trong kịch bản pilot; chưa bấm giờ. |
| Impact | Có thể trì hoãn quyết định nghiên cứu hoặc bỏ sót bài phản bác. Chưa đo tỷ lệ bỏ sót. |
| Success metric (baseline → target) | **Baseline chưa đo:** bấm giờ 3 phiên, mỗi phiên 10 bài ứng viên, ghi phút từng bước và số bài liên quan bỏ sót khi người thứ hai rà soát. **Target đề xuất:** giảm ≥25% median phút/phiên, số bài bỏ sót không tăng. |
| Phương án không dùng AI | Tiêu chí vào/loại viết trước; quản lý DOI/Zotero; bảng trích xuất cố định; hai người kiểm tra bài sát ranh giới. |
| Giả thuyết về AI | Soạn nháp bảng trích xuất có đoạn/trang nguồn; người nghiên cứu kiểm tra từng claim trong PDF gốc. |
| Cảm nhận nhanh | Chưa biết; thử template và quy trình trước, cân nhắc Workflow nếu vẫn nghẽn. |

Quy trình nháp — **toàn bộ phút là giả định cho 10 bài ứng viên**:

```text
[Đặt câu hỏi/tiêu chí: 10'] → [Tìm bài: 15'] → [Lọc tóm tắt: 20']
→ [Đọc sâu 3 bài + trích xuất: 90'] ← BOTTLENECK giả định
→ [Đối chiếu và tìm tiếp: 25']
Tổng giả định: 160'/phiên. Cần bấm giờ.
```

### Problem Card #2 — Kiểm tra dấu hiệu mạo danh trước khi hành động

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận tin nhắn, cuộc gọi hoặc bài đăng có dấu hiệu mạo danh, người dùng muốn kiểm tra nguồn và yêu cầu thanh toán, để không chuyển tiền hay tiết lộ thông tin nhầm. |
| Actor | Người nhận thông điệp; pilot nên tập trung một nhóm, chẳng hạn sinh viên nhận tin tuyển dụng/học bổng. |
| Thời điểm / bối cảnh | Ngay trước khi bấm link, cung cấp thông tin hoặc chuyển tiền. |
| Quy trình hiện tại (5 bước) | Nhận thông điệp → đọc lời đề nghị/yêu cầu → xem tài khoản, link, số liên hệ → tìm kênh chính thức độc lập → quyết định bỏ qua/báo cáo/tiếp tục. |
| Bottleneck | **Giả thuyết:** bước 4, tìm và đối chiếu kênh chính thức, **10 phút/thông điệp**; chưa đo. |
| Impact | Quyết định sai có thể gây mất tiền hoặc lộ thông tin. FTC ghi nhận quy mô lớn tại Mỹ [3], chưa chứng minh quy mô tại nhóm pilot. |
| Success metric (baseline → target) | **Baseline chưa đo:** 20 thông điệp đã gỡ thông tin cá nhân, có đáp án được người kiểm tra xác minh; ghi phút/ca, số vụ lừa bị bỏ sót và số thông điệp hợp lệ bị báo nhầm. **Target đề xuất:** giảm ≥30% thời gian kiểm tra, **0** vụ lừa bị bỏ sót trong bộ pilot; báo nhầm không tăng. |
| Phương án không dùng AI | Checklist dấu hiệu, không bấm link trong tin nhắn, tự tìm tên tổ chức trên kênh chính thức, xác minh qua số liên hệ lấy từ website chính thức. |
| Giả thuyết về AI | Gợi ý điểm bất thường và câu hỏi cần xác minh; không kết luận “an toàn” hay tự mở link/chuyển tiền. |
| Cảm nhận nhanh | Rule/checklist trước; chỉ cân nhắc Workflow nếu văn bản mạo danh đa dạng làm rule không đủ. |

Quy trình nháp — **phút giả định cho một thông điệp**:

```text
[Nhận: 1'] → [Đọc yêu cầu: 2'] → [Xem tài khoản/link: 3']
→ [Tìm kênh chính thức để đối chiếu: 10'] ← BOTTLENECK giả định
→ [Quyết định/báo cáo: 2']
Tổng giả định: 18'/thông điệp. Cần quan sát.
```

### Problem Card #3 — Kiểm chứng claim trước khi chia sẻ

| Trường | Nội dung |
|---|---|
| Job Story | Khi định chia sẻ một tin đang lan truyền, người tạo nội dung muốn kiểm tra claim và nguồn gốc, để không phát tán thông tin sai. |
| Actor | Người tạo nội dung hoặc quản trị trang cộng đồng; pilot với một nhóm cụ thể. |
| Thời điểm / bối cảnh | Trước khi đăng lại một claim về sự kiện, số liệu hoặc sức khỏe. |
| Quy trình hiện tại (5 bước) | Đọc bài gốc → tách claim kiểm chứng được → truy nguồn đầu tiên → đối chiếu nguồn độc lập và ngày/bối cảnh → đăng kèm nguồn, hoãn hoặc không đăng. |
| Bottleneck | **Giả thuyết:** bước 3, tìm nguồn đầu tiên của claim, **15 phút/claim**; chưa đo. |
| Impact | Chia sẻ sai có thể làm nhiều người hiểu nhầm; khảo sát UNESCO cho thấy hành vi không kiểm tra nguồn ở mẫu người tạo nội dung [4]. |
| Success metric (baseline → target) | **Baseline chưa đo:** 15 claim công khai, ghi phút/claim và tỷ lệ dẫn đúng nguồn gốc do hai người kiểm tra độc lập. **Target đề xuất:** ≥90% claim có nguồn gốc và bối cảnh kiểm được, median thời gian không tăng quá 20%. |
| Phương án không dùng AI | Checklist “ai nói, bằng chứng gốc, ngày, bối cảnh”; tra nguồn chính thức và công bố đường dẫn; không đăng khi chưa kiểm được. |
| Giả thuyết về AI | Gợi ý các claim cần kiểm và từ khóa tìm nguồn; người đăng mở nguồn, đánh giá và chịu trách nhiệm quyết định. |
| Cảm nhận nhanh | No AI/checklist trước; Workflow chỉ khi đã chứng minh bước tìm nguồn tốn thời gian. |

Quy trình nháp — **phút giả định cho một claim**:

```text
[Đọc bài: 3'] → [Tách claim: 5']
→ [Tìm nguồn gốc: 15'] ← BOTTLENECK giả định
→ [Đối chiếu ngày/bối cảnh: 10'] → [Đăng/hoãn: 2']
Tổng giả định: 35'/claim. Cần quan sát.
```

### Card muốn pitch nhất

- Card số: **1**.
- Vì sao: Xuất phát từ vấn đề tôi nêu, gần bối cảnh học thuật của nhóm và có pilot nhỏ có thể làm trước khi chọn giải pháp.
- Câu hỏi muốn nhóm phản biện: “Trong một phiên khảo sát 10 bài gần nhất, bước nào thật sự mất thời gian nhất? Chúng ta đã bỏ sót bài nào khi chỉ xem tiêu đề/tóm tắt?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1 dễ biến quy mô PubMed thành bằng chứng tôi phải đọc quá nhiều. | Có | Ghi rõ 40 triệu là quy mô kho; baseline cá nhân chưa đo. |
| Card #2 có thể khuyến khích giao quyết định an toàn cho AI. | Có | Ưu tiên checklist, kênh chính thức và con người quyết định; đo cả bỏ sót lừa đảo lẫn báo nhầm. |
| Card #3 có thể dùng tốc độ làm metric khiến người đăng kiểm tra hời hợt. | Có | Ưu tiên tỷ lệ claim có nguồn và bối cảnh đúng; giới hạn thời gian tăng tối đa 20%. |
| Ba card dùng số liệu quốc tế để suy ra pain tại Việt Nam. | Có | Giữ là candidate, chỉ chọn sau khi phỏng vấn/pilot đúng nhóm người dùng. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

Chưa có hoạt động nhóm được cung cấp. Phần này cần ghi sau khi pitch, phản biện và kiểm chứng thật.

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Tra cứu nguồn cho sáu vấn đề tôi tự nêu; thảo luận cách viết Job Story và dấu hiệu cần đo. | Tìm số liệu có nguồn từ FTC, UNESCO, WHO, UNICEF và giúp làm rõ phạm vi từng vấn đề. | Số liệu quốc tế không tự chứng minh pain của tôi hoặc nhóm tại Việt Nam. | Ghi rõ quần thể, năm, giới hạn nguồn; đánh dấu các dấu hiệu chưa được kiểm chứng bằng quan sát hay phỏng vấn. |
| CP2 Problem Card | Thảo luận và phản biện ba card tôi chọn, tập trung vào bottleneck, metric và rủi ro. | Giúp tôi nhận ra chỉ đo tốc độ là chưa đủ và không nên giao quyết định an toàn cho AI. | Các số phút trong quy trình chỉ là ước lượng, chưa có baseline quan sát. | Gắn nhãn giả định, bổ sung cách đo thực tế, phương án không AI và tiêu chí chất lượng. |
| CP4 Research | Chưa làm | — | — | — |
| CP5 Quy trình | Chưa làm | — | — | — |
| CP5–6 Problem Statement | Chưa làm | — | — | — |
| CP6 Mức can thiệp / quyết định | Chưa làm | — | — | — |

## 6. Reflection (CP7)

Chưa viết. Theo RULES.md, phần này phải do tôi tự viết từ trải nghiệm thật sau CP3–CP6; AI không viết thay.

## 7. Tài liệu tham khảo

1. National Library of Medicine, *About PubMed*: https://pubmed.ncbi.nlm.nih.gov/about/
2. *Title and Abstract Screening and Evaluation in Systematic Reviews* (TASER pilot trial): https://pmc.ncbi.nlm.nih.gov/articles/PMC4217707/
3. Federal Trade Commission, *New trends in reports of imposter scams* (2026): https://consumer.ftc.gov/consumer-alerts/2026/05/new-trends-reports-imposter-scams
4. UNESCO, *Behind the Screens* (2024), khảo sát 500 người tạo nội dung: https://www.unesco.org/en/articles/shared-frontlines-unesco-bridges-gap-between-journalists-and-content-creators-age-doubt
5. WHO, *Heat and health*: https://www.who.int/en/news-room/fact-sheets/detail/climate-change-heat-and-health
6. UNICEF, *Learning Interrupted: Global Snapshot on Climate-related School Disruptions in 2025* (2026): https://www.unicef.org/reports/learning-interrupted
7. WHO, *Global patient safety report 2024*: https://iris.who.int/bitstream/handle/10665/376928/9789240095458-eng.pdf

