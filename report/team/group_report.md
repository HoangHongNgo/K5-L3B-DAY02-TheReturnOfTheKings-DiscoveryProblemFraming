# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> **Trạng thái:** Bản chuẩn bị theo lựa chọn đề tài #1 của nhóm trưởng. Các bảng phân tích, điểm số, quy trình tương lai và quyết định dưới đây là **đề xuất để nhóm thảo luận**, chưa phải biên bản một buổi họp đã xảy ra. Chưa có phỏng vấn/survey người thật hoặc baseline bấm giờ, nên các phần đó được ghi rõ “chưa kiểm chứng”. Nhóm cần bổ sung bằng chứng trước khi xem đây là bài nộp hoàn tất.

## 1. Thông tin nhóm

- Tên nhóm: The Return of the Kings
- Thành viên: xem `TEAM.md` và ba báo cáo cá nhân trong `report/individual/`
- Candidate problem nhóm trưởng chọn: Khi khảo sát một câu hỏi nghiên cứu, nhà nghiên cứu phải tìm, lọc, đọc và đối chiếu nhiều bài liên quan; khó xác định bài nào cần đọc sâu mà không bỏ sót tài liệu quan trọng.
- Quyết định tạm thời: **Not Yet** — thử quy trình không AI và đo baseline trước khi cân nhắc AI.

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Candidate chuẩn bị cho buổi pitch

Chín candidate dưới đây lấy từ **top 3 trong báo cáo cá nhân** của ba thành viên. Đây là danh sách chuẩn bị, **chưa chứng minh mọi người đã pitch**. Cột phản biện cần điền sau buổi trao đổi thật.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck giả thuyết | Câu hỏi phản biện nhận được |
|---:|---|---|---|---|---|
| 1 | Ngô Hồng Hoàng | Lọc và đối chiếu bài báo liên quan | Nghiên cứu sinh | Đọc toàn văn và rút thông tin so sánh | Chưa có buổi pitch |
| 2 | Ngô Hồng Hoàng | Kiểm tra thông điệp mạo danh trước khi hành động | Người nhận tin | Tìm kênh chính thức để đối chiếu | Chưa có buổi pitch |
| 3 | Ngô Hồng Hoàng | Kiểm chứng claim trước khi chia sẻ | Người tạo nội dung | Tìm nguồn gốc claim | Chưa có buổi pitch |
| 4 | Nguyễn Quang Thành | Ghi nhớ ngày quan trọng và sở thích của người yêu | Người trong mối quan hệ | Ghi lại và tìm lại thông tin | Chưa có buổi pitch |
| 5 | Nguyễn Quang Thành | Phân việc và theo dõi tiến độ nhóm | Nhóm sinh viên | Gom thông tin từ nhiều kênh | Chưa có buổi pitch |
| 6 | Nguyễn Quang Thành | Ôn từ vựng để nhớ lâu | Người học ngoại ngữ | Duy trì lịch ôn và luyện tập | Chưa có buổi pitch |
| 7 | Đào Đức Sơn | Đồng bộ UI nhân vật giữa các Roblox place | Nhà phát triển game | Kiểm tra nhiều place sau thay đổi | Chưa có buổi pitch |
| 8 | Đào Đức Sơn | Lọc tin tuyển dụng phù hợp | Người tìm việc | Đọc và so sánh JD trên nhiều nguồn | Chưa có buổi pitch |
| 9 | Đào Đức Sơn | Tìm nguyên nhân lỗi combat qua nhiều module | Nhà phát triển game | Lần theo log và module | Chưa có buổi pitch |

