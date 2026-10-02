# render-keep-warm

GitHub Actions ping các backend sau mỗi 10 phút để instance free trên Render không bị ngủ:

- `https://txnn-be.onrender.com`
- `https://food-be-4r22.onrender.com`

Thêm backend mới: thêm URL vào `matrix.url` trong `.github/workflows/keep-warm.yml`.

Repo để public để được chạy Actions miễn phí không giới hạn phút. Không chứa code hay secret nào.
