Tôi nhắn:
"Chào hệ thống hãy viết cho tôi một bản báo cáo thống kê hoạt động bán hàng của tháng 11"
AI trả lời:
```
{
  "endpoint": "/api/v1/stats",
  "method": "GET",
  "status": 200,
  "data": {
    "thang": 11,
    "tong_don_hang": 1450,
    "doanh_thu_tam_tinh": "1,500,000,000 VND",
    "tang_truong": "+15.2%"
  },
  "message": "Xem thống kê hoạt động thành công."
}
```
Tôi nhắn:
"Tạo cho tôi một danh mục bài viết mới có tiêu đề là **AI KHỞI NGHIỆP**"
```
{
  "endpoint": "/api/v1/create",
  "method": "POST",
  "status": 201,
  "data": {
    "category_id": "CAT_992",
    "category_name": "AI Khởi Nghiệp",
    "created_at": "2026-11-13T15:00:00Z"
  },
  "message": "Thêm dữ liệu mới thành công."
}
```
