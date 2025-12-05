<Input Text>
Quy trình kiểm soát tài liệu bên ngoài (V.QMS-P04) gồm các bước: Bước 1: Xác định, nhận biết tài liệu bên ngoài do Cơ quan/Chi nhánh thực hiện. Bước 2: Tiếp nhận tài liệu bên ngoài do Đơn vị liên quan thực hiện. Bước 3: Xử lý và đánh giá nội dung. Thời gian xử lý không quá 05 ngày làm việc.


<Output>
entity<|#|>Quy trình kiểm soát tài liệu bên ngoài<|#|>QUY_TRINH<|#|>Quy trình xử lý các tài liệu có nguồn gốc từ bên ngoài tổ chức.
entity<|#|>V.QMS-P04<|#|>TAI_LIEU<|#|>Mã văn bản quy định quy trình kiểm soát tài liệu.
entity<|#|>Bước 1: Xác định, nhận biết<|#|>BUOC_THUC_HIEN<|#|>Bước đầu tiên là nhận diện tài liệu.
entity<|#|>Bước 2: Tiếp nhận tài liệu<|#|>BUOC_THUC_HIEN<|#|>Bước thứ hai là tiếp nhận tài liệu về đơn vị.
entity<|#|>Bước 3: Xử lý và đánh giá<|#|>BUOC_THUC_HIEN<|#|>Bước thứ ba là đánh giá nội dung tài liệu.
entity<|#|>Cơ quan/Chi nhánh<|#|>DON_VI<|#|>Đơn vị chịu trách nhiệm thực hiện bước 1.
entity<|#|>Đơn vị liên quan<|#|>DON_VI<|#|>Đơn vị chịu trách nhiệm thực hiện bước 2.
entity<|#|>05 ngày làm việc<|#|>THONG_SO<|#|>Thời gian giới hạn tối đa để xử lý.
relation<|#|>Quy trình kiểm soát tài liệu bên ngoài<|#|>BAO_GOM<|#|>Bước 1: Xác định, nhận biết<|#|>thành phần<|#|>Quy trình bắt đầu với bước 1.
relation<|#|>Quy trình kiểm soát tài liệu bên ngoài<|#|>QUY_DINH_TAI<|#|>V.QMS-P04<|#|>nguồn<|#|>Quy trình được quy định tại tài liệu V.QMS-P04.
relation<|#|>Bước 1: Xác định, nhận biết<|#|>TIEP_THEO_LA<|#|>Bước 2: Tiếp nhận tài liệu<|#|>trình tự<|#|>Sau khi xác định xong thì chuyển sang tiếp nhận.
relation<|#|>Bước 2: Tiếp nhận tài liệu<|#|>TIEP_THEO_LA<|#|>Bước 3: Xử lý và đánh giá<|#|>trình tự<|#|>Sau khi tiếp nhận thì chuyển sang xử lý.
relation<|#|>Bước 1: Xác định, nhận biết<|#|>THUC_HIEN_BOI<|#|>Cơ quan/Chi nhánh<|#|>trách nhiệm<|#|>Cơ quan chi nhánh thực hiện bước này.
relation<|#|>Bước 3: Xử lý và đánh giá<|#|>GIOI_HAN<|#|>05 ngày làm việc<|#|>thời hạn<|#|>Việc xử lý phải hoàn thành trong 5 ngày.
<|COMPLETE|>