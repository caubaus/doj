---
layout: post
type: option
title: "Long Call Option"
subtitle: "Option Basics 1"
author: Trinh Nguyen Ba
background: '/img/posts/option-basic-1/option-basic-1.png'
---

#### Khái quát

Long Call Option

> - Long: nghĩa là Mua.

> - Call Option: là Quyền được thâu tóm một Cổ Phiếu nào đó.

> - Khi bạn “Long Call Option” là bạn mua một cái quyền (nhưng không phải nghĩa vụ) được thâu tóm một cổ phiếu nào đó (Ví dụ: cổ phiếu #SOFI), ở một mức giá nào đó do chính bạn chọn, gọi là Strike Price (Ví dụ: Strike = $20), tại một thời điểm nào đó trong tương lai cũng do chính bạn chọn (gọi là ngày đáo hạn, Expiration Date).

#### Chi Tiết

Tuỳ thuộc vào việc bạn Strike ở giá nào và ngày đáo hạn là ngày nào mà Call Option sẽ có giá khác nhau. Giá của Call Option là số tiền bạn phải bỏ ra để mua cái “Quyền thâu tóm” này (còn được gọi là Premium). Thường thì Strike càng thấp thì giá Call Option (Premium) càng cao. Và nếu ngày đáo hạn càng xa thì giá Call Option (Premium) cũng càng cao, nếu bạn chọn ngày đáo hạn xa trên 6 tháng, thì Call Option này còn được gọi là LEAPs Call (LEAPs Call rất an toàn dành cho đầu tư dài hạn).

> - Nếu bạn chọn giá Strike Price < giá hiện tại của Stock #SOFI (Spot Price): thì Call Option này được gọi là In-The-Money Call Option (ITM)

> - Nếu bạn chọn giá Strike Price > giá hiện tại của Stock #SOFI: thì Call Option này gọi là Out-The-Money Call Option (OTM)

> - Sau cùng, nếu chọn giá Strike Price = giá hiện tại của Stock #SOFI: thì được gọi là At-The-Money Call Option (ATM)

#### Tóm tắt
![option-basic-1](/img/posts/option-basic-1/option-basic-1-summary.png)

#### Ví dụ

Lấy ví dụ là cổ phiếu #SOFI, hiện đang có giá vào khoảng $21 cho một cổ phiếu. Giả sử bạn quyết định mua 1 Call Option trên cổ phiếu này, với Strike = $20, và có ngày đáo hạn là ngày APR 14th 2022 (khoảng 6 tháng kể từ hôm nay). Call Option này sẽ có giá Premium vào khoảng $3.50. Điều này có nghĩa là:

> - Bạn vừa bỏ ra $3.50 để mua một cái Quyền được thâu tóm 1 cổ phiếu #SOFI ở mức giá $20/cp, và bạn có thể kích hoạt quyền này bất kỳ lúc nào, kể từ hôm nay cho đến hết ngày APR 14th 2022, mà không cần quan tâm giá của #SOFI trên thị trường sẽ tăng hay giảm.

> - Giả sử tới trước ngày APR 14th 2022 mà cổ phiếu #SOFI đã tăng lên tới $30, thì bạn vẫn có Quyền thâu tóm lại cp này với giá chỉ $20. Nghĩa là bạn đã lời $10. 

> - Nhưng chắc bạn còn nhớ mình đã bỏ ra $3.50 để mua cái Quyền này, nên trừ ra thì bạn chỉ còn lời khoảng $10 — $3.50 = $6.50 cho mỗi cổ phiếu. 

> - Lại phải nói thêm, thường là mỗi Call Option sẽ chi phối 100 cổ phiếu. Nghĩa là, bạn phải bỏ ra những $350 để mua Call Option như trên, và bạn sẽ có Quyền thâu tóm 100 cổ phiếu #SOFI ở giá $20/cp. Theo như giả sử như trên, nếu tới trước ngày APR 14th 2022 mà #SOFI đã tăng lên tới $30/cp, thì tiền lời của bạn sẽ là $650.

#### Rủi ro

Tất nhiên, lợi nhuận cao cũng sẽ đi kèm với rủi ro nhất định. Rủi ro của Call Option dạng này là nếu cổ phiếu không tăng hoặc giảm trong thời gian từ hôm nay tới ngày đáo hạn, thì Call Option này sẽ mất giá trị. Và càng sát tới ngày đáo hạn thì tốc độ "mất giá trị" của Call Option càng nhanh.

> - Trong ví dụ của #SOFI ở trên, điểm hoà vốn của bạn là $23.50 (= giá Strike + Premium)

> - Nếu tới ngày đáo hạn APR 14th 2022 mà cổ phiếu #SOFI vẫn ở dưới mức $20 thì Call Option này trở nên vô giá trị (nghĩa là mất sạch).

> - Nhưng nếu #SOFI đóng ở giá từ $20 đến $23.50 thì Call Option bị lỗ (nhưng không mất trắng như trường hợp trên).

> - Nếu #SOFI đóng trên $23.50 thì là bạn lời (như giả sử phía trên).

Chính vì vậy mà bạn nên chọn ngày đáo hạn tương đối xa, thường là nên chọn trên 6 tháng để có đủ thời gian cho cổ phiếu tăng tới giá trị hoà vốn hoặc vượt lên giá hoà vốn. Những Call Option có ngày đáo hạn xa như vậy được gọi là LEAP Call. 

> - Trong trường hợp #SOFI này thì vận dụng LEAP Call để đầu tư dài hạn là khá an toàn, vì khả năng cao là giá #SOFI sẽ vượt lên trên con số $23.50 tới trước ngày APR 14th 2022.

Tham khảo: *Trading Options Greeks: How Time, Volatility, and Other Pricing Factors Drive Profits* by Dan Passarelli

Chú thích (Disclaimer):
*Bài viết chỉ mang mục đích giáo dục và giải trí, hoàn toàn không có giá trị như một lời khuyên về đầu tư (Not Financial Advice).*
*Các bài viết trên Streetone.org (ngoài những bài có trích nguồn) là sản phẩm của Streetone.org, xin vui lòng dẫn nguồn nếu chia sẻ nơi khác (Please cite us).*