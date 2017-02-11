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
# Nội dung
---
#I. HTML là gì và vì sao nó quan trọng. 
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
   - **Một thẻ có thể sử dụng nhiều thuộc tính chứ không phải chỉ một thuộc tính.** 
 - Dùng chương trình gì để tạo tập tin HTML? 
    HTML là một tập tin siêu văn bản nên bạn có thể dùng các chương trình soạn thảo văn bản không có chức năng định dạng văn bản để tạo ra một tập tin HTML. 
 - HTML đóng vai trò gì trong website? 

    <img src="http://hoclamwebonline.com/media/1026/html-css-javascript.png?width=555&height=343"> 

 - Một website bao gồm:  
    - **HTML**: Xây dựng cấu trúc và định dạng các siêu văn bản.  
    - **CSS**: Định dạng các siêu văn bản dạng thô tạo ra từ HTML thành một bố cục
    website, có màu sắc, ảnh nền,….  
    - **Javascript**: Tạo ra các sự kiện tương tác với hành vi của người dùng (ví dụ nhấp vào ảnh trên nó sẽ có hiệu ứng phóng to).  
    - **PHP**: Ngôn ngữ lập trình để xử lý và trao đổi dữ liệu giữa máy chủ đến trình duyệt (ví dụ như các bài viết sẽ được lưu trong máy chủ).  
    - **MySQL**: Hệ quản trị cơ sở dữ liệu truy vấn có cấu trúc (SQL – ví dụ như các bài viết sẽ được lưu lại với dạng dữ liệu SQL).  
 **- Như vậy HTML như là một cái khung sườn của website.** 

#II. Soạn một đoạn HTML đầu tiên
 Soạn thảo văn bản HTML ở đây nghĩa là chúng ta sẽ tập viết một văn bản được định dạng bằng các thẻ HTML chứ không phải là tạo ra một tập tin HTML hoàn chỉnh. 
##Hãy sử dụng Sublime Text để soạn thảo. 
 - Sublime Text là một chương trình soạn thảo văn bản (Text Editor) miễn phí mà thường là phục vụ cho việc soạn thảo các loại văn bản đơn giản cho đến các đoạn code phức tạp 
 - Soạn thảo văn bản HTML đầu tiên 
     - Cặp thẻ `<h1> </h1>` để thiết lập tiêu đề cho văn bản, và đặt các đoạn văn bản nhỏ vào cặp thẻ `<p> </p>`
     ``
     <h1>Tiêu đề 1</h1>  

     <p> 

      Đoạn văn bản 

     </p> 
     ``
 - Giải thích thêm: 
     - Thẻ `<h1>` (viết tắt của chữ Heading level 1) là cặp thẻ để xác định một tiêu đề trong văn bản. Tiêu đề sẽ được in đậm, có size chữ lớn hơn và được ngăn cách với các đoạn văn bản khác (có margin). Ngoài thẻ `<h1>` thì còn có các thẻ **heading** với thứ bậc thấp hơn như `<h2>`, `<h3>`,`<h4>`, `<h5>`, `<h6>`. Thẻ `<p>`(viết tắt của chữ Paragraph) là cặp thẻ xác định một đoạn văn bản. Mỗi đoạn văn bản đặt trong thẻ `<p>` sẽ được xem như là một dòng, mỗi dòng sẽ có những khoảng cách ngăn với nhau.  

#III. Cấu trúc một tài liệu web bằng HTML. 
##1. Một tài liệu hay tập tin HTML để được gọi là một tài liệu web thì sẽ được bao gồm bốn yếu tố chính đó là:  
  - Có thẻ khai báo loại tập tin/tài liệu.  
  - Có thẻ đóng và mở tài liệu HTML.  
  - Có thẻ đóng và mở phần thông tin website.  
  - Có thẻ đóng và mở phần nội dung website. 

##2. Thẻ khai báo loại tập tin  
  - Ngay tại đoạn đầu tiên của tài liệu, chúng ta phải có một thẻ khai báo loại tập tin cho nó như thế này, cụ thể là ta sẽ khai báo rằng đây là tập tin HTML. 
     `<!DOCTYPE html>` 
  - Với thẻ `<!DOCTYPE>` ở trên, ta có thêm một tham số đó là html. Tham số html này nghĩa là chúng ta khai báo với trình duyệt rằng đây là tài liệu HTML5 (HTML 
   phiên bản 5), dù rằng chúng ta có thể không sử dụng HTML5 nhưng hiện tại khi khai báo tập tin HTML thì bạn cứ sử dụng tham số này vừa ngắn gọn lại vừa dễ 
   dàng sử dụng thêm HTML5 nếu thích. 
  - Có một điều thú vị là thẻ `<!DOCTYPE>` không phải là một thẻ của HTML, mà nó chỉ là một thẻ khai báo thông tin trên tài liệu để trình duyệt hiểu phiên bản  
   HTML mà bạn sử dụng trên website mà thôi. 

