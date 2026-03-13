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

## Thụt lề
- Phải có một khoảng trắng cách nhau sau mỗi từ
- Mỗi nested block (khối lệnh lồng nhau) nên được thụt lề và cách đều

## Độ dài hàm (Function Length)
- Không quá 20 dòng code/hàm (nếu vượt quá, cần tách thành các hàm con)
- Mỗi hàm chỉ làm một nhiệm vụ duy nhất

## Cấu trúc code
- Áp dụng Design Patterns phù hợp
- Sử dụng dependency injection
- Viết unit test cho mọi hàm quan trọng
