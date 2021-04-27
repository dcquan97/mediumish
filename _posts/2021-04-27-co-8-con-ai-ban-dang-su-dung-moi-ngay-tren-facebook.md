---
layout: post
title:  "Có 8 con AI bạn đang sử dụng mỗi ngày trên Facebook"
author: DcQ
categories: [ Facebook, AI, Apple ]
tags: [apple, facebook]
image: assets/images/elon-musk.jpg
featured: true
hidden: true
rating: 5
---

### Có 8 con AI bạn đang sử dụng mỗi ngày trên facebook. Cùng xem  mấy con này làm bởi thuật toán gì nha.

**AI mang lại khả năng dự đoán vượt trội so với các thuật toán thông thường, nó có khả năng hiểu và đưa ra dự đoán phù hợp cho từng cá nhân dựa vào lượng dữ liệu khổng lồ mà facebook có từ bạn.**

1. ***News feed (Dòng thời gian)***<br>
  Con AI này tính điểm cho mỗi bài post và chỉ đưa những bài viết/ story/ ảnh/ video có điểm cao lên đầu. Con này được train mỗi ngày 1 lần, sử dụng thuật toán Multi Layer Perceptron (MLP)
2. ***Ads (Quảng cáo)***<br>
Con AI này học mọi hành vi của bạn trên facebook để ném vào bạn những quảng cáo mà nó nghĩ có hiệu quả cao nhất, 3 yếu tố để đánh giá 1 post quảng cáo hiệu quả là tỉ lệ bạn bấm vào, tỉ lệ bạn vào website, tỉ lệ bạn mua hàng. Doanh thu lớn nhất của facebook và google là ads, ads mà không hiệu quả thì người ta sẽ không chạy. Con này dùng thuật toán MLP.
3. ***Search (Tìm kiếm)***<br>
Con AI này chốn ở thanh tìm kiếm, khi bạn tìm một cái gì đó (sự kiện, hotgirl, facebook của crush, bạn bè, tin tức) thì con này sẽ giúp bạn tìm được thứ bạn muốn tìm. Ví dụ bạn yêu quý Dũng Lại và quan tâm đến Lập Trình thì khi gõ Dũng nó sẽ hiển thị mình thay vì ca sĩ nào đó tên Dũng mà bạn không biết. Con này dùng MLP.
4. ***Sigma (Mạo danh, lừa đảo)***<br>
Con AI này check những thông tin, bài viết, sự kiện, tin nhắn website để đảm bảo nó không phải lừa đảo. Nó phát hiện những thứ không bình thường để bảo vệ bạn. Con này dùng GBDT (gradient boosted decision tree) và MLP
5. ***Lumos (Hiểu bức ảnh)***<br>
Con AI phân tích các bức ảnh trên facebook để hiểu xem ảnh đó có nghĩa gì, có thông tin gì, nói về cái gì, mục đích cũng là để tránh lừa đảo, biết được nội dung ảnh để đưa ảnh đó đến người phù hợp. Con này dùng CNN (convolutional neural networks) và MLP.
6. ***Facer (nhận diện mặt người)***<br>
Con AI này tìm xem có mặt ai trong 1 bức ảnh để đoán xem họ có phải bạn của bạn không, thỉnh thoảng bạn dùng facebook con này sẽ hỏi bạn đây có phải bạn không/ đây có phải người bạn quen không. Con này dùng Support Vector Machines (SVM) và CNN
7. ***Translation (Dịch ngôn ngữ)***<br>
Con AI này tự động dịch các bài post ở các ngôn ngữ khác nhau để đưa mọi người đến gần nhau hơn ❤ bỏ qua rào cản ngôn ngữ. Con này hiểu 45 ngôn ngữ, mỗi ngày nó dịch 4.5 tỉ bài post. Con này dùng Recurrent Neural Networks (RNN)
8. ***Caption (Dịch giọng nói)***<br>
Con này nhận diện giọng nói để hiện được dòng phụ đề tự động ở các video, con này còn khá non, chủ yếu chỉ hỗ trợ tiếng anh. Con này dùng RNN.
Tên bài nghiên cứu được Facebook công bố năm 2018 "Applied Machine Learning at Facebook: A Datacenter Infrastructure Perspective"

***Nguồn:*** [Dũng Lại Lập Trình](https://www.facebook.com/dung.lai.733)
