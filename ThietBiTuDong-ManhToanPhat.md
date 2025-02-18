# Creating a markdown file with product details for the "Thiết Bị Tự Động" category

product_list_auto = """
# Thiết Bị Tự Động - Mạnh Toàn Phát

1. **Bộ Hẹn Giờ Tưới**: [Link](https://manhtoanphat.vn/sp/bo-hen-gio-tuoi)
2. **Van Điện Từ**: [Link](https://manhtoanphat.vn/sp/van-dien-tu)

For more details, visit the [Thiết Bị Tự Động page](https://manhtoanphat.vn/sp/thiet-bi-tu-dong).
"""

# Writing to a .md file
file_path_auto = "/mnt/data/Thiet_Bi_Tu_Dong_Products.md"
with open(file_path_auto, "w") as file:
    file.write(product_list_auto)

file_path_auto
