# 📖 Hướng Dẫn Setup Profile GitHub

## ✅ Checklist - Những gì cần làm

### 1. 📁 Upload Ảnh

Bạn cần upload các ảnh theo đúng đường dẫn:

#### Ảnh Profile Chính

```
tuongnguyen913/
└── assets/
    └── anh_3.jpg  ← Upload ảnh suit đen ở đây
```

#### Ảnh Gallery

```
tuongnguyen913/
└── image/
    └── README/
        ├── anh_1.jpg  ← Ảnh cá nhân 1
        ├── anh_2.jpg  ← Ảnh cá nhân 2
        ├── anh_3.jpg  ← Ảnh cá nhân 3
        ├── anh_4.jpg  ← Ảnh cá nhân 4
        ├── cc1.jpg    ← Chứng chỉ 1
        ├── cc2.jpg    ← Chứng chỉ 2
        ├── cc3.jpg    ← Chứng chỉ 3
        ├── cc4.jpg    ← Chứng chỉ 4
        └── cc5.jpg    ← Chứng chỉ 5
```

### 2. ✏️ Cập nhật thông tin cá nhân

Mở file `README.md` và tìm section này để chỉnh sửa:

```typescript
const profile = {
  fullName: "Nguyen Minh Tuong",    // Tên đầy đủ
  englishName: "Ryan Wilson",        // Tên tiếng Anh
  role: "Software Engineer",         // Vị trí
  company: "VPSTech Co. LTD",       // Công ty
  location: "Phú Thọ, Vietnam",     // Địa điểm
  focus: "Government Digital Solutions",
  experience: "3+ years",
  motto: "Building value through stability and logic"
};
```

### 3. 🔗 Cập nhật Links

Tìm section "Connect With Me" và thay đổi links:

```markdown
[![LinkedIn](...))](https://www.linkedin.com/in/nguyen-minh-tuong)   ← Thay link LinkedIn
[![Gmail](...))](mailto:devnguyen1910@gmail.com)                      ← Thay email
[![HackerRank](...))](https://www.hackerrank.com/devnguyen1910)      ← Thay link HackerRank
```

### 4. 📊 Thay GitHub Username

Tìm tất cả `tuongnguyen913` và thay bằng username GitHub của bạn:

- GitHub Stats
- GitHub Streak
- Activity Graph
- Profile Views

Ví dụ:

```markdown
https://github-readme-stats.vercel.app/api?username=tuongnguyen913
                                                     ↓
https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME
```

---

## 🎨 Tùy Chỉnh Nâng Cao

### Thay đổi màu theme

Các theme có sẵn: `tokyonight`, `radical`, `dark`, `cobalt`, `onedark`, `synthwave`, `dracula`

```markdown
&theme=tokyonight  →  &theme=radical
```

### Thêm/Xóa Projects

Để thêm project mới, copy template này:

```markdown
<details>
<summary><h3>🎯 Tên Project</h3></summary>

> **Mô tả ngắn** — Chi tiết project

**Key Features:**
- ✨ Feature 1
- ✨ Feature 2
- ✨ Feature 3

**Status:** ✅ Production / 🚧 In Progress / 📝 Planning

</details>
```

### Thêm/Xóa Tech Stack

Tìm badges tại: https://shields.io/

Format:

```markdown
![Tên](https://img.shields.io/badge/Tên-MàuHex?style=flat-square&logo=tên-logo&logoColor=white)
```

---

## 🚀 Deploy lên GitHub

### Cách 1: Qua VS Code / Cursor

```bash
# 1. Add tất cả file
git add .

# 2. Commit
git commit -m "Update professional GitHub profile"

# 3. Push
git push origin main
```

### Cách 2: Qua GitHub Desktop

1. Open GitHub Desktop
2. Chọn repo `tuongnguyen913`
3. Review changes
4. Commit to main
5. Push origin

---

## 🔍 Kiểm Tra

Sau khi push, truy cập:

```
https://github.com/tuongnguyen913
```

Profile sẽ hiển thị file README.md từ repo `tuongnguyen913`.

---

## ❓ Troubleshooting

### Ảnh không hiển thị?

**Nguyên nhân:**

- File chưa được upload
- Tên file không đúng (phân biệt hoa/thường)
- Đường dẫn sai

**Giải pháp:**

1. Kiểm tra file tồn tại
2. Đảm bảo tên file đúng: `anh_3.jpg` (không phải `Anh_3.jpg` hay `anh-3.jpg`)
3. Đảm bảo đường dẫn: `./assets/anh_3.jpg` (không phải `/assets` hay `assets`)

### Stats không cập nhật?

**Giải pháp:**

- Đợi 5-10 phút
- Xóa cache browser (Ctrl + Shift + R)
- Kiểm tra username đúng chưa

### Layout bị vỡ?

**Giải pháp:**

- Kiểm tra đóng tag `</table>`, `</div>`, `</details>`
- Validate Markdown tại: https://validator.w3.org/

---

## 💡 Tips & Best Practices

### 1. Tối ưu hình ảnh

- Nén ảnh < 500KB: https://tinypng.com/
- Kích thước khuyến nghị:
  - Profile ảnh: 800x800px
  - Gallery: 1200x800px
  - Certificate: 1920x1080px

### 2. Update thường xuyên

- Cập nhật khi có project mới
- Thêm achievements mới
- Refresh stats định kỳ

### 3. Mobile friendly

- Test trên mobile browser
- Đảm bảo responsive

### 4. Cache busting

Nếu ảnh không cập nhật, thêm version:

```markdown
![Image](./assets/anh_3.jpg?v=2)
```

---

## 🎯 Roadmap Phát Triển

### Short-term (1-2 tuần)

- [ ] Upload tất cả ảnh
- [ ] Cập nhật thông tin cá nhân
- [ ] Test trên GitHub
- [ ] Chia sẻ với team

### Mid-term (1-3 tháng)

- [ ] Thêm blog posts
- [ ] Thêm project demos
- [ ] Viết case studies
- [ ] Kết nối WakaTime stats

### Long-term (3-6 tháng)

- [ ] Tạo personal website
- [ ] Video demos
- [ ] Technical writing
- [ ] Community contributions

---

## 📚 Tài Nguyên Bổ Sung

- **Shields.io**: https://shields.io/
- **GitHub Stats**: https://github.com/anuraghazra/github-readme-stats
- **Profile Generator**: https://rahuldkjain.github.io/gh-profile-readme-generator/
- **Awesome Profiles**: https://github.com/abhisheknaiidu/awesome-github-profile-readme

---

**Chúc bạn có một GitHub Profile chuyên nghiệp và ấn tượng! 🚀**
