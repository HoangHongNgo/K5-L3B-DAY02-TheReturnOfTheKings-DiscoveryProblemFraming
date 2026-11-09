# Báo cáo cá nhân — 2A202604093_NgoHongHoang

## 1. Thông tin học viên

- Họ tên: Ngô Hồng Hoàng
- MSSV: 2A202604093
- Email trường: Không công khai
- Tên nhóm: The Return of the Kings
- Link repo nhóm: https://github.com/HoangHongNgo/K5-L3B-DAY02-TheReturnOfTheKings-DiscoveryProblemFraming

> **Phạm vi bằng chứng:** Sáu vấn đề trong CP1 đều là ý tưởng tôi tự nghĩ ra và chọn để nhóm cân nhắc. AI hỗ trợ tư vấn, phản biện và tra cứu; tôi và nhóm quyết định nội dung. Với #1, tôi đã cung cấp ghi chú **hai cuộc phỏng vấn thật với hai lab coach**; với #2–6, bằng chứng hiện đến từ nguồn công khai, **chưa phải kết quả quan sát cá nhân hoặc phỏng vấn của tôi**. Các số liệu công khai không phải baseline của nhóm. Mốc 90 phút/lượt và 1 giờ/ngày của hai coach khác đơn vị, đều là tự thuật chưa bấm giờ.

---

## 2. Scan problem (CP1)

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật, nguồn và giới hạn |
|---:|---|---|---|---|
| 1 | Lặp lại; cần đọc, tổng hợp | Khi khảo sát một câu hỏi nghiên cứu, tôi muốn tìm đủ bài liên quan và rút được ý chính có thể dùng, để không bỏ sót công trình quan trọng và có căn cứ cho bước nghiên cứu tiếp theo. | Nhà khoa học, nghiên cứu sinh | **Hai phỏng vấn lab coach [8]:** cả hai tìm gần như hằng ngày. Coach A tự thuật khoảng **90 phút/lượt tìm và chọn**, thấy tìm khó nhất và lo sót bài mới/ít trích dẫn. Coach B dành khoảng **1 giờ/ngày để tìm**, nhưng thấy đọc/rút ý khó nhất; chưa ghi thời gian đọc. Hai mốc không cùng đơn vị và chưa đo độc lập. |
| 2 | Pain từ người khác; tốn thời gian | Khi nhận tin nhắn, cuộc gọi hoặc bài đăng có dấu hiệu mạo danh, người dùng muốn kiểm tra nguồn và yêu cầu thanh toán, để không chuyển tiền hay tiết lộ thông tin nhầm. | Người dùng mạng, đặc biệt người dễ bị lừa đảo | **Candidate từ dữ liệu công khai.** FTC ghi nhận hơn **1 triệu** báo cáo lừa đảo mạo danh và **3,5 tỷ USD** tổn thất được báo cáo tại Mỹ năm 2025 [3]. Đây là số báo cáo ở Mỹ, không phải tỷ lệ trong nhóm hoặc Việt Nam. |
| 3 | Cần đọc, tổng hợp; pain từ người khác | Khi định chia sẻ một tin đang lan truyền, người tạo nội dung muốn kiểm tra claim và nguồn gốc, để không phát tán thông tin sai. | Người tạo nội dung, người đọc | **Candidate từ khảo sát.** UNESCO khảo sát **500** người tạo nội dung ở **45** quốc gia/vùng lãnh thổ; **62%** cho biết không kiểm tra tính chính xác trước khi chia sẻ [4]. Mẫu này không đại diện cho mọi người dùng mạng. |
| 4 | Pain từ người khác; cấp thiết | Khi có cảnh báo nắng nóng cực đoan, người chăm sóc muốn hiểu ai có nguy cơ và cần làm gì trong ngày, để giảm phơi nhiễm cho người dễ tổn thương. | Người cao tuổi, người bệnh nền, người chăm sóc | **Candidate sức khỏe, chưa phỏng vấn.** WHO ước tính **61.672** ca tử vong vượt mức liên quan đến nắng nóng ở châu Âu mùa hè 2022 [5]. Đây là ước tính khu vực và năm cụ thể, không đo tác động của thông báo. |
| 5 | Pain từ người khác; cấp thiết | Khi trường phải nghỉ vì lũ, bão hoặc nắng nóng, học sinh và giáo viên muốn biết kế hoạch học bù đáng tin cậy, để không mất tiến độ học. | Học sinh, giáo viên, phụ huynh | **Candidate từ báo cáo.** UNICEF ước tính ít nhất **171 triệu** học sinh bị gián đoạn học do biến cố khí hậu trong năm 2025 [6]. Chưa biết một trường cụ thể đang phối hợp thông báo ra sao. |
| 6 | Pain từ người khác; cấp thiết | Khi được kê nhiều thuốc hoặc đổi liều, bệnh nhân muốn đối chiếu hướng dẫn dùng thuốc và chỗ chưa rõ với nhân viên y tế, để tránh dùng sai. | Bệnh nhân, người chăm sóc, nhân viên y tế | **Candidate y tế, chưa phỏng vấn.** WHO nêu khoảng **5%** bệnh nhân trên toàn cầu gặp tổn hại liên quan thuốc có thể phòng tránh [7]. Không suy ra vấn đề chủ yếu là bệnh nhân đọc sai hướng dẫn; cần xác minh nguyên nhân tại bối cảnh cụ thể. |

