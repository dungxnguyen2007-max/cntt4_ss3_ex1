# Kết quả trích xuất dữ liệu 20 ứng viên

**Nguồn:** `20_raw_emails_input.docx`\
**Quy tắc chuẩn hóa:** Họ tên viết hoa chữ cái đầu mỗi từ; số điện thoại
Việt Nam chuyển sang `+84` và bỏ số `0` đầu; email chuyển chữ thường; kỹ
năng loại bỏ trùng lặp; thông tin không được nêu rõ trả về `null`.

> Lưu ý: Email 3 ghi rõ chưa có kinh nghiệm làm việc chính thức; 1 năm
> được nêu là thời gian thực hiện đồ án, vì vậy `experience_years` được
> ghi là `0`. Email 20 ghi khoảng 3 năm, được chuẩn hóa thành `3`. Email
> 5 có ký tự Unicode trong địa chỉ email; giữ nguyên nội dung nguồn sau
> khi chuyển chữ thường, không tự sửa địa chỉ.

## 20 bản ghi ứng viên

### Email 1

``` json
{
  "name": "Nguyễn Văn An",
  "phone": "+84912345678",
  "email": "nguyen.van.a@gmail.com",
  "position": "Backend Developer",
  "experience_years": 3,
  "skills": ["Python", "Django", "PostgreSQL"]
}
```

### Email 2

``` json
{
  "name": "Trần Thị Bình",
  "phone": "+84988776655",
  "email": "tranthib@yahoo.com",
  "position": "Frontend Engineer",
  "experience_years": 2,
  "skills": ["ReactJS", "TypeScript", "TailwindCSS"]
}
```

### Email 3

``` json
{
  "name": "Lê Vũ",
  "phone": "+84355123456",
  "email": "levu.dev@gmail.com",
  "position": "Junior Python Developer",
  "experience_years": 0,
  "skills": ["FastAPI", "MySQL", "Docker", "Git"]
}
```

### Email 4

``` json
{
  "name": "Hoàng Văn Nam",
  "phone": "+84903112233",
  "email": "hoangnam95@outlook.com",
  "position": "Data Analyst",
  "experience_years": 4,
  "skills": ["SQL", "Python", "PowerBI", "Excel"]
}
```

### Email 5

``` json
{
  "name": "Phạm Thị Dung",
  "phone": "+84978112233",
  "email": "pham.thị.dung@gmail.com",
  "position": "Kiểm thử phần mềm (QA Engineer)",
  "experience_years": 2,
  "skills": ["Selenium", "Appium", "Java", "Postman"]
}
```

### Email 6

``` json
{
  "name": "Nguyễn Hoàng Long",
  "phone": "+84911222333",
  "email": "alex.nguyen99@gmail.com",
  "position": "DevOps Engineer",
  "experience_years": 3.5,
  "skills": ["AWS", "Docker", "Kubernetes", "Terraform"]
}
```

### Email 7

``` json
{
  "name": "Bùi Đức Hoàng",
  "phone": "+84933445566",
  "email": "buihoang.ptit@gmail.com",
  "position": "Fullstack Developer",
  "experience_years": 5,
  "skills": ["Node.js", "React", "MongoDB", "Docker"]
}
```

### Email 8

``` json
{
  "name": "Võ Minh Thư",
  "phone": null,
  "email": "vo.minh.thu@gmail.com",
  "position": "UI/UX Designer",
  "experience_years": 2,
  "skills": ["Figma", "Adobe XD", "Illustrator"]
}
```

### Email 9

``` json
{
  "name": "Đỗ Anh Tuấn",
  "phone": "+84909888777",
  "email": "tuan.architect@gmail.com",
  "position": "Solutions Architect",
  "experience_years": 7,
  "skills": ["System Design", "Microservices", "Java", "Kubernetes", "Kafka"]
}
```

### Email 10

``` json
{
  "name": "Ngô Thanh Hướng",
  "phone": "+84966554433",
  "email": "ngo.thanh.huong@gmail.com",
  "position": "Business Analyst",
  "experience_years": 3,
  "skills": ["SQL", "Agile", "JIRA", "Wireframing", "Excel"]
}
```

### Email 11

