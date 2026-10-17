# Bài: Lợi ích của rau sạch

## Phần 1. Phân tích lỗi

1. **Nhảy cấp tiêu đề:** đang đi từ `#` (H1) xuống `###` (H3), bỏ qua H2 nên thứ tự bị lộn xộn. phải đi lần lượt H1, H2, H3.
2. **Ảnh không hiện:** thiếu dấu `!` ở đầu và có khoảng trắng giữa `]` và `(`. nên markdown không nhận ra đây là ảnh.
3. **In đậm sai:** chỉ dùng 1 dấu `*` nên ra chữ in nghiêng. in đậm phải dùng 2 dấu `**`.
4. **Lưu ý bẫy:** mỗi bài chỉ có 1 H1 duy nhất, và sau dấu `#` phải có 1 khoảng trắng.

## Phần 2. Code đã sửa

```markdown
# Lợi ích của rau sạch

## Danh sách các loại rau

- Rau muống
- Cải xanh
- Rau dền

![Logo Dự án](https://greentech.vn/logo.png)

**Rất quan trọng**, *nên ăn rau mỗi ngày*.

> Ăn rau sạch giúp cơ thể khỏe mạnh.

Xem thêm tại [GreenTech](https://greentech.vn)
```