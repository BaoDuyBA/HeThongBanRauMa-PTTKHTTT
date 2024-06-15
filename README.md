TRƯỜNG ĐẠI HỌC SÀI GÒN
KHOA CÔNG NGHỆ THÔNG TIN

BÁO CÁO MÔN PHÂN TÍCH THIẾT KẾ VÀ HỆ THỐNG THÔNG TIN
ĐỀ TÀI:
QUẢN LÝ CỬA HÀNG BÁN NƯỚC RAU MÁ
Giảng viên hướng dẫn: Phan Nguyệt Minh
1.	Nguyễn Lê Bảo Duy - 3121410120	
2.	Nguyễn Thùy Duyên - 3121410127	
3.	Võ Hồ Ngọc Trâm - 3121410518	
4.	Nguyễn Anh Tuấn - 3120410587	
        Nhóm thực hiện 28
  	
PHẦN I: GIỚI THIỆU HỆ THỐNG
Mô tả tổng quát về hệ thống sẽ xây dựng
	Trong đồ án, chúng em xây dựng các biểu đồ mô hình về hệ thống quản lý một cửa hàng bán nước rau má với các nghiệp vụ liên quan như mua hàng, quản lý tồn kho, doanh thu, …
Lý do chọn đề tài
	Hiện nay, mọi ngành nghề đang phát triển công nghệ hóa với tốc độ chóng mặt. Để một doanh nghiệp có thể phát triển chính mình trong hiện tại và tương lai cần có một hệ thống rõ ràng và chặt chẽ, kể cả một cửa hàng bán nước rau má cũng vậy. Chúng em quyết định chọn đề tài quản lý cửa hang bán nước rau má vì muốn hiểu hơn về cơ cấu và cách hoạt động bên trong những cửa hàng này.
Các chức năng hoạt động của hệ thống
-	Theo dõi ghi nhận quá trình thực hiện đơn hang
-	Quản lý thông tin khách hàng.
-	Quản lý thông tin kho, thông tin xuất/nhập kho, báo cáo tồn kho.
-	Báo cáo thống kê doanh thu.
Đối tượng sử dụng hệ thống
-	Nhân viên cửa hàng
-	Quản lý cửa hàng
Các công việc cần thực hiện trong đồ án
-	Mô tả bài toán của dự án
-	Lập bảng kế hoạch 
-	Khảo sát hệ thống 
-	Vẽ các sơ đồ: BFD, ERD, DFD (mức 0, mức 1, mức 2, mức 3)
-	Thiết kế lược đồ cơ sơ dữ liệu, bảng mô tả thuộc tính
-	Thiết kế xử lý
-	Thiết kế giao diện
Khảo sát hệ thống
-	Lặp bảng câu hỏi
STT	Câu hỏi	Trả lời
I.	Thông tin chung	
1.	Các cách thức sử dụng để đặt hàng hiện tại của cửa hàng ( tỷ lệ % của các cách thức này)?	
	o	Điện thoại	40%
	o	Đến mua trực tiếp tại cửa hàng	60%
	o	Phương thức khác (nếu có hãy mô tả)?	Không có
2.	Đơn đặt hàng (ĐĐH) được xử lý/tiếp nhận ở đâu?	
	o	Bàn giao dịch	Máy Ipos
	o	Tiếp nhận và xử lý	Nhân viên dùng điện thoại ở cửa hàng và bấm trên máy Ipos
	o	Nơi khác (Hãy miêu tả nếu có)	Không có
3.	Cửa hàng có gửi bản xác nhận (xác nhận đã xét duyệt, số lượng duyệt ,…) của ĐĐH cho khách hàng không?	Có
4.	Cửa hàng sẽ giao hàng ngay lập tức khi hàng hoá đáp ứng nhu cầu của ĐĐH?	Có
5.	Tất cả các ĐĐH sẽ đựơc lưu trữ lại sau khi đã giao hàng và lập hoá đơn	Có
6.	Số lượng nhân viên bán hàng của cửa hàng hiện nay? Tốc độ dự đoán phát triển(về số lượng) hàng năm là bao nhiêu?	4 nhân viên . Không thay đổi số lượng hàng năm
7.	Nhân viên bán hàng của cửa hàng đại diện cho:	
STT	Câu hỏi	Trả lời
	o	Cửa hàng	
	o	Theo vùng địa lý	
	o	Cả 2 trường hợp trên	Có
	o	Trường hợp khác (nếu có hãy nếu rõ)	Không có