##3. Thẻ đóng mở tài liệu HTMl 
  - Kế tiếp, ở tầng tiếp theo sẽ là thẻ `<html> </html>` có nhiệm vụ khai báo cho trình duyệt biết rằng những nội dung bên trong cặp thẻ này là HTML. Tuy nhiên, bên
    trong thẻ này mình có thêm một thuộc tính tên là lang với giá trị là vi `(<html lang="vi">)`. Thuộc tính này nghĩa là chúng ta khai báo cho trình duyệt biết mã ngôn ngữ mà ta sử dụng trên website, mã **vi** nghĩa là *Vietnamese – tiếng Việt*. 
  - Bạn nên nhớ một điều là thẻ `<html> </html>` phải bao bọc toàn bộ nội dung website, không bao gồm thẻ `<!DOCTYPE>`. 

##4. Thẻ đóng và mở phần thông tin website. 
  - Phần khai báo thông tin của website sẽ được đặt vào bên trong cặp thẻ gọi là `<head> </head>`. Nội dung bên trong thẻ này là các thẻ chuyên cho khai báo thông tin website (meta), tên website (title), khai báo CSS (style), khai báo các đoạn Javascript (script) và một số thông tin khác. Thường là các thông tin được khai báo trong đây sẽ không hiển thị trực tiếp thành siêu văn bản trên web nhưng nó sẽ có nhiệm vụ chứa các thông tin quan trọng về website. 

##5. Có thẻ đóng và mở phần nội dung website 
  - Đây là cặp thẻ mà bạn sẽ tiến hành viết nội dung vào, đó là cặp thẻ <body> </body>. Cặp thẻ này là để trình duyệt xác định đây là phần thân của website, nó sẽ chứa toàn bộ các nội dung siêu văn bản hoặc media mà bạn muốn nó hiển thị lên trang web của bạn. Phần này chúng ta sẽ làm việc nhiều hơn ở các bài sau.  

#IV. Các thẻ khai báo thông tin web cơ bản
##1. Khai báo tên tài liệu với cặp thẻ `<title>` 
 - Thẻ `<title> </title>` có tác dụng khai báo tên tài liệu web của bạn đang soạn. Ứng dụng thực tiễn của thẻ này là giúp trình duyệt hiển thị tên tài liệu khi mở lên và các cỗ máy tìm kiếm như Google cũng hiển thị nội dung trong cặp thẻ này để lấy tên tài liệu. 

##2. Khai báo dữ liệu vĩ mô với thẻ <meta>
 - Thẻ `<meta>` là một thẻ đặc biệt vì nó không có thẻ đóng như các thẻ khác mà sẽ có dấu gạch chéo như `/` ở đằng trước ký tự > cuối cùng. Thẻ này có mục đích khai báo các dữ liệu vĩ mô trong tài liệu web HTML của bạn như mô tả, từ khóa, tên tác giả, bảng mã ký tự sử dụng,… 
 - Thẻ meta luôn được khai báo kèm theo ít nhất là một thuộc tính và mỗi thuộc tính phải luôn có giá trị. 
   Ví dụ: 
    `<meta charset="utf-8" />` 
 - Trong đó, **charset** là tên thuộc tính và **utf-8** là giá trị của thuộc tính **charset**. 