**AI đã hỗ trợ:** Tôi tự nghĩ ra sáu candidate. AI giúp tra cứu các nguồn FTC, UNESCO, WHO, UNICEF và tài liệu về công cụ nghiên cứu; cùng tôi thảo luận actor, tình huống, cách đo và phản biện cách viết. Tôi cung cấp dữ liệu phỏng vấn và quyết định nội dung đưa vào báo cáo; AI không thay thế người được phỏng vấn hoặc buổi pitch thật.

**Khoảng trống CP1:** Với #2–6, bằng chứng hiện mới là **nghiên cứu thứ cấp**. Trước khi dùng làm bằng chứng cá nhân, cần hỏi về một sự kiện đã xảy ra, ai thực hiện bước nào, mất bao lâu, gặp mấy lần; không hỏi “bạn có muốn dùng ứng dụng này không?”.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tìm, đọc và rút ý từ bài báo liên quan | Bắt đầu từ pain tôi nêu; hai lab coach xác nhận công việc lặp lại gần như hằng ngày [8] | Hai coach nêu hai bottleneck khác nhau; chưa bấm giờ từng bước hoặc kiểm số bài bị sót |
| 2 | Kiểm tra tin nhắn/bài đăng mạo danh | Nhiều báo cáo tổn thất; actor và điểm quyết định trước khi chuyển tiền rõ | Dữ liệu FTC là ở Mỹ; cần kiểm chứng tại Việt Nam, nhất là hành vi kiểm tra thực tế |
| 3 | Kiểm chứng claim trước khi chia sẻ | Có tín hiệu hành vi từ khảo sát UNESCO; có thể thử với người tạo nội dung hoặc nhóm sinh viên | 62% không đại diện cho mọi người; chưa biết bước nghẽn là tìm nguồn, đọc nguồn hay thiếu động lực |

### Problem Card #1 — Khảo sát và rút ý từ bài báo