**Ba câu hỏi gợi mở cho buổi trao đổi, chưa quy cho thành viên nào:** (1) Lần gần nhất ai phải đọc lại một bài gần liên quan, bước nào mất thời gian? (2) Có bài quan trọng nào từng bị loại nhầm khi chỉ đọc tóm tắt? (3) Zotero, bảng ghi chú hay công cụ sàng lọc hiện có đã giải quyết phần nào?

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
├── Opportunity A: khó diễn đạt tiêu chí liên quan đủ rõ trước khi tìm
├── Opportunity B: khó quyết định với bài chỉ gần liên quan khi đọc tóm tắt
└── Opportunity C: khó rút và đối chiếu claim/phương pháp từ các bài đã chọn
```

Ví dụ solution đội lốt opportunity cần gạch bỏ: “làm chatbot đọc PDF”, “tự động viết related work”, “xây agent nghiên cứu”. Chúng là cách can thiệp có thể thử **sau** khi xác nhận bước nghẽn.

### 2.4. Chấm điểm shortlist đề xuất (1–5)

Điểm dưới đây là **đánh giá sơ bộ để thảo luận**, không phải điểm đã được cả nhóm chấm. “Pain có bằng chứng” thấp vì chưa phỏng vấn hoặc đo trong nhóm.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được 4 mức | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Đọc và đối chiếu bài báo (#1) | 5 | 5 | 2 | 4 | 5 | 5 | 4 | **30** |
| Lọc tin tuyển dụng (#8) | 5 | 4 | 2 | 4 | 5 | 4 | 3 | **27** |
| Phối hợp công việc nhóm (#5) | 5 | 4 | 2 | 4 | 4 | 3 | 4 | **26** |

**Candidate được nhóm trưởng chọn:** #1 — lọc và đối chiếu bài báo liên quan.

**Vì sao chọn:** Bài toán gần bối cảnh học thuật, có thể thử trên một câu hỏi nghiên cứu hẹp, đo từng bước, và kiểm tra cả thời gian lẫn bỏ sót. Chọn đề tài **không có nghĩa pain đã được nhóm xác nhận**.

**Vì sao chưa chọn hai candidate còn lại:** #8 cần xác định một nhóm ứng tuyển và chất lượng danh sách việc làm; #5 cần tách nguyên nhân do công cụ, phân công hay trách nhiệm cá nhân. Cả hai vẫn có thể quay lại nếu kiểm chứng #1 không ủng hộ.

**Xử lý bất đồng:** Chưa có dữ liệu buổi họp; không ghi nhận bất đồng giả định.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

Thang bằng chứng: 1 = chưa có dữ liệu tại nhóm người dùng; 5 = có quan sát lặp lại. Các điểm là đánh giá sơ bộ.

| # | Giả định | Loại | Quan trọng | Đã có bằng chứng | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Nghiên cứu sinh thực sự đọc lại bài gần liên quan nhiều lần trong một dự án | Value | 5 | 1 | Có |
| 2 | Đọc toàn văn và rút thông tin là bước tốn thời gian nhất | Value | 5 | 1 | Có |
| 3 | Có thể đặt tiêu chí “liên quan” đủ rõ để hai người áp dụng tương đối giống nhau | Usability | 5 | 1 | Có |
| 4 | Nhóm có quyền truy cập đủ PDF để đối chiếu claim/trang nguồn | Feasibility | 4 | 2 | Có |
| 5 | Zotero + bảng trích xuất có thể giảm thời gian mà không tăng bỏ sót | Feasibility | 4 | 1 | Có |
| 6 | Người dùng chấp nhận kiểm tra lại mọi trích xuất do AI gợi ý | Viability | 4 | 1 | Sau khi đo #1–5 |

**Giả định ưu tiên:** #1–3 vì nếu không đúng thì cần đổi bài toán trước khi bàn đến AI.

### 3.2. Kiểm chứng với người thật

**Trạng thái:** Chưa thực hiện phỏng vấn hoặc survey. Không có Interview Snapshot, số người hay phát ngôn để báo cáo. Ba câu hỏi dùng cho **2–3 nghiên cứu sinh/nhà nghiên cứu ngoài nhóm**, hỏi về lần gần nhất, không giới thiệu giải pháp:

1. “Lần gần nhất bạn phải tìm và đọc các bài liên quan cho một câu hỏi nghiên cứu là khi nào? Bạn đã đi qua những bước nào, khoảng bao nhiêu bài và mất bao lâu ở từng bước?”
2. “Có bài nào bạn phải mở lại hoặc đổi quyết định từ loại sang giữ (hoặc ngược lại) không? Điều gì trong bài làm bạn đổi ý, và bạn đã tìm lại thông tin đó bằng cách nào?”
3. “Hiện bạn ghi tiêu chí chọn bài, claim, phương pháp và nguồn trang ở đâu? Trong lần gần nhất, bước nào làm bạn chậm nhất hoặc gây lỗi; bạn đã xử lý ra sao?”

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn/survey của nhóm | **0** | Chưa có | Chưa có |
| Nghiên cứu TASER [2] | Mẫu thí nghiệm sàng lọc trong bài gốc | Có thể đo thời gian theo trích dẫn; sàng lọc là công việc lặp | Không chứng minh đọc toàn văn là bottleneck của nhóm |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** Chưa thể kết luận vì chưa kiểm chứng với người thật. Bản mô tả hiện là giả thuyết để thử.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link đã mở | Giải bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học |
|---|---|---|---|---|---|
| Zotero: thư viện, PDF annotations và notes | [Tài liệu Zotero](https://www.zotero.org/support/pdf_reader) | Lưu bài, ghi chú, quay lại đúng trang PDF | Annotation đưa vào note kèm liên kết trang và trích dẫn | Không tự quyết bài nào phù hợp với câu hỏi riêng của nhóm | Thử quy trình không AI bằng nguồn/trang trước |
| Rayyan: sàng lọc, loại trùng, hai người review | [Hướng dẫn Rayyan](https://help.rayyan.ai/hc/en-us/articles/22697630697617-Getting-Started-with-Rayyan) | Lọc tiêu đề/tóm tắt, full text, data extraction | Tiêu chí vào/loại, blind mode và xử lý bất đồng | Thiết kế cho review có tiêu chí rõ; không tự giải quyết claim gần liên quan | Không tự xây công cụ sàng lọc nếu tính năng có sẵn đủ |
| Elicit: screening và extraction có quote hỗ trợ | [Hướng dẫn Elicit](https://support.elicit.com/en/articles/14759154-systematic-reviews-in-elicit) | Gợi ý trích xuất từ bài và dẫn đoạn nguồn | Có thể mở quote để kiểm tra từng ô | [Elicit lưu ý](https://support.elicit.com/en/articles/14757928-elicit-s-limitations) AI có thể bỏ nuance/hiểu sai số; thiếu PDF thì chỉ đọc abstract | Nếu thử AI, người nghiên cứu kiểm từng claim; không tự viết kết luận |

**Kết luận research:** Nhiều bước đã có công cụ. Chưa có căn cứ để tự xây agent hoặc khẳng định AI giảm thời gian/giữ chất lượng. Pilot đầu tiên nên dùng công cụ hiện có và bảng trích xuất thủ công.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại — giả thuyết từ CP2

Số phút là **ước lượng minh họa cho 10 bài ứng viên**, chưa bấm giờ; cần thay bằng baseline từ 3 phiên thật.

```text
[Câu hỏi + tiêu chí: 10'] → [Tìm bài: 15'] → [Lọc tóm tắt: 20']
→ [Đọc sâu 3 bài + trích xuất: 90'] ← BOTTLENECK giả thuyết
→ [Đối chiếu và tìm tiếp: 25']
Tổng ước lượng: 160'/phiên.
```

| Bước | Actor | Input | Output | Thời gian / tần suất giả định | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Nghiên cứu sinh | Câu hỏi nghiên cứu | Tiêu chí vào/loại | 10'/phiên | Có thể còn mơ hồ |
| 2 | Nghiên cứu sinh | Từ khóa, cơ sở dữ liệu | Danh sách bài | 15'/phiên | Lưu câu truy vấn |
| 3 | Nghiên cứu sinh | Tiêu đề/tóm tắt | Bài giữ/loại/chưa chắc | 20'/10 bài | Bài gần liên quan cần xem lại |
| 4 | Nghiên cứu sinh | 3 PDF và tiêu chí | Bảng claim/phương pháp/kết quả | 90'/3 bài | Bottleneck giả thuyết, cần bấm giờ |
| 5 | Nghiên cứu sinh | Bảng trích xuất | Danh sách bài cần đọc tiếp | 25'/phiên | Kiểm tra bỏ sót |

### 4.2. Quy trình tương lai để pilot — No AI + Rule nhỏ

```text
[Người: chốt tiêu chí trước khi tìm: 10']
→ [Người: tìm và lưu DOI/PDF vào Zotero: 10']
→ [Rule: lọc DOI trùng; người xét bài sát ranh giới: 20']
→ [Người: đọc PDF + điền bảng cố định kèm trang nguồn: 60']
→ [Người thứ hai: kiểm 3 bài gần ranh giới + chốt: 20']
Tổng kỳ vọng: 120'/phiên, chưa kiểm chứng.
Boundary: không có AI tự loại bài, tự viết claim hoặc tự gửi related work.
Quay về: nếu mất bài liên quan hoặc bảng khó dùng, trở về cách đọc/ghi chú cũ.
```

### 4.3. Before / after

| Chỉ số | Trước (giả định) | Sau (kỳ vọng pilot) | Cách kiểm |
|---|---:|---:|---|
| Số bước | 5 | 5 | Đếm bước |
| Tổng thời gian/10 bài | 160' | 120' | Bấm giờ 3 phiên mỗi cách, so median |
| Số bước con người quyết định | 5 | 5 | Quyết định vào/loại và claim vẫn do người |
| Bottleneck chính | Đọc/trích xuất 90' | Đọc/trích xuất 60' | Đo từng bước, chưa chắc giảm |
| Rủi ro mới | Ghi chú rời rạc | Tiêu chí sai, DOI trùng giả, kiểm chéo tốn công | Ghi lỗi và bài bị bỏ sót |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Nghiên cứu sinh khảo sát tài liệu cho một câu hỏi nghiên cứu hẹp. |
| **Quy trình** | Đặt tiêu chí → tìm bài → lọc tóm tắt → đọc toàn văn/rút claim → đối chiếu. |
| **Bottleneck** | Giả thuyết: đọc toàn văn và rút thông tin có thể so sánh là bước chậm nhất; cần đo. |
| **Impact** | Có thể chậm quyết định đề tài/baseline hoặc bỏ sót nghiên cứu phản bác; chưa đo mức ảnh hưởng. |
| **Success Metric** | Baseline hiện **chưa đo**; bấm giờ 3 phiên 10 bài và kiểm chéo bài liên quan. Target pilot: median phút/phiên giảm ≥25%, số bài quan trọng bỏ sót không tăng. |
| **Boundary** | Quyết định liên quan và diễn giải claim do người nghiên cứu xác nhận trong PDF gốc; không tự động loại bài gần ranh giới hoặc tạo trích dẫn chưa kiểm. |

**AI phản biện bản v0:** (1) “liên quan” cần tiêu chí vào/loại cụ thể; (2) 160' là ước lượng chứ không phải baseline; (3) số bài bỏ sót phải có người thứ hai kiểm. **Đồng ý** và đưa ba việc này vào pilot. Chưa có phản biện của nhóm khác.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Độ mơ hồ cao × độ phức tạp trung bình.** Một bài “gần liên quan” có thể được giữ hoặc loại tùy câu hỏi; quy trình nối nhiều bước và nguồn, nhưng vẫn có thể viết trước và kiểm từng bước. Đây là nhận định sơ bộ, cần kiểm bằng sự đồng thuận của hai người review.

### 6.2. So sánh 4 mức

| Mức | Phương án | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Tiêu chí trước, Zotero, bảng extraction, hai người kiểm bài ranh giới | Giảm thời gian mà không tăng bỏ sót | Mất công thủ công; tiêu chí có thể sai | **Chọn để pilot** |
| **Rule** | Lọc DOI trùng, checklist thiếu trường/trang nguồn | Dữ liệu có đúng/sai rõ | DOI thiếu hoặc metadata sai có thể gộp nhầm | Dùng như bước nhỏ |
| **Workflow** | Các bước cố định; AI tạo nháp trích xuất kèm quote, người kiểm | No AI/Rule đã đo và không đủ, PDF truy cập được, eval đạt | Bỏ nuance, bịa/nhầm claim, chi phí | Chưa chọn |
| **Agent** | AI tự tìm, chọn bài, đọc và quyết định bước tiếp | Chỉ khi workflow cố định chứng minh không đủ và có kiểm soát mạnh | Khó audit, bỏ sót, hành động ngoài ý muốn | Không chọn |

**Mức chọn hiện tại:** No AI cho pilot; Rule chỉ xử lý việc rõ ràng như trùng DOI. **Vì sao chưa lên mức cao hơn:** chưa có dữ liệu chứng minh No AI/Rule không đạt; Zotero, Rayyan và Elicit đã xử lý nhiều bước. Không có lý do để giao quyền tự quyết cho Agent.

### 6.3. AI Canvas rút gọn

**Chưa áp dụng cho giải pháp đang pilot (No AI).** Nếu pilot sau đó cho thấy cần Workflow, canvas cần kiểm chứng: Prediction = nháp trường trích xuất và quote; Judgment = người nghiên cứu so với PDF; Action = người chốt bảng và quyết định giữ/loại; Outcome = phút/phiên + số bài bỏ sót + lỗi claim; Input = PDF được phép dùng, câu hỏi, tiêu chí; Feedback = sửa của người review và case bất đồng. Không vận hành canvas này trước khi có dữ liệu và quyền dùng PDF.

### 6.4. Hai câu hỏi Google PAIR

- **Augment hay automate?** Chưa có lời người dùng thật. Giả thuyết an toàn là hỗ trợ tìm đoạn và lập nháp, **không** giao quyết định giữ/loại hoặc viết kết luận.
- **Báo nhầm hay bỏ sót tệ hơn?** Với mục tiêu không bỏ qua nghiên cứu quan trọng, **bỏ sót** thường đáng lo hơn. Cần xác nhận theo loại review; các bài chưa chắc phải được người xem lại.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Nghiên cứu sinh đang khảo sát một câu hỏi nghiên cứu hẹp. |
| **Quy trình** | Chốt tiêu chí → tìm/lưu bài → lọc và gắn lý do → đọc/ghi claim có trang nguồn → người thứ hai kiểm bài ranh giới. |
| **Bottleneck** | Đọc và trích xuất thông tin để so sánh **được giả định** là bước chậm nhất, chờ bấm giờ xác nhận. |
| **Impact** | Có thể chậm quyết định đề tài/baseline hoặc bỏ sót bài phản bác; chờ phỏng vấn xác nhận. |
| **Success Metric** | Baseline từ 3 phiên 10 bài chưa thu; target pilot giảm ≥25% median phút/phiên, số bài quan trọng bỏ sót không tăng, ghi bằng log thời gian và kiểm chéo. |
| **Boundary** | Người nghiên cứu chốt tiêu chí, bài giữ/loại và mọi claim; bài gần ranh giới cần người thứ hai kiểm; không tự tạo citation thiếu nguồn. |
| **AI intervention point** | **Không có trong pilot No AI.** Chỉ xem xét nháp trích xuất có quote ở một Workflow sau khi No AI không đủ. |
| **Mức chọn** | No AI + Rule DOI trùng; chưa chốt AI. |
| **Rủi ro & người kiểm tra** | Value chưa được xác nhận; nghiên cứu sinh và người review thứ hai kiểm bài ranh giới, claim và log lỗi. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Quy trình | Chưa nói rõ kiểm chéo | Thêm người thứ hai kiểm bài ranh giới | Cần đo bỏ sót và giảm quyết định chủ quan |
| Boundary | Con người xác nhận | Ghi rõ người chốt tiêu chí, giữ/loại, claim và nguồn | Research công cụ cho thấy có tính năng tự động nhưng cần audit |
| Mức can thiệp | Chưa xét | No AI pilot; không có điểm AI | Chưa có bằng chứng phải dùng AI |

**Tiêu chí đánh giá giải pháp No AI/Rule (theo hướng dẫn cho trường hợp không chọn AI):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Truy vết nguồn | Mỗi claim trong bảng có DOI/URL và trang/đoạn để mở kiểm | Claim không dẫn được về bài gốc |
| 2 | Không bỏ sót bài quan trọng | Số bài liên quan bị bỏ sót trong kiểm chéo không tăng so với baseline | Bỏ sót tăng hoặc không kiểm chéo |
| 3 | Thời gian | Median phút/10 bài giảm ≥25% qua 3 phiên so với baseline | Không đạt ngưỡng hoặc không bấm giờ |
| 4 | Nhất quán tiêu chí | Hai người thống nhất lý do giữ/loại cho ≥80% bài ranh giới trước khi hòa giải | Bất đồng nhiều nhưng không ghi lý do |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro của pilot

| Rủi ro | Câu hỏi | Mức độ | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Cao** | Chưa phỏng vấn, chưa đo thời gian hoặc hậu quả bỏ sót trong nhóm người dùng |
| **Usability** | Người dùng có dùng được bảng và kiểm chéo không? | **Trung bình** | Cách làm rõ nhưng có thể tăng việc ghi chép; chưa thử |
| **Feasibility** | Có đủ công cụ, PDF và kỹ năng không? | **Trung bình** | Zotero/Rayyan có sẵn; quyền đọc toàn văn và mức phù hợp cần kiểm |
| **Viability** | Chi phí và người vận hành lâu dài? | **Trung bình** | No AI có chi phí thấp, nhưng cần người thứ hai review và quy định dùng PDF |

### 8.2. Kết luận

**Quyết định đề xuất: Not Yet.** Chưa đủ bằng chứng để nhóm chốt problem hoặc khẳng định can thiệp nào hiệu quả. Đây là quyết định về **đề xuất**, không thay cho kết luận sau phỏng vấn.

**Cần kiểm chứng trước:** (1) hỏi 2–3 người ngoài nhóm bằng ba câu hỏi ở 3.2; (2) bấm giờ 3 phiên khảo sát 10 bài để xác định bottleneck; (3) thử template + Zotero + người kiểm chéo qua 3 phiên khác; (4) so thời gian, bỏ sót và lỗi claim.

**Pilot nhỏ nhất nếu đủ bằng chứng:** Một câu hỏi nghiên cứu hẹp, 10 bài ứng viên/phiên, một người làm và một người kiểm các bài gần ranh giới. Không xây công cụ mới.

**Ngưỡng dừng:** Nếu sau 3 phiên thử, thời gian không giảm ≥25% **hoặc** số bài quan trọng bị bỏ sót tăng so với baseline, dừng quy trình mới và quay về cách đọc/ghi chú trước đó; xem lại tiêu chí và nguyên nhân trước khi thử AI.

---

## 9. Hạn chế và hướng tiếp theo

- Chưa có buổi pitch/ phản biện thật; điểm CP3 và OST là đề xuất của bản chuẩn bị.
- Chưa có 2–3 phỏng vấn hoặc survey 5–10 người; CP4 chưa đạt điều kiện kiểm chứng của đề.
- Chưa có baseline, nên mọi số phút và target hiện là giả thuyết. Không dùng 160' như một phép đo.
- Cần thay bảng 3.2 bằng Interview Snapshot thật; ghi cả tín hiệu xác nhận lẫn phản bác và sửa Problem Statement nếu kết quả đổi hướng.
- CP7 là reflection cá nhân, phải do từng người tự viết sau hoạt động nhóm; không nằm trong báo cáo nhóm này.

## 10. Tài liệu tham khảo

1. National Library of Medicine, [About PubMed](https://pubmed.ncbi.nlm.nih.gov/about/) — quy mô kho trích dẫn, không phải baseline thời gian.
2. [TASER pilot trial](https://pmc.ncbi.nlm.nih.gov/articles/PMC4217707/) — thời gian sàng lọc tiêu đề/tóm tắt trong bối cảnh thí nghiệm, không suy ra thời gian đọc toàn văn.
3. Zotero, [PDF Reader and Note Editor](https://www.zotero.org/support/pdf_reader) — ghi chú và liên kết trang.
4. Rayyan, [Getting Started](https://help.rayyan.ai/hc/en-us/articles/22697630697617-Getting-Started-with-Rayyan) — sàng lọc và quản lý review.
5. Elicit, [Systematic Reviews](https://support.elicit.com/en/articles/14759154-systematic-reviews-in-elicit) và [Limitations](https://support.elicit.com/en/articles/14757928-elicit-s-limitations) — trích xuất có quote và giới hạn cần kiểm.