8.	Cửa hàng có chuẩn bị hoá đơn sẵn hay không(chẳng hạn để cho trường hợp bán hàng thanh toán bằng tiền  mặt ngay)?	Nếu khách hàng đặt onl khi ship tới thì nhân viên sẽ bấm món và xuất hóa đơn theo thông tin hóa đơn của KH trên web hoặc nếu KH mua mang về thì nhân viên sẽ bấm món KH chọn sau đó xuất hóa đơn và thanh toán = tiền mặt.
9.	Trong trường hợp bán hàng mà khách hàng thanh toán bằng tiền mặt ngay thì cách ghi nhận và lưu giữ sẽ như thế nào?	Bấm hóa đơn và thu ngân sẽ đưa hóa đơn cho KH và yêu cầu KH phải thanh toán
10.	Cửa hàng có các hình thức thanh toán nào?	Tiền mặt , quét mã , thanh toán onl
11.	Cửa hàng có áp dụng hình thức ĐĐH trả trước?	Có
12.	Điểm giao hàng là một thông tin yêu cầu phải có trong một ĐĐH?	Có
13.	Hãy miêu tả tổng quan về hệ thống bán hàng hiện tại của cửa hàng?	Hệ thống bán mang về , bán onl
	o	Hóa đơn bán hàng	Có xuất hóa đơn bán hàng
	o	Kế toán phải thu	Có thu tiền , còn thanh toán onl thì tiền sẽ được gửi vào tài khoản ngân hàng của cửa hàng
14.	Hãy giải thích một số thông tin sau của một ĐĐH?	
STT	Câu hỏi	Trả lời
	o	Quản lý ĐĐH sẽ dựa trên part number hay theo một mã số nào đó?	Sẽ dựa trên part number của mang về hoặc nếu mua onl thì sẽ dựa trên số mã đơn của đơn vị vận chuyển.
	o	Ngày đến hạn của ĐĐH được chỉ định như thế nào?	Không có.
15.	ĐĐH được thể hiện trên ĐH như thế nào ?	Theo hóa đơn
16.	ĐĐH được nhận (chấp nhận ) và xử lý ở những điểm nào (kho, phòng bán hàng,…), có bao nhiêu điểm như vậy?	Nhận trên điện thoại , xử lý trên máy Ipos
17.	Quá trình nhận ĐĐH hiện tại được tự động hoá đến mức độ nào?	KH có thể đặt trên web
18.	Ngày nhận hàng của một ĐĐH được xác định như thế nào?	Xác định dựa trên thời gian và địa điểm  và khoàng cách của shipper tới cửa hàng và từ cửa hàng đến vị trí của KH . Nếu khách đến tiệm thì nước sẽ đc giao tới sau khi đơn hàng đc xác nhận
19.	Hoá đơn bán hàng được chuyển vào bộ phận kế toán phải thu ra sao?	Phải lưu thông tin hoá đơn vào sổ theo dõi doanh thu hằng ngày.
II.	Giá bán hàng	
1.	Cách định giá bán sản phẩm (giá bán sẽ cố định hay mềm dẻo theo một công thức hay chính sách nào đó)?	Cố định
2.	Cửa hàng có áp dụng các chính sách giảm giá (giá khuyến mãi) không?	Có
III.	Các phí liên quan	
1.	Hãy liệt kê các hình thức giao hàng cho một ĐĐH?	Nếu mua tại cửa hàng thì sẽ giao hàng tận tay cho KH . Nếu đặt onl thì shipper sẽ giao tới chỗ KH 
STT	Câu hỏi	Trả lời
2.	Cước phí thanh toán theo hình thức nào?	Trả trước
3.	Việc lựa chọn nước được thực hiện trước hay khi có ĐĐH?	KH lựa chọn nước trước
IV.	Mức độ / Số lượng	
1.	Số lượng nhân viên bán hàng của cửa hàng?	4 nhân viên

