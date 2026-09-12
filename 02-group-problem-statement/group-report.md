# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

> Phần 3.2 → 6.3 bên dưới được dựng dựa trên 15 candidate thật do các thành viên đưa ra, research thật đã có nguồn kiểm được, và kinh nghiệm thật của Khánh (BA trực tiếp của dự án LNG) — nhóm đã xem lại và xác nhận dùng bản này để nộp.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Dương Dương | 2A202602498 | writer |
| 2   | Trần Thế Anh | 2A202602516 | research |
| 3   | Nguyễn Tuấn Khanh | 2A202602819 | research |
| 4   | Nguyễn Long Khánh | 2A202602649 | facilitator |
| 5   | Nguyễn Phạm Oanh Oanh | 2A202602518 | workflow |

**Candidate problem nhóm chọn (1 câu):**

```text
Dịch yêu cầu phân quyền mơ hồ thành RBAC scope-based
```


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Dương Dương | Đóng dấu các giấy tờ, biểu mẫu cho sinh viên | Sinh viên, phòng hành chính | Cán bộ phải kiểm tra và xử lý thủ công từng yêu cầu; việc đóng dấu thường yêu cầu sự có mặt của cán bộ và có thể tạo hàng chờ vào thời điểm nhiều sinh viên cùng thực hiện. | |
| 2 | Dương Dương | Tổ công tác sinh viên kiểm tra minh chứng để chấm điểm rèn luyện | Sinh viên | Việc mở, đọc và đối chiếu từng minh chứng với tiêu chí chấm điểm được thực hiện thủ công; số lượng minh chứng lớn khiến công việc lặp lại và mất nhiều thời gian | |
| 3 | Dương Dương | Nhân viên vệ sinh tòa nhà được yêu cầu phải dọn dẹp lại một khu vực mặc dù không thường xuyên có người sử dụng | Nhân viên phục vụ, nhà trường | Lịch vệ sinh đang dựa nhiều vào lịch cố định thay vì mức độ sử dụng thực tế của từng khu vực | |
| 4 | Trần Thế Anh | Tìm ô trống trong bãi | Người gửi xe | Baseline, góc camera, đêm/mưa | |
| 5 | Trần Thế Anh | Cập nhật biển còn chỗ chậm, Handoff rõ; tác động trực tiếp đến luồng xe | Người dân | Bãi đang dùng biển hay bộ đếm nào | |
| 6 | Trần Thế Anh | Tìm lại xe khi quên khu vực đỗ | Người đỗ xe | Tần suất xảy ra và mức người dùng chấp nhận cung cấp thông tin xe | |
| 7 | Nguyễn Tuấn Khanh | Tìm và chỉnh sửa lại một vài trang trong tài liệu đã in khi không xác định được file nguồn hoặc có quá nhiều phiên bản tương tự | Sinh viên, nhân viên sales, admin, kế toán, ... | File nguồn không được quản lý theo tài liệu đã in; nhiều phiên bản tương tự khiến người dùng không biết file nào là bản gốc/bản mới nhất. | cụ thể và dễ quan sát, bấm giờ, nhưng tần suất có thể không cao đối với một số nhóm người dùng |
| 8 | Nguyễn Tuấn Khanh | Tổng hợp và đối chiếu tình trạng giao dịch từ nhiều kênh bán hàng | Nhân viên sales, admin bán hàng, kế toán, ... | Pain có vẻ lớn và xảy ra thường xuyên, đặc biệt với shop/doanh nghiệp có nhiều kênh. Dễ đo ROI bằng số giờ tiết kiệm. | đã có khá nhiều phần mềm quản lý bán hàng/omnichannel, nên nếu làm AI cần tìm một ngách chưa được giải quyết tốt, thay vì chỉ "tự động tổng hợp đơn" |
| 9 | Nguyễn Tuấn Khanh | Tìm kiếm và nắm bắt knowledge của dự án khi nhân viên mới gia nhập | intern, nhân viên chuyển dự án/team | Knowledge của dự án nằm phân tán trong nhiều nguồn và thiếu context, không có một nơi trả lời được "tại sao, cái gì, phiên bản nào, ai quyết định" | Knowledge của dự án nằm phân tán trong nhiều nguồn và thiếu context |
| 10 | Nguyễn Phạm Oanh Oanh | Công cụ dịch thuật hiện tại kém hiệu quả (CAT truyền thống đắt/phức tạp, tool miễn phí sai ngữ cảnh) | Dịch giả tự do, nhà xuất bản, người dùng cá nhân | Mất nhiều thời gian học sử dụng tool (20h), phải chỉnh sửa thủ công liên tục do phần mềm không tự học được văn phong, chi phí đăng ký cao | |
| 11 | Nguyễn Phạm Oanh Oanh | Quy trình đánh giá Lead B2B lỏng lẻo, gây lãng phí nguồn lực bán hàng | Nhân viên Kinh doanh (Sales B2B) | Thiếu tiêu chí và kịch bản sàng lọc khách hàng ở đầu phễu, mất nhiều thời gian tư vấn nhưng chốt hụt do sai tệp khách hàng (vượt ngân sách, sai nhu cầu) | |
| 12 | Nguyễn Phạm Oanh Oanh | Quy trình tính toán và lập báo giá điện mặt trời, làm sụt giảm tỷ lệ chuyển đổi doanh số | Nhân viên tư vấn bán hàng (Sales Reps), Đội ngũ kỹ thuật hỗ trợ | Khâu tính toán công suất và chờ duyệt báo giá thủ công qua quá nhiều bước, tốc độ phản hồi chậm khiến khách hàng chờ lâu và rời bỏ phễu bán hàng | |
| 13 | Nguyễn Long Khánh | Dịch yêu cầu phân quyền mơ hồ thành RBAC scope-based | Nhân viên các phòng ban khác nhau | Khi HR đưa yêu cầu phân quyền bằng ngôn ngữ tự nhiên (VD: "trưởng phòng khu vực chỉ xem hồ sơ khu vực mình"), tôi phải tự đối chiếu thủ công với toàn bộ `ScopedRolePermissions`/`AccessAssignment` đã tồn tại để tránh tạo scope trùng/chồng chéo; Tôi (BA) trực tiếp; dev bị chờ đặc tả đúng mới code được | **→ Được nhóm chọn** |
| 14 | Nguyễn Long Khánh | Làm rõ yêu cầu KPI mơ hồ thành công thức đo được | Dev, Nhân viên | dev sửa lại tốn công, HR mất niềm tin vào số liệu, lặp lại mỗi khi dashboard mở rộng; so sánh Rule (template câu hỏi) | |
| 15 | Nguyễn Long Khánh | Quyết định cũ bị "quên" khi có thay đổi mới | BA, Dev, gián tiếp cả dự án LNG | Việc đối chiếu yêu cầu mới với quyết định thiết kế cũ phụ thuộc hoàn toàn vào trí nhớ cá nhân, không có nơi tra cứu tập trung; mâu thuẫn thường chỉ lộ ra sau khi dev đã code gần xong, phải revert/sửa lại | |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Thông tin/quyết định phân tán, phải tự đối chiếu thủ công | #7, #8, #9, #13, #15 | Dữ liệu hoặc quyết định nằm rải rác nhiều nguồn (file cũ, quyết định thiết kế, quy tắc phân quyền); người phải tự nhớ/tự tra bằng tay trước khi làm bước tiếp theo, sai sót phát hiện muộn | Cụm rộng nhất (5 candidate), trải trên 2 người đưa ra (Khanh, Khánh) — cho thấy pattern "thiếu nơi tra cứu tập trung" lặp lại ở nhiều bối cảnh khác nhau |
| B — Thông tin không gian/thời gian thực (bãi xe) | #4, #5, #6 | Cần dữ liệu cập nhật liên tục (chỗ trống, vị trí xe), phụ thuộc cảm biến/camera phần cứng, không chỉ là vấn đề xử lý ngôn ngữ/văn bản | Khác hẳn nhóm A về bản chất kỹ thuật — cần input phần cứng, khó làm gọn trong 1 buổi lab |
| C — Thủ tục hành chính/dịch vụ vật lý theo lịch cố định | #1, #2, #3 | Việc phụ thuộc vào lịch cố định hoặc sự có mặt của con người, chưa tận dụng dữ liệu sử dụng thực tế để tối ưu | Gần với bài toán "lập lịch theo nhu cầu thực tế" hơn là bài toán ngôn ngữ tự nhiên |
| D — Tư vấn/tính toán nghiệp vụ tốn thời gian, ảnh hưởng chuyển đổi | #10, #11, #12, #14 | Mỗi lượt xử lý (tư vấn, báo giá, làm rõ KPI) tốn nhiều thời gian và có thể làm mất khách hàng/niềm tin nếu chậm hoặc sai; cần chuẩn hoá câu hỏi/công thức | Đa dạng ngành (dịch thuật, sales B2B, năng lượng, KPI nội bộ) — khó chọn 1 đại diện vì mỗi bài cần domain riêng |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #13 — RBAC scope-based (Khánh, cluster A) | Duy nhất trong 15 candidate đã có sẵn Problem Card đầy đủ (actor, workflow 5 bước, bottleneck, metric, non-AI alternative) từ vòng cá nhân; đã có research (AWS IAM, OpenFGA, OPA) chứng minh hướng đi hợp lý | Chỉ Khánh hiểu sâu domain RBAC/dự án LNG, 4 bạn còn lại không có ngữ cảnh; số liệu 15-20 phút vẫn là ước lượng cá nhân, chưa validate |
| #8 — Tổng hợp giao dịch đa kênh (Khanh, cluster A) | Actor rõ (sales/admin/kế toán), pain có vẻ lớn và lặp lại thường xuyên với shop nhiều kênh, dễ hình dung ROI | Workflow mới chỉ có 1 dòng mô tả lúc pitch, chưa vẽ được các bước cụ thể; thị trường đã có nhiều tool omnichannel, cần tìm ngách rõ hơn mới so sánh được Rule/Workflow/Agent |
| #12 — Báo giá điện mặt trời (Oanh Oanh, cluster D) | Bottleneck rõ (chờ duyệt báo giá qua nhiều bước), impact đo được trực tiếp bằng tỷ lệ chuyển đổi bị mất | Cần hiểu sâu nghiệp vụ kỹ thuật điện mặt trời để làm đúng công thức tính công suất — chỉ 1 người trong nhóm rành, khó cả nhóm cùng phản biện trong buổi lab |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #13 — RBAC scope-based | 5 | 5 | 4 | 4 | 5 | 5 | 3 | 31 |
| #8 — Tổng hợp giao dịch đa kênh | 4 | 2 | 3 | 3 | 3 | 2 | 3 | 20 |
| #12 — Báo giá điện mặt trời | 4 | 2 | 3 | 3 | 2 | 2 | 2 | 18 |

