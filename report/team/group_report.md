# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> **Trạng thái:** Nhóm trưởng chọn đề tài #1 và cung cấp ghi chú **hai cuộc phỏng vấn thật với hai lab coach ngày 09/11/2026**. Ý tưởng và nội dung thảo luận thuộc về nhóm trưởng và nhóm; AI chỉ hỗ trợ tư vấn, phản biện và tra cứu tài liệu. Buổi pitch/phản biện ở mục 2 là **kịch bản giả định**, chưa phải biên bản họp thật. Chưa có baseline bấm giờ; các mốc 90 phút/lượt tìm và 1 giờ/ngày là tự thuật của hai người khác nhau, không cộng hoặc so trực tiếp.

## 1. Thông tin nhóm

- Tên nhóm: The Return of the Kings
- Thành viên: xem `TEAM.md` và ba báo cáo cá nhân trong `report/individual/`
- Vai trò AI: nhóm trưởng và nhóm sở hữu ý tưởng, dữ liệu phỏng vấn và hướng thảo luận; AI hỗ trợ tư vấn cách trình bày, phản biện giả định và tra cứu nguồn công khai. Kịch bản pitch ở CP3 chưa phải lời phát biểu thật của thành viên.
- Candidate problem nhóm trưởng chọn: Trong quá trình khảo sát tài liệu, nhà nghiên cứu phải tìm bài liên quan rồi đọc và rút ý chính có thể dùng được. Hai lab coach cùng làm việc này thường xuyên nhưng nêu **hai bước nghẽn khác nhau**.
- Quyết định tạm thời: **Not Yet** — cần đo riêng bước tìm và bước đọc/rút ý trước khi chốt một can thiệp.

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch và phản biện mô phỏng

Chín candidate lấy từ **top 3 trong báo cáo cá nhân** của ba thành viên. Các câu hỏi dưới đây là **kịch bản giả định theo định hướng của nhóm trưởng**, AI hỗ trợ rà soát cách trình bày; không khẳng định các thành viên đã hỏi hoặc đồng ý với câu trả lời. Nhóm cần thay bằng biên bản thật nếu đã trao đổi.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck giả thuyết | Câu hỏi phản biện mô phỏng (người giả định hỏi) |
|---:|---|---|---|---|---|
| 1 | Ngô Hồng Hoàng | Tìm, đọc và rút ý từ bài báo liên quan | Nghiên cứu sinh/nhà nghiên cứu | **Chưa thống nhất:** coach A nghẽn ở tìm; coach B nghẽn ở đọc/rút ý | Nguyễn Quang Thành (giả định): “Mất thời gian ở tìm bài hay đọc và rút ý?” |
| 2 | Ngô Hồng Hoàng | Kiểm tra thông điệp mạo danh trước khi hành động | Người nhận tin | Tìm kênh chính thức để đối chiếu | Đào Đức Sơn (giả định): “Có mẫu tin đã kiểm chứng để thử không?” |
| 3 | Ngô Hồng Hoàng | Kiểm chứng claim trước khi chia sẻ | Người tạo nội dung | Tìm nguồn gốc claim | Nguyễn Quang Thành (giả định): “Người đăng có sẵn sàng hoãn đăng để kiểm nguồn?” |
| 4 | Nguyễn Quang Thành | Ghi nhớ ngày quan trọng và sở thích của người yêu | Người trong mối quan hệ | Ghi lại và tìm lại thông tin | Ngô Hồng Hoàng (giả định): “Đây là pain lặp lại hay chỉ là một lần quên?” |
| 5 | Nguyễn Quang Thành | Phân việc và theo dõi tiến độ nhóm | Nhóm sinh viên | Gom thông tin từ nhiều kênh | Đào Đức Sơn (giả định): “Nút thắt do công cụ hay do phân công?” |
| 6 | Nguyễn Quang Thành | Ôn từ vựng để nhớ lâu | Người học ngoại ngữ | Duy trì lịch ôn và luyện tập | Ngô Hồng Hoàng (giả định): “Có log ôn tập và quên từ không?” |
| 7 | Đào Đức Sơn | Đồng bộ UI nhân vật giữa các Roblox place | Nhà phát triển game | Kiểm tra nhiều place sau thay đổi | Nguyễn Quang Thành (giả định): “Có thể cấu hình một nguồn chung không?” |
| 8 | Đào Đức Sơn | Lọc tin tuyển dụng phù hợp | Người tìm việc | Đọc và so sánh JD trên nhiều nguồn | Ngô Hồng Hoàng (giả định): “Bộ lọc sẵn có bỏ sót tin phù hợp nào?” |
| 9 | Đào Đức Sơn | Tìm nguyên nhân lỗi combat qua nhiều module | Nhà phát triển game | Lần theo log và module | Nguyễn Quang Thành (giả định): “Có log của một lỗi cụ thể để đo thời gian không?” |

