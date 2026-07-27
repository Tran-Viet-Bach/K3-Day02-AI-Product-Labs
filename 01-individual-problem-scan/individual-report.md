# Phase 1 & 2 — Individual Problem Scan + Top 3 Problem Cards

**Người thực hiện:** Bách

---

# Phase 1 — Individual Scan

## Case 1: Xếp lịch tập nhóm học nhảy

**Nhân vật:** Bách, làm leader trong nhóm học nhảy 6 người. Mỗi đợt, Bách phải xếp một khung giờ tập cố định giữa 6 học viên và cô giáo — trước tiên hỏi ý từng học viên xem giờ nào rảnh, tổng hợp lại, rồi mới nhắn cô giáo để chốt. Nếu cô giáo bận, toàn bộ quy trình phải làm lại từ đầu.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Xếp lịch tập cố định giữa 6 học viên và cô giáo mỗi tuần/mỗi đợt | Leader, 6 học viên, cô giáo | Mất một buổi tối để hỏi hết tất cả học viên, phải hỏi vòng round-robin |
| 2 | Pain từ người khác | Nếu cô giáo bận thì cả quy trình phải hỏi lại từ đầu | Leader, cô giáo, cả nhóm | Xảy ra 1-2 lần/tuần |
| 3 | Lặp lại | Theo dõi ai đã confirm / chưa confirm giờ tập | Leader | Phải nhắn tin thủ công từng người |
| 4 | Pain từ người khác | Đổi giờ tập đột xuất phải báo lại toàn bộ nhóm, dễ sót người | Leader, học viên bị sót | 1-2 bạn không đọc tin nhắn và bị nhầm giờ học |
| 5 | Tốn thời gian | Tổng hợp feedback sau buổi học (ai cần cải thiện gì) | Leader, cô giáo | Không có nơi lưu tập trung, phải nhớ hoặc lục lại tin nhắn |

---

## Case 2: Quản lý tài chính cá nhân

**Nhân vật:** Bách, sinh viên VinUni, tự quản lý toàn bộ tài chính cá nhân hàng tháng, bao gồm chi tiêu sinh hoạt và các khoản đóng học phí theo deadline. Vì không có công cụ theo dõi dòng tiền vào/ra theo thời gian thực, Bách thường không nắm được số dư thực tế tại mỗi thời điểm, dẫn đến hai hệ quả: (1) quên hoặc trễ deadline giao dịch học phí, và (2) hết tiền giữa tháng dù đầu tháng vừa nhận lương/trợ cấp.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng | Dấu hiệu thật |
|---|---|---|---|---|
| 6 | Tốn thời gian / Lặp lại | Không nắm được số dư thực tế, dẫn đến hết tiền giữa tháng | Bách | Hết tiền vào khoảng giữa tháng |
| 7 | AI có thể tốt hơn | Không phân loại được khoản chi nên không biết nên cắt giảm gì để cân đối | Bách | Chi tiêu rải rác nhiều nguồn (tiền mặt, chuyển khoản, ví điện tử), không gộp lại được |
| 8 | Lặp lại / Pain từ người khác | Quên hoặc trễ deadline giao dịch học phí vì không có nhắc nhở gắn với dòng tiền hiện có | Bách, phòng tài chính/học vụ | Từng trễ deadline kỳ trước ở trường, phải liên hệ lại phòng học vụ để xử lý |

---

## Case 3: Lịch trình cá nhân (học 2 trường + thể thao)