PHẦN II: Phân tích
1. Mô tả bài toán 
“Má Xanh” là một chuỗi hệ thống rau má lớn với nhiều cửa hàng nằm ở vị trí đắt địa giúp mọi người có thể tìm thấy “Má Xanh” dễ dàng hơn. Đồng thời “Má Xanh” còn là hệ thống phục vụ khách hàng những sản phẩm về rau má tươi sạch của địa phương với cam kết chất lượng rau má luôn tươi mới. 
Những cửa hàng của “Má Xanh” luôn sạch sẽ và bảo đảm an toàn vệ sinh giúp khách hàng có những trải nghiệm tốt nhất và yên tâm về chất lượng rau má của “Má Xanh”. Cùng với dịch vụ tận tâm và chuyên nghiệp, “Má Xanh” luôn phục vụ khách hàng mang về và khách hàng đặt mua nước trực tuyến. Đây là hai đối tượng chính mà “Má Xanh” hướng đến giúp doanh số thu được đều dựa vào lượng khách hàng này.
1.1.	 Khâu mua hàng:
Cửa hàng sẽ yêu cầu nhập các mặt hàng khác nhau từ các đại lí khác nhau theo phiếu yêu cầu của cửa hàng theo bộ phận pha chế yêu cầu. Các mặt hàng nhập về được kiểm tra chất lượng có đạt yêu cầu hay không - nếu đạt thì nhập về kho. Đối chiếu phiếu yêu cầu mua hàng của cửa hàng, nhân viên pha chế sẽ tiến hành ghi hoá đơn nhập hàng, chuyển cho bộ phận kế toán và lưu vào sổ theo dõi hàng. Nếu không đạt yêu cầu thì gửi đơn phản hồi cho đại lý, nếu đạt thì bộ phận kế toán sẽ viết phiếu chi thanh toán.
1.2.	 Khâu bán hàng:
Khi khách vào cửa hàng sẽ được bộ phận phục vụ gửi Menu để khách hàng lựa chọn loại rau má, khách hàng phải thanh toán sau khi chọn món và nhận hóa đơn tính tiền ngay sau đó. Tên đồ uống sẽ được nhân viên phục vụ in ra tem, dán lên ly và chuyển cho bộ phận pha chế. Căn cứ vào yêu cầu của khách hàng, bộ phận pha chế sẽ pha đồ uống cho khách và bộ phận phục vụ có trách nhiệm chuyển đồ uống đến tay khách hàng. Cuối cùng bộ phận kế toán phải lưu thông tin hóa đơn vào sổ theo dõi doanh thu hằng ngày. Cuối ngày, kế toán trưởng sẽ tổng hợp doanh thu của ba ca trực (sáng, trưa, chiều).
2.	Sơ đồ chức năng BFD
3.	Sơ đồ ERD
4.	Sơ đồ DFD
Mức 0
Mức 1
Mức 2
Mức 3
 

PHẦN III: Thiết kế
1.	Thiết kế CSDL
-	Lược đồ CSDL quan hệ
-	Thiết kế xử lý:
o	Quản lý thông tin sản phẩm: Hệ thống sẽ cung cấp chức năng cho người dùng quản lý thông tin sản phẩm như thêm, xóa, sửa, tìm kiếm thông tin sản phẩm. Đồng thời hệ thống cũng sẽ phải kiểm soát tồn kho của cửa hàng và đưa ra cảnh báo khi sản phẩm sắp hết hàng hoặc quá hạn sử dụng.
o	Quản lý thông tin khách hàng: Hệ thống sẽ cho phép quản lý thông tin khách hàng như thêm, xóa, sửa, tìm kiếm thông tin khách hàng, lịch sử mua hàng của khách hàng. Ngoài ra, hệ thống cũng cần hỗ trợ việc gửi email, SMS hoặc thông báo để thông báo về các khuyến mãi, chương trình giảm giá mới cho khách hàng.
o	Quản lý bán hàng: Hệ thống sẽ cho phép người dùng tạo đơn đặt hàng, quản lý đơn đặt hàng, tạo hóa đơn bán hàng, quản lý hóa đơn bán hàng và lập báo cáo doanh thu. Hệ thống cũng cần hỗ trợ việc thanh toán bằng nhiều phương thức khác nhau như tiền mặt, chuyển khoản, thẻ tín dụng/debit và hỗ trợ quản lý các giao dịch bán hàng trực tuyến.
o	Quản lý chương trình khuyến mãi: Hệ thống cần hỗ trợ việc quản lý và theo dõi các chương trình khuyến mãi của cửa hàng, bao gồm giảm giá sản phẩm, tặng quà tặng, quà tặng khách hàng thân thiết.
o	Quản lý giao hàng: Hệ thống cần hỗ trợ việc quản lý các phiếu giao hàng, theo dõi trạng thái giao hàng và thông tin vận chuyển. Đồng thời, hệ thống cũng cần hỗ trợ cập nhật thông tin giao hàng vào hóa đơn bán hàng và cho phép người dùng tạo phiếu thu tiền khi giao hàng.
-	Thiết kế giao diện

