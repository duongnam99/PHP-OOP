# Bài tập Trainee Colombo 2018
## OOP
- Thực hiện bởi: Dương Minh Nam
## Sự khác nhau giữa Trait, Interface và Abstract   

| Abstract                   |  Interface                 | Trait            
 --------------------------- | -------------------------- | ----------------- 
Là Class cha cho tất cả class có cùng bản chất (kiểu, loại, nhiệm vụ) |  Là một khuôn mẫu để cho một đối tượng implement, không phải là một lớp cụ thể |  Là một nhóm các method mà bạn muốn include nó trong một class khác  
Là một  lớp cụ thể, có thể gọi, định nghĩa phương thức mà lớp con sẽ kế thừa và Rewrite | chỉ khai báo phương thức, không đưọc định nghĩa, chỉ khai báo đưọc hằng, không khai báo biến |  
Khai báo: thêm từ khóa Abstract trước Class | Khai báo 'interface' thay thế cho 'class'  | Dùng 'trait' thay cho 'class'  
Có tính kế thừa, lớp kế  thừa phải rewrite lại tất cả các phương thức của Abstract, nếu không sẽ sai | Tuy không phải là lớp nhưng vẫn có tính kế thừa. Interface A kế thừa Ìnterface B thì đối tượng implement A phải định nghĩa lại tất cả phương thức của A và B |  
Sử dụng: khi muốn định nghĩa sẵn một số phương thức để tuân thủ theo và phát triển các lớp con (không hỗ trợ đa thừa kế) | Một Class có thể thực hiện nhiều Interface, dùng khi muốn lớp con tuân thủ theo đúng các phương thức đã định nghĩa | Dùng khi muốn sử dụng lại trong nhiều Class khác