**Đổi hướng sau hai tín hiệu thật:** Coach A nêu **tìm kiếm** là bước khó nhất; coach B nêu **đọc và rút ý chính có thể dùng**. Vì vậy không thể gán một bottleneck chung cho mọi người. Báo cáo giữ cả hai nhánh để kiểm chứng trước khi thu hẹp problem.

### 2.2. Cluster đề xuất

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — tìm và đối chiếu thông tin | #1, #2, #3, #8 | Nhiều nguồn; phải quyết định dựa trên thông tin có độ tin cậy khác nhau |
| B — ghi nhớ và phối hợp | #4, #5, #6 | Thông tin rải rác, dễ quên hoặc khó duy trì hành động lặp lại |
| C — kiểm tra hệ thống kỹ thuật | #7, #9 | Nhiều thành phần; cần lần theo luồng và xác nhận thay đổi |

### 2.3. Opportunity Solution Tree rút gọn cho đề tài được chọn

Ba nhánh dưới đây là pain **trong lĩnh vực khảo sát tài liệu**, không phải tên công cụ. Cluster B và C ở bảng trên nằm ngoài outcome này.

```text
OUTCOME: Giảm thời gian khảo sát tài liệu mà vẫn tìm đủ bài quan trọng và rút đúng ý có thể dùng
├── Opportunity A: khó tìm đủ bài phù hợp, nhất là bài mới hoặc ít trích dẫn (coach A)
├── Opportunity B: kết quả tìm kiếm thay đổi giữa các lượt/công cụ (coach A)
└── Opportunity C: khó đọc và rút ý chính phục vụ hướng nghiên cứu (coach B)
```

Ví dụ solution đội lốt opportunity cần gạch bỏ: “làm chatbot đọc PDF”, “tự động viết related work”, “xây agent nghiên cứu”. Chúng là cách can thiệp có thể thử **sau** khi xác nhận bước nghẽn.

### 2.4. Chấm điểm shortlist đề xuất (1–5)

