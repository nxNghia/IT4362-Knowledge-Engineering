# Hệ thống gợi ý phim (Movie Recommendation System)

## Project môn học Kỹ nghệ Tri thức (Knowledge Engineering - IT4362)

### Group 17
- Nguyen Viet Huy - 20184120
- Nguyen Xuan Nghia - 20184166
- Tran Quoc Du - 20184070
- Hoang Ngoc Bao - 20184046

[Link dữ liệu](https://drive.google.com/drive/folders/1_1u4bi-3iRlOTJjHq8tphR3UeddWFgcY?usp=sharing)

### Dữ liệu bao gồm 2 file:
- movies_metadata.csv: chứa thông tin về bộ phim như diễn viên, thể loại, đạo diễn, v..v.. của 45,000 bộ phim.
- links_small.csv: chứa thông tin về ID của 9000 bộ phim trên trang IMDB và TMDB.

## Sử dụng
### Upload dữ liệu lên Google Colab
- Copy bộ dữ liệu về drive cá nhân
- Chạy chương trình cho đến hết câu lệnh drive.mount("/content/drive") để tiến hành kết nối với Google Drive
- Copy path của 2 file dữ liệu vào chương trình để pandas đọc dữ liệu.