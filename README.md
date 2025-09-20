# Facebook Filters Collection 📚

> **Lưu ý:** Facebook đã ngừng hỗ trợ tính năng filter này. Kho lưu trữ này được tạo để lưu giữ các filters đã được thu thập trước đó.

## Giới thiệu

Đây là bộ sưu tập các Facebook filters đã được mã hóa Base64, được sử dụng trước khi Facebook ngừng hỗ trợ tính năng lọc bài viết. Mỗi filter được hiển thị ở cả hai dạng: mã hóa gốc và dữ liệu đã giải mã.

## Danh sách Filters

### 📅 Filters theo Thời gian

#### 1. Creation Time 2024
**Mô tả:** Lọc bài viết được tạo trong năm 2024

**Filter gốc (Base64):**
```
eyJycF9jcmVhdGlvbl90aW1lOjAiOiJ7XCJuYW1lXCI6XCJjcmVhdGlvbl90aW1lXCIsXCJhcmdzXCI6XCJ7XFxcInN0YXJ0X3llYXJcXFwiOlxcXCIyMDI0XFxcIixcXFwic3RhcnRfbW9udGhcXFwiOlxcXCIyMDI0LTFcXFwiLFxcXCJlbmRfeWVhclxcXCI6XFxcIjIwMjRcXFwiLFxcXCJlbmRfbW9udGhcXFwiOlxcXCIyMDI0LTEyXFxcIixcXFwic3RhcnRfZGF5XFxcIjpcXFwiMjAyNC0xLTFcXFwiLFxcXCJlbmRfZGF5XFxcIjpcXFwiMjAyNC0xMi0zMVxcXCJ9XCJ9In0
```

**Dữ liệu đã decode:**
```json
{
  "rp_creation_time:0": "{\"name\":\"creation_time\",\"args\":\"{\\\"start_year\\\":\\\"2024\\\",\\\"start_month\\\":\\\"2024-1\\\",\\\"end_year\\\":\\\"2024\\\",\\\"end_month\\\":\\\"2024-12\\\",\\\"start_day\\\":\\\"2024-1-1\\\",\\\"end_day\\\":\\\"2024-12-31\\\"}\"}"
}
```

**Thông số:**
- Năm bắt đầu: 2024
- Tháng bắt đầu: 2024-1
- Ngày bắt đầu: 2024-1-1
- Năm kết thúc: 2024
- Tháng kết thúc: 2024-12
- Ngày kết thúc: 2024-12-31

---

### 🔄 Filters theo Hoạt động

#### 2. Recent Posts
**Mô tả:** Lọc các bài viết gần đây

**Filter gốc (Base64):**
```
eyJyZWNlbnRfcG9zdHM6MCI6IntcIm5hbWVcIjpcInJlY2VudF9wb3N0c1wiLFwiYXJnc1wiOlwiXCJ9In0%3D
```

**Dữ liệu đã decode:**
```json
{
  "recent_posts:0": "{\"name\":\"recent_posts\",\"args\":\"\"}"
}
```

#### 3. Seen Posts
**Mô tả:** Lọc các bài viết đã xem/tương tác

**Filter gốc (Base64):**
```
eyJzZWVuX3Bvc3RzOjAiOiJ7XCJuYW1lXCI6XCJpbnRlcmFjdGVkX3Bvc3RzXCIsXCJhcmdzXCI6XCJcIn0ifQ%3
```

**Dữ liệu đã decode:**
```json
{
  "seen_posts:0": "{\"name\":\"interacted_posts\",\"args\":\"\"}"
}
```

#### 4. Recent + Seen Posts (Combo)
**Mô tả:** Kết hợp filter bài viết gần đây và đã xem

**Filter gốc (Base64):**
```
eyJzZWVuX3Bvc3RzOjAiOiJ7XCJuYW1lXCI6XCJpbnRlcmFjdGVkX3Bvc3RzXCIsXCJhcmdzXCI6XCJcIn0iLCJyZWNlbnRfcG9zdHM6MCI6IntcIm5hbWVcIjpcInJlY2VudF9wb3N0c1wiLFwiYXJnc1wiOlwiXCJ9In0
```

**Dữ liệu đã decode:**
```json
{
  "seen_posts:0": "{\"name\":\"interacted_posts\",\"args\":\"\"}",
  "recent_posts:0": "{\"name\":\"recent_posts\",\"args\":\"\"}"
}
```

---

### 👤 Filters theo Tác giả

#### 5. Posts from You
**Mô tả:** Lọc bài viết của chính bạn

**Filter gốc (Base64):**
```
eyJycF9hdXRob3I6MCI6IntcIm5hbWVcIjpcImF1dGhvcl9tZVwiLFwiYXJnc1wiOlwiXCJ9In0%
```

**Dữ liệu đã decode:**
```json
{
  "rp_author:0": "{\"name\":\"author_me\",\"args\":\"\"}"
}
```

#### 6. Posts from Friends
**Mô tả:** Lọc bài viết từ bạn bè

**Filter gốc (Base64):**
```
eyJycF9hdXRob3I6MCI6IntcIm5hbWVcIjpcImF1dGhvcl9mcmllbmRzX2ZlZWRcIixcImFyZ3NcIjpcIlwifSJ9
```

**Dữ liệu đã decode:**
```json
{
  "rp_author:0": "{\"name\":\"author_friends_feed\",\"args\":\"\"}"
}
```

#### 7. Group and Page Posts
**Mô tả:** Lọc bài viết từ các nhóm và trang

