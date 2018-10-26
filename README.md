# spring-boot-default-logging

Hiểu một cách đơn giản "Logging" là "ghi chép" lại các vấn đề trong quá trình ứng dụng hoạt động. Các vấn đề ở đây là các thông tin lỗi, các cảnh báo (warning), và các thông tin khác, ... Các thông tin này có thể được hiển thị trên màn hình Console hoặc ghi vào file. 

Có nhiều thư viện Logging khác nhau như Logback, Log4j2, JUL,.. Spring Boot có thể làm việc với tất cả các thư viện này. Theo mặc định Spring Boot đã tự động cấu hình và sử dụng thư viện Logback cho logging của nó, và bạn không cần bất kỳ một cấu hình nào thêm, trừ khi bạn muốn tùy biến một vài thông số (argument). Các tùy biến ở đây có thể là chỉ định tên tập tin để ghi các thông tin, khuôn mẫu (pattern), ... 

# Logging Level
1. TRACE
2. DEBUG
3. INFO
4. WARN
5. ERROR
6. FATAL 
7. OFF



