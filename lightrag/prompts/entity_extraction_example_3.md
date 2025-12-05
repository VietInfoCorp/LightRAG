Đối với thời tiết nguy hiểm tại Tân Sơn Nhất (QT18/SGN): Khi gió mạnh từ 40 đến 59 kts, các đơn vị phải thực hiện: Chèn bánh tàu bay, Cài phanh và chằng néo tàu bay. Đồng thời, Dừng các hoạt động trên cao và Dừng tra nạp nhiên liệu.


<Output>
entity<|#|>QT18/SGN<|#|>TAI_LIEU<|#|>Quy trình cảnh báo thời tiết nguy hiểm tại Tân Sơn Nhất.
entity<|#|>Tân Sơn Nhất<|#|>DIA_DIEM<|#|>Sân bay áp dụng quy trình.
entity<|#|>Gió mạnh 40-59 kts<|#|>DIEU_KIEN<|#|>Mức độ thời tiết nguy hiểm cụ thể (Mức 2).
entity<|#|>Chèn bánh tàu bay<|#|>HANH_DONG<|#|>Hành động ứng phó kỹ thuật.
entity<|#|>Chằng néo tàu bay<|#|>HANH_DONG<|#|>Hành động cố định tàu bay.
entity<|#|>Hoạt động trên cao<|#|>HANH_DONG<|#|>Các công việc thực hiện ở độ cao nguy hiểm.
entity<|#|>Tra nạp nhiên liệu<|#|>HANH_DONG<|#|>Hoạt động cung cấp nhiên liệu.
relation<|#|>QT18/SGN<|#|>QUY_DINH_TAI<|#|>Tân Sơn Nhất<|#|>áp dụng<|#|>Quy trình áp dụng tại sân bay TSN.
relation<|#|>Gió mạnh 40-59 kts<|#|>KICH_HOAT<|#|>Chèn bánh tàu bay<|#|>yêu cầu<|#|>Gió mức này yêu cầu phải chèn bánh.
relation<|#|>Gió mạnh 40-59 kts<|#|>KICH_HOAT<|#|>Chằng néo tàu bay<|#|>yêu cầu<|#|>Gió mức này yêu cầu phải chằng néo.
relation<|#|>Gió mạnh 40-59 kts<|#|>NGHIEM_CAM<|#|>Hoạt động trên cao<|#|>dừng<|#|>Khi gió đạt mức này, phải dừng hoạt động trên cao.
relation<|#|>Gió mạnh 40-59 kts<|#|>NGHIEM_CAM<|#|>Tra nạp nhiên liệu<|#|>dừng<|#|>Khi gió đạt mức này, phải dừng tra nạp.
<|COMPLETE|>