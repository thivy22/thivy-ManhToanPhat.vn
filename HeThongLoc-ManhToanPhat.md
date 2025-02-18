# Creating a markdown file with product details and links

product_list = """
# Hệ Thống Lọc - Mạnh Toàn Phát

1. **Bộ Lọc Đĩa T**: [Link](https://manhtoanphat.vn/sp/bo-loc-dia-t)
2. **Bộ Lọc Đĩa Y**: [Link](https://manhtoanphat.vn/sp/bo-loc-dia-y)
3. **Châm Phân Venturi**: [Link](https://manhtoanphat.vn/sp/cham-phan-venturi)
4. **Lọc Tưới 114mm**: [Link](https://manhtoanphat.vn/sp/loc-tuoi-114mm)
5. **Lọc Tưới Bán Tự Động**: [Link](https://manhtoanphat.vn/sp/loc-tuoi-ban-tu-dong)
6. **Lọc Tưới Tách Cát**: [Link](https://manhtoanphat.vn/sp/loc-tuoi-tach-cat)

For more details, visit the [Hệ Thống Lọc page](https://manhtoanphat.vn/sp/he-thong-loc).
"""

# Writing to a .md file
file_path = "/mnt/data/He_Thong_Loc_Products.md"
with open(file_path, "w") as file:
    file.write(product_list)

file_path
