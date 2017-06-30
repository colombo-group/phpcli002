# phpcli002
Bài tập về làm việc với PHP tạo chương trình tương tác qua command line hoặc chạy như service

# Mục tiêu
- Làm quen hơn với tương tác command line
- Làm quen với việc giao tiếp với 1 ứng dụng khác bằng PHP
- Làm quen với thư viện thuộc symfony([Process](http://symfony.com/doc/current/components/process.html))

# Yêu cầu
- Tạo 1 chương trình bằng php, ví dụ pdfinfo.php
- Khi gọi `php pdfinfo.php xxx.pdf` chương trình sẽ hiển thị thông tin file pdf dạng array của PHP.
Ví dụ
```
array(
  'Title' => "Microsoft Word - lvtonghop--ygeyfg _14_",
  'Author' => "Augi",
  'Creator' => "Microsoft Word - lvtonghop--ygeyfg _14_",
  'Producer' => "doPDF Ver 7.1 Build 341 (Windows 7 Ultimate Edition - Version: 6.1.7600 (x86))",
  'CreationDate' => "Sat Jan 19 21:23:08 2013 +07",
  ...
```
- Khi gọi `php pdfinfo.php xxx.pdf --fields=title,author` thì chỉ hiển thị mảng chứa Title và Author 
