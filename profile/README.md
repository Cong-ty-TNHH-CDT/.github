# 📌 Dev Rules & Git Flow

## Code
- Code rõ ràng, dễ đọc, dễ maintain
- Tên biến/hàm có nghĩa, không viết tắt khó hiểu
- 1 hàm = 1 nhiệm vụ
- Tránh hard-code, magic number
- Logic game phức tạp phải comment (vì sao)
- Không commit code lỗi / chưa test

## Game & Asset
- Asset đặt tên rõ ràng, có quy ước
- Không commit asset rác, cache, file build, export
- Kiểm tra asset trước khi merge

## Source Control
❌ Không push thẳng `main`  
❌ Không commit nhiều chức năng trong 1 commit  
❌ Không commit secret, `.env`, key  

✅ Mỗi task = 1 branch  
✅ Mọi merge = Pull Request (có mô tả + cách test)

## Git Flow
- `main` → ổn định, release  
- `develop` → phát triển  
- `feature/*`, `fix/*`, `hotfix/*`

Flow:
