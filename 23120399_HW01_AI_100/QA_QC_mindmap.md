QA/QC trong phát triển phần mềm
│
├── QA – Quality Assurance
│   ├── Định hướng quy trình
│   ├── Xây dựng và cải tiến quy trình chất lượng
│   ├── Xác định tiêu chuẩn và quy tắc làm việc
│   ├── Phòng ngừa defect từ sớm
│   ├── Đánh giá mức độ tuân thủ quy trình
│   └── Phân tích nguyên nhân gốc rễ
│
├── QC – Quality Control
│   ├── Định hướng sản phẩm
│   ├── Kiểm tra sản phẩm có đáp ứng yêu cầu không
│   ├── Phát hiện và báo cáo defect
│   ├── Xác nhận defect đã được sửa
│   ├── Đánh giá rủi ro và mức độ bao phủ
│   └── Cung cấp thông tin chất lượng cho stakeholder
│
├── Hai vai trò chính trong kiểm thử
│   ├── Test Management Role
│   │   └── Test Manager / Test Lead
│   │       ├── Lập kế hoạch kiểm thử
│   │       ├── Xác định chiến lược và phạm vi test
│   │       ├── Ước lượng nguồn lực và thời gian
│   │       ├── Theo dõi tiến độ và rủi ro
│   │       ├── Báo cáo trạng thái kiểm thử
│   │       ├── Đánh giá tiêu chí hoàn thành test
│   │       ├── Quyết định và thực hiện test completion
│   │       └── Điều phối nhóm kiểm thử
│   │
│   └── Testing Role
│       ├── Tester / Test Analyst
│       │   ├── Phân tích test basis
│       │   ├── Xác định test condition
│       │   ├── Thiết kế test case và test data
│       │   ├── Chuẩn bị test environment
│       │   ├── Thực thi test
│       │   ├── Ghi nhận và báo cáo defect
│       └── └── Phân tích kết quả và cung cấp dữ liệu cho test case
│   Các bên liên quan / phối hợp với hoạt động kiểm thử
    ├──Developer – vai trò phối hợp, không phải vai trò chính riêng
│   │    ├── Có thể thực hiện component testing
│   |	 ├── Sửa defect
│   |   ├── Hỗ trợ phân tích nguyên nhân
│   |   └── Phối hợp với tester
|   |
|   ├── Business Analyst / Product Owner
│   	├── Cung cấp và làm rõ yêu cầu
│   	├── Xác định acceptance criteria
│   	├── Hỗ trợ xác nhận expected result
│   	└── Đánh giá mức độ đáp ứng nhu cầu người dùng
│
├── Test Process
│   ├── Test planning
│   ├── Test analysis
│   ├── Test design
│   ├── Test implementation
│   ├── Test execution
│   ├── Test completion
│   └── Test monitoring and control
│
├── Testware
│   ├── Test plan
│   ├── Test case
│   ├── Test data
│   ├── Test procedure
│   ├── Test report
│   └── Defect report
│
└── Công cụ và kỹ năng hỗ trợ
    ├── Test management tool
    ├── Defect tracking tool
    ├── API testing
    ├── Automation testing
    ├── SQL và log analysis
    ├── Risk-based thinking
    └── Communication và teamwork
```

## Nguồn tham khảo

- ISTQB, *Certified Tester Foundation Level Syllabus v4.0.1*: https://istqb.org/wp-content/uploads/2024/11/ISTQB_CTFL_Syllabus_v4.0.1.pdf

## Ghi chú kiểm tra của sinh viên

- Lỗi 1: Tester bị gán trách nhiệm quyết định kết thúc test; đã sửa về Test Management Role.
- Lỗi 2: Developer bị trình bày như một vai trò kiểm thử chính ngang hàng; đã chuyển thành vai trò phối hợp dưới Testing Role.
- Lỗi 3: AI đặt tên ban đầu là QC/ Testing - Quality Control, coi tesing và QC là một; đã sửa lại bằng cách bỏ chữ "testing"
