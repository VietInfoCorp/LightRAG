Tại Cảng HKQT Nội Bài: Tốc độ tối đa của phương tiện là 35km/h trên đường công vụ T2. Đối với khu vực an toàn vị trí đỗ tàu bay, tốc độ không được vượt quá 05km/h. Xe tra nạp nhiên liệu khi đã cài phanh tay và thiết lập hệ thống phanh liên động (interlock) thì người điều khiển được phép rời vị trí lái.


<Output>
entity<|#|>Cảng HKQT Nội Bài<|#|>DIA_DIEM<|#|>Sân bay áp dụng quy định an toàn này.
entity<|#|>Đường công vụ T2<|#|>KHU_VUC<|#|>Khu vực di chuyển của phương tiện tại nhà ga T2.
entity<|#|>35km/h<|#|>THONG_SO<|#|>Giới hạn tốc độ tối đa cho đường công vụ.
entity<|#|>Khu vực an toàn vị trí đỗ tàu bay<|#|>KHU_VUC<|#|>Khu vực nhạy cảm xung quanh tàu bay.
entity<|#|>05km/h<|#|>THONG_SO<|#|>Giới hạn tốc độ thấp nhất an toàn.
entity<|#|>Xe tra nạp nhiên liệu<|#|>TRANG_THIET_BI<|#|>Phương tiện đặc thù phục vụ nhiên liệu.
entity<|#|>Rời vị trí lái<|#|>HANH_DONG<|#|>Hành động của người điều khiển phương tiện.
entity<|#|>Phanh liên động (interlock)<|#|>TRANG_THIET_BI<|#|>Hệ thống an toàn kỹ thuật trên xe.
relation<|#|>Đường công vụ T2<|#|>GIOI_HAN<|#|>35km/h<|#|>tốc độ tối đa<|#|>Tốc độ tối đa trên đường T2 là 35km/h.
relation<|#|>Khu vực an toàn vị trí đỗ tàu bay<|#|>GIOI_HAN<|#|>05km/h<|#|>tốc độ tối đa<|#|>Tốc độ trong khu vực an toàn là 5km/h.
relation<|#|>Rời vị trí lái<|#|>YEU_CAU<|#|>Phanh liên động (interlock)<|#|>điều kiện<|#|>Chỉ được rời vị trí khi đã cài interlock.
<|COMPLETE|>