PHẦN A — ĐỌC HIỂU
    Câu A1 — Grid System
    Kích thước |    <768px     | 768px - 991px | ≥ 992px
    số cột     |    1 cột      |     2 cột     |  4 cột
    box layout | Xếp chồng dọc |   2x2 grid    | 1 hàng ngang
    col-md-6 nghĩa là trên các thiết bị có độ rộng màn hình >= 768px, phần tử này sẽ chiếm 
    6/12 cột
    không cần viết col-sm-12 vì trong Bootstrap, các class col-* mặc định có chiều rộng 100% (col-12) nếu không có class nào khác chỉ định cho breakpoint nhỏ hơn, md là breakpoint tiếp theo sau sm và mặc định, nên col-12 là giá trị mặc định cho các màn hình dưới 768px

    Câu A2 — Utilities & Components
    1. Giải thích class d-none d-md-block:
        d-none: Ẩn phần tử trên tất cả các kích thước màn hình (display: none)
        d-md-block: Hiển thị phần tử dưới dạng block từ màn hình ≥ 768px
        =>Phần tử sẽ bị ẩn trên màn hình nhỏ (Mobile < 768px) và hiển thị từ màn hình Medium trở lên
    2. 5 spacing utilities (margin/padding)
    mt-3: margin-top với mức độ 3 (mặc định là 1rem)
    px-4: padding-left với mức độ 4 (mặc định là 1.5rem)
    mb-auto: margin-bottom: auto!important (thường dùng trong flexbox để đẩy phần tử)
    pt-5: padding-top với mức độ 5 (3rem)
    ms-2`: margin-start (margin-left trong LTR) với mức độ 2 (0.5rem)
    3. Sự khác nhau giữa .container, .container-fluid, .container-md
        .container: Có chiều rộng cố định (fixed width) thay đổi theo từng breakpoint\
        .container-fluid: Luôn chiếm 100% chiều rộng màn hình ở mọi breakpoint
        .container-md: Chiếm 100% chiều rộng cho đến khi đạt breakpoint `md` (768px)

PHẦN B — THỰC HÀNH
