# Creating a markdown file with product details for the "Tưới Sân Vườn" category

product_list_garden = """
# Tưới Sân Vườn - Mạnh Toàn Phát

1. **Thiết Bị Tưới Sân Vườn BACCARA**: [Link](https://manhtoanphat.vn/sp/thiet-bi-tuoi-san-vuon-baccara)
2. **Thiết Bị Tưới Sân Vườn KRAIN**: [Link](https://manhtoanphat.vn/sp/thiet-bi-tuoi-san-vuon-krain)

For more details, visit the [Tưới Sân Vườn page](https://manhtoanphat.vn/sp/tuoi-san-vuon).
"""

# Writing to a .md file
file_path_garden = "/mnt/data/Tuoi_San_Vuon_Products.md"
with open(file_path_garden, "w") as file:
    file.write(product_list_garden)

file_path_garden
