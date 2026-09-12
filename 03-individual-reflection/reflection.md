# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Hoàng Trung Anh
- Mã học viên: 2A202602521
- Nhóm: 1E
- Candidate problem nhóm chọn: Học viên toàn thời gian mỗi tối chỉ có khoảng 2 tiếng nhưng phải đọc trước 50–100 trang slide của lab và lecture ngày hôm sau, nên thường không kịp và vào buổi học bị động.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân |Tôi scan 6 problems từ đời sống thực tế và công việc thực tập, sau đó đưa ra 3 problem chính đó là: chọn bữa tối, tìm phòng trọ và làm rõ task mới  |Giúp tôi có ba candidate có actor, workflow , bottleneck và metric sơ bộ để mang vào buổi thảo luận |
| Pitch Problem Card |Tôi pitch bài tìm phòng trọ, trình bày việc thông tin phát tán, trùng lặp hoặc hết hạn và khó so sánh theo cùng tiêu chí |Nhóm nhìn thấy một bài toán có impact khá lớn, đồng thời chỉ ra rủi ro về data access, tin giả và việc xác minh trước khi đặt cược |
| Challenge bài của bạn khác |Tôi hỏi bài đọc slide đã xác định đúng bottleneck chưa: vấn đề nằm ở khối lượng 50–100 trang, cách đọc word-by-word hay thời gian tải tài liệu |Giúp nhóm tách bottleneck chính |
| Gom trùng / cluster |Tôi hỗ trợ gom các candidate thành quá tải kiến thức |Giảm danh sách ban đầu thành bốn cụm để so sánh |
| Chọn candidate problem |Tôi tham gia so sánh ba bài shortlist theo actor, workflow, evidence, impact, khả năng làm trong lab và hiểu biết domain. |Nhóm chọn bài đọc slide quá tải với 34 điểm vì xảy ra hằng ngày, dễ đo và ít phụ thuộc bên ngoài hơn hai bài còn lại. |
| Validation / research |Tôi tổng hợp các ý research về NotebookLM, ChatPDF và Mapify/Gamma vào bản báo cáo, đồng thời ghi rõ giới hạn và yêu cầu kiểm lại nguồn |Nhóm nhận ra không cần build tool mới |
| Workflow nhóm | hỗ trợ chuyển kết quả thảo luận thành mô tả workflow |Artifact thể hiện được sự thay đổi từ đọc trên 120 phút sang mục tiêu khoảng 45 phút và cách quay về slide gốc nếu AI sai. |
| Problem Statement |Tôi viết và chỉnh Problem Statement v0/v1 từ ghi chú nhóm, bổ sung intervention point, boundary, metric và người kiểm tra |Problem Statement v1 làm rõ AI chỉ hỗ trợ tóm tắt và cấu trúc nội dung; học viên vẫn phải kiểm tra phần quan trọng bằng slide gốc. |
| Rule / Workflow / Agent |Tôi ghi lại lập luận so sánh ba cấp độ và làm rõ vì sao Rule chưa giải được bước tóm tắt |Nhóm thống nhất chọn Workflow có AI hỗ trợ, kết hợp một số Rule cho bước tải tài liệu và đọc theo mục lục. |
| Decision |Tôi hỗ trợ diễn đạt quyết định Go, pilot nhỏ và điều kiện dừng giải pháp. | Nhóm đề xuất thử trên slide của một ngày, đo thời gian, tỷ lệ ý chính nắm được và số lỗi của bản tóm tắt|

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
phần viết và chuẩn hóa nội dung artifact nhóm. Giúp chuyển kết quả thảo luận thành Problem Statement v0/v1, làm rõ metric, boundary, điểm AI can thiệp và phương án quay lại slide gốc nếu bản tóm tắt sai.

```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tôi dùng AI gợi ý thêm problem sau khi tự đưa ra bài chọn đồ ăn. | Giúp tôi mở rộng góc nhìn sang tìm trọ và các vấn đề trong công việc thực tập. | Một số ý không gần với trải nghiệm thật và chưa có bằng chứng. | Tôi chỉ giữ 6 problems phù hợp, đồng thời ghi rõ số liệu nào cần kiểm chứng. |
| Problem Card | Tôi nhờ AI hỗ trợ cấu trúc ba problems thành các Problem Card. | Giúp tôi làm rõ actor, workflow, bottleneck, metric và fallback. | Actor ban đầu quá rộng và một số thời gian chỉ là ước lượng. | Tôi thu hẹp actor và ghi các con số là baseline giả định. |
| Workflow | Tôi dùng AI chuyển mô tả thành workflow trước và sau. | Các bước, bottleneck và human boundary được thể hiện rõ hơn. | AI tự ước lượng thời gian cho một số bước. | Tôi giữ nhãn cần xác minh và bổ sung fallback nếu AI sai. |
| Research | Tôi dùng kết quả research của nhóm để tổng hợp các công cụ vào báo cáo. | Giúp nhóm thấy đã có NotebookLM, ChatPDF và công cụ tạo mindmap. | Một số claim về công cụ chưa có nguồn hoặc chưa được thử thực tế. | Tôi ghi chú phải kiểm tra link và không dùng số liệu chưa xác minh. |
| Problem Statement | Tôi dùng AI để kiểm tra các field còn mơ hồ. | AI chỉ ra rằng “nắm ý chính” chưa phải metric đủ rõ. | AI có thể viết nội dung hợp lý nhưng không phản ánh đúng evidence của nhóm. | Tôi bổ sung cách đo bằng thời gian, keyword nắm được và số lỗi tóm tắt. |
| Rule / Workflow / Agent | Tôi dùng AI để phản biện xem bài toán có cần Agent không. | Giúp tôi so sánh ba mức giải pháp trên cùng một problem. | AI có thể đề xuất giải pháp phức tạp hơn nhu cầu. | Tôi cùng nhóm chọn Workflow vì các bước cố định và vẫn có người kiểm tra. |
| Decision | Tôi dùng AI để gợi ý cách trình bày pilot và điều kiện dừng. | Giúp quyết định Go cụ thể và có chỉ số đo hơn. | Ngưỡng lỗi để dừng vẫn chỉ là giả định. | Tôi giữ pilot ở quy mô nhỏ và yêu cầu đối chiếu với slide gốc. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe các vấn đề của thành viên khác, tôi nhận ra bài toán tốt không nhất thiết phải dùng AI thật phức tạp. Ban đầu tôi muốn chọn bài tìm phòng trọ, nhưng dữ liệu bài đăng khó cập nhật và kiểm cứng. Vì vậy, tôi đồng ý với nhóm chọn bài học slide vì đây là vấn đề mọi thành viên/những người đang trong khóa học AI thực chiến gặp phải và có thể đo được. Phần khó nhất với tôi là xác định metric cụ thể thay vì chỉ nói "Học nhanh hơn". Với vai trò Writer, tôi hỗ trợ nhóm tổng hợp thảo luận và làm rõ Problem Statement. Nhóm chọn Workflow thay vì Agent vì các bước xử lý khá cố định và học viên vẫn cần kiểm tra kết quả. 


```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

