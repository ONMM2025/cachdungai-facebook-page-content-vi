# Biên tập nội dung Fan Page Facebook

> **Một repository, một skill.** Workflow độc lập bằng tiếng Việt cho AI Agent.
>
> **Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)

## Giới thiệu

Soạn bài mới cho Facebook Page từ chủ đề hoặc brief, gồm hook, caption và CTA. Dùng cho nội dung nguyên bản của Page; không chuyển thể một bài blog thành nhiều định dạng.

Mở **SKILL.md** để xem đầu vào, quy trình, đầu ra, giới hạn và prompt mẫu. Gói cài đặt chứa SKILL.md và giấy phép MIT, không kèm script thực thi.

## Tải gói cài đặt

Tải ZIP sẵn dùng: [facebook-page-content-vi.zip](facebook-page-content-vi.zip). ZIP có thư mục gốc tên **facebook-page-content-vi** và chứa **SKILL.md**, phù hợp để tải lên như một skill riêng.

## Cách cài

### Claude.ai

1. Nếu Skills chưa hiện, kiểm tra Settings > Capabilities và bật code execution nếu tài khoản/workspace hỗ trợ.
2. Mở **Customize > Skills**, bấm **+ > Create skill > Upload a skill**.
3. Chọn tệp **facebook-page-content-vi.zip** vừa tải và bật skill sau khi upload.

Khả năng tạo và dùng skill phụ thuộc gói tài khoản, bật code execution và chính sách workspace.

### Claude Code

Chép **SKILL.md** vào **.claude/skills/facebook-page-content-vi/SKILL.md** trong dự án hoặc **~/.claude/skills/facebook-page-content-vi/SKILL.md** để dùng cá nhân. Gọi bằng **/facebook-page-content-vi** hoặc mô tả yêu cầu để Claude tự chọn khi phù hợp.

### ChatGPT

Skills chỉ xuất hiện ở các tài khoản/workspace đủ điều kiện; hiện trang trợ giúp OpenAI nêu Business, Enterprise, Healthcare và Edu, tùy thiết lập workspace.

1. Mở **Plugins > Plugin Directory > Skills**.
2. Chọn **Create > Upload from your computer**.
3. Chọn **facebook-page-content-vi.zip**.

Nếu không có mục Skills, mở **SKILL.md** rồi dán nội dung vào yêu cầu hoặc Project instructions nếu có. Đây là cách dùng thủ công, không phải cài skill tự động.

### Codex

Trong repo dự án, chép **SKILL.md** vào **.agents/skills/facebook-page-content-vi/SKILL.md**, rồi yêu cầu Codex dùng skill này.

## Prompt mẫu

“Viết bài Facebook cho người mới muốn thử tạo video AI nhưng ngại prompt phức tạp. Cho 3 hook, một caption khoảng 120–180 từ, gợi ý ảnh minh họa và CTA về bài hướng dẫn này. Không nói rằng ai cũng tạo được video chuyên nghiệp ngay.”

Gửi thêm mục tiêu, độc giả, tài liệu đầu vào, nền tảng và giới hạn cần giữ để kết quả sát hơn. Kiểm tra dữ kiện và duyệt nội dung trước khi xuất bản.

## Giấy phép

MIT License — xem file **LICENSE** trong repository.

---

**Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)
