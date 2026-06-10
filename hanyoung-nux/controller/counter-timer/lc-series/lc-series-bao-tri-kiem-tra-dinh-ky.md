---
title: "Bảo Trì LC Series Hanyoung Nux | Kiểm Tra Định Kỳ và Xử Lý Sự Cố"
slug: lc-series-bao-tri-kiem-tra-dinh-ky
date: 2026-06-10
updated: 2026-06-10
category: huong-dan-ky-thuat
tags: [HanyoungNux, LCSeries, BaoTri, KiemTra, SuCo, BenVung]
description: "Hướng dẫn bảo trì định kỳ và xử lý sự cố LC Series Hanyoung Nux. Kiểm tra đầu nối, vệ sinh màn hình, xử lý lỗi đếm sai, lỗi mất nguồn."
author: Hanyoung Nux Việt Nam
lang: vi
permalink: /hanyoung-nux/controller/counter-timer/lc-series/lc-series-bao-tri-kiem-tra-dinh-ky/
product_url: https://www.hanyoungnux.com/product/product_view.php?num=236&lcode=01&mcode=0104&pcode=1805100001&scode=0104002
---

# Bảo Trì LC Series Hanyoung Nux | Kiểm Tra Định Kỳ

LC Series được thiết kế để hoạt động liên tục nhiều năm với ít bảo trì. Tuy nhiên, kiểm tra định kỳ giúp phát hiện sớm vấn đề tiềm ẩn.

---

## Checklist bảo trì 6 tháng/lần

- [ ] Kiểm tra đầu nối dây — không lỏng, không oxy hóa
- [ ] Lau sạch mặt LCD bằng vải khô mềm
- [ ] Kiểm tra gioăng cao su mặt trước — không nứt, không biến dạng (quan trọng để duy trì IP66)
- [ ] Đọc và lưu lại các thông số cài đặt hiện tại (Pre-scale, Preset, địa chỉ Modbus)
- [ ] Kiểm tra relay ngõ ra — hoạt động đúng không (relay cơ học: min 50,000 lần)

---

## Xử lý sự cố thường gặp

| Triệu chứng | Nguyên nhân có thể | Cách xử lý |
|---|---|---|
| Đếm nhảy số, không ổn định | Nhiễu tín hiệu, cáp không shield | Dùng cáp shield, nối đất tủ điện |
| Không đếm dù có tín hiệu | Sai loại ngõ vào NPN/PNP | Kiểm tra và đổi mode NPN/PNP |
| Màn hình tối nhưng máy vẫn chạy | Backlight giảm sau nhiều năm | Thay thiết bị mới nếu quá 5–7 năm |
| Mất cài đặt sau mất điện | Bộ nhớ non-volatile bình thường 10 năm | Kiểm tra nếu thiết bị quá 10 năm |
| RS485 không kết nối | Địa chỉ Modbus xung đột hoặc tốc độ baud không khớp | Kiểm tra địa chỉ và baud rate |

---

## Tuổi thọ relay ngõ ra

- **Relay cơ học:** Tối thiểu 10,000,000 lần đóng/mở
- **Relay điện:** Tối thiểu 50,000 lần ở tải định mức
- Nếu ngõ ra kích/nhả liên tục với tần suất cao → dùng ngõ ra contactless (transistor) thay relay

---

📞 **Hotline:** 0909193674 | 🌐 [www.hanyoungnux.com]($PURL) | 📧 hoangphuc@hynux.com