> Vì sao #13 được 5 điểm ở "Workflow rõ" và "So sánh R/W/A được": đây là candidate duy nhất đã có draft workflow trước/sau đầy đủ thời gian từng bước và đã phân tích riêng Rule vs Workflow vs Agent trong Problem Card gốc — 2 bài còn lại mới dừng ở mô tả problem, chưa vẽ được workflow. Vì sao #13 chỉ được 3 điểm "Nhóm hiểu domain": RBAC là domain kỹ thuật, chỉ Khánh trực tiếp làm dự án LNG, các thành viên khác cần thời gian để hiểu trước khi phản biện sâu.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Đối chiếu thủ công yêu cầu phân quyền HR với scope RBAC đã tồn tại
(Problem Card #1 — Nguyễn Long Khánh)
```

**Vì sao chọn (4-5 câu):**

```text
Điểm số (31/35) cách biệt rõ so với 2 candidate còn lại trong shortlist,
chủ yếu vì #13 là bài duy nhất đã có sẵn Problem Card đầy đủ actor, workflow
5 bước, bottleneck và metric từ vòng cá nhân — nhóm không phải dựng lại từ
đầu. Impact dễ đo (15-20 phút/lần → dưới 5 phút) và ranh giới AI hỗ trợ vs
người duyệt rất dễ giải thích cho cả nhóm dù không rành kỹ thuật RBAC: AI
chỉ gợi ý, BA vẫn là người duyệt cuối. Bài toán cũng lặp lại thường xuyên
(mỗi khi có yêu cầu phân quyền mới) nên impact tích lũy theo thời gian dễ
thuyết phục hơn các bài chỉ xảy ra không định kỳ.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#8 (Tổng hợp giao dịch đa kênh): pain có vẻ thật và lặp lại, nhưng nhóm mới
chỉ có 1 dòng mô tả, chưa ai vẽ được workflow chi tiết ngay trong buổi lab;
thị trường đã có nhiều tool omnichannel nên nhóm ngại khó tìm ra góc khác
biệt kịp trong thời gian ngắn.

#12 (Báo giá điện mặt trời): impact rõ nhưng đòi hỏi hiểu sâu nghiệp vụ kỹ
thuật (tính công suất, quy trình duyệt nội bộ ngành năng lượng) mà chỉ một
mình Oanh Oanh nắm được — cả nhóm khó cùng phản biện đúng trọng tâm.

Cluster B (bãi xe) và C (thủ tục hành chính) không vào shortlist vì phụ
thuộc phần cứng/cảm biến (camera, bộ đếm) nhiều hơn là xử lý ngôn ngữ/dữ
liệu — lệch hướng so với thế mạnh AI ngôn ngữ mà lớp đang tập trung, và
nhóm chưa có dữ liệu cảm biến thật để đối chiếu.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Có một băn khoăn nhỏ: các bạn không làm trực tiếp dự án LNG lo ngại khó
hiểu domain RBAC đủ sâu để đóng góp ý kiến trong các phase sau. Nhóm xử lý
bằng cách thống nhất Khánh sẽ diễn giải lại các thuật ngữ kỹ thuật
(ScopedRolePermissions, AccessAssignment) bằng ví dụ nghiệp vụ đơn giản
trước mỗi phase, và cả nhóm tập trung phản biện vào phần dễ đánh giá chung
— ranh giới AI gợi ý vs người duyệt, độ tin cậy khi AI sai — thay vì đi sâu
chi tiết kỹ thuật RBAC.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

> Do giới hạn thời gian buổi lab, nhóm dùng cách xác nhận nội bộ thay cho
> phỏng vấn người ngoài: lấy trực tiếp kinh nghiệm thật của Khánh (BA đang
> làm dự án LNG) làm nguồn chính, đối chiếu chéo với pattern quan sát được
> từ chính candidate thật của các thành viên khác trong Cluster A (#7, #8,
> #9 — cùng dạng "thiếu nơi tra cứu tập trung"), thay vì phỏng vấn người
> ngoài nhóm.

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Xác nhận nội bộ — người trong cuộc (Khánh) | 1 người (Khánh, BA thật của dự án LNG, không phải người ngoài phỏng vấn) | Khánh: "Đúng, mỗi lần HR đưa yêu cầu phân quyền mới, mình đều phải tự đọc lại toàn bộ scope cũ để tránh trùng, khoảng 15-20 phút mỗi lần, và số lượng scope càng tăng thì càng dễ sót." | Khánh cũng thừa nhận: "Số liệu này là ước lượng cá nhân, mình chưa bấm giờ chính xác qua nhiều lần, và ScopedRolePermissions/AccessAssignment hiện có nằm rải rác, chưa chắc export được gọn để AI đọc ngay." | Giữ nguyên hướng problem nhưng không coi 15-20 phút là số đã chốt — ghi rõ đây là ước lượng cần đo lại, đúng lý do quyết định cuối là Not Yet chứ không phải Go |
| Đối chiếu chéo nội bộ nhóm (không phải survey ngoài) | 3 candidate cùng cluster A từ Nguyễn Tuấn Khanh (#7, #8, #9) | Cả 3 candidate của Khanh đều có cùng pattern "dữ liệu/quyết định phân tán, không nơi tra cứu tập trung, phải tự nhớ/tự đối chiếu" — củng cố rằng đây không phải vấn đề riêng của RBAC mà là pattern lặp lại ở nhiều bối cảnh khác nhau trong chính nhóm | Đây là bằng chứng cùng nhóm, không phải mẫu độc lập bên ngoài — không thay được cho một khảo sát thật với người ngoài dự án LNG | Ghi nhận là tín hiệu củng cố hướng đi (pattern có thật, lặp lại), nhưng không dùng để khẳng định quy mô/tần suất — quy mô/tần suất thật vẫn cần đo trực tiếp trên dự án LNG nếu triển khai pilot |
| Nguồn công khai (industry research — **bổ sung, không thay được interview**) | 3 nguồn: NIST, Orca Security, CrossID | NIST: RBAC "thuần" gây role explosion, cần thêm attribute để kiểm soát ([nist.gov](https://www.nist.gov/publications/adding-attributes-role-based-access-control)). Orca Security: *"You cannot see sprawl from a point-in-time IAM export... manual annual reviews collapse at cloud scale"* ([orca.security](https://orca.security/resources/blog/entitlement-sprawl-privilege-creep/)). CrossID: role chồng chéo gây *"redundancy, confusion, increased administration, difficulty in auditing"* ([crossid.io](https://www.crossid.io/academy/role-based-access-control-rbac-challenges)) | Cả 3 nguồn đều nói ở quy mô doanh nghiệp lớn (hàng nghìn identity) — dự án LNG còn nhỏ, chưa chắc đã tới ngưỡng "collapse" như mô tả; cần validate lại đúng quy mô thật của LNG | Giữ nguyên problem nhưng hạ mức độ khẩn cấp trong Problem Statement — đây là rủi ro "sẽ nặng dần nếu không xử lý sớm", chưa phải khủng hoảng ngay bây giờ ở quy mô LNG |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Nguồn công khai xác nhận "role/scope chồng chéo khó audit" là vấn đề công
nghiệp có thật, không phải nhóm tự nghĩ ra — nhưng đây là bằng chứng gián
tiếp (industry research ở quy mô lớn), CHƯA phải validation trực tiếp trên
chính dự án LNG. Nhóm vẫn cần tự làm ít nhất 1 interview/survey thật với
người có kinh nghiệm gần với bối cảnh LNG trước khi chốt Problem Statement
v1, để biết pain này đã tới mức đáng làm hay còn nhẹ.
```

Bằng chứng đính kèm: chưa có file survey/interview riêng — bằng chứng nội bộ nằm trực tiếp trong bảng trên (kinh nghiệm thật của Khánh) và trong bảng 15 candidate ở Phase 3.1.

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| AWS IAM Access Analyzer | [docs.aws.amazon.com](https://docs.aws.amazon.com/IAM/latest/UserGuide/access-analyzer-policy-validation.html) | Tự động quét toàn bộ policy hiện có để phát hiện quyền quá rộng/không dùng tới; có thể generate policy ít quyền nhất dựa trên log sử dụng thực tế (CloudTrail) | Cảnh báo theo mức độ nghiêm trọng (severity), tích hợp real-time ngay lúc tạo/sửa policy — giống ý tưởng "AI gợi ý ngay lúc BA viết đặc tả" | Là hệ thống rule-based/heuristic (>100 check cố định) xây riêng cho AWS IAM, không tự hiểu yêu cầu ngôn ngữ tự nhiên như hypothesis của nhóm; không tổng quát hoá được sang model tuỳ biến như AccessAssignment/ScopedRolePermissions | Hướng "sinh policy từ log sử dụng thực tế" đáng học — thay vì chỉ đối chiếu tĩnh, có thể dùng lịch sử truy cập thật để gợi ý scope hợp lý hơn |
| OpenFGA (triển khai mô hình Zanzibar của Google) | [openfga.dev/docs/authorization-concepts](https://openfga.dev/docs/authorization-concepts) | Định nghĩa phân quyền dạng quan hệ (relationship) giữa user-object theo scope, cùng triết lý với AccessAssignment/ScopedRolePermissions (không gắn quyền thẳng vào Department/Team) | Mô hình đã được Google kiểm chứng ở quy mô lớn (Drive, YouTube, Calendar); tách biệt rõ logic phân quyền khỏi ứng dụng, dễ audit | Chỉ là API kỹ thuật — dev vẫn phải tự viết đúng quan hệ; không có lớp "đọc yêu cầu tiếng Việt tự nhiên rồi tự map vào quan hệ" mà nhóm đang nhắm tới | Xác nhận mô hình scope-based dự án LNG đang dùng là hướng thiết kế đã được kiểm chứng công nghiệp, không phải nhóm tự nghĩ ra — khoảng trống thật nằm ở lớp "dịch ngôn ngữ tự nhiên → quan hệ kỹ thuật", đúng chỗ AI có thể đóng góp mà OpenFGA chưa làm |
| Open Policy Agent (OPA) — Separation of Duty checks | [openpolicyagent.org/docs/comparisons/access-control-systems](https://www.openpolicyagent.org/docs/comparisons/access-control-systems) | Cho phép viết rule truy vấn "có cặp role nào không được phép gán đồng thời cho cùng một người không" — gần với bài toán phát hiện scope trùng/xung đột của nhóm | Chính sách viết dưới dạng code (Rego), có audit trail đầy đủ cho mọi quyết định — dễ truy vết khi có sự cố | OPA không tự động chặn/phát hiện xung đột — nhóm vẫn phải tự biết trước cần hỏi cặp role nào, không tự "hiểu" yêu cầu mới như hypothesis AI của nhóm | Muốn AI gợi ý được, trước tiên cần có audit trail/decision log ghi lại có cấu trúc — nếu quyết định RBAC không được ghi lại rõ ràng, AI (hay cả OPA) cũng không có gì để đối chiếu |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không cần xây lại một hệ thống RBAC mới — mô hình scope-based hiện tại của
LNG đã đi đúng hướng đã được công nghiệp kiểm chứng (Zanzibar/OpenFGA).
Khoảng trống thật sự nằm ở lớp giữa "yêu cầu ngôn ngữ tự nhiên của HR" và
"cấu trúc scope/quan hệ kỹ thuật" — đây là nơi AI (mức Workflow, không phải
Agent) có thể đóng góp thật sự, đúng như hypothesis ban đầu. Điều kiện tiên
quyết (bài học từ OPA): cần có một decision/scope log được ghi lại có cấu
trúc trước, nếu không AI cũng không có gì để đối chiếu — điều này cũng nối
lại với Problem #3 (quyết định cũ bị quên) trong bảng scan cá nhân.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

```text
[1 HR mô tả yêu cầu: 5'] → [2 BA đối chiếu toàn bộ scope cũ: 15-20' — NGHẼN]
→ [3 BA quyết định scope mới/tái dùng: 5-10'] → [4 BA viết đặc tả kỹ thuật: 10']
→ [5 Dev implement + BA test lại: biến động, có thể phát sinh sửa lại]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | HR | Nhu cầu phân quyền, diễn đạt bằng lời/chat | Mô tả yêu cầu bằng ngôn ngữ tự nhiên | 5' / mỗi khi có thay đổi tổ chức-nhân sự | Input không có cấu trúc, dễ hiểu sai giữa HR và BA |
| 2 | BA (Khánh) | Yêu cầu mới + toàn bộ `ScopedRolePermissions`/`AccessAssignment` hiện có | Danh sách scope liên quan/nghi trùng | 15-20' mỗi yêu cầu | **BOTTLENECK** — hoàn toàn thủ công, phụ thuộc trí nhớ, tăng dần theo số scope tích luỹ |
| 3 | BA | Danh sách scope liên quan | Quyết định tạo scope mới hoặc tái dùng scope cũ | 5-10' | Handoff BA → Dev bắt đầu từ đây |
| 4 | BA | Quyết định scope | Đặc tả kỹ thuật gửi dev | 10' | Văn bản dạng kỹ thuật, HR không tự đọc lại được (liên hệ Problem #4 trong scan cá nhân) |
| 5 | Dev | Đặc tả kỹ thuật | Code phân quyền đã implement | Biến động (giờ-ngày) | Phải sửa lại nếu bước 2 bỏ sót xung đột |

**Bottleneck chính (2-3 câu):**

```text
Bước 2 (BA đối chiếu scope cũ) là nghẽn chính: hoàn toàn thủ công, không có
công cụ tra cứu, và càng về sau số lượng scope trong hệ thống càng nhiều
thì càng dễ bỏ sót. Đây cũng là bước duy nhất đứng giữa hệ thống và rủi ro
tạo scope trùng/chồng chéo quyền.
```

### 5.2. Future workflow bản nhóm

```text
[1 HR mô tả yêu cầu: 5' - người] → [2 AI quét scope cũ, gợi ý/cảnh báo trùng: 2' - máy]
→ [3 BA xác nhận gợi ý trước khi dùng: 5' - BOUNDARY, người quyết cuối]
→ [4 AI draft đặc tả kỹ thuật, BA hiệu đính: 3' - máy+người] → [5 Dev implement]

Fallback: nếu AI gợi ý sai hoặc không đủ tự tin (VD: scope log thiếu dữ
liệu) → BA quay lại đối chiếu thủ công như quy trình hiện tại. Không bước
AI nào được áp dụng thẳng vào hệ thống mà thiếu người duyệt.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | ~45-55 phút/yêu cầu | ~15 phút/yêu cầu | BA tự log thời gian từng bước trong 2-3 tuần triển khai thử |
| Số bước | 5 bước | 5 bước (không đổi số bước, đổi ai làm bước 2 và 4) | Đếm bước trong workflow |
| Số bước thủ công | 4/5 bước hoàn toàn tay | 2/5 bước hoàn toàn tay (bước 1, 3) | So sánh cột Actor trước/sau |
| Bottleneck chính | Đối chiếu scope thủ công (15-20') | BA review gợi ý AI (5') | Đo thời gian riêng bước 2/3 |
| Risk mới | — | AI gợi ý sai lệch ngữ nghĩa nếu scope/decision log không cập nhật đầy đủ | BA đối chiếu ngẫu nhiên định kỳ giữa gợi ý AI và kết quả thực tế |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | BA (Khánh) — người trực tiếp đối chiếu và quyết định scope; HR — người đưa yêu cầu bằng ngôn ngữ tự nhiên; Dev — người chờ đặc tả đúng để implement. |
| **Workflow** | HR mô tả yêu cầu phân quyền → BA đối chiếu thủ công với scope RBAC hiện có (`ScopedRolePermissions`/`AccessAssignment`) → BA quyết định scope mới/tái dùng → BA viết đặc tả kỹ thuật → Dev implement và BA test lại. |
| **Bottleneck** | Bước đối chiếu thủ công (15-20 phút/lần), phụ thuộc hoàn toàn vào trí nhớ và khả năng đọc lại toàn bộ scope hiện có của BA, mức độ khó tăng dần khi số lượng scope tích luỹ theo thời gian dự án. |
| **Impact** | Nếu bỏ sót, hệ thống dễ có scope trùng/chồng chéo hoặc lỗ hổng phân quyền; phát hiện muộn (sau khi dev code) phải sửa lại toàn bộ phần liên quan, ảnh hưởng tiến độ dự án LNG. |
| **Success Metric** | Giảm thời gian đối chiếu từ 15-20 phút xuống dưới 5 phút/yêu cầu; giảm số lần phải sửa scope do phát hiện trùng/xung đột muộn — hiện chưa có baseline đo chính thức, mới là ước lượng cá nhân của BA, cần validate thêm. |
| **Boundary** | Làm: AI hỗ trợ gợi ý/cảnh báo scope dựa trên dữ liệu scope hiện có. Không làm: AI không tự tạo/sửa/xoá scope trong hệ thống, không tự động áp dụng thay đổi phân quyền, không xử lý các module ngoài HR. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Success Metric — con số 15-20 phút và mốc "dưới 5 phút" vẫn là ước lượng của một cá nhân (BA), chưa có baseline đo bằng log/khảo sát qua nhiều yêu cầu thật.
- Tôi sửa gì: Giữ hướng metric nhưng thêm điều kiện rõ ràng rằng baseline cần được xác nhận qua 2-3 tuần theo dõi thực tế trước khi chốt Problem Statement v1, thay vì khẳng định chắc chắn con số này đúng cho mọi trường hợp.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: "gợi ý scope phù hợp" không có một đáp án đúng duy nhất, phụ thuộc ngữ cảnh nghiệp vụ của từng phòng ban.
- Độ phức tạp: [x] Thấp (1-2 bước) / [ ] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: chỉ cần đối chiếu 2 nguồn (scope hiện có + yêu cầu mới) để ra 1 gợi ý, không có nhiều bước phụ thuộc lẫn nhau.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ phức tạp thấp + Độ mơ hồ cao → "Workflow có AI hỗ trợ một bước có thể đủ"
```

**Vì sao (2-3 câu):**

```text
Bài toán chỉ cần AI hỗ trợ đúng một bước (đối chiếu & gợi ý scope), không
cần điều phối nhiều bước phụ thuộc kết quả lẫn nhau nên độ phức tạp thấp.
Nhưng vì output "đúng" có thể khác nhau tuỳ ngữ cảnh nghiệp vụ (không phải
đúng/sai tuyệt đối như phân loại cố định), nên độ mơ hồ cao — một Rule
cứng khó bao quát hết, cần AI hỗ trợ ở mức Workflow.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Bảng tra cứu scope tĩnh (spreadsheet/Notion), cập nhật thủ công mỗi khi có scope mới | Khi số lượng scope còn ít (ước lượng dưới 20) và ít thay đổi | Người vẫn phải tự đọc và tự so khớp ngữ nghĩa; không giải quyết gốc vấn đề "hiểu yêu cầu ngôn ngữ tự nhiên" | Không chọn làm giải pháp chính — giữ làm **fallback** khi AI không đủ tự tin |
| **Workflow** | AI đọc scope hiện có + yêu cầu mới (ngôn ngữ tự nhiên), gợi ý scope phù hợp hoặc cảnh báo trùng; BA duyệt trước khi gửi dev | Khi các bước đã rõ ràng theo một trình tự cố định, không cần AI tự quyết định bước tiếp theo | AI gợi ý sai lệch ngữ nghĩa nếu scope/decision log thiếu cập nhật | **ĐƯỢC CHỌN** — dùng cho bước 2 (đối chiếu & gợi ý) và hỗ trợ bước 4 (draft đặc tả) |
| **Agent** | AI tự đọc nhiều nguồn, tự quyết định tạo/sửa scope, tự gọi hệ thống để áp dụng thay đổi | Chỉ cần nếu muốn tự động hoá toàn bộ vòng đời scope mà không cần người duyệt | Rủi ro cao nhất — đây là hệ thống phân quyền/bảo mật, Agent tự quyết sai có thể gây lỗ hổng nghiêm trọng, khó truy vết | **KHÔNG CHỌN** — rủi ro vượt quá lợi ích ở quy mô hiện tại của LNG |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? → Không đủ. Một bảng tra cứu tĩnh chỉ giúp tra nhanh hơn nhưng người vẫn phải tự hiểu ngữ cảnh của yêu cầu HR bằng ngôn ngữ tự nhiên — ước tính chỉ đỡ được khoảng 30-40% công sức đối chiếu.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? → Đi thẳng một đường: mô tả yêu cầu → đối chiếu → gợi ý → người duyệt → viết đặc tả → dev implement; không có nhánh phức tạp cần AI tự chọn hướng đi khác.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? → Không. AI chỉ cần đọc 2 nguồn (scope hiện có, yêu cầu mới) và trả về một gợi ý; không cần tự gọi hệ thống khác hay tự quyết định chuỗi hành động nhiều bước.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? → BA là người duyệt cuối (bước 3, human boundary), phát hiện ngay tại chỗ trước khi bất kỳ thay đổi nào được áp dụng; nếu sót, dev có thể phát hiện thêm ở bước implement/test.
5. Có hạ được từ Agent → Workflow → Rule không? → Có. Nếu Workflow chạy ổn định và ít lỗi trong một thời gian, nhóm có thể hạ về Rule (bảng tra cứu + vài quy tắc cố định) cho các loại yêu cầu lặp lại phổ biến nhất, giữ AI cho các trường hợp mơ hồ hơn.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
AI chỉ cần hỗ trợ đúng một bước (đối chiếu & gợi ý scope) trong một chuỗi
bước đã rõ ràng, không cần tự lập kế hoạch nhiều bước hay tự gọi hệ thống
khác — đúng đặc điểm của mức Workflow. Ranh giới AI hỗ trợ vs người quyết
rất rõ: BA luôn là người duyệt cuối trước khi bất kỳ thay đổi phân quyền
nào được áp dụng, phù hợp với một bài toán chạm tới bảo mật/phân quyền có
rủi ro cao nếu sai.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Vì đầu vào là ngôn ngữ tự nhiên, không có cấu trúc cố định — một bảng tra
cứu tĩnh (Rule) không tự "hiểu" được ý nghĩa của yêu cầu mới để so khớp
ngữ nghĩa với scope cũ, người vẫn phải tự đọc hết, không giải quyết được
gốc của bottleneck.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | BA (Khánh) — người trực tiếp đối chiếu và quyết định scope; HR — người đưa yêu cầu bằng ngôn ngữ tự nhiên; Dev — người chờ đặc tả và implement. |
| **Workflow** | HR mô tả yêu cầu phân quyền → BA đối chiếu thủ công với scope RBAC hiện có → BA quyết định scope mới/tái dùng → BA viết đặc tả kỹ thuật → Dev implement và BA test lại. |
| **Bottleneck** | Bước đối chiếu thủ công (15-20 phút/lần), phụ thuộc hoàn toàn vào trí nhớ của BA, không có công cụ tra cứu nhanh, khó khăn tăng dần theo số lượng scope tích luỹ. |
| **Impact** | Scope trùng/chồng chéo phát hiện muộn (sau khi dev code) gây rework, trễ tiến độ dự án LNG và tiềm ẩn rủi ro lỗ hổng phân quyền. |
| **Success Metric** | Giảm thời gian đối chiếu từ 15-20 phút xuống dưới 5 phút/yêu cầu; giảm số lần sửa lại scope do phát hiện xung đột muộn — đo bằng cách BA tự log thời gian đối chiếu trước/sau qua 4-6 tuần triển khai thử. |
| **Boundary** (làm / không làm) | Làm: AI gợi ý/cảnh báo scope dựa trên dữ liệu scope hiện có. Không làm: AI không tự tạo/sửa/xoá scope, không tự động áp dụng thay đổi phân quyền, không xử lý module ngoài HR. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp sau bước "HR mô tả yêu cầu" (bước 1), trước bước "BA quyết định scope mới/tái dùng" (bước 3) — hỗ trợ trực tiếp bước đối chiếu (bước 2) và có thể hỗ trợ thêm bước viết đặc tả (bước 4). |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow — vì chỉ cần AI hỗ trợ một bước rõ ràng trong chuỗi tuần tự, không cần tự lập kế hoạch nhiều bước hay tự gọi công cụ khác. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất: AI gợi ý sai/sót do scope hoặc decision log chưa được ghi đầy đủ, dẫn tới scope trùng/chồng chéo nếu BA quá tin tưởng AI mà không kiểm kỹ. BA (Khánh) kiểm tra trực tiếp trước khi gửi dev; dev kiểm tra thêm lần nữa khi implement/test. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Đã có Problem Card cá nhân + workflow trước/sau chi tiết theo từng bước, actor rõ (BA, HR, Dev). |
| Baseline + metric đo được chưa? | Not Yet | Số liệu 15-20 phút hiện tại là ước lượng cá nhân của một mình BA, chưa có baseline đo bằng log/khảo sát qua nhiều yêu cầu thật hoặc qua interview/survey đã validate. |
| Data/input đủ dùng chưa? | Not Yet | Chưa xác nhận được `ScopedRolePermissions`/`AccessAssignment` hiện có ở dạng export/đọc được cho AI hay phần lớn vẫn nằm trong đầu BA — cần kiểm tra trước khi build. |
| AI sai, hậu quả chấp nhận được không? | Yes (có điều kiện) | Vì luôn có bước BA duyệt trước khi áp dụng, hậu quả tệ nhất là BA phải làm lại như quy trình cũ — không tự động gây lỗ hổng nếu boundary được giữ đúng. |
| Có người review/owner không? | Yes | BA (Khánh) là owner kiêm reviewer chính trong workflow đề xuất. |
| Có cách non-AI đơn giản hơn không? | Có nhưng chưa đủ | Bảng tra cứu tĩnh (Rule) đỡ được một phần nhưng không giải quyết được bước "hiểu yêu cầu ngôn ngữ tự nhiên" — vẫn cần AI ở mức Workflow để giải đúng gốc bottleneck. |

**Decision:**

```text
Not Yet
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Actor, workflow và hướng can thiệp AI đã đủ rõ để hình dung giải pháp,
nhưng hai điều kiện đầu vào quan trọng nhất cho một pilot còn thiếu bằng
chứng: (1) baseline thời gian mới là ước lượng của một cá nhân, chưa qua
interview/survey thật; (2) chưa xác nhận được scope/decision log hiện có
có ở dạng đủ sạch để AI đọc hay không. Quyết định "Go" ngay lúc này sẽ rơi
vào đúng kiểu rủi ro mà lab cảnh báo — làm AI vì muốn làm AI, chứ chưa chắc
dữ liệu đã sẵn sàng — nên nhóm chọn Not Yet để validate thêm trước.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
(Chỉ áp dụng nếu sau khi validate xong nhóm quyết định Go) Data: export
toàn bộ ScopedRolePermissions/AccessAssignment hiện có dạng text + 5-10
yêu cầu phân quyền thật gần đây. Chạy tay: BA tự đối chiếu thủ công như cũ
nhưng có AI chạy song song để so sánh gợi ý. Đo 3 số: thời gian đối chiếu
(AI hỗ trợ vs thủ công), số lần AI gợi ý đúng/sai so với quyết định cuối
của BA, số lần BA phải bỏ qua gợi ý AI vì không đủ tin cậy.
```

**Nếu Not Yet — cần validate gì trước:**

```text
(1) BA tự log thời gian đối chiếu thật trong 2-3 tuần tới cho mọi yêu cầu
phân quyền mới để có baseline thay vì ước lượng. (2) Kiểm tra xem
ScopedRolePermissions/AccessAssignment có export được ra dạng text/schema
mà AI đọc được không. (3) Phỏng vấn/khảo sát thêm 2-3 người có vai trò
BA/quản trị phân quyền tương tự (ngoài chính mình) để xác nhận pain này
phổ biến, không chỉ là trải nghiệm cá nhân ở một dự án.
```

**Nếu No-Go — làm gì thay AI:**

```text
(Chỉ áp dụng nếu validate cho kết quả pain không đủ lớn) Dùng Rule đơn
giản: một bảng tra cứu scope tập trung (spreadsheet/Notion), cập nhật thủ
công mỗi khi có scope mới, kèm quy ước đặt tên scope rõ ràng để giảm nguy
cơ trùng lặp mà không cần đầu tư AI.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng dùng AI và quay về đối chiếu thủ công nếu: (1) tỷ lệ gợi ý sai của AI
vượt một ngưỡng chấp nhận được (ví dụ trên 20% số lần) trong giai đoạn
pilot; (2) scope/decision log không được duy trì cập nhật đầy đủ khiến AI
không còn dữ liệu đáng tin để đối chiếu; (3) BA nhận thấy thời gian kiểm
tra lại gợi ý AI còn tốn hơn tự đối chiếu thủ công.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 *(thực tế 15 → 1, do nhóm có 5 thành viên)* (cluster + shortlist + score)
- [x] Có validation + research (link kiểm được) *(validation là xác nhận nội bộ từ người trong cuộc — Khánh — không phải phỏng vấn người ngoài dự án; research (AWS IAM, OpenFGA, OPA) có link kiểm được)*
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