| Trường | Nội dung |
|---|---|
| Job Story | Khi khảo sát một câu hỏi nghiên cứu, tôi muốn tìm đủ bài liên quan và rút được ý chính có thể dùng, để có căn cứ cho bước nghiên cứu tiếp theo mà không bỏ sót công trình quan trọng. |
| Actor | Nghiên cứu sinh/nhà nghiên cứu đang khảo sát một chủ đề hẹp. |
| Thời điểm / bối cảnh | Bắt đầu đề tài, chuẩn bị related work hoặc chọn baseline. |
| Quy trình hiện tại (5 bước) | Xác định hướng/câu hỏi → tìm qua từ khóa hoặc tạp chí/hội nghị → chọn bài liên quan → đọc → rút ý chính có thể dùng. |
| Bottleneck | **Chưa có một bước chung:** coach A nêu bước tìm kiếm; coach B nêu bước đọc/rút ý [8]. Cần đo riêng thay vì áp một giả định cho cả hai. |
| Impact | Coach A tự thuật khoảng 90 phút/lượt tìm/chọn và lo sót bài mới/ít trích dẫn. Coach B dành khoảng 1 giờ/ngày để tìm, khó rút ý dùng được; thời gian đọc và lỗi rút ý chưa đo. |
| Success metric (baseline → target) | **Baseline:** cần bấm giờ 3 lượt mỗi nhánh. **Target đề xuất:** median thời gian tìm/chọn (A) hoặc đọc/rút ý (B) giảm ≥25% so với baseline cùng nhánh; A không thiếu bài trong tập chuẩn, B có ý đúng nguồn và được người kiểm xác nhận. |
| Phương án không dùng AI | A: tiêu chí vào/loại, nhiều nguồn, gộp DOI và kiểm bài ranh giới. B: mẫu ghi 3–5 ý kèm mục đích dùng, DOI/trang nguồn và người thứ hai kiểm. |
| Giả thuyết về AI | Workflow có thể gợi ý bài ứng viên (A) hoặc ý chính kèm đoạn nguồn (B); người nghiên cứu mở bài gốc và chốt quyết định. Chưa có bằng chứng hiệu quả. |
| Cảm nhận nhanh | Thử hai quy trình nhỏ không AI trước; chưa chọn một bottleneck chung hoặc xây Agent. |

Quy trình nháp cập nhật sau hai phỏng vấn — **thời gian theo lời kể, chưa bấm giờ từng bước**:

