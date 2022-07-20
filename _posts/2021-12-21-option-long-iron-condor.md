---
layout: post
type: option
title: Long Iron Condor
subtitle: Long Volatility
author: a3
categories: [ option ]
image: img/uploads/screen-shot-2021-12-20-at-5.03.45-pm.png
date: 2021-12-21T01:58:23.475Z
---
##### Khái Niệm

Iron Condor (IC) cũng là cách đánh nhắm vào dự đoán về mức biến động của cổ phiếu (còn gọi là Implied Volatility). Iron Condor cũng có 2 kiểu trade: Long IC & Short IC. 

- Long IC dùng khi dự đoán cổ phiếu sẽ có biến động mạnh (lên hoặc xuống).
- Short IC dùng khi dự đoán cổ phiếu (hiện đang dao động mạnh) sẽ sớm “sóng yên biển lặng”. 

Bài viết này tập trung vào Long IC.

Nhìn vào đồ thị lợi nhuận của Long IC cho thấy: 

- Trade sẽ lời (phần màu xanh) nếu cổ phiếu dao động đủ mạnh về 1 hướng nào đó (up or down), vượt ra khỏi vùng màu đỏ như hình. 
- Trade sẽ lỗ nếu cổ phiếu đứng yên hoặc dao động không đủ mạnh để thoát ra khỏi phạm vi (màu đỏ). Nhưng phần lỗ là có kiểm soát.

Cách thiết kế Long IC như sau, bạn chọn Expiration Date phù hợp (khoảng thời gian bạn nghĩ sẽ có biến động) rồi tiến hành:

> Buy 1 Call OTM (Near ATM)
> Sell 1 Call OTM (Higher)
> Buy 1 Put OTM (Near ATM)
> Sell 1 Put OTM (Lower)

##### Ví Dụ

Cổ phiếu #BKKT đang có giá $9, nếu phỏng đoán trong tuần sau #BKKT sẽ dao động (lên hoặc xuống), bạn chọn ngày đáo hạn là Dec 31, và thiết kế Long IC như sau:

> Buy 1 Call OTM (Near ATM), Strike = 10
> Sell 1 Call OTM (Higher), Strike = 11
> Buy 1 Put OTM (Near ATM), Strike = 8
> Sell 1 Put OTM (Lower), Strike = 7

![Long IC](/img/uploads/screen-shot-2021-12-20-at-5.03.45-pm.png "Long IC")

Kết quả:

- Tổng vốn bỏ ra là $45 (cũng là số tiền lỗ tối đa). Cắt lỗ nếu Loss = 50%-70%, nghĩa là nếu chỉ còn 1-2 ngày nữa là tới Dec 31st mà #BKKT vẫn lưng chừng xấp xỉ $9 thì cắt không thương tiếc.

- Lợi nhuận tối đa của trade là $55, lời khi #BKKT tăng lên > 10.5 hoặc giảm dưới < 7.5

- Khác với Iron Butterfly, Iron Condor cho tỷ lệ risk-reward tốt hơn (xấp xỉ 1-1), nhưng xác suất thành công thấp hơn phương pháp Iron Butterfly. Tuy nhiên, xác suất này vẫn cao so với những phương pháp khác.

- Luôn có sự bù trừ giữa Lợi nhuận và Xác suất. Xác suất càng cao thì lợi nhuận khả dĩ càng thấp và ngược lại. Nên những trade như thế này tuy có lợi nhuận thấp nhưng xác suất thành công lại cao (dễ thắng). Dĩ nhiên bạn có thể làm 10 contracts thì con số lợi nhuận khả dĩ sẽ là $550. Lưu ý, dù lời hay lỗ bạn nhớ đóng trade trước hoặc trong ngày đáo hạn để khỏi rắc rối về kích hoạt hợp đồng.

- Cổ phiếu công nghệ nói chung và #BKKT nói riêng thời gian qua dao động khá mạnh nên việc #BKKT tăng lên 10.5 hay giảm dưới 7.5 trước cuối năm theo mình là không quá khó để hình dung. 

##### Kết Luận

Trade như thế này được cho là an toàn và phù hợp với điều kiện thị trường hiện tại. Nếu không biết thị trường sẽ tăng hay giảm nhưng biết là sẽ có ‘biến’ thì Long IC là một cách kiếm tiền cà phê nhẹ nhàng.

Nếu bạn có nhiều vốn hơn thì có thể áp dụng tương tự với những cổ phiếu mắc hơn và dễ biến động hơn như: #TSLA, #FB, #NVDA.