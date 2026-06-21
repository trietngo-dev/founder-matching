# Tổng quan dự án

```json
{
  "sections": [
    {
      "title": "Tên dự án",
      "content": "Dự án xây dựng nền tảng Founder Matching"
    },
    {
      "title": "Mục đích và bối cảnh dự án",
      "content": "Trong các bài giảng (hoặc chương trình) nhằm mục đích giáo dục khởi nghiệp, dự án hướng tới việc cho phép sinh viên thành lập đội ngũ sáng lập (Founding Team) tối ưu, bổ trợ lẫn nhau dựa trên kỹ năng, chuyên môn, mối quan tâm, ý tưởng và mục tiêu sự nghiệp tương lai của họ. Bằng cách áp dụng công nghệ gợi ý bằng AI, dự án nhằm phá vỡ các giới hạn của việc xây dựng đội ngũ dựa trên mối quan hệ cá nhân hoặc trực giác, đồng thời tự động hỗ trợ thành lập các đội ngũ cân bằng, đa chức năng và có năng lực thực thi mạnh mẽ."
    },
    {
      "title": "Thách thức hiện tại",
      "content": "1. Xây dựng đội ngũ dựa trên cảm xúc và sự thân thiết: Do thành lập đội ngũ giữa những người bạn thân với nhau, cấu trúc kỹ năng và chuyên môn dễ bị lệch (ví dụ: thiên lệch về kỹ năng phát triển phần mềm hoặc kiến thức marketing), dẫn đến việc dễ hình thành các đội ngũ có tính khả thi kinh doanh thấp.\n2. Khó khăn trong việc tìm kiếm nhân sự: Chủ sở hữu ý tưởng (Idea Owner) không tìm được các học viên khác có kỹ năng cần thiết (như kỹ sư, nhà thiết kế, nhân viên kinh doanh,...) để hiện thực hóa ý tưởng, trong khi những người có kỹ năng tốt (Talent) lại không gặp được ý tưởng hấp dẫn để phát huy năng lực.\n3. Thiếu nhất quán về mức độ cam kết và mục tiêu: Sinh viên chỉ muốn \"làm qua loa để qua môn học\" và sinh viên \"thực sự muốn khởi nghiệp như một startup\" xếp chung vào một nhóm, dẫn đến việc đội ngũ tan rã do chênh lệch về nhiệt huyết (※ Giả định đây là vấn đề chung do thiếu kiến thức chuyên môn đặc thù. Yêu cầu này ※ Cần xác nhận lại)."
    },
    {
      "title": "Hướng giải quyết",
      "content": "1. Trực quan hóa chi tiết dữ liệu sinh viên: Tập hợp các thông tin về kỹ năng chuyên môn (hard skill), kỹ năng mềm (soft skill), chuyên ngành, sở thích, nhiệt huyết và mục tiêu khởi nghiệp thành một hồ sơ thống nhất trên hệ thống.\n2. Ghép cặp bổ trợ kỹ năng định hướng bởi AI: Tích hợp AI được huấn luyện trên dữ liệu đội ngũ trong quá khứ để đề xuất phân bổ thành viên bù đắp cho các kỹ năng còn thiếu (ví dụ: kết hợp giữa chuyên ngành CNTT và chuyên ngành Kinh doanh/Marketing) (※ Yêu cầu kỹ thuật và ràng buộc kỹ thuật như thuật toán AI/logic phân tích ※ Cần xác nhận lại).\n3. Lọc theo sự đồng bộ về tầm nhìn và mức độ cam kết: Đưa thời gian có thể cống hiến cho dự án và mức độ mục tiêu vào trọng số ghép cặp để ngăn ngừa sự lệch pha về mức độ động lực (※ Quy tắc nghiệp vụ liên quan đến ghép cặp ※ Cần xác nhận lại)."
    },
    {
      "title": "Phạm vi dự án",
      "content": "【Phạm vi áp dụng (In-scope)】\n・Xây dựng chức năng quản lý hồ sơ sinh viên, đăng tải ý tưởng/dự án\n・Phát triển thuật toán ghép cặp bằng AI (※ Chưa cung cấp ràng buộc kỹ thuật về mô hình AI khả dụng và môi trường phát triển nên ※ Cần xác nhận lại)\n・Xây dựng luồng quản lý trực quan hóa quy trình đồng ý ghép cặp và thành lập đội ngũ giữa các sinh viên\n\n【Ngoài phạm vi (Out-of-scope)】\n・Chức năng ghép cặp với các nhà đầu tư (VC) sau khi khởi nghiệp (Chưa định nghĩa)\n・Chức năng hỗ trợ pháp lý như thành lập công ty hoặc đăng ký pháp nhân (Chưa định nghĩa)\n・Liên kết ghép cặp với các trường đại học khác ngoài trường này (Chưa định nghĩa)"
    },
    {
      "title": "Các bên liên quan chính",
      "content": "・Người dùng hệ thống (Sinh viên): Chủ sở hữu ý tưởng (Idea Owner) và người sở hữu kỹ năng chuyên môn cụ thể (Talent)\n・Tổ chức giáo dục (Trường đại học/Giảng viên): Giảng viên phụ trách môn học khởi nghiệp và người quản lý chương trình đào tạo (※ Do chưa cung cấp biên bản họp về việc liên kết với hệ thống trong trường hay LMS hiện tại nên ※ Cần xác nhận lại)\n・Đơn vị vận hành hệ thống: Văn phòng hỗ trợ khởi nghiệp của trường đại học, v.v. (※ Do chưa cung cấp yêu cầu nghiệp vụ về quy tắc vận hành nên ※ Cần xác nhận lại)\n・Đội ngũ phát triển hệ thống: Các lập trình viên chịu trách nhiệm thiết kế và triển khai hệ thống này"
    },
    {
      "title": "Lịch trình dự kiến",
      "content": "※ Do biên bản họp dự án và thời hạn phát triển cụ thể chưa được cung cấp, lịch trình dưới đây là suy đoán dựa trên giả định phát triển dịch vụ WEB thông thường và xây dựng mô hình AI (※ Cần xác nhận lại).\n・Giai đoạn 1: Xác định yêu cầu và thiết kế cơ bản ghép cặp bằng AI (1 tháng) (※ Cần xác nhận lại)\n・Giai đoạn 2: Phát triển hệ thống (Thiết kế UI/UX, triển khai Front-end/Back-end, xây dựng mô hình AI) (3 tháng) (※ Cần xác nhận lại)\n・Giai đoạn 3: Tích hợp, kiểm thử hệ thống và vận hành thử nghiệm trong lớp học thí điểm (1.5 tháng) (※ Cần xác nhận lại)\n・Phát hành và vận hành chính thức: Sớm nhất khoảng 5-6 tháng từ khi bắt đầu dự án (※ Cần xác nhận lại)"
    }
  ]
}
```