**Nhân vật:** Bách, sinh viên năm cuối, đang theo học song song 2 trường đại học nên khối lượng lịch học vốn đã dày đặc, cộng thêm lịch tập thể thao cá nhân. Vì lịch đến từ nhiều nguồn khác nhau (thời khóa biểu trường A, trường B, lịch tập riêng) mà không có nơi tổng hợp chung, Bách thường xuyên bị chồng lịch hoặc quên lịch, phải huỷ gấp hoặc bỏ lỡ.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng | Dấu hiệu thật |
|---|---|---|---|---|
| 9 | Lặp lại | Quên lịch học/tập vì không có nơi tổng hợp tất cả lịch trình | Bách | Thường hay quên lịch buổi tối 1-2 lần/tháng |
| 10 | Tốn thời gian | Mỗi kỳ phải tự đối chiếu thủ công lịch học của 2 trường để tìm khung giờ trống, dễ sót xung đột | Bách | Mất 1 tiếng/lần đối chiếu, làm lại mỗi khi 1 trong 2 trường đổi lịch |

---

## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Xếp lịch tập cố định giữa 6 học viên và cô giáo | Actor đa dạng nhất (Leader, 6 học viên, cô giáo), có dấu hiệu thật rõ (mất cả buổi tối hỏi round-robin, cô giáo bận 1-2 lần/tuần phải làm lại), workflow lặp lại đều mỗi đợt, hội tụ đủ 3 lăng kính trên cùng workflow | "Đủ tốt" đo bằng gì — số lần chốt lịch thành công ngay lần hỏi đầu tiên? Có nên gộp phần theo dõi confirm và báo đổi lịch vào cùng giải pháp hay tách riêng? |
| 2 | Quên/trễ deadline giao dịch học phí do không nắm số dư thực tế | Có hậu quả thật đã xảy ra (từng trễ deadline, phải liên hệ lại phòng học vụ), có actor thứ 2 ngoài bản thân, deadline là mốc rõ ràng dễ gắn với giải pháp nhắc nhở | Dữ liệu dòng tiền rải rác ở nhiều nguồn (tiền mặt, chuyển khoản, ví điện tử) — nếu không gộp được thì khó cảnh báo kịp deadline |
| 3 | Đối chiếu thủ công lịch học 2 trường để tìm khung giờ trống | Đặc trưng riêng, ít người gặp (differentiation cao vì học song song 2 trường), có con số cụ thể (1 tiếng/lần, làm lại mỗi khi 1 trường đổi lịch) | Tần suất đổi lịch của mỗi trường là bao nhiêu — nếu hiếm khi đổi thì giá trị tự động hoá thấp hơn dự kiến |

---

# Phase 2 — Top 3 Problem Cards + Draft Workflow

## Problem Card #1 — Xếp lịch tập nhóm học nhảy

**Problem 1 câu:**
Mỗi đợt học, Bách (leader) mất một buổi tối hỏi vòng round-robin 6 học viên để tìm khung giờ rảnh chung, rồi mới chốt với cô giáo — và nếu cô giáo bận, toàn bộ quy trình phải làm lại từ đầu.

**Actor:**
Leader (Bách), 6 học viên trong nhóm, cô giáo dạy.

**Thời điểm / bối cảnh:**
Đầu mỗi đợt học mới, hoặc khi cần đổi lịch tập giữa đợt.

**Current workflow:**

```text
1. Nhắn hỏi từng học viên xem giờ nào rảnh (round-robin)
2. Chờ phản hồi, tổng hợp thủ công
3. Nhắn cô giáo đề xuất khung giờ đã tổng hợp
4. Nếu cô giáo bận → quay lại bước 1, hỏi lại từ đầu
5. Chốt giờ, thông báo lại cho cả nhóm
```

**Bottleneck:**
Bước 1-2 — hỏi vòng 6 học viên và chờ tổng hợp mất cả một buổi tối; nếu cô giáo bận (bước 4) thì toàn bộ công sức bị đổ lại.

**Impact:**
1 buổi tối/lần cho leader, xảy ra 1-2 lần/tuần khi phải làm lại vì cô giáo bận. Ngoài ra leader còn tốn thêm công theo dõi confirm và báo lại khi đổi giờ đột xuất (1-2 bạn hay bị sót, nhầm giờ học).

**Success metric:**
Giảm thời gian chốt lịch từ 1 buổi tối xuống dưới 15-20 phút, giảm số lần phải hỏi lại vì trùng lịch cô giáo.

