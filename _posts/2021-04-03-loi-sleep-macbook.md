---
layout: post
title:  "Lỗi sleep của Macbook và cách khắc phục"
author: Andy
categories: [ Thitluoc, Macbook, Hướng dẫn ]
tags: [thitluoc, sleep]
image: assets/images/loi-sleep-macbook.jpeg
featured: true
hidden: true
rating: 4
---

Thỉnh thoảng có anh em thắc mắc là gập máy Macbook qua đêm mà pin sụt mất 20-30%? Hoặc có anh em gập máy sau đó bỏ vào balo, lúc về đến nhà, máy nóng ran, chứng tỏ máy vẫn hoạt động bình thường khi ở bên trong balo.

**Lý do lỗi sleep, nguyên nhân có thể là:**
  - Một ứng dụng nào đó bị lỗi ngăn cản quá trình sleep hoặc có ứng dụng nào đó được thiết kế để chạy 24/24.
  - Có thiết bị bluetooth như chuột/bàn phím ngoài.
**Các việc anh em nên làm để gỡ lỗi:**
  - Reset SMC/PRAM (rất hữu ích, nên làm trước tiên).
  - Gỡ tạm thời các thiết bị cắm ngoài: HDD, USB-HUB, Chuột/phím bluetooth (mục đich rò lỗi).
  - Tìm ra ứng dụng gây lỗi.

Việc của chúng ta bây giờ là tìm ra ứng dụng đó và gỡ nó ra, hoặc thay thế nó bằng một phiên bản tốt hơn.

Nói thêm một chút, MacOS vốn là nhân Unix, anh em nào làm hệ thống thì biết, Unix được tối ưu để chạy 24/24. Các hệ thống Unix mà mình từng quản trị có khi đến 10 năm mà không phải shutdown hoặc restart. Rất khác với hệ thống tương tự dùng Windows nhé, nếu 1-2 tuần mà không khởi động lại là thì tự nó sinh ra rất nhiều lỗi linh tinh cộng với chậm, lag… Chính vì thế người dùng laptop Windows thường có thói quen shutdown.

***Ngược lại, người dùng Macbook chỉ cần gập máy sleep, hành động này là chính xác nhất và được tối ưu bởi Apple.***

**Giờ quay lại với việc tìm ra ứng dụng nào gây lỗi sleep. Có hai cách:**
  - ***Cách 1 dùng Terminal:*** gõ lệnh pmset -g assertions.
  <br>
  Nếu mục PreventUserIdleSystemSleep = 0 thì có nghĩa máy đang ở tình trạng tốt, sleep bình thường, nếu giá trị đó lớn hơn 0 (1) là có ứng dụng ngăn cản quá trình sleep thông thường, bên dưới đó là giải thích về các ứng dụng đó.
  - ***Cách 2 dùng Activity Monitor:*** phần Preventing Sleep (Yes), liệt kê các ứng dụng ngăn cản quá trình sleep.
  <br>
  Vụ này nếu bàn cụ thể ra thì còn rất dài, mà bài viết của mình chỉ có tính phương hướng, không phải là bài hướng dẫn cụ thể. Vì thế anh em nào có thắc mắc, vui lòng còm bên dưới nhé.
***Ghi chú:*** Nếu bạn không tìm thấy YES trong phần Preventing Sleep hoặc PreventUserIdleSystemSleep = 0 là máy bạn đang ở tình trạng TỐT nhé.

Cảm ơn anh em nhiều lắm.

***Nguồn:*** [Hội Macbook Việt](https://www.facebook.com/groups/hoimacbookviet/permalink/1392810217738668/)
