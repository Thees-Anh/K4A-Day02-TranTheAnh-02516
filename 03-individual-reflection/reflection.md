# 03 — Individual Reflection

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Liệt kê 10 vấn đề từ góc nhìn người lái, bảo vệ và quản lý bãi | Chọn được 3 bài có actor, workflow và metric rõ |
| Pitch Problem Card | Pitch bài người lái phải chạy vòng tìm ô trống | Nhóm đưa bài vào shortlist vì có thể đo thời gian cổng–đến–ô |
| Challenge bài khác | Đặt câu hỏi liệu biển theo khu hoặc bộ đếm cổng đã giải được phần lớn pain chưa | Nhóm giữ Rule/non-AI làm baseline thay vì mặc định chọn camera |
| Gom cluster | Gom 9 candidates thành tìm/điều hướng, vận hành và dữ liệu quản lý | Tránh xem các biểu hiện gần nhau là nhiều problem độc lập |
| Chọn candidate | Ưu tiên bài tìm ô trống vì impact trực tiếp và pilot nhỏ được | Hai bài còn lại trở thành lợi ích phụ |
| Validation/research | So sánh Ultralytics Parking Management, PKLot, CNRPark+EXT và phương án sensor/rule | Nhóm thấy tool/dataset có sẵn không thay thế kiểm chứng tại bãi mục tiêu |
| Workflow nhóm | Tách camera, model, polygon/smoothing, human review và bảng chỉ dẫn | Xác định AI chỉ can thiệp ở bước nhận diện xe |
| Problem Statement | Làm rõ baseline chưa đo, success metric và phạm vi 20–30 ô | Không trình bày target như kết quả đã đạt |
| Rule/Workflow/Agent | Lập luận chọn Workflow, không chọn Agent | Có đường đi cố định, ngoại lệ rõ, không cần AI tự lập kế hoạch |
| Decision | Đề xuất Go có điều kiện, shadow mode, quality gate và rollback | Nhóm chưa Go production khi chưa có dữ liệu thực địa |

## Bảng dùng AI

| Phase | Tôi dùng AI làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm góc nhìn quanh bãi xe | Mở rộng từ người lái sang vận hành và quản lý | Một số “dấu hiệu thật” ban đầu chỉ là dữ liệu nên thu, chưa phải bằng chứng | Tôi ghi rõ trạng thái giả định và không gắn số liệu chưa đo |
| Problem Card | Phản biện actor, bottleneck và metric | Chỉ ra cần đo lỗi báo trống giả riêng | AI dễ tập trung vào accuracy mô hình thay vì outcome người lái | Tôi thêm median/P90 thời gian cổng–đến–ô và độ trễ |
| Workflow | Chuyển mô tả thành Mermaid | Làm rõ handoff giữa AI, rule và operator | AI có thể giả định camera luôn hoạt động và nhìn rõ | Tôi thêm health check, trạng thái `không chắc chắn` và fallback |
| Research | Tìm pattern, tool và dataset | Cho thấy giải pháp tương tự đã tồn tại | Kết quả benchmark ngoài bãi mục tiêu không thể dùng làm kết quả của nhóm | Tôi chỉ dùng nguồn để chứng minh tính khả thi sơ bộ và yêu cầu local test |
| Problem Statement | Kiểm tra metric và boundary | Giúp tách pilot khỏi production | AI không thể xác nhận pain hay baseline thay người dùng | Tôi ghi “chưa đo” và đưa việc thu baseline vào pilot |
| Rule/Workflow/Agent | So sánh các mức | Chỉ ra Agent không cần thiết | Dễ thiên về camera vì đó là ý tưởng ban đầu | Tôi giữ signage, bộ đếm và sensor làm phương án thay thế |
| Decision | Gợi ý quality gate và rollback | Biến “Go” thành quyết định có điều kiện | Các ngưỡng ban đầu vẫn là target, chưa được kiểm nghiệm | Tôi chọn shadow mode và chỉ mở rộng sau khi đạt gate |

