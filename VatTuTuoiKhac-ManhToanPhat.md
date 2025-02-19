# Tạo nội dung file Markdown với danh sách sản phẩm
markdown_content = """\
# Danh sách sản phẩm - Vật tư tưới khác

## 1. Van cầu rắc co hai đầu mặt bích 76mm – Automat
- **Giá:** 1.615.000₫
- **[Xem sản phẩm](https://manhtoanphat.vn/sp/van-cau-rac-co-hai-dau-mat-bich-76mm-automat)**

## 2. Van cầu rắc co hai đầu ren phi 60mm – Automat
- **Giá:** 515.000₫
- **[Xem sản phẩm](https://manhtoanphat.vn/sp/van-cau-rac-co-hai-dau-ren-phi-60mm-automat)**

## 3. Van cầu rắc co hai đầu ren phi 76mm – Automat
- **Giá:** 1.415.000₫
- **[Xem sản phẩm](https://manhtoanphat.vn/sp/van-cau-rac-co-hai-dau-ren-phi-76mm-automat)**
"""

# Lưu nội dung vào file Markdown
file_path = "/mnt/data/danh_sach_vat_tu_tuoi_khac.md"
with open(file_path, "w", encoding="utf-8") as file:
    file.write(markdown_content)

# Trả về đường dẫn file
file_path
