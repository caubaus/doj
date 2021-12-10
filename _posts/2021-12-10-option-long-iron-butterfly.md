---
layout: post
type: option
title: Long Iron Butterfly
subtitle: Long Iron Butterfly (Long Volatility)
author: A3
background: /img/uploads/265561826_10217207429816180_1605570501288726014_n.jpeg
date: 2021-12-10T21:31:46.044Z
---
![]()

##### Khái Quát

* Khi một cổ phiếu được dự báo là sẽ có dao động bởi một sự kiện nào đó thì có một phương pháp rất hay để chúng ta kiếm chút tiền Café gọi là Iron Butterfly (viết tắt là IF). Thật ra phương pháp này biến tấu từ một phương pháp khác gọi là Iron Condor (IC), nhưng mình thấy Iron Butterfly dễ hiểu hơn nên sẽ giới thiệu cái này trước, sau đó sẽ nói về IC sau nhé.

##### Khái Niệm

* Iron Butterfly là cách đánh chủ yếu nhắm vào phỏng đoán của bạn về mức độ dao động của cổ phiếu (còn gọi là Implied Volatility). Có 2 cách để sử dụng IF: Long IF & Short IF. Long IF được dùng khi bạn cho rằng giá cổ phiếu sắp tới sẽ có dao động mạnh (bất kể về hướng nào), trong khi Short IF thì dùng khi bạn nghĩ giá cổ phiếu (hiện đang dao động) sẽ sớm “sóng yên biển lặng”.
* Bài viết này mình tập trung vào Long IF, vì dự đoán sắp tới thị trường sẽ có dao động, nên nó còn được gọi là Long Volatility.

![](/img/uploads/265561826_10217207429816180_1605570501288726014_n.jpeg)

* Nhìn vào chart P/L của Long IF bạn thấy trade này sẽ lời (phần màu xanh) khi giá của cổ phiếu dao động đủ mạnh về 1 trong 2 hướng (tăng hoặc giảm). Nôm na là, bạn sẽ hy vọng giá cổ phiếu sẽ tăng mạnh hoặc giảm mạnh ra khỏi một phạm vi nào đó. Nhưng nếu bạn phỏng đoán sai, và giá đứng yên hoặc dao động không đủ mạnh để thoát ra khỏi phạm vi màu đỏ thì bạn lỗ. Nhưng phần lỗ là có kiểm soát.
* Cách thiết kế Long IF như sau, bạn chọn Expiration phù hợp (khoảng thời gian bạn nghĩ sẽ có dao động) rồi tiến hành giao dịch:

> * Buy 1 Call At-the-money
> * Sell 1 Call Out-the-money
> * Buy 1 Put At-the-money
> * Sell 1 Put Out-the-money

* Lấy một ví dụ, #SNAP đang có giá $52, giả sử bạn đoán tuần sau #SNAP sẽ dao động (lên hoặc xuống), bạn chọn ngày đáo hạn là Dec 17, và thiết kế Long IF như sau:

> * Buy 1 Call At-the-money, Strike = 52
> * Sell 1 Call Out-the-money, Strike = 54
> * Buy 1 Put At-the-money, Strike = 52
> * Sell 1 Put Out-the-money, Strike = 50

* Kết quả của trade này:

> * Tổng số vốn bỏ ra là $157 (cũng là số tiền lỗ tối đa, nhưng thường bạn không mất sạch đâu, chỉ mất sạch nếu như #SNAP đóng ngay chính xác giá 52 vào ngày Dec 17th). Nhưng mình sẽ cắt lỗ nếu Loss = 50%-70%, nghĩa là nếu chỉ còn 1-2 ngày nữa là tới đáo hạn mà #SNAP vẫn lưng chừng 52-53 thì mình cắt.
> * Lợi nhuận tối đa là $43, bạn thấy nó ít hơn số tiền lỗ tối đa, nhưng xác suất thành công cao hơn những trade khác. Bạn sẽ lời nếu #SNAP tăng lên > 53.50 hoặc giảm dưới < 50.50.

* Luôn có sự bù trừ giữa Lợi nhuận và Xác suất. Xác suất càng cao thì lợi nhuận khả dĩ càng thấp và ngược lại. Nên những trade như thế này tuy có lợi nhuận thấp nhưng xác suất thành công rất cao.
* Dĩ nhiên bạn có thể làm 10 trades thì con số lợi nhuận khả dĩ sẽ là 10 lần và bằng $430. Nhưng dù lời dù lỗ bạn nhớ đóng trade trước hoặc trong ngày đáo hạn để khỏi rắc rối về kích hoạt hợp đồng.
* Bạn nhìn cổ phiếu công nghệ nói chung và #SNAP nói riêng thời gian qua dao động khá mạnh (riêng #SNAP tăng giảm trong phạm vi 47-57), nếu cộng hưởng với những yếu tố chung từ thị trường công nghệ trong những ngày sắp tới, thì việc #SNAP tăng lên 53.50 hay giảm dưới 50.50 theo mình là không quá khó để hình dung.

##### Lời Kết

* Trade như thế này được cho là an toàn và phù hợp với điều kiện thị trường hiện tại, khi mà bạn lo sợ không biết thị trường tăng hay giảm nhưng biết là sẽ có 'biến' thì phương pháp này là một cách kiếm tiền nhẹ nhàng ít đau đớn.
  Nếu bạn có nhiều vốn hơn thì có thể áp dụng tương tự với những cổ phiếu mắc hơn và dễ dao động hơn như #TSLA, #FB, #NVDA. Xác xuất thành công sẽ cao hơn.