## Reflection

Trước buổi phân tích, tôi nghĩ trọng tâm của đề tài là xây mô hình camera có thể phát hiện chỗ đỗ xe trống. Khi đặt ý tưởng vào cấu trúc problem–workflow, tôi nhận ra camera chỉ là một phương án; vấn đề thật là người lái không nhận được trạng thái chỗ đỗ đúng lúc và phải tìm kiếm tuần tự. Việc nghe và gom các candidates giúp tôi thấy bài cập nhật biển, bảo vệ trả lời câu hỏi và khó tìm lại xe khi quên khu vực đỗ có liên quan, nhưng không nên gộp tất cả vào scope đầu tiên. Riêng bài tìm lại xe còn cần xác thực quyền truy vấn và phải so sánh với cách đơn giản hơn như quét QR để lưu vị trí.

Nhóm có xu hướng solution-first khi bắt đầu bằng “dùng camera và AI”. Challenge quan trọng nhất là liệu bộ đếm cổng, biển theo khu hoặc cảm biến đã giải được phần lớn pain với ít rủi ro hơn chưa. Vì vậy, tôi giữ các phương án đó làm baseline và thu hẹp camera pilot còn 20–30 ô, một góc máy, ban ngày. Tôi cũng đổi cách đánh giá từ accuracy chung sang cả median/P90 thời gian tìm, độ trễ và tỷ lệ không báo trống sai.

Đóng góp rõ nhất của tôi là tách workflow thành model nhận diện xe, rule ánh xạ polygon và ổn định trạng thái, operator kiểm tra ngoại lệ, rồi mới hiển thị. AI giúp mở rộng góc nhìn, phản biện metric và vẽ workflow, nhưng không biết baseline hay điều kiện thật của bãi xe. Tôi sửa bằng cách ghi rõ giả định, không bịa interview và đặt shadow mode trước khi tác động tới người lái. Nếu làm lại, tôi sẽ quan sát 30 hành trình và kiểm tra góc camera sớm hơn, vì hai dữ liệu này có thể khiến nhóm chọn Rule thay cho AI.

## Kiểm tra hiểu bài

1. **Problem của ai và nghẽn ở đâu?** Người lái không quen bãi; trạng thái ô chỉ được khám phá khi đến gần nên phải dò từng dãy.
2. **Baseline và target?** Baseline thời gian/accuracy chưa đo. Target pilot là median thời gian giảm ≥30%, P90 không tăng, accuracy ≥95%, không báo trống sai ≥98% và 95% cập nhật ≤10 giây.
3. **Vì sao cần metric báo trống giả?** Một lần chỉ sai “còn trống” có thể làm người lái đi tới ô không dùng được và mất niềm tin, dù accuracy tổng thể vẫn cao.
4. **Boundary?** Pilot 20–30 ô, một camera, ban ngày; không nhận diện khuôn mặt/biển số, xử phạt, đặt chỗ, thanh toán hoặc điều khiển barrier.
5. **Vì sao chọn Workflow?** Có nhiều bước cố định kết hợp model, rule và human review; không cần Agent tự lập kế hoạch hay quyết định bước tiếp theo.
6. **Khi nào rollback?** Khi dữ liệu cũ quá 30 giây, feed lỗi liên tiếp hoặc metric báo trống đúng dưới gate; hệ thống ẩn chỉ dẫn và quay về biển/bảo vệ thủ công.

## Checklist

- [x] Có vai trò và đóng góp cá nhân trong từng phase.
- [x] Có điểm AI hữu ích và điểm AI không thể xác nhận.
- [x] Có thay đổi cụ thể sau challenge: thêm baseline non-AI, boundary và trạng thái `không chắc chắn`.
- [x] Có bài học và điều sẽ làm khác nếu thực hiện lại.
- [x] Giải thích được problem → workflow → metric → boundary → Workflow → Go có điều kiện.
