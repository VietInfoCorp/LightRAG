<Input Text>
Đối với thời tiết nguy hiểm tại Tân Sơn Nhất (QT18/SGN): Khi gió mạnh từ 40 đến 59 kts, các đơn vị phải thực hiện: Chèn bánh tàu bay, Cài phanh, chằng néo tàu bay, Dừng các hoạt động trên cao và Dừng tra nạp nhiên liệu.

<Output>
entity<|#|>QT18/SGN<|#|>TAI_LIEU<|#|>Quy trình cảnh báo thời tiết nguy hiểm tại Tân Sơn Nhất.
entity<|#|>Tân Sơn Nhất<|#|>DIA_DIEM<|#|>Sân bay áp dụng quy trình.
entity<|#|>Gió mạnh từ 40 đến 59 kts<|#|>DIEU_KIEN<|#|>Mức độ thời tiết nguy hiểm cụ thể (Mức 2).
entity<|#|>Chèn bánh tàu bay<|#|>HANH_DONG<|#|>Hành động ứng phó bắt buộc với tàu bay.
entity<|#|>Cài phanh, chằng néo tàu bay<|#|>HANH_DONG<|#|>Hành động ứng phó bắt buộc với tàu bay.
entity<|#|>Dừng các hoạt động trên cao<|#|>HANH_DONG<|#|>Hành động an toàn lao động.
entity<|#|>Dừng tra nạp nhiên liệu<|#|>HANH_DONG<|#|>Hành động an toàn phòng chống cháy nổ.
relation<|#|>QT18/SGN<|#|>QUY_DINH_TAI<|#|>Tân Sơn Nhất<|#|>áp dụng<|#|>Quy trình QT18/SGN áp dụng tại sân bay Tân Sơn Nhất.
relation<|#|>Gió mạnh từ 40 đến 59 kts<|#|>KICH_HOAT<|#|>Chèn bánh tàu bay<|#|>yêu cầu<|#|>Gió mức này yêu cầu phải chèn bánh tàu bay.
relation<|#|>Gió mạnh từ 40 đến 59 kts<|#|>KICH_HOAT<|#|>Cài phanh, chằng néo tàu bay<|#|>yêu cầu<|#|>Gió mức này yêu cầu phải chằng néo tàu bay.
relation<|#|>Gió mạnh từ 40 đến 59 kts<|#|>KICH_HOAT<|#|>Dừng tra nạp nhiên liệu<|#|>yêu cầu<|#|>Gió mức này yêu cầu dừng tra nạp nhiên liệu.
<|COMPLETE|>