# Từ điển tiếng Việt dành cho Kindle

Mã nguồn cho từ điển dành cho máy đọc sách Kindle. Để sử dụng download tại đây http://catusf.github.io/.

### Hướng dẫn

Chạy từ dòng lệnh `cmd` trong Windows. Yêu cầu có Python 2.5 trở lên.

1. Chuyển vào thư mục `bin`
```
>cd bin
```

2. Chuyển file dữ liệu từ điển gốc .txt phân cách bằng dấu cách thành dạng sách điện tử .opf.
```
>createhtml.bat
```

3. Chuyển file .opf thành từ điển dạng .mobi dùng trên Kindle.

```
createmobi.bat
```

Việc còn lại là copy file .mobi vừa được tạo ra vào máy Kindle để bắt đầu sử dụng.


### Chat với tác giả

[![Join the chat at https://gitter.im/catusf/tudienanhviet](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/catusf/tudienanhviet?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
 