``` json
{
  "name": "Nguyễn Mai Phương",
  "phone": "+84347890123",
  "email": "phuong.intern@gmail.com",
  "position": "AI Research Intern",
  "experience_years": null,
  "skills": ["Python", "PyTorch", "Pandas", "NLP"]
}
```

### Email 12

``` json
{
  "name": "Cao Đức Mạnh",
  "phone": "+84912998877",
  "email": "cao.duc.manh@gmail.com",
  "position": null,
  "experience_years": 6,
  "skills": ["C#", ".NET Core", "SQL Server", "Azure"]
}
```

### Email 13

``` json
{
  "name": "Hà Thục Quyên",
  "phone": "+84981234567",
  "email": "ha.thuc.quyen@gmail.com",
  "position": "HR Executive",
  "experience_years": 2.5,
  "skills": ["Tuyển dụng IT", "Employer Branding", "LinkedIn Recruiter", "HRIS"]
}
```

### Email 14

``` json
{
  "name": "Vũ Hải Đăng",
  "phone": "+84905123123",
  "email": "vu.hai.dang@gmail.com",
  "position": "Mobile Developer (Flutter / React Native)",
  "experience_years": 3,
  "skills": ["Flutter", "Dart", "React Native", "RESTful API", "Firebase"]
}
```

### Email 15

``` json
{
  "name": "Bùi Thị Lan",
  "phone": "+84938765432",
  "email": "bui.thi.lan@gmail.com",
  "position": "Kế toán tổng hợp",
  "experience_years": 8,
  "skills": ["MISA", "Excel nâng cao", "Báo cáo thuế", "Kiểm toán"]
}
```

### Email 16

``` json
{
  "name": "Lê Quang Vinh",
  "phone": "+84977889900",
  "email": null,
  "position": "Security Engineer",
  "experience_years": 4,
  "skills": ["Penetration Testing", "OWASP Top 10", "Wireshark", "Linux Security"]
}
```

### Email 17

``` json
{
  "name": "Hoàng Ngọc Yến",
  "phone": "+84366778899",
  "email": "hoang.yen.design@gmail.com",
  "position": "UI/UX Designer",
  "experience_years": 2,
  "skills": ["Figma", "Photoshop", "After Effects", "User Research"]
}
```

### Email 18

``` json
{
  "name": "Trần Gia Huy",
  "phone": "+84903334455",
  "email": "tran.gia.huy.lead@gmail.com",
  "position": "Engineering Manager / Tech Lead",
  "experience_years": 10,
  "skills": ["Team Management", "Agile/Scrum", "System Architecture", "Python", "Go", "Kubernetes"]
}
```

### Email 19

``` json
{
  "name": "Mai Thị Chi",
  "phone": "+84399112233",
  "email": "mai.chi.content@gmail.com",
  "position": "Content Creator",
  "experience_years": null,
  "skills": ["Viết bài SEO", "Canva", "Quản lý Fanpage"]
}
```

### Email 20

``` json
{
  "name": "Phạm Hoàng Quân",
  "phone": "+84922334455",
  "email": "pham.hoang.quan@gmail.com",
  "position": "Golang Developer",
  "experience_years": 3,
  "skills": ["Go", "Microservices", "gRPC", "Redis", "MySQL"]
}
```

## Ghi chú dữ liệu cần kiểm tra

  --------------------------------------------------------------------------
  Email             Trường               Giá trị xử lý     Lý do
  ----------------- -------------------- ----------------- -----------------
  8                 `phone`              `null`            Email không cung
                                                           cấp số điện
                                                           thoại.

  11                `experience_years`   `null`            Chỉ nêu là sinh
                                                           viên năm cuối,
                                                           không nêu số năm
                                                           kinh nghiệm làm
                                                           việc.

  12                `position`           `null`            Không nêu vị trí
                                                           ứng tuyển cụ thể.

  16                `email`              `null`            Email không cung
                                                           cấp địa chỉ
                                                           email.

  19                `experience_years`   `null`            Không nêu số năm
                                                           kinh nghiệm.

  5                 `email`              Giữ nguyên ký tự  Không tự ý thay
                                         Unicode           đổi địa chỉ email
                                                           được cung cấp
                                                           trong nguồn.
  --------------------------------------------------------------------------
