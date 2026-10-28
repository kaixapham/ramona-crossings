# Ramona · Evening Crossings

Bản build tĩnh của một website demo cho du thuyền catamaran CB29 Lumen Yatch của Ramona (hư cấu). Trang mở đầu bằng cảnh 3D Three.js: thuyền chạy trên biển, camera đổi góc theo nhịp cuộn (ngang mạn, nhìn thẳng từ trên xuống có một đợt sóng chạy qua, rồi cao ngang mũi mạn trái). Giữa là phần editorial trên nền giấy (typography theo tinh thần aupalevodka.com), lộ trình 3D là hải đồ trên bàn với chiếc thuyền nhỏ chạy qua 5 chặng, rồi quay lại cảnh biển qua ô cửa tròn. Cuộn mượt bằng Lenis. Phím H mở bảng chỉnh cảnh, phím F thả camera tự do.

Xem tại: https://kaixapham.github.io/ramona-crossings/

## Ghi công

- Thuyền: catamaran dựng riêng cho trang này. Ghế nằm, bàn, sofa, ghế quầy, cọc buộc dây, radome, gỗ teak và vải bọc navy lấy từ ["Frickie's yacht"](https://sketchfab.com/3d-models/frickies-yacht-1afd320662384bc0910f1778e9cb5eae) của dannzjs, [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/). Bảng chỉnh cảnh cũng cho đổi sang nguyên chiếc Frickie's yacht.
- Cá voi: ["Humpback Whale"](https://sketchfab.com/3d-models/humpback-whale-7984cdf86d6946ca8e13f94a5ad5b33c) của Bohdan Lvov, [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/).
- Đảo xa: địa hình ["Madeira, Portugal"](https://sketchfab.com/3d-models/madeira-portugal-37cce2f26fe14863b59014fa6f62b289) của CMPLab, [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/). Ảnh vệ tinh của nó cũng phủ lên dải bờ xanh phía xa.
- Hải âu: ["Seagulls animated"](https://sketchfab.com/3d-models/seagulls-animated-73aed843190a4dfda55f2b65cc0f8d63) của vicente betoret ferrero, [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/).
- Thành phố sau bờ xa: ["City"](https://sketchfab.com/3d-models/city-1f50f0d6ec5a493d8e91d7db1106b324) của Mateusz Woliński, [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/). Đã gộp mesh và nén Draco cho web.
- Mặt biển tham khảo ["Sea part"](https://sketchfab.com/3d-models/sea-part-e90b3547e64a4bbd825fd126760f1770) của Ayberk Tosunoglu, [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/); mặt nước, bầu trời và mây là shader chạy trên GPU.
- Ảnh dịch vụ, trải nghiệm và khách trên tàu tạo bằng Magnific (Google Nano Banana Pro). Hai ảnh nhỏ trong câu mở đầu được render trực tiếp từ cảnh 3D lúc tải trang.
- Chuyến đi, lịch chạy và giá vé đều là hư cấu.

Model được đóng gói dạng base64 (`models/*.glb.txt`).