**Filter gốc (Base64):**
```
eyJycF9hdXRob3I6MCI6IntcIm5hbWVcIjpcIm15X2dyb3Vwc19hbmRfcGFnZXNfcG9zdHNcIixcImFyZ3NcIjpcIlwifSJ9
```

**Dữ liệu đã decode:**
```json
{
  "rp_author:0": "{\"name\":\"my_groups_and_pages_posts\",\"args\":\"\"}"
}
```

#### 8. Public Posts
**Mô tả:** Lọc bài viết công khai

**Filter gốc (Base64):**
```
eyJycF9hdXRob3I6MCI6IntcIm5hbWVcIjpcIm1lcmdlZF9wdWJsaWNfcG9zdHNcIixcImFyZ3NcIjpcIlwifSJ9
```

**Dữ liệu đã decode:**
```json
{
  "rp_author:0": "{\"name\":\"merged_public_posts\",\"args\":\"\"}"
}
```

---

### 📍 Filters theo Vị trí

#### 9. Location Filter
**Mô tả:** Lọc bài viết theo vị trí địa lý

**Filter gốc (Base64):**
```
eyJycF9sb2NhdGlvbjowIjoie1wibmFtZVwiOlwibG9jYXRpb25cIixcImFyZ3NcIjpcIjEwODQ1ODc2OTE4NDQ5NVwifSJ9
```

**Dữ liệu đã decode:**
```json
{
  "rp_location:0": "{\"name\":\"location\",\"args\":\"108458769184495\"}"
}
```

**Thông số:**
- Location ID: 108458769184495

---

## Cách sử dụng (Khi Facebook còn hỗ trợ)

### Cấu trúc URL
```
https://www.facebook.com/search/posts?q=<keyword>&filters=<base64_filter>
```

### Hướng dẫn sử dụng

#### Bước 1: Chuẩn bị keyword
- Thay thế khoảng trắng trong keyword bằng `%20`
- Ví dụ: "hello world" → "hello%20world"

#### Bước 2: Chọn filter
- Copy filter Base64 từ danh sách bên trên
- Paste vào phần `<base64_filter>` trong URL

#### Bước 3: Tạo URL hoàn chỉnh
Ví dụ URL hoàn chỉnh:
```
https://www.facebook.com/search/posts?q=hello%20world&filters=eyJyZWNlbnRfcG9zdHM6MCI6IntcIm5hbWVcIjpcInJlY2VudF9wb3N0c1wiLFwiYXJnc1wiOlwiXCJ9In0%3D
```

#### Bước 4: Truy cập URL
- Đăng nhập Facebook trên trình duyệt
- Paste URL đã tạo vào thanh địa chỉ
- Nhấn Enter để xem kết quả

### Ví dụ thực tế

#### Tìm kiếm "machine learning" với filter Recent Posts:
```
https://www.facebook.com/search/posts?q=machine%20learning&filters=eyJyZWNlbnRfcG9zdHM6MCI6IntcIm5hbWVcIjpcInJlY2VudF9wb3N0c1wiLFwiYXJnc1wiOlwiXCJ9In0%3D
```

#### Tìm kiếm "AI technology" với filter Posts from Friends:
```
https://www.facebook.com/search/posts?q=AI%20technology&filters=eyJycF9hdXRob3I6MCI6IntcIm5hbWVcIjpcImF1dGhvcl9mcmllbmRzX2ZlZWRcIixcImFyZ3NcIjpcIlwifSJ9
```

#### Tìm kiếm "programming tips" với filter Creation Time 2024:
```
https://www.facebook.com/search/posts?q=programming%20tips&filters=eyJycF9jcmVhdGlvbl90aW1lOjAiOiJ7XCJuYW1lXCI6XCJjcmVhdGlvbl90aW1lXCIsXCJhcmdzXCI6XCJ7XFxcInN0YXJ0X3llYXJcXFwiOlxcXCIyMDI0XFxcIixcXFwic3RhcnRfbW9udGhcXFwiOlxcXCIyMDI0LTFcXFwiLFxcXCJlbmRfeWVhclxcXCI6XFxcIjIwMjRcXFwiLFxcXCJlbmRfbW9udGhcXFwiOlxcXCIyMDI0LTEyXFxcIixcXFwic3RhcnRfZGF5XFxcIjpcXFwiMjAyNC0xLTFcXFwiLFxcXCJlbmRfZGF5XFxcIjpcXFwiMjAyNC0xMi0zMVxcXCJ9XCJ9In0
```

## Cấu trúc Filter

Tất cả các filters đều tuân theo cấu trúc JSON sau:

```json
{
  "<filter_type>:<index>": "{\"name\":\"<filter_name>\",\"args\":\"<filter_arguments>\"}"
}
```

### Các loại Filter chính:
- `rp_creation_time`: Lọc theo thời gian tạo
- `recent_posts`: Bài viết gần đây
- `seen_posts`: Bài viết đã xem
- `rp_author`: Lọc theo tác giả
- `rp_location`: Lọc theo vị trí

## Ghi chú

- ⚠️ **Quan trọng:** Các filters này chỉ hoạt động khi Facebook còn hỗ trợ tính năng này.
- 📅 **Cập nhật cuối:** Tháng 9/2025
- 🔧 **Trạng thái:** Deprecated (Không còn được hỗ trợ)

## Đóng góp

Nếu bạn có thêm filters khác, vui lòng tạo pull request hoặc issue để bổ sung vào collection này.

## License

MIT License - Xem file LICENSE để biết thêm chi tiết.

---

*Repository này được tạo để lưu giữ lịch sử các Facebook filters trước khi tính năng bị ngừng hỗ trợ.*