PHẦN IV: Cài đặt – Kiểm thử
Chưa hoàn thiện
PHẦN V: Kết luận – Hướng mở rộng
1.	Nhận xét và kết luận
-	Sau một học kì chúng em đã hoàn thành đồ án đúng hạn , chúng em đã làm được các mặt yêu cầu về phân tích thiết kế một hệ thống quản lý như : phân tích dữ liệu bằng sơ đồ BFD , ERD và DFD , thiết kế được một hệ thống dữ liệu , thiết kế giao diện . Tuy nhiên , các sơ đồ BFD , ERD và DFD vẫn chưa được trọn vẹn lắm.
-	Do năng lực còn hạn chế nên bài báo cáo còn nhiều thiếu sót, mong nhận được ý kiến đóng góp của cô để bài báo cáo hoàn thiện hơn nữa.
2.	Ưu điểm và nhược điểm của hệ thống
-	Ưu điểm: 
o	Tăng hiệu quả quản lý: Hệ thống giúp bạn quản lý việc nhập kho, xuất kho và quản lý doanh thu bán hàng một cách hiệu quả, giúp tiết kiệm thời gian và công sức.
o	Cải thiện chính xác và độ chính xác: Hệ thống giúp cập nhật số lượng tồn kho và doanh thu bán hàng một cách nhanh chóng và chính xác, đưa ra các quyết định kinh doanh chính xác và phù hợp hơn. 
o	Tăng tính minh bạch: Hệ thống giúp theo dõi hoạt động kinh doanh của mình một cách minh bạch và chi tiết hơn, từ đó đưa ra các quyết định tốt hơn.
o	Giúp quản lý chi phí hiệu quả: Hệ thống giúp quản lý chi phí một cách chặt chẽ hơn, từ đó tối ưu hóa nguồn lực và giảm thiểu chi phí.
-	Nhược điểm:
o	Phụ thuộc vào công nghệ: Hệ thống này phụ thuộc vào công nghệ, nếu có sự cố về mạng hoặc hệ thống, nó có thể gây ra gián đoạn hoặc tạm ngừng hoạt động. 
o	Chi phí đầu tư ban đầu: Để xây dựng một hệ thống thông tin quản lý chất lượng cao, sẽ phải đầu tư một khoản tiền lớn ban đầu. 
o	Đào tạo nhân viên: Để sử dụng hệ thống thông tin quản lý, nhân viên của sẽ cần được đào tạo và hướng dẫn, từ đó sẽ tốn thêm chi phí và thời gian.
3.	Hướng phát triển
-	Tăng tính linh hoạt: Cải thiện tính linh hoạt của hệ thống để có thể dễ dàng thích ứng với các thay đổi trong hoạt động kinh doanh của bạn.
-	Thêm các chức năng gợi cách sử dụng trong chương trình
-	Tối ưu hóa hệ thống: Tối ưu hóa hệ thống để nó hoạt động nhanh hơn và hiệu quả hơn. 
-	Cập nhật thường xuyên: Đảm bảo rằng hệ thống được cập nhật thường xuyên với các bản vá lỗi và tính năng mới để đảm bảo rằng nó luôn hoạt động tốt và đáp ứng được các yêu cầu của doanh nghiệp.
-	Nâng cao tính bảo mật: Tăng cường tính bảo mật của hệ thống để đảm bảo an toàn thông tin.
4.	Phân công công việc
 
ĐIỂM ĐỒ ÁN: 7
