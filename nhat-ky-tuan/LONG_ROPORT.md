# BÁO CÁO TIẾN ĐỘ GÁN NHÃN DỮ LIỆU

## 1. Thông tin công việc

- **Job ID:** 1462
- **Phạm vi ảnh đã thực hiện:** Từ ảnh 75 đến ảnh 99
- **Số lượng nhãn đã gán:** 271 nhãn

## 2. Nội dung thực hiện

Trong phạm vi trên, tôi đã ưu tiên gán nhãn cho các vật thể dễ nhận biết trước, bao gồm: `car`, `area/drivable`, `lane/single light` và các nhãn liên quan.

Hiện tại, việc gán nhãn trên từng ảnh vẫn chưa hoàn tất. Một số vật thể bị mờ, nằm ở khoảng cách xa hoặc không thể xác định chính xác loại đối tượng nên chưa được kết luận.

## 3. Các trường hợp cần kiểm tra

| Ảnh | Label ID | Vấn đề cần xác minh |
|---:|---:|---|
| 75 | 271 | Vật thể bị mờ, chưa xác định được có phải là `car` hay không. |
| 76 | 272 | Vật thể bị mờ, không thể nhận diện rõ. |
| 79 | 273 | Vật thể ở xa và bị mờ, chưa xác định được có phải là `car` hay không. |
| 80 | 80 | Vật thể không rõ, cần kiểm tra lại. |
| 80 | 75 | Vật thể không rõ, cần kiểm tra lại. |
| 80 | 60 | Vật thể không rõ, cần kiểm tra lại. |
| 83 | 111 | Chưa phân biệt được vật thể là `car` hay `truck`. |
| 92 | 214 | Chưa phân biệt được vật thể là `car` hay `truck`. |

## 4. Trạng thái và đề xuất

Công việc đang trong quá trình thực hiện. Cần rà soát lại các trường hợp nêu trên và tiếp tục bổ sung những nhãn còn thiếu để hoàn tất toàn bộ ảnh trong phạm vi từ 75 đến 99.
