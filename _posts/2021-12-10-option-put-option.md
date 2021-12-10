---
layout: post
type: option
title: Long Put Option
subtitle: Long Put (Bullish Trade)
author: A3
background: /img/uploads/240525049_10216789992460507_4666442444156741978_n.jpeg
date: 2021-12-10T21:15:48.051Z
---
##### Khái Niệm

* Put Option là một cái quyền (nhưng không phải nghĩa vụ) được phép bán (thanh lý) một cổ phiếu nào đó (Underlying Asset) ở một mức giá nào đó (Strike Price) trước một thời hạn nào đó (Expiration Date).

##### Chi Tiết

* Khi bạn Mua một Put Option (Long Put) trên cổ phiếu #ABC (với Strike là K, ngày đáo hạn ví dụ là 12/17/2021) thì có nghĩa là bạn mua cái quyền được bán cổ phiếu #ABC này với mức giá bán là $K và bạn có thể thực hiện quyền này bất kỳ lúc nào từ hôm nay cho đến ngày đáo hạn 12/17/2021.

![Long Put](/img/uploads/240525049_10216789992460507_4666442444156741978_n.jpeg "Long Put")

* Lấy ví dụ cụ thể với #NIO đi. Giá của #NIO tại thời điểm này là khoảng $40/cp.
  Giả sử bạn mua một cái Put Option trên cổ phiếu #NIO, với Strike: $50, Expiration Date: 12/17/2021.
* Vì là bạn mua cái quyền bán (mà không phải nghĩa vụ) nên bạn phải trả một số tiền cho “cái quyền” này, số tiền đó gọi là Premium (hay còn gọi là Cost). Giả sử Premium cho cái Put Option trên đang là: $12/contract.
  Như vậy, từ hôm nay tới trước ngày 12/17/2021, bạn có quyền bán cổ phiếu #NIO của bạn với mức giá bán là $50/share mà không cần quan tâm giá #NIO trên thị trường là bao nhiêu.
* Giả sử trong túi bạn đã có sẵn 1 cổ phiếu #NIO đi, dĩ nhiên bạn sẽ không kích hoạt “quyền bán” ngay hôm nay, vì bạn đã phải bỏ ra những $12 để mua cái quyền này. Nên nếu bạn kích hoạt quyền bán, bạn sẽ bán #NIO cho người ta với giá $50, trừ đi $12 tiền Premium mua cái quyền đó thì bạn còn lại chỉ $38. Trong khi bạn có thể bán cổ phiếu #NIO ngay trên thị trường chứng khoán với giá $40/cp (nhiều hơn $2).
  Nghĩa là việc bạn kích hoạt “quyền bán” ngay hôm nay sẽ làm cho bạn mất đi $2 trong nước mắt và tiếc thương.
* Như vậy, bạn chỉ nên kích hoạt “quyền bán” nếu giá #NIO trên thị trường giảm thấp hơn con số $50 - $12 = $38 (giá Strike trừ cho giá Premium). Nói cách khác, con số hoà vốn của bạn là $38, nếu trước ngày đáo hạn #NIO giảm về dưới $38 là bạn có lời, còn nếu quá ngày đáo hạn mà #NIO vẫn ở trên $38 thì bạn lỗ.
  Hơn nữa, khi bạn có lời thì bạn cũng không nhất thiết phải kích hoạt “quyền bán” của mình để “chốt lời”, mà bạn có thể bán lại Put Option đó cũng chốt lời được.
  Để cho dễ hiểu, giả sử một tuần sau giá #NIO trên thị trường là $35 đi. Nếu kích hoạt quyền bán của mình, bạn sẽ bán #NIO với giá Strike $50, trừ cho phí Premium ($12) thì thu về được $38, rồi bạn ra thị trường mua lại ngay cổ phiếu #NIO vừa bán đó với giá trị trường (lúc này đang là $35) thì con số sau cùng là lời được $38 - $35 = $3.
* Nhưng thay vì phải làm dài dòng như vậy, bạn cứ bán luôn cái Put Option đó cho người khác, lúc này giá Put Option sẽ vào khoảng $15/contract. Bạn mua nó ban đầu với giá $12, giờ bán với giá $15 thì cũng là lời $3, và cổ phiếu #NIO của bạn vẫn nằm im trong tài khoản của bạn. (Thông thường người ta sẽ thực hiện cách này để hạn chế kích hoạt hợp đồng, vì đôi khi bạn phải trả một ít phí giao dịch cho việc kích hoạt này hoặc nếu bạn không có sẵn cổ phiếu #NIO để bán thì cũng không nên "kích hoạt").
* Trong trường hợp tới ngày đáo hạn mà #NIO vẫn ở trên $38 (con số hoà vốn) thì bạn sẽ lỗ. Lỗ bao nhiều thì còn tuỳ nhiều yếu tố, nhưng lỗ tối đa của bạn sẽ là $12 (là số tiền bạn bỏ ra mua Put Option).
  Nên thông thường, khi chơi Option, chỉ cần lỗ khoảng 50% đến 70% (như ví dụ trên thì lỗ khoảng -$6 đến -$8) là mình cắt lỗ luôn, tức là bán lại cái Put Option với giá thấp hơn giá mua. Ví dụ trên là mua $12 mà bán lại chỉ còn $6 (lỗ 50%) hoặc $4 (lỗ 70%).
* Nguyên tắc chốt lời và cắt lỗ trong Option Trading rất quan trọng, không giống với Stocks bạn có thể Hold-to-Die, chơi Option tuyệt đối phải cương quyết cắt lỗ khi cần thiết dù phải cắt trong nghẹn ngào và đắng cay. Tuyệt đối không chơi hệ tâm linh cầu may, vì Option càng gần đến ngày đáo hạn thì mất giá trị càng nhanh (gọi là Theta Decay)