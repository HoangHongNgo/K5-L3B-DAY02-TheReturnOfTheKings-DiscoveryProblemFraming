# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> **Trạng thái:** Nhóm trưởng chọn đề tài #1 và cung cấp ghi chú **một cuộc phỏng vấn thật với lab coach ngày 09/11/2026**. Buổi pitch/phản biện ở mục 2 là **mô phỏng giả định**, không phải lời nói hay hoạt động đã xác nhận của các thành viên. Chưa có baseline bấm giờ; mốc 90 phút là lời kể của một người. Phân tích và quyết định bên dưới cần nhóm rà soát sau khi thu thập thêm bằng chứng.

## 1. Thông tin nhóm

- Tên nhóm: The Return of the Kings
- Thành viên: xem `TEAM.md` và ba báo cáo cá nhân trong `report/individual/`
- Candidate problem nhóm trưởng chọn: Khi bắt đầu khảo sát một chủ đề, nhà nghiên cứu mất thời gian tìm và chọn bài liên quan, đồng thời có nguy cơ bỏ sót bài mới hoặc ít trích dẫn.
- Quyết định tạm thời: **Not Yet** — có một tín hiệu từ lab coach; cần đo và phỏng vấn thêm trước khi chọn mức can thiệp.

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch và phản biện mô phỏng

Chín candidate lấy từ **top 3 trong báo cáo cá nhân** của ba thành viên. Các câu hỏi dưới đây là **kịch bản mô phỏng do AI soạn theo vai trò thành viên**, không khẳng định họ đã hỏi hoặc đồng ý với câu trả lời. Nhóm cần thay bằng biên bản thật nếu đã trao đổi.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck giả thuyết | Câu hỏi phản biện mô phỏng (người giả định hỏi) |
|---:|---|---|---|---|---|
| 1 | Ngô Hồng Hoàng | Lọc và đối chiếu bài báo liên quan | Nghiên cứu sinh | **Tìm và chọn bài**, theo lab coach | Nguyễn Quang Thành (giả định): “Mất thời gian ở tìm bài hay đọc bài?” |
| 2 | Ngô Hồng Hoàng | Kiểm tra thông điệp mạo danh trước khi hành động | Người nhận tin | Tìm kênh chính thức để đối chiếu | Đào Đức Sơn (giả định): “Có mẫu tin đã kiểm chứng để thử không?” |
| 3 | Ngô Hồng Hoàng | Kiểm chứng claim trước khi chia sẻ | Người tạo nội dung | Tìm nguồn gốc claim | Nguyễn Quang Thành (giả định): “Người đăng có sẵn sàng hoãn đăng để kiểm nguồn?” |
| 4 | Nguyễn Quang Thành | Ghi nhớ ngày quan trọng và sở thích của người yêu | Người trong mối quan hệ | Ghi lại và tìm lại thông tin | Ngô Hồng Hoàng (giả định): “Đây là pain lặp lại hay chỉ là một lần quên?” |
| 5 | Nguyễn Quang Thành | Phân việc và theo dõi tiến độ nhóm | Nhóm sinh viên | Gom thông tin từ nhiều kênh | Đào Đức Sơn (giả định): “Nút thắt do công cụ hay do phân công?” |
| 6 | Nguyễn Quang Thành | Ôn từ vựng để nhớ lâu | Người học ngoại ngữ | Duy trì lịch ôn và luyện tập | Ngô Hồng Hoàng (giả định): “Có log ôn tập và quên từ không?” |
| 7 | Đào Đức Sơn | Đồng bộ UI nhân vật giữa các Roblox place | Nhà phát triển game | Kiểm tra nhiều place sau thay đổi | Nguyễn Quang Thành (giả định): “Có thể cấu hình một nguồn chung không?” |
| 8 | Đào Đức Sơn | Lọc tin tuyển dụng phù hợp | Người tìm việc | Đọc và so sánh JD trên nhiều nguồn | Ngô Hồng Hoàng (giả định): “Bộ lọc sẵn có bỏ sót tin phù hợp nào?” |
| 9 | Đào Đức Sơn | Tìm nguyên nhân lỗi combat qua nhiều module | Nhà phát triển game | Lần theo log và module | Nguyễn Quang Thành (giả định): “Có log của một lỗi cụ thể để đo thời gian không?” |

