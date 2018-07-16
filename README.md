# Bài tập Trainee Colombo 2018
## OOP
- Thực hiện bởi: Dương Minh Nam
## Sự khác nhau giữa Trait, Interface và Abstract   

| Abstract                   |  Interface                 | Trait             |
| -------------------------- | -------------------------- | ----------------- |
| Là Class cha cho tất cả    | Là một khuôn mẫu để cho một| Là một nhóm các   |
| class có cùng bản chất     | đối tượng implement, không | method mà bạn muốn|
| (kiểu, loại, nhiệm vụ)     | phải là một lớp cụ thể     | include nó trong  |
|                            |                            | một class khác    |
| -------------------------- | -------------------------- | ----------------- |
| Là một  lớp cụ thể, có thể | chỉ khai báo phương thức,   |                   |
| gọi, định nghĩa phương thức| không đưọc định nghĩa, chỉ  |                   |
| mà lớp con sẽ kế thừa và   | khai báo đưọc hằng, không  |                   |
| Rewrite                    | khai báo biến              |                   |
| -------------------------- | -------------------------- | ------------------|
| Khai báo: thêm từ khóa     | Dùng interface thay thế    | Dùng trait thay   |
| Abstract trước Class       | cho Class                  | cho Class         |
| -------------------------- | -------------------------- | ------------------|
| Có tính kế thừa, lớp kế    | Tuy không phải là lớp nhưng|                   |
| thừa phải rewrite lại tất  | vẫn có tính kế thừa        |                   |
| cả các phương thức của     | Interface A kế thừa Ìtf B  |                   |
| Abstract, nếu không sẽ sai | thì đối tượng implement A  |                   |
|                            | phải định nghĩa lại tất cả |                   |
|                            | phương thức của A và B     |                   | -------------------------- | -------------------------- | ----------------- |
| Sử dụng: khi muốn định     | Một Class có thể thực hiện | Dùng khi muốn sử  |
| nghĩa sẵn một số phương    | nhiều Interface, dùng khi  | dụng lại trong    |
| thức để tuân thủ theo và   | muốn lớp con tuân thủ theo | nhiều Class khác  |
| phát triển các lớp con     | đúng các phương thức đã    |                   |
| ( không hỗ trợ đa thừa kế) | định nghĩa                 |                   |