**Non-AI alternative:**
Dùng form khảo sát giờ rảnh (Google Form/Poll) để thay hỏi tay từng người — giảm thời gian tổng hợp nhưng chưa giải quyết được việc khớp với lịch cô giáo.

**AI hypothesis:**
AI thu thập giờ rảnh của 6 học viên + lịch cô giáo, tự động đề xuất khung giờ khớp nhất, giảm số vòng hỏi lại.

**Quick gut:**
Workflow

### Draft current workflow

```text
CURRENT STATE — ~1 buổi tối (~120')

[1 Hỏi round-robin 6 học viên: 60']
→ [2 Chờ + tổng hợp thủ công: 30']
→ [3 Nhắn đề xuất cho cô giáo: 10']
→ [4 Nếu cô giáo bận → quay lại bước 1]  <-- bottleneck
→ [5 Chốt + báo lại cả nhóm: 20']
```

### Draft future workflow

```text
FUTURE STATE — ~20 phút

[1 Gửi form/poll giờ rảnh tự động: 2']
→ [2 AI tổng hợp giờ rảnh chung: 1']
→ [3 AI đối chiếu với lịch cô giáo, đề xuất khung giờ: 2']
→ [4 Leader review + xác nhận: 10']  <-- human boundary
→ [5 Tự động thông báo cho cả nhóm: 5']

Fallback: Không tìm được khung giờ khớp → leader tự thương lượng thủ công.
```

---

## Problem Card #2 — Quên/trễ deadline giao dịch học phí

**Problem 1 câu:**
Vì không theo dõi số dư thực tế theo thời gian thực, Bách từng quên/trễ deadline đóng học phí và phải liên hệ lại phòng học vụ để xử lý.

**Actor:**
Bách (sinh viên tự quản lý tài chính), phòng tài chính/học vụ.

**Thời điểm / bối cảnh:**
Đầu mỗi kỳ học, vào các mốc deadline đóng học phí.

**Current workflow:**

```text
1. Nhận thông báo deadline học phí (email/hệ thống trường)
2. Không kiểm tra số dư ví/tài khoản thường xuyên
3. Chi tiêu sinh hoạt hằng ngày không phân loại theo mục đích
4. Đến gần/qua deadline mới nhận ra thiếu tiền hoặc quên hẳn
5. Liên hệ phòng học vụ xin gia hạn / xử lý trễ hạn
```

**Bottleneck:**
Bước 2-3 — không có cơ chế theo dõi dòng tiền vào/ra real-time và không phân loại khoản chi, nên không biết trước liệu đủ tiền đóng học phí đúng hạn hay không.

**Impact:**
Từng trễ deadline ở kỳ trước, phải tốn thời gian liên hệ lại phòng học vụ để xử lý — có rủi ro về phí phạt hoặc ảnh hưởng đến quyền lợi học tập nếu lặp lại.

**Success metric:**
0 lần trễ deadline học phí trong kỳ tới; nhận cảnh báo số dư trước deadline ít nhất 3-5 ngày.

**Non-AI alternative:**
Đặt lịch nhắc (calendar reminder) thủ công trước mỗi deadline — giúp nhớ ngày nhưng không giải quyết việc không biết có đủ tiền hay không.

**AI hypothesis:**
AI theo dõi dòng tiền vào/ra (nhập tay hoặc kết nối nguồn), tự phân loại khoản chi, và cảnh báo sớm nếu số dư dự kiến không đủ trước deadline học phí.

**Quick gut:**
Workflow

### Draft current workflow

```text
CURRENT STATE — phát hiện trễ, xử lý bị động

[1 Nhận thông báo deadline: 1']
→ [2 Không theo dõi số dư: (không làm)]  <-- bottleneck
→ [3 Chi tiêu không phân loại: liên tục]
→ [4 Phát hiện thiếu tiền/quên gần deadline]
→ [5 Liên hệ phòng học vụ xử lý trễ: ~30'+ thời gian chờ]
```

### Draft future workflow

