# Tìm hiểu HTML	
---
  Thực hiện: **Phạm Văn Đạt**

  Cập nhập lần cuối: *12/2/2017*

## Mục lục 

<a href="#Git">1.Gi</a>
  <ul>
    <li><a href="#Nội dung1">1.1Nội dung</a></li>
    <li><a href="#Công dụng1">1.2Công dụng</a></li>
  </ul>
---
## Nội dung
---
#I. HTML là gì và vì sao nó quan trọng
##1. HTML là gì?
 - HTML là chữ viết tắt của cụm từ HyperText Markup Language(dịch là Ngôn ngữ đánh dấu siêu văn bản) được sử dụng để tạo một trang web, trên một website có thể sẽ chứa nhiều trang và mỗi trang được quy ra là một tài liệu HTML.
 - Một tập tin HTML sẽ bao gồm các phần tử HTML và được lưu lại dưới đuôi mở rộng là .html hoặc .htm.
##2.HTML được xử lý ra sao?
 - Khi một tập tin HTML được hình thành, việc xử lý nó sẽ do trình duyệt web đảm nhận. Trình duyệt sẽ đóng vai trò đọc hiểu nội dung HTML từ các thẻ bên trong và sẽ chuyển sang dạng văn bản đã được đánh dấu để đọc, nghe hoặc hiểu (do các bot máy tính hiểu).

 ```
 <!DOCTYPE html>
 <html>
    <head>
        <title>tiêu đề</title>
    </head>
    <body>
        <p>phân thân của trang web hiểm thị ra bên ngoài</p>
    </body>
 </html>
 ```
 - Cấu trúc một đoạn HTML 
   - Khai báo một đoạn văn bản. 
     `<p>Đây là một đoạn văn bản trong HTML.</p>` 
   - Ngoài ra, trong các thẻ còn có các thuộc tính, thuộc tính sẽ đặt bên trong thẻ mở đầu, mỗi thuộc tính sẽ có giá trị được đặt trong dấu ngoặc kép và cách nhau bởi dấu bằng (=) với tên thuộc tính. 
     `<form action="http://thachpham.com"> </form>` 
   - *Một thẻ có thể sử dụng nhiều thuộc tính chứ không phải chỉ một thuộc tính.* 
 - Dùng chương trình gì để tạo tập tin HTML? 
    HTML là một tập tin siêu văn bản nên bạn có thể dùng các chương trình soạn thảo văn bản không có chức năng định dạng văn bản để tạo ra một tập tin HTML. 
 - HTML đóng vai trò gì trong website? 
    <img src="http://hoclamwebonline.com/media/1026/html-css-javascript.png?width=555&height=343"> 
    Một website bao gồm: 
     -**HTML**: Xây dựng cấu trúc và định dạng các siêu văn bản.
     -**CSS**: Định dạng các siêu văn bản dạng thô tạo ra từ HTML thành một bố cục website, có màu sắc, ảnh nền,….
     -**Javascript**: Tạo ra các sự kiện tương tác với hành vi của người dùng (ví dụ nhấp vào ảnh trên nó sẽ có hiệu ứng phóng to).
     -**PHP**: Ngôn ngữ lập trình để xử lý và trao đổi dữ liệu giữa máy chủ đến trình duyệt (ví dụ như các bài viết sẽ được lưu trong máy chủ).
     **MySQL**: Hệ quản trị cơ sở dữ liệu truy vấn có cấu trúc (SQL – ví dụ như các bài viết sẽ được lưu lại với dạng dữ liệu SQL).
 *- Như vậy HTML như là một cái khung sườn của website.*