##3. Thuộc tính charset 
 - Thuộc tính **charset** trong thẻ `<meta>` có nhiệm vụ khai báo cho trình duyệt biết bảng mã ký tự siêu văn bản bên trong tài liệu là gì. Và hiện nay hầu hết chúng ta đều sử dụng bảng mã **UTF-8** cho tất cả ngôn ngữ bao gồm các ngôn ngữ tiếng latin, chữ Hán – Nôm và các ngôn ngữ đọc từ phải sang trái (Right to Left – RTL) như tiếng Ả-Rập chẳng hạn.
 - Thuộc tính **name**  
     - Đối với thuộc tính **name** thì thẻ **meta** của bạn phải có hai thuộc tính, đó là thuộc tính **name** và **content**, trong đó thuộc tính **content** được xem là thiết lập nội dung cho thuộc tính **name**. 
     - Ví dụ: 
       `<meta name="author" content="Phạm Đạt"/>``
     - Trong đó, giá trị của thuộc tính **name** là một giá trị có sẵn vì hiện tại thuộc tính name hỗ trợ một số giá trị như: 
          - **author**: Khai báo tên tác giả của tài liệu. 
          - **description**: Khai báo mô tả của tài liệu. 
          - **keyword**: Khai báo từ khóa của tài liệu, các từ khóa này sẽ đóng vai trò hỗ trợ các trình tìm kiếm văn bản hoặc máy tìm kiếm website dò tìm. 
     - Ngoài ra còn một số giá trị khác như: 
          - **application-name**: Tên ứng dụng đại diện của tài liệu web. 
          - **generator**: Khai báo tên ứng dụng tạo ra tài liệu. 

#V.Các thẻ định dạng chữ viết và văn bản.
##1. Tiêu đề và đoạn văn bản 
 - Tiêu đề. 
     ```
     <h1>Hello Wolrd 1</h1>

     <h2>Hello Wolrd 2</h2>

     ...

     ...

     <h6>Hello Wolrd 6</h6>
     ``` 
<img src="http://st1.streampow.net/tu-hoc-html-css-javascript/bai-hoc/html-the-co-ban.jpg"> 
 - Còn đoạn văn bản thì nó sẽ được khai báo bằng cặp thẻ `<p> </p>`. Các văn bản nằm trong cặp thẻ này sẽ được hiểu là một đoạn văn bản, mỗi đoạn văn bản sẽ được xuống dòng và cách nhau với tỷ lệ nhất định. 

##2. Các thẻ định dạng chữ viết 
 - `<strong>`: In đậm chữ viết. 
 - `<i>`: In nghiêng chứ viết. 
 - `<u>`: Gạch chân chữ viết. 
 - `<strike>`: Gạch ngang chữ viết. 
 - `<em>`: Nhấn mạnh câu. 
 - `<code>`: Định dạng cho một đoạn mã nào đó. 
 - `<hr>`: Thước kẻ ngang trên tài liệu. 
 - `<mark>`: Tô sáng chữ viết. 
##3. Thẻ trích dẫn 

 - Thẻ trích dẫn được quy định là `<quote>` và tên tác giả trích dẫn được quy định là `<cite>`.  
 - Lưu ý rằng thẻ `<cite>` thường chỉ nên dùng đặt trong thẻ `<quote>` thôi chứ dùng tùy tiện nó lại mất hay. Và mặc định thì các trình duyệt sẽ tự quy định nội dung nằm trong thẻ `<cite>` sẽ được in nghiêng, còn thẻ `<quote>` thì không có gì cả nhưng sau này bạn làm tới phần CSS rồi thì có thể tự thêm tí “phong cách” cho thẻ `quote` đẹp hơn. 
 - Thẻ định dạng sẵn. 
     - Trong HTML hiện tại nó có một thẻ được gọi là thẻ định dạng sẵn (preformatted), thẻ này sẽ được viết là `<pre> </pre>`. Sở dĩ nó được gọi là thẻ định dạng sẵn vì mặc định trình duyệt đã tự động định dạng cho các nội dung nằm bên trong thẻ đó như kích thước chữ, khoảng cách, kiểu chữ.
     - Thẻ `<pre> </pre>` này thường được dùng để đăng một câu đối thoại hoặc in một đoạn mã để cho dễ phân biệt với các văn bản thông thường.
 - Thuộc tính **style** để định dạng chữ viết.
     - Màu chữ. 
         Để thiết lập màu chữ, bạn có thể sử dụng thuộc tính **color**. Giá trị của nó là tên màu trong tiếng Anh hoặc mã màu HEX. 
         `<span style="color: red">chữ màu đỏ</span>` 
     - Màu nền. 
         - Màu nền có cách thiết lập giống hệt màu chữ, tức là bạn có thể dùng giá trị là tên màu trong tiếng Anh hoặc mã màu HEX. Tên thuộc tính của màu nền là 
         **background-color**. 
         `<span style="color: white; background-color: red">Chữ có nền màu đỏ và màu chữ là trắng</span>` 
     - Kích thước chữ. 
         - Kích thước chữ bạn có thể sử dụng thuộc tính font-size và giá trị là số kèm đơn vị. Bạn có thể sử dụng đơn vị px, %, pt hoặc em tùy thích, đơn giản nhất là dùng px. 
         `<span style="font-size: 32px">Chữ có kích thước 32px</span>`
     - Font chữ. 
         - Nếu bạn có nhu cầu sử dụng font chữ khác so với font chữ mặc định thì hãy dùng thuộc tính font-family với giá trị là tên font chữ có trên máy tính. Một số tên font chữ phổ biến nhất là Arial, Helvetica, Time New Roman, Verdana.  
         `<span style="font-family: Arial">Font chữ Arial</span>` 
         - Ngoài ra bạn có thể thêm font chữ dự phòng bằng cách khai báo nhiều tên font chữ khác nhau được ngăn cách bởi dấu phẩy. 
           `<span style="font-family: Helvetica, Arial">Font chữ Arial</span>` 
         - Có nghĩa là nếu máy người đọc không có font chữ Helvetica thì nó sẽ sử dụng font chữ Arial. 
 - Căn lề văn bản. 
     - Để canh lề, chúng ta sử dụng thuộc tính text-align với giá trị là left,center, right hoặc justify. 
     `<span style="text-align: center">Canh giữa văn bản</span>`