**Đổi hướng sau tín hiệu thật:** Card #1 của Hoàng ban đầu giả định đọc toàn văn là bottleneck. Lab coach nói khó khăn lớn nhất nằm ở **tìm kiếm**; vì vậy nhóm cần tập trung câu hỏi và quy trình vào bước tìm/chọn bài, không tiếp tục lấy thời gian đọc PDF làm pain chính.

### 2.2. Cluster đề xuất

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — tìm và đối chiếu thông tin | #1, #2, #3, #8 | Nhiều nguồn; phải quyết định dựa trên thông tin có độ tin cậy khác nhau |
| B — ghi nhớ và phối hợp | #4, #5, #6 | Thông tin rải rác, dễ quên hoặc khó duy trì hành động lặp lại |
| C — kiểm tra hệ thống kỹ thuật | #7, #9 | Nhiều thành phần; cần lần theo luồng và xác nhận thay đổi |

### 2.3. Opportunity Solution Tree rút gọn cho đề tài được chọn

Ba nhánh dưới đây là pain **trong lĩnh vực khảo sát tài liệu**, không phải tên công cụ. Cluster B và C ở bảng trên nằm ngoài outcome này.

```text
OUTCOME: Giảm thời gian xác định tập bài phù hợp mà không tăng số bài quan trọng bị bỏ sót
├── Opportunity A: khó mở rộng từ khóa mà vẫn giữ đúng phạm vi chủ đề
├── Opportunity B: khó phát hiện bài mới hoặc ít trích dẫn khi tìm theo độ nổi bật
└── Opportunity C: kết quả từ các lượt/công cụ tìm kiếm khác nhau thiếu ổn định
```

Ví dụ solution đội lốt opportunity cần gạch bỏ: “làm chatbot đọc PDF”, “tự động viết related work”, “xây agent nghiên cứu”. Chúng là cách can thiệp có thể thử **sau** khi xác nhận bước nghẽn.

### 2.4. Chấm điểm shortlist đề xuất (1–5)