```text
FUTURE STATE — chủ động cảnh báo sớm

[1 Ghi nhận thu/chi hằng ngày (nhập tay/tự động): 1'/ngày]
→ [2 AI phân loại khoản chi theo danh mục: tự động]
→ [3 AI đối chiếu số dư dự kiến với deadline học phí: tự động]
→ [4 Cảnh báo trước 5 ngày nếu có nguy cơ thiếu: tự động]
→ [5 Bách chủ động xoay tiền/đóng đúng hạn: 10']  <-- human boundary

Fallback: Nếu vẫn thiếu tiền dù có cảnh báo → liên hệ phòng học vụ sớm hơn thay vì sau deadline.
```

---

## Problem Card #3 — Đối chiếu thủ công lịch học 2 trường

**Problem 1 câu:**
Mỗi kỳ, Bách mất khoảng 1 tiếng để tự đối chiếu thủ công lịch học của 2 trường tìm khung giờ trống, và phải làm lại mỗi khi một trong hai trường đổi lịch.

**Actor:**
Bách (sinh viên học song song 2 trường).

**Thời điểm / bối cảnh:**
Đầu mỗi kỳ học, hoặc bất cứ khi nào một trong hai trường thay đổi thời khóa biểu.

**Current workflow:**

```text
1. Lấy thời khóa biểu trường A
2. Lấy thời khóa biểu trường B
3. Lấy lịch tập thể thao cá nhân
4. Tự đối chiếu thủ công (thường bằng mắt/note tay) để tìm khung giờ trống
5. Phát hiện xung đột thì điều chỉnh lịch tập/lịch cá nhân
6. Nếu 1 trong 2 trường đổi lịch -> làm lại từ bước 1
```

**Bottleneck:**
Bước 4 — đối chiếu thủ công 3 nguồn lịch khác nhau, dễ sót xung đột vì không có công cụ tổng hợp chung; và toàn bộ công việc phải lặp lại mỗi khi một trường đổi lịch.

**Impact:**
Mất 1 tiếng/lần đối chiếu, lặp lại nhiều lần trong kỳ mỗi khi có thay đổi lịch — kèm rủi ro sót xung đột dẫn đến quên lịch buổi tối 1-2 lần/tháng.

**Success metric:**
Giảm thời gian đối chiếu từ 1 tiếng xuống dưới 10 phút; phát hiện xung đột ngay khi có thay đổi lịch thay vì phải tự rà lại toàn bộ.

**Non-AI alternative:**
Gộp thủ công cả 3 lịch vào 1 Google Calendar chung,  giảm việc phải mở nhiều nguồn nhưng vẫn cần tự đối chiếu bằng mắt để tìm xung đột.

**AI hypothesis:**
AI tự động đồng bộ 3 nguồn lịch, phát hiện và cảnh báo xung đột ngay khi có thay đổi, gợi ý khung giờ trống phù hợp.

**Quick gut:**
Workflow

### Draft current workflow

```text
CURRENT STATE — 1 tiếng/lần, lặp lại khi có đổi lịch

[1 Lấy TKB trường A: 10']
→ [2 Lấy TKB trường B: 10']
→ [3 Lấy lịch thể thao: 5']
→ [4 Đối chiếu thủ công tìm khung trống: 30']  <-- bottleneck
→ [5 Điều chỉnh lịch cá nhân: 5']
→ [Nếu 1 trường đổi lịch → quay lại bước 1]
```

### Draft future workflow

```text
FUTURE STATE — ~10 phút, tự động khi có thay đổi

[1 Đồng bộ 3 nguồn lịch vào 1 hệ thống: tự động]
→ [2 AI quét và phát hiện xung đột: tự động]
→ [3 Cảnh báo ngay khi có lịch mới/đổi lịch: tự động]
→ [4 Bách review + điều chỉnh: 10']  <-- human boundary

Fallback: Xung đột không có khung giờ thay thế → Bách tự quyết định ưu tiên môn học/buổi tập nào.
```