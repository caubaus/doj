---
layout: post
type: option
title: Long Straddle
subtitle: Long Straddle (Long Volatility)
author: A3
background: /img/uploads/246891547_10217000709288296_4484276565697201193_n.jpeg
date: 2021-12-10T21:28:14.534Z
---
##### Khái Niệm

- Long Straddle là một phương pháp bắt trend (xu hướng) và chớp lấy sự tăng tốc (momentum) của giá cổ phiếu bằng công cụ Options.

- Người ta sử dụng phương pháp này khi họ có nhận định cổ phiếu có thể sẽ biến động mạnh (lên hoặc xuống) trong thời gian sắp tới.

##### Chi Tiết

- Nhìn vào Đồ thị P/L, dễ dàng nhận thấy trade này sẽ sinh lời nếu giá cổ phiếu tăng mạnh hoặc giảm mạnh trước khi hết ngày đáo hạn (phần màu xanh).

- Trong trường hợp, cổ phiếu không dao động mạnh (chỉ tăng giảm nhẹ trong một phạm vi nhỏ) thì trade này sẽ thất bại. Nhưng phần tiền lỗ là giới hạn (lỗ tối đa bằng đúng số tiền bỏ ra để mua Call và mua Put Options.

- Đây là một phương pháp Option kinh điển cho những người muốn đặt cược vào một sự kiện nào đó trong tương lai (Event Study) và tin rằng sự kiện đó sẽ tạo ra dịch chuyển mạnh đối với giá cổ phiếu. Một số sự kiện tiêu biểu như: Earning Report, Exercutive Election, Product Announcement, Polictical Election vv...

- Implied Volatility (IV) cũng là chỉ số quan trọng trong phương pháp, bạn nên kích hoạt Trade khi thị trường đang có IV thấp (ví dụ: 1 tuần trước ngày xảy ra sự kiện), vì Trade này có thể hiểu là bạn đang Long Volatility.

- Một thí dụ: Apple #AAPL (giá hiện tại: $148) sẽ có Earning Report vào thứ 4 tuần này (Oct 27th). EPS Estimate là $1.24. Với việc Apple vừa cho ra mắt dòng iPhone 13 và thế hệ MacBook mới thì có lẽ một số người nhân định ER Report này sẽ là sự kiện quan trọng và có thể làm biến động giá cổ phiếu #AAPL.

- Nếu bạn cũng chung nhận định với họ, và muốn kiếm lợi từ sự biến động này (lên hoặc xuống) thì có thể thử phương pháp Straddle như sau:

// - Buy 1 Call #AAPL, Strike: 150, Exp: Oct 29th 2021, với giá $1.80
// - Buy 1 Put #AAPL, Strike: 150, Exp: Oct 29th 2021, với giá $3.10

- Tổng số vốn bạn bỏ ra sẽ là: $4.90 (tương đương $490 cho 100 shares)

- Endgame của trade này như sau:
// - Trade này có 2 điểm hoà vốn: 146.9 và 151.8
// - Nếu tới trước ngày Oct 29th mà giá #AAPL đã giảm dưới 146.9 hoặc tăng lên trên 151.8 thì bạn lời (nhớ chốt lời).
// - Nếu tới hết ngày Oct 29th mà giá #AAPL chỉ quanh quẩn nằm từ 146.9 tới 151.8 thì bạn lỗ.
// - Con số lỗ tối đa là $490, nhưng khả năng lỗ hết $490 là rất thấp (vì để xảy ra trường hợp này, giá #AAPL phải đóng đúng $150 vào cuối ngày Oct 29th), bạn có thể hiểu rằng con số lỗ thường sẽ < $490, lỗ bao nhiều còn tuỳ vào giá chính xác của #AAPL vào ngày ấy. Nhưng bạn nên có biện pháp cắt lỗ khi tới một hạn mức nào đó chứ đừng để lỗ quá 50%.

##### Lời Kết

- Phương pháp Straddle như trên rất hữu dụng cho việc “đánh” vào momentum (gia tốc) và trend (xu hướng) của thị trường theo sau một sự kiện quan trọng nào đó. Phương pháp này cần thời gian luyện tập và thử nghiệm nhiều lần. Mình lấy #AAPL làm ví dụ để bạn dễ hiểu, nhưng vẫn khuyên bạn hãy luyện tập nó với những cổ phiếu có giá rẻ hơn hoặc tốt nhất là thử với tiền giả trước.