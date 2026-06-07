\# NHẬN DIỆN LINH KIỆN ĐIỆN TỬ BẰNG EDGE IMPULSE VÀ FOMO



\## 1. Thông tin sinh viên



\* Họ và tên: Voong Đăng Hùng

\* MSSV: N23DCCI030

\* Lớp: D23CQCI01-N

\* Môn học: Mạng cảm biến

\* Giảng viên hướng dẫn: Hồ Nhựt Minh



\## 2. Mô tả đề tài



Đề tài xây dựng mô hình phát hiện bốn loại linh kiện điện tử bằng thị giác máy tính trên nền tảng Edge Impulse:



\* Led

\* Capacitor

\* IC

\* Resistor



Mô hình sử dụng FOMO MobileNetV2 0.35 và được tối ưu để chạy trên thiết bị biên hoặc trình duyệt thông qua WebAssembly.



\## 3. Thông số mô hình



| Thông số          | Giá trị               |

| ----------------- | --------------------- |

| Kích thước ảnh    | 96 × 96 pixel         |

| Color depth       | RGB                   |

| Processing block  | Image                 |

| Learning block    | Object Detection      |

| Model             | FOMO MobileNetV2 0.35 |

| Training cycles   | 40                    |

| Learning rate     | 0.001                 |

| Batch size        | 32                    |

| Validation set    | 20%                   |

| Data augmentation | Enabled               |

| Model version     | Quantized int8        |



\## 4. Kết quả



\* F1-score tổng: 92.5%

\* Led: 0.95%

\* Capacitor: F1 = 0.93%

\* IC: 1.00%

\* Resistor: F1 = 0,95%



Mô hình đạt yêu cầu F1-score lớn hơn hoặc bằng 0,85.



\## 5. Cấu trúc thư mục



```text

source/         Source code hoặc WebAssembly

model/          File mô hình đã export

screenshots/    Hình ảnh quá trình thực hiện và kết quả

sample-data/    Một số dữ liệu hình ảnh mẫu

report/         Tiểu luận và slide thuyết trình

demo/           Video demo hoặc link video

```



\## 6. Hướng dẫn chạy trên trình duyệt



1\. Đăng nhập Edge Impulse.

2\. Mở project theo đường dẫn được cung cấp.

3\. Vào mục Deployment.

4\. Chọn WebAssembly.

5\. Chọn model Quantized int8.

6\. Bấm Build.

7\. Chọn Launch in browser.

8\. Cho phép trình duyệt sử dụng camera.

9\. Đưa từng linh kiện trước camera để kiểm thử.



\## 7. Dependencies



\* Trình duyệt Google Chrome hoặc Microsoft Edge

\* Camera máy tính hoặc webcam

\* Kết nối Internet

\* Tài khoản Edge Impulse

\* WebAssembly-compatible browser



\## 8. Link project Edge Impulse



Project được giữ ở chế độ Private.



Giảng viên cần đăng nhập bằng tài khoản đã được cấp quyền để truy cập project.



\## 9. Video demo



Link video demo:



```text

(https://drive.google.com/drive/folders/1RKZGpLxtj3S45DSI1tVz7UyX5-IT29k4?usp=sharing)

```



\## 10. Ghi chú



Repository được hoàn thành và tạo commit cuối cùng trước thời hạn nộp bài. Không chỉnh sửa nội dung sau deadline.



