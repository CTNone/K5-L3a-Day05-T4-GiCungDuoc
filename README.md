# K5-L3a-Day05-T4-GiCungDuoc

**Track:** T4 — Thương mại điện tử: Trợ lý khiếu nại “hàng không đúng mô tả”

## Giới thiệu

Dự án thiết kế trải nghiệm AI trong ứng dụng Shopee, tại mục **“Trò chuyện với Shopee”**, hỗ trợ người mua khiếu nại sản phẩm không đúng mô tả. Trợ lý xem xét nội dung khiếu nại và thông tin đơn hàng, đối chiếu với mô tả sản phẩm tại thời điểm đặt hàng, đề nghị người mua bổ sung bằng chứng khi cần, rồi đưa ra hướng xử lý phù hợp hoặc chuyển nhân viên xem xét.

Đây là prototype phục vụ bài tập. Dữ liệu minh họa là dữ liệu dựng, không đại diện cho người mua, người bán hay đơn hàng thật.

## Thành viên

- Học viên 1 — Họ tên — Mã học viên
- Học viên 2 — Họ tên — Mã học viên
- Học viên 3 — Họ tên — Mã học viên
- Học viên 4 — Họ tên — Mã học viên

> Cập nhật họ tên và mã học viên của nhóm trước khi nộp.

## Mục tiêu trải nghiệm

- Giúp người mua trình bày vấn đề rõ ràng, dễ dàng cung cấp bằng chứng liên quan.
- So sánh khiếu nại với thông tin sản phẩm tại thời điểm đặt hàng, không chỉ dựa trên mô tả hiện tại.
- Giải thích kết quả và bước tiếp theo bằng ngôn ngữ dễ hiểu, trung lập.
- Đề xuất phương án xử lý phù hợp, chẳng hạn yêu cầu thêm bằng chứng, đề xuất hoàn tiền theo quy trình hoặc chuyển nhân viên hỗ trợ.
- Để nhân viên xem xét khi thông tin chưa đủ, mâu thuẫn hoặc AI không đủ chắc chắn.

## Tài liệu và prototype

- **Spec:** [`spec.md`](spec.md)
- **Prototype:** [`prototype/`](prototype/)
- **Ảnh demo:** [`prototype/images/`](prototype/images/) hoặc [`docs/`](docs/)
- **Link prototype trực tuyến:** Bổ sung nếu có.

## Các ca demo chính

1. **Người bán đúng mô tả:** AI đối chiếu bằng chứng với thông tin sản phẩm tại thời điểm mua, giải thích nhận định và hướng dẫn người mua bước tiếp theo.
2. **Mô tả đã bị sửa:** AI sử dụng bản mô tả được lưu tại thời điểm đặt hàng để đánh giá, thay vì chỉ dựa vào nội dung hiện tại.
3. **AI chưa chắc chắn:** AI nói rõ điểm còn thiếu hoặc mâu thuẫn, đề nghị bổ sung bằng chứng phù hợp hoặc chuyển nhân viên xử lý; không tự kết luận khi chưa đủ căn cứ.

## Nguyên tắc an toàn và quyền riêng tư

- Chỉ sử dụng dữ liệu dựng trong tài liệu và prototype; không đưa dữ liệu cá nhân hoặc đơn hàng thật vào bài nộp.
- Không hiển thị hoặc yêu cầu chia sẻ số điện thoại, địa chỉ giữa người mua và người bán.
- Không coi lời đe dọa, cảm xúc hay nhận định của một bên là bằng chứng về tình trạng sản phẩm.
- Không hứa phạt shop hoặc cam kết kết quả xử lý trước khi có đủ căn cứ.
- Khi thông tin chưa đủ hoặc có mâu thuẫn, nêu rõ giới hạn và chuyển nhân viên xem xét.
- Giải thích các bước xử lý một cách trung lập, tôn trọng cả người mua lẫn người bán.

## Công nghệ

Repository hiện được nhận diện chủ yếu là **HTML**. Cập nhật mục này nếu nhóm bổ sung công nghệ hoặc công cụ prototype khác.

## Cách xem bài

1. Mở [`spec.md`](spec.md) để xem đặc tả.
2. Truy cập thư mục [`prototype/`](prototype/) để xem prototype và các tài nguyên liên quan.
3. Mở ảnh demo trong `prototype/images/` hoặc `docs/` (nếu có).

---

*Bài tập thiết kế trải nghiệm AI — Track T4.*
