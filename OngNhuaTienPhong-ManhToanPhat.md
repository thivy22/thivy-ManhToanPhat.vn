# Tạo nội dung file Markdown
markdown_content = """\
# Danh sách sản phẩm ống nhựa PVC Gia Lai

## Nhà phân phối: Mạnh Toàn Phát
- **Địa chỉ:** 298F Phạm Văn Đồng, Tổ 5, P.Thống Nhất, Pleiku, Gia Lai
- **Hotline:** 0989 102 879 - 0932 000 345
- **Website:** [Mạnh Toàn Phát](https://manhtoanphat.vn/sp/ong-nhua-pvc-gia-lai-tp)

## Các nhà phân phối khác:
### 1. Cơ Sở Sản Xuất Ống Nhựa Huy Phát
- **Địa chỉ:** Làng B, Xã Gào, Pleiku, Gia Lai
- **Điện thoại:** 0908 491 177
- **Website:** [Huy Phát](https://www.ongnhuahuyphat.com)

### 2. Doanh Nghiệp Tư Nhân Lộc Liên
- **Địa chỉ:** 823 Hùng Vương, Thành phố Pleiku, Gia Lai
- **Điện thoại:** 0935 733 099
"""

# Lưu nội dung vào file
file_path = "/mnt/data/danh_sach_san_pham.md"
with open(file_path, "w", encoding="utf-8") as file:
    file.write(markdown_content)

# Trả về đường dẫn file
file_path
