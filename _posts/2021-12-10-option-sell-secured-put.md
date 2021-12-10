---
layout: post
type: option
title: Sell Secured Put
subtitle: Short Put (Bullish Trade)
author: A3
background: /img/uploads/243480660_10216908453221952_3076735759542231685_n.jpeg
date: 2021-12-10T21:20:59.181Z
---
##### Khái Niệm

* Sell Secured Put nói nôm na là Bán hợp đồng Put Contract cho một bên khác và người bán (là chính bạn) sẽ được chi trả một số tiền gọi là Put Premium. Bạn còn nhớ khi chúng ta mua Put thì chúng ta phải trả một số tiền nào đó (gọi là Cost) nhưng bây giờ chúng ta là bên bán (Seller) nên thay vào đó chúng ta sẽ được hưởng số tiền này.
* Nhắc lại định nghĩa của Buy Put là: mua cái quyền được thanh lý một cổ phiếu nào đó (Underlying Stock), ở một mức giá nào đó (Strike Price), tại bất kỳ thời điểm nào trước ngày đáo hạn (Expiration Date). Người mua Put phải trả tiền cho người bán Put (số tiền này gọi là Cost hoặc Put Premium), cũng giống như mua bảo hiểm vậy.

##### Chi Tiết

* Như vậy, nếu đổi ngược lại, thay vì làm người mua Put, bây giờ bạn là bên bán Put Contract (giống như bạn bán bảo hiểm) thì bạn có NGHĨA VỤ (hoặc cam kết) phải mua lại cổ phiếu của đối phương (Vì họ có quyền bán nên bạn phải có nghĩa vụ mua), cũng ở mức giá Strike (K) đó, và đối phương có quyền kích hoạt hợp đồng này ở bất kỳ thời điểm nào trước ngày đáo hạn. Để bù đắp cho NGHĨA VỤ này, đối phương sẽ trả cho bạn một số tiền gọi là Put Premium (bằng đúng giá trị của Put Option ở thời điểm bạn bán).
* Nhiều người bảo rằng Sell Secured Put là phương pháp đầu tư an toàn nhất trong Options, sự thật đúng là như vậy. Người Sell Secured Put là người tin tưởng (hoặc hi vọng) giá cổ phiếu sẽ đi lên (hoặc ít nhất là không đi xuống quá sâu) là bạn đã có thể có lời.
* Khi bạn sell Put, mục tiêu của bạn là để đạt 1 trong 2 thứ sau đây:

  * Kiếm thêm tiền thu nhập thụ động (từ Put Premium)
  * Mua cổ phiểu tốt ở giá rẻ hơn giá hiện tại trên thị trường (khi hợp đồng bị kích hoạt).

![Sell Secured Put](/img/uploads/243480660_10216908453221952_3076735759542231685_n.jpeg "Sell Secured Put")

##### Ví Dụ

* \#PLTR (Palantir Technologies Inc) là doanh nghiệp về khai thác dữ liệu (Data Mining)

  * Giá cổ phiểu #PLTR vì nhiều lý do mà những ngày này đang bị rớt thảm hại xuống mức gần $24/cp.
  * Nhưng nhìn về tổng thể thì đây vẫn công ty tốt để đầu tư nếu xét về qui mô thị trường Data Mining trong tương lai.
* Giả sử mình quyết định đầu tư vào #PLTR bằng cách Sell Secured Put với:

  * Strike K = 22
  * Expiration Date: Oct 29th 2021
  * Và thu về được một số tiền (Put Premium = $0.65/cp * 100 = $65)
