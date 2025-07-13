# Meta-Prompt: Hướng Dẫn Sử Dụng Kiến Trúc Sư Prompt Bậc Thầy

## 📋 Tổng Quan

Meta-prompt này là một công cụ mạnh mẽ để giúp bạn tạo ra các prompt chất lượng cao cho các mô hình AI Gemini. Nó hoạt động như một "Kiến trúc sư Prompt Bậc thầy" - một chuyên gia AI có khả năng phân tích yêu cầu của bạn và tạo ra các prompt được tối ưu hóa.

## 🎯 Mục Đích

* **Tạo prompt chuyên nghiệp**: Giúp bạn tạo ra các prompt có cấu trúc, rõ ràng và hiệu quả
* **Tối ưu hóa cho Gemini**: Được thiết kế đặc biệt cho các mô hình Gemini (2.5 Pro, 2.5 Flash, v.v.)
* **Hướng dẫn chi tiết**: Cung cấp hướng dẫn từng bước và giải thích lý do thiết kế

## 🚀 Cách Sử Dụng

### Bước 1: Truy cập [Google AI Studio](https://aistudio.google.com/prompts/new_chat)

### Bước 2: Sao Chép System Prompt

* Trên giao diện của Google AI Studio, tìm đến biểu tượng System instructions (📋) trên thanh menu. Khi click vào, một ô textbox sẽ bung ra.
* Sao chép toàn bộ nội dung file `system-prompt.md` và dán vào System instructions

### Bước 3: Điền Thông Tin Vào User Prompt Template

_Bạn nên sử dụng một trình soạn thảo văn bản để thực hiện bước này (Ví dụ Notepad hoặc VS Code)_
* Sao chép toàn bộ nội dung file `user-prompt.md`, dán vào trình soạn thảo văn bản
* Điền thông tin vào các phần được đánh dấu `[...]`. Template chỉ mang tính chất gợi ý. Bạn không cần điền đầy đủ toàn bộ thông tin. Tuy nhiên, hãy cung cấp càng nhiều thông tin càng tốt.
* Sau khi điền xong, sao chép và dán vào ô chat của Google AI Studio

### Bước 4: Thiết Lập Tham Số

Trên thanh công cụ bên phải của Google AI Studio, chỉnh các tham số sau:
* **Temperature**: 0.4 (cho độ chính xác cao)

### Bước 5: Chạy và Nhận Kết Quả

AI sẽ:

1. Đặt câu hỏi làm rõ (nếu thông tin chưa đủ chi tiết)
2. Tạo ra prompt theo định dạng Markdown chuẩn
3. Cung cấp giải thích về các lựa chọn thiết kế

## 💡 Mẹo Sử Dụng Hiệu Quả

### 1. Cung Cấp Thông Tin Chi Tiết

- Càng cung cấp nhiều thông tin, prompt được tạo ra sẽ càng chính xác
- Đừng ngại viết dài, AI sẽ tối ưu hóa cho bạn

### 2. Sử Dụng Ví Dụ

- Cung cấp ví dụ về kết quả mong muốn
- Đề cập những điều KHÔNG muốn AI làm

### 3. Xác Định Rõ Đối Tượng

- Mô tả chi tiết về người sẽ sử dụng kết quả
- Điều này giúp AI chọn giọng điệu và phong cách phù hợp

### 4. Thử Nghiệm và Tinh Chỉnh

- Yêu cầu AI cải thiện prompt nếu kết quả chưa đạt yêu cầu

## 🔧 Khắc Phục Sự Cố

### Vấn đề: AI đặt quá nhiều câu hỏi làm rõ

**Giải pháp:** Cung cấp thông tin chi tiết hơn trong lần đầu, đặc biệt về:
- Định dạng đầu ra cụ thể
- Ngữ cảnh và background
- Ví dụ minh họa

### Vấn đề: Prompt được tạo quá dài hoặc quá ngắn

**Giải pháp:** 

- Điều chỉnh yêu cầu về độ phức tạp của tác vụ
- Chỉ định rõ độ dài mong muốn trong phần ràng buộc

### Vấn đề: Kết quả không phù hợp với mô hình cụ thể

**Giải pháp:**

- Chỉ định rõ mô hình Gemini cụ thể (Pro vs Flash)
- Cung cấp thông tin về giới hạn context window nếu cần

## 📚 Tài Liệu Tham Khảo

- [Google AI Studio](https://aistudio.google.com/) **CHÚ Ý:** Data sẽ bị dùng để huấn luyện AI.
- [Gemini API Documentation](https://ai.google.dev/)
- [Prompt Engineering Best Practices](https://ai.google.dev/docs/prompt_best_practices)
- ["Create prompt" trên Google Vertex AI Studio](https://console.cloud.google.com/vertex-ai/studio/multimodal)
- ["Create a prompt" trên Anthropic Console](https://console.anthropic.com/workbench/new)
- ["Playground" trên OpenAI Platform](https://platform.openai.com/playground)

## 🤝 Đóng Góp

Nếu bạn có ý kiến đóng góp hoặc gặp vấn đề khi sử dụng, vui lòng tạo issue hoặc gửi pull request.

---

**Lưu ý:** Meta-prompt này được tối ưu hóa dựa trên các nguyên tắc Prompt Engineering tiên tiến và được thiết kế đặc biệt cho hệ sinh thái Gemini của Google.
