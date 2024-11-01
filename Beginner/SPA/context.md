# SPA - Single-Page Application
- ReactJS là 1 trong những thư viện tạo ra SPA
- Các "Ông lớn" sử dụng SPA: Google, Facebook, Twitter,...
- Các SPA khác: F8, Shoppe, 30shine, zingmp3

## Cách triển khai
- SPA - Single-Page Application -> CSR -> Client Side Rendering
- MPA - Multiple-Page Application -> SSR -> Server Side Rendering

---

## Difference

### SPA
- Được cho là cách tiếp cận hiện tại hơn
- Không yêu cầu tải lại trang trong quá trình sử dụng 
- Single-Page : Chỉ đến kiến trúc bên dưới

### MPA
- Là cách tiếp cận cổ điển hơn
- Tải lại trang trong quá trình sử dụng (click vào link, chuyển sang, ...)

---

## So sánh

### Speed
- SPA nhanh hơn khi sử dụng
    - Phần lớn tài nguyên được tải trong lần đầu
    - Trang chỉ tải thêm dữ liệu mới khi cần
- MPA chậm hơn khi sử dụng
    - Luôn tải lại toàn bộ trang khi truy cập và chuyển hướng

## Bóc tách
- SPA có phần Front-End riêng biệt
- MPA Front-End & Back-End phụ thuộc vào nhau nhiều hơn, được đặt trong cùng 1 dự án 

### SEO - Search Engine Optimization
- SPA không thân thiện với SEO như MPA
- Trải nghiệm trên thiết bị di động tốt hơn

### UX
- SPA cho trải nghiệm tốt hơn, nhất là các thao tác chuyển trang
- Trải nghiệm trên thiết bị di động tốt hơn

### Quá trình phát triển
- SPA dễ dàng tái sử dụng code (component)
- SPA bóc tách FE & BE
    - Chia team phát triển song song
    - Phát triển thêm mobile app dễ dàng    

### Phụ thuộc Javascript
- SPA phụ thuộc hoàn toàn vào Javascript
- MPa có thể không cần Javascript

---

## Chọn SPA hay MPA
- MPA : Như làm một trang đơn giản và tương lai cũng không có ý định phát triển  lên một trang lớn, không mở mobile app
        - Đảm bảo tốc độ phát triển nhanh 

- SPA : Khách hàng quan tâm tới trải nghiệm người dùng, mượt mà, sau này phát triển thêm mobile app, features, đòi hỏi trải nghiệm người dùng tốt.
        - chi phí phát triển cao

## Performance
- Khi một ứng dụng có nhiều người truy cập thì SPA sẽ "giảm tải cho server" 
- Bởi việc render dữ liệu đẩy về client làm, trình duyệt tự đọc script và render giao diện

- MPA : Khi sử dụng thì all requests sẽ đổ lên phía server và mỗi một thao tác chuyển trang sẽ phải request lên server => Tăng tải cho server
        - Tốn nhiều chi phí hơn về máy chủ, hạ tầng