Điểm dưới đây là **đánh giá sơ bộ để thảo luận**, không phải điểm đã được cả nhóm chấm. Card #1 có hai cuộc phỏng vấn, song hai người nêu hai điểm nghẽn khác nhau và chưa có log thời gian.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được 4 mức | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Khảo sát bài báo liên quan (#1) | 5 | 5 | 3 | 4 | 5 | 5 | 4 | **31** |
| Lọc tin tuyển dụng (#8) | 5 | 4 | 2 | 4 | 5 | 4 | 3 | **27** |
| Phối hợp công việc nhóm (#5) | 5 | 4 | 2 | 4 | 4 | 3 | 4 | **26** |

**Candidate được nhóm trưởng chọn:** #1 — khảo sát bài báo liên quan.

**Vì sao chọn:** Cả hai coach tìm bài gần như mỗi ngày. Coach A tự thuật khoảng 90 phút cho một lượt tìm/chọn; coach B dành khoảng 1 giờ mỗi ngày và thấy khó nhất ở đọc/rút ý. Có thể đo từng bước trên một chủ đề hẹp và đối chiếu hai kiểu pain. Chưa suy ra mức phổ biến từ hai người.

**Vì sao chưa chọn hai candidate còn lại:** #8 cần xác định một nhóm ứng tuyển và chất lượng danh sách việc làm; #5 cần tách nguyên nhân do công cụ, phân công hay trách nhiệm cá nhân. Cả hai vẫn có thể quay lại nếu kiểm chứng #1 không ủng hộ.

**Xử lý bất đồng:** Câu hỏi ở 2.1 chỉ là mô phỏng; chưa có bất đồng thật để ghi nhận.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

Thang bằng chứng: 1 = chưa có dữ liệu tại nhóm người dùng; 5 = có quan sát lặp lại. Các điểm là đánh giá sơ bộ.

| # | Giả định | Loại | Quan trọng | Đã có bằng chứng | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Công việc khảo sát bài báo lặp lại gần như hằng ngày | Value | 5 | 3 | Hai coach tự thuật; cần thêm người ngoài mẫu này |
| 2 | Bước tìm kiếm là bottleneck chung của người nghiên cứu | Value | 5 | 2 | Coach A ủng hộ, coach B nêu bước khác |
| 3 | Bước đọc/rút ý chính có thể dùng là bottleneck chung | Value | 5 | 2 | Coach B ủng hộ, coach A nêu bước khác |
| 4 | Tìm bằng một prompt/công cụ có thể bỏ sót bài mới hoặc ít trích dẫn | Feasibility | 5 | 2 | Coach A kể một tình huống, chưa kiểm tập chuẩn |
| 5 | Tiêu chí chọn bài theo từ khóa/phạm vi hoặc venue/hướng nghiên cứu có thể ghi rõ để người khác kiểm lại | Usability | 5 | 2 | Hai coach mô tả cách chọn khác nhau |
| 6 | Quy trình tìm nhiều nguồn và bảng rút ý có nguồn sẽ giảm thời gian mà giữ chất lượng | Feasibility | 5 | 1 | Chưa pilot |

**Giả định ưu tiên:** #2–3 và #6. Hai phỏng vấn xác nhận hoạt động lặp lại nhưng **không xác nhận cùng một bước nghẽn**; cần đo riêng hai bước và kiểm chất lượng đầu ra.

### 3.2. Kiểm chứng với người thật

**Interview Snapshot A — lab coach, theo ghi chú do nhóm trưởng cung cấp:**

| Mục | Ghi nhận |
|---|---|
| Người được hỏi | Lab coach; không ghi tên để giữ riêng tư |
| Thời điểm | 09/11/2026 theo ngày nhóm trưởng cung cấp thông tin; hình thức phỏng vấn chưa ghi rõ |
| Lần gần nhất | Tìm bài **hôm nay**; tìm gần như mỗi ngày |
| Thời gian | Khoảng **1 giờ 30 phút** để tìm và chọn các bài liên quan trong một lần; đây là tự thuật, chưa bấm giờ |
| Cách chọn bài đào sâu | Xem từ khóa và mức độ bài nằm trong mảng lớn của chủ đề nghiên cứu |
| Khó khăn chính | **Bước tìm kiếm** bài liên quan |
| Công cụ và rủi ro | Chưa dùng Agent. Dù prompt chi tiết, có thể sót bài mới hoặc ít trích dẫn. Coach kể có lần dùng ChatGPT và Claude tìm hai lượt với cùng prompt nhưng nhận kết quả khác nhau. |

**Interview Snapshot B — một lab coach khác, theo ghi chú do nhóm trưởng cung cấp:**

| Mục | Ghi nhận |
|---|---|
| Người được hỏi | Lab coach thứ hai; không ghi tên để giữ riêng tư |
| Thời điểm | 09/11/2026 theo lời “hôm nay” của nhóm trưởng; hình thức phỏng vấn chưa ghi rõ |
| Lần gần nhất | Tìm bài **hôm nay**; tìm gần như mỗi ngày |
| Thời gian | Khoảng **1 giờ mỗi ngày** dành cho việc tìm bài, theo tự thuật; chưa rõ thời lượng đọc/rút ý trong ngày |
| Cách chọn bài đào sâu | Dựa vào tạp chí, hội nghị uy tín và mức độ liên quan với hướng nghiên cứu |
| Khó khăn chính | **Đọc bài và rút ý chính có thể dùng được** |
| Công cụ và rủi ro | Tìm qua các tạp chí và hội nghị uy tín; chưa có thông tin về việc dùng AI/Agent hoặc một sự cố cụ thể |

Hai snapshot là **diễn ý từ ghi chú của nhóm trưởng**, không phải trích dẫn nguyên văn hoặc kết quả kiểm thử độc lập. Khác biệt kết quả ChatGPT/Claude do coach A kể lại chưa đủ để kết luận công cụ nào thiếu chính xác hơn. Mốc **90 phút/lượt** và **1 giờ/ngày** khác đơn vị, nên không dùng để tính trung bình hoặc so hiệu suất hai coach.

**Ba câu hỏi bổ sung** nếu phỏng vấn thêm hoặc mở rộng thành survey:

1. “Lần gần nhất bạn khảo sát bài cho một câu hỏi nghiên cứu là khi nào? Hãy đi qua lần lượt các bước tìm, chọn, đọc và ghi ý; mỗi bước mất bao lâu?”
2. “Bạn dựa vào từ khóa, hướng nghiên cứu hay tạp chí/hội nghị để chọn bài? Có bài phù hợp nào bạn phát hiện muộn hoặc phải đọc lại không?”
3. “Khi đọc một bài gần đây, bạn lấy ý chính có thể dùng bằng cách nào, ghi nguồn ở đâu, và bước nào làm bạn chậm nhất?”

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác / giới hạn |
|---|---:|---|---|
| Phỏng vấn coach A | **1** | Tìm gần như hằng ngày; khoảng 90 phút/lượt tìm/chọn; khó nhất là tìm | Chưa bấm giờ, chưa kiểm bài bị sót |
| Phỏng vấn coach B | **1** | Tìm gần như hằng ngày; khoảng 1 giờ/ngày; khó nhất là đọc/rút ý | Chưa rõ thời gian đọc/rút ý, chưa có ví dụ đầu ra cụ thể |
| Survey | **0** | Chưa có | Chưa thể ước lượng mức phổ biến |

**Sửa problem sau hai phỏng vấn:** Giữ quy trình **tìm → chọn → đọc → rút ý**, tách hai cơ hội cải thiện: độ phủ/tốc độ tìm cho coach A và thời gian/chất lượng rút ý cho coach B. Chưa chốt một bottleneck chung hoặc một giải pháp chung. Hai mốc thời gian là tín hiệu định hướng, chưa phải baseline có kiểm chứng.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link đã mở | Giải bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học |
|---|---|---|---|---|---|
| PubMed: truy vấn nâng cao, lọc và sắp theo ngày | [PubMed Help](https://pubmed.ncbi.nlm.nih.gov/help/) | Tìm trong nguồn y sinh và xem kết quả mới | Có thể lưu truy vấn, dùng bộ lọc ngày và sắp theo Most Recent/Publication Date | Phạm vi y sinh; bài chưa được lập chỉ mục hoặc ngoài nguồn vẫn có thể sót | Không dựa vào một nguồn hay một kiểu sắp xếp |
| OpenAlex: tìm và sắp kết quả | [Search](https://help.openalex.org/how-to/searching/) · [Sort](https://help.openalex.org/api/sorting/) | Mở rộng tìm kiếm học thuật theo từ khóa và metadata | Có thể đối chiếu kết quả theo độ liên quan, ngày và số trích dẫn | Chỉ sắp theo trích dẫn dễ đẩy bài mới/ít trích dẫn xuống thấp; độ phủ cần kiểm từng lĩnh vực | Đối chiếu cả kết quả gần đây và kết quả liên quan |
| Rayyan: nhập tài liệu và sàng lọc | [Hướng dẫn Rayyan](https://help.rayyan.ai/hc/en-us/articles/22697630697617-Getting-Started-with-Rayyan) | Gộp danh sách tìm được, loại trùng và gắn lý do giữ/loại | Hỗ trợ quy trình sàng lọc có thể kiểm lại | Không thay thế bước tìm kiếm trên cơ sở dữ liệu | Dùng cho sàng lọc sau khi tìm, không coi là nguồn tìm chính |
| Zotero: PDF reader và ghi chú | [Tài liệu Zotero](https://www.zotero.org/support/pdf_reader) | Đánh dấu đoạn và ghi ý chính kèm đường về trang nguồn | Hỗ trợ truy vết ý rút ra từ bài | Không tự xác định ý nào dùng được cho câu hỏi nghiên cứu | Thử mẫu ghi chú ngắn cho nhánh đọc/rút ý |
| Elicit: tìm, sàng lọc và trích xuất với AI | [Hướng dẫn Elicit](https://support.elicit.com/en/articles/14759154-systematic-reviews-in-elicit) | Gợi ý bài và trường thông tin để xét | Có thể so với truy vấn thủ công và bảng rút ý | [Giới hạn được công bố](https://support.elicit.com/en/articles/14757928-elicit-s-limitations); có thể thiếu bài hoặc hiểu sai ý | Nếu thử AI, người nghiên cứu kiểm cả bài gốc và đoạn nguồn |

**Kết luận research:** Công cụ hiện có hỗ trợ cả **tìm/sàng lọc** lẫn **ghi chú/rút ý**. Chưa có dữ liệu từ hai coach để kết luận bước nào đáng ưu tiên chung, hoặc AI cải thiện được thời gian mà giữ chất lượng. Nên thử hai phép đo nhỏ riêng biệt trước khi chọn mức can thiệp.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại — dựng từ hai phỏng vấn

```text
[Xác định hướng nghiên cứu] → [Tìm bài] → [Chọn bài để đào sâu]
                                      ↓
                             [Đọc bài] → [Rút ý chính có thể dùng]
Coach A: nghẽn ở tìm kiếm; khoảng 90 phút/lượt tìm và chọn.
Coach B: nghẽn ở đọc/rút ý; khoảng 1 giờ/ngày để tìm bài.
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Hai lab coach | Hướng nghiên cứu | Phạm vi tìm | Tìm gần như mỗi ngày | Chưa ghi câu hỏi nghiên cứu cụ thể |
| 2 | Coach A | Từ khóa, prompt và nguồn tìm | Danh sách bài ứng viên | Khoảng 90 phút/lượt **gồm tìm và chọn** | Nêu tìm là bước khó nhất; lo sót bài mới/ít trích dẫn |
| 3 | Coach B | Tạp chí/hội nghị uy tín, hướng nghiên cứu | Danh sách bài để đào sâu | Khoảng 1 giờ/ngày **dành cho tìm** | Chưa rõ mỗi ngày có bao nhiêu lượt hoặc bài |
| 4 | Coach B | Bài đã chọn | Ý chính có thể dùng | Chưa cung cấp thời gian | Nêu đọc/rút ý là bước khó nhất |

Chưa có thời gian từng bước hoặc số bài xử lý. Hai mốc thời gian khác đơn vị và không đo độc lập.

### 4.2. Hai quy trình tương lai để pilot — No AI + Rule nhỏ

```text
Nhánh A — tìm/chọn bài:
[Người: chốt tiêu chí và từ khóa] → [Tìm nhiều nguồn, xem cả bài mới]
→ [Rule: gộp DOI trùng] → [Người: ghi lý do giữ/loại]
→ [Người thứ hai: kiểm bài ranh giới và tập bài chuẩn]

Nhánh B — đọc/rút ý:
[Người: chốt câu hỏi cần trả lời] → [Đọc bài đã chọn]
→ [Ghi 3–5 ý chính theo mẫu: ý, khả năng dùng, DOI/trang nguồn]
→ [Người thứ hai: mở lại nguồn để kiểm ý và tính liên quan]

Boundary: người nghiên cứu quyết định bài giữ/loại và ý nào dùng được; chưa dùng Agent.
Quay về: nếu mất bài chuẩn hoặc ghi ý sai nguồn, sửa quy trình tương ứng.
```

Mỗi nhánh cần đo **3 lượt trước và 3 lượt thử** trên nhiệm vụ tương đương. Mục tiêu đề xuất: thời gian của từng nhánh giảm ≥25% so với median baseline bấm giờ của chính nhánh đó, không giảm độ phủ bài quan trọng hoặc độ đúng của ý rút ra. Đây chưa phải kết quả. Nguồn tìm cần chọn theo lĩnh vực; PubMed chỉ phù hợp khi chủ đề thuộc phạm vi y sinh.

### 4.3. Before / after

| Chỉ số | Trước (hai coach tự thuật; chưa đo) | Sau (mục tiêu pilot) | Cách kiểm |
|---|---:|---:|---|
| Bước nghẽn | A: tìm; B: đọc/rút ý | Thử hai nhánh riêng | Bấm giờ từng bước và hỏi lại điểm khó nhất |
| Thời gian tìm/chọn | A: khoảng 90 phút/lượt; B: khoảng 1 giờ/ngày để tìm | Giảm ≥25% so với baseline cùng đơn vị ở nhánh A | Bấm giờ 3 lượt trước và 3 lượt thử; không lấy 1 giờ/ngày của B làm thời gian một lượt |
| Thời gian đọc/rút ý | B chưa cho số phút | Giảm ≥25% so với baseline nhánh B | Cùng loại bài/độ dài, bấm giờ 3 lượt trước và 3 lượt thử |
| Chất lượng | Chưa có số bài sót hoặc ý sai | Không sót bài chuẩn; ý rút ra có nguồn và được người kiểm xác nhận | Tập bài chuẩn cho A; kiểm DOI/trang và ý nghĩa cho B |
| Rủi ro mới | A: sót bài; B: ý rút ra khó dùng | A: thêm nhiễu; B: mẫu ghi chú có thể bỏ mất ngữ cảnh | Ghi lỗi, bất đồng và lý do |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Nghiên cứu sinh/nhà nghiên cứu đang khảo sát bài cho một câu hỏi nghiên cứu. |
| **Quy trình** | Xác định hướng → tìm → chọn bài → đọc → rút ý chính có thể dùng. |
| **Bottleneck** | **Chưa có một bước chung:** coach A nêu tìm kiếm; coach B nêu đọc/rút ý. |
| **Impact** | A tự thuật khoảng 90 phút/lượt tìm/chọn và lo sót bài; B dành khoảng 1 giờ/ngày để tìm và gặp khó ở rút ý. Chưa đo thời gian đọc hoặc hậu quả chất lượng. |
| **Success Metric** | Đo 3 lượt mỗi nhánh; sau thử nghiệm giảm ≥25% median thời gian theo từng nhánh, không sót bài chuẩn (A) và ý rút ra được người kiểm xác nhận kèm nguồn (B). |
| **Boundary** | Người nghiên cứu chốt bài và ý có thể dùng; mọi gợi ý phải được kiểm ở bài gốc. |

**Ghi chú trao đổi với AI để phản biện bản v0:** Cần định nghĩa “bài liên quan” và “ý có thể dùng”; hai mốc thời gian khác đơn vị; kết quả khác nhau giữa hai công cụ chưa chứng minh bài nào bị sót. Nhóm trưởng giữ hai nhánh đo riêng. Chưa có phản biện thật của nhóm khác.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Độ mơ hồ cao × độ phức tạp trung bình.** “Bài liên quan” và “ý có thể dùng” phụ thuộc câu hỏi nghiên cứu; tìm nhiều nguồn và rút ý là chuỗi bước có thể lập checklist nhưng cần chuyên môn để kiểm. Đây là đánh giá sơ bộ, cần thử trên một chủ đề cụ thể.

### 6.2. So sánh 4 mức

| Mức | Phương án | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | A: tiêu chí/từ khóa, nhiều nguồn, kiểm bài mới. B: mẫu ghi ý kèm DOI/trang và mục đích dùng | Giảm thời gian từng nhánh mà giữ độ phủ/độ đúng | A: nhiều kết quả nhiễu; B: ghi chú máy móc | **Chọn để pilot hai nhánh** |
| **Rule** | A: gộp DOI trùng. B: checklist đủ ý, mục đích dùng, trang nguồn | Trường dữ liệu đúng/sai rõ | DOI thiếu; checklist không đánh giá được ý nghĩa | Dùng như bước nhỏ |
| **Workflow** | A: AI gợi ý từ khóa/bài. B: AI gợi ý ý chính và đoạn nguồn; người kiểm | No AI/Rule đã đo nhưng không đủ, có tập chuẩn để đánh giá | A: bỏ sót bài; B: rút sai ngữ cảnh hoặc ý không dùng được | Chưa chọn |
| **Agent** | AI tự đổi truy vấn, chọn bài, đọc và chốt danh sách/ý | Chỉ xét nếu Workflow không đủ và có cách kiểm toàn bộ quyết định | Khó truy vết và phát hiện lỗi âm thầm | Không chọn |

**Mức chọn hiện tại:** No AI cho hai pilot nhỏ; Rule chỉ xử lý việc rõ ràng như trùng DOI và đủ trường ghi chú. Chưa có dữ liệu chứng minh AI cải thiện thời gian hoặc chất lượng ở cả hai nhánh. Chỉ coach A cho biết chưa dùng Agent; với coach B, việc dùng AI/Agent chưa được hỏi rõ.

### 6.3. AI Canvas rút gọn

**Chưa áp dụng cho pilot No AI.** Nếu thử Workflow: Input = câu hỏi nghiên cứu, tiêu chí, từ khóa và bài được phép đọc; Prediction = từ khóa/bài ứng viên (A) hoặc ý chính kèm đoạn nguồn (B); Judgment = người nghiên cứu so tiêu chí, mở bài gốc và xét khả năng dùng; Action = người sửa truy vấn, chốt bài và ý; Outcome = thời gian từng nhánh, bài chuẩn tìm được, ý đúng/có nguồn; Feedback = bài bị sót, ý sai ngữ cảnh và sửa của người kiểm. Không tự động chốt kết quả.

### 6.4. Hai câu hỏi Google PAIR

- **Augment hay automate?** Coach A đã dùng prompt tìm bài nhưng chưa dùng Agent; coach B chưa cung cấp thông tin dùng AI. Nếu thử AI, chỉ dùng để gợi ý truy vấn, bài hoặc ý kèm nguồn; người nghiên cứu chốt.
- **Báo nhầm hay bỏ sót tệ hơn?** Nhánh A cần tránh bỏ sót bài quan trọng; nhánh B cần tránh rút ý sai ngữ cảnh. Cần xác nhận mức độ ưu tiên với từng coach khi pilot.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Nghiên cứu sinh/nhà nghiên cứu đang khảo sát một câu hỏi nghiên cứu hẹp. |
| **Quy trình** | Chốt câu hỏi → tìm/chọn bài → đọc → ghi ý chính có thể dùng kèm nguồn → kiểm lại. |
| **Bottleneck** | Chưa thể chốt chung: coach A nghẽn ở tìm; coach B nghẽn ở đọc/rút ý. |
| **Impact** | A: khoảng 90 phút/lượt tìm/chọn và lo sót bài. B: khoảng 1 giờ/ngày tìm bài, khó rút ý dùng được; chưa biết thời gian đọc. |
| **Success Metric** | Đo 3 lượt baseline và 3 lượt thử cho **mỗi nhánh**; mục tiêu giảm ≥25% median thời gian từng nhánh, vẫn tìm đủ bài chuẩn (A) và giữ ý đúng, có nguồn, được người kiểm xác nhận (B). |
| **Boundary** | Người nghiên cứu chốt bài và ý dùng được; người kiểm mở bài gốc. Không lấy venue uy tín hoặc output AI làm bằng chứng đủ về độ liên quan/đúng ý. |
| **AI intervention point** | **Không có trong pilot No AI.** Workflow sau này có thể gợi ý bài (A) hoặc ý kèm đoạn nguồn (B), với người kiểm. |
| **Mức chọn** | No AI + Rule nhỏ cho từng nhánh; chưa chốt AI. |
| **Rủi ro & người kiểm tra** | Hai phỏng vấn tự thuật cho hai pain khác nhau; người nghiên cứu và người kiểm thứ hai xét tập bài chuẩn, log tìm và ý rút ra. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Quy trình | Tìm → chọn → đọc → rút ý | Tách nhánh A tìm/chọn và nhánh B đọc/rút ý | Hai coach nêu hai bước nghẽn khác nhau |
| Success Metric | Hai loại thời gian tự thuật, chưa đo | Baseline và tiêu chí chất lượng riêng cho từng nhánh | 90 phút/lượt và 1 giờ/ngày không cùng đơn vị; thời gian đọc chưa có |
| Mức can thiệp | Chưa xét | No AI pilot ở cả hai nhánh; Workflow chỉ là phương án sau | Chưa có bằng chứng AI cải thiện độ phủ hoặc độ đúng |

**Tiêu chí đánh giá giải pháp No AI/Rule:**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Truy vết tìm kiếm (A) | Lưu nguồn, truy vấn, ngày tìm, DOI/URL và lý do giữ/loại | Không thể tìm lại bài hoặc giải thích quyết định |
| 2 | Độ phủ (A) | Tìm được 100% bài trong tập chuẩn gồm cả bài mới/ít trích dẫn, do người kiểm lập trước | Thiếu một bài chuẩn hoặc không có tập chuẩn |
| 3 | Rút ý đúng và dùng được (B) | Mỗi ý có DOI/trang hoặc đoạn nguồn; người kiểm xác nhận ý đúng ngữ cảnh và liên quan câu hỏi | Ý sai nguồn/ngữ cảnh hoặc không giải thích được dùng vào đâu |
| 4 | Thời gian (A, B riêng) | Median từng nhánh giảm ≥25% qua 3 lượt thử so với 3 lượt baseline tương đương | Không đạt ngưỡng, không bấm giờ hoặc gộp sai hai đơn vị thời gian |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro của pilot

| Rủi ro | Câu hỏi | Mức độ | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Vấn đề có lặp lại và đủ đau không? | **Trung bình–cao** | Hai coach cùng tìm gần như mỗi ngày nhưng nêu hai pain khác nhau; chưa đo hậu quả hoặc mức phổ biến ngoài mẫu |
| **Usability** | Người dùng có duy trì log truy vấn và mẫu rút ý không? | **Trung bình** | Hai quy trình thêm ghi chép; chưa thử với coach |
| **Feasibility** | Có thể đo độ phủ và độ đúng của ý không? | **Trung bình** | Có nguồn tìm và công cụ ghi chú; cần tập bài chuẩn và người kiểm chuyên môn |
| **Viability** | Ai kiểm bài ranh giới và ý rút ra? | **Trung bình** | Cần người thứ hai, thời gian kiểm và phạm vi chủ đề đủ hẹp |

### 8.2. Kết luận

**Quyết định đề xuất: Not Yet.** Hai phỏng vấn xác nhận công việc khảo sát bài diễn ra thường xuyên, nhưng **không đồng thuận về bottleneck**: coach A khó ở tìm, coach B khó ở đọc/rút ý. Chưa có phép đo để chọn một nhánh hoặc kết luận quy trình mới/AI hiệu quả. Đây là đề xuất trong báo cáo, chưa phải quyết định được cả nhóm xác nhận tại buổi họp thật.

**Cần kiểm chứng trước:** (1) hỏi lại hai coach về một ví dụ cụ thể: truy vấn/bài đã tìm và ghi chú ý chính đã dùng; (2) bấm giờ 3 lượt baseline cho từng nhánh; (3) với A, lập tập bài chuẩn gồm bài mới/ít trích dẫn rồi thử tìm nhiều nguồn; (4) với B, chọn các bài tương đương rồi thử mẫu ghi ý kèm trang nguồn; (5) đo 3 lượt thử mỗi nhánh và so thời gian, độ phủ, độ đúng. Có thể hỏi thêm người nghiên cứu để xem nhánh nào phổ biến hơn.

**Pilot nhỏ nhất nếu đủ bằng chứng:** Trên một câu hỏi nghiên cứu hẹp, A thử checklist tìm/chọn với log truy vấn và tập bài chuẩn; B thử mẫu rút 3–5 ý từ các bài đã chọn, kèm mục đích dùng và DOI/trang. Một người thứ hai kiểm bài/ý. Không xây công cụ mới.

**Ngưỡng dừng:** Chưa áp dụng quy trình mới nếu sau 3 lượt thử median của nhánh tương ứng không giảm ≥25%, hoặc A thiếu bài chuẩn, hoặc B có ý sai nguồn/ngữ cảnh. Xem lại nguyên nhân của từng nhánh trước khi thử AI.

---

## 9. Hạn chế và hướng tiếp theo

- Chưa có buổi pitch/phản biện thật; câu hỏi gán cho thành viên là **mô phỏng**, điểm CP3 và OST là đề xuất để nhóm rà soát.
- Đã có **2 phỏng vấn thật với hai lab coach**; đạt số người tối thiểu cho hình thức 2–3 phỏng vấn, nhưng thiếu thời lượng từng bước, ví dụ bài cụ thể và hình thức phỏng vấn. Chưa có survey 5–10 người.
- Mốc 90 phút/lượt của A và 1 giờ/ngày của B là tự thuật với đơn vị khác nhau; chưa có baseline bấm giờ, phép kiểm bài bị sót hoặc đánh giá ý rút ra.
- Cần đo riêng hai nhánh, ghi trường hợp phản bác và thu hẹp Problem Statement theo kết quả thực nghiệm.
- Ý tưởng, lựa chọn đề tài và quyết định cần được nhóm trưởng/nhóm xác nhận. AI hỗ trợ tư vấn, phản biện và tra cứu; phần pitch giả định không thay cho trao đổi nhóm thật.
- CP7 là reflection cá nhân, phải do từng người tự viết sau hoạt động nhóm; không nằm trong báo cáo nhóm này.

## 10. Tài liệu tham khảo

1. Ghi chú hai cuộc phỏng vấn lab coach do nhóm trưởng cung cấp ngày 09/11/2026 — nguồn cho tần suất, thời gian, cách chọn và khó khăn; chưa có bản ghi âm/biên bản nguyên văn trong repo.
2. National Library of Medicine, [PubMed Help](https://pubmed.ncbi.nlm.nih.gov/help/) — truy vấn, bộ lọc và sắp xếp kết quả.
3. OpenAlex, [Searching](https://help.openalex.org/how-to/searching/) và [Sorting](https://help.openalex.org/api/sorting/) — tìm và sắp kết quả theo các tiêu chí.
4. Rayyan, [Getting Started](https://help.rayyan.ai/hc/en-us/articles/22697630697617-Getting-Started-with-Rayyan) — nhập, gộp và sàng lọc tài liệu.
5. Elicit, [Systematic Reviews](https://support.elicit.com/en/articles/14759154-systematic-reviews-in-elicit) và [Limitations](https://support.elicit.com/en/articles/14757928-elicit-s-limitations) — tính năng tìm/sàng lọc và giới hạn của AI.
6. Zotero, [PDF Reader and Note Editor](https://www.zotero.org/support/pdf_reader) — đánh dấu và ghi chú kèm nguồn trong PDF.

