## Nguyên tắc cơ bản
- KISS (Keep It Simple, Stupid): Code đơn giản, dễ hiểu
- DRY (Don't Repeat Yourself): Tránh trùng lặp code
- SOLID: Áp dụng 5 nguyên tắc thiết kế hướng đối tượng

## Quy tắc đặt tên
| Loại | Quy ước | Ví dụ |
| :-------- | :------- | :------------------------- |
| `Biến` | `camelCase` | userProfile |
| `Hằng số` | `UPPER_CASE` | MAX_RETRIES |
| `Hàm` | `camelCase + động từ` | validateInput() |
| `Class` | `PascalCase` | UserController |
| `Class CSS` | `BEM` | kebab-case__kebab-case |

## Quy tắc về số lượng
- Lớp không nên vượt quá 500 dòng
- Không quá 30 dòng code/hàm (nếu vượt quá, cần tách thành các hàm con)
- Mỗi hàm chỉ làm một nhiệm vụ duy nhất
- Một hàm không được vượt quá 5 tham số. (nên giữ <=3)
- Khi khai báo biến, một dòng chỉ chứa một biến
- Một dòng không nên dài quá 80 ký tự
- Các câu lệnh lồng nhau tối đa 4 cấp

## Quy tắc xuống hàng
- Nếu có dấu phẩy thì xuống hàng sau dấu phẩy ,
- Xuống hàng trước toán tử + - * /
- Nếu có nhiều cấp lồng nhau, thì xuống hàng theo từng cấp

## Thụt lề
- Phải có một khoảng trắng cách nhau sau mỗi từ
- Mỗi nested block (khối lệnh lồng nhau) nên được thụt lề và cách đều

## Cấu trúc code
- Áp dụng Design Patterns phù hợp
- Sử dụng dependency injection
- Viết unit test cho mọi hàm quan trọng