* Dịch sang ngôn ngữ bình dân như sau: mình đã bán một cái Put Option và có NGHĨA VỤ phải mua 100 cp #PLTR ở mức giá $22/cp bất kỳ lúc nào đối phương (người mua Put Option) muốn kích hoạt giao dịch, từ hôm nay cho tới ngày đáo hạn Oct 29th 2021. Để bù đắp cho nghĩa vụ này, đối phương trả cho mình một số tiền là $65 (Put Premium). Khi thực hiện giao dịch này, trong đầu mình đang nghĩ tới 2 viễn cảnh.

  * Nếu tới ngày Oct 29th 2021 mà giá của #PLTR đóng trên giá Strike (> $22) thì chắc chắn đối phương sẽ không kích hoạt giao dịch (vì họ có thể bán cp #PLTR trên thị trường với giá cao hơn thì ngu gì lại bán cho mình với giá có $22). Trong trường hợp này, Put Option trở nên vô giá trị, bị vất vào xọt rác và bạn cầm trong tay số tiền $65 ban đầu (cái này gọi là thu nhập thụ động - Passive Income).
  * Trường hợp thứ 2, nếu tới trước ngày Oct 29th 2021 mà cổ phiếu #PLTR đã sụt giảm sâu dưới mức Strike (<$22) (giả sử là #PLTR giảm về 20 đi) thì mình có nghĩa vụ phải mua lại cổ phiếu này ở mức giá $22.
  * Lúc này, chắc chắn đối phương sẽ kích hoạt hợp đồng và như vậy mình mua cao hơn khoảng $2 trên một cổ phiếu (so với thị trường). Tuy nhiên, mình vẫn được giữ số tiền $65 Put Premium ban đầu (là khoảng 0.65/cp), vậy bù qua sớt lại thì mình chỉ lỗ khoảng $2 - $0.65 = $1.35.
  * So sánh với việc nếu mình mua trực tiếp cổ phiếu #PLTR hôm nay (gía #PLTR hôm nay đang là $24) thì mình có lẽ đã lỗ tới $4/cp (từ 24 giảm xuống 20). Như vậy việc Sell Put đã giúp cho mình giảm thiểu rủi ro hơn nhiều so với mua cổ phiếu trực tiếp.
* Lại nói, như mình đã đề cập ban đầu, #PLTR là cổ phiếu tốt nên mình cảm thấy thoải mái để gom hàng ở giá 22 (giá Strike) nên việc Sell Put giúp cho mình xác định được mức giá mà mình muốn mua chứ không phải thấp thỏm chờ đợi thị trường.

  * Tóm lại, trường hợp tốt (giá #PLTR tăng) thì không có gì xảy ra, mình lời được số tiền Put Premium ($0.65/cp), trường hợp không tốt lắm thì mình phải mua #PLTR ở giá $22, trừ ra số tiền Put Premium (vẫn được giữ) thì thành ra mình mua #PLTR chỉ với giá $21.35 (22 trừ cho 0.65), là mức giá mà mình cảm thấy rất thoải mái để xuống tiền gom #PLTR.
* Rõ ràng là Sell Put giúp cho bạn có được thế chủ động trong việc quyết định giá tiền bỏ ra cho một cổ phiếu nào đó cũng như tạo thêm 1 kênh thu nhập thụ động nhưng rất an toàn cho chính bạn. Do đó mà phương pháp này được gọi là Sell Secured Put.
* Điểm bất lợi cần lưu ý khi Sell Put là bạn phải bỏ ra một số tiền thế chân (Collateral) khá cao, bằng với số tiền mua 100 cp ở mức giá Strike price. (Trong ví dụ trên thì Collateral sẽ là 100 * 22 = 2200). Do đó, Sell Put tuy an toàn nhưng đòi hỏi số tiền bỏ ra ban đầu khá lớn. Cần nhớ, tiền thế chân (Collateral) không bị rủi ro, nó chỉ để dùng trong trường hợp bạn bị kích hoạt hợp đồng (người ta sẽ lấy tiền này mua cp #PLTR cho bạn) nên bạn đừng sợ mất số tiền này.
* Còn nhiều yếu tố khác cần xem xét khi sử dụng phương pháp đầu tư Sell Secured Put, ví dụ như nên chọn cổ phiếu nào để Sell, chọn Strike như thế nào, Expiration ra làm sao.
* Thị trường chứng khoán tại thời điểm hiện tại khá bấp bênh và dễ gãy, nên việc đầu tư cẩn trọng rất nên được ưu tiên, Sell Put là một trong những cách đầu tư an toàn nhất lúc này. Ngoài #PLTR mình cũng vừa Sell Put thêm một số cổ phiếu khác, điểm chung của các cổ phiếu này là an toàn nhưng đang bị giảm giá khá sâu vì những biến động từ thị trường BĐS TQ, một số ví dụ như #ATVI #NIO #FB, bạn có thể tham khảo thêm.