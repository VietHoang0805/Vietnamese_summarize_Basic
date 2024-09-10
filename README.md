# Tóm tắt
Đây là đoạn code cơ bản về tóm tắt tiếng việt. Có thể theo các bước hướng dẫn dưới đây để chạy

# Yêu cầu
Có thể chạy đoạn code dưới đây để cài các thư viện cần để chạy code

```
pip install -r requirements.txt
```
# Sau khi cài các thư viện cần thiện có thể chạy notebook Main.ipynb

# Kiến thức sử dụng

1. Tiền xử lý văn bản: Văn bản đầu vào của chúng ta có thể chứa nhiều ký tự thừa, dấu câu thừa, khoảng trắng thừa, các từ viết tắt, viết hoa, ... 
2. Tách câu trong văn bản, hay nói cách khác đó là tokenize văn bản có thể tìm hiểu thêm về các phương pháp tokenize như Byte-pair encoding, character level, word level,...
3. Chuyển các câu sang dạng vector ( Ở đây sử dụng Pretrain-model Word2vec )
4. Phân cụm: Sử dụng giải thuật K-Means để phân cụm các ý liên quan lại với nhau. Có thể sử dụng những giải pháp mô hình khác cho cái này
5. Chọn đoạn văn bản tóm tắt và tóm tắt