```text
[Xác định hướng: chưa đo] → [Tìm bài: chưa đo riêng] → [Chọn bài: chưa đo riêng]
                                      ↓
                         [Đọc: chưa đo] → [Rút ý: chưa đo]
Coach A: tìm là bottleneck; khoảng 90 phút cho một lượt tìm + chọn.
Coach B: đọc/rút ý là bottleneck; tìm khoảng 1 giờ/ngày, chưa rõ thời gian đọc.
Không cộng hoặc so trực tiếp hai mốc thời gian khác đơn vị.
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
- Vì sao: Xuất phát từ vấn đề tôi nêu; hai lab coach đều tìm bài gần như mỗi ngày nhưng chỉ ra hai bước khó khác nhau. Tôi muốn kiểm chứng trước khi chọn nhánh phát triển.
- Câu hỏi muốn nhóm phản biện: “Với người dùng cụ thể, bước nghẽn là tìm đủ bài hay đọc và rút ý dùng được; ta sẽ đo thời gian và chất lượng từng bước thế nào?” Câu hỏi này là phần chuẩn bị pitch, chưa phải biên bản buổi pitch đã diễn ra.
- Dữ liệu quy mô để đặt bối cảnh: UNESCO ghi nhận **8,854 triệu nhà nghiên cứu quy đổi toàn thời gian (FTE) năm 2018** [14]. Con số đó không phải số người thực tế đang tìm/đọc bài mỗi ngày và không được dùng để nhân với thời gian của hai coach. Phần chuẩn bị pitch có nhắc đến “AI Agent”, nhưng ghi chú chi tiết trước đó nói coach A **chưa dùng Agent**; tôi chưa coi mức sử dụng Agent của hai coach là dữ liệu đã xác nhận.

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1 dễ biến quy mô PubMed thành bằng chứng tôi phải đọc quá nhiều. | Có | Ghi rõ 40 triệu là quy mô kho; baseline cá nhân chưa đo. |
| Card #1 trước đây gán đọc sâu là bottleneck chung và dùng tổng 160 phút giả định. | Có | Sau hai phỏng vấn, tôi bỏ mốc giả định đó khỏi card và tách nhánh tìm/chọn (coach A) với đọc/rút ý (coach B). |
| Card #2 có thể khuyến khích giao quyết định an toàn cho AI. | Có | Ưu tiên checklist, kênh chính thức và con người quyết định; đo cả bỏ sót lừa đảo lẫn báo nhầm. |
| Card #3 có thể dùng tốc độ làm metric khiến người đăng kiểm tra hời hợt. | Có | Ưu tiên tỷ lệ claim có nguồn và bối cảnh đúng; giới hạn thời gian tăng tối đa 20%. |
| Ba card dùng số liệu quốc tế để suy ra pain tại Việt Nam. | Có | Giữ là candidate, chỉ chọn sau khi phỏng vấn/pilot đúng nhóm người dùng. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Checkpoint | Phần tôi đã làm / cung cấp | Bằng chứng và giới hạn |
|---|---|---|
| CP3 | Tôi chọn candidate #1 từ các problem card cá nhân và chuẩn bị lập luận pitch dựa trên công việc khảo sát bài báo. | Card #1 ở mục 3; [báo cáo nhóm](../team/group_report.md) mục 2. Bảng câu hỏi gán tên thành viên trong báo cáo nhóm là **kịch bản giả định**, chưa phải phản biện thật của các thành viên. |
| CP4 — kiểm chứng | Tôi phỏng vấn **hai lab coach khác nhau** và cung cấp ghi chú về lần tìm gần nhất, tần suất, thời gian, cách chọn bài và bước khó nhất. | [Hai Interview Snapshot](../team/group_report.md) mục 3.2. Coach A khó ở tìm; coach B khó ở đọc/rút ý. Chưa có bản ghi nguyên văn, hình thức phỏng vấn hoặc thời gian từng bước. |
| CP4 — research | Tôi cùng AI tra cứu, đối chiếu các công cụ đang hỗ trợ tìm, sàng lọc và ghi chú bài báo. | [Bảng research](../team/group_report.md) mục 3.3 và các nguồn [9]–[13]. Đây là research thứ cấp, không thay cho thử nghiệm với hai coach. |
| CP5 | Tôi cập nhật phạm vi bài toán sau phỏng vấn: giữ cả bước tìm/chọn và đọc/rút ý, không cộng 90 phút/lượt với 1 giờ/ngày. | [Quy trình và Problem Statement v0](../team/group_report.md) mục 4–5; các mục tiêu giảm thời gian là đề xuất, chưa có baseline bấm giờ. |
| CP6 | Tôi giữ kết luận đề xuất **Not Yet** và so sánh No AI, Rule, Workflow, Agent theo hai nhánh pain. | [Problem Statement v1 và quyết định](../team/group_report.md) mục 6–8. Chưa có pilot chứng minh mức can thiệp nào tốt hơn. |

Tôi chưa cung cấp biên bản pitch/phản biện thật hoặc một bất đồng thật với thành viên cụ thể, nên không ghi chúng như hoạt động đã xảy ra.

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Tra cứu nguồn cho sáu vấn đề tôi tự nghĩ ra; thảo luận cách viết Job Story và dấu hiệu cần đo. | Tìm số liệu từ FTC, UNESCO, WHO, UNICEF và giúp làm rõ phạm vi từng vấn đề. | Số liệu quốc tế không tự chứng minh pain của tôi hoặc nhóm tại Việt Nam. | Tôi quyết định nội dung, ghi rõ quần thể/năm/giới hạn nguồn và đánh dấu phần chưa được quan sát hay phỏng vấn. |
| CP2 Problem Card | Thảo luận và phản biện ba card tôi xây dựng, tập trung vào bottleneck, metric và rủi ro. | Giúp làm rõ rằng chỉ đo tốc độ là chưa đủ và không nên giao quyết định an toàn cho AI. | Các số phút trong quy trình chỉ là ước lượng, chưa có baseline quan sát. | Tôi quyết định giữ nhãn giả định, cách đo thực tế, phương án không AI và tiêu chí chất lượng để nhóm kiểm chứng. |
| CP4 Research | Nhờ AI tra cứu tài liệu chính thức về PubMed, OpenAlex, Rayyan, Zotero và Elicit; tôi đối chiếu với ghi chú hai coach. | Giúp phân biệt công cụ tìm kiếm, sàng lọc và ghi chú; đưa ra nguồn để kiểm lại. | Tính năng công cụ không chứng minh chúng giải đúng pain của hai coach; dữ liệu phỏng vấn không cho biết chất lượng đầu ra của các công cụ. | Tôi giữ research là thông tin thứ cấp và đề xuất pilot riêng cho tìm/chọn với đọc/rút ý. |
| CP5 Quy trình | Thảo luận với AI cách vẽ quy trình và đo hai bước nghẽn khác nhau. | Giúp làm rõ 90 phút/lượt của A và 1 giờ/ngày của B là hai đơn vị khác nhau. | Quy trình trước đây dùng 160 phút giả định và coi đọc sâu là bottleneck chung. | Tôi yêu cầu bỏ tổng giả định, giữ thời gian chưa đo ở từng bước và tách hai nhánh. |
| CP5–6 Problem Statement | Nhờ AI chỉ ra lỗ hổng về actor, bottleneck, baseline, target và boundary. | Giúp xác định cần kiểm cả độ phủ bài lẫn độ đúng của ý rút ra. | Một Problem Statement gộp hai pain dễ khiến giải pháp và metric mơ hồ. | Tôi giữ kết luận rằng chưa thể chốt bottleneck chung; metric được đo riêng cho hai nhánh. |
| CP6 Mức can thiệp / quyết định | Thảo luận bốn mức No AI, Rule, Workflow, Agent và quyết định đề xuất. | Giúp chỉ ra bước nào có thể dùng rule và bước nào phải do người nghiên cứu kiểm. | Chưa có thử nghiệm để khẳng định AI Agent tiết kiệm thời gian hoặc giảm bỏ sót. | Tôi chọn **Not Yet**, ưu tiên đo và thử quy trình nhỏ trước khi quyết định mức AI. |

## 6. Reflection (CP7)

### 6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

Qua việc xem các vấn đề của các thành viên, tôi nhận ra mỗi người có một góc nhìn khác nhau. Một vấn đề cần được đánh giá dựa trên ai gặp khó khăn, tần suất xảy ra và bằng chứng thực tế, chứ không chỉ dựa vào cảm nhận cá nhân.

### 6.2. Nhóm có lúc nào bị “solution-first” không? Nhóm nhận ra và xử lý thế nào?

Trong quá trình xây dựng đề tài, nhóm có nguy cơ nghĩ ngay đến chatbot hoặc AI Agent để hỗ trợ nghiên cứu. Chúng tôi xử lý bằng cách mô tả quy trình tìm, chọn, đọc và rút ý; xác định bước nghẽn qua phỏng vấn; rồi ưu tiên kiểm tra phương án No AI và Rule trước khi cân nhắc AI Workflow hoặc Agent.

### 6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.

Có. Khi trao đổi với AI về card của Đào Đức Sơn liên quan đến đồng bộ nhân vật giữa các Roblox place, tôi nhận ra bottleneck chưa chắc nằm ở cập nhật dữ liệu mà có thể ở khâu kiểm thử sau thay đổi. Tôi vì thế đổi cách phản biện: hỏi bước nào thực sự mất thời gian và kiểm tra một giải pháp đơn giản trước khi nghĩ đến AI. Với card bài báo của mình, tôi cũng bỏ giả định rằng đọc sâu là bottleneck chung sau khi hai lab coach nêu hai bước khó khác nhau.

### 6.4. Kết quả kiểm chứng có làm tôi bất ngờ không? Điều gì?

Tôi bất ngờ khi hai lab coach cùng khảo sát tài liệu thường xuyên nhưng gặp khó khăn ở hai bước khác nhau. Coach A khó ở tìm kiếm, còn coach B khó ở đọc và rút ý chính có thể dùng. Điều này cho thấy tôi không nên giả định mọi người có cùng một bottleneck.

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

Khó nhất là xác định chính xác bottleneck và đặt metric đo được cho từng nhánh. Giảm thời gian chưa đủ: với tìm kiếm còn phải kiểm bài quan trọng bị bỏ sót, còn với rút ý phải kiểm ý có đúng nguồn và dùng được không. Tôi cũng cần giữ phần mô tả vấn đề tách khỏi ý tưởng giải pháp.

### 6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?

Tôi sẽ thu thập ví dụ cụ thể và bấm giờ từng bước sớm hơn. Khi phản biện nhóm, tôi sẽ hỏi bước nào thật sự nghẽn, bằng chứng nào chứng minh điều đó, chất lượng đầu ra sẽ được kiểm ra sao và liệu một quy trình đơn giản không dùng AI đã đủ hay chưa.

### 6.7. Hiểu bài: problem → quy trình → metric → boundary → mức can thiệp AI → quyết định

Problem của nhóm là người nghiên cứu gặp khó khăn khi tìm đủ bài báo liên quan và rút ý chính có thể dùng cho câu hỏi nghiên cứu. Quy trình hiện tại gồm xác định hướng nghiên cứu, tìm bài, chọn bài, đọc và rút ý. Hai phỏng vấn chưa chỉ ra một bottleneck chung: coach A khó ở tìm kiếm, còn coach B khó ở đọc và rút ý. Nhóm sẽ đo thời gian từng nhánh và kiểm chất lượng bằng số bài quan trọng bị bỏ sót hoặc độ đúng, khả năng dùng của ý rút ra; mục tiêu thử nghiệm là giảm ít nhất 25% thời gian mỗi nhánh so với baseline bấm giờ. Boundary là người nghiên cứu phải kiểm bài gốc và quyết định cuối cùng về bài được chọn cũng như ý được sử dụng. Nhóm ưu tiên thử No AI và Rule, chỉ cân nhắc AI Workflow khi cách đơn giản không đạt và có phép kiểm phù hợp. Vì chưa có baseline và kết quả pilot, quyết định hiện tại là **Not Yet**.

## 7. Tài liệu tham khảo

1. National Library of Medicine, *About PubMed*: https://pubmed.ncbi.nlm.nih.gov/about/
2. *Title and Abstract Screening and Evaluation in Systematic Reviews* (TASER pilot trial): https://pmc.ncbi.nlm.nih.gov/articles/PMC4217707/
3. Federal Trade Commission, *New trends in reports of imposter scams* (2026): https://consumer.ftc.gov/consumer-alerts/2026/05/new-trends-reports-imposter-scams
4. UNESCO, *Behind the Screens* (2024), khảo sát 500 người tạo nội dung: https://www.unesco.org/en/articles/shared-frontlines-unesco-bridges-gap-between-journalists-and-content-creators-age-doubt
5. WHO, *Heat and health*: https://www.who.int/en/news-room/fact-sheets/detail/climate-change-heat-and-health
6. UNICEF, *Learning Interrupted: Global Snapshot on Climate-related School Disruptions in 2025* (2026): https://www.unicef.org/reports/learning-interrupted
7. WHO, *Global patient safety report 2024*: https://iris.who.int/bitstream/handle/10665/376928/9789240095458-eng.pdf
8. Ghi chú hai cuộc phỏng vấn lab coach do tôi cung cấp ngày 09/11/2026; diễn ý và giới hạn được ghi trong [báo cáo nhóm](../team/group_report.md) mục 3.2.
9. National Library of Medicine, *PubMed Help*: https://pubmed.ncbi.nlm.nih.gov/help/
10. OpenAlex, *Searching* và *Sorting*: https://help.openalex.org/how-to/searching/ ; https://help.openalex.org/api/sorting/
11. Rayyan, *Getting Started*: https://help.rayyan.ai/hc/en-us/articles/22697630697617-Getting-Started-with-Rayyan
12. Zotero, *PDF Reader and Note Editor*: https://www.zotero.org/support/pdf_reader
13. Elicit, *Systematic Reviews* và *Limitations*: https://support.elicit.com/en/articles/14759154-systematic-reviews-in-elicit ; https://support.elicit.com/en/articles/14757928-elicit-s-limitations
14. UNESCO, *Science Report 2021 — Statistics and resources*: https://www.unesco.org/reports/science/2021/en/statistics — 8,854 triệu nhà nghiên cứu FTE năm 2018, không phải số người tìm bài hằng ngày.

