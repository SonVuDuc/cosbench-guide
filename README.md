# Tài liệu hướng dẫn sử dụng tool COSBench

## Mô hình

COSBench là một tool dùng để kiểm tra năng lực của những hệ thống object storage.

COSBench bao gồm 2 thành phần chính:
- COSBench driver: Có tác dụng tạo workload, thực thi các operation tới hệ thống objetc storage, đồng thời thu thập dữ liệu về performance
- COSBench controller: Có vai trò điều khiển các drivers, thu thập thông tin về runtime của các driver, chạy các kịch bản kiểm thử

Một hệ thống có thể bao gồm nhiều COSBench driver instance và một COSBench controller

![image](https://user-images.githubusercontent.com/32956424/199870184-f4b310c6-44fb-49f1-a572-a1878350f985.png)

