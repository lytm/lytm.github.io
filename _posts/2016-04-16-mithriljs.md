---
layout: post
title:  "MithrilJS - Building Brilliant Applications (p1)"
date:   2016-04-14 10:18:00
categories: Javascript
---

### Giới thiệu về Mithril framework ![alt text](http://i.imgur.com/PnpwICv.png)  
- [Mithril](http://mithril.js.org) Thật ra dự án này cũng đã được phát triển khoảng một năm rồi, theo như thời gian contributors của dự án này thì nó bắt đầu từ April 2015, khoảng mấy tháng trước lúc mình có thông tin về framework này, sau đó lên xem thì nó đã release version **0.1**, giờ version hiện tại đã là **0.2.3** rồi.

![alt text](http://i.imgur.com/goUsnEZ.png)

- Vậy **Mithril** là gì? Theo như trang chủ thì nó là một client-framework theo mô hình MVC, dùng để tổ chức mã(code) một cách dễ dàng, sáng sủa để đọc hiểu, cũng như là bảo trì sau này (maintain), đơn giản **dễ đọc dể hiểu** thì sẽ **dễ bào trì** hơn :). Và theo ý kiến cá nhân của mình thì đó cũng chính là ngọn nguồn của framework này.   
- Vậy những điểm mạnh của nó là gì?  

> **Light-weight (nhẹ)**: Chỉ 7.8kB gzipped, do không phụ thuộc vào cái gì, nên nó hoàn toàn độc lập. API ít dễ dàng cho việc tìm hiểu về nó (chỉ có 5 phần chính *[Core, Routing, Data, HTML, Rendering]* và API từ đó cũng chỉ có ở trên dưới 20).  
> **Robust (mạnh mẽ)**: An toàn bởi các mẫu template mặc định, sử dụng mô hình MVC cho các components.  
> **Fast** (nhanh): Có **Virtual DOM** và compilable templates (các mẫu có khả năng biên dịch được), intelligent auto-redrawing system (hệ thống tự vẽ lại thông minh).

> **Mithril** là một kim loại trong thế giới tưởng tượng, được lần đầu viết ra với tác giả *J. R. R. Tolkien*, nó giống như bạc nhưng mà cứng hơn thép, đại loại vậy (quí hay không chả biết nữa :D)... (các bạn thể tìm hiểu tiếp ở Wiki nhen :D [Wikipedia Mithril](https://en.wikipedia.org/wiki/Mithril))

### Sử dụng và lý do sử dụng
![alt text](http://i.imgur.com/8bmCMxP.png)
- Giữa vô vàng framework về javascript như hiện nay, thật sự mà nói thì nó nhiều kinh khủng lun đấy :D, ví dụ: **React, Flux, Angular, Aurelia, Mocha, Jasmine, Babel, TypeScript, Flow,...** còn nhiều nhiều nữa, kể thì ko biết bao giờ mới xong, mà không biết kiến thức mình đủ để list bằng hết ko nữa ^_^. Nhưng có một post được viết trên Medium là:

>Hệ sinh thái javascript đang dần chậm lại, các dự án đang được sáp nhận lại với nhau, mọi người đã bắt đầu build trên những công cụ, công nghệ có sẵn thay vì building 1 framework mới.  

- Nghe tuyệt đấy chứ :D, quay lại main của topic nào :D, đó - rõ ràng nhiều khi framework to quá học cũng lâu @_@, nhiều khi không dùng đến hết những thứ của nó, **chỉ cần framework nhỏ thôi, chia module rõ ràng, nhìn vào dễ hiểu dễ học, ít config lăng quăng, có bộ DOM virtual xe đạp riêng nữa thì quá tuyệt**,... nói chung nhỏ nhẹ dễ chơi thì Mithril là một lựa chọn khá ok. Và một điều nữa là nó có dự án cho phần virtual DOM y như JSX của React, đó chính là [MSX](https://github.com/insin/msx) dùng để render cho Mithril.

Đến đây cũng khá là dài rồi (dài hay không không biết nhưng type mỏi tay ghê :D) phần sau mình sẽ nói về khái niệm của nó cũng như cơ chế hoạt động,cách sử dụng và đương nhiên là demo từ cơ bản đến đi sâu hơn về nó phần sau nhé.

{% include disqus.html %}