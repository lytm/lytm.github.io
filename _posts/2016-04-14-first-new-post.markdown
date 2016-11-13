---
layout: post
title:  "Chrome-Extension Highlighter Basic"
date:   2016-04-14 10:18:00
categories: Share
---

### Tiểu sử ra đời
![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/08d5b2f.png_dfdcvvtrvw)   
- Không biết các bạn có bao giờ giống mình không? Nhiều khi lang thang đọc điết trên mạng rồi thấy mấy cái ý hay, ý tâm đắc muốn **đánh dấu để sau này còn đọc tiếp** hoặc là mấy từ tiếng Anh chưa hiểu, đánh dấu lại, hay thêm description = tiếng Anh sẵn tiện **học t.A luôn**,...
- Ah thêm một điều nữa là khi mình đã đọc bài biết trên web đó rồi, highlight description đủ kiểu, muốn **share cho đứa bạn** để nó nhanh nắm ý của bài đó hơn, cũng là một mục đích nữa..hehe.
- Tìm trên chrome store thì chả thấy cái nào ưng ý, thiếu này hụt sau nên thôi nghiên cứu cái extension của google viết cái tiện xài cho thỏa :) Dài dòng nhờ, bạn nào lười bỏ qua xuống dưới luôn cũng được, tại mình phải diễn giải hoàn cảnh ko là ko đc đâu :D.Qua tới phần chính nào.

### Nội dung cái extension - Highlighter-Basic
GitHub: [https://github.com/jinhduong/highlighter-basic](https://github.com/jinhduong/highlighter-basic)

>`Ctr + B`: make highlight for selected text.   
> `Shift + N`: move to next highlight position.  
>`Ctrl+ Shift + F`: create the highlight file(.json).  
>`Ctrl +Shift + L`: clear the highlight data for this page.   
> `Import`: import highlight-data from json file.  

**Update 14.04**

> `Shift + N` : Move to next red point position.  
> _**New feature**_ - Add red point to the web.  
> `Add red point` : Right-click, choose "Make red point" and then type description.  
> Update the feature of `download file`  

**NOTICE** : If you created the highlight with null description then it will become to italic highlight.    
**VIDEO**: [Highlight-basic demo](https://www.youtube.com/watch?v=IexXmwJncYw&feature=youtu.be)

**P/S** : Trong folder `/dist/` có 2 file (`.crx`, `.json`) cách dùng file `crx` là kéo nó vào chrome extension để cài  (**open mode dev lên nhé**), còn file `.json`bạn vào trang https://developer.chrome.com/extensions/messaging rồi sau đó import data để test thử chức năng **`import`** nhé.


**Hình ảnh gọi là**
![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/h2.png_h0x4ncj2og)

### Tâm tư
![alt text](https://s3-ap-southeast-1.amazonaws.com/kipalog.com/hqdefault.jpg_cq0xy0q7f4)
- Code mình thì open trên github, code cùi, ae cứ chém,gạch đá, góp ý thoải mái cho mình nha, cao thủ góp ý thì lại còn đc mở mang đầu óc, nhưng mà nhẹ nhẹ ~.~ chém quá nặng, đau đớn nhau :D. Mình cũng mới viết nó nên cũng lung tung ben xị ngậu, **ae nào thấy thích thì dev với mình cho vui**, tại đang dev xài khi nào thấy ổn, đủ features thì chắc mình up lên chrome store kiếm star :). 

Mọi update mới của tool này sẽ được cập nhật thường xuyên trên blog của mình.
Thanks

{% include disqus.html %}