Điểm dưới đây là **đánh giá sơ bộ để thảo luận**, không phải điểm đã được cả nhóm chấm. Card #1 đã có một cuộc phỏng vấn nhưng chưa có đo log hoặc người thứ hai.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được 4 mức | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Tìm và chọn bài liên quan (#1) | 5 | 5 | 3 | 4 | 5 | 5 | 4 | **31** |
| Lọc tin tuyển dụng (#8) | 5 | 4 | 2 | 4 | 5 | 4 | 3 | **27** |
| Phối hợp công việc nhóm (#5) | 5 | 4 | 2 | 4 | 4 | 3 | 4 | **26** |

**Candidate được nhóm trưởng chọn:** #1 — tìm và chọn bài báo liên quan.

**Vì sao chọn:** Lab coach nói tìm gần như mỗi ngày và cần khoảng 90 phút để chọn bài liên quan. Có thể pilot trên một chủ đề hẹp, đo thời gian và kiểm tra bài mới/ít trích dẫn bị bỏ sót. Đây mới là một người được hỏi.

**Vì sao chưa chọn hai candidate còn lại:** #8 cần xác định một nhóm ứng tuyển và chất lượng danh sách việc làm; #5 cần tách nguyên nhân do công cụ, phân công hay trách nhiệm cá nhân. Cả hai vẫn có thể quay lại nếu kiểm chứng #1 không ủng hộ.

**Xử lý bất đồng:** Câu hỏi ở 2.1 chỉ là mô phỏng; chưa có bất đồng thật để ghi nhận.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

Thang bằng chứng: 1 = chưa có dữ liệu tại nhóm người dùng; 5 = có quan sát lặp lại. Các điểm là đánh giá sơ bộ.

| # | Giả định | Loại | Quan trọng | Đã có bằng chứng | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Việc tìm/chọn bài liên quan lặp lại gần như hằng ngày ở người dùng mục tiêu | Value | 5 | 3 | Có; mới có 1 lab coach |
| 2 | Tìm kiếm, không phải đọc sâu, là bước nghẽn chính | Value | 5 | 3 | Có; cần bấm giờ và hỏi thêm |
| 3 | Tìm bằng một prompt/công cụ có thể bỏ sót bài mới hoặc ít citation | Feasibility | 5 | 2 | Có; coach kể một tình huống, chưa kiểm tập chuẩn |
| 4 | Có thể viết tiêu chí liên quan, từ khóa đồng nghĩa và phạm vi chủ đề đủ rõ | Usability | 5 | 2 | Có |
| 5 | Tìm nhiều nguồn + sắp theo ngày + gộp DOI sẽ tăng coverage mà vẫn tiết kiệm thời gian | Feasibility | 5 | 1 | Có |
| 6 | Người dùng chấp nhận kiểm lại bài được AI gợi ý, không giao Agent tự chọn | Viability | 4 | 1 | Sau pilot |

**Giả định ưu tiên:** #2–3 và #5; lời kể của một coach đã định hướng lại bottleneck, nhưng cần đo trực tiếp và kiểm tra bài bị bỏ sót.

### 3.2. Kiểm chứng với người thật

**Interview Snapshot — 1 người thật, theo ghi chú do nhóm trưởng cung cấp:**

| Mục | Ghi nhận |
|---|---|
| Người được hỏi | Lab coach của nhóm trưởng; không ghi tên để giữ riêng tư |
| Thời điểm | 09/11/2026 theo ngày nhóm trưởng cung cấp thông tin; hình thức phỏng vấn chưa ghi rõ |
| Lần gần nhất | Tìm bài **hôm nay**; tìm gần như mỗi ngày |
| Thời gian | Khoảng **1 giờ 30 phút** để tìm và chọn các bài liên quan trong một lần; đây là tự thuật, chưa bấm giờ |
| Cách chọn bài đào sâu | Xem từ khóa và mức độ bài nằm trong mảng lớn của chủ đề nghiên cứu |
| Khó khăn chính | **Bước tìm kiếm** bài liên quan |
| Công cụ và rủi ro | Chưa dùng Agent. Dù prompt chi tiết, có thể sót bài mới hoặc ít trích dẫn. Coach kể có lần dùng ChatGPT và Claude tìm hai lượt với cùng prompt nhưng nhận kết quả khác nhau. |

Các dòng trên là **diễn ý từ ghi chú của nhóm trưởng**, không phải trích dẫn nguyên văn hoặc kết quả kiểm thử độc lập. Khác biệt giữa hai lần tìm là một quan sát được kể lại; chưa đủ để kết luận công cụ nào thiếu chính xác hơn.

**Ba câu hỏi cho 1–2 người nghiên cứu ngoài nhóm tiếp theo** (nếu yêu cầu 2–3 phỏng vấn) hoặc survey 5–10 người:

1. “Lần gần nhất bạn tìm bài cho một câu hỏi nghiên cứu là khi nào? Bạn dùng những nguồn, từ khóa và bước lọc nào; mất bao lâu từ lúc bắt đầu đến danh sách bài giữ lại?”
2. “Trong lần đó, bạn phát hiện bài phù hợp bị bỏ sót hoặc kết quả khác nhau giữa các lượt tìm không? Bạn phát hiện bằng cách nào, bài mới/ít trích dẫn có bị ảnh hưởng không?”
3. “Bạn quyết định đào sâu một bài dựa vào dấu hiệu nào, xử lý bài gần liên quan ra sao, và bước nào làm bạn chậm nhất?”

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác / giới hạn |
|---|---:|---|---|
| Phỏng vấn lab coach | **1** | Tìm gần như hằng ngày; khoảng 90 phút/lần; khó nhất là tìm; lo sót bài mới/ít trích dẫn | Chưa đo thời gian theo bước, chưa kiểm danh sách bài bị sót; chỉ một người |
| Phỏng vấn/survey tiếp theo | **0** | Chưa có | Chưa có |

**Sửa problem sau phỏng vấn:** Chuyển bottleneck giả định từ đọc/trích xuất toàn văn sang **tìm và chọn tập bài liên quan**. Mốc 90 phút là tín hiệu định hướng cho phép đo, chưa phải baseline có kiểm chứng.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link đã mở | Giải bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học |
|---|---|---|---|---|---|
| PubMed: truy vấn nâng cao, lọc và sắp theo ngày | [PubMed Help](https://pubmed.ncbi.nlm.nih.gov/help/) | Tìm trong nguồn y sinh và xem kết quả mới | Có thể lưu truy vấn, dùng bộ lọc ngày và sắp theo Most Recent/Publication Date | Phạm vi y sinh; bài chưa được lập chỉ mục hoặc ngoài nguồn vẫn có thể sót | Không dựa vào một nguồn hay một kiểu sắp xếp |
| OpenAlex: tìm và sắp kết quả | [Search](https://help.openalex.org/how-to/searching/) · [Sort](https://help.openalex.org/api/sorting/) | Mở rộng tìm kiếm học thuật theo từ khóa và metadata | Có thể đối chiếu kết quả theo độ liên quan, ngày và số trích dẫn | Chỉ sắp theo trích dẫn dễ đẩy bài mới/ít trích dẫn xuống thấp; độ phủ cần kiểm từng lĩnh vực | Đối chiếu cả kết quả gần đây và kết quả liên quan |
| Rayyan: nhập tài liệu và sàng lọc | [Hướng dẫn Rayyan](https://help.rayyan.ai/hc/en-us/articles/22697630697617-Getting-Started-with-Rayyan) | Gộp danh sách tìm được, loại trùng và gắn lý do giữ/loại | Hỗ trợ quy trình sàng lọc có thể kiểm lại | Không thay thế bước tìm kiếm trên cơ sở dữ liệu | Dùng cho sàng lọc sau khi tìm, không coi là nguồn tìm chính |
| Elicit: tìm và sàng lọc với AI | [Hướng dẫn Elicit](https://support.elicit.com/en/articles/14759154-systematic-reviews-in-elicit) | Gợi ý bài và hỗ trợ đánh giá liên quan | Thêm một cách tìm để so với truy vấn thủ công | [Giới hạn được công bố](https://support.elicit.com/en/articles/14757928-elicit-s-limitations); không bảo đảm đủ mọi bài | Chỉ dùng như nguồn gợi ý, kiểm bài gốc và đối chiếu danh sách chuẩn |

**Kết luận research:** Đã có công cụ cho tìm kiếm và sàng lọc. Chưa có dữ liệu cho thấy một công cụ đơn lẻ hoặc Agent tìm đủ bài, nhất là bài mới/ít trích dẫn. Pilot trước tiên cần so các nguồn và ghi rõ bài tìm được ở từng nguồn.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại — dựng từ phỏng vấn

```text
[Xác định mảng chủ đề và từ khóa] → [Tìm bài, có thể dùng prompt chi tiết]
→ [Xem từ khóa và vị trí bài trong mảng chủ đề] → [Chọn bài để đào sâu]
                 ↑ BOTTLENECK được coach nêu: tìm kiếm
Khoảng 90 phút cho việc tìm và chọn bài trong một lần, theo tự thuật của 1 coach.
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Lab coach | Mảng nghiên cứu đang theo đuổi | Phạm vi tìm | Chưa đo riêng; tìm gần như mỗi ngày | Phạm vi có thể rộng |
| 2 | Lab coach | Từ khóa, prompt và nguồn tìm | Danh sách bài ứng viên | Chưa đo riêng | Coach nêu đây là bước khó nhất |
| 3 | Lab coach | Từ khóa của bài, vị trí trong mảng chủ đề | Bài được chọn để đọc sâu | Chưa đo riêng | Có nguy cơ sót bài mới/ít trích dẫn |
| 4 | Lab coach | Danh sách ứng viên | Quyết định tìm tiếp hoặc dừng | Chưa đo riêng | Kết quả có thể khác giữa công cụ/lượt tìm |

Không suy ra số phút cho từng bước hoặc số bài mỗi phiên vì người được hỏi chưa cung cấp. Tổng 90 phút cũng chưa được đo độc lập.

### 4.2. Quy trình tương lai để pilot — No AI + Rule nhỏ

```text
[Người: chốt câu hỏi, tiêu chí và từ khóa đồng nghĩa]
→ [Người: tìm ít nhất 2 nguồn; xem cả kết quả mới và liên quan]
→ [Rule: gộp DOI trùng; người xem bài thiếu DOI]
→ [Người: xét tiêu đề/tóm tắt, gắn lý do giữ/loại/chưa chắc]
→ [Người thứ hai: kiểm bài ranh giới và tập bài chuẩn đã biết]
Mục tiêu thử nghiệm: ≤60 phút/lượt tìm và không bỏ sót bài chuẩn.
Boundary: người nghiên cứu quyết định giữ/loại; chưa dùng Agent.
Quay về: nếu bỏ sót bài chuẩn hoặc thời gian không cải thiện, sửa cách tìm.
```

Mốc 60 phút là **mục tiêu pilot do báo cáo đề xuất**, chưa phải kết quả. Nguồn tìm cần chọn theo lĩnh vực; PubMed chỉ phù hợp khi chủ đề thuộc phạm vi y sinh.

### 4.3. Before / after

| Chỉ số | Trước (coach tự thuật; chưa đo) | Sau (mục tiêu pilot) | Cách kiểm |
|---|---:|---:|---|
| Số bước | 4 bước mô tả | 5 bước đề xuất | Quan sát và ghi thao tác thực tế |
| Thời gian/lượt tìm và chọn | Khoảng 90', một người tự thuật | Mục tiêu ≤60', chưa thử | Bấm giờ 3 lượt mỗi cách trên chủ đề tương đương; so median |
| Người ra quyết định | Lab coach | Người nghiên cứu, có người kiểm bài ranh giới | Ghi lý do giữ/loại |
| Bottleneck chính | Tìm kiếm, theo coach | Tìm nhiều nguồn có cấu trúc | Đo thời gian theo bước, kiểm lại kết luận |
| Rủi ro mới | Bỏ sót bài mới/ít trích dẫn | Tăng số kết quả nhiễu, tiêu chí quá hẹp, DOI thiếu | Kiểm tập bài chuẩn và bài được nguồn khác phát hiện |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Nghiên cứu sinh/nhà nghiên cứu đang tìm bài cho một câu hỏi nghiên cứu. |
| **Quy trình** | Xác định chủ đề và từ khóa → tìm bài → xét từ khóa, phạm vi và tóm tắt → chọn bài để đào sâu. |
| **Bottleneck** | Tìm kiếm bài liên quan; được một lab coach nêu là bước khó nhất, cần đo ở người khác. |
| **Impact** | Khoảng 90 phút cho một lượt tìm/chọn theo tự thuật của coach; có thể sót bài mới/ít trích dẫn. Chưa đo số bài sót hoặc hậu quả. |
| **Success Metric** | Bấm giờ ít nhất 3 lượt tìm, ghi số bài phù hợp theo tập chuẩn; thử đạt ≤60 phút/lượt mà không bỏ sót bài chuẩn. |
| **Boundary** | Người nghiên cứu tự chốt tiêu chí và bài để đào sâu; mọi gợi ý của công cụ phải kiểm ở nguồn gốc. |

**AI hỗ trợ phản biện bản v0:** “Liên quan” phải có tiêu chí vào/loại; 90 phút chỉ là tự thuật của một người; kết quả khác nhau giữa hai công cụ chưa chứng minh bài nào bị sót. Báo cáo chấp nhận các điểm này và đưa vào kế hoạch đo. Chưa có phản biện thật của nhóm khác.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Độ mơ hồ cao × độ phức tạp trung bình.** Ranh giới “liên quan” phụ thuộc câu hỏi nghiên cứu; tìm trên nhiều nguồn và gộp kết quả có nhiều bước nhưng có thể lập checklist. Đây là đánh giá sơ bộ, cần thử trên một chủ đề cụ thể.

### 6.2. So sánh 4 mức

| Mức | Phương án | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Chốt tiêu chí/từ khóa, tìm hai nguồn, xem cả bài mới, ghi lý do giữ/loại | Giảm thời gian mà giữ được bài chuẩn | Nhiều kết quả nhiễu; tiêu chí có thể sai | **Chọn để pilot** |
| **Rule** | Gộp DOI trùng, checklist nguồn/ngày/từ khóa | Metadata đủ rõ | DOI thiếu hoặc metadata sai có thể gộp nhầm | Dùng như bước nhỏ |
| **Workflow** | AI gợi ý từ khóa đồng nghĩa và bài ứng viên theo các bước cố định; người kiểm từng bài | No AI/Rule đã đo nhưng không đủ, có tập chuẩn để đánh giá | AI gợi ý sai hoặc bỏ sót bài mới/ít trích dẫn | Chưa chọn |
| **Agent** | AI tự đổi truy vấn, chọn nguồn và quyết định danh sách cuối | Chỉ xét khi workflow cố định không đủ và có cách kiểm coverage | Khó truy vết truy vấn, bỏ sót âm thầm | Không chọn |

**Mức chọn hiện tại:** No AI cho pilot; Rule chỉ xử lý việc rõ ràng như trùng DOI. Chưa có dữ liệu chứng minh AI cải thiện thời gian và độ phủ. Lab coach cho biết chưa dùng Agent, nên báo cáo không xem Agent là quy trình hiện tại.

### 6.3. AI Canvas rút gọn

**Chưa áp dụng cho pilot No AI.** Nếu thử Workflow: Input = câu hỏi nghiên cứu, phạm vi, từ khóa và danh sách bài từ nguồn; Prediction = từ khóa đồng nghĩa và bài có thể liên quan; Judgment = người nghiên cứu so tiêu chí và mở trang bài gốc; Action = người sửa truy vấn, chốt bài giữ/loại; Outcome = thời gian tìm, số bài chuẩn được tìm thấy và số bài nhiễu; Feedback = bài bị sót và lý do loại sai. Không tự động chốt danh sách.

### 6.4. Hai câu hỏi Google PAIR

- **Augment hay automate?** Coach đã dùng prompt tìm bài nhưng chưa dùng Agent. Nếu thử AI, AI chỉ gợi ý truy vấn hoặc bài ứng viên; người nghiên cứu chốt danh sách.
- **Báo nhầm hay bỏ sót tệ hơn?** Với mục tiêu không bỏ qua nghiên cứu quan trọng, **bỏ sót** thường đáng lo hơn. Cần xác nhận theo loại review; các bài chưa chắc phải được người xem lại.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Nghiên cứu sinh/nhà nghiên cứu đang khảo sát một câu hỏi nghiên cứu hẹp. |
| **Quy trình** | Chốt tiêu chí/từ khóa → tìm trên ít nhất hai nguồn → xét bài mới và bài liên quan → gộp trùng → ghi lý do giữ/loại → kiểm bài ranh giới. |
| **Bottleneck** | Tìm kiếm bài phù hợp; được lab coach xác nhận bằng tự thuật, chưa đo theo bước. |
| **Impact** | Khoảng 90 phút/lượt tìm và chọn theo một coach; nguy cơ sót bài mới/ít trích dẫn chưa lượng hóa. |
| **Success Metric** | Trong 3 lượt pilot cùng chủ đề hoặc độ khó tương đương: median ≤60 phút/lượt; tìm đủ tập bài chuẩn đã xác định trước; ghi số bài nhiễu. |
| **Boundary** | Người nghiên cứu chốt tiêu chí và bài giữ/loại; kiểm bài gốc, không chỉ tin kết quả prompt hoặc thứ hạng trích dẫn. |
| **AI intervention point** | **Không có trong pilot No AI.** Workflow sau này có thể gợi ý từ khóa và bài ứng viên, với người kiểm. |
| **Mức chọn** | No AI + Rule gộp DOI; chưa chốt AI. |
| **Rủi ro & người kiểm tra** | Một người được hỏi; người nghiên cứu và người kiểm thứ hai xem bài ranh giới, tập bài chuẩn và log truy vấn. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Quy trình | Tìm và xét bài | Thêm hai nguồn, sắp theo mới và kiểm bài ranh giới | Coach lo sót bài mới/ít trích dẫn và kết quả không ổn định |
| Success Metric | Mục tiêu ≤60 phút, không sót bài chuẩn | Ghi rõ 3 lượt và tập chuẩn trước khi thử | 90 phút tự thuật chưa đủ làm baseline chắc chắn |
| Mức can thiệp | Chưa xét | No AI pilot; Workflow chỉ là phương án sau | Chưa có bằng chứng AI tăng độ phủ |

**Tiêu chí đánh giá giải pháp No AI/Rule:**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Truy vết tìm kiếm | Lưu nguồn, truy vấn, ngày tìm, DOI/URL và lý do giữ/loại | Không thể tìm lại bài hoặc giải thích quyết định |
| 2 | Không bỏ sót bài chuẩn | Tìm được 100% bài trong tập chuẩn gồm cả bài mới/ít trích dẫn, do người kiểm lập trước | Thiếu một bài chuẩn hoặc không có tập chuẩn |
| 3 | Thời gian | Median ≤60 phút/lượt qua 3 lượt; so với 3 lượt baseline bấm giờ | Không đạt ngưỡng hoặc không có log thời gian |
| 4 | Nhiễu và nhất quán | Ghi số bài không liên quan phải xét và lý do bất đồng ở bài ranh giới | Nhiễu tăng quá mức hoặc bất đồng không được xử lý |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro của pilot

| Rủi ro | Câu hỏi | Mức độ | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Vấn đề có lặp lại và đủ đau không? | **Trung bình–cao** | Một lab coach tìm gần như hằng ngày, tự thuật khoảng 90 phút/lượt; chưa có người thứ hai và chưa đo hậu quả sót bài |
| **Usability** | Người dùng có duy trì log truy vấn và kiểm chéo không? | **Trung bình** | Thêm thao tác ghi chép và xét kết quả từ nhiều nguồn; chưa thử |
| **Feasibility** | Có thể tìm nhiều nguồn và đối chiếu DOI/metadata không? | **Trung bình** | PubMed/OpenAlex và công cụ sàng lọc có sẵn; độ phủ thay đổi theo lĩnh vực |
| **Viability** | Ai duy trì tập bài chuẩn và kiểm bài ranh giới? | **Trung bình** | Cần người kiểm thứ hai và thời gian duy trì danh sách chuẩn |

### 8.2. Kết luận

**Quyết định đề xuất: Not Yet.** Phỏng vấn lab coach đã xác nhận một trường hợp đau thật ở bước tìm kiếm; chưa đủ mẫu và phép đo để kết luận quy trình mới hoặc AI hiệu quả. Đây là đề xuất của báo cáo, chưa phải quyết định được cả nhóm xác nhận trong một buổi họp thật.

**Cần kiểm chứng trước:** (1) hỏi thêm 1–2 nhà nghiên cứu ngoài nhóm bằng ba câu hỏi ở 3.2 để đạt 2–3 phỏng vấn; (2) bấm giờ 3 lượt tìm và chọn bài, ghi thời gian từng bước; (3) lập trước một tập bài chuẩn gồm bài mới/ít trích dẫn; (4) thử tìm hai nguồn, gộp trùng, kiểm chéo qua 3 lượt; (5) so thời gian, bài chuẩn tìm được và số bài nhiễu.

**Pilot nhỏ nhất nếu đủ bằng chứng:** Một câu hỏi nghiên cứu hẹp, một người tìm, một người lập/kiểm tập bài chuẩn và bài ranh giới. Ghi truy vấn, nguồn, ngày tìm, thời gian và lý do giữ/loại. Không xây công cụ mới.

**Ngưỡng dừng:** Nếu sau 3 lượt thử median vẫn trên 60 phút **hoặc** thiếu bất kỳ bài nào trong tập chuẩn, chưa áp dụng quy trình mới; xem lại truy vấn, nguồn và tiêu chí trước khi thử AI.

---

## 9. Hạn chế và hướng tiếp theo

- Chưa có buổi pitch/phản biện thật; câu hỏi gán cho thành viên là **mô phỏng**, điểm CP3 và OST là đề xuất để nhóm rà soát.
- Đã có **1 phỏng vấn thật** với lab coach. Chưa đủ 2–3 phỏng vấn hoặc survey 5–10 người theo yêu cầu CP4.
- Mốc 90 phút là tự thuật của một người; chưa có baseline bấm giờ hoặc phép kiểm bài bị bỏ sót. Mục tiêu 60 phút cũng chưa được thử.
- Cần hỏi thêm người nghiên cứu, ghi trường hợp phản bác, lập tập bài chuẩn và sửa Problem Statement nếu kết quả đổi hướng.
- CP7 là reflection cá nhân, phải do từng người tự viết sau hoạt động nhóm; không nằm trong báo cáo nhóm này.

## 10. Tài liệu tham khảo

1. Ghi chú phỏng vấn lab coach do nhóm trưởng cung cấp ngày 09/11/2026 — nguồn cho các chi tiết về tần suất, thời gian, cách chọn và khó khăn; chưa có bản ghi âm/biên bản nguyên văn trong repo.
2. National Library of Medicine, [PubMed Help](https://pubmed.ncbi.nlm.nih.gov/help/) — truy vấn, bộ lọc và sắp xếp kết quả.
3. OpenAlex, [Searching](https://help.openalex.org/how-to/searching/) và [Sorting](https://help.openalex.org/api/sorting/) — tìm và sắp kết quả theo các tiêu chí.
4. Rayyan, [Getting Started](https://help.rayyan.ai/hc/en-us/articles/22697630697617-Getting-Started-with-Rayyan) — nhập, gộp và sàng lọc tài liệu.
5. Elicit, [Systematic Reviews](https://support.elicit.com/en/articles/14759154-systematic-reviews-in-elicit) và [Limitations](https://support.elicit.com/en/articles/14757928-elicit-s-limitations) — tính năng tìm/sàng lọc và giới hạn của AI.

